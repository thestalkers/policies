GitHub 약관 - GitHub 문서(function(){
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

1. [사이트 정책](/ko/site-policy)
2. [GitHub 약관](/ko/site-policy/github-terms)

GitHub 약관
==========

[GitHub 서비스 약관](/ko/site-policy/github-terms/github-terms-of-service)
----------

[GitHub 기업 서비스 약관](/ko/site-policy/github-terms/github-corporate-terms-of-service)
----------

[GitHub 추가 제품 및 기능 약관](/ko/site-policy/github-terms/github-terms-for-additional-products-and-features)
----------

[GitHub 커뮤니티 지침](/ko/site-policy/github-terms/github-community-guidelines)
----------

[GitHub 커뮤니티 준수 사항](/ko/site-policy/github-terms/github-community-code-of-conduct)
----------

[GitHub 시험판 사용 조건](/ko/site-policy/github-terms/github-pre-release-license-terms)
----------

[GitHub DPA 포함 미리 보기](/ko/site-policy/github-terms/github-dpa-previews)
----------

[GitHub Sponsors 추가 약관](/ko/site-policy/github-terms/github-sponsors-additional-terms)
----------

[GitHub 등록 개발자 계약](/ko/site-policy/github-terms/github-registered-developer-agreement)
----------

[GitHub Marketplace 서비스 약관](/ko/site-policy/github-terms/github-marketplace-terms-of-service)
----------

[GitHub Marketplace 개발자 계약](/ko/site-policy/github-terms/github-marketplace-developer-agreement)
----------

[GitHub Research 프로그램 약관](/ko/site-policy/github-terms/github-research-program-terms)
----------

[GitHub 오픈 소스 애플리케이션 계약조건](/ko/site-policy/github-terms/github-open-source-applications-terms-and-conditions)
----------

[GitHub 이벤트 계약](/ko/site-policy/github-terms/github-event-terms)
----------

[GitHub 이벤트 준수 사항](/ko/site-policy/github-terms/github-event-code-of-conduct)
----------

[GitHub 교육 사용 규약](/ko/site-policy/github-terms/github-educational-use-agreement)
----------

[GitHub Copilot 확장 개발자 정책](/ko/site-policy/github-terms/github-copilot-extension-developer-policy)
----------

[GitHub 비밀 검사 파트너 프로그램 계약](/ko/site-policy/github-terms/github-secret-scanning-partner-program-agreement)
----------
