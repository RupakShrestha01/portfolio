<template>
  <section id="about">
    <h5>Get to Know</h5>
    <h2>About Me</h2>
    <div className="container about__container">
      <div className="about__me">
        <div className="about__me-image">
          <img alt="Vue logo" src="../assets/me.png" />
        </div>
      </div>

      <div className="about__content">
        <div className="about__cards">
          <article className="about__card">
            <h5>Experience</h5>
            <small>1+ Year Working</small>
          </article>
          <article className="about__card">
            <h5>Client</h5>
            <small>1+ Year Working</small>
          </article>
          <article className="about__card">
            <h5>Project</h5>
            <small>1+ Year Working</small>
          </article>
        </div>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolore quam
          quibusdam veritatis eius ab? Ipsum dolorum soluta necessitatibus rem
          laborum.
        </p>

        <a href="#contact" className="btn btn-primary"> Lets Talk </a>
      </div>
    </div>
  </section>
</template>

<script></script>

<style>
:root {
  --color-bg: #1f381f;
  --color-bg-variant: #2c2c6c;
  --color-primary: #4db5ff;
  --color-primary-variant: rgba(77, 181, 255, 0.4);
  --color-white: #fff;
  --color-light: rgba(255, 255, 255, 0.6);

  --container-width-lg: 75%;
  --container-width-md: 86%;
  --container-width-sm: 90%;
  --transition: all 400ms ease;
}
#about {
  margin-top: 5rem;
}
.about__container {
  display: grid;
  grid-template-columns: 35% 50%;
  gap: 15%;
}

.about__me {
  width: 100%;
  aspect-ratio: 1/1;
  border-radius: 2rem;
  background: linear-gradient(
    45deg,
    transparent,
    var(--color-primary),
    transparent
  );
  display: grid;
  place-items: center;
}

.about__me-image {
  border-radius: 2rem;
  overflow: hidden;
  transform: rotate(10deg);
  transition: var(--transition);
}

.about__me-image:hover {
  transform: rotate(0);
}

.about__cards {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 1.5rem;
}

.about__card {
  background: var(--color-bg-variant);
  border: 1px solid transparent;
  border-radius: 1rem;
  padding: 2rem;
  text-align: center;
  transition: var(--transition);
}

.about__card:hover {
  background: transparent;
  border-color: var(--color-primary-variant);
  cursor: default;
}

.about__icon {
  color: var(--color-primary);
  font-size: 1.4rem;
  margin-bottom: 1rem;
}

.about__card h5 {
  font-size: 0.95rem;
}

.about__card small {
  font-size: 0.7rem;
  color: var(--color-light);
}

.about__content p {
  margin: 2rem 0 2.6rem;
  color: var(--color-light);
}
</style>
