<template>
    <footer>
        <p>{{ copyright }}</p>
    </footer>
</template>
<script>
export default {
    data(){
        return{
            copyright: 'Copyright 2018 Due Designs'
        }
    }
}
</script>
<style scoped>
footer{
    background: rgb(41, 41, 41);
    padding: 6px;
}
p{
        color: rgb(255, 255, 255);
        text-align: center;
}
</style>