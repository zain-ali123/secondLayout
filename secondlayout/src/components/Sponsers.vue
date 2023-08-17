<template>
  <div class="max-w-7xl py-20 grid">
    <h2
      class="mx-auto max-w-2xl text-center text-4xl max-w-4xl font-medium text-blue-900"
    >
      Current sponsorships for our <br />
      workshops and speakers.
    </h2>
  </div>
  <div class="mx-40">
    <div class="grid grid-cols-3 gap-4">
      <div class="" v-for="x in 6" :key="x">
        <img
          src="https://keynote.tailwindui.com/_next/static/media/transistor.a1e38d49.svg"
          alt=""
        />
      </div>
    </div>
  </div>
</template>
<script>
export default {
        name:'SponserComp'
    }
</script>
