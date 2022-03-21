<template>
    <button
        class="group not-prose inline-block w-[92px] m-0 mr-6 mb-6 p-2 border-none rounded-md bg-chungking-grey-800 cursor-pointer"
        type="button">
        <div
            class="flex items-center justify-center h-[76px] w-[76px] text-xs rounded-sm group-focus:opacity-70 text-chungking-white">
            {{colorName}}
        </div>
    </button>
</template>

<style scoped>

</style>

<script setup>
    defineProps({
        colorName: String
    })
</script>