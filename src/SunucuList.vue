<template>
    <div class="row">
        <div class="col-xs-12 col-sm-6">
        <ul class="list-group">
            <sunucu-list-for></sunucu-list-for>
        </ul>
      </div>
     <sunucu-status-bottom></sunucu-status-bottom>
     <hr />
    </div>
</template>

<script>
    import SunucuBottomText from "./SunucuBottomText";
    import SunucuListFor from "./SunucuListFor";
    export default {
        components: {
            "sunucu-status-bottom": SunucuBottomText,
            "sunucu-list-for": SunucuListFor,
      },
    };
</script>

<style>
</style>
