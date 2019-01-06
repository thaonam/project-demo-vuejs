<template>
  <div class="masthead-followup row m-0 border border-white">
    <div class="col-12 col-md-4 p-3 p-md-5 bg-light border border-white">
      <app-installation></app-installation>
    </div>
    <div class="col-12 col-md-4 p-3 p-md-5 bg-light border border-white">
      <app-bootstrap-cdn></app-bootstrap-cdn>
    </div>
    <div class="col-12 col-md-4 p-3 p-md-5 bg-light border border-white">
      <app-official-themes></app-official-themes>
    </div>
  </div>
</template>

<script>
import Installation from './Blocks/Installation'
import BootstrapCDN from './Blocks/BootstrapCDN'
import OfficialThemes from './Blocks/OfficialThemes'

export default {
  name: 'MastheadFollowup',
  components: {
    'appInstallation': Installation,
    'appBootstrapCdn': BootstrapCDN,
    'appOfficialThemes': OfficialThemes
  }
}
</script>

<style>
  .btn-clipboard {
    position: absolute;
    top: .5rem;
    right: .5rem;
    z-index: 10;
    display: block;
    padding: .25rem .5rem;
    font-size: 75%;
    color: #818a91;
    cursor: pointer;
    background-color: transparent;
    border: 0;
    border-radius: .25rem;
  }

  .half-rule {
    width: 6rem;
    margin: 2.5rem 0;
  }
</style>
