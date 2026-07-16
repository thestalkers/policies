GitHub 회사 정책 - GitHub 문서(function(){
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

사이드바 축소사이드바 확장

경로를 왼쪽으로 스크롤

1. [홈](/ko)
2. [사이트 정책](/ko/site-policy)
3. [GitHub 회사 정책](/ko/site-policy/github-company-policies)

이동 경로를 오른쪽으로 스크롤

[Site policy](/ko/site-policy)
----------

GitHub 회사 정책
==========

[현대 노예제 및 미성년 노동에 반대하는 GitHub 성명서](/ko/site-policy/github-company-policies/github-statement-against-modern-slavery-and-child-labor)
----------

[GitHub 뇌물 방지 방침](/ko/site-policy/github-company-policies/github-anti-bribery-statement)
----------

[GitHub GPL 협력 약정](/ko/site-policy/github-company-policies/github-gpl-cooperation-commitment)
----------

[GitHub 선물 및 접대 정책](/ko/site-policy/github-company-policies/github-gifts-and-entertainment-policy)
----------
