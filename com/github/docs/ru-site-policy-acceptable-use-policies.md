Политика допустимого использования - Документация GitHub(function(){
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

Прокрутите страницы вправо

[Site policy](/ru/site-policy)
----------

Политика допустимого использования
==========

[Политики допустимого использования GitHub](/ru/site-policy/acceptable-use-policies/github-acceptable-use-policies)
----------

[Активное вредоносное ПО или эксплойты GitHub](/ru/site-policy/acceptable-use-policies/github-active-malware-or-exploits)
----------

[Издевательства и домогательства на GitHub](/ru/site-policy/acceptable-use-policies/github-bullying-and-harassment)
----------

[GitHub мешает работе других пользователей](/ru/site-policy/acceptable-use-policies/github-disrupting-the-experience-of-other-users)
----------

[GitHub Doxxing и вторжение в частную жизнь](/ru/site-policy/acceptable-use-policies/github-doxxing-and-invasion-of-privacy)
----------

[Разжигание ненависти и дискриминация на GitHub](/ru/site-policy/acceptable-use-policies/github-hate-speech-and-discrimination)
----------

[Имперсонация GitHub](/ru/site-policy/acceptable-use-policies/github-impersonation)
----------

[Неправильная информация и дезинформация на GitHub](/ru/site-policy/acceptable-use-policies/github-misinformation-and-disinformation)
----------

[Содержимое сексуального непристойного содержания на GitHub](/ru/site-policy/acceptable-use-policies/github-sexually-obscene-content)
----------

[Угрозы насилия и неоправданно жестокое содержимое на GitHub](/ru/site-policy/acceptable-use-policies/github-threats-of-violence-and-gratuitously-violent-content)
----------

[Терроризм и воинствующий экстремизм на GitHub](/ru/site-policy/acceptable-use-policies/github-terrorism-and-violent-extremism)
----------

[Сексуальная эксплуатация детей или насилие над детьми на GitHub](/ru/site-policy/acceptable-use-policies/github-child-sexual-exploitation-or-abuse)
----------

[Создание и распространение на GitHub интимных изображений без согласия](/ru/site-policy/acceptable-use-policies/github-non-consensual-intimate-imagery)
----------

[Синтетические мультимедиа и средства ИИ на GitHub](/ru/site-policy/acceptable-use-policies/github-synthetic-media-and-ai-tools)
----------

[Апелляция GitHub и восстановление](/ru/site-policy/acceptable-use-policies/github-appeal-and-reinstatement)
----------
