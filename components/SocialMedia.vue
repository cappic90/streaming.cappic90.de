<template>
  <div class="w-1/2 flex justify-between">
    <article
      v-for="account in accounts"
      :key="account.id"
      class="text-white flex items-center mb-4"
    >
      <component :is="account.logo" class="w-12 mr-4" />
      <h5 class="flex text-xl">{{ account.tag }}</h5>
    </article>
  </div>
</template>

<script>
import LogoGithub from './LogoGithub'
import LogoTwitch from './LogoTwitch'

export default {
  data() {
    return {
      accounts: [
        {
          id: 'twitch',
          logo: LogoTwitch,
          tag: 'cappic90',
        },
        {
          id: 'github',
          logo: LogoGithub,
          tag: 'cappic90',
        },
      ],
    }
  },
}
</script>
