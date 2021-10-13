<template>
    <div v-show="showAddTask">
        <AddTask @add-task="addTask"/>
    </div>
    <Tasks 
        @toggle-reminder="toggleReminder"
        @delete-task="deleteTask"
        :tasks="tasks"
    />
</template>
<script>
import AddTask from './components/AddTask'
import Tasks from './components/Tasks'
export default {
    name: 'Home',
    components:{
        Task,
        AddTask
    },
    data: {
        tasks:[s]
    }
}
</script>
