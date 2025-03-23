<template>
  <div id="setting">
    <my-todo />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import MyTodo from '@/components/MyTodo.vue' // @ is an alias to /src

export default defineComponent({
  name: 'SettingView',
  components: {
    MyTodo
  }
})
</script>
