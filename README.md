# OP.GG 클론

[원본 사이트](https://www.op.gg/) <br/>
[클론 사이트]()

![OP.GG](op.gg.PNG)

## 선택요구사항

```html
[
<header>
  ,
  <section>등 시멘틱 태그 활용] [CSS flex 활용]</section>
</header>
```

## 오픈 그래프

```html
<meta property="og:type" content="website" />
<meta property="og:site_name" content="OPGG" />
<meta
  property="og:title"
  content="롤 전적 검색은 OP.GG - 챔피언 공략과 게임 전적, 라이엇 아이디 태그 검색"
/>
<meta
  property="og:description"
  content="챔피언 공략과 게임 전적, 라이엇 아이디 태그 검색"
/>
<meta
  property="og:image"
  content="https://s-lol-web.op.gg/images/icon/opgglogo.svg?v=1707283412529"
/>
<meta property="og:url" content="https://www.op.gg/" />
```

## 트위터 카드

````html
<meta property="twitter:card" content="summary" />
<meta property="twitter:site" content="OPGG" />
<meta
  property="twitter:title"
  content="롤 전적 검색은 OP.GG - 챔피언 공략과 게임 전적, 라이엇 아이디 태그 검색"
/>
<meta
  property="twitter:description"
  content="챔피언 공략과 게임 전적, 라이엇 아이디 태그 검색"
/>
<meta
  property="twitter:image"
  content="https://s-lol-web.op.gg/images/icon/opgglogo.svg?v=1707283412529"
/>
<meta property="twitter:url" content="https://www.op.gg/" />

## Favicon

<img
  src="https://s-lol-web.op.gg/images/icon/opgglogo.svg?v=1707283412529"
  width="65"
  height="16"
  alt="OP.GG"
/>

## Header ```html
<div class="headerMenu">
  <div class="firstLine">
    <a class="logo" href="javascript:void(0)">
      <img
        src="https://s-lol-web.op.gg/images/icon/opgglogo.svg?v=1707283412529"
        width="65"
        height="16"
        alt="OP.GG"
      />
    </a>
    <nav>
      <ul>
        <li>
          <span>
            <img
              src="https://opgg-gnb.akamaized.net/static/images/icons/lol.svg?image=q_auto,f_webp,w_48,h_48&amp;v=1707283412529"
              width="24"
              height="24"
              alt="리그오브레전드"
            />
            <span>리그오브레전드</span>
          </span>
        </li>
        <li>
          <a href="javascript:void(0)" rel="noreferrer"
            ><img
              src="https://opgg-gnb.akamaized.net/static/images/icons/pal.svg?image=q_auto,f_webp,w_48,h_48&amp;v=1707283412529"
              width="24"
              height="24"
              alt="팰월드"
            />
            <span class="palWorld">B</span>
            <span>팰월드</span>
          </a>
        </li>
        <li>
          <a href="javascript:void(0)">
            <img
              src="https://opgg-gnb.akamaized.net/static/images/icons/dskapp.svg?image=q_auto,f_webp,w_48,h_48&amp;v=1707283412529"
              width="24"
              height="24"
              alt="데스크톱"
            />
            <span>데스크톱</span>
          </a>
        </li>
        <li>
          <a href="javascript:void(0)">
            <img
              src="https://opgg-gnb.akamaized.net/static/images/icons/tft.svg?image=q_auto,f_webp,w_48,h_48&amp;v=1707283412529"
              width="24"
              height="24"
              alt="전략적 팀 전투"
            />
            <span>전략적 팀 전투</span>
          </a>
        </li>
        <li>
          <a href="javascript:void(0)">
            <img
              src="https://opgg-gnb.akamaized.net/static/images/icons/val.svg?image=q_auto,f_webp,w_48,h_48&amp;v=1707283412529"
              width="24"
              height="24"
              alt="발로란트"
            />
            <span>발로란트</span>
          </a>
        </li>
        <li>
          <a href="javascript:void(0)"
            ><img
              src="https://opgg-gnb.akamaized.net/static/images/icons/pubg.svg?image=q_auto,f_webp,w_48,h_48&amp;v=1707283412529"
              width="24"
              height="24"
              alt="배틀그라운드"
            />
            <span>배틀그라운드</span>
          </a>
        </li>
        <li>
          <a href="javascript:void(0)">
            <img
              src="https://opgg-gnb.akamaized.net/static/images/icons/overwatch.svg?image=q_auto,f_webp,w_48,h_48&amp;v=1707283412529"
              width="24"
              height="24"
              alt="오버워치2"
            />
            <span>오버워치2</span>
          </a>
        </li>
        <li>
          <a href="javascript:void(0)">
            <img
              src="https://opgg-gnb.akamaized.net/static/images/icons/esports.svg?image=q_auto,f_webp,w_48,h_48&amp;v=1707283412529"
              width="24"
              height="24"
              alt="이스포츠"
            />
            <span>이스포츠</span>
          </a>
        </li>
        <li>
          <a href="javascript:void(0)">
            <img
              src="https://opgg-gnb.akamaized.net/static/images/icons/talk.svg?image=q_auto,f_webp,w_48,h_48&amp;v=1707283412529"
              width="24"
              height="24"
              alt="톡피지지"
            />
            <span>톡피지지</span>
          </a>
        </li>
        <li>
          <a href="javascript:void(0)">
            <img
              src="https://opgg-gnb.akamaized.net/static/images/icons/gigs.svg?image=q_auto,f_webp,w_48,h_48&amp;v=1707283412529"
              width="24"
              height="24"
              alt="Gigs"
            />
            <span class="palWorld">N</span>
            <span>Gigs</span>
          </a>
        </li>
        <li>
          <a href="javascript:void(0)">
            <img
              src="https://opgg-gnb.akamaized.net/static/images/icons/duo.svg?image=q_auto,f_webp,w_48,h_48&amp;v=1707283412529"
              width="24"
              height="24"
              alt="Duo"
            />
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
              <div class="urf">
                우르프
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
</div>
````

## Main

```html
<div class="main">
  <h1 class="hidden">OP.GG</h1>
  <div class="smallder">
    <img
      src="https://meta-static.op.gg/logo/image/8a600438ab0430d4094b6d4e6ecb3d84.png?image=q_auto,f_webp,w_auto,h_448&amp;v=1707283412529"
      height="224"
      alt="OP.GG logo (스몰더)"
      title="스몰더"
    />
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
            </select>
          </div>
          <div class="pickKr">
            <div>
              <button type="button" class="korea">
                <img
                  src="https://s-lol-web.op.gg/assets/images/regions/01-icon-icon-kr.svg?v=1707283412529"
                  width="24"
                  height="24"
                  alt="대한민국"
                />
                <span>korea</span>
              </button>
            </div>
          </div>
        </div>
        <div class="searchWrapper">
          <label for="searchHome" class="label">검색</label>
          <input
            id="searchHome"
            name="search"
            autocomplete="off"
            type="text"
            value
          />
          <label for="searchHome" class="searchPlaceholder">
            <span class="placeHolderHome">
              플레이어 이름
              <!--  -->
              +
            </span>
            <span class="placeHoderTag"> #KR1 </span>
          </label>
        </div>
        <button class="gg-btn" type="submit">.GG</button>
      </form>
    </div>
    <div class="middleSecond">
      <div class="middleSecondBanner"></div>
    </div>
  </div>
</div>
<div class="middleThird">
  <div class="middleThirdBanner">
    <span>프론트엔드 8기 화이팅!</span>
  </div>
</div>
<div class="middleTable">
  <section class="opggTalk">
    <h2><a href="javascript:void(0)">OP.GG Talk 인기글</a></h2>
  </section>
  <section class="playerTab"></section>
</div>
```

## Footer

```html
<footer>
  <footer>
    <div>
      <section style="display: flex;">
        <div class="footerLogo">
          <a href="javascript:void(0)">
            <img
              src="https://s-lol-web.op.gg/images/icon/icon-opgglogo-white.svg?v=1708507553015"
              width="99"
              height="24"
              alt="OP.GG"
              loading="lazy"
            />
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
          <a href="javascript:void(0)"
            >리그오브레전드
            <img
              src="https://s-lol-web.op.gg/images/icon/icon-game-white.svg?v=1708507553015"
              width="16"
              height="16"
              alt="리그오브레전드"
              class="game"
            />
          </a>
          <a href="javascript:void(0)"
            >팰월드
            <img
              src="https://s-lol-web.op.gg/images/icon/icon-game-white.svg?v=1708507553015"
              width="16"
              height="16"
              alt="팰월드"
              class="game"
          /></a>
          <a href="javascript:void(0)"
            >데스크톱
            <img
              src="https://s-lol-web.op.gg/images/icon/icon-game-white.svg?v=1708507553015"
              width="16"
              height="16"
              alt="데스크톱"
              class="game"
            />
          </a>
          <a href="javascript:void(0)"
            >전략적 팀 전투
            <img
              src="https://s-lol-web.op.gg/images/icon/icon-game-white.svg?v=1708507553015"
              width="16"
              height="16"
              alt="전략적 팀 전투"
              class="game"
            />
          </a>
          <a href="javascript:void(0)"
            >발로란트
            <img
              src="https://s-lol-web.op.gg/images/icon/icon-game-white.svg?v=1708507553015"
              width="16"
              height="16"
              alt="발로란트"
              class="game"
            />
          </a>
          <a href="javascript:void(0)"
            >배틀그라운드
            <img
              src="https://s-lol-web.op.gg/images/icon/icon-game-white.svg?v=1708507553015"
              width="16"
              height="16"
              alt="배틀그라운드"
              class="game"
            />
          </a>
          <a href="javascript:void(0)"
            >오버워치2
            <img
              src="https://s-lol-web.op.gg/images/icon/icon-game-white.svg?v=1708507553015"
              width="16"
              height="16"
              alt="오버워치2"
              class="game"
            />
          </a>
          <a href="javascript:void(0)"
            >이스포츠
            <img
              src="https://s-lol-web.op.gg/images/icon/icon-game-white.svg?v=1708507553015"
              width="16"
              height="16"
              alt="이스포츠"
              class="game"
            />
          </a>
          <a href="javascript:void(0)"
            >톡피지지
            <img
              src="https://s-lol-web.op.gg/images/icon/icon-game-white.svg?v=1708507553015"
              width="16"
              height="16"
              alt="톡피지지"
              class="game"
            />
          </a>
          <a href="javascript:void(0)"
            >Gigs
            <img
              src="https://s-lol-web.op.gg/images/icon/icon-game-white.svg?v=1708507553015"
              width="16"
              height="16"
              alt="Gigs"
              class="game"
            />
          </a>
          <a href="javascript:void(0)"
            >Duo
            <img
              src="https://s-lol-web.op.gg/images/icon/icon-game-white.svg?v=1708507553015"
              width="16"
              height="16"
              alt="Duo"
              class="game"
            />
          </a>
        </div>
        <div>
          <a class="aTitle" href="javascript:void(0)">Apps </a>
          <a href="javascript:void(0)"
            >OP.GG Android App
            <img
              src="https://s-lol-web.op.gg/images/icon/icon-game-white.svg?v=1708507553015"
              width="16"
              height="16"
              alt="OP.GG Android App"
              class="game"
            />
          </a>
          <a href="javascript:void(0)"
            >OP.GG iOS App
            <img
              src="https://s-lol-web.op.gg/images/icon/icon-game-white.svg?v=1708507553015"
              width="16"
              height="16"
              alt="OP.GG iOS App"
              class="game"
            />
          </a>
          <a href="javascript:void(0)"
            >TFT Android App
            <img
              src="https://s-lol-web.op.gg/images/icon/icon-game-white.svg?v=1708507553015"
              width="16"
              height="16"
              alt="TFT Android App"
              class="game"
            />
          </a>
          <a href="javascript:void(0)"
            >TFT iOS App
            <img
              src="https://s-lol-web.op.gg/images/icon/icon-game-white.svg?v=1708507553015"
              width="16"
              height="16"
              alt="Apps"
              class="game"
            />
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
              <span
                >서울특별시 강남구 테헤란로 507, 1층, 2층(삼성동,
                wework빌딩)</span
              >
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
            © 2012- 2024 OP.GG. OP.GG is not endorsed by Riot Games and does not
            reflect the views or opinions of Riot Games or anyone officially
            involved in producing or managing League of Legends. League of
            Legends and Riot Games are trademarks or registered trademarks of
            Riot Games, Inc. League of Legends © Riot Games, Inc.
          </p>
        </div>
        <nav class="sns">
          <a href="javascript:void(0)">
            <img
              src="https://s-lol-web.op.gg/images/icon/icon-logo-instagram.svg?v=1708507553015"
              width="24"
              height="24"
              alt="instagram account"
              loading="lazy"
            />
          </a>
          <a>
            <img
              src="https://s-lol-web.op.gg/images/icon/icon-logo-youtube.svg?v=1708507553015"
              width="24"
              height="24"
              alt="twitter account"
              loading="lazy"
            />
          </a>
          <a>
            <img
              src="https://s-lol-web.op.gg/images/icon/icon-logo-x.svg?v=1708507553015"
              width="24"
              height="24"
              alt="twitter account"
              loading="lazy"
            />
          </a>
          <a>
            <img
              src="https://s-lol-web.op.gg/images/icon/icon-logo-facebook.svg?v=1708507553015"
              width="24"
              height="24"
              alt="facebook account"
              loading="lazy"
            />
          </a>
        </nav>
      </section>
    </div>
  </footer>
</footer>
```
