<script>
import StoryReel from "./storyReel.vue";
import MessageSender from "./messageSender.vue";
import Post from "./post.vue";
import {defineComponent} from "vue";

export default defineComponent({
  components: {Post, MessageSender, StoryReel}
})

</script>



<template>
  <StoryReel/>
  <MessageSender/>
  <Post/>

</template>

<script>
export default {
  name: "feed"
}
</script>

<style scoped>

</style>