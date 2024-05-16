<template>
  <h1>Hello</h1>
  <p>Selamat Kamu Menang</p>   

</template>
<script>
import tmb from './components/button.vue'
import  EmitCom from'/components/emit.vue'
 const chilMsg = ref('tidak ada pesan')
 function ubahTeks(msg){
  chilMsg.value = msg
  alert('pesan diterima dari child:'+msg)
 }
</script>
<template>
  <Title title="Emit"/>
  <EmitCom @response="ubahTeks"/>
</template>


