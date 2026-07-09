GitHub Deceased User Policy - GitHub Docs(function(){
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
2. [Other Site Policies](/en/site-policy/other-site-policies)
3. [GitHub Deceased User Policy](/en/site-policy/other-site-policies/github-deceased-user-policy)

GitHub Deceased User Policy
==========

Copy as Markdown

In the event that a GitHub user passes away, we can work with an authorized individual to determine what happens to the account's content.

If you are next of kin, a [pre-designated successor](/en/account-and-profile/setting-up-and-managing-your-personal-account-on-github/managing-access-to-your-personal-repositories/maintaining-ownership-continuity-of-your-personal-accounts-repositories), or other authorized individual (which could include a collaborator or business partner) of a deceased user and would like to make a request regarding their account, you can reach out to us through the [GitHub Support portal](https://support.github.com/). In the portal, click **Contact us**, and provide the following information in your message:

* Name
* Contact Information
* Name of the deceased account holder
* GitHub username of the deceased account holder
* Your relationship to the deceased account holder (please include whether you have been designated as the account successor on GitHub.com)
* If designated as account successor, the username of your GitHub account
* What action you are seeking (e.g. transfer public repositories, cancel billing on account)

Once we have received your request, we may follow up with a request for additional information, such as a copy of your photo identification, copy of the death certificate, and documentation confirming you are authorized to act in relation to the deceased user’s account, to verify that we are properly authorized to process your request.

Please note, the information you provide in your request is collected in accordance with our [Privacy Statement](/en/site-policy/privacy-policies/github-privacy-statement), and we will retain the information only as necessary to comply with our legal obligations and resolve disputes.
