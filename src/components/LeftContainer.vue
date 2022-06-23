<template>
  <div class="left-Container">
    <div class="profile-container bg-dark text-center">
      <img src="./../assets/image/myProfile.png" alt="" class="img" />
    </div>
    <div class="profile-container mt-2">
      <h3 class="text-white text-center fw-bold">Personal Details</h3>
      <hr class="text-white" />
      <div>
        <h5 class="text-white text-center">Email Address</h5>
        <p class="text-white text-center">naybala.153808@gmail.com</p>
      </div>
      <br />
      <div>
        <h5 class="text-white text-center">Phone Number</h5>
        <p class="text-white text-center">09763684400</p>
      </div>
      <br />
      <div>
        <h5 class="text-white text-center">Address</h5>
        <p class="text-white text-center">Ingapu Street,Sanchaung Township,Yangon</p>
      </div>
      <br />
      <div>
        <h5 class="text-white text-center">Date Of Birth</h5>
        <p class="text-white text-center">08.February.1997</p>
      </div>
      <br />
      <div>
        <h5 class="text-white text-center">Place Of Birth</h5>
        <p class="text-white text-center">Zalun,Ayeyarwady</p>
      </div>
      <br />
      <div>
        <h5 class="text-white text-center">Gender</h5>
        <p class="text-white text-center">Male</p>
      </div>
      <br />
      <div>
        <h5 class="text-white text-center">Nationally</h5>
        <p class="text-white text-center">Mynamar,Burma</p>
      </div>
      <br />
      <div>
        <h5 class="text-white text-center">Cilvil Status</h5>
        <p class="text-white text-center">Single</p>
      </div>
    </div>
    <br />
    <hr class="text-white" />
    <div class="profile-container mt-2">
      <h3 class="text-white text-center fw-bold">Skills</h3>
      <hr class="text-white" />
      <h5 class="text-white text-center">Front-End Skills</h5>
      <p class="text-white text-center">Html , Css , BootStrap , JavaScript , Jquery</p>
      <br />
      <h5 class="text-white text-center">Back-End Skills</h5>
      <p class="text-white text-center">Php , Laravel , Api</p>
      <br />
      <h5 class="text-white text-center">Database</h5>
      <p class="text-white text-center">MySQL</p>
      <br />
    </div>
  </div>
</template>

<style scoped>
.left-Container {
  flex: 20%;
  background-color: #569eac;
  border-top-left-radius: 1rem;
  border-bottom-left-radius: 1rem;
}

.profile-container {
  border-top-left-radius: 1rem;
  width: 100%;
}
img {
  width: 250px;
}
h5,
p {
  margin: 0;
  padding: 0;
}
</style>
