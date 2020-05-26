<template>
  <div class="home">
    <div class="navBar">
      <div class="navOptions">
        <a href="" @click.prevent="goToConnect('connectMain')">
          <h4>Connect</h4>
        </a>
      </div>
      <div class="navOptions">
        <h4>
          <a href ="" @click.prevent="goToConnect('otherIntMain')">Belief</a>
        </h4>
      </div>
      <div class="navOptions">
        <h4>
          <a href="" @click.prevent="goToConnect('workMain')" >Work</a>
        </h4>
      </div>
      <div class="navOptions">
        <h4>
          <a href="" @click.prevent="goToConnect('homeMain')">About</a>
        </h4>
      </div>
    </div>
    <div id="homeScreen">
      <div id="homeScreenBanner">
        <div id="bannerHeadingWelcome">
          <h4>Hey, I'm</h4>
        </div>
        <div id="bannerUserName">
          <h1>Chetan Sharma</h1>
        </div>

        <div id="bannerTagLine">
          <h4>TWO minds are better than ONE !</h4>
        </div>
        <div id="bannerImage">
          <img src="../assets/DON.png" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
export default {
  name: "Home",
  components: {},
  methods: {
    goToConnect: function(divId) {
      var elmnt = document.getElementById(divId);
      elmnt.scrollIntoView().scrollTop -= 10;
    }
    //  ,
    // goToWork:function() {
    //     var elmnt = document.getElementById("workMain");
    //   elmnt.scrollIntoView();
    // }
  }
};
</script>

<style scoped>
.home {
  position: relative;
  /* background-color: black; */
  height: 500px;
  width: 100%;
}

.navBar {
  position: absolute;
  height: 50px;
  width: 99%;
  /* background-color: lavenderblush; */
  margin: 5px;
}
.navOptions {
  width: fit-content;
  position: relative;
  float: right;
  margin-right: 25px;
  font-family: Quattrocento;
  color: rgb(67, 67, 255);
}

#homeScreen {
  position: absolute;
  top: 60px;
  width: inherit;
  height: 430px;
  /* background-color: lightcoral; */
}

#homeScreenBanner {
  display: block;
  height: 400px;
  width: 350px;
  /* background-color: lawngreen; */
  margin-left: auto;
  margin-right: auto;
  margin-top: 20px;
}

#bannerHeadingWelcome {
  font-family: Quattrocento;
}

#bannerUserName {
  font-family: Quattrocento;
  font-size: x-large;
}
#bannerTagLine {
  font-family: Quattrocento;
  color: lightslategrey;
  text-align: center;
}
#bannerImage img {
  display: block;
  margin: auto;
  width: 250px;
  height: 200px;
  border-radius: 50%;
}

@font-face {
  font-family: "Quattrocento";
  src: url("../assets/QuattrocentoSans/QuattrocentoSans.eot"); /* IE9 Compat Modes */
  src: url("../assets/QuattrocentoSans/QuattrocentoSans.eot?#iefix")
      format("embedded-opentype"),
    /* IE6-IE8 */ url("../assets/QuattrocentoSans/QuattrocentoSans.woff")
      format("woff"),
    /* Pretty Modern Browsers */
      url("../assets/QuattrocentoSans/QuattrocentoSans.ttf") format("truetype"),
    /* Safari, Android, iOS */
      url("../assets/QuattrocentoSans/QuattrocentoSans.svg#svgFontName")
      format("svg"); /* Legacy iOS */
}
</style>