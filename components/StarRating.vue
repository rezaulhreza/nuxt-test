<template>

<div>
            <span v-for="n in 5" :key="n">
                <span v-if="n <= rating">★</span>
                <span v-else>☆</span>
            </span>
        </div>

</template>

<script setup>

// Create a star rating component
const StarRating = {
    props: {
        rating: {
            type: Number,
            required: true,
            validator: value => value >= 0 && value <= 5
        }
    },
}
</script>