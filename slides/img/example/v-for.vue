<template>
  <ul>
    <li v-for="(item, index) in listItems" :key="index">
      {{ item }}
    </li>
</template>

<script>
  export default {
    data () {
      return {
        items: [
          'one',
          'two',
          'three'
        ]
      }
    }
  }
</script>