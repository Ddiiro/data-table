<template>
    <div class="header">
        <Search/>

        <Button/>
    </div>
  </template>
  
  <script>
    import Search from './Search.vue';
    import Button from './Button.vue';


    export default {
      components: {
        Search,
        Button,
      },

      data() {
        return {

        };
      },
      computed: {
 
      },
      methods: {

      },
      props: {

      },
    };
  </script>
  
  <style>
    .header {
        display: flex;
    }
  </style>