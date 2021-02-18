<template>
  <div id="list">
    <Task name="DIF-122" status="In Development"/>
    <Task name="BS-233" status="Pending CLient"/>
    <Task name="BS-233" status="Pending CLient"/>
    <Task name="BS-233" status="Pending CLient"/>
    <Task name="BS-233" status="Pending CLient"/>
  </div>
</template>

<script>
import Task from './Task';

export default {
  name: 'TaskList',
  components: {
    Task
  }
}
</script>

<style>
#list {
  width: 300px;
  padding: 20px;
  border-radius: 4px;
  background-color: #34495e;
  color: #e74c3c;
  display: flex;
  align-content: center;
  justify-content: center;
  flex-direction: column;
}
</style>