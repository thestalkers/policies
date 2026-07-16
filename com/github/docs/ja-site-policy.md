サイト ポリシーのドキュメント - GitHubドキュメント(function(){
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

階層リンクを右にスクロールする

[Site policy](/ja/site-policy)
----------

サイト ポリシーのドキュメント
==========

GitHub のサービス使用条件、許容できる使用ポリシー、プライバシー プラクティス、コンテンツの削除手順、およびその他のサイト ポリシーを確認します。

[概要](/site-policy/github-terms/github-terms-of-service)

推奨
----------

[### GitHub のサービス使用条件 ###](/ja/free-pro-team@latest/site-policy/github-terms/github-terms-of-service)[### GitHub の一般プライバシー ステートメント ###](/ja/free-pro-team@latest/site-policy/privacy-policies/github-general-privacy-statement)[### GitHub 利用規約 ###](/ja/free-pro-team@latest/site-policy/acceptable-use-policies/github-acceptable-use-policies)

記事
----------

カテゴリ: すべてのカテゴリ

[Request content removal ### DMCA 削除ポリシー ###](/ja/site-policy/content-removal-policies/dmca-takedown-policy)[Request content removal ### DMCA 削除通知提出ガイド ###](/ja/site-policy/content-removal-policies/guide-to-submitting-a-dmca-takedown-notice)[Request content removal ### DMCA 反論通知提出ガイド ###](/ja/site-policy/content-removal-policies/guide-to-submitting-a-dmca-counter-notice)[Review product and program terms ### GitHub Copilot 拡張機能の開発者ポリシー ###](/ja/site-policy/github-terms/github-copilot-extension-developer-policy)[Review product and program terms ### GitHub DPA の適用を受けるプレビュー ###](/ja/site-policy/github-terms/github-dpa-previews)[Review product and program terms ### GitHub Marketplace サービス使用条件 ###](/ja/site-policy/github-terms/github-marketplace-terms-of-service)[Review product and program terms ### GitHub Marketplace 開発者契約 ###](/ja/site-policy/github-terms/github-marketplace-developer-agreement)[Review privacy and security policies ### GitHub SIRT の説明 RFC 2350 ###](/ja/site-policy/security-policies/github-sirt-description-rfc-2350)[Review company and general policies ### GitHub アカウント回復ポリシー ###](/ja/site-policy/other-site-policies/github-account-recovery-policy)

57 の 1-9 の表示

[Previous]()[1](#1)[2](#2)[3](#3)[4](#4)[5](#5)[6](#6)[7](#7)[Next](#2)
