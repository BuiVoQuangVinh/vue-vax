<template>
  <div class="home">
    <HeaderVue />
    <div class="home-container">
      <MenuVue />
      <FilterVue />
      <v-layout>
        <v-flex md8>
          <ListProduct
            :seletedList="seletedList"
            :handleSeleted="handleSeleted"
            :formatPrice="formatPrice"
          />
        </v-flex>
        <v-flex md4>
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

      console.log(this.seletedList);
    },

    formatPrice(price) {
      return price.toString().replace(/\B(?=(\d{3})+(?!\d))/g, ",") + " VND";
    },
  },
};
</script>

<style>
.home-container {
  background: #f2f3f7 !important;
  padding: 20px 40px;
}
</style>