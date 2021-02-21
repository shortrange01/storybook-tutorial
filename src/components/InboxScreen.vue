<template>
    <PureInboxScreen :error="error" />
</template>

<script>
import PureInboxScreen from './PureInboxScreen.vue';
import { mapState } from 'vuex';
export default {
    name: 'InboxScreen',
    components: { PureInboxScreen },
    computed: mapState(['error'])
};
</script>
