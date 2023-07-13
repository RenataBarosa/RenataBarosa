- 👋 Oi, Eu sou @RenataBarosa
- 👀 Sou dentista e hoje tenho muito interesse em aprender infórmatica
- 🌱 Atualmente estou estudando Programação na Alura
- 💞️ Pretendo utilizar este novo conhecimento no meu dia a dia de trabalho 
- 📫 Como me contactar por:
- Email: ren.chris@yahoo.com.br
- Instagran: RenataChristinne

<!---
RenataBarosa/RenataBarosa is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Filmes</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Kumbh+Sans:wght@300;400;500;600&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <main>
    <h2>Filmes Populares</h2>
    <div class="input-container">
      <input type="text" name="movie-name" id="movie-name" placeholder="Digite algum filme para pesquisar...">
      <img src="images/search-icon.svg" alt="Ícone de pesquisa" class="searchIcon">
    </div>
    <div class="showOnlyFavorites">
      <input type="checkbox" name="onlyFavorites" id="onlyFavorites">
      <label for="onlyFavorites">Mostrar apenas meus filmes favoritos</label>
    </div>
    <div class="movies">
      <div class="movie">
        <div class="movie-informations">
          <div class="movie-image">
            <img src="https://img.elo7.com.br/product/original/3FBA809/big-poster-filme-batman-2022-90x60-cm-lo002-poster-batman.jpg" alt="Batman (2022)"/>
          </div>
          <div class="movie-text">
            <h4>Batman (2022)</h4>
            <div class="rating-favorites">
              <div class="rating">
                <img src="images/star.png" alt="Star Icon"/>
                <span>9.2</span>
              </div>
              <div class="favorite">
                <img src="images/heart.svg" alt="Star Icon"/>
                <span>Favoritar</span>
              </div>
            </div>
          </div>
        </div>
        <div class="movie-description">
          <span>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.</span>
        </div>
      </div>

      <div class="movie">
        <div class="movie-informations">
          <div class="movie-image">
            <img src="https://img.elo7.com.br/product/original/3FBA809/big-poster-filme-batman-2022-90x60-cm-lo002-poster-batman.jpg" alt="Batman (2022)"/>
          </div>
          <div class="movie-text">
            <h4>Batman (2022)</h4>
            <div class="rating-favorites">
              <div class="rating">
                <img src="images/star.png" alt="Star Icon"/>
                <span>9.2</span>
              </div>
              <div class="favorite">
                <img src="images/heart.svg" alt="Star Icon"/>
                <span>Favoritar</span>
              </div>
            </div>
          </div>
        </div>
        <div class="movie-description">
          <span>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.</span>
        </div>
      </div>

      <div class="movie">
        <div class="movie-informations">
          <div class="movie-image">
            <img src="https://img.elo7.com.br/product/original/3FBA809/big-poster-filme-batman-2022-90x60-cm-lo002-poster-batman.jpg" alt="Batman (2022)"/>
          </div>
          <div class="movie-text">
            <h4>Batman (2022)</h4>
            <div class="rating-favorites">
              <div class="rating">
                <img src="images/star.png" alt="Star Icon"/>
                <span>9.2</span>
              </div>
              <div class="favorite">
                <img src="images/heart.svg" alt="Star Icon"/>
                <span>Favoritar</span>
              </div>
            </div>
          </div>
        </div>
        <div class="movie-description">
          <span>Lorem Ipsum is simply Lar dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.</span>
        </div>
      </div>
    </div>
  </main>
</body>
</html>
