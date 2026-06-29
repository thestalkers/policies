GitHub でのなりすまし - GitHubドキュメント(function(){
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
* [利用規約](/ja/site-policy/acceptable-use-policies)/
* [偽装](/ja/site-policy/acceptable-use-policies/github-impersonation)

GitHub でのなりすまし
==========

Markdown としてコピー

お客様は、自身の身元、または他の人や組織と自身の関係について虚偽の表示をすることはできません。 これには、他の人を誤解させたりだましたりするような以下の行為が含まれます。

* 他のユーザーのアバターまたは他人のプロファイル情報をコピーすること
* 他のユーザーの電子メール アドレスを使用してコンテンツを投稿すること
* 似たような紛らわしいユーザー名、組織名、またはその他の名前空間を使用すること
* 別のユーザーのトークンまたは資格情報を使用してアカウントまたは組織にアクセスする
* その他の方法で他人または他の組織の振りをすること

なりすましは一種の嫌がらせであり、本ポリシーの違反となるため、アカウントにアクセスできなくなる場合があります。

他のユーザー名に似たユーザー名が、必ずしもなりすましとは限りません。 GitHub は状況を考慮します。 たとえば、[誤報または偽情報](/ja/site-policy/acceptable-use-policies/github-misinformation-and-disinformation)の申し立てに関する場合と同様に、一般に[利用規約](/ja/site-policy/acceptable-use-policies/github-acceptable-use-policies)に従うパロディおよび風刺は容認されます。
