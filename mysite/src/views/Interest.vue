<template>
  <div id="interestMain">
    <div id="intHeading">
      <h4> Who 'I' am ?</h4>
    </div>

    <div id="intAboutContainer">

        <div id="intAboutImg">
            <img src="../assets/myImg.jpeg"/>
        </div>
        <div id="intAboutContent">
                <br><h2>Few interesting facts about me</h2><br>
                <ul>
               <li>I am Chetan Sharma my friends call me <b><i>'Che .'</i></b></li>
                <li>I am a Programmer ,Solution designer and a <b>Full Stack Developer</b>.</li>
               
                <li>I love to do outdoors like highking and bike rides .</li>
                <li>I love to travel different places ...now I m in <b>IRELAND</b>   </li>
                <li>Disciplined Daily Meditiation practioner.</li>
                <li >I love to hear U2 and Aersosmith .</li>
                <br>
                ......Comming next .....<br>
                <li>Learing to become a Cybersecurity Engineer.</li>
                <li><i>Tring to find ways to date Margot Robbie . OOPS!</i></li>
                 </ul>
        </div>
    </div>

  </div>
</template>

<script>
export default {
  name: "Interest",
  components: {}
};
</script>

<style scoped>

@import url('https://fonts.googleapis.com/css2?family=Chelsea+Market&display=swap');

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

#interestMain {
  position: relative;
  width: 100%;
  height: 600px;
  margin-top: 50px;
  /* background-color: burlywood; */
      /* background-color: rgb(245, 242, 247); */


}
#intHeading {
    display: block;
  font-family: "SpecialElite";
  font-size: 40px;
  width: fit-content;
  margin-left: 40px;
  margin-top: 20px;
  color: #032a66;
}

#intAboutContainer {
position: relative;
    display: inline-block;
    height: 380px;
    overflow: hidden;
    width: inherit;
    /* background-color: rgb(245, 236, 248); */
}

#intAboutImg {
position: relative;
    display: inline-block;
    height: 350px;
    width: fit-content;
    margin-left: 150px;
    margin-top: 20px;
      background-color:rgb(10, 10, 10);
      border-radius: 10px;
      overflow: hidden;

}

#intAboutImg img {
display: block;
margin-left: auto;
margin-right: auto;



}

#intAboutContent {
position: absolute;
    display: inline-block;
    height: 350px;
    width: 70%;
    margin-left: 60px;
    font-family: Quattrocento;
    /* background-color:rgb(31, 19, 15); */
    font-size: large;

}
#intAboutContent h2 {
  font-family: 'Chelsea Market', cursive;
  color: rgb(192, 5, 5);
}


/* Mobile Version */

@media screen and (max-width: 400px) and (min-width: 200px) {

  #interestMain {
  position: relative;
  width: 100%;
  height: 1000px;
  margin-top: 50px;
  /* background-color: burlywood; */
      /* background-color: rgb(245, 242, 247); */


}
#intHeading {
  position: static;
    display: block;
  font-family: "SpecialElite";
  font-size: 40px;
  width: fit-content;
  margin-left: 40px;
  margin-top: 20px;
  /* color: #032a66; */
    color:black;

}

#intAboutContainer {
position: static;
    display: inline-block;
    height: 380px;
    overflow: hidden;
    width: inherit;
    /* background-color: rgb(245, 236, 248); */
}

#intAboutImg {
position: relative;
    display: block;
    height: 350px;
    width: fit-content;
margin-left: auto;
margin-right: auto;

    margin-top: 20px;
      background-color:rgb(10, 10, 10);
      border-radius: 10px;
      overflow: hidden;

}

#intAboutImg img {
display: block;




}

#intAboutContent {
position: absolute;
    display: block;
    height: 350px;
    width: 70%;
    margin-left: 10px;
    font-family: Quattrocento;
    /* background-color:rgb(31, 19, 15); */
    font-size: medium;

}
#intAboutContent h2 {
  font-family: 'Chelsea Market', cursive;
  color: rgb(192, 5, 5);
  font-size: 30px;
}
  
#intAboutContent ul {
  margin: 5px;
  padding: 0px;
}

#intAboutContent ul li {
  margin: 0px;
  font-size: smaller;
  width: 340px;
}
}




</style>