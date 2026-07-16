GitHub での憎悪の言葉と差別 - GitHubドキュメント(function(){
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
3. [利用規約](/ja/site-policy/acceptable-use-policies)
4. [憎悪の言葉と差別](/ja/site-policy/acceptable-use-policies/github-hate-speech-and-discrimination)

階層リンクを右にスクロールする

[Site policy](/ja/site-policy)
----------

GitHub での憎悪の言葉と差別
==========

Markdown としてコピー

GitHub は、年齢、体格、能力、民族、性同一性、性表現、経験の程度、国籍、容姿、人種、宗教、性アイデンティティ、性的指向などに基づいて、個人またはグループに対して攻撃したり憎悪を助長したりする言葉を容認しません。 これには、次のものが含まれます。

* 上記の信念や特性に基づいて個人やグループを嘲笑、攻撃、または排除すること
* 既知の[テロリストまたは暴力的な過激派組織](/ja/site-policy/acceptable-use-policies/github-terrorism-and-violent-extremism)との明白な関係やそれらへの帰属意識を誇示すること
* 憎悪グループまたは憎悪に基づく陰謀論を支持または助長すること
* 憎悪と同じ意味を持つ記号や画像を共有すること
* 有害な固定観念、中傷、または非人間的な言葉を使用すること
* 認識されている性に基づいて個人を攻撃すること
* 隠語を使うこと、あるいは暴言や憎悪を助長する暗示的または暗号化された言葉や記号を使用すること

GitHub は、プラットフォーム上の暴言や嫌がらせのすべての事例に真剣に取り組んでおり、特に歴史的にそのような暴言の標的となってきたコミュニティに過大な影響を及ぼす場合に、憎悪に基づく暴言と戦うことに努めています。 GitHub をすべての人が安全で歓迎されていると感じる場所にすることを目指しています。
