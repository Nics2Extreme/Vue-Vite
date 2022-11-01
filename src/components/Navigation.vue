<template>
<nav class="sm:flex sm:items-start sm:justify-between">
    <div class="p-2">
        <span class="sm:text-lg">Kanasite</span><span class='text-xs'> by Kanasei </span>
    </div>
    <ul class="flex p-2">
        <li class="ml-4 mr-6">
          <router-link class="text-sm text-blue-500 hover:text-blue-800" to="/login">Login</router-link>
        </li>
        <li class="ml-2 mr-6">
          <router-link class="text-sm text-blue-500 hover:text-blue-800" to="/register">Register</router-link>
        </li>
    </ul>
</nav>
<router-view />
</template>