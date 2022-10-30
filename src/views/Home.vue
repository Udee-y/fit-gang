<template>
  <!-- <div id="overlay"></div> -->
  <div class="bck-ground px-6 mx-auto overflow-hidden">
    <div
      class="text-white justify-center w-full hero bg-center items-center mx-auto xl:py-4 py-12 px-6 text-center"
    >
      <h1
        class="text-3xl xl:text-5xl text-center leading-snug font-bold xl:mt-0 mt-12"
      >
        Develop your body the<span class="text-green-500"> right</span> way
      </h1>
      <p class="text-xl mt-2 py-4 leading-6">
        Lorem, ipsum dolor sit amet consectetur adipisicing elit. Consectetur
        quibusdam vero,dolores.
      </p>
      <button
        class="text-center text-xl text-white mx-auto mt-4 py-3 px-6 hover:bg-green-400 rounded-md"
      >
        Get Started
      </button>
    </div>
  </div>

  <section>
    <div
      class="px-4 mt-20 mx-auto sm:max-w-xl md:max-w-full lg:max-w-screen-xl md:px-24 md:mb-12 lg:px-8 text-3xl xl:text-4xl"
    >
      <h2
        class="uppercase text-center py-2 mt-8 mb-16 font-medium text-gray-800"
      >
        Your fitness is our priority
      </h2>
    </div>
    <div class="flex flex-wrap overflow-hidden py-12 bg-gray-100">
      <div
        class="w-full flex justify-center 2xl:justify-start overflow-hidden sm:my-8 md:my-8 xl:my-4 xl:px-16 xl:w-1/2 px-6"
      >
        <img src="../assets/hero-2.jpg" alt="" />
      </div>
      <div
        class="w-full overflow-hidden xl:py-20 xl:pr-16 xl:px-4 xl:w-1/2 mt-8 px-6"
      >
        <h1
          class="font-semibold text-black text-2xl 2xl:text-5xl xl:text-3xl py-4 xl:text-left text-center"
        >
          Track your Fitness Journey on a Single Platform
        </h1>
        <p class="text-xl justify-center mt-4 xl:text-left">
          At
          <span :style="{ color: '#42b983' }" class="text-2xl font-bold"
            >Fit_Gang</span
          >
          we help you discover the right workout techniques that will suit your
          body type. we help you set monthly fitness goals and we help you
          achieve them through our flexible work out schedules and professional
          instructors.
        </p>
      </div>
    </div>
  </section>

  <!-- NEXT SECTION -->

  <section>
    <div class="flex flex-wrap overflow-hidden py-12 mt-8">
      <div class="w-full overflow-hidden xl:my-12 xl:w-1/2 xl:px-12 px-6">
        <h1 class="font-semibold text-black text-2xl 2xl:text-4xl xl:px-4 py-8">
          Keeping Fit Shouldn't be So Difficult. We've Got You Covered.
        </h1>
        <p class="text-xl xl:px-6">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Ratione fuga
          exercitationem aut suscipit doloremque eos voluptas deserunt beatae,
        </p>
      </div>
      <div
        class="w-full flex 2xl:justify-end overflow-hidden sm:my-8 md:my-8 xl:my-4 xl:pr-20 xl:w-1/2 px-6 xl:px-0 mt-4"
      >
        <img src="../assets/hero-1.jpg" alt="" />
      </div>
    </div>
  </section>

  <!-- Next Section  -->
  <section class="bg-gray-100 mt-8">
    <div class="px-6 xl:py-12 xl:flex mx-auto justify-between xl:px-12">
      <div>
        <h3
          class="text-center font-semibold uppercase px-8 text-2xl xl:py-12 py-8 mt-24"
          :style="{ color: '#42b983' }"
        >
          Begin Your Journey Now
        </h3>
      </div>
      <div class="flex flex-col xl:px-12 xl:py-8 mt-2">
        <p class="xl:my-6 text-xl text-center xl:text-left mb-3">
          Get Acces to all Our Latest Informations, Workout Plans and Daily
          Offers
        </p>
        <form action="" class="text-center">
          <input
          type="text"
          name="first-name"
          id=""
          placeholder="First Name"
          class="border my-2 mx-auto rndoued-md rounded-full xl:w-3/4
           py-3 px-4 w-full focus:outline-none focus:border-green-500"
        />
        <input
          type="text"
          name="last-name"
          id=""
          placeholder="Last Name"
          class="my-4 border rounded-full py-3 px-4 mx-auto xl:w-3/4 w-full focus:outline-none focus:border-green-500"
        />
        <input
          type="email"
          name="email-address"
          id=""
          placeholder="Your Email Address"
          class="border rounded-lg shadow-md my-2 py-3 px-4 mx-auto xl:w-3/4 w-full focus:outline-none focus:border-green-500"
        />
        <button
          type="submit"
          class="block submit mx-auto rounded-md border py-3 px-10 mt-4 mb-8 xl:mb-0 shadow-md text-white"
        >
          Submit
        </button>
        </form>
      </div>
    </div>
  </section>

  <!-- NEXT SECTION -->
  <section class="text-gray-600 body-font">
    <div class="container px-6 xl:px-14 py-24 mx-auto">
      <div class="flex flex-wrap w-full mb-20">
        <div class="lg:w-1/2 w-full mb-6 lg:mb-0">
          <h1
            class="sm:text-3xl text-2xl font-medium title-font mb-2 text-gray-900"
          >
            Workout Programms
          </h1>
          <div class="h-1 w-20 bg-green-500 rounded"></div>
        </div>
        <p class="lg:w-1/2 w-full leading-relaxed text-gray-500">
          Whatever cardigan tote bag tumblr hexagon brooklyn asymmetrical
          gentrify, subway tile poke farm-to-table. Franzen you probably haven't
          heard of them man bun deep jianbing selfies heirloom prism food truck
          ugh squid celiac humblebrag.
        </p>
      </div>
      <div class="flex flex-wrap -m-3">
        <div class="xl:w-1/3 md:w-1/2 p-4">
          <div class="bg-gray-100 p-6 rounded-lg relative">
            <img
              class="rounded w-full object-cover object-center relative"
              src="../assets/cagin-kargi-Qzp60FT380E-unsplash.jpg"
              alt="content"
            />
            <a href="#"
              ><button
                class="text-white uppercase text-sm w-3/4 py-3 px-4 link"
              >
                Body building
              </button></a
            >
          </div>
        </div>
        <div class="xl:w-1/3 md:w-1/2 p-4">
          <div class="bg-gray-100 p-6 rounded-lg relative">
            <img
              class="rounded w-full object-cover h-96 object-center relative"
              src="../assets/weights.jpg"
              alt="content"
            />
            <a href="#" 
              ><button
                class="text-white uppercase  text-sm w-3/4 py-3 px-4 link"
              >
                Weight Loss / gain
              </button></a
            >
          </div>
        </div>
        <div class="xl:w-1/3 md:w-1/2 p-4">
          <div class="bg-gray-100 p-6 rounded-lg relative">
            <img
              class="rounded w-full object-cover object-center relative"
              src="../assets/tangerine-newt-N0Ai_Hc5s0I-unsplash.jpg"
              alt="content"
            />
            <a href="#"
              ><button
                class="text-white uppercase text-sm w-3/4 py-3 px-4 link"
              >
                Nutrition
              </button></a
            >
          </div>
        </div>
      </div>
    </div>
  </section>


  <!-- Why choose us section -->
  <section>
    <div
      class="px-4 mx-auto sm:max-w-xl md:max-w-full lg:max-w-screen-xl md:px-24 lg:px-8 lg:py-8"
    >
      <div
        class="max-w-xl mb-10 md:mx-auto sm:text-center lg:max-w-2xl md:mb-12"
      >
        <h2
          class="max-w-lg mb-6 font-sans text-3xl font-bold leading-none tracking-tight text-gray-900 sm:text-4xl md:mx-auto"
        >
          Why<span :style="{ color: '#42b983' }"> Choose</span> us
        </h2>
        <p class="text-base text-gray-700 md:text-lg">
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque rem aperiam, eaque ipsa quae.
        </p>
      </div>
      <div class="grid gap-8 row-gap-8 lg:grid-cols-3">
        <div class="sm:text-center">
          <div
            class="flex items-center justify-center w-16 h-16 mb-4 rounded-full bg-green-50 sm:mx-auto sm:w-24 sm:h-24"
          >
            <img
              src="../assets/dumbbell.png"
              class="w-16 h-16 text-deep-purple-accent-400 sm:w-20 sm:h-20"
            />
          </div>
          <h6 class="mb-2 font-semibold leading-5">Free Training</h6>
          <p class="max-w-md mb-3 text-sm text-gray-900 sm:mx-auto">
            Cheese on toast airedale the big cheese. Danish fontina cheesy grin
            airedale danish
          </p>
          <a
            href="/"
            aria-label=""
            class="inline-flex items-center font-semibold transition-colors duration-200 text-deep-purple-accent-400 hover:text-deep-purple-800"
            >Learn more</a
          >
        </div>
        <div class="sm:text-center">
          <div
            class="flex items-center justify-center w-16 h-16 mb-4 rounded-full bg-green-50 sm:mx-auto sm:w-24 sm:h-24"
          >
            <img
              src="../assets/low-cost.png"
              class="w-16 h-16 sm:w-20 sm:h-20"
            />
          </div>
          <h6 class="mb-2 font-semibold leading-5">Affordable Prices</h6>
          <p class="max-w-md mb-3 text-sm text-gray-900 sm:mx-auto">
            Satoshi Nakamoto launched lots of decentralisation when Litecoin
            required
          </p>
          <a
            href="/"
            aria-label=""
            class="inline-flex items-center font-semibold transition-colors duration-200 text-deep-purple-accent-400 hover:text-deep-purple-800"
            >Learn more</a
          >
        </div>
        <div class="sm:text-center">
          <div
            class="flex items-center justify-center w-16 h-16 mb-4 rounded-full bg-green-50 sm:mx-auto sm:w-24 sm:h-24"
          >
            <img
              src="../assets/schedule.png"
              class="w-14 h-14 text-deep-purple-accent-400 sm:w-16 sm:h-16"
            />
          </div>
          <h6 class="mb-2 font-semibold leading-5">Personalized schedules</h6>
          <p class="max-w-md mb-3 text-sm text-gray-900 sm:mx-auto">
            Bavaria ipsum dolor sit amet Radler Schneid vui huift vui ognudelt i
            mechad
          </p>
          <a
            href="/"
            aria-label=""
            class="inline-flex items-center font-semibold transition-colors duration-200 text-deep-purple-accent-400 hover:text-deep-purple-800"
            >Learn more</a
          >
        </div>
      </div>
    </div>
  </section>

  <!-- pricings -->
<section id="price">
  <div class="bg-white dark:bg-gray-900 lg:pt-16" >
    <div class="container px-6 py-8 md:px-16 mx-auto">
      <h1
        class="text-3xl font-semibold text-center text-gray-800 capitalize lg:text-4xl dark:text-white"
      >
        Pricing Plan
      </h1>

      <p
        class="max-w-2xl mx-auto mt-4 text-center text-gray-500 xl:mt-6 dark:text-gray-300"
      >
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Alias quas
        magni libero consequuntur voluptatum velit amet id repudiandae ea,
        deleniti laborum in neque eveniet.
      </p>

      <div
        class="grid grid-cols-1 gap-8 mt-6 xl:mt-12 xl:gap-12 md:grid-cols-2 lg:grid-cols-3"
      >
        <div
          class="w-full p-8 space-y-8 text-center border border-gray-200 rounded-lg dark:border-gray-700"
        >
          <p class="font-medium text-gray-500 uppercase dark:text-gray-300">
            Free
          </p>

          <h2
            class="text-5xl font-bold text-gray-800 uppercase dark:text-gray-100"
          >
            $0
          </h2>

          <p class="font-medium text-gray-500 dark:text-gray-300">Life time</p>

          <button
            class="w-full px-4 py-2 mt-10 tracking-wide text-white capitalize transition-colors duration-200 transform rounded-md
             hover:bg-green-700 focus:outline-none focus:ring
              focus:ring-green-100 focus:ring-opacity-80"
          >
            Start Now
          </button>
        </div>

        <div
          class="w-full p-8 space-y-8 text-center rounded-lg"
          :style="{ backgroundColor: '#42b983' }"
        >
          <p class="font-medium text-white uppercase">Premium</p>

          <h2
            class="text-5xl font-bold text-white uppercase dark:text-gray-100"
          >
            $40
          </h2>

          <p class="font-medium text-white">Per month</p>

          <button
            class="w-full px-4 py-2 mt-10 tracking-wide text-green-500 capitalize transition-colors duration-200
             transform rounded-md bg-white  focus:outline-none focus:ring
              focus:ring-green-100 focus:ring-opacity-80"
          >
            Start Now
          </button>
        </div>

        <div
          class="w-full p-8 space-y-8 text-center border border-gray-200 rounded-lg dark:border-gray-700"
        >
          <p class="font-medium text-gray-500 uppercase dark:text-gray-300">
            Enterprise
          </p>

          <h2
            class="text-5xl font-bold text-gray-800 uppercase dark:text-gray-100"
          >
            $100
          </h2>

          <p class="font-medium text-gray-500 dark:text-gray-300">Life time</p>

          <button
            class="w-full px-4 py-2 mt-10 tracking-wide text-white capitalize transition-colors duration-200 transform rounded-md
             hover:bg-green-700 focus:ring
              focus:ring-green-100 focus:ring-opacity-80"
          >
            Start Now
          </button>
        </div>
      </div>
    </div>
  </div>
</section>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<style>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
</style>
