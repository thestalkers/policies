GitHub 条件 - GitHubドキュメント(function(){
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
var q=window.matchMedia?window.matchMedia('(prefers-color-scheme: dark)'):null;
var apply=function(){
var night=css.colorMode==='auto'?!!(q&&q.matches):css.colorMode==='dark';
var theme=night?css.darkTheme:css.lightTheme;
var mode=theme.indexOf('dark')===0?'dark':'light';
h.setAttribute('data-color-mode',mode);
h.setAttribute('data-'+mode+'-theme',theme);
};
h.setAttribute('data-color-mode-preference',css.colorMode);
h.setAttribute('data-light-theme',css.lightTheme);
h.setAttribute('data-dark-theme',css.darkTheme);
apply();
if(css.colorMode==='auto'&&q){
if(q.addEventListener)q.addEventListener('change',apply);
else if(q.addListener)q.addListener(apply);
}
}catch(e){}
})();

[Skip to main content](#main-content)

[Skip to content](#main-content)

サイドバーを折りたたむサイドバーを展開する

階層リンクを左にスクロールする

1. [ホーム](/ja)
2. [サイト ポリシー](/ja/site-policy)
3. GitHub 条件

階層リンクを右にスクロールする

[Site policy](/ja/site-policy)
----------

GitHub 条件
==========

[GitHub のサービス使用条件](/ja/site-policy/github-terms/github-terms-of-service)
----------

[GitHub の企業向けサービス使用条件](/ja/site-policy/github-terms/github-corporate-terms-of-service)
----------

[追加の製品および機能に適用される GitHub 条件](/ja/site-policy/github-terms/github-terms-for-additional-products-and-features)
----------

[GitHub コミュニティ ガイドライン](/ja/site-policy/github-terms/github-community-guidelines)
----------

[GitHub コミュニティの行動規範](/ja/site-policy/github-terms/github-community-code-of-conduct)
----------

[GitHub プレリリース ライセンス条項](/ja/site-policy/github-terms/github-pre-release-license-terms)
----------

[GitHub DPA の適用を受けるプレビュー](/ja/site-policy/github-terms/github-dpa-previews)
----------

[GitHub スポンサーの追加条件](/ja/site-policy/github-terms/github-sponsors-additional-terms)
----------

[GitHub の登録開発者契約](/ja/site-policy/github-terms/github-registered-developer-agreement)
----------

[GitHub Marketplace サービス使用条件](/ja/site-policy/github-terms/github-marketplace-terms-of-service)
----------

[GitHub Marketplace 開発者契約](/ja/site-policy/github-terms/github-marketplace-developer-agreement)
----------

[GitHub のリサーチ プログラム条項](/ja/site-policy/github-terms/github-research-program-terms)
----------

[GitHub オープン ソース アプリケーションの契約条件](/ja/site-policy/github-terms/github-open-source-applications-terms-and-conditions)
----------

[GitHub イベント条件](/ja/site-policy/github-terms/github-event-terms)
----------

[GitHub イベントの行動規範](/ja/site-policy/github-terms/github-event-code-of-conduct)
----------

[GitHub 教育目的利用契約](/ja/site-policy/github-terms/github-educational-use-agreement)
----------

[GitHub Copilot 拡張機能の開発者ポリシー](/ja/site-policy/github-terms/github-copilot-extension-developer-policy)
----------

[GitHub シークレット スキャン パートナー プログラム契約](/ja/site-policy/github-terms/github-secret-scanning-partner-program-agreement)
----------
