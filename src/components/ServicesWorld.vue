<template>
  <section id="services">
    <h5>What I Offer</h5>
    <h2>Services</h2>

    <div className="container services__container">
      <article className="service">
        <div className="service__head">
          <h3>UI/UX Design</h3>
        </div>

        <ul className="service__list">
          <li>
            <p>Lorem, ipsum dolor sit amet</p>
          </li>
          <li>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit.</p>
          </li>
          <li>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit.</p>
          </li>
          <li>
            <p>Lorem, ipsum dolor sit amet</p>
          </li>
          <li>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit.</p>
          </li>
          <li>
            ]
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit.</p>
          </li>
          <li>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit.</p>
          </li>
        </ul>
      </article>
      <!-- {/* End of UI/UX */} -->

      <article className="service">
        <div className="service__head">
          <h3>Web Development</h3>
        </div>

        <ul className="service__list">
          <li>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit.</p>
          </li>

          <li>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit.</p>
          </li>

          <li>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit.</p>
          </li>
          <li>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit.</p>
          </li>
          <li>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit.</p>
          </li>
          <li>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit.</p>
          </li>
          <li>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit.</p>
          </li>
          <li>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit.</p>
          </li>
        </ul>
      </article>
      <!-- {/* End of Web Development */} -->

      <article className="service">
        <div className="service__head">
          <h3>Content Creation</h3>
        </div>

        <ul className="service__list">
          <li>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit.</p>
          </li>
          <li>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit.</p>
          </li>
          <li>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit.</p>
          </li>
          <li>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit.</p>
          </li>
          <li>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit.</p>
          </li>
          <li>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit.</p>
          </li>
        </ul>
        <!-- {/* End of Content Creation */} -->
      </article>
    </div>
  </section>
</template>

<script></script>

<style>
.services__container {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 3rem;
}

.service {
  background: var(--color-bg-variant);
  border-radius: 0 0 2rem 2rem;
  border: 1px solid var(--color-primary);
  height: fit-content;
  transition: var(--transition);
}

.service:hover {
  background: transparent;
  background-color: var(--color-primary-variant);
  cursor: default;
}

.service__head {
  background: var(--color-primary);
  padding: 2rem;
  border-radius: 0 0 2rem 2rem;
  box-shadow: 0 2rem 1rem rgba(0, 0, 0, 0.1);
}

.service__head h3 {
  color: var(--color-bg);
  font-size: 1rem;
  text-align: center;
}

.service__list {
  padding: 2rem;
}

.service__list li {
  display: flex;
  gap: 1rem;
  margin-bottom: 0.8rem;
}

.service__list-icon {
  color: var(--color-primary);
  margin-top: 2px;
}

.service__list p {
  color: black;
  font-size: 0.9rem;
}
</style>
