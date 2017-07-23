<template>
    <div class="z-block">
    	<div v-for="n in 11">{{msg + '-' + n}}</div>
        <div class="vue-test">test.css</div>
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
    @import '../csses/test.css';
    .z-block {
        background-color: #ff00ff
    }
</style>