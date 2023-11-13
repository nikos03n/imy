import { RouterLink, RouterView } from 'vue-router'

<template>

  <div class="about">
    

    <WelcomeItem>
    <img alt="Vue logo" class="logo" src="https://firebasestorage.googleapis.com/v0/b/cborka.appspot.com/o/foto%2F0540_26105_1911_0.jpg?alt=media&token=beb8b885-cb6f-4fac-a1e9-9451af0bca05" width="500" height="500" />

    <template #heading>№1</template>
    <RouterLink to="/">Home</RouterLink>

      <h4>Для оформлення замовлення необхідно заповнити коротку форму/макет <a href="https://firebasestorage.googleapis.com/v0/b/cborka.appspot.com/o/foto%2F%D0%9A%D0%BD%D0%B8%D0%B3%D0%B0firebase.xlsx?alt=media&token=63c3e144-60e8-4691-b2ae-b48646990171" target="_blank" rel="noopener">Excel</a> та відправити її за адресою <a href="" target="_blank" rel="noopener">tamazenko@polygraphist.kiev.ua</a> для узгодження</h4>
       
       
       
   </WelcomeItem>



  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
