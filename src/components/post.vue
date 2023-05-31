<template>
  <div class="post">
    <div class="post__top">
      <img class="user__avatar post__avatar"
           src="https://image.freepik.com/free-vector/businessman-avatar-cartoon-character-profile_18591-50584.jpg"
           alt="" />
      <div class="post__topInfo">
        <h3>FengChia Zoo</h3>
        <p>25 April at 20:30</p>
      </div>
    </div>

    <div class="post__bottom">
      Caption
    </div>

    <div class="post__image">
      <img src="https://www.mlar.org/media/1638/yolanda.jpg" alt="" />
    </div>

    <div class="post__options">
      <div class="post__option">
        <span class="material-icons">thumb_up</span>
        <p>Like</p>
      </div>

      <div class="post__option">
        <span class="material-icons"> chat_bubble_outline </span>
        <p>Comment</p>
      </div>

      <div class="post__option">
        <span class="material-icons"> near_me </span>
        <p>Share</p>
      </div>
    </div>
  </div>

  <div class="post">
    <div class="post__top">
      <img class="user__avatar post__avatar"
           src="https://image.freepik.com/free-vector/businessman-avatar-cartoon-character-profile_18591-50584.jpg"
           alt="" />
      <div class="post__topInfo">
        <h3>FengChia Zoo</h3>
        <p>25 April at 20:30</p>
      </div>
    </div>

    <div class="post__bottom">
      Caption
    </div>

    <div class="post__image">
      <img src="https://images.unsplash.com/photo-1474511320723-9a56873867b5?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxleHBsb3JlLWZlZWR8Mnx8fGVufDB8fHx8&w=1000&q=80"
           alt="" />
    </div>

    <div class="post__options">
      <div class="post__option">
        <span class="material-icons">thumb_up</span>
        <p>Like</p>
      </div>

      <div class="post__option">
        <span class="material-icons"> chat_bubble_outline </span>
        <p>Comment</p>
      </div>

      <div class="post__option">
        <span class="material-icons"> near_me </span>
        <p>Share</p>
      </div>
    </div>
  </div>

  <div class="post">
    <div class="post__top">
      <img class="user__avatar post__avatar"
           src="https://image.freepik.com/free-vector/businessman-avatar-cartoon-character-profile_18591-50584.jpg"
           alt="" />
      <div class="post__topInfo">
        <h3>FengChia Zoo</h3>
        <p>25 April at 20:30</p>
      </div>
    </div>

    <div class="post__bottom">
      Caption
    </div>

    <div class="post__image">
      <img src="https://www.nashvillezoo.org/assets/2147/red-kangaroo---2017---david-duplessis-web-sq.jpg"
           alt="" />
    </div>

    <div class="post__options">
      <div class="post__option">
        <span class="material-icons">thumb_up</span>
        <p>Like</p>
      </div>

      <div class="post__option">
        <span class="material-icons"> chat_bubble_outline </span>
        <p>Comment</p>
      </div>

      <div class="post__option">
        <span class="material-icons"> near_me </span>
        <p>Share</p>
      </div>
    </div>
  </div>

  <div class="post">
    <div class="post__top">
      <img class="user__avatar post__avatar"
           src="https://image.freepik.com/free-vector/businessman-avatar-cartoon-character-profile_18591-50584.jpg"
           alt="" />
      <div class="post__topInfo">
        <h3>FengChia Zoo</h3>
        <p>25 April at 20:30</p>
      </div>
    </div>

    <div class="post__bottom">
      Caption
    </div>

    <div class="post__image">
      <img src="https://kb.rspca.org.au/wp-content/uploads/2018/11/golder-retriever-puppy.jpeg" alt="" />
    </div>

    <div class="post__options">
      <div class="post__option">
        <span class="material-icons">thumb_up</span>
        <p>Like</p>
      </div>

      <div class="post__option">
        <span class="material-icons"> chat_bubble_outline </span>
        <p>Comment</p>
      </div>

      <div class="post__option">
        <span class="material-icons"> near_me </span>
        <p>Share</p>
      </div>
    </div>
  </div>

  <div class="post">
    <div class="post__top">
      <img class="user__avatar post__avatar"
           src="https://image.freepik.com/free-vector/businessman-avatar-cartoon-character-profile_18591-50584.jpg"
           alt="" />
      <div class="post__topInfo">
        <h3>FengChia Zoo</h3>
        <p>25 April at 20:30</p>
      </div>
    </div>

    <div class="post__bottom">
      Caption
    </div>

    <div class="post__image">
      <img src="https://seaworld.com.au/-/media/project/seaworld/images/masonarygallery/73a-masonry-gallery-fairy-penguins-1000x1000-mob.jpg"
           alt="" />
    </div>

    <div class="post__options">
      <div class="post__option">
        <span class="material-icons"> thumb_up </span>
        <p>Like</p>
      </div>

      <div class="post__option">
        <span class="material-icons"> chat_bubble_outline </span>
        <p>Comment</p>
      </div>

      <div class="post__option">
        <span class="material-icons"> near_me </span>
        <p>Share</p>
      </div>
    </div>
  </div>

</template>

<script>
export default {
  name: "post"
}
</script>

<style scoped>

post {
  width: 100%;
  margin-top: 15px;
  border-radius: 15px;
  background-color: white;
  box-shadow: 0px 5px 7px -7px rgba(0, 0, 0, 0.75);
}

post__image img {
  width: 100%;
}

post__top {
  display: flex;
  position: relative;
  align-items: center;
  padding: 15px;
  margin-top: 15px;
  background-color: white;
}

post__avatar {
  margin-right: 10px;
}

post__topInfo h3 {
  font-size: medium;
}

post__topInfo p {
  font-size: small;
  color: gray;
}

post__bottom {

  padding: 15px 25px;
  background-color: white;
}

post__options {
  padding-top: 10px;
  border-top: 1px solid lightgray;
  display: flex;
  justify-content: space-evenly;
  font-size: medium;
  color: gray;
  cursor: pointer;
  padding: 15px;
  background-color: white;
}

post__option {
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 5px;
  flex: 1;
}

post__option p {
  margin-left: 10px;
}

post__option:hover {
  background-color: #eff2f5;
  border-radius: 10px;
}


</style>