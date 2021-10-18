<template>
    <li>{{book.title}}:{{book.author}}</li>
</template>
<script>
import BookItem from '@/components/BookItem';
export default {
    name : "BookItem",
    props : ['book']
}
</script>
<style lang="css">
li {
    display: block;
    margin: 0 10px;
}   
</style>