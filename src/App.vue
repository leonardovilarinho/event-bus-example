<template>
    <div id="app">
        <lv-container />
        <hr>
        <lv-notification />
    </div>
</template>

<script>
import LvContainer from './components/Container.vue'
import LvNotification from './components/Notification.vue'
export default {
    name: 'app',
    components: { LvContainer, LvNotification }
}
</script>
