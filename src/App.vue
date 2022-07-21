<template>
<div>
  <div class="bg-red-400 text-3xl">
    테스트
  </div>
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
@import "/dist/output.css";
</style>
