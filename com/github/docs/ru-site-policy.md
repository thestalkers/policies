Документация по политике сайта - Документация GitHub(function(){
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

Свернуть боковую панель

Развернуть боковую панель

1. [Домашняя страница](/ru)
2. Политика сайта

[Site policy](/ru/site-policy)
----------

Документация по политике сайта
==========

Просмотрите условия предоставления услуг GitHub, политику допустимого использования, практики конфиденциальности, процедуры удаления контента и другие политики сайта.

[Обзор](/site-policy/github-terms/github-terms-of-service)

Рекомендуемая конфигурация
----------

### [Условия обслуживания GitHub](/ru/free-pro-team@latest/site-policy/github-terms/github-terms-of-service) ###

### [Общие заявления о конфиденциальности GitHub](/ru/free-pro-team@latest/site-policy/privacy-policies/github-general-privacy-statement) ###

### [Политики допустимого использования GitHub](/ru/free-pro-team@latest/site-policy/acceptable-use-policies/github-acceptable-use-policies) ###

Статьи
----------

Категория: Все категории

Follow acceptable use policies

### [Активное вредоносное ПО или эксплойты GitHub](/ru/site-policy/acceptable-use-policies/github-active-malware-or-exploits) ###

Follow acceptable use policies

### [Апелляция GitHub и восстановление](/ru/site-policy/acceptable-use-policies/github-appeal-and-reinstatement) ###

Review privacy and security policies

### [Глобальное уведомление о конфиденциальности данных для кандидатов на GitHub](/ru/site-policy/privacy-policies/github-candidate-privacy-policy) ###

Review product and program terms

### [Договор об использовании GitHub в образовательных целях](/ru/site-policy/github-terms/github-educational-use-agreement) ###

Review product and program terms

### [Договор с зарегистрированным разработчиком GitHub](/ru/site-policy/github-terms/github-registered-developer-agreement) ###

Review privacy and security policies

### [Дополнительные обработчики данных GitHub](/ru/site-policy/privacy-policies/github-subprocessors) ###

Review product and program terms

### [Дополнительные условия GitHub Sponsors](/ru/site-policy/github-terms/github-sponsors-additional-terms) ###

Review company and general policies

### [Заявление GitHub о борьбе со взяточничеством](/ru/site-policy/github-company-policies/github-anti-bribery-statement) ###

Review company and general policies

### [Заявление GitHub против современного рабства и детского труда](/ru/site-policy/github-company-policies/github-statement-against-modern-slavery-and-child-labor) ###

Отображение {начало}-{конец} {всего}

[Previous]()[1](#1)[2](#2)[3](#3)[4](#4)[5](#5)[6](#6)[7](#7)[Next](#2)
