<template>
    <button @click="$emit('click')" class="btn btn-success">{{  title }}</button>
</template>

<script>
export default {
    name: "CustomBtn",
    props: {
        title: {
            type: String,
            default: ""
        }
    }
}
</script>

<style></style>