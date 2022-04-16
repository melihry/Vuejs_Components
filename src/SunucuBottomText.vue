<template>
    <div class="col-xs-12 col-sm-6">
        <p>{{sunucu_status_text}}</p>
    </div>
</template>


<script>
    export default {
        data: function () {
        return {
            sunucu_status_text: "Sunucu Bilgisi güncel değil!!",
        };
    }
  };
</script>

<style>
</style>
