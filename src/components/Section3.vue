<template>
  <div class="container">
    <div class="section3">
      <div class="title"></div>
      <div class="grid">
        <div class="paragraphe"></div>
        <div class="paragraphe"></div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "Section3",
};
</script>
<style lang="scss">
.section3 {
  width: 100%;
  position: relative;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  padding: 20px 0;

  .title {
    height: 30px;
    width: 120px;
    background-color: gray;
  }

  .grid {
    width: calc(100% + 20px);
    display: flex;
    margin: 20px -10px 0;

    .paragraphe {
      height: 150px;
      width: 100%;
      margin: 0 10px;
      background-color: gray;
    }
  }
}
</style>
