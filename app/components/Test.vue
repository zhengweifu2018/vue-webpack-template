<template>
    <div class="z-block">
    	<div v-for="n in 11">{{msg + '-' + n}}</div>
    </div>
</template>

<script>
    export default {
        data () {
            return {
                msg: 'Hello World!'
            };
        }
    };
</script>

<style>
    .z-block {
        background-color: #ff00ff
    }
</style>