# islamic_-quiz_-game
It is a islamic game in this game offline people can play islamic quiz 
<!DOCTYPE html>
<html>
<head>
<title>Islamic Quiz - Quran & Seerat</title>
<style>
body {background: linear-gradient(135deg, #0F9D58, #00BFA5); font-family: sans-serif; color: white; text-align: center}
.card {background: white; color: #222; margin: 20px auto; padding: 20px; border-radius: 15px; max-width: 400px}
.btn {background: #FF6F00; color: white; padding: 12px; margin: 5px; border: none; border-radius: 8px; width: 90%}
</style>
</head>
<body>
<h1>🌙 Islamic Quiz</h1>
<div class="card">
  <h3 id="question">Quran me sabse pehli surah konsi hai?</h3>
  <button class="btn" onclick="check(1)">Al-Fatiha</button>
  <button class="btn" onclick="check(0)">Al-Baqarah</button>
  <button class="btn" onclick="check(0)">An-Naas</button>
  <p id="result"></p>
</div>
<script>
function check(ans){ 
  document.getElementById('result').innerText = ans ? 'Mashallah ✅ Sahi!' : 'Galat ❌ Koshish karo';
}
</script>
</body>
</html>

