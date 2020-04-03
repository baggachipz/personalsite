<template>
  <q-layout view="lHh Lpr lFf">
    <q-header elevated>
      <q-toolbar>
        <q-btn
          flat
          dense
          round
          icon="menu"
          aria-label="Menu"
          @click="leftDrawerOpen = !leftDrawerOpen"
        />

      </q-toolbar>
    </q-header>

    <q-drawer
      v-model="leftDrawerOpen"
      show-if-above
      bordered
      content-class="bg-grey-3"
    >
      <q-list>
        <EssentialLink
          v-for="link in essentialLinks"
          :key="link.title"
          v-bind="link"
        />
      </q-list>
    </q-drawer>

    <q-page-container>
      <router-view />
    </q-page-container>
  </q-layout>
</template>

<script>
import EssentialLink from 'components/EssentialLink'

export default {
  name: 'MainLayout',

  components: {
    EssentialLink
  },

  data () {
    return {
      leftDrawerOpen: false,
      essentialLinks: [
        {
          title: 'Skills',
          icon: 'laptop',
          link: '#skills'
        },
        {
          title: 'Experience',
          icon: 'business',
          link: '#experience'
        },
        {
          title: 'Education',
          icon: 'school',
          link: '#education'
        },
        {
          title: 'Personal',
          icon: 'fingerprint',
          link: '#personal'
        },
        {
          title: 'Contact',
          icon: 'feedback',
          link: '#contact'
        },
        {
          title: 'Résumé / CV',
          icon: 'description',
          link: '#resume'
        },
        {
          title: 'Github',
          caption: 'github.com/baggachipz',
          icon: 'code',
          link: 'https://github.com/baggachipz'
        }
      ]
    }
  }
}
</script>
