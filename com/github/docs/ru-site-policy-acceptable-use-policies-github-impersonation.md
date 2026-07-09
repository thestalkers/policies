Имперсонация GitHub - GitHub Docs(function(){
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
2. [Политика допустимого использования](/ru/site-policy/acceptable-use-policies)
3. [Имперсонация](/ru/site-policy/acceptable-use-policies/github-impersonation)

Имперсонация GitHub
==========

Копировать как Markdown

Вы не имеете права ложным образом представлять свою личность или вашу связь с другим лицом или организацией. Это включает в себя любое из следующих действий, которое вводит в заблуждение или обманывает других:

* Копирование аватара другого пользователя или другой личной информации профиля
* Публикация контента под адресом электронной почты другого пользователя
* Использование обманчиво похожего имени пользователя, названия организации или другого пространства имен
* Доступ к учетной записи или организации с помощью маркера или учетных данных другого пользователя
* Иным образом выдавать себя за другое лицо или организацию

Имперсонация является формой преследования, и нарушение этой политики может привести к потере доступа к вашей учетной записи.

Обратите внимание, что наличие имени пользователя, похожего на другое, не обязательно означает имперсонацию. GitHub будет учитывать контекст. Например, как и в случаях, связанных с утверждениями о [неправильной информации или дезинформации](/ru/site-policy/acceptable-use-policies/github-misinformation-and-disinformation), мы обычно разрешаем пародию и сатиру, которая соответствует нашим [Политикам допустимого использования](/ru/site-policy/acceptable-use-policies/github-acceptable-use-policies).
