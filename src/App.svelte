<script lang="ts">
  import svelteLogo from './assets/svelte.svg'
  import viteLogo from '/vite.svg'
  import Counter from './lib/Counter.svelte'
  import { Router, Route } from "svelte-router";
  import Demo1 from "./views/demo/demo1.svelte";
  import Demo2 from "./views/demo/demo2.svelte";
  import Demo3 from "./views/demo/demo3.svelte";
  import Demo4 from "./views/demo/demo4.svelte";
  import Demo5 from "./views/demo/demo5.svelte";
  import Demo6 from "./views/demo/demo6.svelte";
  import Demo7 from "./views/demo/demo7.svelte";
  import Demo8 from "./views/demo/demo8.svelte";
  import Demo9 from "./views/demo/demo9.svelte";
  import Demo10 from "./views/demo/demo10.svelte";
  import Demo11 from "./views/demo/demo11.svelte";
  import Demo12 from "./views/demo/demo12.svelte";
  import Demo13 from "./views/demo/demo13.svelte";
  import Demo14 from "./views/demo/demo14.svelte";
  import Demo15 from "./views/demo/demo15.svelte";
  import Demo16 from "./views/demo/demo16.svelte";
  import Demo17 from "./views/demo/demo17.svelte";
</script>

<main>
  <div>
    <a href="https://vitejs.dev" target="_blank" rel="noreferrer">
      <img src={viteLogo} class="logo" alt="Vite Logo" />
    </a>
    <a href="https://svelte.dev" target="_blank" rel="noreferrer">
      <img src={svelteLogo} class="logo svelte" alt="Svelte Logo" />
    </a>
  </div>
  <h1>Vite + Svelte + Demo</h1>

  <div class="card">
    <Counter />
  </div>

  <p>
    Check out <a href="https://github.com/sveltejs/kit#readme" target="_blank" rel="noreferrer">SvelteKit</a>, the official Svelte app framework powered by Vite!
  </p>

  <p class="read-the-docs">
    Click on the Vite and Svelte logos to learn more
  </p>

  <Demo17 />
  <Demo16 />
  <Demo15 />
  <Demo14 />
  <Demo13 />
  <Demo12 />
  <Demo1 />
  <Demo2 />
  <Demo3 />
  <Demo4 />
  <Demo5 />
  <Demo6 />
  <Demo7 />
  <Demo8 />
  <Demo9 />
  <Demo10 />
  <Demo11 />

</main>

<style>
  .logo {
    height: 6em;
    padding: 1.5em;
    will-change: filter;
    transition: filter 300ms;
  }
  .logo:hover {
    filter: drop-shadow(0 0 2em #646cffaa);
  }
  .logo.svelte:hover {
    filter: drop-shadow(0 0 2em #ff3e00aa);
  }
  .read-the-docs {
    color: #888;
  }
</style>
