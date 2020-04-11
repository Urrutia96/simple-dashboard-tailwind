<template>
  <div class="bg-navbar shadow p-3">
    <div class="md:mx-8 flex justify-between items-center">
      <div class="text-default text-xl font-bold ">
        Dashboard
      </div>
      <div class="hidden md:block w-1/3 p-1">
        <input class="apparience-none rounded-lg bg-page w-full p-2 text-default" placeholder="Buscar.."> 
      </div>
      <div class="sm:flex sm:jutify-end text-default">
          <div class="flex">
            <div class=" text-xl p-2">
              <i class="bx bx-moon"></i>
            </div>
            <div class="sm:hidden text-xl p-2">
              <i class="bx bx-menu"></i>
            </div>
          </div>
          <div class="hidden sm:flex p-2">
            <div class="p-1">Inicio</div>
            <div class="p-1">Inicio</div>
          </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String
  }
};
</script>
