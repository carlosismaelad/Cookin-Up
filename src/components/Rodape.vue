<template>
    <footer class="rodape paragrafo">
      Desenvolvido por Carlos Dourado | 2024 - Projeto fictício para fins de estudo sobre Vue.js.
    </footer>
  </template>
  
  <style scoped>
  .rodape {
    background: var(--verde-escuro, #263A29);
    padding: 1.5rem 7.5rem;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  
  @media only screen and (max-width: 1300px) {
    .rodape {
      padding: 1.5rem 3.75rem;
    }
  }
  
  @media only screen and (max-width: 767px) {
    .rodape {
      padding: 1.5rem;
    }
  }
  </style>