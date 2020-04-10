<template>
  <div class="index">
    <Rightbar>
      <template v-slot:Rightbar>
        <div class="sep20"></div>
        <div class="box"></div>
      </template>
    </Rightbar>
    <Main>
      <template v-slot:Main>
        <div class="sep20"></div>
        <div class="box"></div>
      </template>
    </Main>
    <Box/>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import Rightbar from '~/components/Rightbar.vue'
import Main from '~/components/Main.vue'

export default Vue.extend({
  components: {
    Rightbar,
    Main
  }
})
</script>
