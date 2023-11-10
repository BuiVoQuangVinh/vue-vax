<template>
  <v-container>
    <v-layout row>
      <v-flex
        xl4
        md4
        lg4
        class="vaccine-item"
        v-for="(vaccine, index) in vaccines"
        :key="index"
      >
        <div class="vaccine-item-container">
          <div class="vaccine-info">
            <p class="vaccine-name">{{ vaccine.name }}</p>
            <div class="vaccine-originOfAProduct">
              <p>Nguồn gốc: {{ vaccine.originOfAProduct }}</p>
              <p>{{ vaccine.codeNamePrevention }}</p>
            </div>
            <p class="vaccine-price-text">
              <v-icon color="#2A388F">{{ icons.mdiTag }}</v-icon>
              {{ formatPrice(vaccine.price) }}
            </p>
          </div>
          <div class="vaccine-prevention">Phòng bệnh:</div>
          <div class="vaccine-detail">
            <p class="vaccine-detail-text">{{ vaccine.prevention }}</p>
          </div>

          <div class="vaccine-select">
            <!-- <button
              :class="vaccine.quality > 0 ? 'stocking' : 'runOutOf'"
              @click="handleSeleted(vaccine)"
            >
              {{ vaccine.quality > 0 ? "Chọn" : "Liên hệ" }}
            </button> -->

            <button
              v-if="vaccine.quality > 0"
              class="stocking"
              @click="handleStocking(vaccine)"
            >
              Chọn
            </button>

            <button
              v-if="vaccine.quality === 0"
              class="runOutOf"
              @click="handleRunOutOf(vaccine)"
            >
              Liên hệ
            </button>
          </div>
        </div>
      </v-flex>
    </v-layout>

    <div  v-if="alert" class="vaccine-alert" >
      Phasellus tempus. Fusce ac felis sit amet ligula pharetra condimentum. In
      dui magna, posuere eget, vestibulum et, tempor auctor, justo. Pellentesque
      posuere. Curabitur ligula sapien, tincidunt non, euismod vitae, posuere
      imperdiet, leo. Phasellus nec sem in justo pellentesque facilisis.
      Phasellus magna. Cras risus ipsum, faucibus ut, ullamcorper id, varius ac,
      leo. In hac habitasse platea dictumst. Praesent turpis.
    </div >
  </v-container>
</template>

<script>
import vaccines from "@/api/vaccine";
import { mdiTag } from "@mdi/js";
export default {
  props: {
    seletedList: Array,
    handleSeleted: Function,
    formatPrice: Function,
  },
  data() {
    return {
      icons: {
        mdiTag,
      },
      vaccines,
      alert: false,
    };
  },

  methods: {
    handleStocking(vaccine) {
      console.log("vaccine vẫn còn", vaccine);
    },
    handleRunOutOf(vaccine) {
      console.log("vaccine đã hết", vaccine);
      this.alert = !this.alert;
    },
  },
};
</script>




<style>
.vaccine-item {
  padding: 0 16px 32px 16px;
  line-height: 1.6;
}

.vaccine-item-container {
  background: white;
  border-radius: 14px;
  padding: 12px 16px 4px 16px;
}

.vaccine-info {
  background: rgb(227, 240, 254);
  background-image: url(~@/assets/bg-img.png);
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  padding: 12px 16px;
  border-radius: 14px;
}

.vaccine-name {
  height: 46px;
  font-weight: 500;

  overflow: hidden;
  text-overflow: ellipsis;
}

.vaccine-originOfAProduct {
  margin: 8px 0;
  min-height: 90px;
  max-height: 110px;
  font-size: 14px;

  overflow: hidden;
  text-overflow: ellipsis;
}
.vaccine-price-text {
  color: #2a388f;
  font-size: 20px;
}
.vaccine-prevention,
.vaccine-detail {
  padding: 0 8px;
}

.vaccine-detail-text {
  height: 72px;

  overflow: hidden;
  text-overflow: ellipsis;
}

.stocking {
  background: #2a388f;
}

.runOutOf {
  background-color: rgb(243, 144, 33);
}

.vaccine-select button {
  height: 46px;
  width: 100%;
  margin-top: 18px;
  color: white;
  margin: 18px 0;
  font-size: 18px;
  border-radius: 8px;
}

.vaccine-alert {
  z-index: 99;
  position: fixed;
  top: 20%;
  left: 50%;
  transform: translate(-50%, -50%);
  background: #2a388f;
  color: white;
}
</style>