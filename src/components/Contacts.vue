<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
import GithubIcon from './icons/IconGithub.vue'
import TelegramIcon from './icons/IconTelegram.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <TelegramIcon />
    </template>
    <template #heading>Telegram</template>
    <a href="https://t.me/superboomer" target="_blank" rel="noopener">@Superboomer</a>
  </WelcomeItem>
  
  <WelcomeItem>
    <template #icon>
      <GithubIcon />
    </template>
    <template #heading>Github</template>
    <a href="https://github.com/Superboomer" target="_blank" rel="noopener">@Superboomer</a>
  </WelcomeItem>
</template>
