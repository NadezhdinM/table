<template>
  <v-app>
    <v-container fluid>
      <Table />
    </v-container>
  </v-app>
</template>

<script>
import Table from "@/components/table/Table";

export default {
  name: "App",

  components: {
    Table,
  },
};
</script>
