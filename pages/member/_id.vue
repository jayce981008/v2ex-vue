<template>
  <div class="member">
    <Rightbar>
      <template v-slot:Rightbar>
        <div class="sep20"></div>
        <div class="box">
          <div class="cell">
            <img
              src="https://www.v2ex.com/static/img/neue_comment.png"
              width="18"
              align="absmiddle"
            /> &nbsp;jayce981008 最近的时间轴更新
          </div>
          <div id="statuses"></div>
        </div>
      </template>
    </Rightbar>
    <Main>
      <template v-slot:Main>
        <div class="sep20"></div>
        <div class="box">
          <div class="cell">
            <table cellpadding="0" cellspacing="0" border="0" width="100%">
              <tbody>
                <tr>
                  <td width="73" valign="top" align="center">
                    <img
                      src="https://cdn.v2ex.com/gravatar/7ba094c72ea6794d62bda45e8a1fb27e?s=73&amp;d=retro"
                      class="avatar"
                      border="0"
                      align="default"
                      alt="jayce981008"
                      loading="lazy"
                    />
                    <div class="sep10"></div>
                    <strong class="online">ONLINE</strong>
                  </td>
                  <td width="10"></td>
                  <td width="auto" valign="top" align="left">
                    <div class="fr"></div>
                    <h1 style="margin-bottom: 5px;">jayce981008</h1>
                    <div class="sep10"></div>
                    <span class="gray">
                      V2EX 第 482715 号会员，加入于 2020-04-10 01:45:22 +08:00
                      <div class="sep5"></div>今日活跃度排名
                      <a href="/top/dau">5296</a>
                    </span>
                  </td>
                </tr>
              </tbody>
            </table>
            <div class="sep5"></div>
          </div>
        </div>
        <div class="sep20"></div>
        <div class="box">
          <div class="cell_tabs">
            <div class="fl">
              <img
                src="https://cdn.v2ex.com/gravatar/7ba094c72ea6794d62bda45e8a1fb27e?s=48&amp;d=retro"
                width="24"
                style="border-radius: 24px; margin-top: -2px;"
                border="0"
              />
            </div>
            <a href="/member/jayce981008" class="cell_tab_current">jayce981008 创建的所有主题</a>
            <a href="/member/jayce981008/qna" class="cell_tab">提问</a>
            <a href="/member/jayce981008/tech" class="cell_tab">技术话题</a>
            <a href="/member/jayce981008/play" class="cell_tab">好玩</a>
            <a href="/member/jayce981008/jobs" class="cell_tab">工作信息</a>
            <a href="/member/jayce981008/deals" class="cell_tab">交易信息</a>
            <a href="/member/jayce981008/city" class="cell_tab">城市相关</a>
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
  },
  validate({ params, query }) {
    console.log(params.id)
    if (params.id) {
      return true
    } else {
      return false
    }
  }
})
</script>
