# OP.GG

[원본 사이트](https://www.op.gg/) <br/>
[클론 사이트](https://animated-llama-195ed0.netlify.app/)
<hr/>

## OP.GG를 클론코딩 한 이유...
**html css를 배우고 클론코딩 할 사이트를 고르면서, 디자인이 화려하고 특별한 사이트를 많이 봤지만, 배운 지식으로 처음 만들어본 사이트인만큼, 처음보는 사이트보다는 자주 들어가봤고, 추억이 남아있는 사이트를 만들어보고 싶어서 고르게 됐답니다.**

_낭만..._
<hr/>

## HEAD

```
<!DOCTYPE html>
<html lang="ko">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta property="og:type" content="website" />
  <meta property="og:site_name" content="OPGG" />
  <meta property="og:title" content="롤 전적 검색은 OP.GG - 챔피언 공략과 게임 전적, 라이엇 아이디 태그 검색" />
  <meta property="og:description" content="챔피언 공략과 게임 전적, 라이엇 아이디 태그 검색" />
  <meta property="og:image" content="https://s-lol-web.op.gg/images/icon/opgglogo.svg?v=1707283412529" />
  <meta property="og:url" content="https://www.op.gg/" />
  <meta property="twitter:card" content="summary" />
  <meta property="twitter:site" content="OPGG" />
  <meta property="twitter:title" content="롤 전적 검색은 OP.GG - 챔피언 공략과 게임 전적, 라이엇 아이디 태그 검색" />
  <meta property="twitter:description" content="챔피언 공략과 게임 전적, 라이엇 아이디 태그 검색" />
  <meta property="twitter:image" content="https://s-lol-web.op.gg/images/icon/opgglogo.svg?v=1707283412529" />
  <meta property="twitter:url" content="https://www.op.gg/" />
  <title>롤 전적 검색은 OP.GG - 챔피언 공략과 게임 전적, 라이엇 아이디 태그 검색</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/reset-css@5.0.2/reset.min.css">
  <link rel="stylesheet" href="./main.css">
  <link rel="icon" type="image/x-icon" href="https://s-lol-web.op.gg/favicon.ico">
  <!-- 같은 링크끼리는 묶어서 작성하기 -->
</head>
```
**오픈 그래프와 트위터카드를 작성하여 링크를 보냈을때 부가 설명이 있도록 하였습니다.**
<br/>

`<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/reset-css@5.0.2/reset.min.css">`

▶ **jsDelivr 에서 가져온 css reset 링크를 활용하여 css기본설정을 초기화 해줬습니다.**
<br/>
`<link rel="icon" type="image/x-icon" href="https://s-lol-web.op.gg/favicon.ico">`

▶ **원본사이트에서 파비콘 링크를 가져왔습니다**
<br/>
`<link rel="stylesheet" href="./main.css">`

▶ **main.css를 html과 연결해줬습니다.**
<br/>
<hr/>

## Header x 주요내용

![](https://velog.velcdn.com/images/codiee/post/61900148-7efb-4ff8-b5f7-38c931e5bbf3/image.PNG)

**라인을 클래스 firstLine,rightMenu,secondLine, thirdLine 나누었습니다.**
<hr/>

**firstLine**
![](https://velog.velcdn.com/images/codiee/post/8c350e80-b8de-41d6-b6db-2ae7d2acc71f/image.PNG)

▶** 좌측패딩을 로고(OP.GG) width만큼 주고 로고를 넣었습니다. 백그라운드 컬러를 검정계열로 주고, li:first-child를 사용하여 배경컬러를 넣었으며 nav ul li태그를 사용하여 정리하였습니다. 
hover를 줘서 포인터 효과를 주었습니다.**
<hr/>

**rightLine**
![](https://velog.velcdn.com/images/codiee/post/5b0fa1ca-c6a8-47e3-afce-4cb59f960746/image.PNG)
▶** 아이콘 이미지 링크는 원본사이트를 참고하였습니다.**
<hr/>

**secondLine**
![](https://velog.velcdn.com/images/codiee/post/d919fdc5-181c-43f1-8d36-2d7463cdf945/image.PNG)
▶** 아이템들에 좌측마진을 주고 first-child 사용하여 첫아이템만 좌측마진을 0을 주고
정렬하였습니다. hover효과를 주고 home에만 border를 없앴습니다.**
<hr/>

**thirdLine**
![](https://velog.velcdn.com/images/codiee/post/9a9c9449-7fd8-4553-9c3b-2a843e5cc6c2/image.PNG)
▶**thirdLine 배경색을 넣고 hover로 underline을 입혔습니다. (🚀로켓은 이모티콘🚀)
🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀**
<hr/>

## Main x 주요내용
![](https://velog.velcdn.com/images/codiee/post/4427f6c6-c763-400f-9f00-0692d3b044f6/image.PNG)
<hr/>

**smallder** (~~챔피언 이름은 smolder입니다...헤헤.. 발음때문에 헷갈렸네요..~~)
<br/>

![](https://velog.velcdn.com/images/codiee/post/89736bd0-06d7-4dfe-828a-883ad2e1deb9/image.PNG)
▶**원본사이트에서 이미지를 얻어 width값을 주고 마진을 0 auto를 줘서 정렬하였습니다.**
<hr/>

**middle searchBox**
![](https://velog.velcdn.com/images/codiee/post/fd7e50aa-33b3-435b-8f18-3bc3f4e2a871/image.PNG)

▶**클래스명 middle에서는 flex-direction을 컬럼으로 줘서 아래방향으로 정렬하였습니다. searchBox는 지역,검색,버튼 부분으로 나누었고, 박스쉐도우를 주고, radius를 사용하여 박스를 꼭지점을 깎아줬습니다. 
text-align을 left 줘서 좌측정렬하였습니다. searchWrapper에는 flex:1을 줬습니다.  
input을 클릭했을때 검정테두리가 생겨서 outline:none을 줘서 제거하였습니다. 
버튼이미지는 원본사이트에서 얻어왔습니다.**
<hr/>

**middleSecondBanner**
**middleThirdBanner**

![](https://velog.velcdn.com/images/codiee/post/446f4d31-d814-433d-a10f-a2c6de762582/image.PNG)![](https://velog.velcdn.com/images/codiee/post/db630120-48a2-472b-8c5f-a7e0e74026bc/image.PNG)

▶**광고가 노출 되는 부분이라 이미지 삽입을 하였습니다.**
<hr/>

**middleTable**
**opggTalk**
**playerTab**
![](https://velog.velcdn.com/images/codiee/post/6822f273-4ca1-4bf7-883c-df1836c0684c/image.PNG)

▶**클래스 middleTable에서 2개의 섹션으로 나누어서, 좌측 opggTalk 우측 playerTab으로 만들었습니다. 
 기존사이트에는 그리드가 포함 돼있지 않아서, 좌측은 플렉스, 우측은 그리드를 조금씩 응용하여 바꿔봤습니다.**

## Footer x 주요내용

![](https://velog.velcdn.com/images/codiee/post/97942d6b-ed0f-4c1a-af8a-8e06f883b4fe/image.PNG)
<hr/>

**footerLogo**
**aTitle**
![](https://velog.velcdn.com/images/codiee/post/90b6629d-d2eb-418a-b247-efcf3ba50086/image.PNG)

▶**로고는 원본사이트에서 이미지를 가져왔고, flex를 활영하여 정리하였습니다.
상단에 첫줄은 aTitle로 같은클래스로 묶어서 정리하였고, 각 a태그로 만들어줬습니다. 
products와 apps에 글 우측 게임기모양은 이미지이며, 본사이트에서 링크를 가져왔습니다.
**
<hr/>



**footerBottom**

![](https://velog.velcdn.com/images/codiee/post/dcdcfffc-c2bb-4af5-9221-a18c01e59b91/image.PNG)

▶**footerBottom 부분은 먼저 border탑을 사용하여 선을 그어주고, flex를 활용하여 정렬하였습니다.**
**ul li태그를 사용하여 정리하였고, 제일하단에 카피라이터 영어문단은 p태크를 사용하였습니다.
sns는 본사이트에서 이미지를 가져와 a태그안에 감싸서 넣어줬습니다.**
<hr/>

## 소감...
**스스로가 보기에도 코드 가독성이나, 클래스 네이밍센스, 다방면에서 부족한 부분은 많았다. 
하지만 끝까지 따라 만들어봤다는거에 만족하고, 부족한 부분을 리팩토링하면서 js를 배워 기능도 추가 해볼계획이다. 클론코딩을 하는 습관은 시간은 걸리지만, 그만큼 성취감과 실력을 많이 올릴수있다.    **
<hr/>

# HTML 코드
```
<!DOCTYPE html>
<html lang="ko">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta property="og:type" content="website" />
  <meta property="og:site_name" content="OPGG" />
  <meta property="og:title" content="롤 전적 검색은 OP.GG - 챔피언 공략과 게임 전적, 라이엇 아이디 태그 검색" />
  <meta property="og:description" content="챔피언 공략과 게임 전적, 라이엇 아이디 태그 검색" />
  <meta property="og:image" content="https://s-lol-web.op.gg/images/icon/opgglogo.svg?v=1707283412529" />
  <meta property="og:url" content="https://www.op.gg/" />
  <meta property="twitter:card" content="summary" />
  <meta property="twitter:site" content="OPGG" />
  <meta property="twitter:title" content="롤 전적 검색은 OP.GG - 챔피언 공략과 게임 전적, 라이엇 아이디 태그 검색" />
  <meta property="twitter:description" content="챔피언 공략과 게임 전적, 라이엇 아이디 태그 검색" />
  <meta property="twitter:image" content="https://s-lol-web.op.gg/images/icon/opgglogo.svg?v=1707283412529" />
  <meta property="twitter:url" content="https://www.op.gg/" />
  <title>롤 전적 검색은 OP.GG - 챔피언 공략과 게임 전적, 라이엇 아이디 태그 검색</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/reset-css@5.0.2/reset.min.css">
  <link rel="stylesheet" href="./main.css">
  <link rel="icon" type="image/x-icon" href="https://s-lol-web.op.gg/favicon.ico">
  <!-- 같은 링크끼리는 묶어서 작성하기 -->
</head>

<body>
  <header>
    <div class="headerMenu">
      <div class="firstLine">
        <a class="logo" href="javascript:void(0)">
          <img src="https://s-lol-web.op.gg/images/icon/opgglogo.svg?v=1707283412529" width="65" height="16"
            alt="OP.GG">
        </a>
        <nav>
          <ul>
            <li>
              <span>
                <img
                  src="https://opgg-gnb.akamaized.net/static/images/icons/lol.svg?image=q_auto,f_webp,w_48,h_48&amp;v=1707283412529"
                  width="24" height="24" alt="리그오브레전드">
                <span>리그오브레전드</span>
              </span>
            </li>
            <li>
              <a href="javascript:void(0)" rel="noreferrer"><img
                  src="https://opgg-gnb.akamaized.net/static/images/icons/pal.svg?image=q_auto,f_webp,w_48,h_48&amp;v=1707283412529"
                  width="24" height="24" alt="팰월드">
                <span class="palWorld">B</span>
                <span>팰월드</span>
              </a>
            </li>
            <li>
              <a href="javascript:void(0)">
                <img
                  src="https://opgg-gnb.akamaized.net/static/images/icons/dskapp.svg?image=q_auto,f_webp,w_48,h_48&amp;v=1707283412529"
                  width="24" height="24" alt="데스크톱">
                <span>데스크톱</span>
              </a>
            </li>
            <li>
              <a href="javascript:void(0)">
                <img
                  src="https://opgg-gnb.akamaized.net/static/images/icons/tft.svg?image=q_auto,f_webp,w_48,h_48&amp;v=1707283412529"
                  width="24" height="24" alt="전략적 팀 전투">
                <span>전략적 팀 전투</span>
              </a>
            </li>
            <li>
              <a href="javascript:void(0)">
                <img
                  src="https://opgg-gnb.akamaized.net/static/images/icons/val.svg?image=q_auto,f_webp,w_48,h_48&amp;v=1707283412529"
                  width="24" height="24" alt="발로란트">
                <span>발로란트</span>
              </a>
            </li>
            <li>
              <a href="javascript:void(0)"><img
                  src="https://opgg-gnb.akamaized.net/static/images/icons/pubg.svg?image=q_auto,f_webp,w_48,h_48&amp;v=1707283412529"
                  width="24" height="24" alt="배틀그라운드">
                <span>배틀그라운드</span>
              </a>
            </li>
            <li><a href="javascript:void(0)">
                <img
                  src="https://opgg-gnb.akamaized.net/static/images/icons/overwatch.svg?image=q_auto,f_webp,w_48,h_48&amp;v=1707283412529"
                  width="24" height="24" alt="오버워치2">
                <span>오버워치2</span>
              </a>
            </li>
            <li><a href="javascript:void(0)">
                <img
                  src="https://opgg-gnb.akamaized.net/static/images/icons/esports.svg?image=q_auto,f_webp,w_48,h_48&amp;v=1707283412529"
                  width="24" height="24" alt="이스포츠">
                <span>이스포츠</span>
              </a>
            </li>
            <li>
              <a href="javascript:void(0)">
                <img
                  src="https://opgg-gnb.akamaized.net/static/images/icons/talk.svg?image=q_auto,f_webp,w_48,h_48&amp;v=1707283412529"
                  width="24" height="24" alt="톡피지지">
                <span>톡피지지</span>
              </a>
            </li>
            <li><a href="javascript:void(0)">
                <img
                  src="https://opgg-gnb.akamaized.net/static/images/icons/gigs.svg?image=q_auto,f_webp,w_48,h_48&amp;v=1707283412529"
                  width="24" height="24" alt="Gigs">
                <span class="palWorld">N</span>
                <span>Gigs</span>
              </a>
            </li>
            <li>
              <a href="javascript:void(0)">
                <img
                  src="https://opgg-gnb.akamaized.net/static/images/icons/duo.svg?image=q_auto,f_webp,w_48,h_48&amp;v=1707283412529"
                  width="24" height="24" alt="Duo">
                <span>Duo</span>
              </a>
            </li>
          </ul>
        </nav>
        <div class="rightMenu">
          <button class="ghost">
            <span class="hidden">1:1 문의하기</span>
          </button>
          <button class="brightNess">
            <span class="hidden">Theme Button</span>
          </button>
          <button class="language">
            <span class="hidden">언어</span>
          </button>
        </div>
        <div class="loginMenu">
          <button class="login">
            <a href="javascript:void(0)">로그인</a>
          </button>
        </div>
      </div>
      <div class="secondLine">
        <div class="routeMenu">
          <nav class="routeNav">
            <ul class="routeList">
              <li class="routeItem">
                <a href="javascript:void(0)">
                  <div class="home">홈</div>
                </a>
              </li>
              <li class="routeItem">
                <a href="javascript:void(0)">
                  <div class="champion">챔피언 분석</div>
                </a>
              </li>
              <li class="routeItem">
                <a href="javascript:void(0)">
                  <div class="gameMode">게임 모드</div>
                </a>
              </li>
              <li class="routeItem">
                <a href="javascript:void(0)">
                  <div class="urf">우르프
                    <div class="urfTag">N</div>
                  </div>
                </a>
              </li>
              <li class="routeItem">
                <a href="javascript:void(0)">
                  <div class="statistics">통계</div>
                </a>
              </li>
              <li class="routeItem">
                <a href="javascript:void(0)">
                  <div class="lanking">랭킹</div>
                </a>
              </li>
              <li class="routeItem">
                <a href="javascript:void(0)">
                  <div class="pro">프로관전</div>
                </a>
              </li>
              <li class="routeItem">
                <a href="javascript:void(0)">
                  <div class="multiSearch">멀티서치</div>
                </a>
              </li>
              <li class="routeItem">
                <a href="javascript:void(0)">
                  <div class="talk">커뮤니티</div>
                </a>
              </li>
              <li class="routeItem">
                <a href="javascript:void(0)">
                  <div class="edu">강의</div>
                </a>
              </li>
              <li class="routeItem">
                <a href="javascript:void(0)">
                  <div class="myPage">마이페이지</div>
                </a>
              </li>
            </ul>
          </nav>
        </div>
      </div>
      <div class="banner">
        <div class="thirdLine">
          <a href="javascript:void(0)">배치고사 연승으로 협곡을 지배하세요! 🚀</a>
        </div>
      </div>
  </header>
  <main>
    <h1 class="hidden">OP.GG</h1>
    <div class="smallder">
      <img
        src="https://meta-static.op.gg/logo/image/8a600438ab0430d4094b6d4e6ecb3d84.png?image=q_auto,f_webp,w_auto,h_448&amp;v=1707283412529"
        height="224" alt="OP.GG logo (스몰더)" title="스몰더">
    </div>
    <div class="middle">
      <div>
        <form class="searchBox">
          <div>
            <small class="label">지역</small>
            <div class="pickArea">
              <label class="hidden" for="kr">kr</label>
              <select id="kr">
                <option value="kr">KR</option>
                <option value="na">NA</option>
                <option value="euw">EUW</option>
                <option value="oce">OCE</option>
                <option value="kr" selected="">KR</option>
                <option value="jp">JP</option>
              </select>
            </div>
            <div class="pickKr">
              <div>
                <button type="button" class="korea">
                  <span>Korea</span>
                </button>
              </div>
            </div>
          </div>
          <div class="searchWrapper">
            <label for="searchHome" class="label">검색</label>
            <input id="searchHome" name="search" autocomplete="off" type="text" value>
            <label for="searchHome" class="searchPlaceholder">
              <span class="placeHolderHome">
                플레이어 이름
                +
              </span>
              <span class="placeHoderTag">
                #KR1
              </span>
            </label>
          </div>
          <button class="gg-btn" type="submit">.GG</button>
        </form>
      </div>
      <div class="middleSecond">
        <div class="middleSecondBanner">
        </div>
      </div>
    </div>
    <div class="middleThird">
      <div class="middleThirdBanner">
        <span><img
            src="https://search.pstatic.net/common/?src=http%3A%2F%2Fblogfiles.naver.net%2FMjAyNDAxMThfMTE0%2FMDAxNzA1NTU1MzIwMzQx.t4Vg3vuXLJHzSYGfYRjS8mupii4__BtXrKXqbjvcr-Ug.kIecAmp7KT6Noyvas69z_jUp6o3EEMjmF33KVuL5sPIg.JPEG.marugameacademy%2F%25BF%25F8%25B5%25F4_%25B4%25EB%25C7%25A5_%25C3%25A8%25C7%25C7%25BE%25F0.jpg&type=sc960_832"
            alt="롤"></span>
      </div>
    </div>
    <div class="middleTable">
      <section class="opggTalk">
        <h2><a href="javascript:void(0)">OP.GG Talk 인기글</a></h2>
        <div>
          <span class="numbering">1</span>
          <img
            src="https://images.velog.io/images/kyungjin/post/fdd5cc22-dfdc-4091-a2fb-039ce36ce9d8/%ED%8B%B0%EB%AA%A8.png"
            alt="티모" width="90px" height="70px">
          <span class="topic"><a href="">프론트엔드는 패스트캠퍼스</a></span>
          <span class="saw">[12]</span>
        </div>
        <div>
          <span class="numbering">2</span>
          <img src="https://cdn-store.leagueoflegends.co.kr/images/v2/emotes/3202.png" alt="이즈" width="90px"
            height="70px">
          <span class="topic"><a href="">백엔드는 패스트캠퍼스</a></span>
          <span class="saw">[24]</span>
        </div>
        <div>
          <span class="numbering">3</span>
          <img src="https://cdn-store.leagueoflegends.co.kr/images/v2/emotes/4477.png" alt="용" width="90px"
            height="70px">
          <span class="topic"><a href="">그로스 마케팅은 패스트캠퍼스</a></span>
          <span class="saw">[52]</span>
        </div>
        <div>
          <span class="numbering">4</span>
          <img src="https://cdn-store.leagueoflegends.co.kr/images/v2/emotes/4033.png" alt="콘" width="90px"
            height="70px">
          <span class="topic"><a href="">프로덕트 매니저는 패스트캠퍼스</a></span>
          <span class="saw">[11]</span>
        </div>
        <div>
          <span class="numbering">5</span>
          <img src="https://cdn-store.leagueoflegends.co.kr/images/v2/emotes/4035.png" alt="크산테" width="90px"
            height="70px">
          <span class="topic"><a href="">UXUI 디자인은 패스트캠퍼스</a></span>
          <span class="saw">[36]</span>
        </div>
      </section>
      <section class="playerTab">
        <div>
          <span>
            <img
              src="https://images.contentstack.io/v3/assets/blt731acb42bb3d1659/blte41a162aed9339b7/5db05fc60b39e86c2f83dc0d/RiotX_ChampionList_garen.jpg?quality=90&width=250"
              alt="가렌" width="177px" height="256px">
          </span>
          <span>
            <img
              src="https://images.contentstack.io/v3/assets/blt731acb42bb3d1659/bltb94b4161d8022c45/5db05fdfe9d7526ab429e53c/RiotX_ChampionList_lux.jpg?quality=90&width=250"
              alt="럭스" width="177px" height="256px">
          </span>
          <span>
            <img
              src="https://images.contentstack.io/v3/assets/blt731acb42bb3d1659/blt075d278529811445/5db05fde6af83b6d7032c8fe/RiotX_ChampionList_leesin.jpg?quality=90&width=250"
              alt="리신" width="177px" height="256px">
          </span>
          <span>
            <img
              src="https://images.contentstack.io/v3/assets/blt731acb42bb3d1659/bltc81eece55f126d2d/5db05fe86af83b6d7032c904/RiotX_ChampionList_morgana.jpg?quality=90&width=250"
              alt="모르가나" width="177px" height="256px">
          </span>
          <span>
            <img
              src="https://images.contentstack.io/v3/assets/blt731acb42bb3d1659/blt825d0c333f6e74ae/5db060142140ec675d68f4bb/RiotX_ChampionList_velkoz.jpg?quality=90&width=250"
              alt="벨코즈" width="177px" height="256px">
          </span>
          <span>
            <img
              src="https://images.contentstack.io/v3/assets/blt731acb42bb3d1659/bltc8ca2e9bba653dda/5db05fb2dc674266df3d5d30/RiotX_ChampionList_brand.jpg?quality=90&width=250"
              alt="브랜드" width="177px" height="256px">
          </span>
        </div>
        <span class="playerTabEnd">
          <span class="white">Grid</span>
          <span class="black">X</span>
          <span class="orange">League of Legend</span>
        </span>
      </section>
    </div>
  </main>
  <footer>
    <div>
      <section style="display: flex;">
        <div class="footerLogo">
          <a href="javascript:void(0)">
            <img src="https://s-lol-web.op.gg/images/icon/icon-opgglogo-white.svg?v=1708507553015" width="99"
              height="24" alt="OP.GG" loading="lazy">
          </a>
        </div>
        <div>
          <a class="aTitle" href="javascript:void(0)">OP.GG</a>
          <a href="javascript:void(0)">About OP.GG</a>
          <a href="javascript:void(0)">Company</a>
          <a href="javascript:void(0)">Blog</a>
          <a href="javascript:void(0)">로고 히스토리</a>
        </div>
        <div>
          <a class="aTitle" href="javascript:void(0)">Products</a>
          <a href="javascript:void(0)">리그오브레전드
            <img src="https://s-lol-web.op.gg/images/icon/icon-game-white.svg?v=1708507553015" width="16" height="16"
              alt="리그오브레전드" class="game">
          </a>
          <a href="javascript:void(0)">팰월드
            <img src="https://s-lol-web.op.gg/images/icon/icon-game-white.svg?v=1708507553015" width="16" height="16"
              alt="팰월드" class="game"></a>
          <a href="javascript:void(0)">데스크톱
            <img src="https://s-lol-web.op.gg/images/icon/icon-game-white.svg?v=1708507553015" width="16" height="16"
              alt="데스크톱" class="game">
          </a>
          <a href="javascript:void(0)">전략적 팀 전투
            <img src="https://s-lol-web.op.gg/images/icon/icon-game-white.svg?v=1708507553015" width="16" height="16"
              alt="전략적 팀 전투" class="game">
          </a>
          <a href="javascript:void(0)">발로란트
            <img src="https://s-lol-web.op.gg/images/icon/icon-game-white.svg?v=1708507553015" width="16" height="16"
              alt="발로란트" class="game">
          </a>
          <a href="javascript:void(0)">배틀그라운드
            <img src="https://s-lol-web.op.gg/images/icon/icon-game-white.svg?v=1708507553015" width="16" height="16"
              alt="배틀그라운드" class="game">
          </a>
          <a href="javascript:void(0)">오버워치2
            <img src="https://s-lol-web.op.gg/images/icon/icon-game-white.svg?v=1708507553015" width="16" height="16"
              alt="오버워치2" class="game">
          </a>
          <a href="javascript:void(0)">이스포츠
            <img src="https://s-lol-web.op.gg/images/icon/icon-game-white.svg?v=1708507553015" width="16" height="16"
              alt="이스포츠" class="game">
          </a>
          <a href="javascript:void(0)">톡피지지
            <img src="https://s-lol-web.op.gg/images/icon/icon-game-white.svg?v=1708507553015" width="16" height="16"
              alt="톡피지지" class="game">
          </a>
          <a href="javascript:void(0)">Gigs
            <img src="https://s-lol-web.op.gg/images/icon/icon-game-white.svg?v=1708507553015" width="16" height="16"
              alt="Gigs" class="game">
          </a>
          <a href="javascript:void(0)">Duo
            <img src="https://s-lol-web.op.gg/images/icon/icon-game-white.svg?v=1708507553015" width="16" height="16"
              alt="Duo" class="game">
          </a>
        </div>
        <div>
          <a class="aTitle" href="javascript:void(0)">Apps
          </a>
          <a href="javascript:void(0)">OP.GG Android App
            <img src="https://s-lol-web.op.gg/images/icon/icon-game-white.svg?v=1708507553015" width="16" height="16"
              alt="OP.GG Android App" class="game">
          </a>
          <a href="javascript:void(0)">OP.GG iOS App
            <img src="https://s-lol-web.op.gg/images/icon/icon-game-white.svg?v=1708507553015" width="16" height="16"
              alt="OP.GG iOS App" class="game">
          </a>
          <a href="javascript:void(0)">TFT Android App
            <img src="https://s-lol-web.op.gg/images/icon/icon-game-white.svg?v=1708507553015" width="16" height="16"
              alt="TFT Android App" class="game">
          </a>
          <a href="javascript:void(0)">TFT iOS App
            <img src="https://s-lol-web.op.gg/images/icon/icon-game-white.svg?v=1708507553015" width="16" height="16"
              alt="Apps" class="game">
          </a>
          <a href="javascript:void(0)">TalkG Android App</a>
          <a href="javascript:void(0)">TalkG iOS App</a>
        </div>
        <div>
          <a class="aTitle" href="javascript:void(0)">Resources</a>
          <a href="javascript:void(0)">개인정보처리방침</a>
          <a href="javascript:void(0)">이용약관</a>
          <a href="javascript:void(0)">도움말</a>
          <a href="javascript:void(0)">이메일 문의하기</a>
          <a href="javascript:void(0)">고객센터 문의</a>
        </div>
        <div>
          <a class="aTitle" href="javascript:void(0)">More</a>
          <a href="javascript:void(0)">제휴</a>
          <a href="javascript:void(0)">광고</a>
          <a href="javascript:void(0)">채용</a>
        </div>
      </section>
      <section class="footerBottom">
        <div class="footerBottonFirst">
          <ul class="company">
            <li>
              <span>주식회사 오피지지 (OP.GG)</span>
            </li>
            <li>
              <span>통신판매업신고 :</span>
              <span>제2019-서울강남-01973호</span>
            </li>
            <li>
              <span>사업자등록번호 :</span>
              <span>295-88-00023</span>
            </li>
            <li>
              <span>대표자 :</span>
              <span>최상락</span>
            </li>
            <li>
              <span>서울특별시 강남구 테헤란로 507, 1층, 2층(삼성동, wework빌딩)</span>
            </li>
            <li>
              <span>전화 :</span>
              <span>02-455-9903 (평일 09:00 ~ 18:00)</span>
            </li>
            <li>
              <span>이메일 :</span>
              <span>
                <a href="javascript:void(0)">service@op.gg</a>
              </span>
            </li>
          </ul>
          <p class="copyright">
            © 2012-
            2024
            OP.GG. OP.GG is not endorsed by Riot Games and does not reflect the views or opinions of Riot Games or
            anyone officially involved in producing or managing League of Legends. League of Legends and Riot Games
            are trademarks or registered trademarks of Riot Games, Inc. League of Legends © Riot Games, Inc.
          </p>
        </div>
        <nav class="sns">
          <a href="javascript:void(0)">
            <img src="https://s-lol-web.op.gg/images/icon/icon-logo-instagram.svg?v=1708507553015" width="24"
              height="24" alt="instagram account" loading="lazy">
          </a>
          <a>
            <img src="https://s-lol-web.op.gg/images/icon/icon-logo-youtube.svg?v=1708507553015" width="24" height="24"
              alt="twitter account" loading="lazy">
          </a>
          <a>
            <img src="https://s-lol-web.op.gg/images/icon/icon-logo-x.svg?v=1708507553015" width="24" height="24"
              alt="twitter account" loading="lazy">
          </a>
          <a>
            <img src="https://s-lol-web.op.gg/images/icon/icon-logo-facebook.svg?v=1708507553015" width="24" height="24"
              alt="facebook account" loading="lazy">
          </a>
        </nav>
      </section>
    </div>
  </footer>
</body>

</html>
```
<hr/>

# CSS 코드
```
/* common */
:root {
  /* 글자색 */
  --primary-font-color: #c3cbd1;
  --sub-font-color: #fff;

  /* 테두리 색 */
  --primary-background-color: #5383e8;
  --sub-background-color: #28344e;
  --route-hover-background-color: #2f436e;
}
body {
  background-color: var(--primary-background-color);
}
.hidden {
  position: absolute;
  clip: rect(0 0 0 0);
  width: 1px;
  height: 1px;
  margin: -1px;
}
label {
  cursor: pointer;
}
select {
  appearance: none;
  background: var(--sub-font-color);
  border: none;
  vertical-align: middle;
  border-radius: 0;
}
button {
  border: 0;
  padding: 0;
  background: transparent;
  cursor: pointer;
  margin: 0;
}
option {
  font-weight: normal;
  display: block;
  min-height: 1.2em;
  padding: 0px 2px 1px;
  white-space: nowrap;
}
ol,
ul,
li {
  list-style: none;
}
img {
  border: 0;
  vertical-align: center;
  max-width: 100%;
}
a {
  cursor: pointer;
}
/* header */
header {
  display: block;
}
header .headerMenu {
  min-width: 1080px;
}
header .headerMenu .firstLine {
  position: relative;
  height: 40px;
  padding-left: 98px;
  background-color: var(--sub-background-color);
  display: flex;
  align-items: center;
}
header .headerMenu .firstLine .logo {
  position: absolute;
  top: 0;
  left: 0;
  width: 98px;
  height: 40px;
  background-color: var(--primary-background-color);
  display: flex;
  align-items: center;
  justify-content: center;
}
header .headerMenu .firstLine nav {
  flex: 1;
}
header .headerMenu .firstLine nav ul {
  display: flex;
  flex-wrap: wrap;
  overflow: hidden;
  height: 40px;
  width: 1550px;
}
header .headerMenu .firstLine nav ul li {
  display: flex;
  align-items: center;
  height: 40px;
}
header .headerMenu .firstLine nav ul li a {
  display: flex;
  justify-content: center;
  align-items: center;
  color: var(--primary-font-color);
  height: 32px;
  line-height: 32px;
  margin: 4px;
  padding: 0 8px;
  text-decoration: none;
}
header .headerMenu .firstLine nav ul li a:hover {
  background-color: var(--route-hover-background-color);
  border-radius: 7px;
}
header .headerMenu .firstLine nav ul li > a > span,
header .headerMenu .firstLine nav ul li > span > span {
  margin-left: 8px;
  font-size: 12px;
}
header .headerMenu .firstLine nav ul li > span {
  display: flex;
  justify-content: center;
  align-items: center;
}
header .headerMenu .firstLine nav ul li:first-child {
  padding: 0 12px 0 0;
  background-color: var(--primary-background-color);
}
header .headerMenu .firstLine nav ul li:first-child > span {
  color: var(--sub-font-color);
}
.palWorld {
  display: block;
  width: 16px;
  height: 16px;
  line-height: 16px;
  border-radius: 50%;
  font-weight: bold;
  text-align: center;
  background-color: #ffb900;
  color: var(--sub-background-color);
}
header .headerMenu .rightMenu {
  width: 90px;
}
header .headerMenu .rightMenu .ghost {
  width: 24px;
  height: 24px;
  background-image: url(https://s-lol-web.op.gg/images/icon/chatbot.gif);
  background-size: cover;
  padding: 0;
  border: none;
}
header .headerMenu .rightMenu .brightNess {
  width: 24px;
  height: 24px;
  background: url(https://s-lol-web.op.gg/images/icon/icon-lightmode.svg);
}
header .headerMenu .rightMenu .language {
  width: 24px;
  height: 24px;
  background: url(https://s-lol-web.op.gg/images/icon/icon-world-light-blue.svg?v=1707283412529);
}
header .headerMenu .loginMenu {
  width: 80px;
}
header .headerMenu .loginMenu .login > a {
  display: block;
  padding: 4px 16px;
  line-height: 18px;
  font-size: 12px;
  background-color: var(--primary-background-color);
  color: var(--sub-font-color);
  border-radius: 4px;
  white-space: nowrap;
  text-decoration: none;
}
header .headerMenu .secondLine {
  border-bottom: 1px solid #4171d6;
  background-color: 1px solid var(--primary-background-color);
  display: flex;
  justify-content: center;
  box-sizing: border-box;
  height: 49px;
}
header .headerMenu .secondLine .routeMenu {
  position: relative;
  display: flex;
  align-items: center;
  width: 1080px;
}
header .headerMenu .secondLine .routeMenu .routeList {
  display: flex;
}
header .headerMenu .secondLine .routeMenu .routeList .routeItem {
  margin-left: 24px;
}
header .headerMenu .secondLine .routeMenu .routeList .routeItem:hover {
  color: var(--sub-font-color);
  border-bottom: 3px solid var(--sub-font-color);
}
header .headerMenu .secondLine .routeMenu .routeList .routeItem a {
  text-decoration: none;
}

header .headerMenu .secondLine .routeMenu .routeList .routeItem:first-child {
  margin-left: 0;
}
header .headerMenu .secondLine .routeMenu .routeList .routeItem .home {
  display: flex;
  align-items: center;
  color: var(--sub-font-color);
  border-bottom: 3px solid var(--sub-font-color);
  font-size: 15px;
  box-sizing: border-box;
  line-height: 22px;
  padding: 10px 0 9px;
}
header .headerMenu .secondLine .routeMenu .routeList .routeItem .home:hover {
  border: none;
}
header .headerMenu .secondLine .routeMenu .routeList .routeItem .champion,
header .headerMenu .secondLine .routeMenu .routeList .routeItem .urf,
header .headerMenu .secondLine .routeMenu .routeList .routeItem .statistics,
header .headerMenu .secondLine .routeMenu .routeList .routeItem .lanking,
header .headerMenu .secondLine .routeMenu .routeList .routeItem .pro,
header .headerMenu .secondLine .routeMenu .routeList .routeItem .multiSearch,
header .headerMenu .secondLine .routeMenu .routeList .routeItem .talk,
header .headerMenu .secondLine .routeMenu .routeList .routeItem .edu,
header .headerMenu .secondLine .routeMenu .routeList .routeItem .myPage {
  display: flex;
  align-items: center;
  color: #b3cdff;
  font-size: 15px;
  border-bottom: 3px solid transparent;
  box-sizing: border-box;
  line-height: 22px;
  padding: 10px 0 9px;
}
header .headerMenu .secondLine .routeMenu .routeList .routeItem .gameMode {
  display: flex;
  align-items: center;
  color: #00fede;
  border-bottom: 3px solid transparent;
  font-size: 15px;
  box-sizing: border-box;
  line-height: 22px;
  padding: 10px 0 9px;
}
header .headerMenu .secondLine .routeMenu .routeList .routeItem .urf .urfTag {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 16px;
  height: 16px;
  color: #fff;
  background: #ffb900;
  border-radius: 4px;
  font-size: 12px;
  font-weight: 700;
}

header .banner .thirdLine {
  display: block;
  width: 100%;
  color: #202d37;
  background: #ffb900;
}
header .banner .thirdLine > a {
  display: block;
  margin: 0 auto;
  text-align: left;
  box-sizing: border-box;
  width: 1080px;
  font-size: 14px;
  min-height: 40px;
  line-height: 40px;
  padding: 0;
  color: inherit;
  text-decoration: none;
}
header .banner .thirdLine > a:hover {
  text-decoration: underline;
}
main {
  display: block;
  width: 1080px;
  margin: 0 auto;
}
main .smallder {
  margin: 56px 0 46px;
}
main .smallder img {
  display: block;
  max-height: 224px;
  margin: 0 auto;
}
main .middle {
  display: flex;
  flex-direction: column;
  gap: 24px;
  position: relative;
  width: 800px;
  margin: 0 auto;
  text-align: center;
}
main .middle div:first-of-type {
  position: relative;
}
main .middle .searchBox {
  box-shadow: 0 2px 2px 0 rgba(0, 0, 0, 0.19);
  display: flex;
  align-items: center;
  position: relative;
  background: #fff;
  border-radius: 30px;
  height: 60px;
  text-align: left;
}
main .middle .searchBox div {
  position: relative;
  height: 20px;
}
main .middle .searchBox div:first-of-type {
  padding-left: 32px;
  padding-right: 8px;
  margin-right: 16px;
}
main .middle .searchBox div small,
main .middle .searchBox div .label {
  display: block;
  font-size: 12px;
  line-height: 16px;
  color: #202d37;
  font-style: normal;
}
main .middle .searchBox .label {
  margin-bottom: 4px;
  font-weight: bold;
}
main .middle .searchBox .pickArea {
  font-size: 12px;
  line-height: 16px;
  position: absolute;
  visibility: hidden;
  display: block;
  width: 194px;
}
main .middle .searchBox .pickArea::after {
  position: absolute;
  content: "";
  top: 50%;
  right: 15px;
  width: 0;
  height: 0;
  border: 5px solid transparent;
  border-top-color: #9aa4af;
  margin-top: -2.5px;
}
main .middle .searchBox .pickKr {
  position: relative;
  display: block;
  width: 194px;
}
main .middle .searchBox .pickKr .korea {
  display: flex;
  position: relative;
  overflow: hidden;
  padding: 0;
  height: auto;
  color: #9aa4af;
  width: 100%;
  border: 0 none;
  text-align: left;
  align-items: center;
  border-radius: 4px;
  box-sizing: border-box;
}
main .middle .searchBox .pickKr .korea::after {
  position: absolute;
  content: "";
  top: 50%;
  right: 15px;
  width: 0;
  height: 0;
  border: 5px solid transparent;
  margin-top: -2.5px;
  border-top-color: #9aa4af;
}
main .middle .searchBox .pickKr .korea span {
  font-size: 14px;
  line-height: 20px;
  white-space: nowrap;
  text-overflow: ellipsis;
  overflow: hidden;
}
main .middle .searchBox > div:first-of-type::after {
  content: "";
  display: block;
  position: absolute;
  right: 0;
  top: 50%;
  margin-top: -7px;
  width: 1px;
  height: 14px;
  background: #ebeef1;
}
main .middle .searchBox > div {
  position: relative;
  height: 40px;
}
main .middle .searchBox .searchWrapper {
  flex: 1;
}
main .middle .searchBox .searchWrapper label + input {
  background: #fff;
  position: relative;
  border: 0;
  width: 100%;
  box-sizing: border-box;
  font-size: 14px;
  line-height: 20px;
  color: #202d37;
}
main .middle .searchBox .searchWrapper input {
  outline: none;
}
main .middle .searchBox .searchWrapper .searchPlaceholder {
  font-size: 14px;
  height: 20px;
  left: 0;
  bottom: 0;
  color: #9aa4af;
  position: absolute;
  display: flex;
  align-items: center;
  gap: 4px;
  cursor: inherit;
  z-index: 1;
  line-height: 16px;
}
main .middle .searchBox .searchWrapper .searchPlaceholder:active {
  display: none;
}
main .middle .searchBox .searchWrapper .searchPlaceholder .placeHoderTag {
  font-weight: 500;
  border-radius: 3px;
  background-color: #f7f7f9;
}
main .middle .searchBox button[type="submit"] {
  background-image: url(https://s-lol-web.op.gg/images/icon/icon-gg.svg);
  background-repeat: no-repeat;
  background-size: 42px;
  background-position: center;
  width: 90px;
  height: 60px;
  font-size: 0;
}
main .middle .middleSecond {
  width: 100%;
  height: 130px;
  display: flex;
  position: relative;
}
main .middle .middleSecond .middleSecondBanner {
  width: 600px;
  margin: 0 auto;
  border-radius: 10px;
  background-image: url(./fastcampus.PNG);
  background-size: auto;
  background-repeat: no-repeat;
}
main .middleThird .middleThirdBanner {
  width: 1080px;
  height: 270px;
  border-radius: 10px;
  margin: 25px auto;
  background: var(--primary-background-color);
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 90px;
  font-weight: 700;
}
main .middleThird .middleThirdBanner span img {
  width: 900px;
  height: 270px;
  border-radius: 20px;
}
main .middleTable {
  display: flex;
  width: 1080px;
  margin: 36px auto 0px;
  box-sizing: border-box;
}
main .middleTable > :first-of-type {
  flex-basis: 536px;
  margin-right: 8px;
}
main .middleTable > section {
  background-color: white;
  border-radius: 4px;
  min-height: 405px;
}
main .middleTable .opggTalk {
  width: 100%;
}
main .middleTable .opggTalk h2 a {
  display: block;
  padding: 17px 0px 16px 20px;
  text-decoration: none;
  color: inherit;
  font-weight: bold;
  line-height: 17px;
  font-size: 14px;
}
main .middleTable .opggTalk .opggTalkTopic {
  padding-bottom: 13px;
  display: flex;
  flex-flow: column;
}
main .middleTable .opggTalk > div {
  margin: 0 20px;
  display: flex;
  border-bottom: 1px solid #d1d3d3;
  width: 500px;
  height: 100px;
  align-items: center;
}
main .middleTable .opggTalk > div:nth-child(6) {
  border-bottom: none;
}
main .middleTable .opggTalk > div .numbering {
  display: flex;
  justify-content: center;
  width: 40px;
  font-size: 20px;
  font-style: italic;
}
main .middleTable .opggTalk > div .topic {
  display: inline-block;
  margin-left: 20px;
}
main .middleTable .opggTalk > div span a {
  text-decoration: none;
  color: #171818;
}
main .middleTable .opggTalk > div .saw {
  display: inline-block;
  color: #4171d6;
  padding-left: 4px;
  font-size: 13px;
}
main .middleTable .opggTalk > div .saw:hover {
  cursor: pointer;
}
main .middleTable .playerTab {
  max-width: 536px;
  border-radius: 9px;
  background-color: var(--primary-background-color);
}
main .middleTable .playerTab div {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  grid-template-rows: 256px 256px;
}
main .middleTable .playerTab div span {
  display: grid;
  justify-content: center;
  border: 1px solid var(--primary-background-color);
}
main .middleTable .playerTab div span img {
  border-radius: 9px;
}
main .middleTable .playerTab .playerTabEnd {
  width: 532px;
  height: 50px;
  display: flex;
  background-color: black;
  align-items: center;
  justify-content: center;
  font-size: 30px;
  border-radius: 0 0 9px 9px;
}
main .middleTable .playerTab .white {
  color: white;
  padding-right: 10px;
}
main .middleTable .playerTab .black {
  color: white;
  padding-right: 10px;
}
main .middleTable .playerTab .orange {
  color: orange;
}
footer {
  min-width: 1080px;
  margin-top: 48px;
  padding: 48px 0;
  background: transparent;
}
footer > div {
  width: 1080px;
  margin: 0 auto;
}
footer > div section {
}
footer > div section .footerLogo {
  margin-left: 0;
  flex-grow: 1;
}
footer > div section .footerLogo a {
  font-size: 14px;
}
footer > div section div {
  flex-basis: 170px;
  margin-left: 12px;
}
footer > div section div .aTitle {
  font-weight: bold;
  font-size: 14px;
  color: white;
  padding-bottom: 16px;
}
footer > div section div a {
  display: inline-block;
  width: 100%;
  line-height: 24px;
  text-decoration: none;
  color: white;
  font-size: 14px;
}
footer .footerBottom {
  margin-top: 24px;
  padding-top: 24px;
  border-top: 1px solid #dbe0e4;
  align-items: flex-start;
  gap: 16px;
  color: #fff;
  font-size: 12px;
  line-height: 16px;
  display: flex;
}
footer .footerBottom .footerBottonFirst {
  flex: 1;
  display: flex;
  flex-direction: column;
  gap: 8px;
}
footer .footerBottom .footerBottonFirst .company {
  display: flex;
  flex-wrap: wrap;
  gap: 2px 8px;
  margin: 0;
  padding: 0;
}
footer .footerBottom .footerBottonFirst .company > li {
  position: relative;
  gap: 8px;
  display: flex;
  align-items: center;
}
footer .footerBottom .footerBottonFirst .company > li::after {
  content: "";
  display: block;
  width: 1px;
  height: 12px;
  background: #81acff;
}
footer .footerBottom .footerBottonFirst .copyright {
  font-size: 11px;
  font-weight: 500;
}
footer .footerBottom .sns {
  display: flex;
  flex-basis: auto;
}
footer .footerBottom .sns a {
  vertical-align: bottom;
  width: 24px;
  height: 24px;
  display: inline-block;
  margin-right: 9px;
}
footer .footerBottom .sns a:first-of-type {
  margin-left: 0;
}
```
<hr/>
```
