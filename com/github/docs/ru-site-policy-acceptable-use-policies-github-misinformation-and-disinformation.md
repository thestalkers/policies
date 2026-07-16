Неправильная информация и дезинформация на GitHub - Документация GitHub(function(){
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

Свернуть боковую панельРазвернуть боковую панель

Прокрутите панели навигации слева

1. [Домашняя страница](/ru)
2. [Политика сайта](/ru/site-policy)
3. [Политика допустимого использования](/ru/site-policy/acceptable-use-policies)
4. [Политика в отношении дезинформации](/ru/site-policy/acceptable-use-policies/github-misinformation-and-disinformation)

Прокрутите страницы вправо

[Site policy](/ru/site-policy)
----------

Неправильная информация и дезинформация на GitHub
==========

Копировать как Markdown

Вы не можете публиковать содержимое, которое представляет искаженное представление о реальности: неточное или ложное (неправильная информация) или преднамеренно вводящее в заблуждение (дезинформация), если такое содержимое может нанести вред обществу или помешать честным и равным возможностям в свободном и открытом обществе. Это может включать следующее:

* Неточные или научно не обоснованные медицинские заявления, что угрожает здоровью или безопасности общества
* Манипулятивные медиа, аудио или визуальные, которые могут вводить в заблуждение, что может нанести ущерб общественным интересам.
* Ложный или вводящий в заблуждение контент, который может помешать возможностям человека участвовать в общественной жизни.
* Необоснованные утверждения, которые могут пропагандировать ненависть или целенаправленное преследование определенных групп людей.

Мы поощряем активное участие в выражении идей, точек зрения и личного опыта и не можем оспаривать личные мнения или наблюдения. Как правило, мы разрешаем пародию и сатиру, если это соответствует нашим [Политикам допустимого использования](/ru/site-policy/acceptable-use-policies/github-acceptable-use-policies), и мы считаем, что контекст играет важную роль в том, как информация воспринимается и понимается. При проверке контента в соответствии с этой политикой GitHub будет учитывать влияние различных факторов, которые могут помочь сориентировать зрителя, например: предоставлен ли контент с четкими заявлениями об отказе от ответственности и ссылками на достоверные источники, или включает другие детали, удостоверяющие точность предоставляемой информации.
