<template>
  <div>
    <v-layout class="justify-space-between align-center">
      <v-flex md9>
        <v-layout class="align-center justify-start">
          <div class="text-center menu">
            <v-menu open-on-hover bottom offset-y>
              <template v-slot:activator="{ on, attrs }">
                <v-btn
                  color="#f39021"
                  class="menu-button pa-2"
                  dark
                  v-bind="attrs"
                  v-on="on"
                >
                  <v-icon class="mr-2">{{ icons.mdiMenu }}</v-icon>
                  <span>Danh Mục</span>
                </v-btn>
              </template>

              <v-list class="menu-dropdown">
                <v-list-item
                  v-for="(item, index) in items"
                  :key="index"
                  class="menu-dropdown-text"
                >
                  <v-list-item-title class="white--text">
                    {{ item.title }}
                  </v-list-item-title>
                </v-list-item>
              </v-list>
            </v-menu>
          </div>

          <div class="menu-select">Thông tin sản phẩm vắc xin</div>
        </v-layout>
      </v-flex>
      <v-flex md3>
        <v-card class="mx-auto menu-input" text color="grey-lighten-3" width="600">
          <v-card-text>
            <v-text-field
              :loading="loading"
              label="Tìm kiếm tên vắc xin"
              single-line
              hide-details
              class="menu-input-text-field"
            
            >
              <template v-slot:prepend>
                <v-icon v-if="icons.mdiMagnify">{{ icons.mdiMagnify }}</v-icon>
              </template>
            </v-text-field>
          </v-card-text>
        </v-card>
      </v-flex>
    </v-layout>
  </div>
</template>

<script>
import { mdiMenu, mdiMagnify } from "@mdi/js";
export default {
  data: () => ({
    loaded: false,
    loading: false,
    icons: {
      mdiMenu,
      mdiMagnify,
    },
    items: [
      { title: "Mua đặt giữ vắc xin theo yêu cầu" },
      { title: "Vắc xin cho trẻ em" },
      { title: "Vắc xin cho trẻ tièn học đường" },
      { title: "Vắc xin cho tuổi vị thành niên và thanh niên" },
      { title: "Vắc xin cho người trưởng thành" },
      { title: "Vắc xin cho phụ nữ chuẩn bị mang thai" },
    ],
  }),
};
</script>

<style  scoped>
.menu {
  color: #f2f3f7;
  padding: 24px 8px;
  margin-right: 32px;
}

.menu-button {
  color: white;
  font-size: 16px;
  border-radius: 10px;
  padding: 6px 12px;
}
.menu-dropdown {
  background: #f39021;
}
.menu-dropdown-text {
  font-size: 14px;
  cursor: pointer;
  background: #f39021;
  transition: all 300ms;
}

.menu-dropdown-text:hover {
  background: #c2731a;
}

.menu-select {
  color: #2a388f;
  font-weight: bold;
  font-size: 24px;
}

.menu-input {
  border-radius: 50px;
}

.menu-input-text-field {
  padding: 0;
  margin: 0;
  box-shadow: none;
}
s
.v-card__subtitle, .v-card__text, .v-card__title {
    padding: 12px;
}
</style>