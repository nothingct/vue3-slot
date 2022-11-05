<template>
  <MyBtn>
    <template #icon>
      <span>(H)</span>
    </template>
    <template #text>
      <span>Here Comes The Life.</span>
    </template>
  </MyBtn>  
</template>
<script>

import MyBtn from '~/components/MyBtn'
export default {
  components:{
    MyBtn
  }
}
</script>
