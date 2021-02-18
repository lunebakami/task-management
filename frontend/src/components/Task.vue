<template>
    <div v-on:click="showTask(name)" class="task">
        <span class="name">{{ name }}</span>
        <span class="status">{{ status }}</span>    
    </div>
</template>

<script>
export default {
    name: 'Task',
    props: {
        name: String,
        status: String
    },
    data() {
        return {
            hello: 'Hello'
        }
    },
    methods: {
        showTask: function(taskID) {
            alert(`See ${taskID}`)
        }
    }
}
</script>

<style>
.task {
    height: 50%;
    width: 100%;
    background-color: #ecf0f1;
    margin-bottom: 5px;
    display: grid;
    align-items: center;
    border-radius: 5px;
    justify-content: center;
    cursor: pointer;
}

.name {
    font-size: 18px;
    padding: 5px;
}

.status {
    width: 100%;
    background-color: #000;
    padding: 5px;
    color: #f1c40f;
    border-radius: 4px;
    margin-bottom: 3px;
}
</style>