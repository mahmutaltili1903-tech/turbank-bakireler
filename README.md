index.html
<!DOCTYPE html>
<html lang="tr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Türbanlı Bakireler</title>
<style>
body{
  margin:0;
  font-family:Arial,Helvetica,sans-serif;
  background:linear-gradient(135deg,#1e3c72,#2a5298);
  min-height:100vh;
  display:flex;
  align-items:center;
  justify-content:center;
  color:#333;
}
.card{
  background:#fff;
  border-radius:20px;
  padding:35px 25px;
  max-width:720px;
  width:92%;
  box-shadow:0 20px 40px rgba(0,0,0,.25);
  text-align:center;
}
h1{margin-top:0}
.subtitle{color:#666;margin-bottom:25px}
button{
  padding:14px 30px;
  border:none;
  border-radius:30px;
  background:#e91e63;
  color:#fff;
  font-size:16px;
  cursor:pointer;
}
button:hover{background:#c2185b}
.list{display:none;margin-top:30px;text-align:left}
.member{
  border-bottom:1px dashed #ddd;
  padding-bottom:15px;
  margin-bottom:18px;
}
.member h3{margin:0 0 6px}
</style>
</head>
<body>

<div class="card">
  <h1>Türbanlı Bakireler</h1>
  <div class="subtitle">Gizli haneye girmek için tıklayın</div>

  <button onclick="openList()">Giriş Yap</button>

  <div class="list" id="list">

    <div class="member">
      <h3>Mahmut Altılı (Hoca)</h3>
      <p>
        Arkadaş grubunun en zor çözüleni.<br>
        En zekisi.<br>
        Herkes onu çözmeye çalışır, çoğu kıskanır.
      </p>
    </div>

    <div class="member">
      <h3>Turgay Tekgöl (Renkli Ruh)</h3>
      <p>
        Grubun enerjisi hiç bitmez.<br>
        Muhabbeti bol, tarzı kendine özeldir.<br>
        Gözlükleriyle her ortamda fark edilir.
      </p>
    </div>

    <div class="member">
      <h3>Muhammed Şentürk (Kaos Ustası)</h3>
      <p>
        Grubun en şamatacısı.<br>
        PUBG tutkunu.<br>
        Ne yapacağı hiç belli olmaz.
      </p>
    </div>

    <div class="member">
      <h3>Burak Ceylan (Mangal Bakanı)</h3>
      <p>
        Grubun tek arabası olanı.<br>
        Sürekli mangal planı yapar.<br>
        Planlar genelde plan olarak kalır.
      </p>
    </div>

    <div class="member">
      <h3>Samet Altılı (İmam Adayı)</h3>
      <p>
        Grubun en küçüğü.<br>
        Liseye gidiyor.<br>
        Hedefi net, yolu uzun.
      </p>
    </div>

  </div>
</div>

<script>
function openList(){
  document.getElementById("list").style.display="block";
}
</script>

</body>
</html>
