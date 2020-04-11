<template>
  <div class="t">
    <Rightbar>
      <template v-slot:Rightbar>
        <div class="sep20"></div>
        <div class="box">
          <div class="cell">
            <table cellpadding="0" cellspacing="0" border="0" width="100%">
              <tbody>
                <tr>
                  <td width="48" valign="top">
                    <a href="/member/jayce981008">
                      <img
                        src="https://cdn.v2ex.com/gravatar/7ba094c72ea6794d62bda45e8a1fb27e?s=48&amp;d=retro"
                        class="avatar"
                        border="0"
                        align="default"
                        style="max-width: 48px; max-height: 48px;"
                        alt="jayce981008"
                        loading="lazy"
                      />
                    </a>
                  </td>
                  <td width="10" valign="top"></td>
                  <td width="auto" align="left">
                    <div class="fr">
                      <a href="/settings/night/toggle?once=14996" class="light-toggle">
                        <img
                          src="https://www.v2ex.com/static/img/toggle-light.png"
                          align="absmiddle"
                          height="10"
                          alt="Light"
                        />
                      </a>
                    </div>
                    <span class="bigger">
                      <a href="/member/jayce981008">jayce981008</a>
                    </span>
                  </td>
                </tr>
              </tbody>
            </table>
            <div class="sep10"></div>
            <table cellpadding="0" cellspacing="0" border="0" width="100%">
              <tbody>
                <tr>
                  <td width="33%" align="center">
                    <a href="/my/nodes" class="dark" style="display: block;">
                      <span class="bigger">0</span>
                      <div class="sep3"></div>
                      <span class="fade">节点收藏</span>
                    </a>
                  </td>
                  <td
                    width="34%"
                    style="border-left: 1px solid rgba(100, 100, 100, 0.4); border-right: 1px solid rgba(100, 100, 100, 0.4);"
                    align="center"
                  >
                    <a href="/my/topics" class="dark" style="display: block;">
                      <span class="bigger">0</span>
                      <div class="sep3"></div>
                      <span class="fade">主题收藏</span>
                    </a>
                  </td>
                  <td width="33%" align="center">
                    <a href="/my/following" class="dark" style="display: block;">
                      <span class="bigger">0</span>
                      <div class="sep3"></div>
                      <span class="fade">特别关注</span>
                    </a>
                  </td>
                </tr>
              </tbody>
            </table>
          </div>
          <div class="cell" id="member-activity">
            <div class="member-activity-bar">
              <div class="member-activity-start" style="width: 33px;"></div>
            </div>
          </div>
          <div class="cell" style="padding: 8px; line-height: 100%;">
            <table cellpadding="0" cellspacing="0" border="0" width="100%">
              <tbody>
                <tr>
                  <td width="28">
                    <a href="/new">
                      <img
                        src="https://www.v2ex.com/static/img/essentials/compose.png?v=b9e1f045f4ad639733bf9f6dbc62ed4c"
                        width="28"
                        border="0"
                        style="vertical-align: bottom;"
                      />
                    </a>
                  </td>
                  <td width="10"></td>
                  <td width="auto" valign="middle" align="left">
                    <a href="/new">创作新主题</a>
                  </td>
                </tr>
              </tbody>
            </table>
          </div>
          <div class="inner">
            <div class="fr" id="money" style="margin: -3px 0px 0px 0px">
              <a href="/balance" class="balance_area" style>
                0
                <img
                  src="https://www.v2ex.com/static/img/bronze@2x.png"
                  height="16"
                  alt="B"
                  style="vertical-align: baseline;"
                  border="0"
                />
              </a>
            </div>
            <a href="/notifications" class="fade">0 条未读提醒</a>
          </div>
          <div class="dock_area">
            <div class="inner">
              <span class="chevron">&nbsp;›&nbsp;</span>
              <a href="/balance">在你开始发帖之前，请先领取初始资本</a>
            </div>
          </div>
        </div>
      </template>
    </Rightbar>
    <Main>
      <template v-slot:Main>
        <div class="sep20"></div>
        <div class="box" style="border-bottom: 0px;">
          <div class="header">
            <div class="fr">
              <a href="/member/longjiahui">
                <img
                  src="https://cdn.v2ex.com/avatar/d1ab/0ef8/213281_large.png?m=1486258752"
                  class="avatar"
                  border="0"
                  align="default"
                  alt="longjiahui"
                  loading="lazy"
                />
              </a>
            </div>
            <a href="/">V2EX</a>
            <span class="chevron">&nbsp;›&nbsp;</span>
            <a href="/go/js">JavaScript</a>
            <div class="sep10"></div>
            <h1>为什么 new Date().getMonth()返回 0-11</h1>
            <div id="topic_661469_votes" class="votes">
              <a href="javascript:" onclick="upVoteTopic(661469);" class="vote">
                <li class="fa fa-chevron-up"></li>
              </a> &nbsp;
              <a href="javascript:" onclick="downVoteTopic(661469);" class="vote">
                <li class="fa fa-chevron-down"></li>
              </a>
            </div>&nbsp;
            <small class="gray">
              <a href="/member/longjiahui">longjiahui</a> · 4 小时 22 分钟前 · 954 次点击 &nbsp;
            </small>
          </div>
          <div class="cell">
            <div class="topic_content">
              <div class="markdown_body">
                <p>js 或 某些库，返回月份要用 0-11.</p>
                <p>很迷惑啊喂😂</p>
              </div>
            </div>
          </div>
          <div class="subtle">
            <span class="fade">第 1 条附言 &nbsp;·&nbsp; 16 分钟前</span>
            <div class="sep5"></div>
            <div class="topic_content">
              啊 感谢科普 确实外国不说 1 月 2 月，
              <br />还有 getYear 也是 😂
              <br />每次用的时候 都要 先输出验证一下 有点麻烦。问完问题之后 感觉我现在印象变深了。
            </div>
          </div>
          <div class="subtle">
            <span class="fade">第 2 条附言 &nbsp;·&nbsp; 14 分钟前</span>
            <div class="sep5"></div>
            <div class="topic_content">
              我刚毕业做了一段时间 java，那时候就是 用到过 Date 。
              <br />啊，所以从头到尾迷惑的原因是一致的。
            </div>
          </div>
          <div class="topic_buttons">
            <div class="fr topic_stats" style="padding-top: 4px;">954 次点击 &nbsp;∙&nbsp; 1 人收藏 &nbsp;</div>
            <a href="/favorite/topic/661469?t=hqyjdpqtswulyeejbxrjvwcpobakqquq" class="tb">加入收藏</a> &nbsp;
            <a
              href="#;"
              onclick="window.open('https://twitter.com/share?url=https://www.v2ex.com/t/661469?r=jayce981008&amp;related=v2ex&amp;hashtags=js&amp;text=为什么 new Date().getMonth()返回 0-11', '_blank', 'width=550,height=370'); recordOutboundLink(this, 'Share', 'twitter.com');"
              class="tb"
            >Tweet</a> &nbsp;
            <a
              href="#;"
              onclick="window.open('https://service.weibo.com/share/share.php?url=https://www.v2ex.com/t/661469?r=jayce981008&amp;title=V2EX%20-%20为什么 new Date().getMonth()返回 0-11', '_blank', 'width=550,height=370'); recordOutboundLink(this, 'Share', 'weibo.com');"
              class="tb"
            >Weibo</a> &nbsp;
            <a
              href="#;"
              onclick="if (confirm('确定不想再看到这个主题？')) { location.href = '/ignore/topic/661469?once=14996'; }"
              class="tb"
            >忽略主题</a>
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
  validate({ params }) {
    // 必须是number类型
    return /^\d+$/.test(params.id)
  }
})
</script>
