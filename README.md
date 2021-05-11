
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>로그인창 만들기</title>

    <link rel="shortcut icon" href="https://www.dwclonch.com/wp-content/uploads/2017/12/favicon.png">

    <meta property="og:image"
        content="https://1.gall-img.com/tdgall/files/attach/images/82/801/161/070/b01d2d105e7a4e65ce4da63c6ed9d7c3.jpg">
    <meta property="og:title" content="수연이의 로그인창">
    <meta property="og:description" content="엘사랑 로그인 할래?">
    <script src="https://s3.ap-northeast-2.amazonaws.com/materials.spartacodingclub.kr/xmas/snow.js"></script>

    <style>
        .WRAP {
            width: 200px;
            margin: auto;
        }

        .MAIN_IMAGE {
            background-image: url(https://1.gall-img.com/tdgall/files/attach/images/82/801/161/070/b01d2d105e7a4e65ce4da63c6ed9d7c3.jpg);
            background-size: cover;
            background-position: top;
            width: 200px;
            height: 200px;
            border-radius: 400PX;
        }

        .MYBUTTON {
            width: 200PX;
            height: 25PX;
            background-color: steelblue;

        }


        body {
            background-color: skyblue;
        }

        .TEXT {
            width: 200PX;
        }

    </style>

    <script> function MYBUTTON()
        {
            alert('사실 로그인이 안되어서 미안합니다');
      
        }
</script>
</head>

<body>
    <DIV CLASS="WRAP">
       
        <DIV CLASS="MAIN_IMAGE"> </DIV>
        <p>ID <input class="TEXT"></input></p>
        <p>PW <input class="TEXT"></input></p>
        <P><button CLASS="MYBUTTON" onclick="MYBUTTON()">START LOGIN</button></P>
       
    </DIV>
</body>

</html>
