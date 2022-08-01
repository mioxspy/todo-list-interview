<template>
  <q-page class="flex flex-center">
    <q-input v-model="todolist" label="Todo" />
    {{ todolist }}
    <q-btn @click="$emit('')" color="primary" label="Submit" />
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
  }
}
</script>
