<template>
  <div class="h-[10vh] fixed top-0 left-0 right-0 bg-gray-100 dark:bg-gray-900">
    <div class="container mx-auto flex items-center h-full justify-between">
      <NuxtLink to="/" class="flex items-center space-x-3 p-3">
        <NuxtImg src="/logo.svg" width="50" height="50" />
        <span class="text-2xl font-medium">Jira Software</span>
      </NuxtLink>
      <!-- <NuxtButton /> -->
      <div class="flex items-center space-x-3 p-3">
        <SharedColorMode />
        <NuxtLink to="/auth">
          <UButton truncate label="Get it free" color="blue" />
        </NuxtLink>
        <NuxtLink to="/">
          <UButton truncate color="blue" variant="ghost" label="Button" />
        </NuxtLink>
      </div>
    </div>
  </div>
</template>
