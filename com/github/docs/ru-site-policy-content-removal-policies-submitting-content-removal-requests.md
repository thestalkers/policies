Отправка запросов на удаление содержимого - GitHub Docs(function(){
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
2. [Политики удаления контента](/ru/site-policy/content-removal-policies)
3. [Отправка запросов на удаление содержимого](/ru/site-policy/content-removal-policies/submitting-content-removal-requests)

Отправка запросов на удаление содержимого
==========

Копировать как Markdown

В этой статье
----------

* [Политика удаления DMCA](#dmca-takedown-policy)
* [Политика GitHub в отношении товарных знаков](#github-trademark-policy)
* [Политика удаления личной информации GitHub](#github-private-information-removal-policy)

Мы понимаем, что защищенное авторским правом, товарным знаком или частное содержимое может быть опубликовано на GitHub — случайно или намеренно — иногда в репозиториях, которыми вы не владеете. Поскольку характер этого содержимого различается, а применимые законы различаются, для каждой категории действуют свои собственные требования к отчетности, изложенные в наших правилах.

Если вы хотите запросить удаление содержимого с GitHub, найдите время, чтобы ознакомиться с каждой из этих политик и их соответствующими требованиями к отчетности, прежде чем отправлять отчет. Если мы получим неполный отчет, нам потребуется запросить разъяснения или исправления, а вам потребуется повторно отправить исправленный отчет.

Обратите внимание, что мы не можем помочь вам определить, какая политика подходит для вашей конкретной ситуации. Если вы ознакомились с приведенными ниже политиками и у вас все еще есть вопросы о том, следует ли сообщать о содержимом как об авторских правах, товарных знаках или частной информации, мы рекомендуем проконсультироваться с независимым юрисконсультом.

[Политика удаления DMCA](#dmca-takedown-policy)
----------

[Политика удаления содержимого DMCA](/ru/site-policy/content-removal-policies/dmca-takedown-policy) может использоваться для сообщения о содержимом, который, по вашему мнению, нарушает авторские права, принадлежащие вам или вашей организации. После того, как вы ознакомились с политикой, перед отправкой отчета вы также можете ознакомиться с [Руководством по подаче уведомления об удалении DMCA](/ru/site-policy/content-removal-policies/guide-to-submitting-a-dmca-takedown-notice).

[Политика GitHub в отношении товарных знаков](#github-trademark-policy)
----------

[Политика GitHub](/ru/site-policy/content-removal-policies/github-trademark-policy) в отношении товарных знаков может использоваться для сообщения о содержании, которое, как представляется, использует название вашей компании или компании, логотип или другие материалы, защищенные товарным знаком, таким образом, что это может ввести в заблуждение или сбить с толку других в отношении бренда или принадлежности к бизнесу.

[Политика удаления личной информации GitHub](#github-private-information-removal-policy)
----------

[Политика удаления частной информации GitHub](/ru/site-policy/content-removal-policies/github-private-information-removal-policy) может использоваться для сообщения о данных, которые являются частными (конфиденциальными и представляют угрозу безопасности), но которые не обязательно защищены авторским правом или торговой маркой.

Пользователи в Индии могут [связаться со специалистом GitHub по принятию жалоб](https://support.github.com/contact/india-grievance-officer).
