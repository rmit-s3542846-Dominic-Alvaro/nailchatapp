<template>
<div class="columns" id="mail-app">
    <Userpanel></Userpanel>
    <Chatcard></Chatcard>
    <Conversationthread></Conversationthread>
</div>
</template>

<script>
import Userpanel from '@/components/Userpanel.vue'
import Chatcard from '@/components/Chatcard.vue'
import Conversationthread from '@/components/Conversationthread.vue'

export default {
    name: 'app',
    components: {
        Userpanel,
        Chatcard,
        Conversationthread,
  }
}
</script>

<style>

</style>

