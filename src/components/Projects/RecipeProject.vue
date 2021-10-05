<template>
  <div>
    <div class="shape bg-gray-300 py-28 md:py-20 px-4">
      <div class="flex flex-col items-center">
        <div
          class="flex flex-col md:flex-row justify-center items-center gap-8"
        >
          <img
            class=""
            src="https://github.com/pnyamuda/comicstats/blob/master/image/trendyrecipe.jpg?raw=true"
            alt="food recipes app"
            width="500px"
          />
          <div class="w-full md:w-1/4 flex flex-col justify-start">
            <p class="text-3xl text-blue-400 py-2">TrendyRecipe</p>
            <p>
              A single page app (SPA) that boasts hundreds of recipes and
              provides users with easy ways to cook. It uses a "what's in your
              fridge" API endpoint, allowing users to find recipes they can cook
              with the ingredients they have. Using an artificial intelligence
              based calculator, the app also uses Natural Language Processing to
              estimate calories burned for various exercises
            </p>
            <p class="text-lg py-2">Technology</p>
            <p>
              TrendyRecipe was built using Vue.js and Bootstrap and consumes a
              third party RESTful API called Spoonacular for recipes and
              nutrition data.
            </p>
          </div>
        </div>
        <div class="flex justify-evenly flex-wrap mt-4">
          <img
            src="https://www.positivethinking.tech/wp-content/uploads/2021/01/Logo-Vuejs.png"
            alt=""
            width="120"
          />
          <img
            src="https://download.logo.wine/logo/Bootstrap_(front-end_framework)/Bootstrap_(front-end_framework)-Logo.wine.png"
            alt=""
            width="120"
          />
        </div>
        <div
          class="flex flex-col md:flex-row items-center w-full justify-center gap-4 mt-4 flex-wrap"
        >
          <a
            href="https://trendyrecipe.netlify.com/"
            target="_blank"
            class="cursor-pointer focus:outline-none bg-green-600 rounded-sm text-gray-100 px-4 py-1 transition duration-300 ease-in-out hover:bg-green-800"
          >
            Launch
          </a>
          <a
            href="https://github.com/pnyamuda/trendyrecipe"
            target="_blank"
            class="focus:outline-none bg-green-600 rounded-sm text-gray-100 px-4 py-1 transition duration-300 ease-in-out hover:bg-green-800"
          >
            Github
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "RecipeProject",
  props: {},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
.shape {
  clip-path: polygon(0 1%, 100% 10%, 100% 95%, 0 99%);
}
</style>
