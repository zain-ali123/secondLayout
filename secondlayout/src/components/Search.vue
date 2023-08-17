<template>
  <div class="max-w-7-xl mx-40  ">
    <div class="py-32 ">
      <div
        class="bg-cover bg-center rounded-3xl"
        width="918"
        height="1495"
        style="
          background-image: url('https://keynote.tailwindui.com/_next/static/media/background.6c3571e0.jpg');
        "
      >
        <div class="flex flex-cols-2 ">
          <div class="px-4 py-20 text-left">
            <p class="text-5xl text-blue-900">Stay up to date</p>
            <p class="mt-4 text-lg text-blue-900 w-2/4">
              Get updates on all of our events and be the first to get notified
              when tickets go on sale.
            </p>
          </div>
          <div class="grid py-20">
            <h3 class="text-lg font-semibold text-left text-blue-900">
              Sign up to our newsletter ↓
            </h3>
            <div
              class="flex w-72 mr-20 rounded-2xl border-2 border-blue-900 h-16 overflow-hidden"
            >
              <input type="email" placeholder="Email address " class="py-0" />

              <button class="bg-blue-600 text-white hover:bg-blue-500">
                SignUp Today
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "SearchComp",
};
</script>
