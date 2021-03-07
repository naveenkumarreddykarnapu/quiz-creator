# quiz-creator
Create Quiz using HTML
<!DOCTYPE html>
<html lang="en">
<head>
<title>Aptitude Test</title>
<script type = "text/javascript" >
function preventBack() { window.history.forward(); }
setTimeout("preventBack()", 0);
window.onunload = function () { null };

var randomlinks=new Array()

randomlinks[0]="D:/HTML/first.html"
randomlinks[1]="D:/HTML/second.html"
randomlinks[2]="D:/HTML/third.html"
randomlinks[3]="D:/HTML/fourth.html"
randomlinks[4]="D:/HTML/fifth.html"
randomlinks[5]="D:/HTML/sixth.html"
randomlinks[6]="D:/HTML/seventh.html"
randomlinks[7]="D:/HTML/eight.html"
randomlinks[8]="D:/HTML/ninth.html"
randomlinks[9]="D:/HTML/tenth.html"
function randomlink(){
window.location=randomlinks[Math.floor(Math.random()*randomlinks.length)]
}

</script>
</head>
<body>
<br>
<h2 style="color:olive green"><u>Aptitude Test:</u></h2>
<br>
<u style="color:green">Instructions:</u>
<ul>
	<li style="list-style-type:square;">Total number of questions:10.</li><br>
	<li style="list-style-type:square;">Each question carry 1 mark, no negative marks.</li><br>
	<li style="list-style-type:square;">DO NOT refresh the page.</li><br>
	<li style="list-style-type:square;">All the best :-)</li><br>
</ul>
<form method="post">
<p align="center"><input type="button"  name="B1" value="Start Test..."  onclick="randomlink()"></p> 
</form>
</body>
