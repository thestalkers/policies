개인정보보호정책 - GitHub 문서(function(){
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

Collapse sidebarExpand sidebar

Scroll breadcrumbs left

1. [홈](/ko)
2. [사이트 정책](/ko/site-policy)
3. [개인정보보호정책](/ko/site-policy/privacy-policies)

Scroll breadcrumbs right

[Site policy](/ko/site-policy)
----------

개인정보보호정책
==========

[GitHub 일반 개인정보처리방침](/ko/site-policy/privacy-policies/github-general-privacy-statement)
----------

[GitHub 보조 처리자](/ko/site-policy/privacy-policies/github-subprocessors)
----------

[GitHub 쿠키](/ko/site-policy/privacy-policies/github-cookies)
----------

[지원자를 위한 GitHub 글로벌 데이터 개인 정보 보호 고지](/ko/site-policy/privacy-policies/github-candidate-privacy-policy)
----------
