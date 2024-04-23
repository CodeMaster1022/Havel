<script setup lang="js">
import { Motion } from '@oku-ui/motion';
import VTooltip from 'v-tooltip';
</script>

<template>
  <div
    className="mx-auto grid gap-6 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 max-w-5xl pt-6 items-center"
  >
    <motion
      v-b-tooltip.hover
      title="Tooltip directive content"
      :hover="{ scale: [null, 1.5, 1.1] }"
      :transition="{ duration: 0.5 }"
      :press="{ scale: 0.8 }"
      className="relative flex flex-col border-2 border-white items-center p-6 rounded-xl shadow-xl h-24 backdrop-blur-xl bg-white/10"
    >
      <h1 class="text-2xl">50</h1>
      <p>4 OF STAKERS ⓘ</p>
    </motion>
    <motion
      v-b-tooltip.hover
      title="Tooltip directive content"
      :hover="{ scale: [null, 1.5, 1.1] }"
      :transition="{ duration: 0.5 }"
      :press="{ scale: 0.8 }"
      className="relative flex flex-col items-center p-6 border-2 border-white bg-white rounded-xl shadow-xl h-24 backdrop-blur-xl bg-white/10"
    >
      <h1 class="text-2xl">Next Payout</h1>
      <p></p>
    </motion>
    <motion
      v-b-tooltip.hover
      title="Tooltip directive content"
      :hover="{ scale: [null, 1.5, 1.1] }"
      :transition="{ duration: 0.5 }"
      :press="{ scale: 0.8 }"
      className="relative flex border-2 border-white flex-col items-center p-6 bg-white rounded-xl shadow-xl h-24 backdrop-blur-xl bg-white/10"
    >
      <h1 class="text-2xl">10.00%</h1>
      <p>DISTRIBUTION ⓘ</p>
    </motion>
    <motion
      v-b-tooltip.hover
      title="Tooltip directive content"
      :hover="{ scale: [null, 1.5, 1.1] }"
      :transition="{ duration: 0.5 }"
      :press="{ scale: 0.8 }"
      className="relative flex flex-col border-2 border-white items-center p-6 bg-white rounded-xl shadow-xl h-24 backdrop-blur-xl bg-white/10"
    >
      <h1 class="text-2xl">100.00</h1>
      <p>TOTAL STAKE ⓘ</p>
    </motion>
    <motion
      :hover="{ scale: [null, 1.5, 1.1] }"
      :transition="{ duration: 0.5 }"
      :press="{ scale: 0.8 }"
      className="relative flex flex-col border-2 border-white items-center p-6 bg-white rounded-xl shadow-xl lg:col-start-2 h-24 backdrop-blur-xl bg-white/10"
    >
      <h1 class="text-2xl">700M NIM</h1>
      <p>Rewards paid out ⓘ</p>
    </motion>
    <motion
      :hover="{ scale: [null, 1.5, 1.1] }"
      :transition="{ duration: 0.5 }"
      :press="{ scale: 0.8 }"
      className="relative flex flex-col border-2 border-white items-center p-6 bg-white rounded-xl shadow-xl  lg:col-start-3 h-24 backdrop-blur-xl bg-white/10"
    >
      <h1 class="text-2xl">2.9%</h1>
      <p>Commission ⓘ</p>
    </motion>
  </div>
</template>

<style scoped>
.v-b-tooltip {
  width: 200px;
}
</style>
