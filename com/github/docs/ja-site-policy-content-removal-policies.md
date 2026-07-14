コンテンツ削除ポリシー - GitHubドキュメント(function(){
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

1. [ホーム](/ja)
2. [サイト ポリシー](/ja/site-policy)
3. [コンテンツ削除ポリシー](/ja/site-policy/content-removal-policies)

Scroll breadcrumbs right

[Site policy](/ja/site-policy)
----------

コンテンツ削除ポリシー
==========

[コンテンツ削除要求の提出](/ja/site-policy/content-removal-policies/submitting-content-removal-requests)
----------

[DMCA 削除ポリシー](/ja/site-policy/content-removal-policies/dmca-takedown-policy)
----------

[GitHub の個人情報削除ポリシー](/ja/site-policy/content-removal-policies/github-private-information-removal-policy)
----------

[GitHub の商標ポリシー](/ja/site-policy/content-removal-policies/github-trademark-policy)
----------

[DMCA 反論通知提出ガイド](/ja/site-policy/content-removal-policies/guide-to-submitting-a-dmca-counter-notice)
----------

[DMCA 削除通知提出ガイド](/ja/site-policy/content-removal-policies/guide-to-submitting-a-dmca-takedown-notice)
----------
