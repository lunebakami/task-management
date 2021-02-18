<template>
    <button v-on:click="goToAddForm">
        Add Task
    </button>
</template>

<script>
export default {
    name: 'Button',
    methods: {
        goToAddForm() {
            alert('add');
        }
    }
}
</script>

<style>
button {
    margin-bottom: 10px;
    padding: 13px 0;
    border-radius: 4px;
    color: #f8f8f2;
    font-weight: bold;
    font-size: 20px;
    background-color: #ff5555;
    border: 0;
    cursor: pointer;
}
</style>