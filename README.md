<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Diário da Max</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Diário da Max</h1>
    <p>Clique em um personagem para ver mais detalhes</p>
  </header>

  <main class="diary">
    <a href="max.html" class="photo"><img src="img/max.jpg"><span>Max</span></a>
    <a href="chloe.html" class="photo"><img src="img/chloe.jpg"><span>Chloe</span></a>
    <a href="rachel.html" class="photo"><img src="img/rachel.jpg"><span>Rachel</span></a>
    <a href="kate.html" class="photo"><img src="img/kate.jpg"><span>Kate</span></a>
    <a href="victoria.html" class="photo"><img src="img/victoria.jpg"><span>Victoria</span></a>
    <a href="jefferson.html" class="photo"><img src="img/jefferson.jpg"><span>Jefferson</span></a>
    <a href="warren.html" class="photo"><img src="img/warren.jpg"><span>Warren</span></a>
    <a href="frank.html" class="photo"><img src="img/frank.jpg"><span>Frank</span></a>
    <a href="joyce.html" class="photo"><img src="img/joyce.jpg"><span>Joyce</span></a>
    <a href="david.html" class="photo"><img src="img/david.jpg"><span>David</span></a>
    <a href="nathan.html" class="photo"><img src="img/nathan.jpg"><span>Nathan</span></a>
  </main>
</body>
</html>

<style>
body{
  margin:0;
  font-family: 'Segoe UI', sans-serif;
  background:#f2e9d8;
}
header{
  text-align:center;
  padding:20px;
}
.diary{
  display:grid;
  grid-template-columns: repeat(auto-fit, minmax(150px,1fr));
  gap:20px;
  padding:30px;
}
.photo{
  text-decoration:none;
  color:#000;
  background:#fff;
  padding:10px;
  box-shadow:2px 2px 8px rgba(0,0,0,0.2);
  transform: rotate(-2deg);
  transition:0.3s;
}
.photo:nth-child(even){transform: rotate(2deg);}
.photo:hover{
  transform: scale(1.05) rotate(0deg);
}
.photo img{
  width:100%;
  display:block;
}
.photo span{
  display:block;
  text-align:center;
  margin-top:8px;
  font-weight:bold;
}
</style>


<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Max Caulfield</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Max Caulfield</h1>
    <a href="index.html">← Voltar ao diário</a>
  </header>
  <main class="profile">
    <img src="img/max.jpg">
    <p>Max é a protagonista de Life is Strange. Uma estudante de fotografia que descobre o poder de voltar no tempo.</p>
  </main>
</body>
</html>

<style>
.profile{
  max-width:600px;
  margin:40px auto;
  background:#fff;
  padding:20px;
  box-shadow:2px 2px 10px rgba(0,0,0,0.2);
}
.profile img{
  width:100%;
}
</style>
