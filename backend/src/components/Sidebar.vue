<template>
  <div class="w-[200px]  transition-all bg-indigo-700 text-white py-4 px-2">

    <router-link :to="{name: 'app.dashboard'}"
                 class="flex items-center p-2 rounded transition-colors hover:bg-black/30">
      <span class="mr-2 text-gray-300">
        <HomeIcon class="w-5"/>
      </span>
      <span class="text-xs">
          Панель управления
      </span>
    </router-link>

    <router-link :to="{name: 'app.products'}"
                 class="flex items-center p-2 rounded transition-colors hover:bg-black/30">
      <span class="mr-2 text-gray-300">
          <Bars3Icon class="w-5"/>
      </span>
      <span class="text-xs">
          Товары
      </span>
    </router-link>

    <router-link :to="{name: 'app.dashboard'}"
                 class="flex items-center p-2 rounded transition-colors hover:bg-black/30">
      <span class="mr-2 text-gray-300">
          <UsersIcon class="w-5"/>
      </span>
      <span class="text-xs">
          Пользователи
      </span>
    </router-link>

    <router-link :to="{name: 'app.dashboard'}"
                 class="flex items-center p-2 rounded transition-colors hover:bg-black/30">
      <span class="mr-2 text-gray-300">
          <ChartBarIcon class="w-5"/>
      </span>
      <span class="text-xs">
          Отчёты
      </span>
    </router-link>
  </div>
</template>

<script setup>
import { HomeIcon, UsersIcon, ChartBarIcon } from '@heroicons/vue/24/solid'
import { Bars3Icon } from '@heroicons/vue/16/solid'
</script>

<style scoped>
</style>