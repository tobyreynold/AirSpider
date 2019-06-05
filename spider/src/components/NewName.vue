<template>
    <div>
        <h1>{{msg}}</h1>
        <p>this is vue components</p>       
    </div>
</template>

<script>
export default {
    name: 'New',
    props: {
        msg: String
    }
}
</script>

<style scoped>
    p {
        color: aqua;
    }
</style>

