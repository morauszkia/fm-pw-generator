<script lang="ts">
  import copyImgUrl from "../assets/images/icon-copy.svg";
</script>

<section>
  <p>P4$5W0rD!</p>
  <img src={copyImgUrl} alt="Copy to Clipboard" />
</section>

<style scoped>
  section {
    width: 100%;
    background-color: var(--container);
    padding: 1rem 1.125rem;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  p {
    color: var(--placeholder);
    font-size: 1.5rem;
    font-weight: 700;
  }

  img {
    height: 1.25rem;
  }
</style>
