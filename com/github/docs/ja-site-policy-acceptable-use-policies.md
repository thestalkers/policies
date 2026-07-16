利用規約 - GitHubドキュメント(function(){
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

階層リンクを右にスクロールする

[Site policy](/ja/site-policy)
----------

利用規約
==========

[GitHub 利用規約](/ja/site-policy/acceptable-use-policies/github-acceptable-use-policies)
----------

[GitHub におけるアクティブなマルウェアまたはエクスプロイト](/ja/site-policy/acceptable-use-policies/github-active-malware-or-exploits)
----------

[GitHub のいじめまたは嫌がらせ](/ja/site-policy/acceptable-use-policies/github-bullying-and-harassment)
----------

[GitHub での他のユーザー エクスペリエンスの妨害](/ja/site-policy/acceptable-use-policies/github-disrupting-the-experience-of-other-users)
----------

[GitHub でのドキシングとプライバシーの侵害](/ja/site-policy/acceptable-use-policies/github-doxxing-and-invasion-of-privacy)
----------

[GitHub での憎悪の言葉と差別](/ja/site-policy/acceptable-use-policies/github-hate-speech-and-discrimination)
----------

[GitHub でのなりすまし](/ja/site-policy/acceptable-use-policies/github-impersonation)
----------

[GitHub の誤報と偽情報](/ja/site-policy/acceptable-use-policies/github-misinformation-and-disinformation)
----------

[GitHub のわいせつなコンテンツ](/ja/site-policy/acceptable-use-policies/github-sexually-obscene-content)
----------

[GitHub の暴力の脅威と根拠のない暴力的コンテンツ](/ja/site-policy/acceptable-use-policies/github-threats-of-violence-and-gratuitously-violent-content)
----------

[GitHub でのテロおよび暴力的な過激主義](/ja/site-policy/acceptable-use-policies/github-terrorism-and-violent-extremism)
----------

[GitHub での児童の性的搾取または虐待](/ja/site-policy/acceptable-use-policies/github-child-sexual-exploitation-or-abuse)
----------

[GitHub における同意のない親密な写真](/ja/site-policy/acceptable-use-policies/github-non-consensual-intimate-imagery)
----------

[GitHub の合成メディアと AI ツール](/ja/site-policy/acceptable-use-policies/github-synthetic-media-and-ai-tools)
----------

[GitHub の異議申し立ておよび復活](/ja/site-policy/acceptable-use-policies/github-appeal-and-reinstatement)
----------
