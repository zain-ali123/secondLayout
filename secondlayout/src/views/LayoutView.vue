<template>

    <div class="flex min-h-full">
        <div class="flex w-full flex-col">
            <NavBar/>
            <FooterBar/>
        </div>
    </div>
    
</template>
<script>
import NavBar from '@/components/NavBar.vue';
import FooterBar from '@/components/FooterBar.vue';
export default {
    name: 'LayoutView',
    components: {
        NavBar,
           FooterBar
        }
    }
</script>