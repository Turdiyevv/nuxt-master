<template>
  <div class="fixed top-0 left-0 right-0 bg-gray-100
    dark:bg-gray-900 z-50">
    <div class="container my-2 px-4 flex items-center justify-between">
      <NuxtLink to="/" class="flex items-center space-x-1">
        <NuxtImg src="/logo.svg" width="50" height="50"/>
        <span class="text-2xl font-medium">Jira soft</span>
      </NuxtLink>

      <div class="flex items-center space-x-2">
        <shred-color-mode/>
        <NuxtLink>
          <UButton color="blue">
            Get it free
          </UButton>
        </NuxtLink>
        <NuxtLink>
          <UButton color="blue" variant="soft">
            Sign in
          </UButton>
        </NuxtLink>
      </div>
    </div>
  </div>
</template>
