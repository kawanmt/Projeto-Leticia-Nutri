<script setup>
import FramedImage from './FramedImage.vue'
import NomeLeticia from './NomeLeticia.vue'
import SectionLayout from './SectionLayout.vue'

import imgTeste from '@/assets/images/messi.jpeg'

const alt1 = 'Letícia Palestrando'

</script>
<template>
  <SectionLayout>
    <div class="grid grid-cols-2 pt-20">
      <div class="flex flex-col gap-26">
        <NomeLeticia />
        <div class="flex flex-col gap-16">
          <div class="flex flex-col gap-6">
            <h1 class="text-textColor font-bold font-title text-6xl">
              Nutrição com ciência, acolhimento e equilíbrio
            </h1>
            <p class="text-textColor font-text text-xl">
              Ajudo pessoas a construírem saúde, bem-estar e uma relação mais leve com a
              alimentação, respeitando sua individualidade e seus objetivos.
            </p>
          </div>
          <a
            href="#"
            class="w-64 h-18 flex items-center justify-center rounded-lg bg-yellow font-bold font-text text-lg"
            >SUA EVOLUÇÃO AGORA</a
          >
        </div>
      </div>
      <div class="flex items-start justify-end">
        <FramedImage :src="imgTeste" :alt="alt1" />
      </div>
    </div>
  </SectionLayout>
</template>
