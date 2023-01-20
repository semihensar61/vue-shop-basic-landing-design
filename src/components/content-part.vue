<script setup>
import itemSlider from "./item-slider.vue";
</script>
<template>
  <div
    className="md:mt-[6rem] text-white md:text-black font-bold leading-[26px] md:leading-[40.62px] text-[20px] md:text-[31.25px] pr-6 md:pr-[6.625rem]"
  >
    Everyday items, we have something to suit every occasion.
  </div>
  <div
    className="hidden md:flex md:mt-[0.75rem] font-normal md:leading-[25.6px] md:text-[16px] md:pr-[10.5rem]"
  >
    At suspendisse augue lectus arcu, accumsan ut sit posuere vitae sit
    tincidunt semper eu proin leo gravida cursus.
  </div>
  <div
    className="mt-4 md:mt-[2rem] text-white md:text-black font-medium md:leading-[17.48px] md:text-[12.8px] underline cursor-pointer"
  >
    Shop all everyday items
  </div>
  <div className="mt-[32px] md:mt-[68px]"><itemSlider></itemSlider></div>
</template>
