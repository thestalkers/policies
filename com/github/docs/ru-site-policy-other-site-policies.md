Другие правила сайта - Документация GitHub(function(){
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

Свернуть боковую панельРазвернуть боковую панель

Прокрутите панели навигации слева

1. [Домашняя страница](/ru)
2. [Политика сайта](/ru/site-policy)
3. Другие правила сайта

Прокрутите страницы вправо

[Site policy](/ru/site-policy)
----------

Другие правила сайта
==========

[GitHub и управление торговлей](/ru/site-policy/other-site-policies/github-and-trade-controls)
----------

[Политика умерших пользователей GitHub](/ru/site-policy/other-site-policies/github-deceased-user-policy)
----------

[Политика логотипа GitHub](/ru/site-policy/other-site-policies/github-logo-policy)
----------

[Политика GitHub в отношении правительственных запретов](/ru/site-policy/other-site-policies/github-government-takedown-policy)
----------

[Политика имени пользователя GitHub](/ru/site-policy/other-site-policies/github-username-policy)
----------

[Руководство по юридическим запросам пользовательских данных](/ru/site-policy/other-site-policies/guidelines-for-legal-requests-of-user-data)
----------

[Политика восстановления учетных записей GitHub](/ru/site-policy/other-site-policies/github-account-recovery-policy)
----------
