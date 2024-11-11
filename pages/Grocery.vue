<script setup lang="ts">
const links = [
  [{
    label: 'Profile',
    avatar: {
      src: 'https://avatars.githubusercontent.com/u/155015410?v=4'
    },
    badge: 100
  }, {
    label: 'Your repositories',
    icon: 'i-heroicons-home',
    to: '/getting-started/installation'
  }, {
    label: 'Your commits',
    icon: 'i-heroicons-chart-bar',
    to: '/components/vertical-navigation'
  }, {
    label: 'Your orgarnizations',
    icon: 'i-heroicons-command-line',
    to: '/components/command-palette'
  }], [{
    label: 'Your stars',
    icon: 'i-heroicons-light-bulb'
  }, {
    label: 'Your pull requests',
    icon: 'i-heroicons-question-mark-circle'
  }]
]
</script>

<template>
  <UVerticalNavigation :links="links" />
</template>

