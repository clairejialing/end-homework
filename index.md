<!DOCTYPE html>
<head> 
        <meta charset="UTF-8">
        <title>Document</title>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>

<style>

.full-screen{
	position:fixed;
	top:0;
	left:0;
	width:100%;
	height:100%;
	background:hsla(120, 100%, 20%, 0.4);
	z-index:10;
	display:flex;
	justify-content:center;
	align-items:center;
}


p{
           color:lightpink;
           margin:5px;
           cursor:pointer;

}
p:hover{
           background:seashell;
}

h1{
           color:rosybrown;
          

}


.close{
 position: absolute;
 z-index:11;
 right: 25px;
 top: 25px;
 width: 50px;
 height: 50px; 
 background: silver;
 border-radius: 25px; 
 box-shadow: 2px 2px 5px 0px black;
 cursor: pointer;

}
.close:hover {
background: red;
}

.close:before {
 position: absolute;
 content: ''; 
 width: 30px;
 height: 10px; 
 background: white; 
 transform: rotate(45deg); 
 top: 20px; left: 10px;

}
.close:after{
 content: '';
 position: absolute;
 width: 30px;
 height: 10px;
 background: white; 
 transform: rotate(-45deg);
 top: 20px;
 left: 10px;
}

</style>
</head>

<body>
<h1>限時特惠買一送一</h1>
<p>優惠商品</p>



<div class="full-screen" align="center">
<img src="大苑子.jpg">
</div>


 





<div class="close">
</div>
<script>

$("p").click(function(){
 $(".full-screen").slideToggle();
});


$("p").click(function(){
 $(".close").slideToggle();
});


$(".close").click(function(){
 $(".full-screen").slideToggle();
});


$(".close").click(function(){
 $(".close").slideToggle();
});


</script>


</body>

<html lang="tw"><head> 
        <meta charset="UTF-8">
        <title>Document</title>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>

<style>

.full-screen{
	position:fixed;
	top:0;
	left:0;
	width:100%;
	height:100%;
	background:rgba(255,160,35,0.6);
	z-index:10;
	display:flex;
	justify-content:center;
	align-items:center;
}


p{
           color:lightpink;
           margin:5px;
           cursor:pointer;

}
p:hover{
           background:seashell;
}

h1{
           color:rosybrown;
          

}


.close{
 position: absolute;
 z-index:11;
 right: 25px;
 top: 25px;
 width: 50px;
 height: 50px; 
 background: silver;
 border-radius: 25px; 
 box-shadow: 2px 2px 5px 0px black;
 cursor: pointer;

}
.close:hover {
 background: red;
}

.close:before {
 position: absolute;
 content: ''; 
 width: 30px;
 height: 10px; 
 background: white; 
 transform: rotate(45deg); 
 top: 20px; left: 10px;

}
.close:after{
 content: '';
 position: absolute;
 width: 30px;
 height: 10px;
 background: white; 
 transform: rotate(-45deg);
 top: 20px;
 left: 10px;
}

</style>
</head>

<body>
<h1>可愛の卡娜赫拉小動物們</h1>
<p>卡納赫拉</p>



<div class="full-screen" align="center">
<img src="001.gif">
</div>


 





<div class="close">
</div>
<script>

$("p").click(function(){
 $(".full-screen").slideToggle();
});


$("p").click(function(){
 $(".close").slideToggle();
});


$(".close").click(function(){
 $(".full-screen").slideToggle();
});


$(".close").click(function(){
 $(".close").slideToggle();
});


</script>


</body>

</html>
