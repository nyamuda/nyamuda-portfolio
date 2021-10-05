<template>
  <div>
    <div class="shape py-28 md:py-20 px-4">
      <div class="flex flex-col items-center">
        <div
          class="flex flex-col md:flex-row-reverse justify-center items-center gap-8"
        >
          <img
            class=""
            src="https://github.com/pnyamuda/comicstats/blob/master/wordinfo2.jpg?raw=true"
            alt="food recipes app"
            width="500px"
          />
          <div class="w-full md:w-1/4 flex flex-col justify-start">
            <p class="text-3xl text-blue-400 py-2">WordInfo</p>
            <p>
              A web app that provides a great and detailed explanation of the
              meaning of any word and high quality images related to the word.
              It also uses the Wordnik API to provide the word of the day. The
              app was developed from scratch using only HTML, CSS and vanilla
              JavaScript
            </p>
            <p class="text-lg py-2">Technology</p>
            <p>
              WordInfo was built from scratch using only HTML, CSS and vanilla
              JavaScript. It consumes three third party RESTful APIs: Wordnik,
              Pixabay and WordsAPI.
            </p>
          </div>
        </div>
        <div class="flex justify-evenly flex-wrap items-center mt-6">
          <!-- <img
            src="https://1000logos.net/wp-content/uploads/2020/09/JavaScript-Logo.png"
            alt=""
            width="150"
          /> -->
          <img
            src="https://www.freepnglogos.com/uploads/html5-logo-png/html5-logo-devextreme-multi-purpose-controls-html-javascript-3.png"
            alt=""
            width="200"
          />
        </div>
        <div
          class="flex flex-col md:flex-row items-center w-full justify-center gap-4 flex-wrap mt-8"
        >
          <a
            href="https://pnyamuda.github.io/mywordinfo/"
            target="_blank"
            class="cursor-pointer focus:outline-none bg-green-600 rounded-sm text-gray-100 px-4 py-1 transition duration-300 ease-in-out hover:bg-green-800"
          >
            Launch
          </a>
          <a
            href="https://github.com/pnyamuda/mywordinfo/tree/gh-pages"
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
