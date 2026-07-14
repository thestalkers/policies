Politique de nom d'utilisateur GitHub - Documentation GitHub(function(){
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

Collapse sidebarExpand sidebar

Scroll breadcrumbs left

1. [Accueil](/fr)
2. [Politique du site](/fr/site-policy)
3. [Autres politiques du site](/fr/site-policy/other-site-policies)
4. [Politique de nom d'utilisateur GitHub](/fr/site-policy/other-site-policies/github-username-policy)

Scroll breadcrumbs right

[Site policy](/fr/site-policy)
----------

Politique de nom d'utilisateur GitHub
==========

Copier en tant que Markdown

Dans cet article
----------

* [Que faire si le nom d'utilisateur que je veux est déjà pris ?](#que-faire-si-le-nom-dutilisateur-que-je-veux-est-déjà-pris)
* [Politique relative aux marques](#trademark-policy)
* [Politique de squattage de nom](#name-squatting-policy)

Les noms de compte GitHub sont disponibles selon le principe du premier arrivé, premier servi, et sont destinés à une utilisation immédiate et active.

[Que faire si le nom d'utilisateur que je veux est déjà pris ?](#que-faire-si-le-nom-dutilisateur-que-je-veux-est-déjà-pris)
----------

Gardez à l'esprit que toutes les activités sur GitHub ne sont pas visibles publiquement ; les comptes sans activité visible peuvent être en cours d'utilisation active.

Nous n’acceptons pas les demandes de publication, de transfert ou de récupération des noms d’utilisateur sur le simple constat qu’ils semblent inactifs ou non utilisés. Si le nom d’utilisateur souhaité a déjà été revendiqué, vous devez sélectionner un autre nom disponible, sauf si vous soumettez une plainte concernant une marque commerciale comme décrit ci-dessous.

Si le nom d'utilisateur que vous souhaitez a déjà été revendiqué, envisagez d'autres noms ou des variantes uniques. L'utilisation d'un numéro, d'un trait d'union ou d'une orthographe alternative peut vous aider à identifier un nom d'utilisateur souhaitable encore disponible.

[Politique relative aux marques](#trademark-policy)
----------

Si vous pensez que le compte d’une personne enfreint vos droits en matière de marques commerciales, vous trouverez plus d’informations sur la manière de déposer une plainte pour ce problème sur notre page [Politique de marque GitHub](/fr/site-policy/content-removal-policies/github-trademark-policy). Les plaintes relatives aux marques commerciales valides sont les seules demandes que nous examinerons dans le cadre dְ’une éventuelle publication d’un nom d’utilisateur déjà revendiqué.

[Politique de squattage de nom](#name-squatting-policy)
----------

GitHub interdit le squattage de noms de compte, et les noms de compte ne peuvent pas être réservés ou détenus de manière inactive pour une utilisation future. Les comptes qui enfreignent cette politique de squattage de nom peuvent être supprimés ou renommés sans préavis. Les tentatives de vente, d'achat ou de sollicitation d'autres formes de paiement en échange de noms de compte sont interdites et peuvent entraîner la suspension permanente du compte.
