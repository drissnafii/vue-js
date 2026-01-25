
<template>
  <h2>Hello from template</h2>
  <div id="app">
    <h3>
      Hello Dendo
    </h3>

  </div>
</template>
<script>
const {createApp, ref} = vue
createApp({
  setup(){
    const name = ref("dednddd")
    return name
  }
}).mounth 
</script>