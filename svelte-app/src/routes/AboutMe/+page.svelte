<link rel="stylesheet" href="/styles/global.css" />

<div class="container">

  <div class="section">
    <div class="text">Hello! My name is Mikey and I am currently studying in SETU Carlow, I am studying the Interactive Digital Art and Design course, I enjoy doing artwork although my artistic skills need improvement, my design and coding abilities are much better than my artistic abilities in my opinion. I feel that during my time participating in this course I have greatly improved in each of the areas I listed above.</div>
    <img src="setu.jpg" alt="SETU image">
  </div>

  <div class="section column">
    <div class="text">I enjoy gaming, especially FPS and sandbox games. I also like making and editing videos—it’s something I have a lot of fun with. When I’m not online, I like watching anime (One Piece is one of my favorites) and playing sports like soccer and hurling.I’m motivated because I want to be successful doing something I love. My dream is to turn one of my hobbies into a career someday.</div>
    <img src="luffy.jpg" alt="anime luffy image" class="second-image">

  </div>
</div>

<style>
  .container {
    display: flex;
    flex-direction: column;
    gap: 20px;
    margin: 20px;
  }
  
  .section {
    display: flex;
    align-items: center;
    gap: 20px;
  }

  .section.column {
    flex-direction: column;
  }

  img {
    max-width: 100%;
    height: auto;
    border-radius: 8px;
    transition: transform 0.3s ease;
  }

  img:hover {
    transform: scale(1.1); 
  }
  
  .text {
    font-family: 'Poppins', sans-serif;
    font-size: 1rem;
    line-height: 1.6;
    color: #333333;
    text-align: justify;
    padding: 12px;
    margin: 10px 0;
    background-color: rgba(173, 216, 230, 0.6);
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  }

  .text:hover {
    transform: scale(1.02);
    font-size: 1.1em;
    cursor: pointer;
  }
  

  .second-image {
    max-width: 60%;
    height: auto;
  }
</style>