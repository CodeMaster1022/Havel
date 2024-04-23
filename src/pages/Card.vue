<script setup lang="js">
import { Motion } from '@oku-ui/motion';
import './Tooltip.css'
</script>

<template>
  <div
    className="mx-auto grid gap-6 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 max-w-5xl pt-6 items-center"
  >
    <motion
      className="relative flex flex-col border-2 border-white px-3 pb-3 items-center  rounded-xl shadow-xl h-32 backdrop-blur-xl bg-white/10"
    >
      <div class="w-[100%] flex flex-row-reverse">
        <div class="tooltip-container">
          <span class="tooltip"
            >The number of unique NIMIQ accounts that have delegated their stake
            to our validator</span
          >
          <!-- <span class="text">Tooltip</span> -->
          <img src="../assets/information.svg" alt="info" />
        </div>
      </div>
      <div>
        <div class="loader">
          <div class="bar1"></div>
          <div class="bar2"></div>
          <div class="bar3"></div>
          <div class="bar4"></div>
          <div class="bar5"></div>
          <div class="bar6"></div>
          <div class="bar7"></div>
          <div class="bar8"></div>
          <div class="bar9"></div>
          <div class="bar10"></div>
          <div class="bar11"></div>
          <div class="bar12"></div>
        </div>
      </div>
      <p>NUMBER OF STAKERS</p>
    </motion>
    <motion
      :press="{ scale: 0.9 }"
      v-b-tooltip.click
      title="Tooltip directive content"
      className="relative flex flex-col items-center px-3 pb-3 border-2 border-white rounded-xl shadow-xl h-32 backdrop-blur-xl bg-white/10"
    >
      <div class="w-[100%] flex flex-row-reverse">
        <div class="tooltip-container">
          <span class="tooltip"
            >The time remaining until the next automated reward payout is sent
            to our stakers</span
          >
          <!-- <span class="text">Tooltip</span> -->
          <img src="../assets/information.svg" alt="info" />
        </div>
      </div>
      <div>
        <div class="loader">
          <div class="bar1"></div>
          <div class="bar2"></div>
          <div class="bar3"></div>
          <div class="bar4"></div>
          <div class="bar5"></div>
          <div class="bar6"></div>
          <div class="bar7"></div>
          <div class="bar8"></div>
          <div class="bar9"></div>
          <div class="bar10"></div>
          <div class="bar11"></div>
          <div class="bar12"></div>
        </div>
      </div>
      <p>NEXT PAYOUT</p>
    </motion>
    <motion
      :press="{ scale: 0.9 }"
      v-b-tooltip.hover
      title="Tooltip directive content"
      className="relative flex border-2 border-white flex-col items-center px-3 pb-3 bg-white rounded-xl shadow-xl h-32 backdrop-blur-xl bg-white/10"
    >
      <div class="w-[100%] flex flex-row-reverse">
        <div class="tooltip-container">
          <span class="tooltip"
            >This is the percentage of all staked NIMIQ that is staked with
            us</span
          >
          <!-- <span class="text">Tooltip</span> -->
          <img src="../assets/information.svg" alt="info" />
        </div>
      </div>
      <div>
        <div class="loader">
          <div class="bar1"></div>
          <div class="bar2"></div>
          <div class="bar3"></div>
          <div class="bar4"></div>
          <div class="bar5"></div>
          <div class="bar6"></div>
          <div class="bar7"></div>
          <div class="bar8"></div>
          <div class="bar9"></div>
          <div class="bar10"></div>
          <div class="bar11"></div>
          <div class="bar12"></div>
        </div>
      </div>
      <p>DISTRIBUTION</p>
    </motion>
    <motion
      :press="{ scale: 0.9 }"
      v-b-tooltip.hover
      title="Tooltip directive content"
      className="relative flex flex-col border-2 border-white items-center px-3 pb-3 bg-white rounded-xl shadow-xl h-32 backdrop-blur-xl bg-white/10"
    >
      <div class="w-[100%] flex flex-row-reverse">
        <div class="tooltip-container">
          <span class="tooltip"
            >This is how much NIMIQ is staked with us right now</span
          >
          <!-- <span class="text">Tooltip</span> -->
          <img src="../assets/information.svg" alt="info" />
        </div>
      </div>
      <div>
        <div class="loader">
          <div class="bar1"></div>
          <div class="bar2"></div>
          <div class="bar3"></div>
          <div class="bar4"></div>
          <div class="bar5"></div>
          <div class="bar6"></div>
          <div class="bar7"></div>
          <div class="bar8"></div>
          <div class="bar9"></div>
          <div class="bar10"></div>
          <div class="bar11"></div>
          <div class="bar12"></div>
        </div>
      </div>
      <p>TOTAL STAKE</p>
    </motion>
    <motion
      :press="{ scale: 0.9 }"
      className="relative flex flex-col border-2 border-white items-center px-3 pb-3 bg-white rounded-xl shadow-xl lg:col-start-2 h-32 backdrop-blur-xl bg-white/10"
    >
      <div class="w-[100%] flex flex-row-reverse">
        <div class="tooltip-container">
          <span class="tooltip"
            >This is the sum of all rewards we have paid</span
          >
          <!-- <span class="text">Tooltip</span> -->
          <img src="../assets/information.svg" alt="info" />
        </div>
      </div>
      <div>
        <div class="loader">
          <div class="bar1"></div>
          <div class="bar2"></div>
          <div class="bar3"></div>
          <div class="bar4"></div>
          <div class="bar5"></div>
          <div class="bar6"></div>
          <div class="bar7"></div>
          <div class="bar8"></div>
          <div class="bar9"></div>
          <div class="bar10"></div>
          <div class="bar11"></div>
          <div class="bar12"></div>
        </div>
      </div>
      <p>REWARDS PAID</p>
    </motion>
    <motion
      :press="{ scale: 0.9 }"
      className="relative flex flex-col border-2 border-white items-center px-3 pb-3 bg-white rounded-xl shadow-xl  lg:col-start-3 h-32 backdrop-blur-xl bg-white/10"
    >
      <div class="w-[100%] flex flex-row-reverse">
        <div class="tooltip-container">
          <span class="tooltip"
            >This is how much we deduct from reward payouts</span
          >
          <!-- <span class="text">Tooltip</span> -->
          <img src="../assets/information.svg" alt="info" />
        </div>
      </div>
      <div>
        <div class="loader">
          <div class="bar1"></div>
          <div class="bar2"></div>
          <div class="bar3"></div>
          <div class="bar4"></div>
          <div class="bar5"></div>
          <div class="bar6"></div>
          <div class="bar7"></div>
          <div class="bar8"></div>
          <div class="bar9"></div>
          <div class="bar10"></div>
          <div class="bar11"></div>
          <div class="bar12"></div>
        </div>
      </div>
      <p>COMMISSION</p>
    </motion>
  </div>
</template>

<style scoped></style>
