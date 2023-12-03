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
      <div class="job_title">Full Stack Developer and Web Browser Engineer</div>
    </div>
  </div>
  <div class="content__content">
  <h2>👨‍🔧About Me</h2>
  <p>Welcome to my personal website!👋 I'm Aaro Alhainen, a passionate and versatile Software Developer and Web Browser Engineer based in Helsinki, Finland. I have been working in the software industry since 2017 and currently I'm employed by a company that offers a world leading Sales Acceleration Platform. In my spare time, I'm also developing my own web browser project, tentatively named theBrowser (I'm still working on a better name😅).</p>
  <br/>
  <h2>🛠️My Skills</h2>
  <p>I have extensive Full Stack experience with various technologies, such as <strong>Vue.js</strong>, <strong>NodeJS</strong>, <strong>Python</strong>, <strong>Django</strong>, <strong>Nginx</strong>, <strong>Apache</strong>, and <strong>MySQL</strong> . For JavaScript development, I prefer <strong>TypeScript</strong> but I also use <strong>Vanilla JS</strong> when needed. Besides Full Stack, I have also done mobile development for <strong>Android</strong> and <strong>iOS</strong> with <strong>Swift</strong>, <strong>Java/Kotlin</strong>, and <strong>Flutter</strong>, integrating different kinds of Back-End solutions. For data processing and Neural Networks/Machine Learning I have used to do with <strong>Pandas</strong>, <strong>PyTorch</strong> and <strong>TensorFlow</strong>.</p>
  <br/>
  <h2>🏡My Hobbies</h2>
  <p>I'm always eager to learn new things and improve myself as a developer. My long-term interest has been Machine Learning/Artificial Intelligence in general and recently I have also explored functional programming with languages like <strong>Clojure</strong>. I will share some of my projects and insights in the Projects section (coming soon™️). You can also check out my other coding-related projects on my <a href="https://github.com/aaralh">GitHub</a> .</p>
<p>Apart from coding, I enjoy reading📚, listening to books🎧, taking walks🚶‍♂️ and bouldering🧗‍♂️ with my friends. For the year 2023, I set a goal to read more books and so far I have been successful in keeping up the habit.</p></div>
</div>
