<template>
  <div>
    <div class="note-selector" v-bind:class="{ active: selectedNoteId === note.id }">
      <p class="note-selector-title">{{ note.body }}</p>
      <p class="note-selector-timestamp">{{ note.timestamp }}</p>
    </div>
  </div>
</template>

<script>
export default {
  props: ["note", "selectedNoteId"],
};
</script>
