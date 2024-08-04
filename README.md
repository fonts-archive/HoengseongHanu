# 횡성한우체

[배포처 바로가기](https://gongu.copyright.or.kr/gongu/wrt/wrt/view.do?wrtSn=13302264&menuNo=200023)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `Hoengseong Hanu`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/HoengseongHanu/HoengseongHanu.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/HoengseongHanu/HoengseongHanu.css');
```

### CSS `@font-face`

```css
@font-face {
    font-family: 'Hoengseong Hanu';
    font-weight: normal;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/HoengseongHanu/HoengseongHanu.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/HoengseongHanu/HoengseongHanu.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/HoengseongHanu/HoengseongHanu.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/HoengseongHanu/HoengseongHanu.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/HoengseongHanu/subsets/HoengseongHanu-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/HoengseongHanu/subsets/HoengseongHanu-dynamic-subset.css');
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.


```css
font-family: "Hoengseong Hanu", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
횡성군 전용서체 개발 배경 
횡성군 전용서체는 지역 대표 명품인 ‘횡성한우’ 뿔을 모티브로 하여 단단하고 강한 횡성의 이미지를 담고 있습니다. 
‘횡성한우체’는 횡성을 널리 알리고, 횡성군민 나아가 대한민국 국민이 모두 함께 쓸 수 있도록 제작했습니다. 
 
횡성한우체 저작권 
누구나 무료로 다운로드 받아 사용할 수 있습니다. 
영상, 인쇄물, 인터넷, 모바일 등 다양한 매체에 자유롭게 사용 가능합니다. 
 
횡성한우체 구성 
횡성한우체는 한글 2,780자, 영문 94자, 약물 986자로 구성되어 있습니다. 
볼드체로 구성되어 있으며, 타이틀, 패키지 등에 사용하기 좋습니다.
```
