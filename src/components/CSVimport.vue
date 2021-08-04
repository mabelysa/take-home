<template>
  <vue-csv-import
    v-model="csv"
    :fields="{ name: { required: false, label: 'Name' }, price: { required: true, label: 'Price' } }"
  >
    <vue-csv-toggle-headers></vue-csv-toggle-headers>
    <vue-csv-errors></vue-csv-errors>
    <vue-csv-input></vue-csv-input>
    <vue-csv-map></vue-csv-map>
  </vue-csv-import>
</template>

<script>
import { defineComponent } from "@vue/composition-api";

export default defineComponent({
  setup() {},
});
</script>
