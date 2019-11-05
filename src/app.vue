<template>
    <div id="test">{{test}}</div>
</template>

<script>
    export default {
        data() {
            return {
                text: "abc"
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
