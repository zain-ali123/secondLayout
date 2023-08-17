<template>
       <div class=" flex max-w-7xl flex-cols mb-32">
          <div class="grid text-left max-w-4xl  mx-auto">
            <p class="text-5xl max-w-5xl text-blue-600 tracking-tighter">
              Our three day schedule is jam-packed <br> with  brilliant, creative, evil
              geniuses.
            </p>
            <p class="text-2xl text-blue-900 w-3/4">
              The worst people in our industry giving the best talks you’ve ever
              seen. Nothing will be recorded and every attendee has to sign an NDA
              to watch the talks.
            </p>
          </div>
        </div>
        <div class="grid grid-cols-3 max-w-4xl mx-auto gap-6  ">
            <div class="  shadow-lg" v-for="x in 3" :key="x">
                 <h3 class="text-2xl font-semibold text-left text-blue-900">April 4</h3>
                <p class="text-blue-900 mt-1.5 text-wrap text-left  text-sm mb-5">The first day of the conference is focused on dark patterns for ecommerce.</p>
                <ul >
                    <li class="mb-5 " v-for="x in 7" :key="x">
                        <h4 class="text-lg font-semibold tracking-tight text-blue-900">Steven McHail</h4>
                        <p class="mt-1 tracking-tight text-blue-900">Not so one-time payments</p>
                        <p class="mt-1 font-mono text-sm text-slate-500">9:00AM - 10:00M</p>
                    </li>
                </ul>
            </div>
        </div>
</template>

<script>
export default {
        name:'SchedulerComp'
    }
</script>