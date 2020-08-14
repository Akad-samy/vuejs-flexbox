<template>
  <div>
    <div class="section5">
      <div class="title"></div>
      <div class="grid">
        <div class="paragraphe"></div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "Section5",
};
</script>
<style lang="scss">
.section5 {
  height: 300px;
  width: 100%;
  position: relative;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;

  .title {
    height: 30px;
    width: 120px;
    background-color: gray;
  }

  .grid {
    height: 80%;
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: space-around;
    .paragraphe {
      height: 70%;
      width: 40%;
      background-color: gray;
    }
  }

}
</style>
