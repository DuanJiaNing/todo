<template>
    <div id="test">should show abc: {{text}}</div>
</template>

<script>
    export default {
        data() {
            return {
                text: "abcdef"
            }
        },
        props: {},
    };
</script>

<style>
    #test {
        color: red;
    }
</style>
