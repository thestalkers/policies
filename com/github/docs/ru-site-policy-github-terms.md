Условия GitHub - GitHub Docs(function(){
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

[Домашняя страница](/ru)

[Site policy](/ru/site-policy)
----------

1. [Политика сайта](/ru/site-policy)
2. [Условия GitHub](/ru/site-policy/github-terms)

Условия GitHub
==========

[Условия обслуживания GitHub](/ru/site-policy/github-terms/github-terms-of-service)
----------

[Корпоративные условия обслуживания GitHub](/ru/site-policy/github-terms/github-corporate-terms-of-service)
----------

[Условия GitHub для дополнительных продуктов и функций](/ru/site-policy/github-terms/github-terms-for-additional-products-and-features)
----------

[Правила сообщества GitHub](/ru/site-policy/github-terms/github-community-guidelines)
----------

[Правила поведения в сообществе GitHub](/ru/site-policy/github-terms/github-community-code-of-conduct)
----------

[Условия лицензии GitHub Pre-release](/ru/site-policy/github-terms/github-pre-release-license-terms)
----------

[Предварительные версии на GitHub, на которые распространяется DPA](/ru/site-policy/github-terms/github-dpa-previews)
----------

[Дополнительные условия GitHub Sponsors](/ru/site-policy/github-terms/github-sponsors-additional-terms)
----------

[Договор с зарегистрированным разработчиком GitHub](/ru/site-policy/github-terms/github-registered-developer-agreement)
----------

[Условия предоставления услуг GitHub Marketplace](/ru/site-policy/github-terms/github-marketplace-terms-of-service)
----------

[Соглашение с разработчиком GitHub Marketplace](/ru/site-policy/github-terms/github-marketplace-developer-agreement)
----------

[Условия исследовательской программы GitHub](/ru/site-policy/github-terms/github-research-program-terms)
----------

[Условия использования приложений GitHub с открытым исходным кодом](/ru/site-policy/github-terms/github-open-source-applications-terms-and-conditions)
----------

[Условия проведения мероприятий на GitHub](/ru/site-policy/github-terms/github-event-terms)
----------

[Правила поведения на мероприятиях GitHub](/ru/site-policy/github-terms/github-event-code-of-conduct)
----------

[Договор об использовании GitHub в образовательных целях](/ru/site-policy/github-terms/github-educational-use-agreement)
----------

[Политика разработчика расширений GitHub Copilot](/ru/site-policy/github-terms/github-copilot-extension-developer-policy)
----------

[Соглашение о партнерской программе сканирования секретов GitHub](/ru/site-policy/github-terms/github-secret-scanning-partner-program-agreement)
----------
