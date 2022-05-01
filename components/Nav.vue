<template>
  <nav class="absolute top-10 right-1 p-2 text-sm">
    <div class="flex">
      <div>
        <span
          @click="$slidev.nav.prev"
          class="px-1 rounded cursor-pointer"
          hover="bg-white bg-opacity-20"
        >
          <kbd>&lt;-</kbd>
        </span>
        <SlideCurrentNo /> / <SlidesTotal />
        <span
          @click="$slidev.nav.next"
          class="px-1 rounded cursor-pointer"
          hover="bg-white bg-opacity-20"
        >
          <kbd>-></kbd>
        </span>
      </div>
    </div>
  </nav>
</template>
