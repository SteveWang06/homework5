<template>
  <div class="messageSender">
    <div class="messageSender__top">
      <img class="user__avatar"
           src="https://image.freepik.com/free-vector/businessman-avatar-cartoon-character-profile_18591-50584.jpg"
           alt="" />
      <form>
        <input class="messageSender__input" placeholder="What's on your mind?" type="text" />
      </form>
    </div>

    <div class="messageSender__bottom">
      <div class="messageSender__option">
        <span style="color: red" class="material-icons"> videocam </span>
        <h3>Live</h3>
      </div>

      <div class="messageSender__option">
        <span style="color: green" class="material-icons"> photo_library </span>
        <h3>Photo</h3>
      </div>

      <div class="messageSender__option">
        <span style="color: orange" class="material-icons"> insert_emoticon </span>
        <h3>Feeling</h3>
      </div>
    </div>
  </div>

</template>

<script>
export default {
  name: "messageSender"
}
</script>

<style scoped>

messageSender {
  display: flex;
  margin-top: 30px;
  flex-direction: column;
  background-color: white;
  border-radius: 15px;
  box-shadow: 0px 5px 7px -7px rgba(0, 0, 0, 0.75);
  width: 100%;
}

messageSender__top {
  display: flex;
  align-items: center;
  border-bottom: 1px solid #eff2f5;
  padding: 15px;
}

messageSender__top form {
  flex: 1;
  display: flex;
}

messageSender__top form input {
  flex: 1;
  outline-width: 0;
  border: none;
  padding: 15px 20px;
  margin: 0 10px;
  border-radius: 999px;
  background-color: #eff2f5;
}

messageSender__bottom {
  display: flex;
  justify-content: space-evenly;
}

messageSender__option {
  padding: 8px;
  display: flex;
  align-items: center;
  color: gray;
  margin: 5px;
}

messageSender__option h3 {
  font-size: medium;
  margin-left: 10px;
}

messageSender__option:hover {
  cursor: pointer;
  background-color: #eff2f5;
  border-radius: 20px;
}

</style>