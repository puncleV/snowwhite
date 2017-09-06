<template>
  <div class="menu">
    <h1 class="menu_header">меню</h1>
    <ul class="menu_list">
      <li>пройти тест</li>
      <li>загрузить тест</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'menu',
  data () {
    return {
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .menu {
    display: flex;
    flex-flow: column;
    align-items: center;
  }

  .menu::first-letter {
    text-transform: uppercase;
  }

  .menu_list {
    display: flex;
    flex-flow: column;
    padding: 0;
    text-align: center;
  }

  .menu_list > li {
    display: block;
    text-transform: uppercase;
  }

  .menu_header {

  }

</style>
