<template>
    <div>
        <h2>BODY HERE</h2>
        <BodySidePanel></BodySidePanel>
        <BodyMeetTheTeam></BodyMeetTheTeam>
        <BodyMySecret></BodyMySecret>

    </div>
</template>

<script>
import BodyMeetTheTeam from './bodyMeetTheTeam.vue'
import BodyMySecret from './bodyMySecret.vue'
import BodySidePanel from './bodySidePanel.vue'

export default {
    name : "AppBody",
    components: {
        BodySidePanel,
        BodyMeetTheTeam,
        BodyMySecret

    }
}
</script>

<style scoped>
    h2 {
        color: blue;
    }
</style>