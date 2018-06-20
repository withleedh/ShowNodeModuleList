<script src="index.js"></script>
<template>
  <div class="modules">
    You are using Vue {{version}}
  </div>
</template>
 
<script type="text/javascript">
  import Vue from 'vue'
export default {
  computed: {
    version() {
        return Vue.version
    }
  }
}
</script>
 
<style>
.modules {
  font-weight: bold;
  font-family: tahoma;
}
</style>