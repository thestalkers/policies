사이트 정책 설명서 - GitHub 문서(function(){
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
var q=window.matchMedia?window.matchMedia('(prefers-color-scheme: dark)'):null;
var apply=function(){
var night=css.colorMode==='auto'?!!(q&&q.matches):css.colorMode==='dark';
var theme=night?css.darkTheme:css.lightTheme;
var mode=theme.indexOf('dark')===0?'dark':'light';
h.setAttribute('data-color-mode',mode);
h.setAttribute('data-'+mode+'-theme',theme);
};
h.setAttribute('data-color-mode-preference',css.colorMode);
h.setAttribute('data-light-theme',css.lightTheme);
h.setAttribute('data-dark-theme',css.darkTheme);
apply();
if(css.colorMode==='auto'&&q){
if(q.addEventListener)q.addEventListener('change',apply);
else if(q.addListener)q.addListener(apply);
}
}catch(e){}
})();

[Skip to main content](#main-content)

[Skip to content](#main-content)

사이드바 축소

사이드바 확장

1. [홈](/ko)
2. 사이트 정책

[Site policy](/ko/site-policy)
----------

사이트 정책 설명서
==========

GitHub의 서비스 이용약관, 허용 가능한 사용 정책, 개인정보보호 취급 방침, 콘텐츠 삭제 절차 및 기타 사이트 정책을 검토합니다.

[개요](/site-policy/github-terms/github-terms-of-service)

추천됨
----------

### [GitHub 서비스 약관](/ko/free-pro-team@latest/site-policy/github-terms/github-terms-of-service) ###

### [GitHub 일반 개인정보처리방침](/ko/free-pro-team@latest/site-policy/privacy-policies/github-general-privacy-statement) ###

### [GitHub 사용 제한 정책](/ko/free-pro-team@latest/site-policy/acceptable-use-policies/github-acceptable-use-policies) ###

기사
----------

범주: 모든 범주

Follow acceptable use policies

### [다른 사용자의 경험을 방해하는 GitHub](/ko/site-policy/acceptable-use-policies/github-disrupting-the-experience-of-other-users) ###

Review company and general policies

### [법적 사용자 데이터 요청을 위한 가이드라인](/ko/site-policy/other-site-policies/guidelines-for-legal-requests-of-user-data) ###

Review privacy and security policies

### [조정된 보안 취약점 공개](/ko/site-policy/security-policies/coordinated-disclosure-of-security-vulnerabilities) ###

Review privacy and security policies

### [지원자를 위한 GitHub 글로벌 데이터 개인 정보 보호 고지](/ko/site-policy/privacy-policies/github-candidate-privacy-policy) ###

Request content removal

### [콘텐츠 제거 요청 제출](/ko/site-policy/content-removal-policies/submitting-content-removal-requests) ###

Review company and general policies

### [현대 노예제 및 미성년 노동에 반대하는 GitHub 성명서](/ko/site-policy/github-company-policies/github-statement-against-modern-slavery-and-child-labor) ###

Request content removal

### [DMCA 게시 중단 정책](/ko/site-policy/content-removal-policies/dmca-takedown-policy) ###

Request content removal

### [DMCA 게시 중단 통지 제출 가이드](/ko/site-policy/content-removal-policies/guide-to-submitting-a-dmca-takedown-notice) ###

Request content removal

### [DMCA 반론 통지 제출 가이드](/ko/site-policy/content-removal-policies/guide-to-submitting-a-dmca-counter-notice) ###

57의 1-9 표시

[Previous]()[1](#1)[2](#2)[3](#3)[4](#4)[5](#5)[6](#6)[7](#7)[Next](#2)
