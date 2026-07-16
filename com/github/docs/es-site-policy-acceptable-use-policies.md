Directivas de Uso Aceptable - Documentación de GitHub(function(){
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

Contraer barra lateralExpandir barra lateral

Desplazar las migas de pan a la izquierda

1. [Inicio](/es)
2. [Política del sitio](/es/site-policy)
3. [Directivas de Uso Aceptable](/es/site-policy/acceptable-use-policies)

Desplazar las migas de pan hacia la derecha

[Site policy](/es/site-policy)
----------

Directivas de Uso Aceptable
==========

[Políticas de uso aceptable de GitHub](/es/site-policy/acceptable-use-policies/github-acceptable-use-policies)
----------

[Exploits o malware activo de GitHub](/es/site-policy/acceptable-use-policies/github-active-malware-or-exploits)
----------

[Intimidación y acoso de GitHub](/es/site-policy/acceptable-use-policies/github-bullying-and-harassment)
----------

[GitHub interrumpiendo la experiencia de otros usuarios](/es/site-policy/acceptable-use-policies/github-disrupting-the-experience-of-other-users)
----------

[GitHub Doxxing e invasión de la privacidad](/es/site-policy/acceptable-use-policies/github-doxxing-and-invasion-of-privacy)
----------

[GitHub Discurso de odio y discriminación](/es/site-policy/acceptable-use-policies/github-hate-speech-and-discrimination)
----------

[Suplantación de GitHub](/es/site-policy/acceptable-use-policies/github-impersonation)
----------

[Información errónea y desinformación de GitHub](/es/site-policy/acceptable-use-policies/github-misinformation-and-disinformation)
----------

[Contenido sexualmente obsceno de GitHub](/es/site-policy/acceptable-use-policies/github-sexually-obscene-content)
----------

[GitHub Amenazas de violencia y contenido violento gratuito](/es/site-policy/acceptable-use-policies/github-threats-of-violence-and-gratuitously-violent-content)
----------

[Terrorismo y extremismo violento en GitHub](/es/site-policy/acceptable-use-policies/github-terrorism-and-violent-extremism)
----------

[Explotación o abuso sexual infantil en GitHub](/es/site-policy/acceptable-use-policies/github-child-sexual-exploitation-or-abuse)
----------

[Imágenes íntimas no consentidas en GitHub](/es/site-policy/acceptable-use-policies/github-non-consensual-intimate-imagery)
----------

[Herramientas de inteligencia artificial y material sintético de GitHub](/es/site-policy/acceptable-use-policies/github-synthetic-media-and-ai-tools)
----------

[Apelación y restablecimiento de GitHub](/es/site-policy/acceptable-use-policies/github-appeal-and-reinstatement)
----------
