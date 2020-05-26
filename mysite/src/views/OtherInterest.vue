<template>
 <div id="otherIntMain">
    <div id="otherIntHeading">
      <h4> What I Believe</h4>
      
    </div>
    <div id="believeList">
        <h2>CUSTOMER FIRST</h2>
        <h2>CHANGE IS INEVITABLE</h2> 
        <h2>GET THE JOB DONE AND BE RELETLESS</h2>
       <h2> NEVER STOP LEARNING</h2>
              <h2> PLAN AGGRESIVELY</h2>

       <h2> LOVE YOUR SELF </h2>
        <h2> LIFE IS SHORT</h2>


      </div>
    </div>
</template>
<script>
export default {
    name:"OtherInterest"
}
</script>


<style scoped>
#otherIntMain {
  position: relative;
  width: 100%;
  height: 500px;
  margin-top: 200px;
  overflow: hidden;
  /* background-color: burlywood; */
    background-image: radial-gradient(circle,white,#032a66);



}
#otherIntHeading {
    display: block;
  font-family: "SpecialElite";
  font-size: 40px;
  width: fit-content;
  margin-left: 40px;
  color:white;
}

#believeList {
  /* background-image:url("../assets/yellow.jpg"); */
  /* background-color:whitesmoke; */
    /* background-image: radial-gradient(circle,white,#032a66); */
}
#believeList h2{
  margin:0;
  margin-bottom:15px;
  text-align:center;
  font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
  font-weight: 900;

  text-shadow: 1px 1px #f7f3f3;
}
</style>