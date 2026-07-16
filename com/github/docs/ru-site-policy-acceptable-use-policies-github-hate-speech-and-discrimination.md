Разжигание ненависти и дискриминация на GitHub - Документация GitHub(function(){
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
4. [Разжигание ненависти и дискриминация](/ru/site-policy/acceptable-use-policies/github-hate-speech-and-discrimination)

Прокрутите страницы вправо

[Site policy](/ru/site-policy)
----------

Разжигание ненависти и дискриминация на GitHub
==========

Копировать как Markdown

GitHub не терпит высказываний, которые нападают или пропагандируют ненависть к отдельным людям или группам людей на основании того, кем они являются, включая возраст, размер тела, способности, этническую принадлежность, гендерную идентичность и самовыражение, уровень опыта, национальность, внешний вид, расу., религии, сексуальной идентичности или сексуальной ориентации. Сюда входит следующее:

* Высмеивание, нападение или исключение человека или группы на основе их убеждений или характеристик, перечисленных выше.
* Демонстрация явной принадлежности или идентификации с известными [террористическими или воинствующими экстремистскими организациями](/ru/site-policy/acceptable-use-policies/github-terrorism-and-violent-extremism)
* Поддержка или продвижение групп ненависти или теорий заговора, основанных на ненависти
* Обмен символами или изображениями, синонимами ненависти
* Использование вредных стереотипов, оскорблений или бесчеловечной речи
* Нападение на человека на основании его предполагаемого пола
* свист собаки; или использование закодированного или намекающего языка и / или символов для пропаганды оскорблений или ненависти

Хотя GitHub серьезно относится ко всем случаям злоупотреблений и притеснений на платформе, мы особенно привержены борьбе с оскорблениями на почве ненависти, когда они несоразмерно затрагивают сообщества, которые исторически подвергались таким оскорблениям. Мы стремимся сделать GitHub местом, где все люди чувствуют себя желанными и безопасными.
