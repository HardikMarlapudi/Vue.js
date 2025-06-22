<template>
    <header>
        <h1>{{title}}</h1>
        <Button text="Add Task" color="green" />
        <Button text="Update Task" color="blue" />
        <Button text="Delete Task" color="red" />
    </header>
</template>

<script>
import Button from './Button'

export default {
    name: 'Header',
    props: {
        title: String,
    },
    components: {
        Button,
    }
}
</script>


<style scoped>
    header {
        display: block;
        text-align: center;
        justify-content: center;
        align-items: center;
        margin-bottom: 20px;
    }
</style>
