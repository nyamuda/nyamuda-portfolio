<template>
  <div>
    <div class="shape bg-gray-300 py-28 md:py-20 px-4">
      <div class="flex flex-col items-center">
        <div
          class="flex flex-col md:flex-row justify-center items-center gap-8"
        >
          <img
            class=""
            src="https://github.com/pnyamuda/comicstats/blob/master/image/coachjoe.jpg?raw=true"
            alt="food recipes app"
            width="500px"
          />
          <div class="w-full md:w-1/4 flex flex-col justify-start">
            <p class="text-3xl text-blue-400 py-2">Joe’s Wheel of Life</p>
            <p>
              A booking application that allows users to book lifestyle coaching
              sessions. Joe’s Wheel of Life is an easy, high level tool to
              identify a baseline for where you are in life
            </p>
            <p class="text-lg py-2">Technology</p>
            <p>
              Was developed using only vanilla JavaScript, HTML and CSS.
            </p>
          </div>
        </div>
        <div class="flex flex-wrap w-full justify-center mt-6">
          <img
            src="https://www.freepnglogos.com/uploads/html5-logo-png/html5-logo-devextreme-multi-purpose-controls-html-javascript-3.png"
            alt=""
            width="200"
          />
        </div>
        <div
          class="flex flex-col md:flex-row items-center w-full justify-center gap-4 mt-8 flex-wrap"
        >
          <a
            href="https://www.joebukartek.com/wheeloflife"
            target="_blank"
            class="cursor-pointer focus:outline-none bg-green-600 rounded-sm text-gray-100 px-4 py-1 transition duration-300 ease-in-out hover:bg-green-800"
          >
            Launch
          </a>
          <a
            href="https://github.com/pnyamuda/wheel-of-life/tree/gh-pages"
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
