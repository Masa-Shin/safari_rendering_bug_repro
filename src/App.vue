<template>
  <main>
    <div
      v-for="i in [...Array(2000).keys()]" :key="i" 
      class="rect"
    >
      This element disappears when you scroll quickly up and down on an iOS browser.
    </div>
  </main>
</template>

<style scoped>
.rect {
  background-color: #0dd;
}
</style>
