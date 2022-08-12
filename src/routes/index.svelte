<script lang="ts">
  let cat = "cat";
</script>

<h1 class="text-4xl">Welcome to my portfolio</h1>
<a
  href="https://alsadig-ahmed.netlify.app"
  target="_blank"
  rel="noopener noreferrer">the old version of my portfolio</a
>

<style lang="scss">
  a {
    @apply text-blue-700  text-xl;
    &:hover {
      @apply text-red-400;
    }
  }
  h1 {
    $v: rgb(0, 255, 13);
    background-color: $v;
  }
</style>
