Содержимое сексуального непристойного содержания на GitHub - Документация GitHub(function(){
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
4. [Содержимое сексуального непристойного содержания](/ru/site-policy/acceptable-use-policies/github-sexually-obscene-content)

Прокрутите страницы вправо

[Site policy](/ru/site-policy)
----------

Содержимое сексуального непристойного содержания на GitHub
==========

Копировать как Markdown

Мы не допускаем демонстрации контента, связанного с сексуальной эксплуатацией и насилием над другими людьми, в том числе [несовершеннолетними](/ru/site-policy/acceptable-use-policies/github-child-sexual-exploitation-or-abuse). Мы не разрешаем содержимое сексуальной тематики или непристойное содержимое, которое практически не служит никакой цели, кроме как вызвать эротическую или шокирующую реакцию, особенно если этот контент усиливается за счет его размещения в профилях или других социальных контекстах. Сюда входит следующее:

* Порнографическое содержимое
* Интимные образы без согласия
* Графические изображения половых актов, включая фотографии, видео, анимацию, рисунки, компьютерные изображения или текстовое содержимое.

Мы понимаем, что не всякая нагота или материалы, связанные с сексуальностью, являются непристойными. Мы можем разрешить визуальные и/или текстовые изображения в художественном, образовательном, историческом или журналистском контексте или в связи с защитой интересов жертв. В некоторых случаях отказ от ответственности может помочь сообщить контекст проекта. Тем не менее, пожалуйста, поймите, что мы можем ограничить содержимое, предоставив пользователям возможность подписаться перед просмотром.
