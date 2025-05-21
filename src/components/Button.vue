<template>
  <button class="button">
    <slot />
  </button>
</template>

<style scoped>
.button {
  width: 335px;
  height: 68px;
  padding-top: 16px;
  padding-bottom: 16px;
  padding-left: 10px;
  padding-right: 10px;
  border-radius: 100px;
  background: var(--btn-bg);
  color: var(--text-color);
  font-size: 24px;
  border: none;
}

.button:hover {
  cursor: pointer;
}
</style>
