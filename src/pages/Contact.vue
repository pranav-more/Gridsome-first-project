<template>
<div>
       <Custom-layout>
   <div class="p-6 mt-4 flex flex-row backgroundhero">
      <div class="w-full md:w-1/2">
        <div class="font-primary font-bold textcolor md:text-9xl text-3xl">
          Contact
        </div>
        <div>
            Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic
        </div>
        <form class="w-full">
          <div class="flex flex-wrap -mx-3 mb-6">
            <div class="w-full md:w-1/2 px-3 mb-6 md:mb-0">
              <label
                class="
                  block
                  uppercase
                  tracking-wide
                  textcolor
                  text-xs
                  font-bold
                  mb-2
                "
              >
                First Name
              </label>
              <input
                class="
                  appearance-none
                  block
                  w-full
                  text-xs
                  textcolor
                  border border-red-500
                  rounded
                  py-2
                  md:py-3
                  px-4
                  mb-3
                  leading-tight
                  focus:outline-none focus:bg-white
                "
                id="grid-first-name"
                type="text"
                placeholder="Jane"
              />
              <p class="text-red-500 text-xxs italic">
                Please fill out this field.
              </p>
            </div>
            <div class="w-full md:w-1/2 px-3">
              <label
                class="
                  block
                  uppercase
                  tracking-wide
                  textcolor
                  text-xs
                  font-bold
                  mb-2
                "
                for="grid-last-name"
              >
                Last Name
              </label>
              <input
                class="
                  appearance-none
                  block
                  w-full
                  textcolor
                  border
                  text-xs
                  border-gray-200
                  rounded
                  py-2
                  md:py-3
                  px-4
                  leading-tight
                  focus:outline-none focus:bg-white focus:border-gray-500
                "
                id="grid-last-name"
                type="text"
                placeholder="Doe"
              />
            </div>
          </div>
          <div class="flex flex-wrap -mx-3 mb-6">
            <div class="w-full px-3">
              <label
                class="
                  block
                  uppercase
                  tracking-wide
                  textcolor
                  text-xs
                  font-bold
                  mb-2
                "
                for="grid-password"
              >
                E-mail
              </label>
              <input
                class="
                  appearance-none
                  block
                  w-full
                  textcolor
                  border border-gray-200
                  rounded
                  py-2
                  md:py-3
                  px-4
                  mb-3
                  leading-tight
                  focus:outline-none focus:bg-white focus:border-gray-500
                "
                id="email"
                type="email"
              />
            </div>
          </div>
          <div class="flex flex-wrap -mx-3 mb-6">
            <div class="w-full px-3">
              <label
                class="
                  block
                  uppercase
                  tracking-wide
                  textcolor
                  text-xs
                  font-bold
                  mb-2
                "
                for="grid-password"
              >
                Message
              </label>
              <textarea
                class="
                  no-resize
                  appearance-none
                  block
                  w-full
                  textcolor
                  border border-gray-200
                  rounded
                  py-2
                  md:py-3
                  px-4
                  mb-3
                  leading-tight
                  focus:outline-none focus:bg-white focus:border-gray-500
                  h-20
                  md:h-48
                  resize-none
                "
                id="message"
              ></textarea>
            </div>
          </div>
          <div class="md:flex md:items-center">
            <div class="md:w-1/3">
              <button
                class="
                  shadow
                  backgroundtext
                  hover:backgroundhero
                  text-white
                  font-bold
                  text-sm
                  md:text-lg
                  py-2
                  px-4
                  rounded
                "
                type="button"
              >
                Send
              </button>
            </div>
            <div class="md:w-2/3"></div>
          </div>
        </form>
      </div>
    </div>
      </Custom-layout>
    </div>
</template>

<script>
import CustomLayout from '../layouts/CustomLayout.vue'
export default {
  components: { CustomLayout },

}
</script>

<style>

</style>