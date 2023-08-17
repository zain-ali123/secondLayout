<template>
  <div
        class="bg-cover bg-center"
        width="918"
        height="1495"
        style="
        background-image: url('https://keynote.tailwindui.com/_next/static/media/background.6c3571e0.jpg');">
        <NavBar />
        <div class=" absolute inset-x-0 top-0 h-40 bg-gradient-to-b from-white"></div>
     
        <BodyText />
          <div class="  inset-x-0 bottom-0 h-40  bg-gradient-to-t from-white"></div>

    </div> 
    
  <Speakers />
  <Scheduler />
  <Sponsers />
  <Search />

  <FooterBar />
</template>
<script>
import NavBar from "@/components/NavBar.vue";
import FooterBar from "@/components/FooterBar.vue";
import BodyText from "@/components/BodyText.vue";
import Speakers from "@/components/Speakers.vue";
import Scheduler from "@/components/Scheduler.vue";
import Sponsers from "@/components/Sponsers.vue";
import Search from "@/components/Search.vue";
export default {
  name: "LayoutView",
  components: {
    NavBar,
    FooterBar,
    BodyText,
    Speakers,
    Scheduler,
    Sponsers,
    Search,
  },
};
</script>
