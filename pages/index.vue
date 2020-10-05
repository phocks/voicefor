<template>
  <main>
    <h1>Hello world!</h1>
    <p><NuxtLink to="fun">Fun</NuxtLink></p>
  </main>
</template>

<script lang="ts">
// use TypeScript here

interface User {
  name: string;
  id: number;
}

const user: User = {
  name: "Hayes",
  id: 0,
};

console.log(user);
</script>
