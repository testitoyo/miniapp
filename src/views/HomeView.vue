<script lang="ts" setup>
import { ScanQr } from 'vue-tg'

function handleScanResult(data: string) {
  // ...
}
</script>

<template>
  <ScanQr @result="handleScanResult" />
</template>