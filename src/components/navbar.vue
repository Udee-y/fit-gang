<template>
      <nav class="bg fixed w-full z-50" :class="{ scrolled: !view.atTopOfPage }">
        <div class="container px-6 py-4 mx-auto md:flex md:justify-between md:items-center">
            <div class="flex items-center justify-between">
                <div class="md:mx-6">
                    <a class="text-2xl font-bold  transition-colors duration-200 transform dark:text-white lg:text-3xl
                    hover:text-green-400 dark:hover:text-gray-300" href="#">Fit_<span>Gang</span>
                    </a>

                </div>
                <!-- Mobile menu button -->
                <div class="flex md:hidden">
                    <button type="button" class="text-black dark:text-gray-200 hover:text-gray-600
                    dark:hover:text-gray-400 focus:outline-none focus:text-gray-600 dark:focus:text-gray-400" aria-label="toggle menu"
                     @click="isMenuOpen = true">
                        <svg viewBox="0 0 24 24" class="w-6 h-6 fill-current">
                            <path fill-rule="evenodd" d="M4 5h16a1 1 0 0 1 0 2H4a1 1 0 1 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2z"></path>
                        </svg>
                    </button>
                </div>
            </div>

            <!-- Mobile Menu open: "block", Menu closed: "hidden" -->
            
            <div class="items-center md:flex">
                <div class=" hidden md:block md:flex-row md:mx-6">
                  <router-link to="/about">
                     <a class="my-1 text-sm font-medium  transition-colors duration-200 transform dark:text-gray-200
                      hover:text-green-400 dark:hover:text-blue-400 md:mx-4 md:my-0" href="#">About</a>
                  </router-link>
                    <a href="#" class="my-1 text-sm font-medium  transition-colors duration-200 transform dark:text-gray-200
                     hover:text-green-400
                     dark:hover:text-blue-400 md:mx-4 md:my-0">Contact</a>
                    <router-link to="/features">
                      <a class="my-1 text-sm font-medium  transition-colors duration-200 transform dark:text-gray-200
                     hover:text-green-400 dark:hover:text-blue-400 md:mx-4 md:my-0" href="#">Features</a>
                    </router-link>
                    <a class="my-1 text-sm font-medium  transition-colors duration-200 transform dark:text-gray-200 hover:text-green-400 dark:hover:text-blue-400 md:mx-4 md:my-0" href="#">Pricing</a>
                   <router-link to="/register">
                     <a class="my-1 text-sm font-medium  transition-colors duration-200 transform dark:text-gray-200
                     hover:text-green-400 dark:hover:text-blue-400 md:mx-4 md:my-0 
                    shadow-md bg-green-500 text-white py-2 px-3 rounded-md" href="#">signup</a>
                   </router-link>
                </div>
            </div>

            <div v-if="isMenuOpen" class="absolute top-0 left-0 w-full">
            <div class="p-5 bg-white border rounded shadow-sm">
              <div class="flex items-center justify-between mb-4">
                <div>
                  <button
                    aria-label="Close Menu"
                    title="Close Menu"
                    class="p-2 -mt-2 -mr-2 transition duration-200 rounded hover:bg-gray-200 focus:bg-gray-200 focus:outline-none focus:shadow-outline"
                    @click="isMenuOpen = false"
                  >
                    <svg class="w-5 text-white" viewBox="0 0 24 24">
                      <path
                        fill="currentColor"
                        d="M19.7,4.3c-0.4-0.4-1-0.4-1.4,0L12,10.6L5.7,4.3c-0.4-0.4-1-0.4-1.4,0s-0.4,1,0,1.4l6.3,6.3l-6.3,6.3 c-0.4,0.4-0.4,1,0,1.4C4.5,19.9,4.7,20,5,20s0.5-0.1,0.7-0.3l6.3-6.3l6.3,6.3c0.2,0.2,0.5,0.3,0.7,0.3s0.5-0.1,0.7-0.3 c0.4-0.4,0.4-1,0-1.4L13.4,12l6.3-6.3C20.1,5.3,20.1,4.7,19.7,4.3z"
                      ></path>
                    </svg>
                  </button>
                </div>
              </div>
              <div class="w-1/2 items-center mx-auto">
                <div class="flex flex-col mx-auto items-center text-center justify-center space-y-6">
                    <a class="my-1 text-sm font-medium  transition-colors duration-200 transform dark:text-gray-200 hover:text-green-400 dark:hover:text-blue-400 md:mx-4 md:my-0" href="#">About</a>
                    <a class="my-1 text-sm font-medium  transition-colors duration-200 transform dark:text-gray-200 hover:text-green-400 dark:hover:text-blue-400 md:mx-4 md:my-0" href="#">Contact</a>
                    <a class="my-1 text-sm font-medium  transition-colors duration-200 transform dark:text-gray-200 hover:text-green-400 dark:hover:text-blue-400 md:mx-4 md:my-0" href="#">Features</a>
                    <a class="my-1 text-sm font-medium  transition-colors duration-200 transform dark:text-gray-200 hover:text-green-400 dark:hover:text-blue-400 md:mx-4 md:my-0" href="#">Pricing</a>
                    <a class="my-1 text-sm font-medium  transition-colors duration-200 transform dark:text-gray-200 hover:text-green-400 dark:hover:text-blue-400 md:mx-4 md:my-0 shadow-md bg-green-500 text-white py-2 rounded-md w-1/2 mx-auto" href="#">signup</a>
                </div>
            </div>
            </div>
        </div>
        </div>
    </nav>
</template>
<script>
export default {
  name: 'Navbar',

  data () {
    return {
      isMenuOpen: false,
      view: {
        atTopOfPage: true
      }
    }
  },

  beforeMount () {
    window.addEventListener('scroll', this.handleScroll)
  },

  methods: {
    // the function to call when the user scrolls, added as a method
    handleScroll () {
      // when the user scrolls, check the pageYOffset
      if (window.pageYOffset > 0) {
        // user is scrolled
        if (this.view.atTopOfPage) this.view.atTopOfPage = false
      } else {
        // user is at top of page
        if (!this.view.atTopOfPage) this.view.atTopOfPage = true
      }
    }
  }
}
</script>
