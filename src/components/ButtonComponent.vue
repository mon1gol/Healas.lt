<template>
  <button class="text-white bg-grad h-12.5 w-45 rounded-[25px] cursor-pointer">
    {{ text }}
  </button>
</template>

<script>
export default {
  name: "ButtonComponent",
  props:{
    text: String
  },
}
</script>

<style>
  .bg-grad{
    background-image: linear-gradient(90deg, #4499d9 50%, #7367be 100%);
    background-size: 200% auto;
    background-position: right center;
    transition: all 0.5s ease;
  }

  .bg-grad:hover {
    background-position: left center;
    box-shadow: 0 3px 10px rgba(0, 0, 0, 0.2);
  }
</style>
