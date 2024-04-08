<script>
export default {
  name: "HeaderPromo",
  data () {
    return {}
  }
}
</script>

<template>
  <div class="my_container_sm debug">
    <div class="row align-items-center">
      <!-- caption -->
      <div class="col-6">
        <p>Starts TOMORROW Our biggest event of the year...</p>
      </div>
      <!-- clock -->
      <div class="col-3">
        <i class="fa-regular fa-clock"></i>
        <span> 00 : 00 : 00 : 00</span>
      </div>
      <div class="col-3">
        <a class="btn btn-primary" href="#" role="button">Get ticket</a>
      </div>
    </div>
    
  </div>
</template>

<style lang="scss" scoped>
*{
  margin: 0 auto;
  text-align: center;
}
.debug{
  border: 1px dashed black;
}

.my_container_sm{
  width: 50%;
  margin: 0 auto;
  padding-right: 15px;
  padding-left: 15px;

  .row{
    height: 40px;
  }
}
</style>