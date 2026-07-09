Издевательства и домогательства на GitHub - GitHub Docs(function(){
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
3. [Издевательства и домогательства](/ru/site-policy/acceptable-use-policies/github-bullying-and-harassment)

Издевательства и домогательства на GitHub
==========

Копировать как Markdown

Мы не приемлем домогательств, издевательств или оскорблений любого рода, будь то напрямую или путем поощрения других к участию в запрещенных действиях. Сюда входит следующее:

* Целенаправленные личные нападки
* Наращивание или организация [деструктивной](/ru/site-policy/acceptable-use-policies/github-disrupting-the-experience-of-other-users) деятельности, что равносильно злоупотреблению
* Следование за другим пользователем по платформе таким образом, что это приводит к запугиванию
* Делать сексуальные домогательства или комментарии, направленные на другого человека
* Неискреннее участие в разговоре таким образом, что провоцирует конфликт или подрывает искреннюю дискуссию.
* Создание альтернативных учетных записей специально для того, чтобы избежать модерации со стороны персонала или пользователей GitHub.

Обратите внимание, что не всякое нежелательное поведение обязательно считается домогательством. Например, несогласие с другим пользователем или голосование против его комментариев не может рассматриваться как оскорбление на нашей платформе. Кроме того, распространение критики общественных деятелей или проектов или тем, представляющих общественный интерес, не обязательно подпадает под действие этой политики. Тем не менее, мы рекомендуем вам внимательно относиться к тому, как вы взаимодействуете с другими пользователями и платформой, так как эта деятельность может по-прежнему нарушать наше ограничение на нарушение работы других пользователей.
