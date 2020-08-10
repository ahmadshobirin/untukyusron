<template>
  <div>
    <div class="px-2 my-3 bg-white-100 p-1">
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
      <form class="mb-6 my-5" action="/" method="post">
        <div class="flex flex-col mb-4">
          <label class="mb-2 uppercase font-bold text-xs text-grey-darkest" for="first_name">First Name</label>
          <input placeholder="Jhon" class="border py-2 px-3 text-grey-darkest" type="text" name="first_name"
            id="first_name">
        </div>
        <div class="flex flex-col mb-4">
          <label class="mb-2 uppercase font-bold text-xs text-grey-darkest" for="last_name">Last Name</label>
          <input placeholder="Jhon" class="border py-2 px-3 text-grey-darkest" type="text" name="last_name"
            id="last_name">
        </div>
        <div class="flex flex-col mb-4">
          <label class="mb-2 uppercase font-bold text-xs text-grey-darkest" for="email">Email</label>
          <input placeholder="example@example.com" class="border py-2 px-3 text-grey-darkest" type="email" name="email"
            id="email">
        </div>
        <div class="flex flex-col mb-6">
          <label class="mb-2 uppercase font-bold text-xs text-grey-darkest" for="password">Password</label>
          <input placeholder="******" class="border py-2 px-3 text-grey-darkest" type="password" name="password"
            id="password">
        </div>
        <button class="block w-400 p-2 rounded no-underline text-sm text-white bg-blue-500">KIRIM</button>
      </form>
    </div>
    <div class="flex items-center justify-center h-screen">

      <div class="bg-white-800 text-black font-bold rounded-lg border shadow-lg p-10">
        Centered Content
      </div>

    </div>
  </div>
</template>