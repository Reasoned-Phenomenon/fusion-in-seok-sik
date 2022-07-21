<template>
<div>
  <!--Nav-->
  <div>
    <Nav 
      @selectedStore="selectedStoreInfo=$event;"
    >
    </Nav>
  </div>
  <!--Nav 끝-->

  <!--메뉴판-->
  <div>
    <StoreComponent 
      :selectedStoreInfo="selectedStoreInfo"
    >
    </StoreComponent>
  </div>
  <!--메뉴판-->

</div>
</template>

<script>
import Nav from './components/Nav.vue'
import StoreComponent from './components/Store.vue'

export default {
  name: 'App',
  components: {
    Nav,
    StoreComponent
  },
  data () {
    return {
      selectedStoreInfo : {},
    }
  }
}
</script>

<style>
.storeItem {
  text-align: left;
}
.storeInfo .title {
  font-size: 20px;
  font-weight: bold;
}
</style>
