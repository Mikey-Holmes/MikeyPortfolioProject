<link rel="stylesheet" href="/styles/global.css" />

<div class="cv-container">
  <img src="cv.png" alt="my CV" />
</div>

<style>
.cv-container {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  background-color: #eef2f5;
}

.cv-container img {
  max-width: 80%;
  max-height: 80%;
  border: 5px solid #4a90e2;
  border-radius: 20px;
  box-shadow: 0 8px 16px rgba(0, 0, 0, 0.25);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.cv-container img:hover {
  transform: scale(1.05);
  box-shadow: 0 12px 24px rgba(0, 0, 0, 0.3);
}

 @media (max-width: 768px){
   .cv-container {
    height: auto; 
    padding: 20px;
  }

  .cv-container img{
     max-width: 90%; 
     max-height: 70%; 
  }
 }

 @media (max-width: 480px){
  .cv-container {
    padding: 10px; 
  }

  .cv-container img{
    max-width: 100%; 
    max-height: auto; 
   }
 }
</style>