<template>
  <div>
    <div class="shape bg-gray-300 py-32 md:py-20 px-4">
      <div class="flex flex-col items-center">
        <div
          class="flex flex-col md:flex-row justify-center items-center gap-8"
        >
          <img
            class=""
            src="https://github.com/pnyamuda/comicstats/blob/master/ScienceDefs2.jpg?raw=true"
            alt="food recipes app"
            width="400px"
          />
          <div class="w-full md:w-1/3 flex flex-col justify-start">
            <p class="text-3xl text-blue-400 py-2">ScienceDefs</p>
            <p>
              A Restful API for A 'Level physics and chemistry students. The API
              uses JWT for authentication and authorization. One of the main
              reasons students fail physics and chemistry exams is the inability
              to define and state physics and chemistry terms properly. In
              physics and chemistry, unlike other subjects, terms are required
              to be defined in a specific way and must contain specific
              keywords. Failure to do so means losing marks. It is this API’s
              aim to help such students. The API’s main focus is on Cambridge A’
              level and South African matric students.
            </p>
            <p class="text-lg py-2">Technology</p>
            <p>
              ScienceDefs was built using Java, Spring Boot, Hibernate and
              MySQL.
            </p>
          </div>
        </div>
        <div class="flex justify-evenly flex-wrap items-center gap-4">
          <img
            src="https://1000logos.net/wp-content/uploads/2020/09/Java-Logo.png"
            alt=""
            width="150"
          />
          <img
            class="mt-4"
            src="https://miro.medium.com/max/700/1*-uckV8DOh3l0bCvqZ73zYg.png"
            alt=""
            width="250"
          />
          <img
            src="https://download.logo.wine/logo/MySQL/MySQL-Logo.wine.png"
            alt=""
            width="150"
          />
          <img
            src="https://cdn.worldvectorlogo.com/logos/hibernate-1.svg"
            alt=""
            width="150"
          />
        </div>
        <div class="flex items-center w-full justify-center gap-4 mt-4">
          <a
            href="https://github.com/pnyamuda/JAVA-SPRING-BOOT-RESTful-API/tree/master"
            target="_blank"
            class="focus:outline-none bg-green-600 rounded-sm text-gray-100 px-4 py-1 transition duration-300 ease-in-out hover:bg-green-800"
          >
            Documentation
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ScienceDef",
  props: {},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
.shape {
  clip-path: polygon(0 1%, 100% 10%, 100% 95%, 0 99%);
}
</style>
