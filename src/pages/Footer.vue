<script setup>
import Logo from "./logo.vue";
import Hero from "./hero.vue";
import SearchBar from "./SerchBar.vue";
import Card from "./Card.vue";
</script>

<template>
  <header class="w-full">
    <div
      className="max-w-6xl mx-auto px-5 flex items-center justify-between h-[7vh]"
    >
      <div class="w-[300px] flex">
        <ul className="text-sm flex flex-col sm:flex-row">
          <li className="mb-2">
            <a
              href="#0"
              className="text-gray-600 hover:text-gray-900 transition duration-150 ease-in-out pl-4"
              >Security</a
            >
          </li>
          <li className="mb-2">
            <a
              href="#0"
              className="text-gray-600 hover:text-gray-900 transition duration-150 ease-in-out pl-4"
              >Privacy</a
            >
          </li>
          <li className="mb-2">
            <a
              href="#0"
              className="text-gray-600 hover:text-gray-900 transition duration-150 ease-in-out pl-4"
              >Terms</a
            >
          </li>
        </ul>
      </div>
      <div class="w-[300px] flex text-[#1F2348] justify-center items-center">
        <svg
          width="16"
          height="16"
          viewBox="0 0 16 16"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            d="M11.1584 1.50313C10.0578 1.46106 8.9843 1.8507 8.16688 2.58894C8.12102 2.63005 8.06159 2.65279 8 2.65279C7.93841 2.65279 7.87899 2.63005 7.83313 2.58894C7.05574 1.88758 6.04579 1.49957 4.99878 1.5C4.94653 1.5 4.89403 1.50097 4.84156 1.50294C2.58544 1.5855 0.750001 3.54009 0.750001 5.86006C0.747766 7.00821 1.19325 8.11199 1.99181 8.93694L6.90938 14.0366C7.0507 14.1831 7.22011 14.2997 7.4075 14.3793C7.59489 14.459 7.7964 14.5 8 14.5C8.2036 14.5 8.40512 14.459 8.5925 14.3793C8.77989 14.2997 8.9493 14.1831 9.09063 14.0366L14.0081 8.93694C14.8067 8.112 15.2522 7.00822 15.25 5.86006C15.25 3.54009 13.4146 1.5855 11.1584 1.50313ZM11 8.5C11 8.5663 10.9737 8.62989 10.9268 8.67678C10.8799 8.72366 10.8163 8.75 10.75 8.75H9.25V10.25C9.25 10.3163 9.22366 10.3799 9.17678 10.4268C9.1299 10.4737 9.06631 10.5 9 10.5H7C6.9337 10.5 6.87011 10.4737 6.82323 10.4268C6.77634 10.3799 6.75 10.3163 6.75 10.25V8.75H5.25C5.1837 8.75 5.12011 8.72366 5.07322 8.67678C5.02634 8.62989 5 8.5663 5 8.5V6.5C5 6.4337 5.02634 6.37011 5.07322 6.32322C5.12011 6.27634 5.1837 6.25 5.25 6.25H5.75C5.81631 6.25 5.87989 6.27634 5.92678 6.32322C5.97366 6.37011 6 6.4337 6 6.5C6 6.5663 5.97366 6.62989 5.92678 6.67678C5.87989 6.72366 5.81631 6.75 5.75 6.75H5.5V8.25H7C7.06631 8.25 7.12989 8.27634 7.17678 8.32322C7.22366 8.37011 7.25 8.4337 7.25 8.5V10H8.75V8.5C8.75 8.4337 8.77634 8.37011 8.82323 8.32322C8.87011 8.27634 8.9337 8.25 9 8.25H10.5V6.75H9C8.9337 6.75 8.87011 6.72366 8.82323 6.67678C8.77634 6.62989 8.75 6.5663 8.75 6.5V5H7.25V6.5C7.25 6.5663 7.22366 6.62989 7.17678 6.67678C7.12989 6.72366 7.06631 6.75 7 6.75H6.75C6.6837 6.75 6.62011 6.72366 6.57322 6.67678C6.52634 6.62989 6.5 6.5663 6.5 6.5C6.5 6.4337 6.52634 6.37011 6.57322 6.32322C6.62011 6.27634 6.6837 6.25 6.75 6.25V4.75C6.75 4.6837 6.77634 4.62011 6.82323 4.57322C6.87011 4.52634 6.9337 4.5 7 4.5H9C9.06631 4.5 9.1299 4.52634 9.17678 4.57322C9.22366 4.62011 9.25 4.6837 9.25 4.75V6.25H10.75C10.8163 6.25 10.8799 6.27634 10.9268 6.32322C10.9737 6.37011 11 6.4337 11 6.5V8.5Z"
            fill="url(#paint0_linear_30_152)"
          />
          <defs>
            <linearGradient
              id="paint0_linear_30_152"
              x1="8"
              y1="1.5"
              x2="8"
              y2="14.5"
              gradientUnits="userSpaceOnUse"
            >
              <stop stop-color="#DA4533" />
              <stop offset="1" stop-color="#CE3444" />
            </linearGradient>
          </defs>
        </svg>
        <a
          href="#0"
          className="text-gray-600 hover:text-gray-900 transition duration-150 ease-in-out pl-4"
          >Made with love in Switzerland</a
        >
      </div>
      <a
        href="#0"
        className="text-gray-600 hover:text-gray-900 transition duration-150 ease-in-out pl-4"
        >Terms</a
      >
    </div>
  </header>
</template>

<style scoped></style>
