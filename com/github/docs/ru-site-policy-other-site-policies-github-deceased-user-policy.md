Политика умерших пользователей GitHub - GitHub Docs(function(){
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
* [Политика умерших пользователей GitHub](/ru/site-policy/other-site-policies/github-deceased-user-policy)

Политика умерших пользователей GitHub
==========

Копировать как Markdown

В случае смерти пользователя GitHub мы можем работать с уполномоченным лицом, чтобы определить, что произойдет с содержимым учетной записи.

Если вы являетесь ближайшим родственником, [предварительно назначенным наследником](/ru/account-and-profile/setting-up-and-managing-your-personal-account-on-github/managing-access-to-your-personal-repositories/maintaining-ownership-continuity-of-your-personal-accounts-repositories) или другим уполномоченным лицом (например, коллегой или бизнес-партнером) умершего пользователя и хотите отправить запрос, связанный с учетной записью умершего пользователя, вы можете связаться с нами через [Портал поддержки GitHub](https://support.github.com/). Нажмите кнопку **Связаться с нами** на портале и укажите в сообщении следующие сведения:

* Наименование
* Контактные сведения
* Имя умершего владельца счета
* Имя пользователя GitHub умершего владельца аккаунта
* Ваши отношения с умершим владельцем учетной записи (пожалуйста, укажите, были ли вы назначены преемником учетной записи на GitHub.com)
* Если назначен преемником учетной записи, имя пользователя вашей учетной записи GitHub
* Какое действие вы ищете (например, перенос общедоступных репозиториев, отмена выставления счетов на счет)

После того, как мы получим ваш запрос, мы можем запросить дополнительную информацию, такую как копия вашего удостоверения личности с фотографией, копия свидетельства о смерти и документы, подтверждающие, что вы уполномочены действовать в отношении учетной записи умершего пользователя, чтобы убедитесь, что мы должным образом уполномочены обрабатывать ваш запрос.

Обратите внимание, что информация, предоставляемая вами в запросе, собирается в соответствии с нашим [Заявлением о конфиденциальности](/ru/site-policy/privacy-policies/github-privacy-statement), и мы будем хранить информацию только по мере необходимости в соответствии с нашими юридическими обязательствами и условиям разрешения споров.
