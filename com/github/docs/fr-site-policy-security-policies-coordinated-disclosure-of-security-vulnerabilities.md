Divulgation coordonnée des vulnérabilités de sécurité - Documentation GitHub(function(){
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

[Accueil](/fr)

[Site policy](/fr/site-policy)
----------

* [Politique du site](/fr/site-policy)/
* [Politiques de Sécurité](/fr/site-policy/security-policies)/
* [Divulgation coordonnée des vulnérabilités de sécurité](/fr/site-policy/security-policies/coordinated-disclosure-of-security-vulnerabilities)

Divulgation coordonnée des vulnérabilités de sécurité
==========

Copier en tant que Markdown

Nous voulons garder GitHub sûr pour tout le monde. Si vous avez découvert une faille de sécurité dans GitHub, nous apprécions votre aide pour nous la divulguer de manière coordonnée.

[Programme de primes](#bounty-program)
----------

Comme plusieurs autres grandes sociétés de logiciels, GitHub offre une prime de bogue pour mieux interagir avec les chercheurs en sécurité. L'idée est simple : les hackers et les chercheurs en sécurité (comme vous) trouvent et signalent les vulnérabilités grâce à notre processus de divulgation coordonné. Ensuite, pour reconnaître l'effort important que ces chercheurs déploient souvent lors de la chasse aux bogues, nous les récompensons avec de l'argent sonnant et trébuchant.

Référez-vous au site [GitHub Bug Bounty](https://bounty.github.com) pour en savoir plus sur les primes et passez en revue les conditions complètes de notre [Politique de sécurité du programme Safe Harbor](/fr/site-policy/security-policies/github-bug-bounty-program-legal-safe-harbor) et bonne chasse !
