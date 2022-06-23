# Frontend Mentor - Profile card component solution

이 솔루션은 다음 챌린지의 참여 결과물입니다.
[Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ).

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

- Frontend Mentor에서 제공하는 챌린지 첫 번째 참여이다.

### Screenshot

url(./screenshot.jpg)

### Links

- Solution URL: [Add solution URL here](https://github.com/juurom/Profilecard___frontendMentor)
- Live Site URL: [Add live site URL here](https://juurom.github.io/Profilecard___frontendMentor/)

## My process

### Built with

- HTML 5
- CSS


### What I learned

1. 다운받은 TTF 폰트 추가 방법 : @font-face
```css
@font-face {
    font-family: 'NanumSquare';
     src: url("./NanumSquareR.ttf") format("truetype");
}
```

2. 가운데 정렬 방법 : left 50% top 50% 후 재정렬
```css
.card{
    position: absolute;
    left: 50%;
    top: 50%;
    margin-left:-150px;
    margin-top:-200px;
}
```

3. div 안의 div 가리키기 : div>div / 나란히 정렬: display:inline-box;
```css
.name{
    text-align: center;
}

.name>.myname{ /*div name 안의 div myname*/
    display:inline-block; /*div myage와 나란히*/
    margin-top: 50px;
    font-size: 20px;
    font-weight: 1000;
}
```
*참고: [The Markdown Guide](https://www.markdownguide.org/)

### Continued development

css 활용 방법을 어느 정도 익혔다고 생각했는데 안 쓰니까 까먹는 것 같다.
기본적인 div 정렬 방법, css class 호출 방법 등 가장 기초적인 스킬을 다시 다질 수 있었다.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [눈누](https://noonnu.cc/) - 상업 폰트 사이트.
- [WebGradients](https://webgradients.com/) - css 그라디언트 사이트.
- [Git bash 사용법](https://shxrecord.tistory.com/179) - Github repository에 commit하는 방법. 아직 손에 안 익은 것 같다.

## Author

- Website - [Juurom](https://github.com/juurom)
- Frontend Mentor - [@juurom](https://www.frontendmentor.io/profile/juurom)
- velog - [@juurom](https://velog.io/@juurom)

## Acknowledgments

방학 기간동안 스킬 많이 쌓아야지!
