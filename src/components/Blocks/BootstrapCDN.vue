<template>
  <div>
    <!-- Icon by Bytesize https://github.com/danklammer/bytesize-icons -->
    <svg xmlns="http://www.w3.org/2000/svg" focusable="false" width="32" height="32" fill="none" stroke="currentcolor"
         stroke-width="2" class="text-primary mb-2" viewBox="0 0 32 32" stroke-linecap="round" stroke-linejoin="round"
         aria-hidden="true"><title>Download</title>
      <path d="M9 22c-9 1-8-10 0-9C6 2 23 2 22 10c10-3 10 13 1 12m-12 4l5 4 5-4m-5-10v14"></path>
    </svg>
    <h3>BootstrapCDN</h3>
    <p>When you only need to include Bootstrap’s compiled CSS or JS, you can use <a
      href="https://www.bootstrapcdn.com/">BootstrapCDN</a>.</p>
    <h5>CSS only</h5>
    <div class="bd-clipboard">
      <button type="button" class="btn-clipboard" title="" data-original-title="Copy to clipboard">Copy</button>
    </div>
    <figure class="highlight">
        <pre><code class="language-html" data-lang="html"><span class="nt">&lt;link</span> <span
          class="na">rel=</span><span class="s">"stylesheet"</span> <span class="na">href=</span><span class="s">"https://stackpath.bootstrapcdn.com/bootstrap/4.2.1/css/bootstrap.min.css"</span> <span
          class="na">integrity=</span><span class="s">"sha384-GJzZqFGwb1QTTN6wy59ffF1BuGJpLSa9DkKMp0DgiMDm4iYMj70gZWKYbI706tWS"</span> <span
          class="na">crossorigin=</span><span class="s">"anonymous"</span><span class="nt">&gt;</span></code></pre>
    </figure>
    <h5>JS, Popper.js, and jQuery</h5>
    <div class="bd-clipboard">
      <button type="button" class="btn-clipboard" title="" data-original-title="Copy to clipboard">Copy</button>
    </div>
    <figure class="highlight"><pre><code class="language-html" data-lang="html"><span
      class="nt">&lt;script </span><span class="na">src=</span><span class="s">"https://code.jquery.com/jquery-3.3.1.slim.min.js"</span> <span
      class="na">integrity=</span><span class="s">"sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo"</span> <span
      class="na">crossorigin=</span><span class="s">"anonymous"</span><span class="nt">&gt;&lt;/script&gt;</span>
<span class="nt">&lt;script </span><span class="na">src=</span><span class="s">"https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.6/umd/popper.min.js"</span> <span
        class="na">integrity=</span><span class="s">"sha384-wHAiFfRlMFy6i5SRaxvfOCifBUQy1xHdJ/yoi7FRNXMRBu5WHdZYu1hA6ZOblgut"</span> <span
        class="na">crossorigin=</span><span class="s">"anonymous"</span><span class="nt">&gt;&lt;/script&gt;</span>
<span class="nt">&lt;script </span><span class="na">src=</span><span class="s">"https://stackpath.bootstrapcdn.com/bootstrap/4.2.1/js/bootstrap.min.js"</span> <span
        class="na">integrity=</span><span class="s">"sha384-B0UglyR+jN6CkvvICOB2joaf5I4l3gm9GU6Hc1og6Ls7i6U/mkkaduKaBhlAXv9k"</span> <span
        class="na">crossorigin=</span><span class="s">"anonymous"</span><span
        class="nt">&gt;&lt;/script&gt;</span></code></pre>
    </figure>
    <hr class="half-rule">
    <a class="btn btn-outline-primary" href="">Explore the docs</a>
  </div>
</template>

<script>
export default {
  name: 'BootstrapCDN'
}
</script>

<style scoped>

</style>
