<template>
  <div class="container">
    <sunucu-status></sunucu-status>
    <sunucu-list></sunucu-list>
    <sunucu-haklar></sunucu-haklar>
  </div>
</template>

<script>
  import sunucudurum from "./Sunucu";
  import SunucuList from "./SunucuList";
  import SunucutumHaklar from "./SunucutumHaklar";
  export default {
      components: {
        "sunucu-status": sunucudurum,
        "sunucu-list": SunucuList,
        "sunucu-haklar": SunucutumHaklar,
      },
  };
</script>

