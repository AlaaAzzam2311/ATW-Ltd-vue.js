<template>
  <div class="project">
    <h1 class="header">Our <br />Projects</h1>
      <div class="images">
        <div class="imgs">
          <img class="img" width="500px,'src/assets/images&icons&vectors/image1.png'" />
          <p class="img-title">Minify - Web Design</p>
          <div class="img-details">
            <p class="study-case">
              <img src="src\assets\images&icons&vectors\icon1.png" alt="layers icon" />View
              Study Case
            </p>
            <p class="live-preview">
              <img src="src\assets\images&icons&vectors\icon2.png" alt="show icon" />Live
              Preview
            </p>
          </div>
        </div>
        <div class="imgs">
          <img class="img" src="src\assets\images&icons&vectors\image2.png" />
          <p class="img-title">Ant - Personal Portofolio</p>
          <div class="img-details">
            <p class="study-case">
              <img src="src\assets\images&icons&vectors\icon1.png" alt="layers icon" />View
              Study Case
            </p>
            <p class="live-preview">
              <img src="src\assets\images&icons&vectors\icon2.png" alt="show icon" />Live
              Preview
            </p>
          </div>
        </div>
        <div class="imgs">
          <img class="img" src="src\assets\images&icons&vectors\image 3.png" />
          <p class="img-title">Lumy - Dashboard UI Kit</p>
          <div class="img-details">
            <p class="study-case">
              <img src="src\assets\images&icons&vectors\icon1.png" alt="layers icon" />View
              Study Case
            </p>
            <p class="live-preview">
              <img src="src\assets\images&icons&vectors\icon2.png" alt="show icon" />Live
              Preview
            </p>
          </div>
        </div>
        </div>
        <div class="imgs">
          <img class="img" src="src\assets\images&icons&vectors\image 4.png" />
          <p class="img-title">Keeper - Soccer Site</p>
          <div class="img-details">
            <p class="study-case">
              <img src="src\assets\images&icons&vectors\icon1.png" alt="layers icon" />View
              Study Case
            </p>
            <p class="live-preview">
              <img src="src\assets\images&icons&vectors\icon2.png" alt="show icon" />Live
              Preview
            </p>
          </div>
        </div>
       <div class="contact-div">
        <h1 class="contact-heading">
          Interested working<br />
          with me?
        </h1>
        <div class="email-container">
          <img src="src\assets\images&icons&vectors\mailmail.png" alt="icon" />Email Me
        </div>
      </div>
      <div class="foot-icons">
        <img class="instgram" src="src\assets\images&icons&vectors\Instagram - Negative.png" alt="icon" />
        <img class="youtube" src="src\assets\images&icons&vectors\Vectoryoutube.png" alt="icon" />
        <img class="kora" src="src\assets\images&icons&vectors\Vectordribble.png" alt="icon" />
      </div>
      <div class="back-to-top-container">
        <p>Back to Top</p>
        <a class="back-to-top" href="#">
          <img src="src\assets\images&icons&vectors\short_uparrow.png" />
        </a>
      </div>
  </div>
</template>
<script>

export default {
  name: "project-view",
  methods: {
    getImageSrc(imageName) {
      return `../../assets/${imageName}`;
    },
  },
};
</script>
