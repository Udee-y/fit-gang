<template>
  <navbar></navbar>
  <div class="about">
    <div class="py-24 width mx-auto">
      <h1 class="text-white text-7xl text-center mt-20 pt-8">
        About <span :style="{ color: '#42b983' }">Fit_Gang</span>
      </h1>
    </div>
  </div>
  <div class="width mx-auto mt-8 ">
    <h3 class="py-4 uppercase text-2xl font-semibold">Our mission</h3>
    <p class="text-lg font-medium">Due to the high number of people living with health issues resulting from 
      underweight or overweight, we at <span class="text-xl font-semibold" :style="{ color: '#42b983' }">Fit-Gang</span>
    have developed a system to help you stay healthy at your own convinience.
    Our mission is to provide adequate facilities and the right conditions to help you achieve your desired body weight and 
    live a longer and healthier life. </p>
  </div>
<!-- SERVICES -->
<div class="width mx-auto mt-8">
  <h1 class="text-2xl font-semibold uppercase py-4">Services</h1>
  <p class="text-lg font-medium">Lorem ipsum dolor sit amet consectetur adipisicing elit. Recusandae quibusdam exercitationem necessitatibus quas, 
    optio officia voluptatibus non distinctio,
     quos quae iure rem hic natus perferendis, minima dignissimos? Itaque, incidunt fuga!</p>
     <div class="flex flex-wrap -m-3 mt-6">
        <div class="xl:w-1/4 md:w-1/2 p-4">
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
        <div class="xl:w-1/4 md:w-1/2 p-4">
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
                Weight Loss / gain
              </button></a
            >
          </div>
        </div>
        <div class="xl:w-1/4 md:w-1/2 p-4">
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
                Nutrition
              </button></a
            >
          </div>
        </div>
         <div class="xl:w-1/4 md:w-1/2 p-4">
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
                Nutrition
              </button></a
            >
          </div>
        </div>
      </div>
</div>
<!-- OUR PARTNERS -->
<!-- MEET OUR TEAM -->
<section class="bg-white dark:bg-gray-900">
            <div class="container px-8 py-10 mx-auto">
                <div class="xl:flex xl:items-center xL:-mx-4">
                    <div class="xl:w-1/2 xl:mx-4">
                        <h1 class="text-2xl font-semibold text-gray-800 capitalize lg:text-3xl dark:text-white">Our Team</h1>
                        
                        <p class="max-w-2xl mt-4 text-gray-500 dark:text-gray-300">
                        Our team of highly trained industry experts are well suited to meet every of your fitness needs.
                        </p>
                    </div>
                    
                    <div class="grid grid-cols-1 gap-8 mt-8 xl:mt-0 xl:mx-4 xl:w-1/2 md:grid-cols-2">
                        <div>
                            <img class="object-cover rounded-xl aspect-square" src="https://images.unsplash.com/photo-1570295999919-56ceb5ecca61?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=880&q=80" alt="">
                            
                            <h1 class="mt-4 text-2xl font-semibold text-gray-700 capitalize dark:text-white">John Doe</h1>
                            
                            <p class="mt-2 text-gray-500 capitalize dark:text-gray-300">Nutritionist</p>
                        </div>

                        <div>
                            <img class="object-cover rounded-xl aspect-square" src="https://images.unsplash.com/photo-1499470932971-a90681ce8530?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1470&q=80" alt="">
                            
                            <h1 class="mt-4 text-2xl font-semibold text-gray-700 capitalize dark:text-white">Mia</h1>
                            
                            <p class="mt-2 text-gray-500 capitalize dark:text-gray-300">Gym Instructor</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>
<!-- FOLLOW US ON SOCIAL MEDIA -->
<!-- <div class="width mx-auto bg-green-600 h-28 py-4 mt-12">
  <p class="text-white text-center font-semibold text-xl">You can follow us on social media</p>
</div> -->
  <Footer />
</template>

<script>
import Navbar from "../components/navbar.vue";
import Footer from "../components/footer.vue";

export default {
  name: "about",
  components: {
    Navbar,
    Footer,
  },
};
</script>
