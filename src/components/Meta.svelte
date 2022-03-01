<script>
  export let title = "Thunder Roads";
  export let description = "Visualizing F1 Races in the 2021 Season";
  export let url = "https://obumbratta.com";
  export let keywords = "";
  // export let preloadFont = [];
</script>

<svelte:head>
  <title>{title}</title>
  <meta name="description" content={description} />
  <meta name="author" content="Joey Cherdarchuk" />
  <meta name="news_keywords" content={keywords} />

  <meta property="og:title" content={title} />
  <meta property="og:site_name" content="Thunder Roads" />
  <meta property="og:url" content={url} />
  <meta property="og:description" content={description} />
  <meta property="og:type" content="article" />
  <meta property="og:locale" content="en_US" />

  <!-- <meta property="ogsurl}/assets/social-twitter.jpg" /> -->

  <meta name="robots" content="max-image-preview:large" />

  <link rel="canonical" href="{url}/" />
<!-- 
  {#each preloadFont as href}
    <link rel="preload" {href} as="font" type="font/woff2" crossorigin />
  {/each} -->
</svelte:head>
