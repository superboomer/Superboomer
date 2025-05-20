<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
import SupportIcon from './icons/IconSupport.vue'
import QuestionIcon from './icons/IconQuestion.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Привет</template>
( ͡° ͜ʖ ͡°)
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <QuestionIcon />
    </template>
    <template #heading>А зачем нужна эта страница?</template>
Просто чтобы было. Ну и вроде бы даже работает...
  </WelcomeItem>
</template>
