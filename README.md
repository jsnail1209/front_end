html5, css, javascript 연습
21.12
![image](https://github.com/jsnail1209/front_end/assets/103093755/b7b73e71-03a3-4304-9f84-e61098c783dd)

자바스크립트[제이쿼리]
- 드롭다운 메뉴 구현
<img src = "https://github.com/jsnail1209/front_end/blob/main/jquery.gif" width="200" height="200">

```
<script src="http://ajax.googleapis.com/ajax/libs/jquery/1.10.2/jquery.min.js"></script>
<script>
    $(document).ready(function () {
        $('.outer-menu-item').hover(function () {
            $(this).find('.inner-menu').show();
        }, function () {
            $(this).find('.inner-menu').hide();
        });
    });
</script>
```

$(document).ready()
- 문서가 준비되면 매개변수로 넣은 콜백 함수 실행

콜백함수 function(){}
- 한 함수가 실행되고 난 후에, 실행하고 싶은 또 다른 명령을 삽입할 때 사용하는 함수

.hover()
- 선택한 요소에 마우스를 올리거나 선택한 요소에서 마우스가 벗어날 때 실행

.find()
어떤 요소의 하위 요소 중 특정 요소를 찾을 때 사용
$(this).find('.inner-menu')
> this의 하위 요소 중 .inner-menu를 선택




