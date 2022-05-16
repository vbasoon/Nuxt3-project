<template>
  <div class="wrapper">
    <TheHeader />

    <div class="main container mx-auto">
      <router-view />
    </div>
    <TheFooter />
  </div>
</template>

<style>
.wrapper {
  max-width: 1400px;
  min-height: 100vh;
  margin: 0 auto;
  display: flex;
  flex-direction: column;
}
.main {
  flex: 1;
}
</style>
