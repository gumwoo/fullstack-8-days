# fullstack-8-days

2024년 1월 6일

오늘의 학습일기: html+css

오늘도 코딩애플에서 강의를 수강하고 웹사이트를 만들어보았다. HTML과 CSS를 사용하여 기본 레이아웃을 구성했으며, 특히 CSS를 통해 다음과 같은 스타일링 포인트에 집중했다:

- 메인 배경 이미지 적용과 콘텐츠 배치
- 입력 필드와 버튼 디자인
- 추가 정보를 제공하는 박스 스타일링
- 폼 요소들의 정렬과 스타일링


```css
/* 기본 리셋 스타일 */
div {
    box-sizing: border-box;
}
body {
    margin: 0;
}
html {
    line-height: 1.15;
}

```css
/* 메인 배경 스타일 */
.main-background {
    height: 600px;
    background-image: url(shoes.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
    padding: 20px;
    position: relative;
}

```css
/* 메인 타이틀 스타일 */
.main-title {
    color: white;
    font-size: 40px;
    margin-top: 100px;
    text-align: center;
}

```css
/* 메인 콘텐츠 스타일 */
.main-content {
    color: white;
    text-align: center;
    font-size: 20px;
}

```css
/* 메인 버튼 스타일 */
.main-button {
    display: block;
    margin: auto;
    border-radius: 5px;
    padding: 5px;
    border: none;
    background: white;
    font-size: 15px;
    position: absolute;
    left: 0;
    right: 0;
    width: 75px;
}

```css
/* 추가 박스 스타일 */
.additional-box {
    background: #eee;
    position: relative;
    top: 280px;
    margin-top: -50px;
    width: 80%;
    display: block;
    margin-left: auto;
    margin-right: auto;
    height: 180px;
    max-width: 600px;
