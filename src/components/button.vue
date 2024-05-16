<template>
    <h3>Tekan Yes Jika Mau, Tekan No Jika Tidak</h3>
    <button class="Yes" @click="ubahTeks">Yes</button>
    <button class="No" @click="ubahTeks">No</button>
<tmb/>
</template>
<script>
import tex from "./text.vue";
</script>
<style scoped>
button{
    margin: 0 20px;
}
.Yes{
    background-color: goldenrod;
}
.No{
    background-color: aqua;
}
</style>
