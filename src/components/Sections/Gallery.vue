<template>
  <div
      class="
        w-full
        md:min-h-screen
        flex flex-col
        md:flex-row
        px-3
        md:px-6 md:py-24
        mt-5
      "
    >
      <div class="w-full md:w-1/4 px-6 md:min-h-screen">
        <div class="flex flex-col justify-between md:min-h-screen">
          <div class="">
            <div class="font-primary font-bold textcolor md:text-9xl text-2xl">
              Gallery
            </div>
          </div>
          <div
            class="
              font-primary font-bold
              textcolor
              text-1xl
              mt-3
              flex flex-row
              md:flex-col
              justify-center
              items-center
              gap-3
            "
          >
            <div>
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="h-5 w-5"
                viewBox="0 0 20 20"
                fill="currentColor"
              >
                <path
                  fill-rule="evenodd"
                  d="M14.707 12.707a1 1 0 01-1.414 0L10 9.414l-3.293 3.293a1 1 0 01-1.414-1.414l4-4a1 1 0 011.414 0l4 4a1 1 0 010 1.414z"
                  clip-rule="evenodd"
                />
              </svg>
            </div>
            <div class="text-sm md:text-xl">Street</div>
            <div class="text-lg md:text-3xl">Wildlife</div>
            <div class="text-sm md:text-xl">Abstract</div>
            <div>
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="h-5 w-5"
                viewBox="0 0 20 20"
                fill="currentColor"
              >
                <path
                  fill-rule="evenodd"
                  d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z"
                  clip-rule="evenodd"
                />
              </svg>
            </div>
          </div>
          <div
            class="
              hidden
              md:block
              font-primary font-bold
              textcolor
              md:text-1xl
              items-center
              text-sm
              italic
              md:pb-11
            "
          >
            View full gallery
          </div>
        </div>
      </div>
      <div class="w-full md:w-3/4 mt-4 md:min-h-screen">
        <div class="md:w-full md:h-screen md:py-11">
          <img
            class="md:h-full md:w-full object-cover"
            src="https://res.cloudinary.com/pranav1421/image/upload/v1648185514/Portfolio/Group_1466_e2sjsb.png"
            alt=""
          />
        </div>
      </div>
    </div>
</template>

<script>
export default {

}
</script>

<style>

</style>