<style>
  .content {
    overflow: visible;
  }
  .content__info {
    display: grid;
    grid-template-columns: 1fr minmax(250px, 1fr);
    column-gap: 15px;
    align-items: center;
    justify-items: center;
    margin-top: 2.5em;
    margin-bottom: 8.5em;
  }

  .content__image {
    height: 250px;
    overflow: hidden;
    justify-self: self-end;
  }

  .content__image > img {
    height: 100%;
    border-radius: 100%;
  }

  @media only screen and (max-width: 470px) {
    .content__info {
      grid-template-columns: 1fr minmax(200px, 2fr);
    }

    .content__image {
      height: 170px;
    }
  }

  span {
    white-space: nowrap;
  }
</style>

<svelte:head>
  <title>Aaro Alhainen | Software Developer</title>
</svelte:head>

<div class="content">
  <div class="content__info">

    <div class="content__image">
      <img alt="Here I am" src="profile.jpeg" />
    </div>
    <div class="content__info__contact">
      <h1 class="name">Aaro Alhainen</h1>
      <div class="job_title">Full Stack Developer and CS student</div>
    </div>
  </div>
  <div class="content__content">
    <h2>👨‍🔧Who I am?</h2>
    <p>
      Hi, I'm Aaro Alhainen - a Software Developer and CS student from Helsinki,
      Finland. I have been working in the industry since 2017
      and currently I'm a Software Developer in a company which provides world 
      leading Sales Acceleration Platform. Alongside my work, I'm pushing my final CS
      studies forward.
    </p>
    <br />
    <h2>🛠️My skills?</h2>
    <p>
      I have broad Full Stack experience with technologies like
      <strong>Vue.js</strong>
      ,
      <strong>NodeJS</strong>
      ,
      <strong>Nginx</strong>
      ,
      <strong>Apache</strong>
      ,
      <strong>PHP</strong>
      , and
      <strong>MySQL</strong>
      . For
      <strong>JavaScript</strong>
      development I prefer
      <strong>TypeScript</strong>
      but do frequently Vanilla JS when needed. In addition to Full Stack, I have
      also done mobile development for
      <strong>Android</strong>
      and
      <strong>iOS</strong>
      with
      <strong>Swift</strong>
      ,
      <strong>Java</strong>
      , and
      <strong>Flutter</strong>
      with different kinds of Back-End solutions. Another strong language is
      <strong>Python</strong>
      which I use mostly with data processing and Neural Networks/Machine
      Learning with Keras and TensorFlow.
    </p>
    <br />
    <h2>🏡How about my free time?</h2>
    <p>
      I'm eager to learn new things and train myself to be a better developer.
      My long time point of interest have been Machine Learning/Artificial
      intelligence in general and recently also functional programming with
      language like
      <strong>Clojure</strong>
      . I will add some of the projects to the Projects section(coming soon™️) with
      some insights. My other coding-related projects can be found in my
      <a href="https://github.com/aaralh" target="_blank" rel="noopener">
        GitHub
      </a>
      .
    </p>
    <p>
      Besides coding and studies, I like to
      <span>read📚,</span>
      listen to
      <span>books🎧,</span>
      take
      <span>walks🚶‍♂️</span>
      and go
      <span>boulder🧗‍♂️</span>
      with my friends. For the year 2020, I set a goal to read more and it has been
      successful and I'm trying to keep the habit going.
    </p>
  </div>
</div>
