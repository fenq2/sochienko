<template>
  <header class="header">
    <a href="#top" class="link">
      <div class="avatar-icon">
        <img src="./assets/avatar.jpg" alt="My photo" width="16" height="16" />
      </div>
      <span>Serhii Sochienko</span>
    </a>

    <a href="#" class="link">
      <span>🖨️ Download PDF</span>
    </a>
  </header>
  <section class="banner" id="top">
    <img
      src="https://images.unsplash.com/photo-1581276879432-15e50529f34b?ixlib=rb-1.2.1&q=85&fm=jpg&crop=entropy&cs=srgb&w=6000"
      alt="Code banner"
    />
  </section>
  <main class="main">
    <div class="logo">
      <img src="./assets/avatar.jpg" alt="My photo" width="124" height="124" />
    </div>
    <h1 class="name">Serhii Sochienko</h1>
    <p class="position">Frontend Engineer</p>

    <section class="section">
      <h2 class="sectionTitle">Personal info</h2>
      <div class="sectionContent">
        <ul>
          <li>Lviv, Ukraine</li>
          <li>Mobile: <a href="tel:+380663488092">+38(066) 348 80 92</a></li>
          <li>Email: <a href="mailto:fenzqr@gmail.com">fenzqr@gmail.com</a></li>
          <li>
            LinkedIn:
            <a href="https://www.linkedin.com/in/finchdev/" target="_blank">Serhii Sochienko</a>
          </li>
          <li>GitHub: <a href="https://github.com/fenq2" target="_blank">@fenq2</a></li>
        </ul>
      </div>
    </section>

    <section class="section">
      <h2 class="sectionTitle">👨‍💻 Summary</h2>
      <div class="sectionContent">
        <ul>
          <li>3+ years in Frontend Development building single page applications</li>
          <li>
            Product-oriented mindset: not just write a code — find and deliver the best solutions
            needed for business
          </li>
          <li>Passionate in processes and people management</li>
          <li>Attentive to the details and care about UX in interfaces</li>
          <li>Experience in Frontend Mentoring</li>
        </ul>
      </div>
    </section>

    <section class="section">
      <h2 class="sectionTitle">🛠 Technical Skills</h2>
      <div class="sectionContent">
        <ul>
          <li>JavaScript (ES2015+), TypeScript</li>
          <li>React, NextJS, Storybook, i18n</li>
          <li>CSS, BEM, CSS Modules, SASS, Styled Components</li>
          <li>HTML, template engines, static site generators</li>
          <li>Unit / e2e testing, TDD, Jest, Playwright</li>
          <li>Production monitoring, Sentry, Grafana</li>
          <li>CI/CD, Git</li>
          <li>NodeJS, NestJS</li>
        </ul>
      </div>
    </section>

    <section class="section">
      <h2 class="sectionTitle">💼 Work Experience</h2>
      <div class="sectionContent">
        <div class="work">
          <div class="workInfo">
            <span class="workHeading">Feb 2023 - now</span>
            <h3 class="workHeading">Frontend Engineer</h3>
            <p class="workPlace">
              <a href="https://amo.tech/" target="_blank">@amo.tech</a>
            </p>
          </div>
          <div class="workContent">
            <p class="text">
              Work on one the health&fitness product HARNA. My responsibilities include development
              and support core features related to payments, subscriptions, various admin panels to
              optimise the development process. Our frontend team is not large, so a big chance you
              will see interfaces created by me.
            </p>
            <div class="text">
              Participated in all feature development phases:
              <p>- understanding customer pains,</p>
              <p>- helping business find a solution,</p>
              <p>- implementing them in interfaces,</p>
              <p>- A/B testing,</p>
              <p>- production monitoring,</p>
              <p>- etc.</p>
            </div>
            <p class="text">The main stack was NextJS, TypeScript, Storybook, Jest, Solidgate.</p>
          </div>
        </div>
        <span class="divider" />
        <div class="work">
          <div class="workInfo">
            <span class="workHeading">Dec 2021 - Jan 2023</span>
            <h3 class="workHeading">Frontend Engineer</h3>
            <p class="workPlace">
              <a href="https://www.halo-lab.com/" target="_blank">@halolab</a>
            </p>
          </div>
          <div class="workContent">
            <p class="text">
              HALO - is design-driven product development company, providing full-stack: Design,
              Development & Marketing services. My responsibilities included the development of a UI
              dashboard library for the creation of a personal business card page. Participated in
              the development of features using OpenAI and DALLE APIs.
            </p>
            <div class="text">
              Major achievements:
              <p>
                – gave an online tech talk on "storybook" and "optimization react components" as a
                speaker,
              </p>
              <p>
                – successfully created design library for the project (rollup configuration, npm
                deploy),
              </p>
              <p>
                – for some time as a mentor on a project for new developers, conducted code review,
              </p>
            </div>
            <p class="text">
              The main stack was React, Redux, TypeScript, JSS, Scss modules, Storybook, Git.
            </p>
          </div>
        </div>
        <span class="divider" />
        <div class="work">
          <div class="workInfo">
            <span class="workHeading">Jul 2021 - Dec 2021</span>
            <h3 class="workHeading">Frontend Engineer</h3>
            <p class="workPlace">
              <a href="https://www.halo-lab.com/" target="_blank">@merehead</a>
            </p>
          </div>
          <div class="workContent">
            <p class="text">
              HALO - is Blockchain Development Company. My responsibilities included the development
              of a UI dashboard library for the creation of a personal business card page.
              Participated in the development of features using OpenAI and DALLE APIs.
            </p>
            <p class="text">
              Worked on different projects: landing pages, dashboards, company websites. Developed
              expertise in the React library and used it to create scalable and reusable interfaces.
            </p>
            <p class="text">The main stack was HTML, Scss, JavaScript, React, Git</p>
          </div>
        </div>
        <span class="divider" />
        <div class="work">
          <div class="workInfo">
            <span class="workHeading">Mar 2020 - Jul 2021</span>
            <h3 class="workHeading">HTML Coder</h3>
            <p class="workPlace">
              <span>@freelance</span>
            </p>
          </div>
          <div class="workContent">
            <p class="text">
              First experience in web development was creating simple static web sites using HTML,
              CSS and JavaScript as a freelancer. Successfully completed more than 100 orders
            </p>
          </div>
        </div>
      </div>
    </section>

    <section class="section">
      <h2 class="sectionTitle">🎓 Education</h2>
      <div class="sectionContent">
        <div class="info">
          <p>Years: 2022 – 2023</p>
          <p>Degree: Master</p>
          <p>
            Alma mater:
            <a href="https://donntu.edu.ua/en/donetsk-national-technical-university" target="_blank"
              >Donetsk National Technical University</a
            >
          </p>
          <p>Major: Electronic systems</p>
        </div>
        <span class="divider" />
        <div class="info">
          <p>Years: 2018 – 2021</p>
          <p>Degree: Bachelor</p>
          <p>
            Alma mater:
            <a href="https://donntu.edu.ua/en/donetsk-national-technical-university" target="_blank"
              >Donetsk National Technical University</a
            >
          </p>
          <p>Major: Electronic systems</p>
        </div>
      </div>
    </section>

    <section class="section">
      <h2 class="sectionTitle">🌎 Languages</h2>
      <div class="sectionContent">
        <ul>
          <li>Ukrainian - Native</li>
          <li>English - A2 (Pre-Intermidiate)</li>
        </ul>
      </div>
    </section>
  </main>
</template>

<style src="./App.css" />
