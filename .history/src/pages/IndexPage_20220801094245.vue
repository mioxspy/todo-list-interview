<template>
  <q-page class="flex flex-center">
    <q-input v-model="text" label="Standard" />
    <q-btn v-model="existentialQuestion"color="primary" label="Submit" />

    <q-btn color="secondary" label="Clear" />
  </q-page>
</template>

<script>

export default {
  name: 'Homepage',
}
</script>
