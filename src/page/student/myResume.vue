<template>
  <div>
  <myHeader></myHeader>
  <resume></resume>
  </div>
</template>
<script>
import resume from '../../components/resume'
import myHeader from '../../components/header'
export default {
  components: {
      resume,
      myHeader
  },
  methods: {
      
  }
}
</script>
<style lang="scss">
  @import "../../style/scss/student/myResume.scss"
</style>

