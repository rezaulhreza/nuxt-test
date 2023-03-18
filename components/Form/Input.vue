<template>
    <input type="text" :value="value" @input="updateValue($event.target.value)" />
</template>

<script setup>

const { emit, props } = defineProps({
    value: {
        type: String,
        required: true
    }
})

const updateValue = (value) => {
    emit('update:value', value)

    console.log(value)
}

</script>