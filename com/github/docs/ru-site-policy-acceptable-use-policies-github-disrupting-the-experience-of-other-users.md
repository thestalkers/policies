GitHub мешает работе других пользователей - GitHub Docs(function(){
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

1. [Домашняя страница](/ru)
2. [Политика сайта](/ru/site-policy)
3. [Политика допустимого использования](/ru/site-policy/acceptable-use-policies)
4. [Помехи работе других пользователей](/ru/site-policy/acceptable-use-policies/github-disrupting-the-experience-of-other-users)

Scroll breadcrumbs right

[Site policy](/ru/site-policy)
----------

GitHub мешает работе других пользователей
==========

Копировать как Markdown

Быть частью сообщества означает осознавать, как ваше поведение влияет на других, и участвовать в осмысленном и продуктивном взаимодействии с людьми и платформой, на которую они полагаются.

Мы не допускаем поведения, которое существенно или постоянно мешает работе других пользователей. Сюда входит следующее:

* Размещение комментариев не по теме
* Открытие пустых или бессмысленных задач или запросов на включение
* Запуск и/или подписка на учетные записи или репозитории в большом объеме за короткий период времени
* Создание бессмысленных или неуместных обзоров кода
* Взаимодействие с функциями платформы таким образом, что это приводит к чрезмерным уведомлениям других пользователей.
* Использование любой другой функции платформы таким образом, который создает сбои

Хотя мы призываем сопровождающих модерировать свои собственные проекты на индивидуальной основе, персонал GitHub может принять дополнительные ограничительные меры в отношении учетных записей, которые ведут себя подобным образом.

Обратите внимание, что вышеуказанное поведение может также нарушать другие ограничения в нашей [Политике допустимого использования](/ru/site-policy/acceptable-use-policies/github-acceptable-use-policies). Например, в зависимости от характера и тяжести деятельности она может повышаться до уровня [издевательства и домогательства](/ru/site-policy/acceptable-use-policies/github-bullying-and-harassment).
