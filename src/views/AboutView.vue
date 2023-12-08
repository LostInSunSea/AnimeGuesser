<template>
  <div class='about card container content'>
    <h1 class="title">How To Play</h1>
    <p class="left">
      The Goal is to guess which anime is the correct answer like wordle,gamedle, etc... <br />
      You will be given six categories [ Genres, Popularity, Source, Season, Studio, Related Series].
      Each category will have a values to help you determine how close you are to the solution. <br />
      These values are taken from ANILIST and are based off the information provided by their API. <br />
      You will have five lives to guess the correct answer. <br />
    </p>
    <ul class="list left">
      <li>Genres: Each guess will list the associated genres with your guess. Hover over the icons to see what genres they
        are. If the genre section is green then you have matched genres with the solution exactly.
        Otherwise if it is yellow you have a partial match and if red none of the genres have matched at all.
      </li>
      <li>Popularity: This denotes the popularity of the anime on ANILIST. If it is red and the arrow is up, it means that
        the solution
        is more popular than your guess. If it is red and the arrow is down, it means that the solution is less popular
        than your guess.
        If it is green, then you have guessed the correct answer.
      </li>
      <li>Source: This denotes the origin of the anime i.e. Mange, Original, Light Novel. If will be green if your guess
        matches the solution. Red if otherwise
      </li>
      <li>Season: This is the season and year that the anime aired. It will be green if you have the correct year and
        season.
        Yellow if you have the correct year, and red if you have neither. If you have neither, the arrow will point up if
        the solution
        is newer than your guess and down if it is older.
      </li>
      <li>Studio: This refers to the primary studio that animated the show. If will be green if it matches the solution
        and red if not
      </li>
      <li>Related Series: This will be green if your guess is related to the solution i.e spinoff or sequel. It will be
        red if not
      </li>
    </ul>
  </div>
</template>
<style scoped>
.about {
  margin: 0 auto;
  width: 80%;
  padding: 20px;
}

.title {
  text-align: center;
  font-size: large;
}

.left {
  text-align: left;
}

.list li{
  display: list-item;
  list-style-type: disc;
}
</style>
