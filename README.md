# number1
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width,initial-scale=1,maximum-scale=1" />
	<!--手機概念必須加上這行-->
	<title></title>
	<link href="style.css" rel="stylesheet" type="text/css" media="all"/>
	<style type="text/css">
	.head{
		height: 300px;
		background-color: #00ffff;	
		text-align:center;
		line-height: 300px;
		margin: 0px;
	}
	.img{
		width: 270px;
		height: 200px;
	}
	main{
	display: flex;
	justify-content: center;
	align-items: flex-start;
	flex-wrap:wrap;
}
main>.item{
	flex: none;
	width: 270px;margin: 10px;
	background-color: #ffcccc;
}
@media (max-width: 1200px){
	main>.item{
		width: 45%;
	}
}
@media(max-width: 600px){
	main>.item{
		width: 90%;
	}
}
	@media screen and (max-width: 600px){
		.content{
			width: 90%;
		}
	}
	/*上面那個是要弄出手機縮放大小*/
</style>
</head>
<body style="margin: 0px;">
<div style="font-size: 20px;font-weight: bold;">My Website<span style="position: absolute;right: 0px;">Item1  Item2  Item3  Item4</span></div>
<div  class="head" style="font-size: 40px;font-weight: bold;position:center;">Welcome to MyHome</div>
	<main>
		<div class="item" align="center" > <img src="1.jpg" width="270" height="200">
		炎柱</img></div>
		<div class="item" align="center" > <img src="2.jpg" width="270" height="200">
		水柱</img></div>
		<div class="item" align="center" > <img src="3.jpg" width="270" height="200">
		岩柱</img></div>
		<div class="item" align="center" > <img src="4.jpg" width="270" height="200">
		戀柱</img></div>
		<div class="item" align="center" > <img src="5.jpg" width="270" height="200">
		音柱</img></div>
		<div class="item" align="center" > <img src="6.jpg" width="270" height="200">
		蛇柱</img></div>
		<div class="item" align="center" > <img src="7.jpg" width="270" height="200">
		風住</img></div>
		<div class="item" align="center" > <img src="8.jpg" width="270" height="200">
		佐柱</img></div>
	</main>
</div>
</body>
</html>
