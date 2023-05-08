<!DOCTYPE html>
<html lang="ko">
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <title> window6 회원가입 페이지 </title>
        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.2/css/bootstrap.min.css">
        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.2/css/bootstrap-theme.min.css">
        <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.2/js/bootstrap.min.js"></script>
    <style>
        ul{
            background-color:  #99ccff;
        }
        
    </style>

    </head>

    <body>
    
    <ul class="nav nav-pills" >
        <li role="presentation"><a href="https://minnnjiii.github.io/windowsix6/"> 로그인</a></li>
        <li role="presentation"><a href="https://minnnjiii.github.io/windowsix/"> 회원가입 </a></li>
        <li role="presentation"><a href="#"> 마이페이지 </a></li>
      </ul>
    <br> <!--줄바꿈-->
    <br>
    <br>

    <form class="form-inline"> <!-- 아이디 입력 칸 -->
        <div class = "form-group">
            <label for="exampleInputName2">아이디&nbsp&nbsp&nbsp&nbsp</label>
            <input type="text" class="form-control" id="exampleInputName2" placeholder="아이디를 입력하세요." >
        </div>
        <br>
        <br>
        <div class="form-group"> <!-- 비밀번호 입력 칸 -->
            <label for="exampleInputEmail2">비밀번호</label>
            <input type="password" class="form-control" id="exampleInputPassword1" placeholder="비밀번호를 입력하세요.">
        </div>
        <br>
        <br>
        <div> <!-- 이름 입력 칸 -->
            <label for="exampleInputName2">이름&nbsp&nbsp&nbsp&nbsp&nbsp</label>
            <input type="text" class="form-control" id="exampleInputName2" placeholder="이름을 입력하세요." >
        </div>
        <br>
        <label> 성별&nbsp&nbsp&nbsp </label>
        <select class="form-control">  <!-- 성별 입력 칸 -->
            <option> 여자 </option>
            <option> 남자 </option>
          </select>
        <br>
        <br>
        <br>

        <!--<button type="submit" class="btn btn-default">로그인</button>-->
        <a href = "https://minnnjiii.github.io/windowsix6/" class = "btn btn-success" onclick = "alert('회원가입이 완료되었습니다. ')">가입하기</a>
    </form>
    
    </body>
</html>
