GitHub でのドキシングとプライバシーの侵害 - GitHubドキュメント(function(){
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
4. [ドキシングとプライバシーの侵害](/ja/site-policy/acceptable-use-policies/github-doxxing-and-invasion-of-privacy)

階層リンクを右にスクロールする

[Site policy](/ja/site-policy)
----------

GitHub でのドキシングとプライバシーの侵害
==========

Markdown としてコピー

他者の個人情報を投稿しないでください。 これには、次のものが含まれます。

* 個人のプライベートな電子メール アドレス
* 各電話番号
* 実際の住所やその他のプライベートな位置情報
* 銀行口座情報やクレジット カード番号
* 社会保障/国民識別番号
* パスワード
* 投票者情報
* 医療情報や個人の生体認証データ
* 安全またはセキュリティ リスクをもたらす可能性があるその他のプライベートな情報

当社では、被写体の同意なく撮影または配布された写真や動画などの情報を、特にかかる題材が脅迫や嫌がらせなどのように、被写体に安全上の危険を引き起こす場合は、プライバシーの侵害と見なします。

GitHub は、前後の状況だけでなく報告されたコンテンツが他の場所で公開されているかどうかも考慮します。 ただし、公表されたコンテンツの共有がこのポリシーの違反には当たらないものの、情報が他の虐待的行為を助長または扇動する意図で共有されている場合は、[いじめまたは嫌がらせ](/ja/site-policy/acceptable-use-policies/github-bullying-and-harassment)に対する当社の禁止事項に違反します。

詳細、または違反の報告方法については、当社の [プライバシー情報の削除に関するポリシー](/ja/site-policy/content-removal-policies/github-private-information-removal-policy)および[不正使用の報告](/ja/communities/maintaining-your-safety-on-github/reporting-abuse-or-spam)の手順を参照してください。
