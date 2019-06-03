<template>
  <div>
    <!-- TODO: Get this data from the parent, App.vue -->
    <li>
      <h1>{{newsHeader}}</h1>
      {{newsBody}}
      <hr>
      <a :href='blogURL'>View Full Post</a>

    </li>
  </div>
</template>

<script>
export default {
  props: ['newsHeader', 'newsBody', 'blogURL']
};
</script>

<style>
</style>

