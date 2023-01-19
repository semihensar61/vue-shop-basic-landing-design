<script setup>
import itemSlider from "./item-slider.vue";
</script>
<template>
  <div
    className="md:mt-[6rem] font-bold md:leading-[40.62px] md:text-[31.25px] md:pr-[6.625rem]"
  >
    Everyday items, we have something to suit every occasion.
  </div>
  <div
    className="md:mt-[0.75rem] font-normal md:leading-[25.6px] md:text-[16px] md:pr-[10.5rem]"
  >
    At suspendisse augue lectus arcu, accumsan ut sit posuere vitae sit
    tincidunt semper eu proin leo gravida cursus.
  </div>
  <div
    className="md:mt-[2rem] font-black md:leading-[17.48px] md:text-[12.8px] underline cursor-pointer"
  >
    Shop all everyday items
  </div>
  <div className="mt-[68px]"><itemSlider></itemSlider></div>
</template>
