<template>
  <div class="surah"></div>
</template>

<script>
export default {
  mounted() {
    console.log(this.$route.params.id);
  },
};
</script>