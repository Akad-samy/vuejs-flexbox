<template>
  <div>
    <div class="section4">
      <div v-for="n in 3" :key="n">
          <div class="columns" >
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
    height: 300px;
    background-color: palevioletred;
    display: flex;
    align-items: center;
    justify-content: space-around;
    .columns {
        height: 200px;
        width: 150px;
        background-color: white;
        display: flex;
        flex-direction: column;
        justify-content: flex-end;
        align-items: center;
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
