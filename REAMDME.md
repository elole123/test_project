<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>LOL 메인화면</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
    <meta name="author" content="20231021">
    <meta name="keywords" content="computer">
    <base href="http://127.0.0.1:5500">
    <style>
        table {
            font-size: 20pt;
            color: white;
        }
    </style>
</head>
<body style="background-color:black;">
    <nav class="navbar navbar-expand-lg bg-body-tertiary" data-bs-theme="dark"> 
        <div class="container-fluid">
            <a class="navbar-brand" href="#">
                <img src="LOL.png" alt="Logo" width="90" height="84" class="d-inline-block align-text-top">
                Bootstrap
            </a>
            <a class="navbar-brand" href="#">Navbar</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                    <li class="nav-item">
                        <a class="nav-link active" aria-current="page" href="#">홈페이지</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Link</a>
                    </li>
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                            Dropdown
                        </a>
                        <ul class="dropdown-menu">
                            <li><a class="dropdown-item" href="#">외부사이트</a></li>
                            <li><a class="dropdown-item" href="#">Another action</a></li>
                            <li><hr class="dropdown-divider"></li>
                            <li><a class="dropdown-item" href="#">Something else here</a></li>
                        </ul>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link disabled" aria-disabled="true">Disabled</a>
                    </li>
                </ul>
                <form class="d-flex" role="search">
                    <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                    <button class="btn btn-outline-success" id="search_btn" type="submit">검색</button>
                </form>
                <a href="login/login.html" class="btn btn-outline-success" id="login_btn">로그인 하기</a>
            </div>
        </div>
    </nav>

    <div style="display: flex; justify-content: center;">
        <img src="image/LOL.png" width="200" height="60">
        <h3 style="font-size: 24px; font-weight: bold; font-style: italic; color: white;">
            <a href="https://www.leagueoflegends.com/ko-kr/how-to-play/" target="_blank">기본정보</a> 챔피언 패치 노트 새소식 등 (메뉴 정보 입력하기)
        </h3>
    </div>
    <div style="display: flex; justify-content: center;">
        <a href="index.html" target="_blank">
            <img src="image/MAIN.jpg" class="img-fluid" width="1200" height="768">
        </a>
    </div>
    <div style="display: flex; justify-content: center;">
        <table border="1">
            <caption>인기 캐릭터</caption>
            <tbody>
                <tr bgcolor="red">
                    <td width="80" rowspan="2">사이온</td>
                    <td>아리</td>
                    <td>가렌</td>
                    <td>가렌2</td>
                    <td>가렌3</td>
                </tr>
                <tr bgcolor="grey">
                    <td>아리</td>
                    <td>가렌</td>
                    <td>가렌1</td>
                    <td>가렌3</td>
                </tr>
                <tr> 
                    <td bgcolor="blue"><b>카직스</b></td>
                    <td>루시안</td>
                    <td>루시안2</td>
                    <td colspan="2"><font size="13">바이1</font></td>
                    <td><font size="13">바이2</font></td>
                </tr>
            </tbody>
        </table>
    </div>
</body>
</html>
