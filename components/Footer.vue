<template>
  <div>
    <div class="container mb-12">
      <div class="row flex -mx-4">
        <div class="w-1/4 px-4 flex items-center">
          <div class="min-w-max mr-5">
            <img class="w-20" src="~/assets/img/call-center.png" alt="" />
          </div>
          <div class="w-full">
            <h4 class="font-medium text-xl mb-2">24 Customer Support</h4>
            <p class="Contact us 24 hours text-base text-gray-500">
              Contact us 24 hours
            </p>
          </div>
        </div>
        <div class="w-1/4 px-4 flex items-center">
          <div class="min-w-max mr-5">
            <img class="w-20" src="~/assets/img/product.png" alt="" />
          </div>
          <div class="w-full">
            <h4 class="font-medium text-xl mb-2">Authentic Products</h4>
            <p class="Contact us 24 hours text-base text-gray-500">
              Contact us 24 hours
            </p>
          </div>
        </div>
        <div class="w-1/4 px-4 flex items-center">
          <div class="min-w-max mr-5">
            <img class="w-20" src="~/assets/img/secure-payment.png" alt="" />
          </div>
          <div class="w-full">
            <h4 class="font-medium text-xl mb-2">Secure Payment</h4>
            <p class="Contact us 24 hours text-base text-gray-500">
              Contact us 24 hours
            </p>
          </div>
        </div>
        <div class="w-1/4 px-4 flex items-center">
          <div class="min-w-max mr-5">
            <img class="w-20" src="~/assets/img/best-price.png" alt="" />
          </div>
          <div class="w-full">
            <h4 class="font-medium text-xl mb-2">Best Prices & Offers</h4>
            <p class="Contact us 24 hours text-base text-gray-500">
              Contact us 24 hours
            </p>
          </div>
        </div>
      </div>
    </div>
    <div class="bg-gray-100 py-20">
      <div class="container">
        <div class="flex items-center justify-between">
          <div class="w-3/5 pr-16">
            <Logo />
            <p class="my-10">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla
              diam ornare nam est gravida. Netus viverra rhoncus sit magna
              sapien ac eget parturient id. Est luctus dapibus quam aliquam in
              nisl turpis. Elit et dictum lacus morbi nec accumsan a in.
            </p>
            <div class="flex">
              <a class="mr-4" href=""
                ><img src="~/assets/img/apple-store-badge.png" alt=""
              /></a>
              <a href=""
                ><img src="~/assets/img/play-store-badge.png" alt=""
              /></a>
            </div>
          </div>
          <div class="w-1/5 pl-6">
            <h4 class="text-xl font-normal mb-6">About Us</h4>
            <ul class="">
              <li class="mb-5 text-sm font-normal">
                <nuxt-link to="">Contact</nuxt-link>
              </li>
              <li class="mb-5 text-sm font-normal">
                <nuxt-link to="">Carrer</nuxt-link>
              </li>
              <li class="mb-5 text-sm font-normal">
                <nuxt-link to="">Terms & Conditions</nuxt-link>
              </li>
              <li class="mb-5 text-sm font-normal">
                <nuxt-link to="">Category</nuxt-link>
              </li>
              <li class="mb-5 text-sm font-normal">
                <nuxt-link to="">Contact</nuxt-link>
              </li>
            </ul>
          </div>
          <div class="w-1/5 pl-6">
            <h4 class="text-xl font-normal mb-6">Info</h4>
            <ul class="">
              <li class="mb-5 text-sm font-normal">
                <nuxt-link to="">Information</nuxt-link>
              </li>
              <li class="mb-5 text-sm font-normal">
                <nuxt-link to="">Shipping</nuxt-link>
              </li>
              <li class="mb-5 text-sm font-normal">
                <nuxt-link to="">Payment</nuxt-link>
              </li>
              <li class="mb-5 text-sm font-normal">
                <nuxt-link to="">Return Policy</nuxt-link>
              </li>
              <li class="mb-5 text-sm font-normal">
                <nuxt-link to="">Blog</nuxt-link>
              </li>
            </ul>
          </div>
        </div>
        <div class="flex mt-24">
          <div class="min-w-max flex">
            <div class="relative mr-4">
              <div
                class="
                  w-14
                  h-14
                  rounded-xl
                  bs-dark-orange
                  flex
                  items-center
                  justify-center
                  hover:bg-blue-900
                "
              >
                <img class="" src="~/assets/img/fb.png" alt="" />
              </div>
            </div>
            <div class="relative mr-4">
              <div
                class="
                  w-14
                  h-14
                  rounded-xl
                  flex
                  items-center
                  justify-center
                  hover:bg-blue-900
                "
              >
                <img class="" src="~/assets/img/instagram.png" alt="" />
              </div>
            </div>
            <div class="relative mr-4">
              <div
                class="
                  w-14
                  h-14
                  rounded-xl
                  flex
                  items-center
                  justify-center
                  hover:bg-blue-900
                "
              >
                <img class="" src="~/assets/img/twitter.png" alt="" />
              </div>
            </div>
            <div class="relative">
              <div
                class="
                  w-14
                  h-14
                  rounded-xl
                  flex
                  items-center
                  justify-center
                  hover:bg-blue-900
                "
              >
                <img class="" src="~/assets/img/skype.png" alt="" />
              </div>
            </div>
          </div>
          <div class="w-full text-center">
            <p class="text-base font-medium">
              @2022 Copyright All Right Reserved by Moazzem
            </p>
          </div>
          <div class="min-w-max">
            <img src="~/assets/img/pg-logos.png" alt="" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Logo from "./Logo.vue";
export default {
  components: { Logo },
  name: "Footer",
};
</script>

<style>
</style>