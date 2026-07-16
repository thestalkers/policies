Politique des utilisateurs décédés de GitHub - Documentation GitHub(function(){
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

Réduire la barre latéraleDévelopper la barre latérale

Faire défiler les barres de navigation vers la gauche

1. [Accueil](/fr)
2. [Politique du site](/fr/site-policy)
3. [Autres politiques du site](/fr/site-policy/other-site-policies)
4. [Politique des utilisateurs décédés de GitHub](/fr/site-policy/other-site-policies/github-deceased-user-policy)

Faire défiler les barres de navigation vers la droite

[Site policy](/fr/site-policy)
----------

Politique des utilisateurs décédés de GitHub
==========

Copier en tant que Markdown

En cas de décès d'un utilisateur GitHub, nous pouvons travailler avec une personne autorisée pour déterminer ce qu'il advient du contenu du compte.

Si vous êtes un parent proche, un [successeur prédésigné](/fr/account-and-profile/setting-up-and-managing-your-personal-account-on-github/managing-access-to-your-personal-repositories/maintaining-ownership-continuity-of-your-personal-accounts-repositories) ou une toute autre personne autorisée (notamment un collaborateur ou un partenaire commercial) d'un utilisateur décédé et que vous souhaitez faire une demande concernant son compte, vous pouvez nous contacter via le [portail de support GitHub](https://support.github.com/). Dans le portail, cliquez sur **Nous contacter** et fournissez les informations suivantes dans votre message :

* Nom
* Coordonnées des interlocuteurs
* Nom du titulaire du compte décédé
* Nom d'utilisateur GitHub du titulaire du compte décédé
* Votre relation avec le titulaire du compte décédé (veuillez indiquer si vous avez été désigné comme successeur du compte sur GitHub.com)
* Si désigné comme successeur de compte, le nom d'utilisateur de votre compte GitHub
* Quelle action recherchez-vous (par exemple, transférer des référentiels publics, annuler la facturation sur compte) ?

Une fois que nous avons reçu votre demande, nous pouvons effectuer un suivi avec une demande d'informations supplémentaires, telles qu'une copie de votre pièce d'identité avec photo, une copie du certificat de décès et des documents confirmant que vous êtes autorisé à agir en relation avec le compte de l'utilisateur décédé, afin de vérifier que nous sommes dûment habilités à traiter votre demande.

Veuillez noter que les informations que vous fournissez dans votre demande sont collectées conformément à notre [Déclaration de Confidentialité](/fr/site-policy/privacy-policies/github-privacy-statement), et que nous ne conserverons ces informations que dans la mesure nécessaire pour nous conformer à nos obligations légales et résoudre les litiges.
