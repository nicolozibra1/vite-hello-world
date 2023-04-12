<template>
    <div class="hero-container">
       <h3>{{ title }}</h3>
    </div>
</template>

<script>
    export default {
        name: 'AppHero',
        data() {
            return{
                title: 'Hero Here!'
            }
        } 
    }
</script>

<style lang="scss" scoped></style>