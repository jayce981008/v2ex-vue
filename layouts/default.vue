<template>
  <div>
    <Top />
    <Wrapper />
    <Bottom />
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import Top from '~/components/Top.vue'
import Wrapper from '~/components/Wrapper.vue'
import Bottom from '~/components/Bottom.vue'

export default Vue.extend({
  components: {
    Top,
    Wrapper,
    Bottom
  }
})
</script>
