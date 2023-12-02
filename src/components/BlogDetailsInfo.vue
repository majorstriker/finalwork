<template>
  <div class="blog-details__sub-box">
    <p class="blog-details__number">{{ numberandtext.number }}</p>
    <p class="blog-details__text">{{ numberandtext.text }}</p>
  </div>
</template>

<script>
export default {
  name: "BlogDetailsInfo",
  props: {
    numberandtext: Object,
  },
  data() {
    return {};
  },
};
</script>
