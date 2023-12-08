<template>
  <div class='about card container'>
    <h1 class="title">How To Play</h1>
    <p class="left">
      The Goal is to guess which anime is the correct answer. <br />
      You will be given six categories [ Genres, Popularity, Source, Season, Studio, Related Series].
      Each category will have a value that is either higher or lower than the correct answer. <br />
      You will have five lives to guess the correct answer. <br />
      For genres it will be green for an exact match, yellow for a partial match and red for no match. <br />
      For popularity it will be green for an exact match or red if not. The arrow denotes the popularity of the solution.
      <br />
      i.e. if it is an up arrow the solution is more popular than your guess.
      For source it will be green for an exact match or red if not and relates to if it came from a light novel, manga,
      original etc... <br />
      For season it will be green for an exact match, yellow if it is in the same year, and red from a completely
      different year. <br />
      For studio it will be green for an exact match or red if not and is based off of the primary studio for the anime.
      <br />
      Related series will be green if it is from a related series and red if not.
    </p>
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
</style>
