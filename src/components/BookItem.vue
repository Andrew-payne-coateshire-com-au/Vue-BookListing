<template>
         <li>{{book.title}}:{{book.author}}</li>
</template>

<script>
    export default {
        name:'BookITem',
        props: ['book']
    }
</script>

<style lang="scss" scoped>
li {
    display: block;
    margin: 0 10px;
}
</style>