<template>
    <section class="space-y-5">
      <div v-for="check in checkList" :key="check.id" class="flex space-x-1 text-lg items-center" :class="{'fnt-1': isBlack, 'text-white': !isBlack,}">
        <img class="object-contain h-full" :src="isBlack ? '/check black.png' : '/check white.png'" :alt="isBlack ? 'check black' : 'check white'">
        <span>{{ check }}</span>
      </div>
    </section>
</template>

<script>
export default {
  name: 'CheckBoxListComponent',
  props:{
    checkList: Array,
    isBlack: Boolean,
  }
}
</script>
