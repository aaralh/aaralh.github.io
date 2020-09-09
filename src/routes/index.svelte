<style>
  .content {
    overflow: visible;
  }
  .content__info {
    display: flex;
    flex-direction: row;
    height: 250px;
    justify-content: space-evenly;
    align-items: center;

	margin-top: 2.5em;
	margin-bottom: 8.5em;
  }
  .content__image {
    height: 100%;
  }

  .content__image > img {
    height: 100%;
    border-radius: 100%;
  }
</style>

<svelte:head>
  <title>Aaro Alhainen</title>
</svelte:head>

<div class="content">
  <div class="content__info">

    <div class="content__image">
      <img alt="Here I am" src="profile.jpg" />
    </div>
    <div class="content__info__contact">
      <h1 class="name">Aaro Alhainen</h1>
      <div class="job_title">Software Developer</div>
      <div class="email">aaro.alhainen@gmail.com</div>
    </div>
  </div>
  <div class="content__content">
    <h2>Who I am?</h2>
    <p>
      Hi, I'm Aaro Alhainen - a Software Developer and CS student from Joensuu,
      Finland. I'm on fourth year on my studies and have been working in
      industry for two and half years. I'm currently a Software Developer in a
      company that creates solutions in field of Industrial IoT.
    </p>
	<br>
    <h2>My skills?</h2>
    <p>
      I have broad Full Stack experience with technologies like Vue.js, NodeJS,
      Nginx, Apache, PHP and MySQL. For JavaScript development I prefer
      TypeScript but do frequently Vanilla JS when needed. In addition to Full
      Stack I have also done mobile development for Android and iOS with Swift,
      Java and Flutter with different kind of Back-Ends. Other strong language
      is Python which I use mostly with data processing and Neural
      Networks/Machine Learning with Keras and TensorFlow.
    </p>
	<br>
    <h2>What I do in my free time?</h2>
    <p>
      I'm eager to learn new things and train my self to be a better developer.
      My long time point of interest have been Machine Learning/Artificial
      inteligence in general and recently also low level development with
      language like Rust. I will add some of the projects to Projects section
      with some text. My other free time projects can be found from my Github.
    </p>
  </div>
</div>
