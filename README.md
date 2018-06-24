# search.html

<html>
	<head>
		<meta charset="utf-8">
		<title>関連本検索サービス</title>
		<link rel="stylesheet" href="style.css">
		<script src="script.js"></script>
		<link rel="stylesheet" href="fontawesome-free-5.1.0-web/css/all.css">
	</head>
	<body>
		<div class="head">
			<div class="header-left">
				<a class="title" href="https://www.amazon.co.jp/?tag=hydraamazonav-22&hvadid=247739078780&hvpos=1t1&hvnetw=g&hvrand=13246387327890836074&hvpone=&hvptwo=&hvqmt=e&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=1009343&hvtargid=kwd-893523692&ref=pd_sl_8eaqjij3p0_e">関連本検索サービス<span class="fas fa-book-open"></span></a>
			</div>
			<div class="header-right">
				<span class="fas fa-list"></span>
			</div>
		</div>
		<div class="body">
			<form action="file_form.php" method="post">
				<div class="container">
					<div class="bookname">
						<label>書籍名　</label>
						<input type="text" name="search">
					</div>
					<!--<div class="bookcost">
						<label>金額　</label>
						<input type="text" name="search">
						　円　～　
						<input type="text" name="search">
						　円
					</div>-->

					<div class="btn">
						<input class="btn" type="button" value="検索">
					</div>
				</div>
			</form>
		</div>
		<div class="foot">
			<div class="footer-left">
				<a href="https://www.u-tokyo.ac.jp/index_j.html">
					<img  class="logo" width="170" height="50" src="utokyo.png">
				</a>
			</div>
			<div class="clear">

			</div>
		</div>
	</body>
</html>
