<script setup>
defineProps({
  size: {
    type: [Number, String],
    default: 45,
  },
  color: {
    type: String,
    default: '#F2D675',
  },
  strokeWidth: {
    type: [Number, String],
    default: 3,
  },
})
</script>

<template>
  <div class="flex flex-col">
    <div class="flex items-center gap-2">
      <svg
        viewBox="16 34 88 48"
        :width="size"
        :height="size * (48 / 88)"
        xmlns="http://www.w3.org/2000/svg"
        class="shrink-0"
      >
        <line
          x1="17.5"
          y1="78"
          x2="102.5"
          y2="78"
          :stroke="color"
          :stroke-width="strokeWidth"
          stroke-linecap="butt"
        />
        <line
          x1="60"
          y1="78"
          x2="20.5"
          y2="63.6"
          :stroke="color"
          :stroke-width="strokeWidth"
          stroke-linecap="butt"
        />
        <line
          x1="60"
          y1="78"
          x2="26.7"
          y2="52.4"
          :stroke="color"
          :stroke-width="strokeWidth"
          stroke-linecap="butt"
        />
        <line
          x1="60"
          y1="78"
          x2="35.9"
          y2="43.6"
          :stroke="color"
          :stroke-width="strokeWidth"
          stroke-linecap="butt"
        />
        <line
          x1="60"
          y1="78"
          x2="47.4"
          y2="37.9"
          :stroke="color"
          :stroke-width="strokeWidth"
          stroke-linecap="butt"
        />
        <line
          x1="60"
          y1="78"
          x2="60.0"
          y2="36.0"
          :stroke="color"
          :stroke-width="strokeWidth"
          stroke-linecap="butt"
        />
        <line
          x1="60"
          y1="78"
          x2="72.6"
          y2="37.9"
          :stroke="color"
          :stroke-width="strokeWidth"
          stroke-linecap="butt"
        />
        <line
          x1="60"
          y1="78"
          x2="84.1"
          y2="43.6"
          :stroke="color"
          :stroke-width="strokeWidth"
          stroke-linecap="butt"
        />
        <line
          x1="60"
          y1="78"
          x2="93.3"
          y2="52.4"
          :stroke="color"
          :stroke-width="strokeWidth"
          stroke-linecap="butt"
        />
        <line
          x1="60"
          y1="78"
          x2="99.5"
          y2="63.6"
          :stroke="color"
          :stroke-width="strokeWidth"
          stroke-linecap="butt"
        />
      </svg>
      <span class="text-yellow font-semibold font-brand text-4xl leading-none">Letícia</span>
    </div>
    <span class="text-yellow font-semibold font-brand text-4xl leading-none translate-x-13"
      >Mesquita</span
    >
  </div>
</template>
