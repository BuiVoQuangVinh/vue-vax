<template>
  <div class="home">
    <HeaderVue />
    <div class="home-container">
      <MenuVue />
      <FilterVue />
      <v-layout row class="home-content">
        <v-flex md8 sm12>
          <ListProduct
            :seletedList="seletedList"
            :handleSeleted="handleSeleted"
            :formatPrice="formatPrice"
            @handleEmitVaccine='handleEmitVaccine'
          />
        </v-flex>
        <v-flex md4 sm12>
          <VaccineChoose
            :seletedList="seletedList"
            :formatPrice="formatPrice"
          />
        </v-flex>
      </v-layout>
    </div>
    <FooterVue />
  </div>
</template> 

<script>
import HeaderVue from "@/components/HeaderVue.vue";
import ListProduct from "@/components/ListProduct.vue";
import VaccineChoose from "@/components/VaccineChoose.vue";
import MenuVue from "@/components/MenuVue.vue";
import FilterVue from "@/components/FilterVue.vue";

import FooterVue from "@/components/FooterVue.vue";
export default {
  components: {
    HeaderVue,
    ListProduct,
    VaccineChoose,
    MenuVue,
    FilterVue,
    FooterVue,
  },
  data() {
    return {
      seletedList: [],
    };
  },
  
  created() {
    const seletedList = localStorage.getItem('seletedList')
    if( seletedList){
      this.seletedList = JSON.parse(seletedList)
    }
  
  },
  methods: {
    handleSeleted(vaccine) {
      const index = this.seletedList.findIndex(
        (item) => item.name === vaccine.name
      );
      if (index !== -1) {
        this.seletedList.splice(index, 1);
      } else {
        this.seletedList.push(vaccine);
      }

      localStorage.setItem('seletedList',JSON.stringify(this.seletedList))
    },

    formatPrice(price) {
      return price.toString().replace(/\B(?=(\d{3})+(?!\d))/g, ",") + " VND";
    },

    handleEmitVaccine(vaccine){
      this.handleSeleted(vaccine);
    }
  },
};
</script>

<style>
.home-container {
  background: #f2f3f7 !important;
  padding: 20px 40px;
}

@media screen and (max-width: 1264px){
  .home-container{
    padding: 20px;

  }

}

@media screen and (max-width: 960px){
    .home-content{
    display: block;
  }
}
</style>