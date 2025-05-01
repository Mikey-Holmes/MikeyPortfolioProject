<link rel="stylesheet" href="/styles/global.css" />


<h1>Hi, my name is Mikey, welcome to my Portfolio</h1>
<h2>I am currently a student at SETU Carlow, here you will find relative information about me and my work.</h2>

<div class="image-container">
  <img src="hawaii.jpg" alt="Hawaii Island Paradise Image" class="portfolio-image first-image">
  <img src="molegame.png" alt="Whack a mole game Image" class="portfolio-image second-image">
</div>

<style>

 .image-container {
    display: flex;
    justify-content: center;
    gap: 20px;
    margin-top: 20px;
  }

  .portfolio-image {
    height: auto;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    transition: transform 0.3s ease-in-out;
  }

  .portfolio-image:hover {
    transform: scale(1.1);
  }

  .first-image {
    max-width: 300px;
  }

  .second-image {
    max-width: 750px;
  }

  h1, h2 {
    font-family: 'Poppins', sans-serif;
    font-weight: 600;
    color: #34495e;
    text-align: center;
    line-height: 1.4;
  }

  h1 {
    font-size: 2.5em;
    margin-top: 30px;
    margin-bottom: 10px;
  }

  h2 {
    font-size: 1.5em;
    margin-bottom: 30px;
    color: #34495e;
  }

  @media (max-width: 768px){
  .image-container{
    flex-direction: column;
    gap: 10px;
  }

  .portfolio-image{
    max-width: 90%;
  }

  h1{
    font-size: 2em;
  }

  h2{
    font-size: 1.2em;
  }
}

@media (max-width: 480px){
  h1{
    font-size: 1.8em;
  }

  h2{
    font-size: 1em;
  }
}
</style>