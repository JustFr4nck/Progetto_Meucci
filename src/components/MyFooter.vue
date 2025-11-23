<template>
    <footer id="contactId" class=" flex flex-col items-center footer footer-horizontal footer-center backFoot text-base-content rounded pt-10  lg:p-10 text-lg">
        <nav>
            <div class="flex flex-row justify-center gap-5">
                <a href="https://www.instagram.com/lista_3_meucci?igsh=cWZ0b2xyaTJpMThv&utm_source=qr" target="_blank">
                    <Icon :icon="'streamline-logos:instagram-logo-2-solid'" class="iconColor" width="40" height="40" viewBox="0 0 24 24"></Icon>
                </a>
            </div>
        </nav>
        <aside class="flex flex-row text-center pt-2 lg:pb-1 pb-10 iconColor">
            <p>Copyright © JustFr4nck</p>
        </aside>
    </footer>
</template>

<script setup lang="ts">

    import {Icon} from '@iconify/vue';

</script>


<style scoped>

.backFoot{

  background-color: #042C54;;
}

.iconColor{

  color: #FFFCF2;
}

</style>
