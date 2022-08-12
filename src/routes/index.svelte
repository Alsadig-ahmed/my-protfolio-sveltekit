<script lang="ts">
  let cat = "cat";
</script>

<h1 class='text-4xl'>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
<p>alsadig profoloi <a href="https://alsadig-ahmed.netlify.app">alsadig.ahmed.netlify.app</a></p>

<style lang="scss">
    a{
        @apply text-blue-700  text-xl;
        &:hover{
            @apply text-red-400 ;
        }
    }
  h1 {
    $v: red;
    background-color: $v;
  }
</style>
