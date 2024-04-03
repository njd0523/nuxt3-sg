<template>
  <div class="molecule__welcome-header">
    <AtomWelcomeTitle :title="'Welcome to simple membership project !'" />
    <AtomWelcomeDescription :description="'Welcome to my simple membership project !'" />
  </div>
</template>

<script setup lang="ts"></script>

<style scoped lang="postcss">
.molecule {
  &__welcome-header {
    @apply flex flex-col items-center justify-center w-full h-screen;
  }
}
</style>
