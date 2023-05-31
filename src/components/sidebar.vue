<template>
  <div class="sidebar">
    <div class="sidebarRow">
      <img class="user__avatar"
           src="https://img.freepik.com/free-vector/businessman-character-avatar-isolated_24877-60111.jpg?w=2000"
           alt="" />
      <h4>FengChia Zoo</h4>
    </div>

    <div class="sidebarRow">
      <span class="material-icons"> local_hospital </span>
      <h4>Covid - 19 Information Center</h4>
    </div>

    <div class="sidebarRow">
      <span class="material-icons"> emoji_flags </span>
      <h4>Pages</h4>
    </div>

    <div class="sidebarRow">
      <span class="material-icons"> people </span>
      <h4>People</h4>
    </div>

    <div class="sidebarRow">
      <span class="material-icons"> chat </span>
      <h4>Messenger</h4>
    </div>

    <div class="sidebarRow">
      <span class="material-icons"> storefront </span>
      <h4>Marketplace</h4>
    </div>

    <div class="sidebarRow">
      <span class="material-icons"> video_library </span>
      <h4>Videos</h4>
    </div>

    <div class="sidebarRow">
      <span class="material-icons"> expand_more </span>
      <h4>More</h4>
    </div>
  </div>

</template>

<script>
export default {
  name: "sidebar"
}
</script>

<style scoped>
sidebarRow {
  display: flex;
  align-items: center;
  padding: 10px;
  cursor: pointer;
}

sidebarRow:hover {
  background-color: lightgray;
  border-radius: 10px;
}

sidebarRow h4 {
  margin-left: 20px;
  font-weight: 600;
}

sidebarRow .material-icons {
  font-size: xx-large;
  color: #2e81f4;
}
</style>