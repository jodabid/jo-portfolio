<template>

    <header>
        <h1>{{ title }}</h1>
    </header>
    
</template>
<script>
export default {
    data(){
        return{
            title: 'DUE DESIGNS'
        }
    }
}
</script>
<style scoped>
header{
    background: rgb(41, 41, 41);
    padding: 10px;
}
h1{
    color: rgb(255, 255, 255);
    text-align: center;
}
</style>