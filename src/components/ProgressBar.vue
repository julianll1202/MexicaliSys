<template>
  <div class="progress-info">
    <div class="progress-label">
      <span>{{ skill }}</span>
    </div>
    <div class="progress-percentage">
      <span>{{ level }}%</span>
    </div>
    <div class="progress">
      <div
        class="progress-bar bg-primary"
        role="progressbar"
        aria-valuenow="95"
        aria-valuemin="0"
        id="progress-bar"
        aria-valuemax="100"
        v-bind:style="{ width: level + '%' }"
      ></div>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    skill: String,
    level: Number,
  },
  setup(props) {},
};
</script>

<style></style>
