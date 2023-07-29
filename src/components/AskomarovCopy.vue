<template lang="pug">
p(:class='parentClass').ascopy created by
  | ;
  a(href="https://www.youtube.com/channel/UClj_YDnrBmAOLirho9sX0WA" :class='linkClass') 
    span Juan Carlos Perez Mtz.
</template>

<script setup>
const props = defineProps({
  parentClass: {
    type: String,
  },
  linkClass: {
    type: String,
  },
});
</script>

<style lang="scss">
.ascopy {
  text-align: center;
  padding: 1.9rem;

  a:hover span {
    text-decoration: underline;
    color: white;
  }
}
</style>

