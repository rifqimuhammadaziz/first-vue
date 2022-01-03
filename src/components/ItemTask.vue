<template>
    <div>
        <input class="form-check-input" type="checkbox" value="" id="defaultCheck1">
        <label class="form-check-label item" for="defaultCheck1" v-bind:class="{'item-completed':myTask.isDone}">
        {{ myTask.name }}
        </label>
    </div>
</template>

<script>
export default {
    name: "ItemTask",
    props: ["myTask"]
}
</script>

<style scoped>

</style>