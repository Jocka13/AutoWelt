<template>
  <div id="app">
    <router-view/>
    <AutoWeltBody/>
  </div>
</template>

<style lang="scss">

</style>
<script>
import AutoWeltBody from "@/components/AutoWeltBody";
export default {
  components: {AutoWeltBody}
}
</script>