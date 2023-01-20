<script setup>
import colorsComp from "./colors-comp.vue";
// TODO caurusel will be added
</script>
<template>
  <div className="flex max-width-[300px] overflow-hidden md:mr-10">
    <div className="min-w-[148px] md:min-w-[230px]">
      <img src="../assets/images/sweat-green.svg" />
      <div className="text-[12.8px] mt-2">365 Signature Hoodie</div>
      <div className="flex flex-row md:flex-col w-full justify-between">
        <div className="text-[12.8px] mt-1 font-medium">€33.95</div>
        <div className="text-[12.8px] mt-1 "><colorsComp></colorsComp></div>
      </div>
    </div>
    <div className="min-w-[148px] md:min-w-[230px]  ml-3 md:ml-8">
      <img src="../assets/images/sweat-blue.svg" />
      <div className="text-[12.8px] mt-2">Organic Skinny High Waist Jeans</div>
      <div className="flex flex-row md:flex-col w-full justify-between">
        <div className="text-[12.8px] mt-1 font-medium">€33.95</div>
        <div className="text-[12.8px] mt-1 "><colorsComp></colorsComp></div>
      </div>
    </div>
    <div className="min-w-[148px] md:min-w-[230px]  ml-3 md:ml-8" id="toScroll">
      <img src="../assets/images/pant.svg" />
      <div className="text-[12.8px] mt-2">Organic Skinny High Waist Jeans</div>
      <div className="flex flex-row md:flex-col w-full justify-between">
        <div className="text-[12.8px] mt-1 font-medium">€33.95</div>
        <div className="text-[12.8px] mt-1 "><colorsComp></colorsComp></div>
      </div>
    </div>
  </div>
</template>
