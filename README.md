# project01
![Image alt text](로그인페이지.png)

<!DOCTYPE html>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

<html>
<head>
	<title>LIKE LION</title>
	<style>
		header {
            font-size: 25;
			padding: 10px;
            margin-top: 70px;
			background-color:black;
			color: #fff;
            margin-bottom: -20px;
		}
        body{
            background-color: black;
            color:#fff ;
            margin-left: 80px;
        }
		form {
            display: -webkit-inline-flex;
			align-items: center;
            justify-content: center;
            flex-direction: column;
            margin : 10 10px ;
            margin-top : -480px;
            margin-left : 730px;
		}
        .login-container {
            display: flex ;
            align-items: center;
            justify-content: center;
        }

        input[type="text"], input[type="password"], button {
            margin: 5px;
        }

		input[type="text"], input[type="password"], button {
			font-size: 14px;
			padding: 10px;
			border: none;
			margin: 0 5px;
		}
		input[type="text"], input[type="password"] {
			background-color: #eee;
			border-radius: 20px;
			width: 280px;
            font-style: italic;
		}
		button {
			background-color: orange;
			color: #fff;
			border-radius: 20px;
			cursor: pointer;
            width: 200px;
		}
    .div{
        justify-content: center;
        align-items: center;
        margin: 5px;
        background-color: white;
        color: black;
        width: 150px;
        height: 160px;
        border-radius: 5px;
        vertical-align: top;
        text-align: center;
        display: inline-block;
    }
    div > p{
        margin-top: 40px;
    }
    #t1 {
        margin-top: 70px;
   }
   #t2 {
        margin-top: 70px;
   }
   .input-icon {
    position: absolute;
    font-size:16px;
    margin-top: 13px;
    margin-left: -315px;
    color: gray;
    }
    input[type="text"], input[type="password"] {
    padding-left: 30px;
    }
  
	</style>
</head>
<body>
	<header>
		<img src="likelion.png" alt="Logo" style="width: 200px; height: 100px;">
        <br>
		<h1><em>LIKE LION </em></h1>
	</header>
	<main>
		<p>우리는 '성장 의지를 가진 사람들을 돕기 위해' 존재합니다. 그리고<br>
        이들을 돕기 위한 가장 근본적이고 효과적인 방법은 교육이라고 생<br>각합니다<br><br>
        지금 바로 지원하세요!</p>
        <div class="div">
            <p><em><b>Plan <br> & <br> Design</b></em></p>
        </div>
        <div class="div">
            <p id = "t1"><em><b>Frontend</b></em></p>
        </div>
        <div class="div">
            <p id = "t2"><em><b>backend</b></em></p>
        </div>
        <div class="login-container">
            <form>
              <h2><em>LOGIN</em></h2>
              <label>
                <input type="text" placeholder="ID" name="username" id="username">
                <i class="fa fa-user fa-lg input-icon" aria-hidden="true"></i>
              </label>
              <br>
              <label>
                <input type="password" placeholder="PW" name="password">
                <i class="fa fa-lock fa-lg input-icon" aria-hidden="true"></i>
              </label>
              <br>
              <button type="submit"><b> 로그인 후 지원하기</b> </button>
            </form>
          </div>
	</main>
</body>
</html>
