<template>
  <div>
    <div class="px-2 my-3">
      <div class="bg-teal-100 border-t-4 border-teal-500 rounded-b text-teal-900 px-4 py-3 shadow-md" role="alert">
        <div class="flex">
          <div class="py-1"><svg class="fill-current h-6 w-6 text-teal-500 mr-4" xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 20 20">
              <path
                d="M2.93 17.07A10 10 0 1 1 17.07 2.93 10 10 0 0 1 2.93 17.07zm12.73-1.41A8 8 0 1 0 4.34 4.34a8 8 0 0 0 11.32 11.32zM9 11V9h2v6H9v-4zm0-6h2v2H9V5z" />
              </svg></div>
          <div>
            <p class="font-bold">Hello!</p>
            <p class="text-sm">Kamu dapat meninggalkan pesan disini</p>
          </div>
        </div>
      </div>
      <!-- <div class="flex my-3 -mx-2">
        <div class="w-1 px-2">
          <div class="bg-white-400 h-12"></div>
        </div>
        <div class="w-99 px-2">
          <div class="bg-white-500 h-12">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ratione, asperiores
            reprehenderit, nulla quos culpa in unde, cupiditate iusto reiciendis fuga sint aliquam. Eaque consequuntur
            soluta, iste consectetur quibusdam dolorum! Repellendus.</div>
        </div>
        <div class="w-1 px-2">
          <div class="bg-white-400 h-12"></div>
        </div>
      </div> -->
      <form class="mb-6 my-5" action="/" method="post">
        <div class="flex flex-col mb-4">
          <label class="mb-2 uppercase font-bold text-xs text-grey-darkest" for="first_name">First Name</label>
          <input class="border py-2 px-3 text-grey-darkest" type="text" name="first_name" id="first_name">
        </div>
        <div class="flex flex-col mb-4">
          <label class="mb-2 uppercase font-bold text-xs text-grey-darkest" for="last_name">Last Name</label>
          <input class="border py-2 px-3 text-grey-darkest" type="text" name="last_name" id="last_name">
        </div>
        <div class="flex flex-col mb-4">
          <label class="mb-2 uppercase font-bold text-xs text-grey-darkest" for="email">Email</label>
          <input class="border py-2 px-3 text-grey-darkest" type="email" name="email" id="email">
        </div>
        <div class="flex flex-col mb-6">
          <label class="mb-2 uppercase font-bold text-xs text-grey-darkest" for="password">Password</label>
          <input class="border py-2 px-3 text-grey-darkest" type="password" name="password" id="password">
        </div>
        <button class="block bg-teal hover:bg-teal-dark text-white uppercase text-lg mx-auto p-4 rounded"
          type="submit">Create Account</button>
      </form>
    </div>
  </div>
</template>