<script setup>
import colorsComp from "./colors-comp.vue";
</script>
<template>
  <div className="w-[148px] md:w-[230px]">
    <img src="../assets/images/pant.svg" />
    <div className="text-[12.8px] mt-2">365 Signature Hoodie</div>
    <div className="flex flex-row md:flex-col w-full justify-between">
      <div className="text-[12.8px] mt-1 font-medium">€33.95</div>
      <div className="text-[12.8px] mt-1 "><colorsComp></colorsComp></div>
    </div>
  </div>
</template>
