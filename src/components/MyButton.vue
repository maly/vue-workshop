<template>
  <div>
    <p>Value: {{number}}</p>
    <button @click="inc">ADD ONE</button>
  </div>
</template>

<script>
export default {
  name: 'myButton',
  data () {
    return {
      number: 0
    }
  },
  methods: {
    inc () {
      this.number++
    }
  }
}
</script>
