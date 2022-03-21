<template>
    <button @click="onClick" >
        <slot>Submit</slot>
    </button>
</template>

<script>
export default {
    props: {
        onClick: {
            type: Function,
            required: true
        },
        styles: 'bg-white'
    }
}
</script>

<style>

</style>