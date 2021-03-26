<template>
    <div class="about">
        <h1>Hello , This is an about page</h1>
        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Eius explicabo vero consectetur ducimus praesentium aperiam, ex voluptatem repellendus commodi ipsam architecto laborum minima! A, voluptates earum mollitia hic similique tenetur.</p>
    </div>
</template>

<script>
export default {
    name: 'About',
    data() {
        return {
            their_name: this.$route.params.name
        }
    }
}
</script>