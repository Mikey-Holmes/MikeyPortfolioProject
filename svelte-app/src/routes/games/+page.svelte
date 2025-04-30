<link rel="stylesheet" href="/styles/global.css" />

<div class="container">
  <div class="pics">
    <img src="zombiegame.png" alt="Zombie Game" class="image" />
    <div class="text-box">This is one game I had alot of fun coding, I made this game for a project in year one semester 2, the aim of the game was to get a set amount of score without dying to the zombies, but as the game carried on it gradually got harder, my lecturer couldn't even beat the game!</div>
  </div>
  <div class="pics">
    <img src="birdgame.png" alt="Flying Helicopter Game" class="image" />
    <div class="text-box">This game is quite special to me, this is where I finally got a grasp of how to create a fun game, it was very difficult and there was a lot of trial and error involved, in the end I got there, in this game the player controls the helicopter and must fly to the star on the right side of the screen without colliding with a bird, the birds move around on the screen and if the player hits one they must restart the game.</div>
  </div>
</div>

<div class="small-footer">
  Game links are available upon request.
</div>

<style>
  .container {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    padding: 20px;
  }

  .pics {
    text-align: center;
    max-width: 45%;
  }

  .image {
    width: 100%;
    height: auto;
    transition: transform 0.3s ease;
    border-radius: 10px;
  }

  .image:hover {
    transform: scale(1.1);
    cursor: pointer;
  }

  .text-box {
    margin-top: 30px;
    padding: 15px;
    background-color: rgba(173, 216, 230, 0.6);
    font-family: 'Poppins', sans-serif;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  }

  .text-box:hover {
    transform: scale(1.1);
    font-size: 1.2em;
    cursor: pointer;
  }

  .small-footer {
    margin: 30px auto;
    padding: 10px;
    background-color: rgba(173, 216, 230, 0.6);
    text-align: center;
    font-family: 'Poppins', sans-serif;
    font-size: 0.9em;
    font-weight: bold;
    border-radius: 10px;
    max-width: 300px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s, font-size 0.3s;
}

.small-footer:hover {
  transform: scale(1.05);
  font-size: 1em;
}

</style>
