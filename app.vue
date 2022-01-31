<template>
  <div id="app">
    <page-header />
    <about-me />
    <juon-pointe />
    <contact />
  </div>
</template>

<script>
import './assets/css/tailwind.scss';
import './assets/css/app.scss';
import AboutMe from './components/AboutMe.vue';
import PageHeader from './components/PageHeader.vue';
import Contact from './components/Contact.vue';
import JuonPointe from './components/JuonPointe.vue';

export default {
  components: {
    PageHeader,
    AboutMe,
    Contact,
    JuonPointe
  },
}
</script>