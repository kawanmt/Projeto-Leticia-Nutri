<script setup>

import SectionLayout from './SectionLayout.vue';
import FramedImage from './FramedImage.vue';
import NomeLeticia from './NomeLeticia.vue';

import imgTeste from '@/assets/images/messi.jpeg'

const alt2 = "Leticia Sorrindo"

</script>

<template>
  <SectionLayout>
    <div class="grid grid-cols-2 pt-20">
      <div class="flex justify-start">
        <FramedImage :src="imgTeste" :alt="alt2" />
      </div>
      <div class="flex items-center flex-col gap-28">
        <NomeLeticia />
        <div class="flex flex-col gap-12">
          <div class="flex flex-col gap-6">
            <span class="text-yellow font-bold font-title text-6xl">Minha visão</span>
            <p class="text-textColor font-semibold font-text text-2xl">
              Mais do que transformar o seu corpo, meu objetivo é transformar a sua relação com a alimentação.</p>
          </div>
          <p class="text-textColor font-text text-xl">Através de um acompanhamento individualizado,
            construímos hábitos sustentáveis, promovemos equilíbrio e alcançamos resultados que permanecem, sem
            restrições extremas e sem fórmulas prontas.</p>
        </div>
      </div>
    </div>
  </SectionLayout>
</template>
