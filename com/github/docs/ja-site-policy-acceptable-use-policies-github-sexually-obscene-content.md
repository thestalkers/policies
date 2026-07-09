GitHub のわいせつなコンテンツ - GitHubドキュメント(function(){
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

1. [サイト ポリシー](/ja/site-policy)
2. [利用規約](/ja/site-policy/acceptable-use-policies)
3. [わいせつなコンテンツ](/ja/site-policy/acceptable-use-policies/github-sexually-obscene-content)

GitHub のわいせつなコンテンツ
==========

Markdown としてコピー

当社は、[未成年者が関与する](/ja/site-policy/acceptable-use-policies/github-child-sexual-exploitation-or-abuse)場合を含め、他者の性的な搾取または虐待に関連するコンテンツを許容しません。 特に、当該コンテンツがプロファイルまたは他のソーシャル コンテンツに配置されたことにより増幅される場合、性的または衝撃的反応を誘う以外にほとんどまたは全く目的を持たない、性をテーマとしたり連想させたりするコンテンツを許容しません。 これには、次のものが含まれます。

* 性的コンテンツ
* 同意のない親密な写真
* 写真、動画、アニメーション、絵、コンピューター生成画像、またはテキストベースのコンテンツなど、性行為のあからさまな描写

当社は、裸体または性に関するコンテンツがすべてわいせつであると認識しているわけではありません。 芸術的、教育的、またはジャーナリスティックな意味合いにおける、または被害者擁護に関連する視覚的および/またはテキスト記述は許容されます。 免責事項によりプロジェクトの背景が伝えられる場合もあります。 ただし、当社では、表示する前にオプトインする選択肢をユーザーに提供して、コンテンツを制限できるようにしています。
