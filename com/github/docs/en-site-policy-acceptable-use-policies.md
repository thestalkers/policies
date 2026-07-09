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
h.setAttribute('data-color-mode',css.colorMode);
h.setAttribute('data-light-theme',css.lightTheme);
h.setAttribute('data-dark-theme',css.darkTheme);
}catch(e){}
})();

[Skip to main content](#main-content)

[Home](/en)

[Site policy](/en/site-policy)
----------

1. [Site policy](/en/site-policy)
2. [Acceptable Use Policies](/en/site-policy/acceptable-use-policies)

Acceptable Use Policies
==========

* [GitHub Acceptable Use Policies, 1 of 15](/en/site-policy/acceptable-use-policies/github-acceptable-use-policies)
* [GitHub Active Malware or Exploits, 2 of 15](/en/site-policy/acceptable-use-policies/github-active-malware-or-exploits)
* [GitHub Bullying and Harassment, 3 of 15](/en/site-policy/acceptable-use-policies/github-bullying-and-harassment)
* [GitHub Disrupting the Experience of Other Users, 4 of 15](/en/site-policy/acceptable-use-policies/github-disrupting-the-experience-of-other-users)
* [GitHub Doxxing and Invasion of Privacy, 5 of 15](/en/site-policy/acceptable-use-policies/github-doxxing-and-invasion-of-privacy)
* [GitHub Hate Speech and Discrimination, 6 of 15](/en/site-policy/acceptable-use-policies/github-hate-speech-and-discrimination)
* [GitHub Impersonation, 7 of 15](/en/site-policy/acceptable-use-policies/github-impersonation)
* [GitHub Misinformation and Disinformation, 8 of 15](/en/site-policy/acceptable-use-policies/github-misinformation-and-disinformation)
* [GitHub Sexually Obscene Content, 9 of 15](/en/site-policy/acceptable-use-policies/github-sexually-obscene-content)
* [GitHub Threats of Violence and Gratuitously Violent Content, 10 of 15](/en/site-policy/acceptable-use-policies/github-threats-of-violence-and-gratuitously-violent-content)
* [GitHub Terrorism and Violent Extremism, 11 of 15](/en/site-policy/acceptable-use-policies/github-terrorism-and-violent-extremism)
* [GitHub Child Sexual Exploitation or Abuse, 12 of 15](/en/site-policy/acceptable-use-policies/github-child-sexual-exploitation-or-abuse)
* [GitHub Non-Consensual Intimate Imagery, 13 of 15](/en/site-policy/acceptable-use-policies/github-non-consensual-intimate-imagery)
* [GitHub Synthetic Media and AI Tools, 14 of 15](/en/site-policy/acceptable-use-policies/github-synthetic-media-and-ai-tools)
* [GitHub Appeal and Reinstatement, 15 of 15](/en/site-policy/acceptable-use-policies/github-appeal-and-reinstatement)
