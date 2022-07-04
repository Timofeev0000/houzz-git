<template>
    <div>
	   <div id="fb-root" class=" fb_reset">
	      <div style="position: absolute; top: -10000px; width: 0px; height: 0px;"></div>
	   </div>
	   <div class="hz-main">
	      <div class="hz-header">
	         <div id="headerContainer" scopeid="headerContainer" class="comp-box">
	            <div id="navHeader" class="authflow signin-header--parent ">
	               <div class="houzz-header  ">
	                  <div class="container">
	                     <div class="signin-header">
	                        <a id="navHome" objid="navHome" class="brand " href="/">
	                        <img class="svg-houzz-logo" style="" src="https://st.hzcdn.com/res/27580096/ru-RU/pic/houzz_logo.svg?v=27580096" width="114" height="26">        </a>
	                        <ul class="list-unstyled header-nav attach-right">
	                        </ul>
	                     </div>
	                  </div>
	               </div>
	            </div>
	         </div>
	      </div>
	      <div id="mainArea">
	         <div id="mainContent">
	            <div class="container">
	               <div class="hz-main-contents">
	                  <div id="web-body" scopeid="web-body" class="comp-box">
	                     <div id="mainContent" class="signin">
	                        <div id="authFlowContainer">
	                           <h1 class="authFlowTitle header-1">Вход в Houzz</h1>
	                           <div id="signinErrors" class="authFlowError"></div>
	                           <table>
	                              <tbody>
	                                 <tr>
	                                    <td>
	                                       <div class="dlgUserDetails">
	                                          <form id="signinForm" scopeid="sign_in_form" onsubmit="return true;" method="POST" action="javascript:;" novalidate="">
	                                             <div class="authFlowFieldTitle text-l mts mbs">Имя пользователя или email</div>
	                                             <div class="dlgInputRow">
	                                                <input class="authFlowInput form-control" placeholder="" id="username" name="username" value="" type="email" autocorrect="off" autocapitalize="off">
	                                             </div>
	                                             <div class="authFlowFieldTitle text-l mts mbs">Пароль</div>
	                                             <div class="dlgInputRow">
	                                                <input class="authFlowInput" placeholder="" id="password" name="password" type="password">
	                                             </div>
	                                             <div class="checkbox-block">
	                                               <input type="checkbox" class="checkbox-input">
	                                               <p>Запомнить меня</p>
	                                             </div>
	                                             <div class="dlgInputRow">
	                                                <input id="signIn" type="submit" style="width: 100%; font-size: 15px;" class="btn btn-primary btn-lg btn-block text-l trackMe" value="Войти" name="submit" compid="sign_in_btn">
	                                             </div>
	                                             <div>
	                                                <a class="forgotPwdLink text-primary subHeadingText icon-wrap trackMe" compid="forgot_pw_link" href="https://www.houzz.ru/forgotPassword" target="_new">Забыли пароль?<span class="more-icon"></span></a>
	                                             </div>
	                                          </form>
	                                       </div>
	                                    </td>
	                                    <td>
	                                       <div id="dlgFbSignIn">
	                                          <div class="pic-wrapper">
	                                             <img src="https://st.hzcdn.com/static_ru-RU/assets/login_chill.png" alt="">
	                                          </div>
	                                       </div>
	                                    </td>
	                                 </tr>
	                                 <tr>
	                                    <td colspan="2">
	                                       <div class="dlgFbSubMessage">У вас нет учетной записи? <a class="colorLink icon-wrap mls" href="https://www.houzz.ru/signup/m=0/u=aHR0cHM6Ly93d3cuaG91enoucnUv/t=39/s=aG91enotbG9naW4%3D/d=web/fl=a/">Зарегистрироваться<span class="more-icon"></span></a></div>
	                                       <div id="tos" class="tos">
	                                          <p>Регистрируясь, входя или продолжая, я соглашаюсь с <a href="https://www.houzz.ru/termsOfUse" target="_blank" class="colorLink">Условиями использования Houzz</a> и принимаю <a href="https://www.houzz.ru/privacyPolicy" target="_blank" class="colorLink">Политику конфиденциальности Houzz</a>. Я согласен с тем, что Houzz может использовать мой адрес электронной почты в маркетинговых целях. Я могу отказаться от этого в любое время через мои <a href="https://www.houzz.ru/privacy-settings" target="_blank" class="colorLink">настройки</a>.</p>
	                                       </div>
	                                    </td>
	                                 </tr>
	                              </tbody>
	                           </table>
	                        </div>
	                     </div>
	                  </div>
	               </div>
	            </div>
	         </div>
	      </div>
	   </div>
	</div>
</template>

<script>

export default {
  name: 'FormRegister'
}
</script>

<style>
  body {
    font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
    font-size: 14px;
    line-height: 1.42857143;
    color: #333333;
    background-color: #ffffff;
    -webkit-font-smoothing: antialiased;
    -webkit-tap-highlight-color: rgba(0,0,0,0);
    height: 100%;
    margin: 0;
    display: block;
}

.fb_reset {
    background: none;
    border: 0;
    border-spacing: 0;
    color: #000;
    cursor: auto;
    direction: ltr;
    font-family: "lucida grande", tahoma, verdana, arial, sans-serif;
    font-size: 11px;
    font-style: normal;
    font-variant: normal;
    font-weight: normal;
    letter-spacing: normal;
    line-height: 1;
    margin: 0;
    overflow: visible;
    padding: 0;
    text-align: left;
    text-decoration: none;
    text-indent: 0;
    text-shadow: none;
    text-transform: none;
    visibility: visible;
    white-space: normal;
    word-spacing: normal;
}

.fb_reset>div {
    overflow: hidden;
}

.hz-main {
    min-height: 100%;
    height: 100%;
}

.simple-header #navHeader {
    position: relative;
}

#navHeader {
    position: fixed;
    top: 0;
    width: 100%;
    z-index: 1499;
    backface-visibility: hidden;
    height: 60px;
}

.houzz-header {
    background: #fff;
    height: 60px;
    border-bottom: 1px solid #e6e6e6;
    position: relative;
    z-index: 2;
}

.simple-header .houzz-header > .container {
    padding-left: 0;
}

.signin-header--parent .houzz-header .container {
    width: 1000px;
}

.authflow .houzz-header > .container, .authflow ul#tabs {
    width: 780px;
    margin: 0 auto;
}

.container {
    margin-right: auto;
    margin-left: auto;
    width: 1000px;
}

.signin-header--parent .signin-header {
    width: 560px;
    margin: 0 auto;
}

#navHeader #navHome {
    width: auto;
}

#navHome {
    float: left;
    margin: 0;
    height: 60px;
    width: 140px;
    position: relative;
}

a {
    color: #333333;
    text-decoration: none;
}

.houzz-header .svg-houzz-logo {
    margin-top: 13px;
    width: 114px;
    height: 26px;
}

img {
    vertical-align: middle;
}

.houzz-header .header-nav.attach-right {
    float: right;
}

.houzz-header .header-nav {
    padding-left: 0;
    float: left;
    position: relative;
    list-style: none;
    margin: 0 0 0 5px;
    font-size: 13px;
}

/*MAIN*/

#mainArea {
    min-height: 100%;
    width: 100%;
}

.simple-header #mainContent {
    padding-top: 0;
}

#mainContent {
    padding-top: 26px;
    min-height: 600px;
}

#mainContent {
    padding-bottom: 462px;
}

.container {
    margin-right: auto;
    margin-left: auto;
    width: 1000px;
}

.simple-header #mainContent {
    padding-top: 0;
}

#mainContent.signin {
    width: 780px;
    margin-right: auto;
    margin-left: auto;
    padding-top: 0;
}

#mainContent {
    padding-top: 26px;
    min-height: 600px;
}

#mainContent {
    padding-bottom: 462px;
}

#mainContent .signin #authFlowContainer {
    margin: 0 auto;
    width: 560px;
}

#mainContent.signin #authFlowContainer {
    margin-bottom: 60px;
    margin-top: 50px;
}

.ru-RU.hbs .header-1 {
    font-weight: 200;
}

.header-1 {
    font-size: 30px;
    font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
    font-weight: 300;
}

.header-1, .header-2, .header-3, .header-4, .header-5, .header-6 {
    margin: 16px 0;
    line-height: 1.2;
}

.authFlowTitle {
    text-align: left;
    width: 100%;
}

.authFlowError {
    color: red;
    margin: 4px 0px 4px 0px;
    min-height: 18px;
    overflow: visible;
    white-space: nowrap;
}

table {
    background-color: transparent;
}

tr {
    display: table-row;
    vertical-align: inherit;
    border-color: inherit;
}

td, th {
    padding: 0;
}

#mainContent .signin .dlgUserDetails {
    margin-right: 20px;
    border-right: 1px solid #eaeaea;
    padding: 10px 25px 5px 0;
    margin-bottom: 24px;
}

.signup .dlgUserDetails, .signin .dlgUserDetails {
    margin-top: 0px;
    width: 315px;
    margin-right: 50px;
}

.mbs {
    margin-bottom: 5px;
}

.mts {
    margin-top: 5px;
}

.text-l {
    font-size: 16px;
}

.dlgInputRow {
    overflow: hidden;
    margin-bottom: 15px;
}

#mainContent .signin .dlgUserDetails input {
    height: 40px;
}

input.authFlowInput {
    margin-bottom: 0px;
}

.form-control, input[type=text], input[type=password], input[type=email], input[type=tel] {
    display: block;
    width: 100%;
    height: 30px;
    padding: 4px 6px;
    font-size: 14px;
    line-height: 1.42857143;
    color: #555555;
    background-color: #ffffff;
    background-image: none;
    border: 1px solid #ccc;
    border-radius: 3px;
    -webkit-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
    -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
    transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
}

.radio, .checkbox {
    position: relative;
    display: block;
    margin-top: 10px;
    margin-bottom: 10px;
}

.btn-primary {
    color: #ffffff;
    background-color: #007562;
    border-color: #007562;
}

.btn {
    display: inline-block;
    margin-bottom: 0;
    font-weight: bold;
    text-align: center;
    vertical-align: middle;
    touch-action: manipulation;
    cursor: pointer;
    background-image: none;
    border: 1px solid transparent;
    white-space: nowrap;
    padding: 4px 12px;
    font-size: 14px;
    line-height: 1.42857143;
    border-radius: 3px;
    -webkit-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none;
}

.text-primary {
    color: #007562;
    font-size: 14px;
}

.colorLink {
    color: #007562;
}

#mainContent .signin .dlgFbSubMessage {
    padding: 15px 0;
    margin: 0;
    width: 100%;
    border-top: 1px solid #eaeaea;
}

.tos p {
    margin: 0 0 10px;
}

.signin .tos {
    font-size: 12px;
    line-height: normal;
    margin-top: 5px;
    width: 620px;
}

#mainContent .signin #authFlowContainer .pic-wrapper img {
    width: 100%;
    min-width: 264px;
}

.authFlowFieldTitle.subHeadingText {
    margin-bottom: 0px;
}

#mainContent .signin .custom-checkable-input {
    padding-left: 0;
    height: 100%;
    line-height: inherit;
}

.checkbox label {
    min-height: 20px;
    padding-left: 20px;
    margin-bottom: 0;
    font-weight: normal;
    cursor: pointer;
}

.custom-checkable-input .custom-checkable-input__label {
    -webkit-transform: translateX(-50%) translateY(-50%);
    -ms-transform: translateX(-50%) translateY(-50%);
    transform: translateX(-50%) translateY(-50%); 
    position: absolute; 
    top: 50%; 
    left: 50%;
    max-height: 2.8em; 
    line-height: 1.4em;
    overflow: hidden; 
    width: 100%; 
}

.checkbox-block {
    display: flex;
}

.checkbox-block p {
    font-size: 15px;
    margin-top: 9px;
    margin-left: 5px;
}

.checkbox-block input {
    background-color: #007562;
}
</style>