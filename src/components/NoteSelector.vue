<template>
  <div>
    <div class="note-selector active">
      <p class="note-selector-title">{{ note.body }}</p>
      <p class="note-selector-timestamp">{{ note.timestamp }}</p>
    </div>
  </div>
</template>

<script>
export default {
  props: ["note"],
};
</script>
