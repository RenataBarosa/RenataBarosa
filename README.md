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

<h1> html 
</h1>
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

<h1> style </h1>
:root {
  --background-color: #17162E;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Kumbh Sans', sans-serif;
}

body {
  max-width: 1260px;
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 2rem;
  background: var(--background-color);
  margin: 0 auto;
}

main {
  width: 100%;
}

h2 {
  color: #FFF;
  text-align: center;
  margin: 2rem 0;
}

.input-container {
  background-color: rgba(255, 255, 255, 0.2);
  width: 50%;
  margin: 0 auto;
  margin-bottom: 2rem;
  display: flex;
  padding: 0.5rem 1rem;
  border-radius: 0.5rem;
}

.input-container input {
  padding: 0.5rem;
  width: 100%;
  height: 100%;
  outline: none;
  border: none;
  background-color: transparent;
  color: #FFF;
}

.input-container img {
  cursor: pointer;
}

.showOnlyFavorites {
  text-align: center;
  margin-bottom: 2rem;
  color: #FFF;
}

.movie {
  color: #FFF;
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 2rem;
  background: #1D1C3B;
  border-radius: 0.5rem; 
  padding: 1rem;
  margin: 0 auto;
  margin-bottom: 2rem;
  max-width: 1024px;
  box-shadow: 10px 10px 30px rgba(0, 0, 0, 0.2);
}

.movie .movie-image {
  width: 92px;
  height: 92px;
  margin-right: 1rem;
}

.movie .movie-image img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  border-radius: 50%;
  box-shadow: 10px 10px 20px rgba(0, 0, 0, 0.3);
}

.movie-informations {
  display: flex;
  align-items: center;
  gap: 1rem;
}

.movie-informations .movie-text {
  display: flex;
  flex-direction: column;
  gap: 1rem;
}

.movie-informations .movie-text .rating-favorites {
  display: flex;
  align-items: center;
  gap: 2rem;
}

.movie-informations .rating, .movie-informations .favorite {
  display: flex;
  align-items: center;
  gap: 0.5rem;
  font-size: 0.8rem;
}

.movie-informations .rating img {
  width: 16px;
}

.movie-informations .favorite img {
  cursor: pointer;
  transition: all .3s;
  width: 1.2rem;
}

.movie-informations .favorite img:hover {
  transform: scale(1.1);
}

.movie-description {
  max-width: 50%;
  color: #ACACAC;
  font-weight: 400;
  font-size: 0.85rem;
  line-height: 1.5rem;
}

<h1> imagemCoraçãoVermelho </h1>
images/heart-fill.svg
<svg width="21" height="19" viewBox="0 0 21 19" fill="none" xmlns="http://www.w3.org/2000/svg">
<path d="M19.2913 1.61183C18.7805 1.10083 18.1741 0.695472 17.5066 0.41891C16.8392 0.142347 16.1238 0 15.4013 0C14.6788 0 13.9634 0.142347 13.2959 0.41891C12.6285 0.695472 12.022 1.10083 11.5113 1.61183L10.4513 2.67183L9.39129 1.61183C8.3596 0.580134 6.96032 0.000534762 5.50129 0.000534773C4.04226 0.000534784 2.64298 0.580134 1.61129 1.61183C0.579599 2.64352 1.08706e-08 4.04279 0 5.50183C-1.08706e-08 6.96086 0.579599 8.36013 1.61129 9.39183L2.67129 10.4518L10.4513 18.2318L18.2313 10.4518L19.2913 9.39183C19.8023 8.88107 20.2076 8.27464 20.4842 7.60718C20.7608 6.93972 20.9031 6.22431 20.9031 5.50183C20.9031 4.77934 20.7608 4.06393 20.4842 3.39647C20.2076 2.72901 19.8023 2.12258 19.2913 1.61183Z" fill="#BA0707"/>
</svg>

<h1> imagemCoraçãoVazado </h1>
images/heart.svg
<svg width="23" height="21" viewBox="0 0 23 21" fill="none" xmlns="http://www.w3.org/2000/svg">
<path d="M20.2913 2.61183C19.7805 2.10083 19.1741 1.69547 18.5066 1.41891C17.8392 1.14235 17.1238 1 16.4013 1C15.6788 1 14.9634 1.14235 14.2959 1.41891C13.6285 1.69547 13.022 2.10083 12.5113 2.61183L11.4513 3.67183L10.3913 2.61183C9.3596 1.58013 7.96032 1.00053 6.50129 1.00053C5.04226 1.00053 3.64298 1.58013 2.61129 2.61183C1.5796 3.64352 1 5.04279 1 6.50183C1 7.96086 1.5796 9.36013 2.61129 10.3918L3.67129 11.4518L11.4513 19.2318L19.2313 11.4518L20.2913 10.3918C20.8023 9.88107 21.2076 9.27464 21.4842 8.60718C21.7608 7.93972 21.9031 7.22431 21.9031 6.50183C21.9031 5.77934 21.7608 5.06393 21.4842 4.39647C21.2076 3.72901 20.8023 3.12258 20.2913 2.61183V2.61183Z" stroke="#BA0707" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
</svg>

<h1> imagemLupa </h1>
<svg width="21" height="22" viewBox="0 0 21 22" fill="none" xmlns="http://www.w3.org/2000/svg">
<path d="M9 17C13.4183 17 17 13.4183 17 9C17 4.58172 13.4183 1 9 1C4.58172 1 1 4.58172 1 9C1 13.4183 4.58172 17 9 17Z" stroke="#8A8A8A" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
<path d="M19.35 20.35L15 16" stroke="#8A8A8A" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
</svg>

<h1> imagemEstrela </h1>
images/star.png
