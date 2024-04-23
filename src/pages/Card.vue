<script setup lang="js">
import { Motion } from '@oku-ui/motion';
import './Tooltip.css'
</script>

<template>
  <div
    className="mx-auto grid gap-6 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 max-w-5xl pt-6 items-center"
  >
    <motion
      :press="{ scale: 0.9 }"
      className="relative flex flex-col border-2 border-white px-3 pb-3 items-center  rounded-xl shadow-xl h-28 backdrop-blur-xl bg-white/10"
    >
      <div class="w-[100%] flex flex-row-reverse">
        <div class="tooltip-container">
          <span class="tooltip"
            >The number of unique NIMIQ accounts that have delegated their stake
            to our validator</span
          >
          <!-- <span class="text">Tooltip</span> -->
          <div
            class="relative flex-col gap-4 w-full flex items-center justify-center"
          >
            <div
              class="w-4 h-4 border-2 animate-spin border-gray-300 flex items-center justify-center border-t-blue-400 rounded-full"
            ></div>
            <div
              class="absolute top-[50%] left-[50%] -translate-x-[50%] -translate-y-[50%] text-blue-400 text-sm"
            >
              1
            </div>
          </div>
        </div>
      </div>
      <h1 class="text-2xl">50</h1>
      <p>NUMBER OF STAKERS</p>
    </motion>
    <motion
      :press="{ scale: 0.9 }"
      v-b-tooltip.click
      title="Tooltip directive content"
      className="relative flex flex-col items-center px-3 pb-3 border-2 border-white rounded-xl shadow-xl h-28 backdrop-blur-xl bg-white/10"
    >
      <div class="w-[100%] flex flex-row-reverse">
        <div class="tooltip-container">
          <span class="tooltip"
            >The time remaining until the next automated reward payout is sent
            to our stakers</span
          >
          <!-- <span class="text">Tooltip</span> -->
          <div
            class="relative flex-col gap-4 w-full flex items-center justify-center"
          >
            <div
              class="w-4 h-4 border-2 animate-spin border-gray-300 flex items-center justify-center border-t-blue-400 rounded-full"
            ></div>
            <div
              class="absolute top-[50%] left-[50%] -translate-x-[50%] -translate-y-[50%] text-blue-400 text-sm"
            >
              2
            </div>
          </div>
        </div>
      </div>
      <h1 class="text-2xl">NEXT PAYOUT</h1>
    </motion>
    <motion
      :press="{ scale: 0.9 }"
      v-b-tooltip.hover
      title="Tooltip directive content"
      className="relative flex border-2 border-white flex-col items-center px-3 pb-3 bg-white rounded-xl shadow-xl h-28 backdrop-blur-xl bg-white/10"
    >
      <div class="w-[100%] flex flex-row-reverse">
        <div class="tooltip-container">
          <span class="tooltip"
            >This is the percentage of all staked NIMIQ that is staked with
            us</span
          >
          <!-- <span class="text">Tooltip</span> -->
          <div
            class="relative flex-col gap-4 w-full flex items-center justify-center"
          >
            <div
              class="w-4 h-4 border-2 animate-spin border-gray-300 flex items-center justify-center border-t-blue-400 rounded-full"
            ></div>
            <div
              class="absolute top-[50%] left-[50%] -translate-x-[50%] -translate-y-[50%] text-blue-400 text-sm"
            >
              3
            </div>
          </div>
        </div>
      </div>
      <h1 class="text-2xl">10.00%</h1>
      <p>DISTRIBUTION</p>
    </motion>
    <motion
      :press="{ scale: 0.9 }"
      v-b-tooltip.hover
      title="Tooltip directive content"
      className="relative flex flex-col border-2 border-white items-center px-3 pb-3 bg-white rounded-xl shadow-xl h-28 backdrop-blur-xl bg-white/10"
    >
      <div class="w-[100%] flex flex-row-reverse">
        <div class="tooltip-container">
          <span class="tooltip"
            >This is how much NIMIQ is staked with us right now</span
          >
          <!-- <span class="text">Tooltip</span> -->
          <div
            class="relative flex-col gap-4 w-full flex items-center justify-center"
          >
            <div
              class="w-4 h-4 border-2 animate-spin border-gray-300 flex items-center justify-center border-t-blue-400 rounded-full"
            ></div>
            <div
              class="absolute top-[50%] left-[50%] -translate-x-[50%] -translate-y-[50%] text-blue-400 text-sm"
            >
              4
            </div>
          </div>
        </div>
      </div>
      <h1 class="text-2xl">100.00</h1>
      <p>TOTAL STAKE</p>
    </motion>
    <motion
      :press="{ scale: 0.9 }"
      className="relative flex flex-col border-2 border-white items-center px-3 pb-3 bg-white rounded-xl shadow-xl lg:col-start-2 h-28 backdrop-blur-xl bg-white/10"
    >
      <div class="w-[100%] flex flex-row-reverse">
        <div class="tooltip-container">
          <span class="tooltip"
            >This is the sum of all rewards we have paid</span
          >
          <!-- <span class="text">Tooltip</span> -->
          <div
            class="relative flex-col gap-4 w-full flex items-center justify-center"
          >
            <div
              class="w-4 h-4 border-2 animate-spin border-gray-300 flex items-center justify-center border-t-blue-400 rounded-full"
            ></div>
            <div
              class="absolute top-[50%] left-[50%] -translate-x-[50%] -translate-y-[50%] text-blue-400 text-sm"
            >
              5
            </div>
          </div>
        </div>
      </div>
      <h1 class="text-2xl">700M NIM</h1>
      <p>REWARDS PAID</p>
    </motion>
    <motion
      :press="{ scale: 0.9 }"
      className="relative flex flex-col border-2 border-white items-center px-3 pb-3 bg-white rounded-xl shadow-xl  lg:col-start-3 h-28 backdrop-blur-xl bg-white/10"
    >
      <div class="w-[100%] flex flex-row-reverse">
        <div class="tooltip-container">
          <span class="tooltip"
            >This is how much we deduct from reward payouts</span
          >
          <!-- <span class="text">Tooltip</span> -->
          <div
            class="relative flex-col gap-4 w-full flex items-center justify-center"
          >
            <div
              class="w-4 h-4 border-2 animate-spin border-gray-300 flex items-center justify-center border-t-blue-400 rounded-full"
            ></div>
            <div
              class="absolute top-[50%] left-[50%] -translate-x-[50%] -translate-y-[50%] text-blue-400 text-sm"
            >
              6
            </div>
          </div>
        </div>
      </div>
      <h1 class="text-2xl">2.9%</h1>
      <p>COMMISSION</p>
    </motion>
  </div>
</template>

<style scoped></style>
