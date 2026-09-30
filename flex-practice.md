<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <title>박스 색 입히기</title>
    <style>
        /* 박스 공통 모양 */
        .container > div {
            padding: 30px;
            border-radius: 8px;
            margin-bottom: 14px;
            color: #ffffff;
        }

        /* 박스별 색 */
        .container > div:nth-child(1) {
            background-color: #14aecd;
        }

        .container > div:nth-child(2) {
            background-color: #0e7490;
        }

        .container > div:nth-child(3) {
            background-color: #101f35;
        }
    </style>
</head>
<body>

    <div class="container">
        <div>박스1</div>
        <div>박스2</div>
        <div>박스3</div>
    </div>

</body>
</html>



https://drive.google.com/file/d/19Wip9snpwq-JvvItk1LLK5FYn87VULKq/view?usp=sharing


<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <title>박스 색 입히기 - Flexbox</title>
    <style>
        /* CSS: 부모에게 flex 지시 */
        .container {
            display: flex;
            justify-content: center;
            gap: 12px;
        }

        /* 박스 공통 모양 */
        .container > div {
            padding: 30px;
            border-radius: 8px;
            color: #ffffff;
        }

        /* 박스별 색 */
        .container > div:nth-child(1) {
            background-color: #14aecd;
        }

        .container > div:nth-child(2) {
            background-color: #0e7490;
        }

        .container > div:nth-child(3) {
            background-color: #101f35;
        }
    </style>
</head>
<body>

    <div class="container">
        <div>박스1</div>
        <div>박스2</div>
        <div>박스3</div>
    </div>

</body>
</html>

https://drive.google.com/file/d/192PHs5EJWznSqVdjKV-4G6bTvxiOKtOM/view?usp=sharing
