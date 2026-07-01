GitHub 条款 - GitHub 文档(function(){
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

[主](/zh)

[Site policy](/zh/site-policy)
----------

* [站点政策](/zh/site-policy)/
* [GitHub 条款](/zh/site-policy/github-terms)

GitHub 条款
==========

[GitHub 服务条款](/zh/site-policy/github-terms/github-terms-of-service)
----------

[GitHub 公司服务条款](/zh/site-policy/github-terms/github-corporate-terms-of-service)
----------

[GitHub 附加产品和功能条款](/zh/site-policy/github-terms/github-terms-for-additional-products-and-features)
----------

[GitHub 社区指导方针](/zh/site-policy/github-terms/github-community-guidelines)
----------

[GitHub 社区行为准则](/zh/site-policy/github-terms/github-community-code-of-conduct)
----------

[GitHub 预发行许可条款](/zh/site-policy/github-terms/github-pre-release-license-terms)
----------

[GitHub DPA 约束的预览版](/zh/site-policy/github-terms/github-dpa-previews)
----------

[GitHub 赞助商附加条款](/zh/site-policy/github-terms/github-sponsors-additional-terms)
----------

[GitHub 注册开发人员协议](/zh/site-policy/github-terms/github-registered-developer-agreement)
----------

[GitHub Marketplace 服务条款](/zh/site-policy/github-terms/github-marketplace-terms-of-service)
----------

[GitHub Marketplace 开发人员协议](/zh/site-policy/github-terms/github-marketplace-developer-agreement)
----------

[GitHub 研究计划条款](/zh/site-policy/github-terms/github-research-program-terms)
----------

[GitHub 开源应用程序条款和条件](/zh/site-policy/github-terms/github-open-source-applications-terms-and-conditions)
----------

[GitHub 活动条款](/zh/site-policy/github-terms/github-event-terms)
----------

[GitHub 活动行为准则](/zh/site-policy/github-terms/github-event-code-of-conduct)
----------

[GitHub 教育使用协议](/zh/site-policy/github-terms/github-educational-use-agreement)
----------

[GitHub Copilot 扩展开发人员策略](/zh/site-policy/github-terms/github-copilot-extension-developer-policy)
----------

[GitHub 机密扫描合作伙伴计划协议](/zh/site-policy/github-terms/github-secret-scanning-partner-program-agreement)
----------
