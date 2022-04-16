<template>
  <div>
    <div class="row">
      <div class="col-xs-12">
        <header>
          <h1>{{sunucu_status}}</h1>
        </header>
      </div>
    </div>
    <hr />
  </div>
</template>

<script>
    export default {
        data: function () {
            return {
                sunucu_status: "Sunucu Durumu",
            };
        }
    };
</script>

