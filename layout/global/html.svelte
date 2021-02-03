<script>
  import Head from './head.svelte';
  import Nav from './nav.svelte';

  export let route, content, allContent, allComponents;
</script>

<html lang="en">
<Head title={content.filename} />
<body>
  <header class="navigation">
    <div class="container">
      <Nav />
    </div>
  </header>
  <svelte:component this={route} {...content.fields} {allContent} {allComponents}/>
</body>
</html>
