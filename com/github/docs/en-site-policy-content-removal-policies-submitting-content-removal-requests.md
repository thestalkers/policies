Submitting content removal requests - GitHub Docs(function(){
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
* [Content Removal Policies](/en/site-policy/content-removal-policies)/
* [Submitting content removal requests](/en/site-policy/content-removal-policies/submitting-content-removal-requests)

Submitting content removal requests
==========

Copy as Markdown

In this article
----------

* [DMCA Takedown Policy](#dmca-takedown-policy)
* [GitHub Trademark Policy](#github-trademark-policy)
* [GitHub Private Information Removal Policy](#github-private-information-removal-policy)

We understand that copyrighted, trademarked, or private content may get published on GitHub – either accidentally or on purpose – sometimes in repositories that you do not own. Because the nature of this content varies, and because of different applicable laws, each category has its own, distinct reporting requirements outlined in our policies.

If you'd like to request that content be removed from GitHub, please take some time to acquaint yourself with each of these policies and their respective reporting requirements before submitting a report. If we receive an incomplete report, we'll need to ask for clarifications or revisions and you’ll need to re-submit a revised report.

Please note that we're not able to help you determine which policy is appropriate for your specific situation. If you’ve reviewed the policies below and still have questions about whether or not content should be reported as copyright, trademark, or private information, we recommend consulting with independent legal counsel.

[DMCA Takedown Policy](#dmca-takedown-policy)
----------

The [DMCA Takedown Policy](/en/site-policy/content-removal-policies/dmca-takedown-policy) can be used to report content that you believe infringes a copyright owned by you or your organization. Once you have reviewed the policy, you may also want to review our [Guide to Submitting a DMCA Takedown Notice](/en/site-policy/content-removal-policies/guide-to-submitting-a-dmca-takedown-notice) before submitting a report.

[GitHub Trademark Policy](#github-trademark-policy)
----------

The [GitHub Trademark Policy](/en/site-policy/content-removal-policies/github-trademark-policy) can be used to report content that appears to use your company or business name, logo, or other trademark-protected materials in a manner that may mislead or confuse others about brand or business affiliation.

[GitHub Private Information Removal Policy](#github-private-information-removal-policy)
----------

The [GitHub Private Information Removal Policy](/en/site-policy/content-removal-policies/github-private-information-removal-policy) can be used to report data that is private (confidential and poses a security risk), but that is not necessarily protected by copyright or trademark.

Users in India can [contact GitHub's Grievance Officer](https://support.github.com/contact/india-grievance-officer).
