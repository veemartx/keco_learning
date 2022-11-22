<script>
  import { Router, Route } from "svelte-navigator";
  import { fade, fly } from "svelte/transition";
  import Footer from "./components/Footer.svelte";
  import Header from "./components/Header.svelte";
  import Sticky from "./components/Sticky.svelte";
  import About from "./routes/About.svelte";
  import Landing from "./routes/Landing.svelte";

  let y;

  $: {
    console.log(y);
  }
</script>

<main>
  <div class="header">
    {#if y < 40}
      <Header />
    {:else}
      <div in:fly={{ y: 10, duration: 2 }} out:fade class="stickyNav">
        <Sticky />
      </div>
    {/if}
  </div>
  <div class="mainContentContainer">
    <Router>
      <Route path="/">
        <Landing />
      </Route>

      <Route path="/about">
        <About />
      </Route>
    </Router>
  </div>
  <div class="footer">
    <Footer />
  </div>
</main>
<svelte:window bind:scrollY={y} />

<style>
  .stickyNav {
    position: fixed;
    top: 0;
    left: 0;
    width: 100vw;
  }
</style>
