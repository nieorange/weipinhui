<template>
    <div class="fransnana">
        <Search></Search>
        <TopNav></TopNav>
        <Banner></Banner>
        <Classify></Classify>
        <SaleHot></SaleHot>
        <SaleFast></SaleFast>
        <Promotion></Promotion>
    </div>
</template>
<script>
import Banner from './components/banner'
import Classify from './components/classify'
import SaleHot from './components/saleHot'
import SaleFast from './components/saleFast'
import Promotion from '@/components/home/components/promotion'
import Search from '@/common/search'
import TopNav from '@/common/topNav'
export default {
  data () {
    return {

    }
  },
  components: {
    Banner,
    Classify,
    SaleHot,
    SaleFast,
    Promotion,
    Search,
    TopNav
  }
}
</script>

<style lang="less" scoped>
.fransnana{
  margin-top: 80px;
}
</style>
