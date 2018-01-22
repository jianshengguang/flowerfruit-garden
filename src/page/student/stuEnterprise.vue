<template>
  <div class="stuWholeContent">
    <div class="blankUnderNavi" style="height:101px;magin-top:71px;"></div>
    <div class="container">    
      <stuEnGrid></stuEnGrid>
      <stuEnGrid></stuEnGrid>
      <stuEnGrid></stuEnGrid>
    </div>
    <div class="moreEnterperise">
      <button type="button" class="btn btn-default btn-lg"><span class="glyphicon glyphicon-plus" aria-hidden="true"></span>查看更多</button>
    </div>
  </div>
</template>
<script>
import stuEnGrid from '../../components/stuEnGrid'
export default {
  components: {
    stuEnGrid
  },
  
}
</script>

