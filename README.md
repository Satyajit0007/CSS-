
<!DOCTYPE html>
<html>
<head><title></title>
<style>
*{
   margin:0;
   padding:0;
}
.mainMarioBg{
       width: 100%;
       height:100vh;
       background-image:url('field_flowers_fence.png');
       background-size: 100% 100%;
       position: relative;
}
.mario img{
    position: absolute;
    bottom:10px;
    animation-name: mariorun;
    animation-duration: 6s;
    animation-iteration-count: 10000;
    animation-timing-function: linear;
}
@keyframes mariorun{
	0%{left:0%;}
	100%{left:79%;}
}
h2{
	color:violet;
	text-transform:uppercase;
	font-size:2em;
	font-family: 'Bangers', cursive;
	letter-spacing: 2px;
	position: absolute;
	left: 45%;
	top: 20%;
	animation: mariotext 4s linear;
	animation-iteration-count: 10000;
	animation-delay:1s;
	
	

}
@keyframes mariotext{
	0%{font-size: 2em;}
	100%{font-size: 4em; left:40%;}
}
</style>


 </head>
<body>
<div class="mainMarioBg">
    <div class="mario">
           <img src="C:\Users\Satyajit\Desktop\html\loading_mario.gif" width="350px">
           <h2> run mario run</h2>
    </div>
</div>




</body>
</html>
