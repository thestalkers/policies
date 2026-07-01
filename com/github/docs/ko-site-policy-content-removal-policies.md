콘텐츠 제거 정책 - GitHub 문서(function(){
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

[홈](/ko)

[Site policy](/ko/site-policy)
----------

* [사이트 정책](/ko/site-policy)/
* [콘텐츠 제거 정책](/ko/site-policy/content-removal-policies)

콘텐츠 제거 정책
==========

[콘텐츠 제거 요청 제출](/ko/site-policy/content-removal-policies/submitting-content-removal-requests)
----------

[DMCA 게시 중단 정책](/ko/site-policy/content-removal-policies/dmca-takedown-policy)
----------

[GitHub 개인 정보 제거 정책](/ko/site-policy/content-removal-policies/github-private-information-removal-policy)
----------

[GitHub 상표 정책](/ko/site-policy/content-removal-policies/github-trademark-policy)
----------

[DMCA 반론 통지 제출 가이드](/ko/site-policy/content-removal-policies/guide-to-submitting-a-dmca-counter-notice)
----------

[DMCA 게시 중단 통지 제출 가이드](/ko/site-policy/content-removal-policies/guide-to-submitting-a-dmca-takedown-notice)
----------
