Política del logotipo de GitHub - Documentación de GitHub(function(){
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

1. [Inicio](/es)
2. [Política del sitio](/es/site-policy)
3. [Otras políticas del sitio](/es/site-policy/other-site-policies)
4. [Política del logotipo de GitHub](/es/site-policy/other-site-policies/github-logo-policy)

Scroll breadcrumbs right

[Site policy](/es/site-policy)
----------

Política del logotipo de GitHub
==========

Copiar como Markdown

Puede añadir logotipos de GitHub a su sitio web o aplicación de terceros en algunas situaciones. Para obtener más información y directrices específicas sobre el uso de logotipos, consulte la [GitHub página de logotipos y uso](https://github.com/logos).

También puede usar un octocat como su avatar personal o en su sitio web para vincularlo a su cuenta de GitHub, pero no para su empresa o un producto que esté creando. GitHub tiene una extensa colección de octocats en [Octodex](https://octodex.github.com/). Para obtener más información sobre el uso de octocats de Octodex, consulte las [preguntas frecuentes sobre Octodex](https://octodex.github.com/faq/).
