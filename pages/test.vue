<template>
  <div>
    <Name/>
    <Tutorial/>
  </div>

</template>

<script lang="ts">
import Vue from 'vue'
import Name from '~/components/Name.vue'

export default Vue.extend({components: {Name}})
</script>
