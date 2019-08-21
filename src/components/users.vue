<template>
  <div class="users">
    <div class="container">
      <div class="users-title">
        <div class="h2">Our cheerful users</div>
        <p class="l">Attention! Sorting users by registration date</p>
      </div>
      <div class="f-j-c">
        <div class="user flex">
          <img src="../assets/imgs/user-noah-2x.jpg" class="img" />
          <div class="user-data">
            <div class="name">Noah</div>
            <div class="position">
              Leading specialist of the Control <br />
              Department
            </div>
            <div class="email">noah.controldepartment@gmail...</div>
            <div class="phone">+38 (050) 678 03 24</div>
          </div>
        </div>
        <div class="user flex">
          <img src="../assets/imgs/user-adolph-2x.png" class="img" />
          <div class="user-data">
            <div class="name">
              Adolph Blaine <br />
              Charles David Earl
            </div>
            <div class="position">
              The contextual advertising <br />
              specialist
            </div>
            <div class="email">adolph.blainecharles-davidearl@...</div>
            <div class="phone">+38 (095) 556 08 45</div>
          </div>
        </div>
        <div class="user flex">
          <img src="../assets/imgs/user-liam-2x.jpg" class="img" />
          <div class="user-data">
            <div class="name">
              Liamgrievescasey <br />
              Smith Wiam
            </div>
            <div class="position">Lead designer</div>
            <div class="email">liamgrievescasey@example.com</div>
            <div class="phone">+38 (050) 273 93 32</div>
          </div>
        </div>

        <div class="user flex">
          <img src="../assets/imgs/user-elizabeth-2x.jpg" class="img" />
          <div class="user-data">
            <div class="name">Elizabeth</div>
            <div class="position">Frontend developer</div>
            <div class="email">elisabet.frontend@gmail.com</div>
            <div class="phone">+38 (095) 924 66 37</div>
          </div>
        </div>
        <div class="user flex">
          <img src="../assets/imgs/user-alexander-2x.jpg" class="img" />
          <div class="user-data">
            <div class="name">Alexander</div>
            <div class="position">Backend developer</div>
            <div class="email">alexander.backend@gmail.com</div>
            <div class="phone">+38 (050) 789 24 09</div>
          </div>
        </div>
        <div class="user flex">
          <img src="../assets/imgs/user-mason-2x.jpg" class="img" />
          <div class="user-data">
            <div class="name">Mason</div>
            <div class="position">QA</div>
            <div class="email">mason.qa@gmail.com</div>
            <div class="phone">+38 (095) 283 27 00</div>
          </div>
        </div>
      </div>
      <div class="f-j-c">
        <button class="btn2">Show More</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "users"
};
</script>
<style lang="scss">
.users-title {
  padding-top: 150px;
  padding-bottom: 25px;
  text-align: center;
  line-height: 26px;
}
.users .img {
  background-repeat: no-repeat;
  background-size: cover;
  width: 70px;
  height: 70px;
  border-radius: 50%;
}

.users .name {
  font-size: 22px;
  font-family: "Overpass";
}
.users .user-data:not(.name) {
  font-size: 14px;
}
.f-j-c {
  display: flex;
  flex-wrap: wrap;
}
.users .user-data {
  padding: 20px 0 0 10px;
}
.users .user {
  padding: 15px 20px 50px 30px;
  flex: 0 0 33%;
}
.btn2 {
  margin: 5px 0px 160px 0;
}
</style>
