<template>   
    <div class="page page_onboarding">
      <h1 class="page__title text-center">{{title}}</h1>
      <slot></slot>
    </div>
</template>

<script>
export default {
  name: 'AuthLayout',
  props: {
    title: {
      type: String
    }
  }
};
</script>

<style scoped>
.page.page_onboarding {
  max-width: 374px;
  width: 100%;
  margin: 0 auto;
}
</style>
