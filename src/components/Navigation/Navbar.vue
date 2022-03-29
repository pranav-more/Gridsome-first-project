<template>
  <div>
    <nav class="w-full fixed top-0 z-40">
      <div class="w-full h-16 bg-white">
        <div class="flex justify-between h-full px-3 md:px-6">
          <div class="flex items-center justify-center h-full textcolor">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="h-6 w-6"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
              stroke-width="2"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M3 9a2 2 0 012-2h.93a2 2 0 001.664-.89l.812-1.22A2 2 0 0110.07 4h3.86a2 2 0 011.664.89l.812 1.22A2 2 0 0018.07 7H19a2 2 0 012 2v9a2 2 0 01-2 2H5a2 2 0 01-2-2V9z"
              />
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M15 13a3 3 0 11-6 0 3 3 0 016 0z"
              />
            </svg>
          </div>
          <!-- logo end -->
          <!-- desktop wala nav items-->
          <div class="hidden md:block">
            <div class="flex gap-6 justify-center items-center h-full textcolor text-lg font-semibold">
              <div>
                <g-link to="/">
                  Home
                </g-link>
              </div>
              <div>About</div>
              <div>
                <g-link to="/Gallery">
                Gallery
                </g-link>
                </div>
              <div>
              <g-link to="/Contact">Contact</g-link>
            </div>
            </div>
          </div>
          <!-- hamburger start -->
          <div class="block md:hidden">
            <div class="flex items-center justify-center h-full">
              <span v-if="!isopen">
                <svg
                  @click="isopen = true"
                  xmlns="http://www.w3.org/2000/svg"
                  class="h-6 w-6 textcolor"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                  stroke-width="2"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    d="M4 6h16M4 12h16M4 18h16"
                  />
                </svg>
              </span>
              <span v-else>
                <svg
                  @click="isopen = false"
                  xmlns="http://www.w3.org/2000/svg"
                  class="h-6 w-6 textcolor"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                  stroke-width="2"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    d="M6 18L18 6M6 6l12 12"
                  />
                </svg>
              </span>
            </div>
          </div>
          <!-- hamburger end -->
        </div>
        <!--  mobile nav items -->
        <div
          v-if="isopen"
          class="block md:hidden w-full h-screen overflow-y-auto backgroundhero"
        >
          <div
            class="
              flex flex-col
              h-screen
              w-full
              justify-center
              items-center
              -mt-16
              gap-3
              text-xl
              textcolor
              font-semibold
            "
          >
            <div>
              <g-link to="/">
                Home
              </g-link>
            </div>
            <div>About</div>
            <div>
                <g-link to="/Gallery">
                Gallery
                </g-link>
                </div>
            <div>
              <g-link to="/Contact">Contact</g-link>
            </div>
          </div>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  data() {
    return {
      isopen: false,
    };
  },
};
</script>

<style></style>
