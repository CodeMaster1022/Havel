<script setup>
import Logo from "./logo.vue";
import Hero from "./hero.vue";
import SearchBar from "./SerchBar.vue";
import Card from "./Card.vue";
import Footer from "./Footer.vue";
</script>

<template>
  <div class="">
    <div class="w-full bg-[url('./assets/background.png')] min-h-[93vh]">
      <div className="max-w-6xl mx-auto px-5">
        <div className="flex items-center justify-between h-16 md:h-20">
          <div className="shrink-0 flex">
            <Logo />
            <h1 class="text-xl font-semibold ml-6">Helvetia Staking</h1>
          </div>
        </div>
        <div class="h-[1px] w-full bg-white" />
        <div>
          <Hero />
          <SearchBar />
          <Card />
          <div class="mx-auto text-center pt-12">
            <a>Further information about Helvetia Staking</a>
          </div>
        </div>
      </div>
    </div>
    <Footer />
  </div>
</template>

<style lang="scss"></style>
