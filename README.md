<html lang="en">
<head>
<meta charset="UTF-8">
<title>Animated Background</title>
<link rel="stylesheet" href="style.css">
<style>
*{
 m a r g i n :   0 ; 
 p a d d i n g :   0 ; 
 } 
 b o d y { 
     fo n t - f a m i l y :   B a l o o ; 
 } 
 . b a n n e r - t e x t { 
         w i d t h :   1 0 0 %; 
         p o s i t i o n :   absolute; 
 } 
 . b a n n e r - t e x t   u l { 
         h e i g h t :     5 0px; 
         float: right;
 } 
 . b a n n e r - t e x t   u l    li { 
         d i s p l a y :   i n l i n e - b lock; 
         p a d d i n g :   4 0 p x   1 5 p x ; 
         t e x t - t r a n s f o r m :   u p p e r c a s e ; 
         c o l o r :   white; 
         f o n t - s i z e :   2 0 p x ; 
 } 
.banner-text h2{
text-align: center;
color: Turquoise;
font-size: 50px;
margin-top: 20%;
}
.animation-area{
background: linear-gradient(to left , #8942a8, #ba382f);
width: 100%;
height: 100vh;
}
.box-area{
position: absolute;
top: 0;
left: 0;
width: 100%;
height: 100%;
overflow: hidden;
}
.box-area li{
position: absolute;
display:block ;
list-style: none;
width: 25px;
height: 25px;
background: rgba(255,255,255,0.2);
animation: animate 30s linear infinite;
bottom: -10px;
}
.box-area li:nth-child(1){
left: 86%;
width: 80px;
height: 80px;
animation-delay: 0s;
animation-duration: 6s
}
.box-area li:nth-child(2){
left: 16%;
width: 190px;
height: 190px;
animation-delay: 0.5s;
animation-duration: 3s;
}
.box-area li:nth-child(3){
left: 70%;
width: 100px;
height: 100px;
animation-delay: 0s;
animation-duration: 3s;
}
.box-area li:nth-child(4){
left: 42%;
width: 150px;
height: 150px;
animation-delay: 1s;
animation-duration: 5s;
}
.box-area li:nth-child(5){
left: 65%;
width: 120px;
height: 120px;
animation-delay: 1s;
animation-duration: 5s;
}

@keyframes animate{
   0%{
     transform: translateY(0) rotate(0deg);
     opacity: 1;
   }
100%{
   transform: translateY(-1500px) rotate(360deg);
     opacity: 0;
        }
}
</style>
</head>
<body>
    <div class="banner-text">
       <ul>
              <li>h</li>
              <li>e </li>
               <li>g </li>
               <li>g</li>
               <li>j</li>
               <li>k</li>
       </ul>
        <h2>HAPPY BIRTHDAY TAN!$HQ</h2>
</div>


 <div class="animation-area">
    <ul class="box-area">
             <li>IMG-20200329-WA0009</li>
              <li> IMG-20200329-WA0009 </li>
             <li>IMG-20200329-WA0009</li>
             <li>IMG-20200329-WA0009</li>
              <li>IMG-20200329-WA0009</li>  
</ul>
</div>
</body>
</html>
