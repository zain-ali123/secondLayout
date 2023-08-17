<template>
    <div class="bg-indigo-100/20">
        
        <NavBar />
        <main class="flex-auto ">
          <BodyText />
          <Speakers />
          <Scheduler/>
          <Sponsers/>
        </main>
        <FooterBar />
    </div>
</template>
<script>
import NavBar from "@/components/NavBar.vue";
import FooterBar from "@/components/FooterBar.vue";
import BodyText from "@/components/BodyText.vue";
import Speakers from "@/components/Speakers.vue";
import Scheduler from "@/components/Scheduler.vue";
import Sponsers from "@/components/Sponsers.vue";
export default {
  name: "LayoutView",
  components: {
    NavBar,
    FooterBar,
    BodyText,
      Speakers,
      Scheduler,
      Sponsers
  },
};
</script>
