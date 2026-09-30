<!DOCTYPE html>
<html>
  <head>
    <title>내 첫 웹페이지</title>
  </head>
  <body>
    <h1>안녕하세요!</h1>
  </body>
</html>



<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <title>Flexbox 전후 비교</title>
    <style>
        /* 박스가 잘 보이도록 최소한의 꾸밈 */
        .container div {
            border: 1px solid;
            padding: 12px;
        }

        /* After: 부모에게 flex 지시 */
        .flex-container {
            display: flex;
            justify-content: center;
            gap: 12px;
        }
    </style>
</head>
<body>

    <h2>Before — Flexbox 없이 (기본값)</h2>

    <div class="container">
        <div>박스1</div>
        <div>박스2</div>
        <div>박스3</div>
    </div>

    <h2>After — Flexbox 적용</h2>

    <div class="container flex-container">
        <div>박스1</div>
        <div>박스2</div>
        <div>박스3</div>
    </div>

</body>
</html>
