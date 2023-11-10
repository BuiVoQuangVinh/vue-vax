<template>
  <div class="button">
    <v-btn class="orange white--text"> Click me </v-btn>
    <!-- depressed: xóa box-shadow  -->
    <v-btn color="orange" dark depressed> Click me </v-btn>
    <!-- text: chuyển màu background: transparent .. hover vẫn ra màu chứ không trong suốt hẳn -->
    <v-btn text color="orange"> Click me</v-btn>
    <v-btn color="orange" dark depressed>
      <v-icon >mdi-email</v-icon>
    </v-btn>

  </div>
</template>

<script>
export default {};
</script>

<style scoped>
/* .button{
  background: rgb(158, 158, 227);
} */
button {
  margin: 8px;
}
</style>