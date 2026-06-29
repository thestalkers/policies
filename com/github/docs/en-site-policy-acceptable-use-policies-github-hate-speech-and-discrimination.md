GitHub Hate Speech and Discrimination - GitHub Docs(function(){
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

[Home](/en)

[Site policy](/en/site-policy)
----------

* [Site policy](/en/site-policy)/
* [Acceptable Use Policies](/en/site-policy/acceptable-use-policies)/
* [Hate Speech and Discrimination](/en/site-policy/acceptable-use-policies/github-hate-speech-and-discrimination)

GitHub Hate Speech and Discrimination
==========

Copy as Markdown

GitHub does not tolerate speech that attacks or promotes hate toward an individual or group of people on the basis of who they are, including age, body size, ability, ethnicity, gender identity and expression, level of experience, nationality, personal appearance, race, religion, sexual identity, or sexual orientation. This includes:

* Mocking, attacking, or excluding a person or group based on their beliefs or the characteristics listed above
* Displaying clear affiliation or identification with known [terrorist or violent extremist organizations](/en/site-policy/acceptable-use-policies/github-terrorism-and-violent-extremism)
* Supporting or promoting hate groups or hate-based conspiracy theories
* Sharing symbols or images synonymous with hate
* Using harmful stereotypes, slurs, or dehumanizing speech
* Attacking an individual based on their perceived gender
* Dog whistling; or using coded or suggestive language and/or symbols to promote abuse or hate

While GitHub takes all instances of abuse and harassment on the platform seriously, we are especially committed to fighting hate-based abuse where it disproportionately affects communities that have historically been targeted by such abuse. We aim to make GitHub a place where all individuals feel welcome and safe.
