GitHub Doxxing and Invasion of Privacy - GitHub Docs(function(){
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
* [Doxxing and Invasion of Privacy](/en/site-policy/acceptable-use-policies/github-doxxing-and-invasion-of-privacy)

GitHub Doxxing and Invasion of Privacy
==========

Copy as Markdown

Don't post other people's personal information. This includes:

* Personal, private email addresses
* Phone numbers
* Physical addresses or other private location information
* Bank account information or credit card numbers
* Social Security/National Identity numbers
* Passwords
* Voter information
* Medical information and personal biometric data
* Other private information that may pose a safety or security risk

We may consider other information, such as photos or videos that were taken or distributed without the subject's consent, to be an invasion of privacy, especially when such material presents a safety risk to the subject, such as in the case of intimidation or harassment.

GitHub will take context into account as well as whether the reported content is publicly available elsewhere. Please note, however, that while sharing publicly available content may not be a violation of this policy, if the information is shared with the intent to harass or incite other abusive behavior, it may violate our prohibition against [bullying and harassment](/en/site-policy/acceptable-use-policies/github-bullying-and-harassment).

For more information, or to learn how to report a violation, see our [Private Information Removal Policy](/en/site-policy/content-removal-policies/github-private-information-removal-policy) and our instructions for [Reporting Abuse](/en/communities/maintaining-your-safety-on-github/reporting-abuse-or-spam).
