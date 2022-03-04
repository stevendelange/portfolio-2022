<template>
  <section :class="$style.hero">
    <div>about</div>
  </section>
</template>

<script>
export default {
  name: "IndexPage",
};
</script>

<style lang="scss" module>
$color--background: #c14917;
$color--text: #f0efef;

body {
  background: $color--background;
  color: $color--text;
}

.hero {
  width: 100vw;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>
