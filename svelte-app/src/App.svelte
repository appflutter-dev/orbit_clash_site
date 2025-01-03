<script>
  import "./styles/global.css";
  import Header from "./components/Header.svelte";
  import Downloads from "./components/Downloads.svelte";
  import Legal from "./components/Legal.svelte";
  import PrivacyPolicy from "./components/PrivacyPolicy.svelte";
  import GdprNotice from "./components/GdprNotice.svelte";
</script>

<Header />
<main>
  <section class="about">
    <h2>Orbit Clash</h2>
    <div class="short-description">
      <h3>
        Defend your planet by controlling a spaceship to collide with and
        deflect asteroids!
      </h3>
    </div>
    <div class="detailed-description">
      <p>Embark on an epic cosmic journey with Orbit Clash!</p>
      <p>
        In this immersive mobile game, you’re tasked with protecting your planet
        from deadly asteroids. Pilot a spaceship in orbit, harnessing the power
        of physics to alter its speed and trajectory. Use your ship to collide
        with and deflect asteroids, ensuring your planet's survival in the vast
        depths of space.
      </p>
      <p>
        Experience dynamic gameplay that blends strategy and action as you
        calculate your ship’s movements and react quickly to new asteroid
        threats. Every decision matters: change your orbit, adjust your speed,
        and decide how to tackle the next challenge.
      </p>
    </div>
    <div class="features">
      <h3>Features</h3>
      <ul>
        <li>
          Thrilling gameplay: Control an orbiting spaceship to defend your
          planet from destruction.
        </li>
        <li>
          Strategic mechanics: Adjust trajectory and speed to collide with
          asteroids at the right time.
        </li>
        <li>
          Immersive visuals: Enjoy stunning cosmic landscapes and fluid
          animations.
        </li>
        <li>
          Progressive difficulty: Face increasingly challenging waves of
          asteroids.
        </li>
      </ul>
    </div>
  </section>
  <Downloads />
  <PrivacyPolicy />
  <GdprNotice />
  <Legal />
</main>

<style>
  .about {
    max-width: 800px;
    margin: 2rem auto;
    padding: 2rem;
    background: #f9f9f9;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  }

  .about h2 {
    text-align: center;
    color: #4caf50;
    margin-bottom: 1rem;
  }

  .short-description {
    text-align: center;
    margin-bottom: 2rem;
  }

  .short-description h3 {
    color: #333;
    font-size: 1.25rem;
  }

  .detailed-description {
    margin-bottom: 2rem;
  }

  .detailed-description p {
    line-height: 1.6;
    margin-bottom: 1rem;
  }

  .features {
    margin-top: 2rem;
  }

  .features h3 {
    color: #4caf50;
    margin-bottom: 1rem;
  }

  .features ul {
    list-style-type: disc;
    padding-left: 1.5rem;
  }

  .features li {
    margin-bottom: 0.5rem;
    line-height: 1.6;
  }
</style>
