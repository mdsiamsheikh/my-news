<template>
  <section class="body-section w-[1099px] m-auto">
    <div
      class="container main_wbsite bg-[#ffffff] pr-[15px] pl-[15px] mr-auto ml-auto text-[17px]"
    >
      <home-navbar></home-navbar>
      <slot></slot>
      <footer-section></footer-section>
    </div>
  </section>
</template>

<script setup></script>

<style scoped>
.body-section {
  font-family: SolaimanLipiNormal;
  line-height: 1.42857143;
  box-sizing: border-box;
}

.main_wbsite {
  box-shadow: 0 0 20px #ddd;
  line-height: 1.42857143;
}
</style>
