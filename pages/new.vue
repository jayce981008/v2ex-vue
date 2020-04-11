<template>
  <div class="new">
    <Rightbar>
      <template v-slot:Rightbar></template>
    </Rightbar>
    <Main>
      <template v-slot:Main>
        <div class="sep20"></div>
        <div class="box" id="box">
          <div class="cell">
            <div class="fr fade" id="content_remaining">20000</div>正文
          </div>
          <div
            style="text-align: left; border-bottom: 1px solid #e2e2e2; font-size: 14px; line-height: 120%;"
          >
            <textarea style="visibility: hidden;" maxlength="20000" id="editor" name="content"></textarea>
          </div>
        </div>
      </template>
    </Main>
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
