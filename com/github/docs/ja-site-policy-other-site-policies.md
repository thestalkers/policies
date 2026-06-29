その他のサイト ポリシー - GitHubドキュメント(function(){
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

[ホーム](/ja)

[Site policy](/ja/site-policy)
----------

* [サイト ポリシー](/ja/site-policy)/
* [その他のサイト ポリシー](/ja/site-policy/other-site-policies)

その他のサイト ポリシー
==========

[GitHub と貿易管理](/ja/site-policy/other-site-policies/github-and-trade-controls)
----------

[GitHub の死亡ユーザー ポリシー](/ja/site-policy/other-site-policies/github-deceased-user-policy)
----------

[GitHub ロゴのポリシー](/ja/site-policy/other-site-policies/github-logo-policy)
----------

[GitHub の行政機関による削除のポリシー](/ja/site-policy/other-site-policies/github-government-takedown-policy)
----------

[GitHub のユーザー名ポリシー](/ja/site-policy/other-site-policies/github-username-policy)
----------

[ユーザー データの司法手続き上の要求に関するガイドライン](/ja/site-policy/other-site-policies/guidelines-for-legal-requests-of-user-data)
----------

[GitHub アカウント回復ポリシー](/ja/site-policy/other-site-policies/github-account-recovery-policy)
----------
