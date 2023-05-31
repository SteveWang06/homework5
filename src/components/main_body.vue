<script>
import Sidebar from "./sidebar.vue";
import Feed from "./feed.vue";

import {defineComponent} from "vue";

export default defineComponent({
  components: {Feed, Sidebar}
})


</script>



<template>

  <div class="main__body">
    <Sidebar/>
    <Feed/>

  </div>

</template>

<script>
export default {
  name: "main_body"
}
</script>

<style scoped>
main__body {
  display: flex;
}

</style>