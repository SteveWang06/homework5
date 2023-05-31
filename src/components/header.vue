<template>
  <div class="header">
    <div class="header__left">
      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/05/Facebook_Logo_%282019%29.png/640px-Facebook_Logo_%282019%29.png" alt="" />
      <div class="header__input">
        <span class="material-icons"> search </span>
        <input type="text" placeholder="Search Facebook" />
      </div>
    </div>

    <div class="header__middle">
      <div class="header__option active">
        <span class="material-icons"> home </span>
      </div>
      <div class="header__option">
        <span class="material-icons"> flag </span>
      </div>
      <div class="header__option">
        <span class="material-icons"> subscriptions </span>
      </div>
      <div class="header__option">
        <span class="material-icons"> storefront </span>
      </div>
      <div class="header__option">
        <span class="material-icons"> supervised_user_circle </span>
      </div>
    </div>

    <div class="header__right">
      <div class="header__info">
        <img class="user__avatar"
             src="https://img.freepik.com/free-vector/businessman-character-avatar-isolated_24877-60111.jpg?w=2000"
             alt="" />
        <h4>FengChia Zoo</h4>
      </div>
      <span class="material-icons"> add </span>
      <span class="material-icons"> forum </span>
      <span class="material-icons"> notifications_active </span>
      <span class="material-icons"> expand_more </span>
    </div>
  </div>

</template>

<script>
export default {

}
</script>

<style scoped>
header__left img {
  height: 40px;
}

header {
  padding: 15px 20px;
  display: flex;
  justify-content: space-between;
  position: sticky;
  background-color: white;
  z-index: 100;
  top: 0;
  box-shadow: 0 5px 8px -9px rgba(0, 0, 0, 0.75);
}

header__left {
  display: flex;
  align-items: center;
  justify-content: space-evenly;
}

header__input {
  display: flex;
  align-items: center;
  background-color: #eff2f5;
  padding: 10px;
  margin-left: 10px;
  border-radius: 999px;
}

header__middle {
  display: flex;
  flex: 1;
  justify-content: center;
}

header__option .material-icons {
  font-size: xx-large;
  color: gray;
}

header__option:hover .material-icons {
  color: #2e81f4;
}

header__option {
  display: flex;
  align-items: center;
  padding: 0 30px;
  cursor: pointer;
}

header__option.active .material-icons {
  color: #2e81f4;
}

header__option.active {
  border-bottom: 4px solid #2e81f4;
}

header__option:hover {
  background-color: #eff2f5;
  border-radius: 10px;
  align-items: center;
  padding: 0 30px;
  border-bottom: none;
}

header__info {
  display: flex;
  align-items: center;
}

header__info h4 {
  margin-left: 10px;
}

header__right {
  display: flex;
  align-items: center;
}

header__right .material-icons {
  color: gray;
  margin: 0 10px;
}

header__right .material-icons:hover {
  cursor: pointer;
}
</style>