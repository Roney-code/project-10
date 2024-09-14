

<!DOCTYPE html>
<html>
<head>
<style>
div{
  width:100px;
  height:100px;
  background:green;
  position: relative;
  animation:mymove 5s infinite;
}
@keyframes mymove {
   0%   {top:0px; left:0px; background:green; width:100px;}
  25%  {top: 0px;left:100px; background:blue; width:300px;}
  50% {top: 100px;left:100px; background:yellow; width:300px;}
  75% {top: 100px;left:0px; background:red; width:300px;}
 100%  {top: 0px;left:0px; background:black; width:300px;}
}
 </style>
</head>
</body>
<h1> my first animination </h1>
<div></div>
</body>
</html>
