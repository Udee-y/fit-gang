<template>
  <div class="register mx-auto">
    <div class="member p-6">
      <div class="text-center pb-8">
        <h1 class="py-4 text-2xl font-bold">Gym Membership Form</h1>
        <p class="">
          Want to become a member of our Gym? Then start by filling our form to
          complete registration. We will contact you shortly to notify you about
          your membership card.
        </p>
      </div>
      <form action="">
        <div>
          <label for="Name" class="block mt-4">Name*</label>
          <div class="flex gap-8">
            <input type="text" name="" id="" placeholder="FIRST" class="w-full" />
          <input type="text" placeholder="LAST" class="w-full" />
          </div>
          <div>
            <label for="Email" class="block mt-4">Email</label>
            <input
              type="email"
              name=""
              id=""
              placeholder="Enter Email Address"
              class="block"
            />
          </div>
          <div>
            <label for="Phone" class="block mt-4">Phone Number</label>
            <input
              type="tel"
              name=""
              id=""
              placeholder="+234 xxxxxxxx"
              class="block"
            />
          </div>
          <div>
            <label for="weight" class="block mt-4">Your current weight(Kg)</label>
            <input type="number" name="weight" id="" class="block" />
          </div>
          <div>
            <label for="desired-weight" class="block mt-4">Desired Weight(Kg)</label>
            <input type="number" name="weight" id="" class="block" />
          </div>
          <div>
            <label for="height" class="block mt-4">Height</label>
            <input type="number" name="height" id="" class="block" />
          </div>
          <div>
            <label for="address" class="block mt-4">Home address</label>
            <input
              type="text"
              name="address"
              id=""
              class="block rounded-md"
              placeholder="Street Address"
            />
          </div>
          <div class="flex gap-8 mt-2">
            <input type="text" name="city" id="" placeholder="City" class="" />
            <select name="" id="" class="rounded-md w-full mt-2 px-1 h-11 text-gray-400">
              <option value="">State</option>
              <option value="">Lagos</option>
              <option value="">Oyo</option>
              <option value="">Rivers</option>
            </select>
          </div>
        </div>
      </form>
    </div>
  </div>
</template>

<style scoped>
input{
   padding: 0.6rem 0.8rem;
   margin: 0.5rem 0;
   width: 100%;
   border-radius: 0.375rem;
}
</style>