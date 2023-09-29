<script setup></script>

<template>
  <section id="experience">
    <p class="section__text__p1"></p>
    <h1 class="title">Experience</h1>
    <div class="experience-details-container">
      <div class="about-containers">
        <div class="details-container">
          <h2 class="experience-sub-title">Frontend Development</h2>
          <div class="article-container">
            <article>
              <img
                src="https://logos-download.com/wp-content/uploads/2017/07/HTML5_badge.png"
                alt="Experience icon"
                class="icon"
              />
              <div>
                <h3>HTML</h3>
                <p></p>
              </div>
            </article>
            <article>
              <img
                src="https://th.bing.com/th/id/R.12644856e97889db8644e1c8cac2a426?rik=K1L5Z4p4p5pXUA&riu=http%3a%2f%2fbenjaminfevrat.com%2fpictures%2ftechnos_logo%2fcss_logo.png&ehk=eB%2bU19LWYMMG1m%2bGIInA%2bXGa6TI2yDz%2f8FJ08iKSX00%3d&risl=&pid=ImgRaw&r=0"
                alt="Experience icon"
                class="icon"
              />
              <div>
                <h3>CSS</h3>
                <p></p>
              </div>
            </article>
            <article>
              <img
                src="https://miro.medium.com/max/1024/1*9U1toerFxB8aiFRreLxEUQ.png"
                alt="Experience icon"
                class="icon"
              />
              <div>
                <h3>JavaScript</h3>
                <p></p>
              </div>
            </article>
            <article></article>
          </div>
        </div>
        <div class="details-container">
          <h2 class="experience-sub-title">Backend Development</h2>
          <div class="article-container">
            <article>
              <img
                src="https://th.bing.com/th/id/R.bab2c760c60f17191cb3a002e08a3dbf?rik=zJoEjAb2we9vbQ&pid=ImgRaw&r=0"
                alt="Experience icon"
                class="icon"
              />
              <div>
                <h3>SQL</h3>
                <p></p>
              </div>
            </article>
            <article>
              <img
                src="https://th.bing.com/th/id/R.093bd57c711ea2f031fb4579f9da9547?rik=BkDQC6mdRxAxOA&pid=ImgRaw&r=0"
                alt="Experience icon"
                class="icon"
              />
              <div>
                <h3>Node JS</h3>
                <p></p>
              </div>
            </article>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
#experience {
  position: relative;
}

.icon {
  cursor: pointer;
  height: 2rem;
}

.experience-sub-title {
  color: rgb(22, 135, 155);
  font-weight: 600;
  font-size: 1.75rem;
  margin-bottom: 2rem;
}

.experience-details-container {
  display: flex;
  justify-content: center;
  flex-direction: column;
}

.article-container {
  display: flex;
  text-align: initial;
  flex-wrap: wrap;
  flex-direction: column;
  gap: 1.5rem;
  justify-content: space-around;
}

article {
  display: flex;
  width: 10rem;
  justify-content: space-around;
  gap: 0.7rem;
}

article .icon {
  cursor: default;
}
p {
  color: rgb(85, 85, 85);
}
.title {
  font-size: 3rem;
  text-align: center;
}
</style>
