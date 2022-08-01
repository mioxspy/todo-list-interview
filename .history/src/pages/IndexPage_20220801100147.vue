<template>
  <q-page class="flex flex-center">
    <q-input v-model="todolist" label="Todo" />
    <q-btn @click="submit" color="primary" label="Submit" />
    <q-btn color="secondary" label="Clear" type="c/>

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
      console.log(this.todolist);
    }
  }
}
</script>
