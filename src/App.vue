<template>
    <div class="container">
        <h1> My Cool Vue App</h1>
        <button>Add Task</button>
    </div>
</template>

<script> 
export default{
    name: 'App'
}
</script>

<style>

#app {
    text-align: center;
    color: yellowgreen;
    margin-top: 60px;
}
.container{
    border: 1px solid steelblue;
    padding: 30px;
    max-width: 500px;
    margin: auto;
}

button {
    padding: 10px 20px;
    font-size: 15px;
    background: seagreen;
    color: white;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

</style>