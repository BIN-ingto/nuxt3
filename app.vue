<template>
  <div>
    <NuxtRouteAnnouncer />
    <NuxtWelcome title="awdnka" />
    <NuxtPage  />
  </div>
</template>
<script setup>
const appConfig = useAppConfig();
console.log("appConfig111", appConfig);
</script>
