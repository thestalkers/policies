GitHub での他のユーザー エクスペリエンスの妨害 - GitHubドキュメント(function(){
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
3. [他のユーザー エクスペリエンスの妨害](/ja/site-policy/acceptable-use-policies/github-disrupting-the-experience-of-other-users)

GitHub での他のユーザー エクスペリエンスの妨害
==========

Markdown としてコピー

コミュニティの一員であることには、お客様の行為が他者に与える影響を認識し、他者やその依存するプラットフォームで有意義で生産的なやり取りを行うことが含まれます。

当社は、他のユーザーのエクスペリエンスを大幅にまたは継続的に妨害する行動を許容しません。 これには、次のものが含まれます。

* 本題からそれたコメントを投稿すること
* 中身または意味のないイシューやプル リクエストを開くこと
* アカウントまたはリポジトリを大量に短時間で星印を付けたりフォローしたりすること
* 無意味または無関係なコード レビューを作成すること
* プラットフォーム機能を操作して他のユーザーに必要以上の通知を送信すること
* 他のプラットフォーム機能を使用して混乱をもたらすこと

管理者には自らのプロジェクトを個別に調整することを推奨しますが、GitHub スタッフは、このような行為を行うアカウントに対してさらに制限を加える場合があります。

上記の行為は、当社の[利用規約](/ja/site-policy/acceptable-use-policies/github-acceptable-use-policies)のその他の制限事項に違反する場合もあります。 たとえば、行動の性質と重大度に応じて、[いじめまたは嫌がらせ](/ja/site-policy/acceptable-use-policies/github-bullying-and-harassment)のレベルに達することがあります。
