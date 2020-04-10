<template>
  <div id="Top">
    <div class="content">
      <div style="padding-top: 6px;">
        <table width="100%" cellspacing="0" cellpadding="0" border="0">
          <tbody>
            <tr>
              <td width="110" align="left">
                <a href="/" name="top" title="way to explore">
                  <div id="Logo"></div>
                </a>
              </td>
              <td width="auto" align="left">
                <div id="Search">
                  <form
                    action="https://www.google.com"
                    onsubmit="return dispatch()"
                    target="_blank"
                  >
                    <div id="qbar">
                      <input
                        type="text"
                        maxlength="40"
                        name="q"
                        id="q"
                        value
                        onfocus="$('#qbar').addClass('qbar_focus')"
                        onblur="$('#qbar').removeClass('qbar_focus')"
                      />
                    </div>
                  </form>
                </div>
              </td>
              <td style="padding-top: 2px;" width="570" align="right">
                <a href="/" class="top">首页</a>&nbsp;&nbsp;&nbsp;
                <a href="/signup" class="top">注册</a>&nbsp;&nbsp;&nbsp;
                <a href="/signin" class="top">登录</a>
              </td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
  </div>
</template>
