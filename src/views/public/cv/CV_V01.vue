<template>
  <div class="cv">
    <div class="cv-inner">
      <Step1Top />
      <Step2Objective />
      <Step3Summery />
      <Step4Skills />
      <Step5Experience />
      <Step6Education />
      <Step7ExtraCurricularActivities />
      <Step8PersonalDetails />
    </div>
  </div>
</template>

<script>
import Step1Top from "../../../components/public/cv/cv_v01/Step1_Top";
import Step2Objective from "../../../components/public/cv/cv_v01/Step2_Objective";
import Step3Summery from "../../../components/public/cv/cv_v01/Step3_Summery";
import Step4Skills from "../../../components/public/cv/cv_v01/Step4_Skills";
import Step5Experience from "../../../components/public/cv/cv_v01/Step5_Experience";
import Step6Education from "../../../components/public/cv/cv_v01/Step6_Education";
import Step7ExtraCurricularActivities from "../../../components/public/cv/cv_v01/Step7_ExtraCurricularActivities";
import Step8PersonalDetails from "../../../components/public/cv/cv_v01/Step8_PersonalDetails";

export default {
  name: "CV",
  components: {
    Step1Top,
    Step2Objective,
    Step3Summery,
    Step4Skills,
    Step5Experience,
    Step6Education,
    Step7ExtraCurricularActivities,
    Step8PersonalDetails,
  },
  created() {
    document.querySelector("#nav").style.display = "none";
  },
};
</script>

<style scoped>
.cv {
  background: #272727a3;
  position: absolute;
  left: 0;
  right: 0;
  margin-left: auto;
  margin-right: auto;
  color: #222222;
  font-family: Arial, Helvetica, sans-serif;
}
.cv-inner {
  background: #fffff4;
  width: 660px;
  margin: 40px auto;
  box-shadow: 0 1px 20px 4px #222222;
  padding: 60px 46px 50px 94px;
  overflow: hidden;
}
</style>