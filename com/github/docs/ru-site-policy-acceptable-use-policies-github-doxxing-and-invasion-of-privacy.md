GitHub Doxxing и вторжение в частную жизнь - GitHub Docs(function(){
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
4. [Doxxing и вторжение в частную жизнь](/ru/site-policy/acceptable-use-policies/github-doxxing-and-invasion-of-privacy)

Scroll breadcrumbs right

[Site policy](/ru/site-policy)
----------

GitHub Doxxing и вторжение в частную жизнь
==========

Копировать как Markdown

Не публикуйте личную информацию других людей. Сюда входит следующее:

* Личные, частные адреса электронной почты
* Номера телефонов
* Физические адреса или другая частная информация о местоположении
* Информация о банковском счете или номера кредитных карт
* Номера социального страхования/национальные идентификационные номера
* Пароли
* Сведения об избирателях
* Медицинская информация и персональные биометрические данные
* Другая личная информация, которая может представлять угрозу безопасности.

Мы можем рассматривать другую информацию, такую как фотографии или видео, которые были сняты или распространены без согласия субъекта, как вторжение в частную жизнь, особенно когда такой материал представляет угрозу безопасности субъекта, например, в случае запугивания или преследования.

GitHub примет во внимание контекст, а также то, является ли опубликованное содержимое общедоступным в другом месте. Обратите внимание, однако, что, хотя обмен общедоступным содержимым может не являться нарушением этой политики, если информация передается с намерением беспокоить или подстрекать к другому оскорбительному поведению, это может нарушать наш запрет на [издевательства и домогательства](/ru/site-policy/acceptable-use-policies/github-bullying-and-harassment).

Дополнительные сведения, а также информация о том, как сообщить о нарушении, приведены в нашей [Политике удаления частной информации](/ru/site-policy/content-removal-policies/github-private-information-removal-policy) и наших инструкциях по [Сообщению о нарушениях](/ru/communities/maintaining-your-safety-on-github/reporting-abuse-or-spam).
