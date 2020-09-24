<script>
  import { onMount } from "svelte";

  onMount(() => {
    var container = document.getElementById("retainable-rss-embed");
    if (container) {
      var css = document.createElement("link");
      css.href =
        "https://www.retainable.io/assets/retainable/rss-embed/retainable.css";
      css.rel = "stylesheet";
      document.getElementsByTagName("head")[0].appendChild(css);
      var script = document.createElement("script");
      script.src =
        "https://www.retainable.io/assets/retainable/rss-embed/retainable.js";
      document.getElementsByTagName("body")[0].appendChild(script);
    }
  });
</script>

<svelte:head>
  <title>Aaro Alhainen | Blog</title>
</svelte:head>

<h1>Recent posts</h1>
<div>
  <div
    id="retainable-rss-embed"
    data-rss="https://medium.com/feed/@aaro.alhainen"
    data-maxcols="3"
    data-layout="grid"
    data-poststyle="external"
    data-readmore="Read the rest"
    data-buttonclass="btn btn-primary"
    data-offset="-100" />
</div>
