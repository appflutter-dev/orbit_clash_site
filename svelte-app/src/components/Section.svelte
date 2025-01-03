<script>
  export let title;
</script>

<section>
  <h2>{title}</h2>
  <slot></slot>
</section>

<style>
  section {
    padding: 2rem;
    border-bottom: 1px solid #ddd;
  }
  h2 {
    color: #0073e6;
  }
</style>
