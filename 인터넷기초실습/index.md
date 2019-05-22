<!DOCTYPE html>

<html>
<head>
  <meta charset="utf-8">
  <title>알쓸신멍</title>
  <style>
    body{
      position: absolute;
    }
    header ul{
      margin: 0px 50px;
      padding: 0px;
      width: 1800px;
    }
    ul img {
      margin: 20px 110px;
      float: left;
    }
    header ul li{
      font: normal bold 30px 맑은 고딕;
      display: inline-block;
      list-style-type: none;
      padding: 38px 5px;
      margin: 0px 140px 0px -60px;
    }
    a{
      text-decoration: none;
      color: black;
    }
    a:hover{
      color: #F78181;
    }
    input{
      padding: 0px 110px;
      margin: 80px 0px 0px -40px;
      width: 20px;
      height: 40px;
      border: 3px solid pink;
    }
    button{
      margin: 0px 0px 0px -6px;
      padding: 13px 0px 33px 0px;
      width: 70px;
      height: 0px;
      border: 0px;
      background: pink;
      font: normal bold 14px 맑은 고딕;
    }
    .sidemenu{
      font: 20px 맑은 고딕;
      padding: 0px;
      margin: 0px 80px 0px -60px;
    }
    header div {
      padding: 0px 280px;
    }
    section h1{
      font: normal bold 30px 맑은 고딕;
      background-color: rgb(246, 206, 206, 0.5);
      margin: 0px 280px;
    }
    section div .img_list{
      float: left;
      padding: 0px 0px 0px 172px;
      margin: 0px -70px 0px 0px;
      list-style-type: none;
    }
    section .text{
      clear: left;
      font: normal bold 15px 맑은 고딕;
      display: inline-block;
      padding: 0px 500px 200px 0px;
      list-style-type: none;
    }
    ul div{
      font: normal 17px 맑은 고딕;
    }
    footer img{
      padding: 0px 890px 45px 890px;
    }
    footer div{
      text-align: center;
      font: normal 15px 맑은 고딕;
      background-color: rgb(246, 206, 206, 0.5);
      height: 65px;
      padding: 40px 0px;
    }
  </style>
</head>

<body>
  <header>
    <ul>
      <a href="#"><img src="images/main_logo.png" width="150px" height="150px" alt="알쓸신멍 로고"></a>
      <li><a href="#">정보</a></li>
      <li>커뮤니티</li>
      <li>마이페이지</li>
      <li>고객센터</li>
      <li class="sidemenu"><a href="#">LOGIN</a></li>
      <li class="sidemenu">|</li>
      <li class="sidemenu"><a href="#">JOIN</a></li>
      <input type="text">
        <button> 검색 </button>
    </ul>
    <div>
      <img src="images/main_img.jpg" alt="메인 이미지">
    </div><br>
  </header>

  <hr><br>

  <section>
    <h1>| 추천 게시글 |</h1><br>
    <div>
      <ul class="img_list">
        <li><img src="images/post1.jpg" alt="게시글1"></li>
        <li><img src="images/post2.jpg" alt="게시글2"></li>
        <li><img src="images/post3.jpg" alt="게시글3"></li>
        <li><img src="images/post4.jpg" alt="게시글4"></li>
      </ul>
    </div>
    <div>
      <ul>
        <li class="text"><h2>> 혈액형으로 알아보는 나와 찰떡궁합인 댕댕이는?</h2>
        <div>여러분은 무슨형인가요?<br>
             혈액형별 나와 맞는 견종 궁합에 대해 알려드려요!</div></li>
        <li class="text"><h2>> 우리 강아지의 치아관리, 이제는 간식으로 해결하자!</h2>
        <div>매번 양치하기 싫어서 날뛰는 우리 강아지 달래느라 고생이 많으신 견주님들!<br>
             이제는 치아관리 해주는 간식으로 나도 강아지도 평화의 양치시간을 보내요~</div></li>
        <li class="text"><h2>> 펫샵? 입양? 입양!</h2>
        <div>매년마다 수천마리의 유기견들이 생기는 사실을 알고계신가요?<br>
             이제는 펫샵이 아니라 우리의 손길이 필요한 아이들입니다.</div></li>
        <li class="text"><h2>> 반려견을 맞아들일 준비 되셨나요?</h2>
        <div>강아지를 키우려고 하는 당신, 당신과 가족들은 맞아들일 준비가 되셨나요?<br>
             반려견을 키우기 위한 견주의 준비 과정과 고려사항을 알려드립니다!</div></li>
      </ul>
    </div>
  </section>

  <hr><br><br>

  <footer>
    <img src="images/under_logo.jpg" width="250px" height="250px">
    <div>
      <b>주소</b> : 서울특별시 구로구 경인로 445 동양미래대학교 3호관 314호<br>
      <b>대표</b> : 이수빈 ㅣ <b>개인정보보호책임자</b> : 이수빈 ㅣ <b>이메일</b> : suu_6393@naver.com<br>
      <b>사업자등록번호</b> : 201-81-830 ㅣ <b>전화</b> : 010-4981-6939 ㅣ <b>휴대전화</b> : 010-4981-6939
    </div>
  </footer>

</body>

</html>
