<template>
  <div class="flex justify-self-center
              w-5/6 m-auto mt-20
              bg-secondary bg-repeat shadow-inner
              border-solid border-4 rounded-xl ">
    <div class="flex place-items-center this.cssDirection
                hover:border-solid rounded-l hover:border-action hover:border-4 bg-secondary hover:rounded-xl
                hover:-translate-y-4 hover:-translate-x-4 duration-150 overflow-hidden">
      <div class="w-7/12 mx-4">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
        Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
        Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
        Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
      </div>
      <img src="/public/logo_competence/TailwindCSS_logo.png" alt="">
    </div>
  </div>
</template>

<script>
export default {
  name: "Description-Projet",
  props: {
    changeBaseDirection: {
      type: Boolean,
      default: false
    }
  },
  computed: {
    cssDirection: function () {
      if (this.changeBaseDirection) {
        return "flex-row-reverse"
      }
      return "flex-row"
    },
  },
}
</script>

<style scoped>

</style>