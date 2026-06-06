```html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Game Support Center</title>
<style>
body{
    background:#111;
    color:#ddd;
    font-family:Segoe UI,Arial,sans-serif;
    max-width:900px;
    margin:auto;
    padding:40px;
}
h1{
    color:white;
}
.box{
    border:1px solid #444;
    padding:20px;
    margin-top:20px;
}
.hidden{
    display:none;
    color:#ff5555;
}
</style>
</head>
<body>

<h1>Game Support Center</h1>

<div class="box">
<h2>Issue ID #4172</h2>

<p><b>Stop Code:</b> INTRUDER_FOUND</p>

<p>We detected an unexpected error while running the game.</p>

<p>Common causes:</p>
<ul>
<li>Corrupted save data</li>
<li>Memory allocation failure</li>
<li>Unknown</li>
</ul>

<p>Suggested fixes:</p>
<ul>
<li>Restart the game.</li>
<li>Verify game files.</li>
<li>Update to the latest version.</li>
</ul>

<hr>

<div id="m1" class="hidden">
Additional information received...
</div>

<div id="m2" class="hidden">
Source of error: UNKNOWN
</div>

<div id="m3" class="hidden">
Location of intrusion: Hidden Area #3
</div>

<div id="m4" class="hidden">
User activity recovered.
</div>

<div id="m5" class="hidden" style="font-size:28px">
How did you get here?
</div>

</div>

<script>

setTimeout(()=>{
document.getElementById("m1").style.display="block";
},10000);

setTimeout(()=>{
document.getElementById("m2").style.display="block";
},18000);

setTimeout(()=>{
document.getElementById("m3").style.display="block";
},26000);

setTimeout(()=>{
document.getElementById("m4").style.display="block";
},35000);

setTimeout(()=>{
document.getElementById("m5").style.display="block";
},45000);

</script>

</body>
</html>
```
