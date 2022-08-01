<template>
  <q-page class="flex flex-center">
    <q-input v-model="todolist" label="Todo" name="vinput" />
    <q-btn @click="submit" color="primary" label="Submit" />
    <q-btn color="secondary" label="Clear" type="clear" />

  </q-page>
</template>

<script>

export default {
  name: 'Homepage',
  data(){
    return {
      todolist: "" 
      lists: [] 
    };
  },
  methods: {
    submit() {

      console.log(this.todolist);
      
      this.todolist = ''
    }
  }
}
</script>
