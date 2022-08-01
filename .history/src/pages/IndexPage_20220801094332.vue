<template>
  <q-page class="flex flex-center">
    <q-input v-model="text" label="Standard" />
    <q-btn color="primary" label="Submit" />

    <q-btn color="secondary" label="Clear" />
  </q-page>
</template>

<script>
data() {
  return {
    existentialQuestion: 'Am I truly an alligator?'  
  };
}
export default {
  name: 'Homepage',
}
</script>
