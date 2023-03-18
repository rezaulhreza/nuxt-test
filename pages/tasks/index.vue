<template>
    <div>
        <h1>Tasks</h1>
    </div>

    <div>
        <nuxt-link :to="{ name: 'tasks-create' }">Create Task</nuxt-link>
    </div>

    <div>
        <nuxt-link :to="{ name: 'tasks-task-id', params: { id: 1 } }">Task 1</nuxt-link>
        <nuxt-link :to="{ name: 'tasks-task-id', params: { id: 2 } }">Task 2</nuxt-link>
    </div>

</template>