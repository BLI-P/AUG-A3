<script>
export default {
  props: ['classes'],
}
</script>

<template>
  <main style = "background-image : url('../wallpaper.svg'); background-repeat : no-repeat; background-size : cover;" class="min-h-screen text-gray-900">
    <div :class="`mx-auto max-w-screen-md w-[90%] ${classes}`">
      <slot></slot>
    </div>
  </main>
</template>
