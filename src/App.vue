<template>
  <div id="app">
    <app-header></app-header>
    <app-introduction-bootstrap></app-introduction-bootstrap>
    <app-masthead-followup></app-masthead-followup>
    <app-footer></app-footer>
  </div>
</template>

<script>
import Header from './components/Shared/Header'
import Footer from './components/Shared/Footer'
import Servers from './components/Servers/Servers'
import ServerDetail from './components/Servers/ServerDetail'

import IntroductionBootstrap from './components/IntroductionBootstrap'
import MastheadFollowup from './components/MastheadFollowup'

export default {
  data: function () {
    return {
      test: 'Hello world'
    }
  },
  components: {
    appHeader: Header,
    'appIntroductionBootstrap': IntroductionBootstrap,
    'appMastheadFollowup': MastheadFollowup,
    Servers,
    'app-server-details': ServerDetail,
    'app-footer': Footer
  }
}
</script>

<style>

</style>
