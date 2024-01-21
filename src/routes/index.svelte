<script>
  import Title from "$lib/Title.svelte";

  const updateTitle = () => {
    title = "Hello World";
  };
</script>

<div class="index">
  <p>
    Lorem ipsum dolor sit, amet consectetur adipisicing elit. Amet blanditiis
    rerum, hic quis distinctio saepe officia sapiente voluptas, similique vitae
    quo obcaecati delectus illo ea sunt nulla dignissimos ipsam molestias.
  </p>
  <a href="/guides">View Guides</a>
  <a href="/about">About</a>
</div>

<style>
  .index {
    text-align: center;
    display: block;
    margin: 20px auto;
  }
</style>
