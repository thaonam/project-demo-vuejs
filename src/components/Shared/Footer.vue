<template>
  <footer class="bd-footer text-muted">
    <div class="container-fluid p-3 p-md-5">
      <ul class="bd-footer-links">
        <li><a href="https://github.com/twbs/bootstrap">GitHub</a></li>
        <li><a href="https://twitter.com/getbootstrap">Twitter</a></li>
        <li><a href="/docs/4.2/examples/">Examples</a></li>
        <li><a href="/docs/4.2/about/overview/">About</a></li>
      </ul>
      <p>Designed and built with all the love in the world by <a href="https://twitter.com/mdo" target="_blank" rel="noopener">@mdo</a> and <a href="https://twitter.com/fat" target="_blank" rel="noopener">@fat</a>. Maintained by the <a href="https://github.com/orgs/twbs/people">core team</a> with the help of <a href="https://github.com/twbs/bootstrap/graphs/contributors">our contributors</a>.</p>
      <p>Currently v4.2.1. Code licensed <a href="https://github.com/twbs/bootstrap/blob/master/LICENSE" target="_blank" rel="license noopener">MIT</a>, docs <a href="https://creativecommons.org/licenses/by/3.0/" target="_blank" rel="license noopener">CC BY 3.0</a>.</p>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'Footer'
}
</script>
<style scoped>
  .bd-footer {
    font-size: 85%;
    text-align: center;
    background-color: #f7f7f7;
  }
  @media (min-width: 576px){
    .bd-footer {
      text-align: left;
    }
  }
  .bd-footer-links {
    padding-left: 0;
    margin-bottom: 1rem;
  }
  .bd-footer-links li {
    display: inline-block;
  }
  .bd-footer-links li+li {
    margin-left: 1rem;
  }
  .bd-footer p {
    margin-bottom: 0;
  }
  .bd-footer a {
    font-weight: 600;
    color: #495057;
  }

</style>
