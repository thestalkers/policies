GitHub Doxxing et invasion de la vie privée - Documentation GitHub(function(){
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
var q=window.matchMedia?window.matchMedia('(prefers-color-scheme: dark)'):null;
var apply=function(){
var night=css.colorMode==='auto'?!!(q&&q.matches):css.colorMode==='dark';
var theme=night?css.darkTheme:css.lightTheme;
var mode=theme.indexOf('dark')===0?'dark':'light';
h.setAttribute('data-color-mode',mode);
h.setAttribute('data-'+mode+'-theme',theme);
};
h.setAttribute('data-color-mode-preference',css.colorMode);
h.setAttribute('data-light-theme',css.lightTheme);
h.setAttribute('data-dark-theme',css.darkTheme);
apply();
if(css.colorMode==='auto'&&q){
if(q.addEventListener)q.addEventListener('change',apply);
else if(q.addListener)q.addListener(apply);
}
}catch(e){}
})();

[Skip to main content](#main-content)

[Skip to content](#main-content)

Réduire la barre latéraleDévelopper la barre latérale

Faire défiler les barres de navigation vers la gauche

1. [Accueil](/fr)
2. [Politique du site](/fr/site-policy)
3. [Règles de Bon Usage](/fr/site-policy/acceptable-use-policies)
4. Doxxing et atteinte à la vie privée

Faire défiler les barres de navigation vers la droite

[Site policy](/fr/site-policy)
----------

GitHub Doxxing et invasion de la vie privée
==========

Copier Markdown

Ne publiez pas les informations personnelles d'autres personnes. Cela inclut :

* Adresses e-mail personnelles et privées
* Numéros de téléphone
* Adresses physiques ou autres informations de localisation privées
* Informations bancaires ou numéros de carte de crédit
* Numéros de sécurité sociale/d'identité nationale
* Mots de passe
* Informations sur les électeurs
* Informations médicales et données biométriques personnelles
* Autres informations privées pouvant présenter un risque pour la sûreté ou la sécurité

Nous pouvons considérer d'autres informations, telles que des photos ou des vidéos qui ont été prises ou distribuées sans le consentement du sujet, comme une atteinte à la vie privée, en particulier lorsque ce matériel présente un risque pour la sécurité du sujet, comme en cas d'intimidation ou de harcèlement.

GitHub prendra en compte le contexte ainsi que si le contenu signalé est accessible au public ailleurs. Veuillez noter, cependant, que si le partage d'un contenu accessible au public ne constitue pas une violation de cette politique, si l'information est partagée dans l'intention de harceler ou d'inciter d'autres comportements abusifs, celui-ci peut violer notre interdiction [d'intimidation et de harcèlement](/fr/site-policy/acceptable-use-policies/github-bullying-and-harassment).

Pour en savoir plus ou pour savoir comment signaler une violation, consultez notre [Politique de retrait des informations privées](/fr/site-policy/content-removal-policies/github-private-information-removal-policy) et nos instructions pour [Signaler un abus](/fr/communities/maintaining-your-safety-on-github/reporting-abuse-or-spam).
