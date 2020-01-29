# Sample portfolio

## reset 
- css reset

## bxSlider
```js
$(document).ready(function(){
    $('.slider').bxSlider({
        controls: false,
        pager: false,
        auto: true
    });
});
```
- controls
    - Next/Prev 버튼 default true
- pager    
- auto : 자동 슬라이드    

## fontawsome
- 글꼴, 아이콘 제공 library
- css의 text 속성에 영향을 받음

## 영역 
- 한 가운데 정렬
    - top: 50%; left:50%;
    - margin-left: -(콘텐츠 영역의 width / 2);
    - margin-top: -(콘텐츠 height / 2);