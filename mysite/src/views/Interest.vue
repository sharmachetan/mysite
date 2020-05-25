<template>
  <div id="interestMain">
    <div id="intHeading">
      <h4>>> Who 'I' am ?</h4>
    </div>

    <div id="intAboutContainer">

        <div id="intAboutImg">
            <img src="../assets/myImg.jpeg"/>
        </div>
        <div id="intAboutContent">
            <p>Welcome ,
                <br><br>Few interesting facts about me<br>
                <br># I am Chetan Sharma my friends call me 'Che .'
                <br># I am a Progreammer ,Solution designer and a Full Stack Developer .
                <br># I love to do outdoors like highking and bike rides .
                <br># I love to travel different places ...right now I m in IRELAND   
                <br># Disciplined Daily Meditiation practioner.
                <br># I love to hear U2 and Aersosmith .
                <br>
                <br> ......Comming next .....<br>
                <br># Learing to become a Cybersecurity Engineer.
                <br># Tring to find ways to date Margot Robbie . OOPS!</p>
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
  height: 500px;
  margin: 0px;
  /* background-color: burlywood; */
      background-color: rgb(245, 242, 247);


}
#intHeading {
    display: block;
  font-family: "SpecialElite";
  font-size: 40px;
  width: fit-content;
  margin-left: 40px;
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
    font-family: SpecialElite;
    /* background-color:rgb(31, 19, 15); */
    font-size: large;

}
</style>