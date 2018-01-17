<template>
  <div>
    <myHeader></myHeader>
    <stuEnterprise></stuEnterprise>
    <myFooter></myFooter>
    <!-- img test -->
    <!-- <div class="img_test">
      <img src="static/image/lyf.jpg" alt="刘亦菲">
    </div> -->
    <!--  -->
    <!-- <div class="article_list">
      <ul>
        <li v-for="i in list">
          <time v-text="$utils.goodTime(i.create_at)"></time>
          <router-link :to="'/content/' + i.id">
            {{ i.title }}
          </router-link>
        </li>
      </ul>
    </div> -->
    
  </div>
</template>
<script>
import myHeader from '../components/header.vue'
import myFooter from '../components/footer.vue'
import stuEnterprise from '../page/student/stuEnterprise'
export default {
  components: { myHeader, myFooter,stuEnterprise },
  data () {
    return {
      list: []
    }
  },
  created () {
    // this.getData()
  },
  methods: {
    // getData () {
    //   this.$api.get('topics', null, r => {
    //     this.list = r.data
    //   })
    // }
  }
}
</script>
