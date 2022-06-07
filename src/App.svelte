<script lang="ts">
  import Button from './lib/Button.svelte'
</script>

<main>
  <div class="center">
    <h1>Welome to Zyno</h1>
    <p>Take back your privacy.</p>
    <br>
    <Button url="https://place.zyno.us" label="Zyno Place" />
    <Button url="https://github.com/zyno-us/dns" label="ZynoDNS" />
  </div>
</main>

<style>
  :root {
    font-family: 'Poppins', sans-serif;
  }

  .center { 
    position: absolute;
    left: 50%;
    top: 50%;
    transform: translate(-50%, -50%);
    text-align: center;
  }
</style>
