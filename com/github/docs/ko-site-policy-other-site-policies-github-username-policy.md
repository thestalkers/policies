GitHub 사용자 이름 정책 - GitHub 문서(function(){
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

사이드바 축소사이드바 확장

경로를 왼쪽으로 스크롤

1. [홈](/ko)
2. [사이트 정책](/ko/site-policy)
3. [다른 사이트 정책](/ko/site-policy/other-site-policies)
4. [GitHub 사용자 이름 정책](/ko/site-policy/other-site-policies/github-username-policy)

이동 경로를 오른쪽으로 스크롤

[Site policy](/ko/site-policy)
----------

GitHub 사용자 이름 정책
==========

Markdown으로 복사

이 기사에서
----------

* [원하는 사용자 이름이 이미 사용 중인 이름이라면 어떻게 해야 합니까?](#what-if-the-username-i-want-is-already-taken)
* [상표 정책](#trademark-policy)
* [이름 무단 점유 정책](#name-squatting-policy)

GitHub 계정 이름은 선착순으로 사용할 수 있으며, 즉각적인 활성 사용을 위한 것입니다.

[원하는 사용자 이름이 이미 사용 중인 이름이라면 어떻게 해야 합니까?](#what-if-the-username-i-want-is-already-taken)
----------

GitHub에서의 모든 활동이 공개적으로 표시되는 것은 아니라는 점을 명심하십시오. 가시적 활동이 없는 계정도 활성 사용 상태일 수 있습니다.

비활성 상태이거나 사용되지 않는 것으로 보인다는 이유로 사용자 이름을 해지, 이전 또는 회수해 달라는 요청은 허용되지 않습니다. 원하는 사용자 이름이 이미 사용 중인 경우, 아래 설명된 대로 상표 관련 불만 사항을 제출하지 않는 한 사용 가능한 다른 이름을 선택해야 합니다.

원하는 사용자 이름이 이미 사용 중인 이름이라면 다른 이름이나 독특한 변형을 고려해 보십시오. 숫자, 하이픈 또는 다른 철자를 사용하면 아직 사용 가능한 원하는 사용자 이름을 파악하는 데 도움이 될 수 있습니다.

[상표 정책](#trademark-policy)
----------

다른 사람의 계정이 귀하의 상표권을 침해한다고 생각되는 경우, [GitHub 상표 정책](/ko/site-policy/content-removal-policies/github-trademark-policy) 페이지에서 상표 관련 불만을 제기하는 방법에 대한 자세한 정보를 찾을 수 있습니다. 유효한 상표 관련 불만 사항에 대한 요청은 이미 사용 중인 사용자 이름의 해지 가능 여부를 검토하는 유일한 경우입니다.

[이름 무단 점유 정책](#name-squatting-policy)
----------

GitHub는 계정 이름 무단 점유를 금지하며, 장래 사용을 위해 계정 이름을 예약하거나 비활성 상태로 보유할 수 없습니다. 이 이름 무단 점유 정책을 위반하는 계정은 통지 없이 제거되거나 이름이 변경될 수 있습니다. 계정 이름 판매 또는 구입을 시도하거나 계정 이름의 대가로 그 밖의 지불 형식을 권유하는 행위는 금지되며, 계정이 영구 정지될 수 있습니다.
