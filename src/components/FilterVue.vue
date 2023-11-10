<template>
  <div class="filter">
    <v-layout class="align-center">
      <p class="filter-text">Hiển thị theo</p>
      <div class="filter-select">
        <v-menu offset-y>
          <template v-slot:activator="{ on, attrs }">
            <v-btn
              v-bind="attrs"
              v-on="on"
              v-model="selected"
              class="filter-select-button"
            >
              {{ selected }}
              <v-icon class="pl-3">{{ icons.mdiChevronDown }}</v-icon>
            </v-btn>
          </template>
          <v-list>
            <v-list-item
              v-for="(item, index) in items"
              :key="index"
              @click="selectItem(item.title)"
            >
              <v-list-item-title>{{ item.title }} </v-list-item-title>
            </v-list-item>
          </v-list>
        </v-menu>
      </div>
    </v-layout>
  </div>
</template>

<script>
import { mdiChevronDown } from "@mdi/js";
export default {
  data: () => ({
    selected: "Tất cả",
    items: [
      { title: "Tất cả" },
      { title: "Vắc xin Gói" },
      { title: "Vắc xin Lẻ" },
    ],
    icons: {
      mdiChevronDown,
    },
  }),
  methods: {
    selectItem(item) {
      this.selected = item;
    },
  },
};
</script>

<style>
.filter {
  padding: 12px 0;
}
.filter-select {
  width: 300px;
}

.filter-text {
  margin-right: 24px;
}

.filter-select-button {
  border: 1px solid #c0c4cc;

  box-shadow: none;
}
</style>