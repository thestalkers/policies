Acceptable Use Policies - GitHub Docs(function(){
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

Collapse sidebar

Expand sidebar

1. [Home](/en)
2. [Site policy](/en/site-policy)
3. Acceptable Use Policies

[Site policy](/en/site-policy)
----------

Acceptable Use Policies
==========

[GitHub Acceptable Use Policies](/en/site-policy/acceptable-use-policies/github-acceptable-use-policies)
----------

[GitHub Active Malware or Exploits](/en/site-policy/acceptable-use-policies/github-active-malware-or-exploits)
----------

[GitHub Bullying and Harassment](/en/site-policy/acceptable-use-policies/github-bullying-and-harassment)
----------

[GitHub Disrupting the Experience of Other Users](/en/site-policy/acceptable-use-policies/github-disrupting-the-experience-of-other-users)
----------

[GitHub Doxxing and Invasion of Privacy](/en/site-policy/acceptable-use-policies/github-doxxing-and-invasion-of-privacy)
----------

[GitHub Hate Speech and Discrimination](/en/site-policy/acceptable-use-policies/github-hate-speech-and-discrimination)
----------

[GitHub Impersonation](/en/site-policy/acceptable-use-policies/github-impersonation)
----------

[GitHub Misinformation and Disinformation](/en/site-policy/acceptable-use-policies/github-misinformation-and-disinformation)
----------

[GitHub Sexually Obscene Content](/en/site-policy/acceptable-use-policies/github-sexually-obscene-content)
----------

[GitHub Threats of Violence and Gratuitously Violent Content](/en/site-policy/acceptable-use-policies/github-threats-of-violence-and-gratuitously-violent-content)
----------

[GitHub Terrorism and Violent Extremism](/en/site-policy/acceptable-use-policies/github-terrorism-and-violent-extremism)
----------

[GitHub Child Sexual Exploitation or Abuse](/en/site-policy/acceptable-use-policies/github-child-sexual-exploitation-or-abuse)
----------

[GitHub Non-Consensual Intimate Imagery](/en/site-policy/acceptable-use-policies/github-non-consensual-intimate-imagery)
----------

[GitHub Synthetic Media and AI Tools](/en/site-policy/acceptable-use-policies/github-synthetic-media-and-ai-tools)
----------

[GitHub Appeal and Reinstatement](/en/site-policy/acceptable-use-policies/github-appeal-and-reinstatement)
----------
