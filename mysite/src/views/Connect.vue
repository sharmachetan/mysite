<template>
<div id="connectMain">
    
    <div id="connectHeading">
        <h3> Connect </h3>
    </div>
    <div id="connectContent">
<p> Let's connect.The best way to connect is through LinkedIn message</p>
<p> Also, If not related to any professional projects then lets join Insta for cool photos !! </p>


    </div>
    <div id="connectLogo">
        <div id="connectLin">
<a  href="https://www.linkedin.com/in/sharmachetan6/" target="_blank"><img src="../assets/LinkedIn-Logos/linkedin.png"/></a></div>
<div id="connectInsta"><a href="https://www.instagram.com/sharma_chetan9/" target="_blank">
<img src="../assets/insta.png"/></a></div>
    </div>


</div>
    
</template>
<style scoped>
@font-face {
  font-family: 'Quattrocento';
  src: url('../assets/QuattrocentoSans/QuattrocentoSans.eot'); /* IE9 Compat Modes */
  src: url('../assets/QuattrocentoSans/QuattrocentoSans.eot?#iefix') format('embedded-opentype'), /* IE6-IE8 */
       url('../assets/QuattrocentoSans/QuattrocentoSans.woff') format('woff'), /* Pretty Modern Browsers */
       url('../assets/QuattrocentoSans/QuattrocentoSans.ttf')  format('truetype'), /* Safari, Android, iOS */
       url('../assets/QuattrocentoSans/QuattrocentoSans.svg#svgFontName') format('svg'); /* Legacy iOS */
}

@font-face {
  font-family: "SpecialElite";
  src: url("../assets/SpecialElite-Regular/SpecialElite-Regular.eot"); /* IE9 Compat Modes */
  src: url("../assets/SpecialElite-Regular/SpecialElite-Regular.eot?#iefix")
      format("embedded-opentype"),
    /* IE6-IE8 */
      url("../assets/SpecialElite-Regular/SpecialElite-Regular.woff")
      format("woff"),
    /* Pretty Modern Browsers */
      url("../assets/SpecialElite-Regular/SpecialElite-Regular.ttf")
      format("truetype"),
    /* Safari, Android, iOS */
      url("../assets/SpecialElite-Regular/SpecialElite-Regular.svg")
      format("svg"); /* Legacy iOS */
}

#connectMain {
  position: relative;
  width: 100%;
  height: 550px;
  margin: 0px;
  /* background-color: burlywood; */
      /* background-color: rgb(194, 219, 52); */


}
#connectHeading {
    display: block;
  font-family: "SpecialElite";
  font-size: 40px;
  width: fit-content;
  margin-left: 50px;
  color: #032a66;
}

#connectContent {
    font-family: Quattrocento;
    text-align: center;
}

#connectLogo {
    display: block;
    width: 300px;
    height: 200px;
    margin-left: auto;
    margin-right: auto;
        /* background-color: lightcoral; */

}

#connectInsta {
    display: inline;
}
#connectLin{
    display: inline-block;
}
#connectInsta img {
    display: inline-block;

width:90px;
height:90px;
margin:20px;

}
#connectLin img {
    display: inline-block;

width:100px;
height:80px;
margin:20px;

}



</style>
<script>
export default {
    name:"connect"
}
</script>