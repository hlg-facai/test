<template>
    <div>
        <p class="card">
            {{text}}
        </p>
        <slot></slot>
    </div>
</template>

<script>
export default {
    props: ['text']
};
</script>

<style>
.card {
    padding: 10px;
}
</style>
