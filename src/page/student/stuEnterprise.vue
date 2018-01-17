<template>
  <div>
      <div class="container">
        <stuEnGrid></stuEnGrid>
        <div class="row">
            <div class="col-md-2" style="background-color: #fff;border:1px solid;margin-right:3px;float:left">
              <div class="oneEnResume" style="width:100%;height:200px;background-color: #fff;">
                <div class="entPicture" style="width:50%;height:100%;background-color: #959694;"></div>
                <div class="entPicture" style="width:50%;height:100%;background-color: #fff;"></div>
              </div>
            </div>
            <div class="col-md-2" style="background-color: #fff;border:1px solid;margin-right:3px;float:left">
              <div class="oneEnResume" style="width:100%;height:200px;background-color: #fff;">
                <div class="entPicture" style="width:50%;height:100%;background-color: #959694;"></div>
                <div class="entPicture" style="width:50%;height:100%;background-color: #fff;"></div>
              </div>
            </div>
            <div class="col-md-2" style="background-color: #fff;border:1px solid;margin-right:3px;float:left">
              <div class="oneEnResume" style="width:100%;height:200px;background-color: #fff;">
                <div class="entPicture" style="width:50%;height:100%;background-color: #959694;"></div>
                <div class="entPicture" style="width:50%;height:100%;background-color: #fff;"></div>
              </div>
            </div>
            <div class="col-md-2" style="background-color: #fff;border:1px solid;margin-right:3px;float:left">
              <div class="oneEnResume" style="width:100%;height:200px;background-color: #fff;">
                <div class="entPicture" style="width:50%;height:100%;background-color: #959694;"></div>
                <div class="entPicture" style="width:50%;height:100%;background-color: #fff;"></div>
              </div>
            </div>
        </div>
        <div class="row">
            <div class="col-md-2" style="background-color: #fff;border:1px solid;margin-right:3px;float:left">
              <div class="oneEnResume" style="width:100%;height:200px;background-color: #fff;">
                <div class="entPicture" style="width:50%;height:100%;background-color: #959694;"></div>
                <div class="entPicture" style="width:50%;height:100%;background-color: #fff;"></div>
              </div>
            </div>
            <div class="col-md-2" style="background-color: #fff;border:1px solid;margin-right:3px;float:left">
              <div class="oneEnResume" style="width:100%;height:200px;background-color: #fff;">
                <div class="entPicture" style="width:50%;height:100%;background-color: #959694;"></div>
                <div class="entPicture" style="width:50%;height:100%;background-color: #fff;"></div>
              </div>
            </div>
            <div class="col-md-2" style="background-color: #fff;border:1px solid;margin-right:3px;float:left">
              <div class="oneEnResume" style="width:100%;height:200px;background-color: #fff;">
                <div class="entPicture" style="width:50%;height:100%;background-color: #959694;"></div>
                <div class="entPicture" style="width:50%;height:100%;background-color: #fff;"></div>
              </div>
            </div>
            <div class="col-md-2" style="background-color: #fff;border:1px solid;margin-right:3px;float:left">
              <div class="oneEnResume" style="width:100%;height:200px;background-color: #fff;">
                <div class="entPicture" style="width:50%;height:100%;background-color: #959694;"></div>
                <div class="entPicture" style="width:50%;height:100%;background-color: #fff;"></div>
              </div>
            </div>
        </div>
        <div class="row">
            <div class="col-md-2" style="background-color: #fff;border:1px solid;margin-right:3px;float:left">
              <div class="oneEnResume" style="width:100%;height:200px;background-color: #fff;">
                <div class="entPicture" style="width:50%;height:100%;background-color: #959694;"></div>
                <div class="entPicture" style="width:50%;height:100%;background-color: #fff;"></div>
              </div>
            </div>
            <div class="col-md-2" style="background-color: #fff;border:1px solid;margin-right:3px;float:left">
              <div class="oneEnResume" style="width:100%;height:200px;background-color: #fff;">
                <div class="entPicture" style="width:50%;height:100%;background-color: #959694;"></div>
                <div class="entPicture" style="width:50%;height:100%;background-color: #fff;"></div>
              </div>
            </div>
            <div class="col-md-2" style="background-color: #fff;border:1px solid;margin-right:3px;float:left">
              <div class="oneEnResume" style="width:100%;height:200px;background-color: #fff;">
                <div class="entPicture" style="width:50%;height:100%;background-color: #959694;"></div>
                <div class="entPicture" style="width:50%;height:100%;background-color: #fff;"></div>
              </div>
            </div>
            <div class="col-md-2" style="background-color: #fff;border:1px solid;margin-right:3px;float:left">
              <div class="oneEnResume" style="width:100%;height:200px;background-color: #fff;">
                <div class="entPicture" style="width:50%;height:100%;background-color: #959694;"></div>
                <div class="entPicture" style="width:50%;height:100%;background-color: #fff;"></div>
              </div>
            </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
import stuEnGrid from '../../components/stuEnGrid'
export default {
  compcomponents:stuEnGrid,
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

