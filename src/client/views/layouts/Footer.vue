<template>
  <footer>
    <br><br><br>
    <div>
      &copy; Ink CMS
    </div>
  </footer>
</template>

<script>
export default {
  name: "Footer",
  components: {}
}
</script>

<style scoped lang="stylus">
@media $s-up {
  div {
    height: 100px;
    padding: 40px 0;
    text-align: center;
    background-color: $light-gray;
  }
}
</style>
