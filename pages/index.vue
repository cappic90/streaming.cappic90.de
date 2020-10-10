<template>
  <div class="relative w-screen h-screen overflow-hidden">
    <div class="w-3/4 absolute h-screen night-sky-bg">
      <div class="h-full night-sky-bg__content flex flex-col">
        <div class="flex-1 w-full flex items-center justify-center">
          <TextblockGleich>los!</TextblockGleich>
        </div>
        <div class="flex-1 w-full flex items-center justify-center">
          <SocialMedia />
        </div>
      </div>
    </div>
    <div class="w-screen h-screen bg-gray-100">
      <div class="w-1/2 h-full ml-auto flex flex-col">
        <div class="flex-1 flex items-center">
          <Cat class="mx-auto" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>
