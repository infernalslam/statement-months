<template>
  <div>
    <div class="box-info" :style="color">
      <p class="has-text-centered has-text-light"> บัตรเครดิต </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Card',
  props: {
    color: String
  }
}
</script>

<style scoped>
.box-info:hover {
  -webkit-box-shadow: 0 10px 20px -10px rgba(0,0,0,.6);
  box-shadow: 0 10px 20px -10px rgba(0,0,0,.6);
  -webkit-transform: translateY(-4px);
  transform: translateY(-4px);
}
.box-info {
  text-shadow: 1px 2px 4px rgba(0,0,0,.3);
  border-radius: 5px;
  border: 0;
  cursor: pointer;
  outline: none;
  background: #eee;
  color: rgba(0,0,0,.7);
  -webkit-transition: all .2s ease;
  transition: all .2s ease;
  overflow: hidden;
  position: relative;
  margin: 5px;
  width: auto;
  padding: 80px;
}
</style>
