조정된 보안 취약점 공개 - GitHub 문서(function(){
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
3. [보안 정책](/ko/site-policy/security-policies)
4. [조정된 보안 취약점 공개](/ko/site-policy/security-policies/coordinated-disclosure-of-security-vulnerabilities)

Scroll breadcrumbs right

[Site policy](/ko/site-policy)
----------

조정된 보안 취약점 공개
==========

Markdown으로 복사

당사는 모두에게 안전한 GitHub를 유지하고자 합니다. GitHub에서 보안 취약점을 발견한 경우, 이를 조정된 방식으로 공개해주시면 고맙겠습니다.

[보상금 프로그램](#bounty-program)
----------

GitHub는 다른 여러 대형 소프트웨어 업체들과 마찬가지로 보안 연구원과 더 잘 협력할 수 있도록 보안 취약점 보상금을 제공합니다. 개념은 간단합니다. 해커 및 (여러분과 같은) 보안 연구원은 조정된 공개 과정을 통해 취약점을 찾고 보고합니다. 그런 다음, 버그를 추적하는 보안 연구원의 공로를 인정하기 위해 일정 현금 보상을 지급합니다.

보상금에 관한 자세한 내용은 [GitHub 보안 취약점 보상금](https://bounty.github.com) 사이트를 확인하고, 당사의 포괄적인 [법률 세이버 하버 정책](/ko/site-policy/security-policies/github-bug-bounty-program-legal-safe-harbor) 조건도 검토하세요. 즐거운 시간 되시길 바랍니다!
