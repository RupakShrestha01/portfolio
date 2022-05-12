<template>
  <section id="experiences">
    <h5>What Skills I Have</h5>
    <h2>My Experience</h2>
    <div className="container experience__container">
      <div className="experience__frontend">
        <h3>Frontend Development</h3>
        <div className="experience__content">
          <article className="experience__details">
            <div>
              <h4>HTML</h4>
              <small className="text-light">Learner</small>
            </div>
          </article>
          <article className="experience__details">
            <div>
              <h4>CSS</h4>
              <small className="text-light">Apprentice</small>
            </div>
          </article>
          <article className="experience__details">
            <div>
              <h4>JavaScript</h4>
              <small className="text-light">Newcomer</small>
            </div>
          </article>
          <article className="experience__details">
            <div>
              <h4>Tailwind</h4>
              <small className="text-light">Freshman</small>
            </div>
          </article>
          <article className="experience__details">
            <div>
              <h4>React</h4>
              <small className="text-light">Starter</small>
            </div>
          </article>
        </div>
      </div>

      <!-- {/* End Of forntend */} -->

      <div className="experience__backend">
        <h3>Backend Development</h3>
        <div className="experience__content">
          <article className="experience__details">
            <div>
              <h4>Node JS</h4>
              <small className="text-light">Learner</small>
            </div>
          </article>
          <article className="experience__details">
            <div>
              <h4>MongoDB</h4>
              <small className="text-light">Newcomer</small>
            </div>
          </article>
          <article className="experience__details">
            <div>
              <h4>PHP</h4>
              <small className="text-light">Learner</small>
            </div>
          </article>
          <article className="experience__details">
            <div>
              <h4>MySql</h4>
              <small className="text-light">Newcomer</small>
            </div>
          </article>
          <article className="experience__details">
            <div>
              <h4>Python</h4>
              <small className="text-light">Learner</small>
            </div>
          </article>
        </div>
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
h4 {
  color: black;
}
.experience__container {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 2rem;
}

.experience__container > div {
  background: var(--color-bg-variant);
  padding: 2.4rem 5rem;
  border-radius: 2rem;
  border: 1px solid transparent;
}

.experience__container > div:hover {
  background: transparent;
  border-color: var(--color-primary-variant);
  cursor: default;
}

.experience__container > div h3 {
  text-align: center;
  margin-bottom: 2rem;
  color: var(--color-primary);
}

.experience__content {
  display: grid;
  grid-template-columns: 1fr 1fr;
  row-gap: 2rem;
}

.experience__details {
  display: flex;
  gap: 2rem;
  margin-left: 3rem;
}

.experience__details-icons {
  margin-top: 6px;
  color: var(--color-primary);
}
</style>
