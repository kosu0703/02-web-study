<%@ page language="java" contentType="text/html; charset=UTF-8"
	pageEncoding="UTF-8"%>
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<link rel="stylesheet" href="../css/header.css">
<link rel="stylesheet" href="../css/update.css">
<script defer src="../js/header.js"></script>

<script type="text/javascript">
	function update_go(f) {
		//	수정하기 누르면 비밀번호 검사 후
		//	맞으면 정보가지고 감
		f.action = "";
		f.submit();
	}
</script>

<title>회원정보수정 페이지</title>
</head>
<body>
	<header>
		<div class="inner">
			<div class="logo">
				<h1>
					<a href="#">로고</a>
				</h1>
			</div>

			<!-- 로그아웃 유틸 -->
			<div class="util logout_util">
				<ul class="info">
					<li><a href="#">로그인</a></li>
					<li><a href="#">회원가입</a></li>
					<li><a href="#">고객센터</a></li>
				</ul>
			</div>

			<form action="#" class="h_search_form" method="post">
				<input type="text" name="search" id="search" /> <input
					type="submit" value="검색" />
			</form>

			<!-- 로그인 유틸 -->
			<div class="util login_util">
				<ul class="info">
					<li>이름</li>
					<li>보유 포인트 :</li>
					<li><a href="#">로그아웃</a></li>
					<li><a href="#">마이페이지</a></li>
					<li><a href="#">장바구니</a></li>
					<li><a href="#">고객센터</a></li>
				</ul>
			</div>

			<div class="gnb_wrappr">
				<ul class="gnb">
					<li class="category"><a id="category1" data-category-id="1"
						href="#">카테고리1</a></li>
					<li class="category"><a id="category2" data-category-id="2"
						href="#">카테고리2</a></li>
					<li class="category"><a id="category3" data-category-id="3"
						href="#">카테고리3</a></li>
					<li class="category"><a id="category4" data-category-id="4"
						href="#">카테고리4</a></li>
					<li class="category"><a id="category5" data-category-id="5"
						href="#">카테고리5</a></li>
					<li class="category"><a id="category6" data-category-id="6"
						href="#">카테고리6</a></li>
				</ul>
			</div>
		</div>

		<div class="category_detail_wrapper">
			<div id="category_detail1" class="category_detail">
				<div class="c_details detail1"></div>
				<div class="c_details detail2"></div>
				<div class="c_details detail3"></div>
				<div class="c_details detail4"></div>
				<div class="c_details detail5"></div>
			</div>
		</div>
	</header>


	<section>
	
<!--===============================================================================  -->

		<div class="div">
			<br>
			<ul>
				<li><a href="#">주문목록</a></li>
				<li><a href="#">구매목록</a></li>
				<li><a href="#">찜목록</a></li>
				<li><a href="#">회원정보수정</a></li>
				<li><a href="#">회원탈퇴</a></li>
			</ul>
	
			<h2>회원정보수정</h2>	
			
			<div class="update">
			<form action="#" method="post">
				<fieldset>
					<legend>회원 정보</legend>
					<ul>
						<li>
							<label for="uname">이름 : </label>
							<input type="text" name="name" value="홍길동" required>
						</li>			
						<li>
							<label for="phone">연락처 : </label>
							<input type="text" name="phone" value="010-7777-9999" required>
						</li>		
						<li>
							<label for="mail">이메일 : </label>
							<input type="text" name="email" value="hong@naver.com" required>
						</li>	
						<li>
							<label for="birth">생년월일 : </label>
							<input type="text" name="birth" pattern="[0-9]{6}" value="930703">
											<!-- patten 은 숫자형식과 자릿수도 맞춰야 넘어간다. -->
						</li>
						<li> 	<!-- checked : 남자가 기본으로 선택되어 있도록 기본값 -->
							<label for="gender">성별 : </label>
							<input type="radio" name="gender" value="1" checked> 남자
							<input type="radio" name="gender" value="2"> 여자
							<!-- 남성이든 1이든 파라미터는 일단 문자열로 넘어간다. -->
						</li>		
						<li>
							<label for="addr">배송 주소 : </label>
							<input type="text" name="addr" value="회원가입시 받은 기본배송지 주소값" required>
						</li>			
						<li>
							<label for="pwd">비밀번호확인 : </label>
							<input type="password" name="pwd" required>
						</li>	
					</ul>
				</fieldset>
				<br>
				<input type="button" value="수정하기" onclick="update_go(this.form)">
				<input type="reset" value="취소">
			</form>
			</div>		
						
		</div>

<!--===============================================================================  -->

		<footer>
			<div class="footer_info">
				<h1>INFORMATION</h1>
				<br /> <a href="#">개인정보취급방침</a> <a href="#">이용약관</a> <a href="#">이메일수집거부</a>
				<a href="#">고객센터</a>
			</div>
			<hr />
			<div class="footer_cominfo">
				<h1>회사</h1>
				<br />
				<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cras
					laoreet arcu nec massa aliquam, at pharetra tellus ultricies.
					Vestibulum nec velit ante. Duis sed tortor elementum nisl luctus
					dapibus ut ut libero. Morbi vitae gravida nisi, eu mattis augue.
					Donec viverra vestibulum lorem eget lobortis. Praesent id odio in
					urna pulvinar varius. Vestibulum sollicitudin purus a velit
					posuere, nec congue sem sodales. Phasellus sed enim in urna
					hendrerit vestibulum. Etiam id eleifend tortor. Nulla lacinia lorem
					eget mi vehicula, vel fringilla nulla volutpat. Integer mi enim,
					sagittis eget dui nec, ullamcorper volutpat dolor.</p>
				<br />
				<p>저작권 ~~~</p>
			</div>
		</footer>
	</section>
</body>
</html>
