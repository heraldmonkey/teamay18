<script setup>
import Header from "@/examples/Header.vue";
</script>
<template>
  <Header>
    <div
      class="page-header align-items-start min-vh-100"
      :style="{
        backgroundImage: 'url(/applepark.jpg)',
        backgroundPosition: 'center center',
      }"
      loading="lazy"
    >
      <span class="mask bg-gradient-primary opacity-5"></span>
      <div
        class="container my-auto d-flex align-items-center justify-content-center"
      >
        <img src="/am18.svg" class="col-6 col-lg-4" alt="" />
      </div>
    </div>
  </Header>
</template>
