<script setup>
// こちらからスクリプトを記述してください
// import ChildComponent from './components/ChildComponent.vue';

</script>
<template>
  <div class="lesson4_div">
    <!-- こちらからテンプレートを記述してください -->
    
  </div>
</template>
<style>
  .lesson4_div {
    display: flex;
    align-items: center;
    gap: 16px;
  }

  .lesson4_input {
    border-radius: 0;
    -webkit-appearance: none;
    -moz-appearance: none;
    appearance: none;
    position: relative;
    width: 16px;
    height: 16px;
    border: 1px solid #000;
    vertical-align: -5px;
  }

  .lesson4_input:checked:before {
    position: absolute;
    top: 1px;
    left: 4px;
    transform: rotate(50deg);
    width: 4px;
    height: 8px;
    border-right: 2px solid #000;
    border-bottom: 2px solid #000;
    content: '';
  }
</style>