<template>
  <div id="workMain">
    <div id="workHeading">
      <h3>What I Did So Far !</h3>
    </div>
    <div id="work1" class="workContainer">
      <div class="companyImage">
        <img src="../assets/ul_small.jpg" />
      </div>
      <div class="workDesc">
        <h4>University of Limerick</h4>
        <h5>Master's In Information and Network Security, Aug 2019 - Present</h5>
        <h6>Limerick, Ireland</h6>
        <p>University of Limerick provided me the exposure as expected. I learned various
            cybersecurity fields like Data Forensic, Web Security and Network Security Protocal 
            manifestation.My 1 year stay at UL is amazing which because of a wonderful and diverse society.<br>
            <br>
            My favorite topic is Health Care security
            </p>
      </div>
      <div></div>
    </div>


 <div id="work2" class="workContainer">
      <div class="companyImage">
        <img src="../assets/gor_small.jpg" />
      </div>
      <div class="workDesc">
        <h4>GreyOrange Pte</h4>
        <h5>Professional Services Engineer, May 2018 - Aug 2019</h5>
        <h6>Gurgaon, India</h6>
        <p>University of Limerick provided me the exposure as expected. I learned various
            cybersecurity fields like Data Forensic, Web Security and Network Security Protocal 
            manifestation.My 1 year stay at UL is amazing which because of a wonderful and diverse society.<br>
            <br>
            My favorite topic is Health Care security
            </p>
      </div>
      <div></div>
    </div>

<div id="work3" class="workContainer">
      <div class="companyImage">
        <img src="../assets/foodgym.png" />
      </div>
      <div class="workDesc">
        <h4>FoodGym</h4>
        <h5>Founder, Nov 2017 - April 2018</h5>
        <h6>Delhi, India</h6>
        <p>University of Limerick provided me the exposure as expected. I learned various
            cybersecurity fields like Data Forensic, Web Security and Network Security Protocal 
            manifestation.My 1 year stay at UL is amazing which because of a wonderful and diverse society.<br>
            <br>
            My favorite topic is Health Care security
            </p>
      </div>
      <div></div>
    </div>

    <div id="work4" class="workContainer">
      <div class="companyImage">
        <img src="../assets/csc_small.png" />
      </div>
      <div class="workDesc">
        <h4>Computer Sciences Corporation</h4>
        <h5>Software Developer, oct 2015 - Dec 2017</h5>
        <h6>Noida, India</h6>
        <p>University of Limerick provided me the exposure as expected. I learned various
            cybersecurity fields like Data Forensic, Web Security and Network Security Protocal 
            manifestation.My 1 year stay at UL is amazing which because of a wonderful and diverse society.<br>
            <br>
            My favorite topic is Health Care security
            </p>
      </div>
      <div></div>
    </div>
  </div>
</template>
<script>
export default {
  name: "Work"
};
</script>

<style scoped>
#workMain {
  display: block;
  position: static;
  width: 100%;
  height: 1000px;
  margin: 0px;
  /* background-color: burlywood; */
  /* background-color: rgb(194, 219, 52); */
}
#workHeading {
  display: block;
  position: relative;
  font-family: "SpecialElite";
  font-size: 40px;
  width: fit-content;
  margin-left: 50px;
  color: #032a66;
}

.workContainer {
  display: block;
  position: relative;
  margin-left: auto;
  margin-right: auto;
  /* background-color: aqua; */
  width: 700px;
  height: 250px;
    overflow: hidden;

}
.companyImage {
  display: inline-block;
  position: static;
  width: 200px;
  height: 200px;
  /* background-color: blue; */
  margin: 10px;
  border-radius: 5%;
  overflow: hidden;
}
.workDesc {
  display: inline-block;
  position: static;
  float: inline-end;
  width: 450px;
  height: 200px;
  margin: 10px;
  /* background-color: rgb(233, 199, 10); */
}
.workDesc h4,h5,h6 {
    margin-top: 0;
    margin-bottom: 4px;
    font-family: Quattrocento;
    font-weight: lighter;
}
.workDesc h4 {
    color: rgb(68, 136, 0);
font-weight: bold;}
.workDesc h5 {
     color: rgb(180, 25, 25);
font-weight: lighter;}

.workDesc h6 {
     color: rgb(12, 11, 11);
font-weight: bold;}
.workDesc p {
    font-family: Quattrocento;
    font-weight: lighter;
    font-size: 16px;
    color: grey;

}
</style>