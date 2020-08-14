<template>
  <div>
    <div class="section6">
      <div v-for="n in 2" :key="n">
        <div class="side">
          <div class="title"></div>
          <div class="paragraphe"></div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "Section6",
};
</script>
<style lang="scss">
.section6 {
  display: flex;
  justify-content: space-around;
  align-items: center;
  height: 300px;
  background-color: orange;
  .side {
    .title {
      height: 30px;
      width: 120px;
      background-color: white;
      margin: 0 auto;
    }
    .paragraphe {
      height: 90px;
      width: 220px;
      background-color: white;
      margin: 5px;
    }
  }
}
</style>
