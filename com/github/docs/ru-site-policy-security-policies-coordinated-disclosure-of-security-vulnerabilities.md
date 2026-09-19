Скоординированное раскрытие уязвимостей безопасности - Документация GitHub(function(){
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
3. [Политики безопасности](/ru/site-policy/security-policies)
4. Скоординированное раскрытие уязвимостей безопасности

Прокрутите страницы вправо

[Site policy](/ru/site-policy)
----------

Скоординированное раскрытие уязвимостей безопасности
==========

Копирование markdown

Мы хотим, чтобы GitHub был безопасным для всех. Если вы обнаружили уязвимость безопасности в GitHub, мы будем признательны за вашу помощь в скоординированном раскрытии ее нам.

[Бонусная программа](#bounty-program)
----------

Как и некоторые другие крупные компании-разработчики программного обеспечения, GitHub предоставляет вознаграждение за обнаружение ошибок, чтобы лучше взаимодействовать с исследователями безопасности. Идея проста: знатоки программ и исследователи проблем безопасности (как вы) находят уязвимости и сообщают о них в рамках нашего установленного процесса скоординированного раскрытия информации. Затем, чтобы признать значительные усилия, которые эти исследователи часто прилагают при поиске ошибок, мы вознаграждаем их наличными.

Посетите сайт [GitHub Bug Bounty](https://bounty.github.com) для получения подробных сведений о вознаграждениях и ознакомьтесь с полными условиями [Политики Safe Harbor](/ru/site-policy/security-policies/github-bug-bounty-program-legal-safe-harbor). Желаем удачной охоты!
