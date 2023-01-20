<script setup>
import contentPart from "./components/content-part.vue";
</script>

<template className="">
  <div className="flex w-full flex-col md:flex-row ">
    <div className="md:w-[50%]">
      <img
        className="md:min-h-screen object-cover max-h-screen"
        src="../src/assets/images/bg.svg"
        alt="bg"
      />
    </div>
    <div
      className="flex flex-col md:w-[50%] pl-6 pr-6 md:pr-0 md:pl-[7.5rem] -mt-[180px] md:mt-0"
    >
      <contentPart></contentPart>
    </div>
  </div>
</template>
