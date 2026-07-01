GitHub ロゴのポリシー - GitHubドキュメント(function(){
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
* [その他のサイト ポリシー](/ja/site-policy/other-site-policies)/
* [GitHub ロゴのポリシー](/ja/site-policy/other-site-policies/github-logo-policy)

GitHub ロゴのポリシー
==========

Markdown としてコピー

場合によっては、GitHub ロゴをお客様の Web サイトまたは第三者のアプリケーションに追加できます。 ロゴの使用に関する詳細と具体的なガイドラインについては、[GitHub のロゴと使い方のページ](https://github.com/logos) をご覧ください。

また、Octocat をお客様の個人的なアバターとして、またはお客様の Web サイトで使用して、GitHub アカウントにリンクすることもできますが、お客様の会社またはお客様が構築している製品に対して使用することはできません。 GitHub は、[Octodex](https://octodex.github.com/) にさまざまな Octocat を所有しています。 Octodex の octocat の使用方法の詳細については、[Octodex の FAQ](https://octodex.github.com/faq/) のページを参照してください。
