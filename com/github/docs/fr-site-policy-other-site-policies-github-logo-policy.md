Politique relative aux logos GitHub - Documentation GitHub(function(){
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
3. [Autres politiques du site](/fr/site-policy/other-site-policies)
4. Politique relative aux logos GitHub

Faire défiler les barres de navigation vers la droite

[Site policy](/fr/site-policy)
----------

Politique relative aux logos GitHub
==========

Copier Markdown

Vous pouvez, dans certains cas, ajouter des logos GitHub à votre site Web ou à une application tierce. Pour en savoir plus et recevoir des directives spécifiques sur l'utilisation des logos, consultez la [page Utilisation des logos de GitHub](https://github.com/logos).

Vous pouvez également utiliser un Octocat comme avatar personnel ou sur votre site Web pour établir un lien avec votre compte GitHub, mais pas pour votre société ou un produit que vous concevez. GitHub possède une vaste collection d'Octocats dans l'[Octodex](https://octodex.github.com/). Pour en savoir plus sur l'utilisation des Octocats de l'Octodex, consultez la [FAQ de l'Octodex](https://octodex.github.com/faq/).
