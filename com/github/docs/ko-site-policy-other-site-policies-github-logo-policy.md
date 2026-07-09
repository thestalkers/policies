GitHub 로고 정책 - GitHub 문서(function(){
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
2. [다른 사이트 정책](/ko/site-policy/other-site-policies)
3. [GitHub 로고 정책](/ko/site-policy/other-site-policies/github-logo-policy)

GitHub 로고 정책
==========

Markdown으로 복사

일부 시나리오에서는 귀사의 웹 사이트 또는 제3자 애플리케이션에 GitHub 로고를 추가할 수 있습니다. 로고 사용에 대한 자세한 내용 및 구체적인 지침은 [GitHub 로고 및 사용 페이지](https://github.com/logos)를 참조하세요.

또한 octocat을 개인 아바타로 사용하거나 웹 사이트에서 사용하여 GitHub 계정에 연결할 수 있지만 회사나 현재 빌드 중인 제품에는 사용할 수 없습니다. GitHub에서는 [Octodex](https://octodex.github.com/)에 광범위한 octocat 컬렉션을 제공합니다. Octodex에서 octocat을 사용하는 방법에 대한 자세한 내용은 [Octodex FAQ](https://octodex.github.com/faq/)를 참조하세요.
