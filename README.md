html5, css, javascript 연습
21.12
![image](https://github.com/jsnail1209/front_end/assets/103093755/b7b73e71-03a3-4304-9f84-e61098c783dd)

자바스크립트[제이쿼리]
- 내부 메뉴 표시
![녹음 2023-12-26 220747](https://github.com/jsnail1209/front_end/assets/103093755/6ba545e2-13be-4806-b411-c1603a3e1c44)
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
