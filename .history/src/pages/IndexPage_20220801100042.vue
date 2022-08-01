<template>
  <q-page class="flex flex-center">
    <q-input v-model="todolist" label="Todo" />
    <q-btn @click="submit" color="primary" label="Submit" />
    <q-btn color="secondary" label="Clear" />

  </q-page>
</template>

<script>

export default {
  name: 'Homepage',
  data(){
    return {
      todolist: ""  
    };
  },
  methods: {
    submit() {
      this.$emit('submit');
      console.log();
    }
  }
}
</script>
