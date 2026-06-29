Политика имени пользователя GitHub - GitHub Docs(function(){
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

* [Политика сайта](/ru/site-policy)/
* [Другие правила сайта](/ru/site-policy/other-site-policies)/
* [Политика имени пользователя GitHub](/ru/site-policy/other-site-policies/github-username-policy)

Политика имени пользователя GitHub
==========

Копировать как Markdown

В этой статье
----------

* [Что делать, если нужное мне имя пользователя уже занято?](#what-if-the-username-i-want-is-already-taken)
* [Политика в отношении товарных знаков](#trademark-policy)
* [Политика сквоттинга имен](#name-squatting-policy)

Имена учетных записей GitHub доступны в порядке очереди и предназначены для немедленного и активного использования.

[Что делать, если нужное мне имя пользователя уже занято?](#what-if-the-username-i-want-is-already-taken)
----------

Имейте в виду, что не все действия на GitHub видны всем; учетные записи без видимой активности могут активно использоваться.

Мы не принимаем запросы на освобождение, передачу или возвращение имен пользователей на том основании, что они кажутся неактивными или неиспользуемыми. Если желаемое имя пользователя уже заявлено, вам нужно будет выбрать другое доступное имя, если только вы не подаете жалобу на товарный знак, как описано ниже.

Если нужное вам имя пользователя уже было заявлено, рассмотрите другие имена или уникальные варианты. Использование числа, дефиса или альтернативного написания может помочь вам определить желаемое имя пользователя, которое все еще доступно.

[Политика в отношении товарных знаков](#trademark-policy)
----------

Если вы считаете, что чья-то учетная запись нарушает ваши права на товарный знак, вы можете найти дополнительную информацию о подаче жалобы на товарный знак на странице [Политика GitHub в отношении товарных знаков](/ru/site-policy/content-removal-policies/github-trademark-policy). Действительные жалобы, связанные с товарными знаками, — это единственные запросы, которые мы рассматриваем c целью возможного освобождения уже заявленного имени пользователя.

[Политика сквоттинга имен](#name-squatting-policy)
----------

GitHub запрещает сквотирование имен учетных записей, и имена учетных записей не могут быть зарезервированы или неактивно сохранены для использования в будущем. Учетные записи, нарушающие эту политику сквоттинга имен, могут быть удалены или переименованы без предварительного уведомления. Попытки продать, купить или запросить другие формы оплаты в обмен на имена учетных записей запрещены и могут привести к бессрочной блокировке учетной записи.
