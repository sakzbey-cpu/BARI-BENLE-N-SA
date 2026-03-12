# BARI-BENLE-N-SA
LÜTFEN KÜSLÜK BİZE YAKIŞMIYOR AQ
<!DOCTYPE html>
<html lang="tr">
<head>
<meta charset="UTF-8">
<title>Benimle Barışır mısın?</title>

<style>
body{
    font-family: Arial;
    text-align:center;
    background:#ffeef2;
    margin-top:100px;
}

h1{
    font-size:40px;
}

button{
    padding:15px 30px;
    font-size:20px;
    border:none;
    border-radius:12px;
    cursor:pointer;
    margin:10px;
}

#yes{
    background:#4CAF50;
    color:white;
    transition:0.3s;
}

#no{
    background:#ff4d4d;
    color:white;
}

#cats{
    display:none;
    margin-top:30px;
}

img{
    width:200px;
    margin:10px;
    border-radius:10px;
}
</style>
</head>

<body>

<h1>Benimle barışır mısın? 🥺</h1>

<button id="yes">Evet</button>
<button id="no">Hayır</button>

<div id="cats">
<h2>Yaşasın! 💖</h2>

<img src="https://media.giphy.com/media/MDJ9IbxxvDUQM/giphy.gif">
<img src="https://media.giphy.com/media/3oriO0OEd9QIDdllqo/giphy.gif">
<img src="https://media.giphy.com/media/JIX9t2j0ZTN9S/giphy.gif">
<img src="https://media.giphy.com/media/mlvseq9yvZhba/giphy.gif">

</div>

<script>

let yesSize = 1;

document.getElementById("no").onclick = function(){
    yesSize += 0.3;
    document.getElementById("yes").style.transform = "scale("+yesSize+")";
}

document.getElementById("yes").onclick = function(){
    document.getElementById("cats").style.display = "block";
}

</script>

</body>
</html>
