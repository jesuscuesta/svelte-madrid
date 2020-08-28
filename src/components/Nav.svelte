<script>
	export let segment;
</script>

  <header id="header">
    <h1 id="logo">
      <a href="index.html">Svelte Madrid</a>
    </h1>
    <nav id="nav">
      <ul>
        <li>
          <a aria-current="{segment === undefined ? 'page' : undefined}" href=".">home</a>
        </li>
        <!-- <li>
          <a aria-current="{segment === 'about' ? 'page' : undefined}" href="about">about</a>
        </li>
        <li>
          <a rel=prefetch aria-current="{segment === 'blog' ? 'page' : undefined}" href="blog">blog</a>
        </li> -->
      </ul>
    </nav>
  </header>