セキュリティ脆弱性の協調的開示 - GitHubドキュメント(function(){
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
2. [セキュリティ ポリシー](/ja/site-policy/security-policies)
3. [セキュリティ脆弱性の協調的開示](/ja/site-policy/security-policies/coordinated-disclosure-of-security-vulnerabilities)

セキュリティ脆弱性の協調的開示
==========

Markdown としてコピー

私たちは、GitHub をすべての人にとって安全であるよう保ちたいと願っています。 GitHub でセキュリティ上の脆弱性を発見した場合は、協調的な方法で当社に開示するためのご協力をいただければ幸いです。

[報奨金プログラム](#bounty-program)
----------

セキュリティ リサーチャーと良好な関係を築くため、何社かのソフトウェア大企業と同様に、GitHub でもバグ報奨金を提供しています。 その考え方は単純であり、ハッカーや (あなたのような) セキュリティ リサーチャーが、協調的開示プロセスを通じて脆弱性を見つけて報告するというものです。 リサーチャーによるバグ ハンティングの取り組みを称えて、現金をお支払いします。

報奨金の詳細については、[GitHub のバグ報奨金](https://bounty.github.com)のサイトをご覧ください。また、包括的な[法的免責事項ポリシー](/ja/site-policy/security-policies/github-bug-bounty-program-legal-safe-harbor)の条項もご確認ください。それでは、バグ ハンティングをお楽しみください!
