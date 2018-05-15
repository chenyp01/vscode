<template>
  <div className="test-block">
    <basic-container>
      <h1>TestBlock</h1>
    </basic-container>
    <div>{{content}}</div>
  </div>
</template>

<script>
import BasicContainer from '@vue-materials/basic-container'

export default {
  components: { BasicContainer },
  name: 'TestBlock',
  props:{
    content:{
      type:String,
      default:'默认值'
    }
  },
  data() {
    return {}
  },

  created() {
    console.log('123123')
  },

  methods: {}
}

</script>

<style>
  .test-block {

  }
</style>
