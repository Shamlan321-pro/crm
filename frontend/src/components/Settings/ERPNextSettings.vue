<template>
  <SettingsPage
    doctype="ERPNext CRM Settings"
    :title="__('TaskforgeHQ ERP settings')"
    :successMessage="__('TaskforgeHQ ERP settings updated')"
    class="p-8"
  />
</template>
<script setup>
import SettingsPage from '@/components/Settings/SettingsPage.vue'
</script>