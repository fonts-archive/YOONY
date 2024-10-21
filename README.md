# 유니폰트

[배포처 바로가기](http://www.earlyfont.com/portfolio/EARLYFONT_YOONY)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `YOONY`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/YOONY/YOONY.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/YOONY/YOONY.css');
```

### CSS `@font-face`

```css
@font-face {
  font-family: 'YOONY';
  font-weight: normal;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/YOONY/YOONY.woff2') format('woff2'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/YOONY/YOONY.woff') format('woff'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/YOONY/YOONY.otf') format('opentype'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/YOONY/YOONY.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/YOONY/subsets/YOONY-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url("https://cdn.jsdelivr.net/gh/fonts-archive/YOONY/subsets/YOONY-dynamic-subset.css");
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.

```css
font-family: "YOONY", -apple-system, BlinkMacSystemFont, "Segoe UI",Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
모든 분야에 제한없이 
활용할 수 있습니다.

인쇄·출판
도서 잡지 및 정기간행물, 브로슈어, 카탈로그, 달력, 신문광고,
잡지광고, 오프라인 지면 광고, 제품 패키지, 명함, 포트폴리오

일반 문서
일반문서, 내부문서, 홍보문서, 프레젠테이션, 증서, 원서, 신고서,
무료 배포 공문 서식, 교재

영상
일반동영상, 배너 영상, 홍보 영상, 유튜브, CF, 영화, 뮤직비디오,
모든 영상

CI·BI
사명, 브랜드명, 상품명, 로고, 마크, 슬로건, 패키지디자인

웹사이트
웹 이미지, 웹 배너 광고, 이메일, 웹툰, 사내 사보,
카탈로그, 뉴스레터, 상세페이지, 홍보페이지

APP UI·이모티콘
게임UI, 앱UI, 소프트웨어UI, 이모티콘

상품제작·옥외광고
도장, 머그컵, 외류, 가방, 쇼핑백, 명찰, 마우스패드,
간판, 현수막, 시설 안내판, 벽면광고, 업장 내외 사인물

이러닝·이북
동영상 자료, 서적, 학습지, 교과서, 도서, 잡지, 브로슈어, 카탈로그
```
