<template>
  <v-app>
  <div>
    <v-toolbar
      width= "1440px"
      height = "82px"
      src="@/assets/back.png"
    >
      <v-spacer></v-spacer>

      <div class="name">
      <h3>Qomariyatul Hasanah</h3>
      <p>Technical Writer</p>
      </div>
      
      <div class="ic">
      <v-avatar
      size="36"
      >
      <img
        src="@/assets/avatar.png"
      >
    </v-avatar>
    </div>

    <div class="bar">
      <div class="menu">
        <div class="menu1">
        <img src="@/assets/ic-rec-tracking.png" alt="">
        <a class="SKK" href=""> IOC SKK Migas</a>
        </div>
      </div>
    </div>

    </v-toolbar>
  </div>

    <v-main>
      <div class="SCE">
        <p>SCE</p>
      </div>
      <div class="SCE2">
        <p>SCE</p>
      </div>
      <div class="work">
          <p>Work Performance Order by Category</p>
        </div>
      <div class="gas">
        <p>Gas Compressor Performance by Area</p>
      </div>
      <div class="mp">
        <p>MP SYSTEM CONDITIONS</p>
      </div>
    </v-main>

    <footer id="footer">
      <div class="content">
        <img src="@/assets/copy.png" alt="">
        <p>2021 <span> ICT PHI Region3 </span> Policy</p>
      </div>
    </footer>

  </v-app>
</template>

<script>

export default {
  name: 'App',

  data: () => ({
    //
  }),
};
</script>

<style lang="scss">
@import '@/assets/style.scss';


.v-main{
  background: #EFF7FF;
}

h1{
  color: $red;
}

.name {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-end;
  padding: 0px;

  position: absolute;
  width: 153px;
  height: 38px;
  left: 1183px;
  top: 17px;
}

.name h3{
  position: static;
  left: 0%;
  right: 0%;
  top: 0%;
  bottom: 47.37%;

  font-family: Open Sans;
  font-style: normal;
  font-weight: normal;
  font-size: 15px;
  line-height: 20px;
  text-align: right;

  color: #FFFFFF;
  }

.name p{
  position: static;
  left: 40.52%;
  right: 0%;
  top: 57.89%;
  bottom: 0%;
  font-family: Open Sans;
  font-style: normal;
  font-weight: normal;
  font-size: 12px;
  line-height: 16px;
  text-align: right;
  color: #FFFFFF;
}


.ic{
  position: absolute;
  left: 1352px;
  top: 18px;
}

.v-avatar{
  position: absolute;
  left: 0.69%;
  right: -0.69%;
  top: 0%;
  bottom: 0%;
  margin-right: 30px;
}

.bar{
  position: absolute;
  width: 1148px;
  height: 58px;
  left: 146px;
  top: 58px;
  background: #FFFFFF;
  box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
  border-radius: 8px;
}

.bar .menu {
  display: flex;
  flex-direction: row;
  align-items: flex-start;
  padding: 0px;
  position: absolute;
  width: 101px;
  height: 46px;
  left: 32px;
  top: 6px;
}

.bar .menu .menu1 {
  display: flex;
  flex-direction: column;
}

.bar .menu .menu1 a{
  position: static;
  left: 0%;
  right: 0%;
  top: 56.52%;
  bottom: 0%;
  font-family: Open Sans;
  font-style: normal;
  font-weight: normal;
  font-size: 15px;
  line-height: 20px;
  text-align: center;
  color: #52637D;
  text-decoration: none;
  cursor: pointer;
}

.bar .menu .menu1 img{
  position: static;
  width: 24px;
  height: 24px;
  left: 38.5px;
  top: 0px;
  background: #FFFFFF;
  display: block;
  margin-left: auto;
  margin-right: auto;
}

.SCE {
  position: absolute;
  left: 10.14%;
  right: 50.56%;
  top: 148px;
  bottom: 81%;
  background: #FFFFFF;
  border-radius: 8px;
}

.SCE p{
  position: absolute;
  left: 4%;
  right: 85.56%;
  top: 9.88%;
  bottom: 88.53%;
  font-family: Open Sans;
  font-style: normal;
  font-weight: 600;
  font-size: 20px;
  line-height: 27px;
  color: #52637D;
}

.SCE2 {
  display: flex;
  flex-direction: column;
  padding: 16px;
  position: absolute;
  width: 566px;
  height: 441.38px;
  left: 146px;
  top: 311px;
  background: #FFFFFF;
  border-radius: 8px;
}

.work{
  display: flex;
  flex-direction: column;
  padding: 16px;
  position: absolute;
  width: 566px;
  height: 294px;
  left: 728px;
  top: 148px;
  background: #FFFFFF;
  border-radius: 8px;
}

.work p{
  position: static;
  left: 0%;
  right: 15.92%;
  top: 4.17%;
  bottom: 4.17%;
  font-family: Open Sans;
  font-style: normal;
  font-weight: 600;
  font-size: 16px;
  line-height: 22px;
  color: #52637D
}

.gas{
  display: flex;
  flex-direction: column;
  padding: 16px;
  position: absolute;
  width: 566px;
  height: 294px;
  left: 728px;
  top: 458px;
  background: #FFFFFF;
  border-radius: 8px;
}

.gas p{
  position: static;
  left: 0%;
  right: 15.92%;
  top: 4.17%;
  bottom: 4.17%;
  font-family: Open Sans;
  font-style: normal;
  font-weight: 600;
  font-size: 16px;
  line-height: 22px;
  color: #52637D;
}

.mp{
  display: flex;
  flex-direction: column;
  padding: 16px 8px;
  position: absolute;
  width: 1148px;
  height: 650px;
  left: 146px;
  top: 780px;
  background: #FFFFFF;
  border-radius: 8px;
}

.mp p{
  position: static;
  left: 2.03%;
  right: 0%;
  top: 0%;
  bottom: 0%;
  font-family: Open Sans;
  font-style: normal;
  font-weight: 600;
  font-size: 16px;
  line-height: 22px;
  color: #52637D;
  flex: none;
  order: 0;
  flex-grow: 0;
  margin: 0px 10px;
}

footer{
  position: absolute;
  display: flex;
  flex-direction: row;
  left: 0%;
  right: 0%;
  bottom: 0%;
  background: #FFFFFF;
  height: 64px;
}

#footer img{
  width: 17px;
  height: 17px;
  position: absolute;
  left: 10px;
  top: 20px;
}

#footer p{
  position: absolute;
  left: 35px;
  top: 22px;
  font-family: Roboto;
  font-style: normal;
  font-weight: 500;
  font-size: 15px;
  line-height: 14px;
  color: #747474;
}

#footer p span{
  color: #39A3EA;
}




</style>
