<template>
  <div class="flex flex-col min-h-screen bg-primary justify-around ">
    <Navigation class="ml-5 mt-5"></Navigation>
    <div class="flex flex-col grow  self-center
                text-6xl w-full justify-around ">
<!--      block avec mes informations     -->
        <div class=" w-2/3 text-secondary self-center flex flex-col ">
          <p class=" text-8xl ">Antoine JEAN</p>
          <div>
            <p class=" px-4 text-secondary/25 inline-block ">Developpeur</p>
            <p class=" px-4 text-secondary/60 inline-block ">Full stack</p>
          </div>


          <!--      Block de description -->
          <div class="text-xl italic w-2/3 text-secondary/60 mt-12 self-center">
            Description : "Lorem ipsum dolor sit ametiqua. on ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."
          </div>
        </div>


        <div class="self-center mt-10">
          <svg class="rotate-180 w-20 h-20 stroke-2 hover:animate-pulse"
               width="28" height="28" viewBox="0 0 28 28"  fill="none" xmlns="http://www.w3.org/2000/svg">
            <path fill-rule="evenodd" clip-rule="evenodd" d="M26.25 14C26.25 10.7511 24.9594 7.63526 22.6621 5.33794C20.3647 3.04062 17.2489 1.75 14 1.75C10.7511 1.75 7.63526 3.04062 5.33794 5.33794C3.04062 7.63526 1.75 10.7511 1.75 14C1.75 17.2489 3.04062 20.3647 5.33794 22.6621C7.63526 24.9594 10.7511 26.25 14 26.25C17.2489 26.25 20.3647 24.9594 22.6621 22.6621C24.9594 20.3647 26.25 17.2489 26.25 14V14ZM0 14C0 10.287 1.475 6.72601 4.1005 4.1005C6.72601 1.475 10.287 0 14 0C17.713 0 21.274 1.475 23.8995 4.1005C26.525 6.72601 28 10.287 28 14C28 17.713 26.525 21.274 23.8995 23.8995C21.274 26.525 17.713 28 14 28C10.287 28 6.72601 26.525 4.1005 23.8995C1.475 21.274 0 17.713 0 14V14ZM13.125 20.125C13.125 20.3571 13.2172 20.5796 13.3813 20.7437C13.5454 20.9078 13.7679 21 14 21C14.2321 21 14.4546 20.9078 14.6187 20.7437C14.7828 20.5796 14.875 20.3571 14.875 20.125V9.98725L18.6305 13.7445C18.7948 13.9088 19.0176 14.0011 19.25 14.0011C19.4824 14.0011 19.7052 13.9088 19.8695 13.7445C20.0338 13.5802 20.1261 13.3574 20.1261 13.125C20.1261 12.8926 20.0338 12.6698 19.8695 12.5055L14.6195 7.2555C14.5382 7.17401 14.4417 7.10936 14.3354 7.06525C14.2291 7.02114 14.1151 6.99844 14 6.99844C13.8849 6.99844 13.7709 7.02114 13.6646 7.06525C13.5583 7.10936 13.4618 7.17401 13.3805 7.2555L8.1305 12.5055C7.9662 12.6698 7.8739 12.8926 7.8739 13.125C7.8739 13.3574 7.9662 13.5802 8.1305 13.7445C8.2948 13.9088 8.51764 14.0011 8.75 14.0011C8.98236 14.0011 9.2052 13.9088 9.3695 13.7445L13.125 9.98725V20.125Z" fill="black"/>
          </svg>
        </div>
    </div>
  </div>
</template>

<script>
import Navigation from "./Navigation.vue";

export default {
  name: "HeaderComponent",
  components:{
    Navigation
  }
}
</script>

<style scoped>

</style>