GitHub の会社ポリシー - GitHubドキュメント(function(){
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

サイドバーを折りたたむサイドバーを展開する

階層リンクを左にスクロールする

1. [ホーム](/ja)
2. [サイト ポリシー](/ja/site-policy)
3. [GitHub の会社ポリシー](/ja/site-policy/github-company-policies)

階層リンクを右にスクロールする

[Site policy](/ja/site-policy)
----------

GitHub の会社ポリシー
==========

[GitHub の現代奴隷制と児童労働に反対する声明](/ja/site-policy/github-company-policies/github-statement-against-modern-slavery-and-child-labor)
----------

[GitHub の腐敗防止に関する声明](/ja/site-policy/github-company-policies/github-anti-bribery-statement)
----------

[GitHub の GPL Cooperation Commitment](/ja/site-policy/github-company-policies/github-gpl-cooperation-commitment)
----------

[GitHub の贈答品および接待に関するポリシー](/ja/site-policy/github-company-policies/github-gifts-and-entertainment-policy)
----------
