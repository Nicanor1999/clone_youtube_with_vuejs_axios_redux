<template>
  <div id="app">
    <nav>
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </nav>
    <router-view />
    <nav>
      <div class="NavBar">
        <div class="Logo">
          <a href="#"> <span class="material-symbols-outlined">
              menu
            </span></a>
          <img src="./assets/logo.jpg" alt="" class="logo">
        </div>
        <div class="Search">
          <div class="SearchBar">
            <input dir="ltr" aria-autocomplete="list" aria-expanded="true" aria-label="Rechercher" role="combobox"
              placeholder="  Rechercher" autocomplete="off" spellcheck="false" aria-invalid="false" class="TextBar"
              type="search" value="" aria-controls=":rp1:" />
            <button>
              <a href="#"><span class="material-symbols-outlined">
                  search
                </span></a>
            </button>
          </div>
          <div class="VocalSearch">
            <a href="#">
              <span class="material-symbols-outlined">
                mic
              </span>
            </a>
          </div>
        </div>
        <div class="Profile">
          <div class="Features">
            <a href="#">
              <div>
                <span class="material-symbols-outlined">
                  video_call
                </span>
              </div>
            </a>
            <a href="#">
              <div><span class="material-symbols-outlined">
                  notifications
                </span></div>
            </a>
            <a href="#" class="User">
              N
            </a>
          </div>
        </div>
      </div>
    </nav>
    <section class="Main">
      <div class="Options">
        <div class="Features1">
          <ul>
            <li class="First">
              <div>
                <span class="material-symbols-outlined">
                  home
                </span>
                <div class="Name">Accueil</div>
              </div>

            </li>
            <li>
              <div>
                <img src="./assets/youtube-shorts-logo-15252.png" alt="">
                <div class="Name">Shorts</div>
              </div>
            </li>
            <li>
              <div>
                <span class="material-symbols-outlined">
                  subscriptions
                </span>
                <div class="Name">Abonnements</div>
              </div>
            </li>
          </ul>
        </div>
        <div class="Features2">
          <ul>
            <li>
              <div>
                <span class="material-symbols-outlined">
                  video_library
                </span>
                <div class="Name">Bibliothèque</div>
              </div>
            </li>
            <li>
              <div>
                <span class="material-symbols-outlined">history</span>
                <div class="Name">Historique</div>
              </div>
            </li>
            <li>
              <div>
                <span class="material-symbols-outlined">
                  smart_display
                </span>
                <div class="Name">Vos vidéos</div>
              </div>
            </li>
            <li>
              <div>
                <span class="material-symbols-outlined">
                  schedule
                </span>
                <div class="Name">À regarder plus tard</div>
              </div>

            </li>
            <li>
              <div>
                <span class="material-symbols-outlined">
                  thumb_up
                </span>
                <div class="Name">Vidéos "J'aime"</div>
              </div>

            </li>
            <li>
              <div>
                <span class="material-symbols-outlined">
                  expand_more
                </span>
                <div class="Name">Plus</div>
              </div>
            </li>
          </ul>
        </div>
        <div class="subscriptions">
          <div class="title">Abonnements</div>
          <ul>
            <li>
              <div>
                <img src="./assets/shubham-pawar-SanJsOPdLtU-unsplash.jpg" alt="">
                <div class="Name">LA LIGA EA Sports</div>
              </div>
            </li>
            <li>
              <div>
                <img src="./assets/shubham-pawar-SanJsOPdLtU-unsplash.jpg" alt="">
                <div class="Name">LA LIGA EA Sports</div>
              </div>
            </li>
            <li>
              <div>
                <img src="./assets/shubham-pawar-SanJsOPdLtU-unsplash.jpg" alt="">
                <div class="Name">LA LIGA EA Sports</div>
              </div>
            </li>
            <li>
              <div>
                <img src="./assets/shubham-pawar-SanJsOPdLtU-unsplash.jpg" alt="">
                <div class="Name">LA LIGA EA Sports</div>
              </div>
            </li>
            <li>
              <div>
                <img src="./assets/shubham-pawar-SanJsOPdLtU-unsplash.jpg" alt="">
                <div class="Name">LA LIGA EA Sports</div>
              </div>
            </li>
            <li>
              <div>
                <img src="./assets/shubham-pawar-SanJsOPdLtU-unsplash.jpg" alt="">
                <div class="Name">LA LIGA EA Sports</div>
              </div>
            </li>
            <li>
              <div>
                <img src="./assets/shubham-pawar-SanJsOPdLtU-unsplash.jpg" alt="">
                <div class="Name">LA LIGA EA Sports</div>
              </div>
            </li>
            <li>
              <div>
                <span class="material-symbols-outlined">
                  expand_more
                </span>
                <div class="Name">Afficher 316 éléme...</div>
              </div>
            </li>
          </ul>
        </div>
        <div class="Explore">
          <div class="title">Explorer</div>
          <ul>
            <li>
              <div>
                <span class="material-symbols-outlined">
                  local_fire_department
                </span>
                <div class="Name">Tendances</div>
              </div>
            </li>
            <li>
              <div>
                <span class="material-symbols-outlined">
                  music_note
                </span>
                <div class="Name">Musique</div>
              </div>
            </li>
            <li>
              <div>
                <span class="material-symbols-outlined">
                  home
                </span>
                <div class="Name">Direct</div>
              </div>
            </li>
            <li>
              <div>
                <span class="material-symbols-outlined">
                  sports_esports
                </span>
                <div class="Name">Jeux Vidéos</div>
              </div>

            </li>
            <li>
              <div>
                <span class="material-symbols-outlined">
                  news
                </span>
                <div class="Name">Actualités</div>
              </div>
            </li>
            <li>
              <div>
                <span class="material-symbols-outlined">
                  emoji_events
                </span>
                <div class="Name">Sport</div>
              </div>
            </li>
            <li>
              <div>
                <span class="material-symbols-outlined">
                  lightbulb
                </span>
                <div class="Name">Savoirs et Cultures</div>
              </div>
            </li>
            <li>
              <div>
                <span class="material-symbols-outlined">
                  styler
                </span>
                <div class="Name">Mode et Beauté</div>
              </div>
            </li>
          </ul>
        </div>
        <div class="Others">
          <div class="title">Autres contenus YouTube</div>
          <ul>
            <li>
              <div>
                <span class="material-symbols-outlined">
                  home
                </span>
                <div class="Name">Youtube Studio</div>
              </div>
            </li>
            <li>
              <div>
                <span class="material-symbols-outlined">
                  home
                </span>
                <div class="Name">Youtube Kids</div>
              </div>
            </li>
          </ul>
        </div>
        <div class="Settings">
          <ul>
            <li>
              <div>
                <span class="material-symbols-outlined">
                  settings
                </span>
                <div class="Name">Paramètres</div>
              </div>
            </li>
            <li>
              <div>
                <span class="material-symbols-outlined">
                  flag
                </span>
                <div class="Name">Historique des sign...</div>
              </div>
            </li>
            <li>
              <div>
                <span class="material-symbols-outlined">
                  help
                </span>
                <div class="Name">Aide</div>
              </div>
            </li>
            <li>
              <div>
                <span class="material-symbols-outlined">
                  live_help
                </span>
                <div class="Name">Envoyer des comm...</div>
              </div>
            </li>
          </ul>
        </div>
        <div class="OptionsFooter">
          <div class="Footer1">
            <a href="#">Présentation</a>
            <a href="#" class="space">Presse</a><br>
            <a href="#">Droits d'auteur</a>
            <a href="#" class="space">Nous <span class="Correct">Contacter</span></a><br>
            <a href="#">Créateurs</a>
            <a href="#" class="space">Publicités</a><br>
            <a href="#">Développeurs</a>
          </div>
          <div class="Footer2">
            <a href="#">Conditions d'utilisation</a>
            <a href="#">Confidentialité</a><br>
            <a href="#">Règles et sécurité</a><br>
            <a href="#">Premiers pas sur youtube</a><br>
            <a href="#">Tester de nouvelles <span class="Correct">fonctionnalités</span></a>
          </div>
          <div class="Copyright">
            © 2023 Google LLC
          </div>
        </div>
      </div>
      <div class="Center">
        <div class="Keywords">
          <div class="KeywordsContent">
            <div class="first">Tous</div>
            <div class="word">FC Barcelone</div>
            <div class="word">Music</div>
            <div class="word">Premier League</div>
            <div class="word">Mix</div>
            <div class="word">Jeux</div>
            <div class="word">PSG</div>
            <div class="word">En direct</div>
            <div class="word">Cristiano Ronaldo</div>
            <div class="word">Bandes-Annonces</div>
            <div class="word">Manga</div>
            <div class="word">Dribbles</div>
            <div class="arrow">
              <div><span class="material-symbols-outlined">
                  arrow_forward_ios
                </span></div>
            </div>
          </div>
        </div>
        <div class="Grids">
          <div class="Grid1">
            <div class="Element">
              <div class="video">
                <div class="reader">
                  <img src="./assets/Teni-Makanaki-TheCityCeleb-1140x641-1.jpg" alt="">
                </div>
                <div class="Details">
                  <div class="Detail1">
                    <div class="Profile"><img src="./assets/shubham-pawar-SanJsOPdLtU-unsplash.jpg" alt=""></div>
                  </div>
                  <div class="Detail2">
                    <div class="Title">HUSTLE</div>
                    <span>TENI</span>
                    <div class="hour">20M vues · il y a 10 heures</div>
                  </div>
                </div>
              </div>
            </div>
            <div class="Element">
              <div class="video">
                <div class="reader">
                  <img src="./assets/Nigeria's Oxlade Drops His Newest Dance Record “Ku Lo Sa”.jpg" alt="">
                </div>
                <div class="Details">
                  <div class="Detail1">
                    <div class="Profile"><img src="./assets/shubham-pawar-SanJsOPdLtU-unsplash.jpg" alt=""></div>
                  </div>
                  <div class="Detail2">
                    <div class="Title">KU LO SA A</div>
                    <span>KU LO SA A</span>
                    <div class="hour">48M vues · il y a 1 an</div>
                  </div>
                </div>
              </div>
            </div>
            <div class="Element">
              <div class="video">
                <div class="reader">
                  <img src="./assets/Young Jonn – Love is Not Enough, Vol 2 EP(2022) Download ZIP.jpg" alt="">
                </div>
                <div class="Details">
                  <div class="Detail1">
                    <div class="Profile"><img src="./assets/shubham-pawar-SanJsOPdLtU-unsplash.jpg" alt=""></div>
                  </div>
                  <div class="Detail2">
                    <div class="Title">Aquafina</div>
                    <span>Young Jonn</span>
                    <div class="hour">850k vues · il y a 6 mois</div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="Grid2">
            <div class="Element">
              <div class="video">
                <div class="reader">
                  <img src="./assets/Liens du 100 - SDM.jpg" alt="">
                </div>
                <div class="Details">
                  <div class="Detail1">
                    <div class="Profile"><img src="./assets/shubham-pawar-SanJsOPdLtU-unsplash.jpg" alt=""></div>
                  </div>
                  <div class="Detail2">
                    <div class="Title">Hier Encore</div>
                    <span>SDM</span>
                    <div class="hour">3M vues · il y a 10 heures</div>
                  </div>
                </div>
              </div>
            </div>
            <div class="Element">
              <div class="video">
                <div class="reader">
                  <img
                    src="./assets/Le martiniquais Kalash nominé à la cérémonie américaine des BET Hip Hop Awards - Martinique la 1ère.jpg"
                    alt="">
                </div>
                <div class="Details">
                  <div class="Detail1">
                    <div class="Profile"><img src="./assets/shubham-pawar-SanJsOPdLtU-unsplash.jpg" alt=""></div>
                  </div>
                  <div class="Detail2">
                    <div class="Title">Mwaka Moon</div>
                    <span>Kalash</span>
                    <div class="hour">325M vues · il y a 5 an</div>
                  </div>
                </div>
              </div>
            </div>
            <div class="Element">
              <div class="video">
                <div class="reader">
                  <img src="./assets/before I close my eyes- XXXTENTACION.jpg" alt="">
                </div>
                <div class="Details">
                  <div class="Detail1">
                    <div class="Profile"><img src="./assets/shubham-pawar-SanJsOPdLtU-unsplash.jpg" alt=""></div>
                  </div>
                  <div class="Detail2">
                    <div class="Title">MOONLIGHT</div>
                    <span>XXXTENTACION</span>
                    <div class="hour">49k vues · il y a 10 heures</div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="shorts">
          <div class="Title">
            <img src="./assets/youtube-shorts-logo-15250.png" alt="">
            <div>Shorts</div>
          </div>
          <div class="Contents">
            <div class="Content1">
              <img src="./assets/Teni-Makanaki-TheCityCeleb-1140x641-1.jpg" alt="">
              <div class="Legend">
                <div>More News Will Come Soon #trend #Youtube</div>
                <span>503K View</span>
              </div>
            </div>
            <div class="Content">
              <img src="./assets/shubham-pawar-SanJsOPdLtU-unsplash.jpg" alt="">
              <div class="Legend">
                <div>More News Will Come Soon #trend #Youtube</div>
                <span>503K View</span>
              </div>
            </div>
            <div class="Content">
              <img
                src="./assets/Le martiniquais Kalash nominé à la cérémonie américaine des BET Hip Hop Awards - Martinique la 1ère.jpg"
                alt="">
              <div class="Legend">
                <div>More News Will Come Soon #trend #Youtube</div>
                <span>503K View</span>
              </div>
            </div>
            <div class="Content">
              <img src="./assets/Nigeria's Oxlade Drops His Newest Dance Record “Ku Lo Sa”.jpg" alt="">
              <div class="Legend">
                <div>More News Will Come Soon #trend #Youtube</div>
                <span>503K View</span>
              </div>
            </div>
            <div class="Content">
              <img src="./assets/Liens du 100 - SDM.jpg" alt="">
              <div class="Legend">
                <div>More News Will Come Soon #trend #Youtube</div>
                <span>503K View</span>
              </div>
            </div>
          </div>
          <div class="Arrow">
            <button>
              <div>Plus</div>
              <span class="material-symbols-outlined">
                expand_more
              </span>
            </button>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<style>
* {
  font-family: 'Poppins', sans-serif;
}

body {
  /* background-color: cornsilk; */
  margin: 0px;
  height: 100vh;
}

.NavBar {
  /* background-color: #9323fb; */
  display: flex;
  height: 56px;
  padding-left: 16px;
  padding-right: 16px;
  width: calc(100% - 32px);
  position: fixed;
  top: 0px;
  background-color: rgb(255, 255, 255);
  z-index: 3;
}

.Logo {
  /* background-color: rgb(251, 58, 97); */
  width: 15%;
  display: flex;
  align-items: center;
}

.NavBar .Logo a .material-symbols-outlined {
  font-size: 24px;
  padding: 8px;
  font-weight: 300;
  text-decoration: none;
  color: black;
}

.logo {
  height: 20px;
  width: 90px;
  margin-left: 15px;
}

.Search {
  /* background-color: aquamarine; */
  width: 70%;
  display: flex;
  align-items: center;
  justify-content: center;
}

.SearchBar {
  display: flex;
  background-color: #ffffff;
  width: 568px;
  height: 40px;
  border: 1px solid #E2E2E2;
  border-radius: 20px;
  justify-content: space-between;
  margin-right: 20px;
}

.SearchBar button {
  width: 12%;
  height: 100%;
  border: none;
  /* border-left: 1px solid;   */
  /* border-color: #d3d3d3;   */
  background-color: #f0f0f0;
  margin: 0px;
  border-top-right-radius: 20px;
  border-bottom-right-radius: 20px;
}

/* .SearchBar a img {
    width: 13px;
    height: 13px;
    margin-top: 9px;
} */
.SearchBar a .material-symbols-outlined {
  height: 24px;
  width: 50px;
  font-weight: 200;
  text-decoration: none;
  color: black;
}

.TextBar {
  border: 0px solid transparent;
  background: #ffffff;
  border-top-left-radius: 20px;
  border-bottom-left-radius: 20px;
  width: 500px;
  padding-left: 10px;
  font-size: 16px;
}

.TextBar:focus {
  outline-color: #1877F2;
  caret-color: #1877F2;
}

.VocalSearch a {
  height: 40px;
  width: 40px;
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: #f0f0f0;
  border-radius: 50px;
  text-decoration: none;
  color: black;
  font-variation-settings:
    'FILL' 1,
    'wght' 400,
    'GRAD' 0,
    'opsz' 24
}

.Search .VocalSearch a .material-symbols-outlined {
  font-size: 25px;
}

.Profile {
  /* background-color: chartreuse; */
  width: 15%;
  height: 100%;
  display: flex;
  align-items: center;
  justify-content: end;
}

.Features {
  width: 80%;
  display: flex;
  height: 100%;
  margin-left: 80px;
  align-items: center;
}

.Features a .material-symbols-outlined {
  font-weight: 300;
}

.Features a {
  color: black;
  text-decoration: none;
  height: 40px;
  width: 33.33%;
  display: flex;
  align-items: center;
  justify-content: center;
  /* background-color: aqua; */
}

.Features a div {
  /* color: black;
    text-decoration: none; */
  height: 40px;
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
  /* background-color: #f0f0f0;
    border-radius: 1000px; */
}

.Features .User {
  /* color: black;
    text-decoration: none; */
  height: 35px;
  width: 25%;
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: #00887A;
  border-radius: 50px;
  color: white;
  font-size: 20px;
  margin-left: 15px;
}

.Features a div:hover {
  /* color: black;
    text-decoration: none; */
  height: 40px;
  width: 80%;
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: #f0f0f0;
  border-radius: 50px;
}

.Features a :hover {
  color: black;
  text-decoration: none;
  height: 40px;
  width: 33.33%;
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: #f0f0f0;
  border-radius: 1000px;
}

.Main {
  display: flex;
  height: 100vh;
}

.Options {
  /* background-color: brown; */
  height: 100vh;
  width: 16%;
  position: fixed;
  overflow-x: auto;
  top: 56px;
  left: 0px;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.Features1 {
  width: calc(100% - 22px);
  padding-left: 11px;
  padding-right: 11px;
  border-bottom: 1px solid #E5E5E5;
}

.Features1 ul {
  list-style: none;
  margin-top: 13px;
  width: 100%;
  padding-left: 0px;
}

.Features1 ul .First {
  background-color: #f3f3f3;
  border-radius: 10px;
}

.Features1 ul .First:hover {
  background-color: #E6E6E6;
  cursor: pointer;
  border-radius: 10px;
}

.Features1 ul .First .Name {
  font-weight: bold;
}

.Features1 ul li {
  height: 40px;
  width: 100%;
}

.Features1 ul li div {
  display: flex;
  align-items: center;
  height: 40px;
  width: 100%;
}

.Features1 ul li div:hover {
  display: flex;
  align-items: center;
  height: 40px;
  width: 100%;
  background-color: #F2F2F2;
  border-radius: 10px;
  cursor: pointer;
}

.Features1 ul li div .material-symbols-outlined {
  font-size: 24px;
  width: 20%;
  padding-left: 12px;
}

.Features1 ul li div img {
  height: 24px;
  width: 24px;
  padding-left: 12px;
  padding-right: 7px;
}

.Features1 ul .First div .material-symbols-outlined {
  font-size: 24px;
  width: 20%;
  padding-left: 12px;
  font-variation-settings:
    'FILL' 1,
    'wght' 400,
    'GRAD' 0,
    'opsz' 24
}

.Features1 ul li div .Name {
  font-size: 14px;
  margin-left: 18px;
}

.Features2 {
  width: calc(100% - 22px);
  padding-left: 11px;
  padding-right: 11px;
  border-bottom: 1px solid #E5E5E5;
}

.Features2 ul {
  list-style: none;
  margin-top: 13px;
  width: 100%;
  padding-left: 0px;
}

.Features2 ul li {
  height: 40px;
  width: 100%;
}

.Features2 ul li div {
  display: flex;
  align-items: center;
  height: 40px;
  width: 100%;
}

.Features2 ul li div img {
  height: 24px;
  width: 24px;
  padding-left: 12px;
  padding-right: 7px;
}

.Features2 ul li div:hover {
  display: flex;
  align-items: center;
  height: 40px;
  width: 100%;
  background-color: #F2F2F2;
  border-radius: 10px;
  cursor: pointer;
}

.Features2 ul li div .material-symbols-outlined {
  font-size: 24px;
  width: 20%;
  padding-left: 12px;
}

.Features2 ul li div .Name {
  font-size: 14px;
  margin-left: 18px;
}

.subscriptions {
  width: calc(100% - 22px);
  padding-left: 11px;
  padding-right: 11px;
  border-bottom: 1px solid #E5E5E5;
}

.subscriptions .title {
  font-size: 16px;
  font-weight: 550;
  padding-left: 12px;
  margin-top: 15px;
}

.subscriptions ul {
  list-style: none;
  margin-top: 10px;
  width: 100%;
  padding-left: 0px;
}

.subscriptions ul li {
  height: 40px;
  width: 100%;

}

.subscriptions ul li div {
  display: flex;
  align-items: center;
  height: 40px;
  width: 100%;
  padding-left: 12px;
}

.subscriptions ul li div:hover {
  display: flex;
  align-items: center;
  height: 40px;
  width: 100%;
  background-color: #F2F2F2;
  border-radius: 10px;
  cursor: pointer;
}

.subscriptions ul li div img {
  height: 24px;
  width: 24px;
  border-radius: 100px;
}

.subscriptions ul li div .material-symbols-outlined {
  height: 24px;
  width: 24px;
  border-radius: 100px;
}

.subscriptions ul li div .Name {
  font-size: 14px;
  margin-left: 15px;
}

.Explore {
  width: calc(100% - 22px);
  padding-left: 11px;
  padding-right: 11px;
  border-bottom: 1px solid #E5E5E5;
}

.Explore .title {
  font-size: 16px;
  font-weight: 550;
  padding-left: 12px;
  margin-top: 15px;
}

.Explore ul {
  list-style: none;
  margin-top: 10px;
  width: 100%;
  padding-left: 0px;
}

.Explore ul li {
  height: 40px;
  width: 100%;

}

.Explore ul li div {
  display: flex;
  align-items: center;
  height: 40px;
  width: 100%;
  padding-left: 12px;
}

.Explore ul li div:hover {
  display: flex;
  align-items: center;
  height: 40px;
  width: 100%;
  background-color: #F2F2F2;
  border-radius: 10px;
  cursor: pointer;
}

/* .Explore ul li div img {
    height: 24px;
    width: 24px;
    border-radius: 100px;
} */

.Explore ul li div .material-symbols-outlined {
  height: 24px;
  width: 24px;
  border-radius: 100px;
}

.Explore ul li div .Name {
  font-size: 14px;
  margin-left: 15px;
}

.Others {
  width: calc(100% - 22px);
  padding-left: 11px;
  padding-right: 11px;
  border-bottom: 1px solid #E5E5E5;
}

.Others .title {
  font-size: 16px;
  font-weight: 550;
  padding-left: 12px;
  margin-top: 15px;
  width: 100%;
}

.Others ul {
  list-style: none;
  margin-top: 10px;
  width: 100%;
  padding-left: 0px;
}

.Others ul li {
  height: 40px;
  width: 100%;

}

.Others ul li div {
  display: flex;
  align-items: center;
  height: 40px;
  width: 100%;
  padding-left: 12px;
}

.Others ul li div:hover {
  display: flex;
  align-items: center;
  height: 40px;
  width: 100%;
  background-color: #F2F2F2;
  border-radius: 10px;
  cursor: pointer;
}

/* .Others ul li div img {
    height: 24px;
    width: 24px;
    border-radius: 100px;
} */

.Others ul li div .material-symbols-outlined {
  height: 24px;
  width: 24px;
  border-radius: 100px;
}

.Others ul li div .Name {
  font-size: 14px;
  margin-left: 15px;
}

.Settings {
  width: calc(100% - 22px);
  padding-left: 11px;
  padding-right: 11px;
  border-bottom: 1px solid #E5E5E5;
}

.Settings ul {
  list-style: none;
  margin-top: 13px;
  width: 100%;
  padding-left: 0px;
}

.Settings ul li {
  height: 40px;
  width: 100%;
}

.Settings ul li div {
  display: flex;
  align-items: center;
  height: 40px;
  width: 100%;
}

.Settings ul li div:hover {
  display: flex;
  align-items: center;
  height: 40px;
  width: 100%;
  background-color: #F2F2F2;
  border-radius: 10px;
  cursor: pointer;
}

.Settings ul li div .material-symbols-outlined {
  font-size: 24px;
  width: 20%;
  padding-left: 12px;
}

.Settings ul li div .Name {
  font-size: 14px;
  margin-left: 18px;
}

.OptionsFooter {
  width: calc(100% - 22px);
  padding-left: 11px;
  padding-right: 11px;
  border-bottom: 1px solid #E5E5E5;
}

.Footer1 {
  list-style: none;
  margin-top: 13px;
  width: 100%;
  padding-left: 0px;
  /* display: grid;
    grid-template-columns: repeat(2, 1fr);
    grid-gap: 0px;
    grid-auto-rows: minmax(0px, auto); */
}

.Footer1 a {
  height: 40px;
  width: 100%;
  text-decoration: none;
  color: black;
  font-size: 13px;
  padding-left: 12px;
}

.Footer2 {
  list-style: none;
  margin-top: 13px;
  width: 100%;
  padding-left: 0px;
  /* display: grid;
    grid-template-columns: repeat(2, 1fr);
    grid-gap: 0px;
    grid-auto-rows: minmax(60px, auto); */
}

.Footer2 a {
  height: 40px;
  width: 100%;
  text-decoration: none;
  color: black;
  font-size: 13px;
  padding-left: 12px;
}

.Footer2 a :hover {
  height: 40px;
  width: 100%;
  text-decoration: none;
  color: black;
  font-size: 13px;
}

.Copyright {
  margin-top: 15px;
  width: 100%;
  width: calc(100% - 22px);
  padding-left: 11px;
  padding-right: 11px;
  font-size: 13px;
  font-weight: 100;
}

.Correct {
  padding-left: 12px;
  padding-bottom: 100px;
}

.Keywords {
  /* background-color: cadetblue; */
  position: fixed;
  top: 56px;
  left: 16%;
  background-color: white;
  width: 1285px;
  z-index: 3;
}

.KeywordsContent {
  height: 100%;
  height: 56px;
  display: flex;
  align-items: center;
  justify-content: space-around;
  margin-left: 15px;
  margin-right: 15px;
}

.KeywordsContent .first {
  background-color: #000000;
  height: 32px;
  display: flex;
  align-items: center;
  padding-left: 12px;
  padding-right: 12px;
  border-radius: 10px;
  color: white;
  font-size: 14px;
}

.KeywordsContent .first:hover {
  background-color: #000000;
  height: 32px;
  display: flex;
  align-items: center;
  padding-left: 12px;
  padding-right: 12px;
  border-radius: 10px;
  color: white;
  cursor: pointer;
  font-size: 14px;
}

.KeywordsContent .word {
  background-color: #f0f0f0;
  height: 32px;
  display: flex;
  align-items: center;
  padding-left: 12px;
  padding-right: 12px;
  border-radius: 10px;
  font-size: 14px;
}

.KeywordsContent .word:hover {
  background-color: #e1dcdc;
  height: 32px;
  display: flex;
  align-items: center;
  padding-left: 12px;
  padding-right: 12px;
  border-radius: 10px;
  cursor: pointer;
  font-size: 14px;
}

.KeywordsContent .arrow div {
  height: 32px;
  width: 32px;
  display: flex;
  justify-content: center;
  border-radius: 50px;
}

.KeywordsContent .arrow div .material-symbols-outlined {
  background-color: white;
  font-size: 20px;
  display: flex;
  align-items: center;
  padding-left: 7px;
  border-radius: 100px;
  width: 30px;
  font-weight: 200;
}

.KeywordsContent .arrow div .material-symbols-outlined:hover {
  background-color: #f0f0f0;
  font-size: 20px;
  display: flex;
  align-items: center;
  padding-left: 7px;
  border-radius: 100px;
  width: 30px;
  font-weight: 200;
  cursor: pointer;
}

.Center {
  width: 84%;
  height: 200vh;
  /* background-color: #00887A; */
  position: absolute;
  z-index: 0;
  top: 112px;
  left: 16%;
}

.Grids {
  background-color: none;
  height: 50%;
  margin-left: 20px;
  margin-right: 15px;
  width: calc(100% - 35px);
  display: flex;
  flex-direction: column;
}

.shorts {
  margin-left: 20px;
  margin-right: 15px;
  width: calc(100% - 35px);
  height: 50%;
  /* background-color: #883600; */
  border-top: 4px solid #E5E5E5;
  margin-top: 30px;
}

.shorts .Title {
  /* background-color: rgb(250, 84, 117); */
  height: 30%;
  width: 100%;
}

.shorts .Contents {
  /* background-color: #00887A; */
  height: 62%;
  width: 100%;
  display: flex;
}

.shorts .Contents .Content {
  height: 100%;
  width: 234px;
  /* background-color: #e1dcdc; */
  margin-left: 19.5px;
  border-radius: 20px;
}

.shorts .Contents .Content img {
  width: 100%;
  height: 87%;
  object-fit: cover;
  border-radius: 20px;
}

.shorts .Contents .Content .Legend {
  width: 90%;
  height: 13%;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}

.shorts .Contents .Content .Legend div {
  font-size: 15px;
  font-weight: 500;
}

.shorts .Contents .Content .Legend span {
  font-size: 12px;
  color: #909090;
  font-weight: 400;
}

.shorts .Contents .Content1 {
  height: 100%;
  width: 234px;
  /* background-color: #e1dcdc; */
  border-radius: 20px;
  /* margin-left: 19.5px; */
}

.shorts .Contents .Content1 img {
  width: 100%;
  height: 87%;
  object-fit: cover;
  border-radius: 20px;
}

.shorts .Contents .Content1 .Legend {
  width: 90%;
  height: 13%;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}

.shorts .Contents .Content1 .Legend div {
  font-size: 15px;
  font-weight: 500;
}

.shorts .Contents .Content1 .Legend span {
  font-size: 12px;
  color: #909090;
  font-weight: 400;
}

.shorts .Arrow {
  /* background-color: bisque; */
  margin-top: 20px;
  height: calc(8% - 20px);
  width: 100%;
  display: flex;
  justify-content: center;
}
.shorts .Arrow button{
  width: 28%;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: white;
  border: 1px solid #90909050;
  border-radius: 40px;
}
.Grid1 {
  /* background-color: #1877F2; */
  height: 360px;
  display: flex;
  width: 100%;
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 23px;
  grid-auto-rows: minmax(60px, auto);
  margin-top: 35px;
}

.Grid2 {
  /* background-color: #1877F2; */
  height: 360px;
  display: flex;
  width: 100%;
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 23px;
  grid-auto-rows: minmax(60px, auto);
}

.Element {
  height: 360px;
  width: 400px;
}

.video {
  height: 100%;
  width: 100%;
}

.reader {
  height: 220px;
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
}

.reader img {
  height: 100%;
  width: 100%;
  border-radius: 10px;
}

.Details {
  height: 100px;
  width: 100%;
  display: flex;
  margin-top: 10px;
}

.Detail1 {
  width: 10%;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: flex-start;
}

.Detail1 .Profile {
  width: 100%;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: flex-start;
}

.Detail1 .Profile img {
  height: 36px;
  width: 36px;
  border-radius: 50px;
}

.Detail2 {
  width: 90%;
  height: 100%;
  margin-left: 10px;
}

.Detail2 .Title {
  width: 100%;
  height: 50%;
  font-weight: bolder;
}

.Detail2 span {
  font-size: 13px;
}

.Detail2 .hour {
  font-size: 13px;
}

.shorts {
  height: 50%;
}

.shorts .Title {
  height: 10%;
  display: flex;
  align-items: center;
}

.shorts .Title img {
  height: 24px;
  width: 24px;
  padding-left: 12px;
  padding-right: 7px;
}

.shorts .Title div {
  font-weight: bold;
  font-size: 19px;
}

::-webkit-scrollbar {
  width: 8px;
  height: 10px;
  /* display: none; */
  margin-left: 1500px !important;
  background-color: transparent;
}

/* ::-webkit-scrollbar:hover {
    width: 10px;
    height: 15px;
    margin-left: 1500px !important;
    background-color: #e6e6e7;   
} */

::-webkit-scrollbar-track {
  -webkit-box-shadow: 0 0 1px rgba(255, 255, 255, 0.3);
  /* border-radius: 10px; */
}

::-webkit-scrollbar-thumb {
  border-radius: 10px;
  -webkit-box-shadow: 0 0 6px rgba(0, 0, 0, 0.5);
  background-color: #909090 !important;
}

::-webkit-scrollbar-thumb:hover {
  border-radius: 10px;
  -webkit-box-shadow: 0 0 6px rgba(0, 0, 0, 0.5);
  background-color: #909090 !important;
}</style>
