<script setup></script>

<template>
  <div class="w-full pt-4">
    <div
      className="max-w-5xl flex mx-auto px-3 space-y-4 border-2 border-white rounded-2xl py-4 backdrop-blur-sm"
    >
      <form class="flex-grow">
        <div class="relative">
          <div
            class="absolute inset-y-0 start-0 flex items-center ps-3 pointer-events-none w-8"
          >
            <svg
              class="w-12 h-12 text-gray-500 dark:text-gray-400"
              aria-hidden="true"
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 20 20"
            >
              <path
                stroke="currentColor"
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="m19 19-4-4m0-7A7 7 0 1 1 1 8a7 7 0 0 1 14 0Z"
              />
            </svg>
          </div>
          <input
            type="search"
            id="default-search"
            class="block w-full p-4 ps-10 text-sm h-20 text-gray-900 border border-gray-300 rounded-lg bg-gray-50 focus:ring-blue-100 focus:border-blue-100 dark:bg-gray-100 dark:border-gray-100 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-100 dark:focus:border-blue-100"
            placeholder="If you are an existing staker with us, please enter your NIMIQ address here to see your payout history"
            required
          />
          <button
            type="submit"
            class="text-white absolute end-2.5 bottom-2.5 focus:outline-none hidden sm:block focus:ring-blue-300 font-medium rounded-lg text-sm px-4 py-2 dark:bg-blue-200 dark:hover:bg-blue-200 dark:focus:ring-blue-100"
          >
            <svg
              width="45"
              height="45"
              viewBox="0 0 45 45"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <circle
                cx="22.5"
                cy="22.5"
                r="22.5"
                fill="url(#paint0_radial_30_188)"
              />
              <path
                d="M25.135 29.2836C25.1368 29.2818 25.1386 29.28 25.1404 29.2782L30.7414 23.6846C30.7856 23.6401 30.8248 23.591 30.8585 23.5381L30.9464 23.3771L30.983 23.2672V23.1867C31.0057 23.0633 31.0057 22.9367 30.983 22.8133V22.7401V22.6522L30.9171 22.5277C30.8794 22.4584 30.8326 22.3943 30.778 22.3374L25.1404 16.7218C24.7674 16.3457 24.1601 16.3433 23.784 16.7164C23.7822 16.7181 23.7804 16.72 23.7786 16.7218C23.4169 17.1008 23.4169 17.6972 23.7786 18.0763L27.1172 21.4222C27.2588 21.5666 27.2565 21.7984 27.1121 21.9399C27.0449 22.0057 26.955 22.0432 26.861 22.0445H15.9592C15.4295 22.0445 15 22.4739 15 23.0036C15 23.5333 15.4293 23.9627 15.9591 23.9628H15.9592H26.861C27.0631 23.9656 27.2247 24.1318 27.2219 24.334C27.2205 24.428 27.1831 24.5179 27.1172 24.5851L23.7786 27.9164C23.4123 28.2964 23.4123 28.8982 23.7786 29.2782C24.1517 29.6543 24.7589 29.6567 25.135 29.2836Z"
                fill="white"
              />
              <defs>
                <radialGradient
                  id="paint0_radial_30_188"
                  cx="0"
                  cy="0"
                  r="1"
                  gradientUnits="userSpaceOnUse"
                  gradientTransform="translate(45 45) rotate(-180) scale(45)"
                >
                  <stop stop-color="#CC3047" />
                  <stop offset="1" stop-color="#D94432" />
                </radialGradient>
              </defs>
            </svg>
          </button>
        </div>
        <button
          class="bg-[#D94432] rounded-[40px] block w-full py-5 sm:hidden mt-4 text-white"
        >
          Sumbit
        </button>
      </form>
    </div>
  </div>
</template>

<style scoped></style>
