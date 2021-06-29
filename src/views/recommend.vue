<template>
  <div>
    xxxxd
  </div>
</template>

<script>
import { getRecommend } from '@/service/recommend'
export default {
  name: 'recommend',
  created () {
    getRecommend()
  }
}
</script>

<style lang="scss" scoped>

</style>
