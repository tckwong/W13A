<template>
    <aside>
        <ul>
            <li>Home</li>
            <li>About Us</li>
            <li>Meet The Team</li>
            <li>Contact</li>
        </ul>
    </aside>
</template>

<script>
export default {
    name: 'BodySidePanel'
}
</script>

<style scoped>
    aside {
        text-align: left;
        width: 200px;
        background-color: #8a95bb;
        position: fixed;
        height: 100vh;
        overflow: auto;
        }
   
</style>