<template>
    <button @click="ubahTeks"> tekan </button>
</template>
<script>
const emit = defineEmits(['respon'])
function ubahTeks(){
    emit('respon','hello para orang bodoh')
}
</script>
