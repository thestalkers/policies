其他站点政策 - GitHub 文档(function(){
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
* [其他站点政策](/zh/site-policy/other-site-policies)

其他站点政策
==========

[GitHub 和贸易管制](/zh/site-policy/other-site-policies/github-and-trade-controls)
----------

[GitHub 已故用户政策](/zh/site-policy/other-site-policies/github-deceased-user-policy)
----------

[GitHub 徽标政策](/zh/site-policy/other-site-policies/github-logo-policy)
----------

[GitHub 政府下架政策](/zh/site-policy/other-site-policies/github-government-takedown-policy)
----------

[GitHub 用户名政策](/zh/site-policy/other-site-policies/github-username-policy)
----------

[用户数据法律请求准则](/zh/site-policy/other-site-policies/guidelines-for-legal-requests-of-user-data)
----------

[GitHub 帐户恢复政策](/zh/site-policy/other-site-policies/github-account-recovery-policy)
----------
