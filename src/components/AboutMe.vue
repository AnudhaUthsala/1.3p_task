<script setup></script>

<template>
  <section id="about" style="margin-top: 40px">
    <p class="section__text__p1"></p>
    <h1 class="title">About Me</h1>
    <div class="section-container">
      <div class="section__pic-container">
        <img
          src="https://cdn-icons-png.flaticon.com/512/1484/1484861.png"
          alt="Profile picture"
          class="about-pic"
        />
      </div>
      <div class="about-details-container">
        <div class="about-containers">
          <div class="details-container">
            <img
              src="https://www.freeiconspng.com/uploads/experience-logo-company-infographic-management-organization-business-computer-icons-0.png"
              alt="Experience icon"
              class="icon"
            />
            <h3>Experience</h3>
            <p>2+ years <br />Game Development</p>
          </div>
          <div class="details-container">
            <img
              src="https://www.pngkey.com/png/full/131-1311026_school-icon-png.png"
              alt="Education icon"
              class="icon"
            />
            <h3>Education</h3>
            <p>Bachelor of IT<br /></p>
          </div>
        </div>
        <div class="text-container">
          <p>
            I'm Anudha Uthsala.currently, I'm an undergraduate at the Deakin
            University and I'm studying Application Development. Game
            Development | Javascript | C++ | Python, Java
          </p>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
#about {
  position: relative;
}

.about-containers {
  gap: 2rem;
  margin-bottom: 2rem;
  margin-top: 2rem;
}

.about-details-container {
  justify-content: center;
  flex-direction: column;
}

.about-containers,
.about-details-container {
  display: flex;
}

.about-pic {
  border-radius: 2rem;
}
.icon {
  cursor: pointer;
  height: 2rem;
}

.arrow {
  position: absolute;
  right: -5rem;
  bottom: 2.5rem;
}

p {
  color: rgb(85, 85, 85);
}
.title {
  font-size: 3rem;
  text-align: center;
}
</style>
