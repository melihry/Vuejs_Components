<template>
    <div>
        <li class="list-group-item" v-for="index in 5"> {{sunucu_name}}{{ index }} </li>
    </div>
</template>

<script>
    export default {
        data: function () {
            return {
                sunucu_name: "Sunucu #",
            };
        }
    };
</script>

<style>
</style>
