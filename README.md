<!DOCTYPE html>
<html lang='pt'>
  <head>
    <title>O Rubi !</title>

    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lato">
    <link rel="stylesheet" href="application.css">
  </head>

  <body>
    <main>
      <div class="logo">
        <img src="ruby.png" alt="ruby"> <height="42"> <width="42">
      </div>

      <h1 class="band-name">Rubi</h1>
      <h2 class="headline">Descrições de um rubi</h2>

      <p>Um rubi é uma pedra preciosa rosa a vermelho-sangue, uma variedade de corindo mineral (óxido de alumínio). Outras variedades de corindo com qualidade de gema são chamadas safiras. ... A palavra rubi vem de "ruber", latim para vermelho.</p>

      <hr>

      <div class="concerts">
        <h2>Shows</h2>

        <table>
          <thead>
            <tr>
              <th>Cidade</th>
              <th>Data</th>
            </tr>
          </thead>

          <tbody>
            <tr>
              <td>Rio de Janeiro</td>
              <td>09/10/2021</td>
            </tr>

            <tr>
              <td>Rio de Janeiro-RJ</td>
              <td>01/11/2018</td>
            </tr>

            <tr>
              <td>Belo Horizonte-MG</td>
              <td>01/12/2018</td>
            </tr>

            <tr>
              <td>Refice-PE</td>
              <td>01/01/2019</td>
            </tr>
          </tbody>
        </table>
      </div>
    </main>
  </body>


</html>

    
    
    
    
    
    
    
    
    body {
  width: 95%;
  max-width: 800px;
  margin: auto;
  background: url(bg.jpg) center;

  font-family: 'Lato';
  line-height: 1.5;
  color: white;
}

main {
  background: #00000054;
  padding: 5px 40px;
  margin-top: 20px;
  border-radius: 10px;
}

.logo, .band-name, .headline {
  margin: 0;
  text-align: center;
}

.concerts {
  margin: 30px 0;
  text-align: center;
  width: 100%;
}

.concerts table {
  background: #cb3a3ab3;
  border-radius: 10px;
  padding: 10px;
  margin: 0 auto;
}
