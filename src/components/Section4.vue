<template>
  <div class="section4">
    <div class="container">
      <div class="grid">
        <div v-for="n in 3" :key="n" class="columns">
          <div class="subtitle"></div>
          <div class="subpara"></div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "Section4",
};
</script>
<style lang="scss">
.section4 {
    background-color: palevioletred;

    .grid{
      height: 300px;
      margin: 0 -10px;
      display: flex;
      align-items: center;
      flex: 1 1 33.33%;
    }

    .columns {
        width: 100%;
        background-color: white;
        display: flex;
        flex-direction: column;
        justify-content: flex-end;
        align-items: center;
        margin: 0 10px;

        .subtitle {
            height: 30px;
            width: 120px;
            background-color: grey;
            margin: 5px;
        }
        .subpara {
            height: 90px;
            width: 120px;
            background-color: grey;
            margin: 5px;
        }
    }
}
</style>
