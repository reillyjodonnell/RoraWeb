<script>
  import Nav from "./Nav.svelte";
  import Hero from "./Hero.svelte";
  import Services from "./Services.svelte";
  import About from "./AboutUs.svelte";
  import Recent from "./Recent.svelte";
  import Testimonials from "./Testimonials.svelte";
  import Footer from "./Footer.svelte";
  import Curve from "./Curve.svelte";
</script>

<main>
  <div class="background">
    <Nav />

    <Hero />
    <svg class="blob" viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg">
      <path
        fill="rgba(75, 52, 235, .1) "
        d="M47.1,-18C54.7,8.1,50.1,35.4,35.3,45.5C20.4,55.6,-4.8,48.4,-28,32.9C-51.2,17.4,-72.4,-6.5,-67.4,-29C-62.4,-51.5,-31.2,-72.7,-5.7,-70.8C19.8,-69,39.5,-44.1,47.1,-18Z"
        transform="translate(100 100)"
      />
    </svg>
    <svg
      class="blob-2"
      viewBox="0 0 200 200"
      xmlns="http://www.w3.org/2000/svg"
    >
      <path
        fill="rgba(77, 189, 188, .1)"
        d="M42.8,-42.2C49.2,-26.2,43.8,-8.7,37.7,4.8C31.6,18.3,24.8,27.9,13.7,36.4C2.5,44.9,-13.1,52.2,-31.5,49.5C-49.9,46.7,-71.2,33.9,-72,19.5C-72.9,5.1,-53.4,-11,-37.9,-29.1C-22.5,-47.2,-11.3,-67.4,3.5,-70.2C18.2,-73,36.5,-58.3,42.8,-42.2Z"
        transform="translate(100 100)"
      />
    </svg>
    <svg class="wave" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"
      ><path
        fill="rgb(247, 247, 247)"
        fill-opacity="1"
        d="M0,128L48,144C96,160,192,192,288,218.7C384,245,480,267,576,277.3C672,288,768,288,864,240C960,192,1056,96,1152,69.3C1248,43,1344,85,1392,106.7L1440,128L1440,320L1392,320C1344,320,1248,320,1152,320C1056,320,960,320,864,320C768,320,672,320,576,320C480,320,384,320,288,320C192,320,96,320,48,320L0,320Z"
      /></svg
    >
  </div>

  <Services />
  <About />
  <Recent />
  <Testimonials />
  <Footer />
</main>

<style>
  .background {
    background: linear-gradient(
      47deg,
      rgba(75, 52, 235, 1) 0%,
      rgba(83, 134, 236, 1) 44%,
      rgba(77, 189, 188, 1) 100%
    );

    position: relative;
    margin: auto 0;

    overflow: hidden;
    /*border-radius: 0 0 80% 80% / 150px;*/
    width: 100vw;
    height: 1100px;
  }
  .blob {
    position: absolute;
    top: 50px;
    right: 50px;
    z-index: 1;
    width: 800px;
  }
  .blob-2 {
    position: absolute;
    top: 300px;
    right: 600px;
    z-index: 1;
    width: 600px;
  }
  .wave {
    position: absolute;
    bottom: 0;
    width: 100vw;
    left: 0;
    right: 0;
  }

  main {
    text-align: center;
    max-width: 240px;
    margin: 0 auto;
  }

  @media (min-width: 640px) {
    main {
      max-width: none;
    }
  }
</style>
