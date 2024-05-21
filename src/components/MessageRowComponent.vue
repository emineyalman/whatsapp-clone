<template>
    <div>
      <div class="flex w-full px-4 py-3 items-center cursor-pointer">
        <img
          src="https://picsum.photos/100/100"
          class="rounded-full ml-1 w-10"
          alt=""
        />
        <div class="w-full">
          <div class="flex justify-between items-center">
            <div class="text-[15px] text-gray-600">Emine</div>
            <div class="text-[12px] text-gray-600">Date</div>
          </div>
          <div class="flex items-center mt-1">
            <CheckAllIcon :size="18" class="mr-1" />
            <div class="text-[15px] w-full text-gray-500">This is message..</div>
          </div>
        </div>
      </div>
      <div class="border-b w-[calc(100%-80px)] float-right"></div>
    </div>
  </template>
  
  <script setup>
  import CheckAllIcon from "vue-material-design-icons/CheckAll.vue";
  </script>
  
  <style lang="scss" scoped>
  </style>
  