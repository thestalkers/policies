GitHub のいじめまたは嫌がらせ - GitHubドキュメント(function(){
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
3. [利用規約](/ja/site-policy/acceptable-use-policies)
4. [いじめまたは嫌がらせ](/ja/site-policy/acceptable-use-policies/github-bullying-and-harassment)

Scroll breadcrumbs right

[Site policy](/ja/site-policy)
----------

GitHub のいじめまたは嫌がらせ
==========

Markdown としてコピー

当社は、禁止されている行為を自ら行うか、または加担することを他者に促すかにかかわらず、いかなる嫌がらせ、いじめ、または虐待も容認しません。 これには、次のものが含まれます。

* 対象を絞った個人攻撃
* 虐待に相当する方法で[破壊的な](/ja/site-policy/acceptable-use-policies/github-disrupting-the-experience-of-other-users)行為を重ねたり、それを画策したりすること
* 脅迫行為の原因となる方法で、プラットフォームの周りの別のユーザーに従うこと
* 他人に向けて性的な誘いかけや発言を行うこと
* 衝突を引き起こしたり、誠実なやり取りを損なったりする方法で、不誠実な態度で会話に参加すること
* 特に GitHub のスタッフやユーザーが行う節度ある行為を避けるために、代替のアカウントを作成すること

好ましくない行為がすべて、必ずしも嫌がらせと見なされるわけではありません。 たとえば、別のユーザーに同意しないことや、彼らの発言に反対することは、当社のプラットフォームでは嫌がらせのレベルに達しない可能性があります。 さらに、著名な人物やプロジェクト、一般の人々が関心を持っているトピックを共有することは、必ずしもこの方針に該当するわけではありません。 ただし、その行為が他のユーザーのエクスペリエンスの妨害に関する当社の制限に違反している場合があるため、他のユーザーやプラットフォームへの関わり方に気を付けることをお勧めします。
