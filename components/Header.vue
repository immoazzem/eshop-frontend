<template>
  <div class="container">
    <div class="row flex justify-between py-8">
      <Logo />

      <div class="w-96">
        <div class="border border-gray-200 rounded-full p-1 flex items-center">
          <div class="min-w-max px-3">
            <img src="~/assets/img/search.png" alt="" />
          </div>
          <input
            class="w-full px-3 py-1 focus:outline-none"
            type="search"
            name=""
            placeholder="search here"
            id=""
          />
          <button
            class="
              search-btn
              text-lg
              font-medium
              rounded-full
              px-4
              py-1
              text-white
            "
            type="submit"
          >
            Search
          </button>
        </div>
      </div>

      <div class="min-w-max flex items-center">
        <nuxt-link to="" class="">
          <span
            class="
              bs-user-icon
              hover:bg-gray-200
              rounded-full
              flex
              items-center
              justify-center
            "
            ><img src="~/assets/img/heart.png" alt=""
          /></span>
        </nuxt-link>
        <nuxt-link to="" class="relative">
          <span
            class="
              bs-user-icon
              hover:bg-gray-200
              rounded-full
              flex
              items-center
              justify-center
            "
            ><img src="~/assets/img/cart.png" alt="" /></span
          ><span
            class="
              absolute
              top-0
              right-0
              rounded-full
              w-6
              h-6
              bs-dark-orange
              text-white text-xs
              flex
              items-center
              justify-center
            "
            >0</span
          >
        </nuxt-link>
        <nuxt-link to="" class="flex items-center">
          <span
            class="
              bs-user-icon
              hover:bg-gray-200
              rounded-full
              flex
              items-center
              justify-center
            "
            ><img src="~/assets/img/user.png" alt="" /></span
          >Account
        </nuxt-link>
      </div>
    </div>
    <div class="row2 flex items-center">
      <div class="w-96">
        <div class="bs-green-2 flex rounded-full px-4 py-2 items-center cursor-pointer">
          <div class="min-w-max">
            <img src="~/assets/img/menu-right.png" class="" alt="" />
          </div>
          <div class="w-full text-white px-6 text-center font-medium font-medium">All Categories</div>
          <div class="min-w-max">
            <img src="~/assets/img/chevron-down.png" class="" alt="" />
          </div>
        </div>
      </div>
      <div class="w-full">
        <ul class="flex justify-center">
          <li><nuxt-link to="" class="px-4">Home</nuxt-link></li>
          <li><nuxt-link to="" class="px-4">Shop</nuxt-link></li>
          <li><nuxt-link to="" class="px-4">Categories</nuxt-link></li>
          <li><nuxt-link to="" class="px-4">Offer</nuxt-link></li>
          <li><nuxt-link to="" class="px-4">Contact</nuxt-link></li>
          <li><nuxt-link to="" class="px-4">About Us</nuxt-link></li>
          <li><nuxt-link to="" class="px-4">FAQs</nuxt-link></li>
        </ul>
      </div>
      <nuxt-link to="" class="min-w-max flex bs-dark-orange-color items-center">
        <img src="~/assets/img/perc.png" class="mr-3" alt="">Special Offers!
      </nuxt-link>
    </div>
  </div>
</template>

<script>
import Logo from './Logo.vue';
export default {
  components: { Logo },
  name: "Header",
};
</script>

<style>
</style>