Политики безопасности - GitHub Docs(function(){
var MODES=["auto","light","dark"],THEMES=["light","dark","dark\_dimmed","dark\_high\_contrast"],D={"colorMode":"auto","lightTheme":"light","darkTheme":"dark"};
var css=D;
try{
var m=document.cookie.match(new RegExp('(?:^|; )'+"color\_mode"+'=([^;]\*)'));
if(m){
var p=JSON.parse(decodeURIComponent(m[1]));
var fMode=function(x){return MODES.indexOf(x)\>-1?x:null;};
var fTheme=function(t){if(!t)return null;if(THEMES.indexOf(t.name)\>-1)return t.name;if(THEMES.indexOf(t.color\_mode)\>-1)return t.color\_mode;return null;};
css={colorMode:fMode(p.color\_mode)||D.colorMode,lightTheme:fTheme(p.light\_theme)||D.lightTheme,darkTheme:fTheme(p.dark\_theme)||D.darkTheme};
}
}catch(e){}
try{
var h=document.documentElement;
h.setAttribute('data-color-mode',css.colorMode);
h.setAttribute('data-light-theme',css.lightTheme);
h.setAttribute('data-dark-theme',css.darkTheme);
}catch(e){}
})();

[Skip to main content](#main-content)

[Домашняя страница](/ru)

[Site policy](/ru/site-policy)
----------

* [Политика сайта](/ru/site-policy)/
* [Политики безопасности](/ru/site-policy/security-policies)

Политики безопасности
==========

[Скоординированное раскрытие уязвимостей безопасности](/ru/site-policy/security-policies/coordinated-disclosure-of-security-vulnerabilities)
----------

[Программа GitHub Bug Bounty Legal Safe Harbour](/ru/site-policy/security-policies/github-bug-bounty-program-legal-safe-harbor)
----------

[Описание GitHub SIRT RFC 2350](/ru/site-policy/security-policies/github-sirt-description-rfc-2350)
----------
