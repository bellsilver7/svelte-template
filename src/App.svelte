<script lang="ts">
  import svelteLogo from './assets/svelte.svg'
  import typescriptLogo from './assets/typescript.svg'
  import tailwindcssLogo from './assets/tailwindcss.svg'
</script>

<main>
  <h1 class="text-3xl font-bold underline bg-red-400">
    Hello world!
  </h1>
  <div>
    <a href="https://vitejs.dev" target="_blank"> 
      <img src="/vite.svg" class="logo" alt="Vite Logo" />
    </a>
    <a href="https://svelte.dev" target="_blank"> 
      <img src={svelteLogo} class="logo svelte" alt="Svelte Logo" />
    </a>
    <a href="https://typescript.dev" target="_blank"> 
      <img src={typescriptLogo} class="logo typescript" alt="Typescript Logo" />
    </a>
    <a href="https://tailwindcss.dev" target="_blank"> 
      <img src={tailwindcssLogo} class="logo tailwindcss" alt="TailwindCSS Logo" />
    </a>
  </div>
  <h1>Vite + Svelte + Typescript + TailwindCSS</h1>
</main>

<style>
  .logo {
    height: 6em;
    padding: 1.5em;
    will-change: filter;
  }
  .logo:hover {
    filter: drop-shadow(0 0 2em #646cffaa);
  }
  .logo.svelte:hover {
    filter: drop-shadow(0 0 2em #ff3e00aa);
  }
  .logo.typescript:hover {
    filter: drop-shadow(0 0 2em #007accaa);
  }
  .logo.tailwindcss:hover {
    filter: drop-shadow(0 0 2em #00bfa5aa);
  }
</style>