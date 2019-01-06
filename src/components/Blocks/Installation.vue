<template>
  <div>
    <!-- Icon by Bytesize https://github.com/danklammer/bytesize-icons -->
    <svg xmlns="http://www.w3.org/2000/svg" focusable="false" width="32" height="32" fill="none" stroke="currentcolor"
         stroke-width="2" class="text-primary mb-2" viewBox="0 0 32 32" stroke-linecap="round" stroke-linejoin="round"
         aria-hidden="true"><title>Import</title>
      <path d="M28 22v8H4v-8M16 4v20m-8-8l8 8 8-8"></path>
    </svg>
    <h3>Installation</h3>
    <p>Include Bootstrap’s source Sass and JavaScript files via npm, Composer or Meteor. Package managed installs
      don’t include documentation, but do include our build system and readme.</p>
    <div class="bd-clipboard">
      <button type="button" class="btn-clipboard" title="" data-original-title="Copy to clipboard">Copy</button>
    </div>
    <figure class="highlight">
      <pre><code class="language-sh" data-lang="sh">npm <span class="nb">install </span>bootstrap</code></pre>
    </figure>
    <div class="bd-clipboard">
      <button type="button" class="btn-clipboard" title="" data-original-title="Copy to clipboard">Copy</button>
    </div>
    <figure class="highlight">
        <pre><code class="language-sh" data-lang="sh">gem <span class="nb">install </span>bootstrap <span
          class="nt">-v</span> 4.2.1</code></pre>
    </figure>
    <hr class="half-rule">
    <a class="btn btn-outline-primary" href="/docs/4.2/getting-started/download/">Read installation docs</a>
  </div>
</template>

<script>
  export default {
    name: 'Installation'
  }
</script>

<style scoped>

</style>
