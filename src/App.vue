<template>
  <div class="py-32 h-128 bg-red">
    <div class="md:flex bg-white rounded-lg p-6">
      <div>
        <img
          class="h-16 w-16 md:h-24 md:w-24 rounded-full mx-auto md:mx-0 md:mr-6"
          src="./assets/avatar.png"
        >
      </div>
      <div class="text-center md:text-left">
        <h2 class="text-lg">
          Hans Muster
        </h2>
        <div class="text-indigo-dark">
          Flamethrower expert
        </div>
        <div class="text-gray-600">
          hans-get-the@flamethrower.now
        </div>
        <div class="text-gray-600">
          +41 (0)76 407 14 72
        </div>
      </div>
    </div>
    <div>
      <div class="text-center text-xs md:text-left">
        Image copyright by martin-missfeldt.de
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: `App`,
  };
</script>
