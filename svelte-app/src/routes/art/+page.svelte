<link rel="stylesheet" href="/styles/global.css" />

<div class="portfolio-container">
  <div class="image-section">
    <div class="image-with-text">
      <img src="turnaround.png" alt="Character Rigging" class="portfolio-image">
      <div class="text-section">
        <h3>Character Rigging</h3>
        <p>Here is one drawing I done for my rigging process in my 2D digital art. I was to create a character, draw how they would look while facing different directions, and later rig the character. I found drawing the character a much easier task than rigging the actual character later in the project.</p>
      </div>
    </div>
    <div class="image-with-text">
      <img src="characterbackground.png" alt="Background" class="portfolio-image">
      <div class="text-section">
        <h3>Background</h3>
        <p>This is an example of the background created to accompany the character rigging project. The design reflects the setting for the character's story. I enjoy making simple cartoonish art pieces like this one, it does be quite a fun process.</p>
      </div>
    </div>
    <div class="image-with-text">
      <img src="weirdanimal.png" alt="Photoshop Skills" class="portfolio-image">
      <div class="text-section">
        <h3>Photoshop Skills</h3>
        <p>Here, I experimented with Photoshop techniques to create a unique animal design. I'm not too sure what my thought process was behind creating the creature, but now it exists deal with it. Yes I know, he lives on the moon!</p>
      </div>
    </div>
  </div>
</div>

<style>
  .portfolio-container {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 20px;
    margin-top: 20px;
  }

  .image-section {
    display: flex;
    flex-direction: column;
    gap: 30px;
    width: 100%;
  }

  .image-with-text {
    display: flex;
    align-items: flex-start;
    gap: 40px;
  }

  .portfolio-image {
    height: auto;
    width: 600px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    transition: transform 0.3s ease;
  }

  .portfolio-image:hover {
    transform: scale(1.1);
  }

  .text-section {
    max-width: 600px;
    text-align: left;
    background-color: rgba(173, 216, 230, 0.6);
    padding: 15px;
    border-radius: 10px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  }

</style>