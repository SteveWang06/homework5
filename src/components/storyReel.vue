<template>
  <div class="storyReel">
    <!-- story starts -->
    <div style="
          background-image: url('https://www.worldanimalprotection.org.br/sites/default/files/styles/600x400/public/media/GettyImages-56158469.jpg?itok=kkUkLaZQ');
        " class="story">
      <img class="user__avatar story__avatar"
           src="https://www.shareicon.net/data/2016/05/24/770139_man_512x512.png" alt="" />
      <h4>FengChia Zoo</h4>
    </div>
    <!-- story ends -->

    <!-- story starts -->
    <div style="
          background-image: url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ4_EEyi9zwwRdJdpfVPBzUWp_UTMdSBcdX4A&usqp=CAU');
        " class="story">
      <img class="user__avatar story__avatar"
           src="https://image.freepik.com/free-vector/businessman-avatar-cartoon-character-profile_18591-50584.jpg"
           alt="" />
      <h4>FengChia Zoo</h4>
    </div>
    <!-- story ends -->

    <!-- story starts -->
    <div style="
          background-image: url('https://images.unsplash.com/photo-1598755257130-c2aaca1f061c?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxzZWFyY2h8M3x8d2lsZCUyMGFuaW1hbHxlbnwwfHwwfHw%3D&w=1000&q=80');
        " class="story">
      <img class="user__avatar story__avatar"
           src="https://image.freepik.com/free-vector/businessman-avatar-cartoon-character-profile_18591-50584.jpg"
           alt="" />
      <h4>FengChia Zoo</h4>
    </div>
    <!-- story ends -->

    <!-- story starts -->
    <div style="
          background-image: url('https://images.immediate.co.uk/production/volatile/sites/23/2023/01/Indias-national-animal-3438b5d.jpg?quality=90&resize=980,654');
        " class="story">
      <img class="user__avatar story__avatar"
           src="https://image.freepik.com/free-vector/businessman-avatar-cartoon-character-profile_18591-50584.jpg"
           alt="" />
      <h4>FengChia Zoo</h4>
    </div>
    <!-- story ends -->

    <!-- story starts -->
    <div style="
          background-image: url('https://www.huntsvilleal.gov/wp-content/uploads/2023/02/Valentines-at-HAS-1024x677.png');
        " class="story">
      <img class="user__avatar story__avatar"
           src="https://image.freepik.com/free-vector/businessman-avatar-cartoon-character-profile_18591-50584.jpg"
           alt="" />
      <h4>FengChia Zoo</h4>
    </div>
    <!-- story ends -->



    <!-- story starts -->
    <div style="
          background-image: url('https://www.niabizoo.com/wp-content/uploads/2018/05/ms-animals-habitats-mammals.jpg');
        " class="story">
      <img class="user__avatar story__avatar"
           src="https://image.freepik.com/free-vector/businessman-avatar-cartoon-character-profile_18591-50584.jpg"
           alt="" />
      <h4>FengChia Zoo</h4>
    </div>
    <!-- story ends -->

    <!-- story starts -->
    <div style="
          background-image: url('https://storage.googleapis.com/pcc-wagtail-media/images/IMG_9426.2e16d0ba.fill-768x402.jpg');
        " class="story">
      <img class="user__avatar story__avatar"
           src="https://image.freepik.com/free-vector/businessman-avatar-cartoon-character-profile_18591-50584.jpg"
           alt="" />
      <h4>FengChia Zoo</h4>
    </div>
    <!-- story ends -->

    <!-- story starts -->
    <div style="
          background-image: url('https://animalhaven.org/wp-content/uploads/2023/03/Gala2022_whats-happening-600x600.jpeg');
        " class="story">
      <img class="user__avatar story__avatar"
           src="https://image.freepik.com/free-vector/businessman-avatar-cartoon-character-profile_18591-50584.jpg"
           alt="" />
      <h4>FengChia Zoo</h4>
    </div>
    <!-- story ends -->
  </div>

</template>

<script>
export default {
  name: "storyReel"
}
</script>

<style scoped>

story {
  position: relative;
  background-repeat: no-repeat;
  background-size: cover;
  width: 200px;
  height: 200px;
  box-shadow: 0px 5px 17px -7px rgba(0, 0, 0, 0.75);
  border-radius: 10px;
  margin-right: 10px;
  transition: transform 100ms ease-in;
  cursor: pointer;
}

story:hover {
  transform: scale(1.07);
}

story__avatar {
  margin: 10px;
  color: blue;
}

story h4 {
  position: absolute;
  bottom: 20px;
  left: 20px;
  color: white;
}

storyReel {
  padding: 10px 0;
  display: flex;


}

</style>