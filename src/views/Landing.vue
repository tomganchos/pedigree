<template>
  <div class="container">
    <div class="header">
      <div class="header-icon">
        <icon-tree/>
      </div>
      <div class="header-label">
        <div class="header-label__text">
          <div>Твоя</div><div>Родословная</div>
        </div>
      </div>
      <div class="header-lang">
        Lang
      </div>
    </div>
  </div>
</template>

<script>
import IconTree from "@/views/IconTree";
export default {
  name: 'Landing',
  components: {IconTree},
  data () {
    return {
      test: 'test',
    }
  }
}
</script>

<style scoped>
  .container {
    max-width: 1200px;
  }
  .header {
    display: flex;
    padding: 10px;
  }
  .header .header-label {
    display: flex;
    flex-grow: 1;
    color: #1b5e20;
    padding-left: 10px;
    font-size: 170%;
    text-align: left;
  }
  .header .header-label__text {
    display: flex;
    flex-direction: column;
    height: 64px;
    align-items: flex-start;
  }
</style>
