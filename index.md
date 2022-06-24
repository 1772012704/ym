@@ -0,0 +1,201 @@
<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8" />
		<meta http-equiv="X-UA-Compatible" content="IE=edge" />
		<meta name="viewport" content="width=device-width, initial-scale=1.0" />
		<title></title>
		<link rel="stylesheet" href="./css/bootstrap.css" />
		<link rel="stylesheet" href="./css/bootstrap.css" />
		<link rel="stylesheet" href="./css/indext.css" />
		<!-- 站点图标 -->
		<link rel="shortcut icon" href="./img/logo.ico" type="image/x-icon">
	</head>
	<body>
		<!-- 头部分 -->
		<header id="header">
			<!-- 导航栏 -->
			<nav class="navbar navbar-inverse">
				<div class="container-fluid">
					<!-- Brand and toggle get grouped for better mobile display -->
					<div class="navbar-header">
						<button type="button" class="navbar-toggle collapsed" data-toggle="collapse"
							data-target="#bs-example-navbar-collapse-1" aria-expanded="false">
							<span class="sr-only">Toggle navigation</span>
							<span class="icon-bar"></span>
							<span class="icon-bar"></span>
							<span class="icon-bar"></span>
						</button>
						<a class="navbar-brand" href="#">首页</a>
					</div>

					<!-- Collect the nav links, forms, and other content for toggling -->
					<div class="collapse navbar-collapse" id="bs-example-navbar-collapse-1">
						<ul class="nav navbar-nav">

							<li class="dropdown">
								<!-- 下拉按钮1 -->
								<a href="#" class="dropdown-toggle" data-toggle="dropdown" role="button"
									aria-haspopup="true" aria-expanded="false">放松一下 <span class="caret"></span></a>
								<ul class="dropdown-menu">
									<button type="button" class="list-group-item"><a href="music.html">music</a></button>
									<button type="button" class="list-group-item">video</button>
									<button type="button" class="list-group-item">cos</button>


								</ul>

							</li>
							<!-- 下拉按钮2 -->
							<li class="dropdown">
								<a href="#" class="dropdown-toggle" data-toggle="dropdown" role="button"
									aria-haspopup="true" aria-expanded="false">商城<span class="caret"></span></a>
								<ul class="dropdown-menu">

									<button type="button" class="list-group-item">jk服装</button>
									<button type="button" class="list-group-item">cos服装</button>
									<button type="button" class="list-group-item">cos道具</button>
									<button type="button" class="list-group-item">Lolita服装</button>

								</ul>
							</li>
							<li><a href="#">社区</a></li>
							<li><a href="#">关于我们</a></li>
							<li><a href="#">活动预约</a></li>
							<li><a href="#"></a></li>
							<li><a href="#"></a></li>
							<li><a href="#"></a></li>
							<li><a href="#"></a></li>
						</ul>
						<form class="navbar-form navbar-left">
							<div class="form-group">
								<input type="text" class="form-control" placeholder="云信息">
							</div>
							<button type="submit" class="btn btn-default">Cloud一下</button>
						</form>
						<ul class="nav navbar-nav navbar-right">
							<li><a href="#">注册</a></li>
							<li><a href="#"></a></li>
							<li class="dropdown">
								<a href="#" class="dropdown-toggle" data-toggle="dropdown" role="button"
									aria-haspopup="true" aria-expanded="false">登录<span class="caret"></span></a>

								<ul class="dropdown-menu">
									<li><a href="#">个人中心</a></li>
									<li class="list-group-item">
										<span class="badge">14</span>
										我的关注
									</li>
									<li class="list-group-item">
										<span class="badge">14</span>
										私信
									</li>
									<li><a href="#">退出</a></li>
								</ul>
							</li>
							<li><a href="#"></a></li>
							<li><a href="#"></a></li>
							<li><a href="#"></a></li>
							<li><a href="#"></a></li>
						</ul>
					</div><!-- /.navbar-collapse -->
				</div><!-- /.container-fluid -->
			</nav>
		</header>

		<!-- 体部分 -->

		<tbody>
			<div class="col-lg-9">
				<!-- 轮播图 -->
				<div id="carousel-example-generic" class="carousel slide" data-ride="carousel">
					<!-- Indicators -->
					<ol class="carousel-indicators">
						<li data-target="#carousel-example-generic" data-slide-to="0" class="active"></li>
						<li data-target="#carousel-example-generic" data-slide-to="1"></li>
						<li data-target="#carousel-example-generic" data-slide-to="2"></li>
						<li data-target="#carousel-example-generic" data-slide-to="3"></li>
						<li data-target="#carousel-example-generic" data-slide-to="4"></li>
					</ol>

					<!-- Wrapper for slides -->
					<div class="carousel-inner" role="listbox">
						<div class="item active">
							<img src="./img/yunjin.png" alt="...">
							<div class="carousel-caption">
							</div>
						</div>
						<div class="item">
							<img src="./img/ganyu.png" alt="...">
							<div class="carousel-caption">
							</div>
						</div>
						<div class="item">
							<img src="./img/wendi.png" alt="Third slide">
							<div class="carousel-caption">
							</div>
						</div>
						<div class="item">
							<img src="./img/xioagong.png" alt="Third slide">
							<div class="carousel-caption">
							</div>
						</div>
						<div class="item">
							<img src="./img/hutao.png" alt="Third slide">
							<div class="carousel-caption">
							</div>
						</div>

					</div>

					<!-- Controls -->
					<a class="left carousel-control" href="#carousel-example-generic" role="button" data-slide="prev">
						<span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
						<span class="sr-only">Previous</span>
					</a>
					<a class="right carousel-control" href="#carousel-example-generic" role="button" data-slide="next">
						<span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
						<span class="sr-only">Next</span>
					</a>
				</div>
				<!-- 轮播图结束 -->

				<!-- 表格开始 -->
				<table class="table">
					<h3 class="text-center">最热cos</h3>
					<tr>
						<td><img class="img-responsive center-block" src="./img/imgs/0.jpg"></td>
						<td><img class="img-responsive center-block" src="./img/imgs/2.jpg"></td>
						<td><img class="img-responsive center-block" src="./img/imgs/3.jpg"></td>
						<td><img class="img-responsive center-block" src="./img/imgs/4.jpg"></td>
						<td><img class="img-responsive center-block" src="./img/imgs/7.jpg"></td>

					</tr>
					<tr>


					</tr>
				</table>
				<!-- 表格结束 -->
			</div>
			<!-- 宣传图部分 -->
			<div class="col-lg-3">
				<img style="width: 100%; height: 30%;" src="./img/竖版海报宣传.jpg" alt="..." class="img-rounded ">
			</div>
		</tbody>



		<!-- 脚部分 -->
		<footer id="footer">
			<div class="col-lg-12">


			</div>
		</footer>
		<script src="js/jquer.js"></script>
		<script src="js/bootstrap.js"></script>
		<script src="js/indext.js"></script>

	</body>
</html>
