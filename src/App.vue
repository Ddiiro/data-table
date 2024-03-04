<template>
    <h1>Employee Data</h1>
   
      <Header/>

  <Table/>
</template>
<script>
  import Table from './components/Table.vue';
  import Header from './components/Header.vue';
  export default {
    components: {
      Table,
      Header
    },
  };
</script>

<style>
</style>
