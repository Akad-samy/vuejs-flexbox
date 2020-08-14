<template>
  <div>
    <div class="section1">
      <div class="square1"></div>
      <div class="square2"></div>
    </div>
  </div>
</template>
<script>
export default {
  name: "Section1",
};
</script>
<style lang="scss">
.section1 {
  height: 200px;
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  .square1 {
    height: 70px;
    width: 70px;
    margin: 10px;
    background-color: gray;
  }
  .square2 {
    height: 30px;
    width: 120px;
    margin: 10px;
    background-color: gray;
  }
}
</style>
