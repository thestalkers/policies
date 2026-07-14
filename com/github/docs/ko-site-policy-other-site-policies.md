다른 사이트 정책 - GitHub 문서(function(){
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
3. [다른 사이트 정책](/ko/site-policy/other-site-policies)

Scroll breadcrumbs right

[Site policy](/ko/site-policy)
----------

다른 사이트 정책
==========

[GitHub와 무역 통제](/ko/site-policy/other-site-policies/github-and-trade-controls)
----------

[GitHub 사망 사용자 정책](/ko/site-policy/other-site-policies/github-deceased-user-policy)
----------

[GitHub 로고 정책](/ko/site-policy/other-site-policies/github-logo-policy)
----------

[GitHub 정부 게시 중단 정책](/ko/site-policy/other-site-policies/github-government-takedown-policy)
----------

[GitHub 사용자 이름 정책](/ko/site-policy/other-site-policies/github-username-policy)
----------

[법적 사용자 데이터 요청을 위한 가이드라인](/ko/site-policy/other-site-policies/guidelines-for-legal-requests-of-user-data)
----------

[GitHub 계정 복구 정책](/ko/site-policy/other-site-policies/github-account-recovery-policy)
----------
