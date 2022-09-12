<svelte:options tag="sunbird-pdf-player" />
<script lang="ts">
  let src = "src/assets/pdfjs/web/viewer.html?file=https://sunbirdstagingpublic.blob.core.windows.net/sunbird-content-staging/content/do_213427882013302784110014/artifact/pdf_222.pdf"
</script>

<main>
 
  <iframe frameborder="0" src={src} title="player"></iframe>
</main>

<style>
  p {
    color: brown;
    font-family: 'Courier New', Courier, monospace;
    font-size: 2rem;
  }
</style>

