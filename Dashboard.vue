<template>
    <div>
        <button type="button" name="button" @click="something1">Click me to load Something1.js</button>
        <button type="button" name="button" @click="something2">Click me to load Something2.js</button>
        <div id="demo"></div>
    </div>
</template>

<script>
import something1 from "./something1.js"
import something2 from "./something2.js"

export default {

   methods: {
      something1,
      something2,
   }
}
</script>
