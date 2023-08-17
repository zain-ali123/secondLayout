<template>


            <NavBar/>
            <main class="flex-auto">
                <BodyText/>
                <Speakers/>
            </main>
            <FooterBar/>

</template>
<script>
import NavBar from '@/components/NavBar.vue';
import FooterBar from '@/components/FooterBar.vue';
import BodyText from '@/components/BodyText.vue';
import Speakers from '@/components/Speakers.vue';
export default {
    name: 'LayoutView',
    components: {
        NavBar,
        FooterBar,
        BodyText,
           Speakers
        }
    }
</script>