<template>
  <div id="all-projects">
    <div class="w-full flex flex-col items-center justify-center mt-10">
      <div class="flex flex-col justify-start">
        <p class="text-4xl py-2">
          Hello, I'm <span class="text-green-600">Pierce Nyamuda.</span>
        </p>
        <p class="text-2xl">I'm a Full Stack Developer.</p>
      </div>

      <ScienceDef />
      <DiseaseCollective />

      <RecipeProject />
      <WordProject />
      <WheelOfLife />
    </div>
    <div class="w-full flex flex-col items-center justify-center mt-16 mb-14">
      <p class="text-2xl text-gray-600">I'm available for work, get in touch</p>
      <p class="text-xl text-gray-600">ptnrlab@gmail.com</p>
    </div>
  </div>
</template>

<script>
import RecipeProject from "./Projects/RecipeProject.vue";
import WordProject from "./Projects/WordProject.vue";
import ScienceDef from "./Projects/ScienceDef.vue";
import WheelOfLife from "./Projects/WheelOfLife.vue";
import DiseaseCollective from "./Projects/DiseaseCollective.vue";
export default {
  name: "MainPage",
  components: {
    RecipeProject,
    WordProject,
    ScienceDef,
    WheelOfLife,
    DiseaseCollective,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Cabin&display=swap");
#all-projects {
  font-family: "Cabin", sans-serif;
}
</style>
