# perujo.github.io
<!DOCTYPE html>
<html>
<head>
<title>Estilos CSS Replicados</title>
<style type="text/css">
nav {
  background-color: black;
  padding: 10px;
}

nav a {
  color: white;
  display: block;
  padding: 5px 0;
  text-decoration: none;
}

section {
  display: flex;
  flex-direction: column;
  align-items: center;
  margin-top: 20px;
}

img {
  width: 100px;
  height: auto;
  border: 4px solid red;
  margin-bottom: 10px;
}

article ul {
  list-style: none;
  padding: 0;
  margin: 20px 0 0 0;
  display: flex;
  justify-content: center;
}

article li {
  padding: 5px 10px;
  border: 1px dashed black;

  margin: 0 5px;
}
</style>
</head>
<body>

<nav>
  <a href="#">Link</a>
  <a href="#">Link</a>
  <a href="#">Link</a>
  <a href="#">Link</a>
</nav>
<section>
<img src="html.png" alt="Icono de diseño"/>
<img src="html.png" alt="Icono de diseño"/>
<img src="html.png" alt="Icono de diseño"/>
<img src="html.png" alt="Icono de diseño"/>
</section>
<article>
<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Coca Cola</li>
</ul>
</article>
</body>
</html>
