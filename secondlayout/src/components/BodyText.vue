<!-- <div class="relative py-20"> 
    <div
      class="absolute inset-0 overflow-hidden bg-indigo-50 -bottom-14 -top-36"
    >
      <img
        width="918"
        height="1495"
        class="absolute top-0 left-0 translate-x-[-55%] translate-y-[-10%] -scale-x-100 sm:left-1/2 translate-x-[-106%]"
        src="../assets/background.jpg"
      /> 
       <div
        class="absolute inset-x-0 top-0 h-40 bg-gradient-to-b from-white"
      ></div>
      <div
        class="absolute inset-x-0 bottom-0 h-40 bg-gradient-to-t from-white"
      ></div>
    </div>
    <div class="mx-auto max-w-7xl px-4 px-8 relative">
      <div class="mx-auto max-w-2xl max-w-4xl px-12">
        <h1
          class="font-display text-5xl font-bold  text-blue-600 text-left"
        >
          A design conference <br> for the dark side.
        </h1>
        <div
          class="mt-6 space-y-6 font-display text-left text-2xl text-left text-blue-900"
        >
          <p>
            The next generation of web users are tech-savvy and suspicious. They
            know how to use dev tools, they can detect a phishing scam from a
            mile away, and they certainly aren’t accepting any checks from
            Western Union.
          </p>
          <p>
            At DeceptiConf you’ll learn about the latest dark patterns being
            developed to trick even the smartest visitors, and you’ll learn how
            to deploy them without ever being detected.
          </p>
        </div>

        <div
          class="mt-10 grid grid-cols-2 gap-x-10 gap-y-6 auto-cols-auto grid-flow-col grid-cols-none justify-start text-left"
        >
          <div>
            <p class="font-mono text-sm text-blue-600">Speakers</p>
            <p
              class="mt-0.5 text-2xl font-semibold  text-blue-900"
            >
              18
            </p>
          </div>
          <div>
            <p class="font-mono text-sm text-blue-600">People Attending</p>
            <p
              class="mt-0.5 text-2xl font-semibold  text-blue-900"
            >
              2,091
            </p>
          </div>
          <div>
            <p class="font-mono text-sm text-blue-600">Venue</p>
            <p
              class="mt-0.5 text-2xl font-semibold  text-blue-900"
            >
              Staples Center
            </p>
          </div>
          <div>
            <p class="font-mono text-sm text-blue-600">Location</p>
            <p
              class="mt-0.5 text-2xl font-semibold  text-blue-900"
            >
              Los Angeles
            </p>
          </div>
        </div>
      </div>
    </div>
  </div> -->
<template>
  <div class="max-w-7xl mx-auto px-8">
    <div
      class="flex flex-col justify-center items-center py-24 mx-auto text-left max-w-2xl"
    >
      <p class="text-5xl font-bold mb-5 text-blue-600">
        A design conference for the dark side.
      </p>
      <p class="mb-5 text-2xl text-blue-900">
        The next generation of web users are tech-savvy and suspicious. They
        know how to use dev tools, they can detect a phishing scam from a mile
        away, and they certainly aren’t accepting any checks from Western Union.
      </p>
      <p class="text-2xl text-blue-900">
        At DeceptiConf you’ll learn about the latest dark patterns being
        developed to trick even the smartest visitors, and you’ll learn how to
        deploy them without ever being detected.
      </p>
    </div>
    <div
      class="flex felx-col justify-between justify-center items-center max-w-2xl mx-auto mt-8"
    >
      <div v-for="x in 4" :key="x">
        <div class="grid">
          <p class="font-mono text-sm text-blue-600">Speakers</p>
          <p class="mt-0.5 text-2xl font-semibold text-blue-900">18</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "BodyText",
};
</script>
