<template>
  <div class="element-item">
    <div class="item">
      {{ element }} , {{ columnId }}, {{ rowId }}, {{ sectionId }}
    </div>
  </div>
</template>

<script>
export default {
  props: {
    element: Object,
    columnId: Number,
    rowId: Number,
    sectionId: Number
  }
};
</script>

<style></style>