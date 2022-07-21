<template>
<div>
    <!--충무국수-->
    <div class="storeItem" v-if="selectedStoreInfo.id == 1">

      <div class="storeInfo">
        <div class="title">충무국수</div>
        <div>053-965-3111</div>
        <div>동구 안심로 283</div>
        <div>배달이 안 되어 직접 가셔야 됩니다. / 곱배기 가격 동일</div>
      </div>

      <div class="menuWrapper flex">

        <div class="menuItem w-48">
          <div>메뉴사진</div>
          <div>불.국수</div>
          <div>잔치국수(냉,온)+돼지불고기(130g)</div>
          <div>6,000</div>
        </div>

        <div class="menuItem">
          <div>메뉴사진</div>
          <div>불.비빔</div>
          <div>비빔국수+돼지불고기(130g)</div>
          <div>7,000</div>
        </div>

        <div class="menuItem">
          <div>메뉴사진</div>
          <div>불.시래기</div>
          <div>시레기국밥+돼지불고기(130g)</div>
          <div>7,000</div>
        </div>

        <div class="menuItem">
          <div>메뉴사진</div>
          <div>잔치국수(냉,온)</div>
          <div></div>
          <div>4,000</div>
        </div>

        <div class="menuItem">
          <div>메뉴사진</div>
          <div>비빔국수</div>
          <div></div>
          <div>5,500</div>
        </div>

        <div class="menuItem">
          <div>메뉴사진</div>
          <div>칼국수</div>
          <div></div>
          <div>6,000</div>
        </div>

        <div class="menuItem">
          <div>메뉴사진</div>
          <div>시레기국밥</div>
          <div></div>
          <div>5,000</div>
        </div>
      
      </div>
    </div>
    <!--충무국수 끝-->

    <!--정담아 김밥-->
    <div class="storeItem" v-if="selectedStoreInfo.id == 2">

      <div class="storeInfo">
        <div class="title">정담아 김밥(매장)</div>
        <div>053-965-3817</div>
        <div>동구 경안로 726</div>
        <div>배달이 안 되어 직접 가셔야 됩니다.</div>
      </div>

      <div class="menuWrapper flex">

        <div class="menuItem">
          <div>메뉴사진</div>
          <div>정담아김밥</div>
          <div></div>
          <div>2,500</div>
        </div>
        <div class="menuItem">
          <div>메뉴사진</div>
          <div>매운멸치김밥</div>
          <div></div>
          <div>3,000</div>
        </div>
        <div class="menuItem">
          <div>메뉴사진</div>
          <div>치즈김밥</div>
          <div></div>
          <div>3,000</div>
        </div>
        <div class="menuItem">
          <div>메뉴사진</div>
          <div>스팸김밥</div>
          <div></div>
          <div>3,000</div>
        </div>
        <div class="menuItem">
          <div>메뉴사진</div>
          <div>참치김밥</div>
          <div></div>
          <div>3,500</div>
        </div>
        <div class="menuItem">
          <div>메뉴사진</div>
          <div>진미김밥</div>
          <div></div>
          <div>3,500</div>
        </div>
        <div class="menuItem">
          <div>메뉴사진</div>
          <div>돈가스김밥</div>
          <div></div>
          <div>3,500</div>
        </div>

        <div class="menuItem">
          <div>메뉴사진</div>
          <div>신라면</div>
          <div></div>
          <div>3,500</div>
        </div>
        <div class="menuItem">
          <div>메뉴사진</div>
          <div>우동</div>
          <div></div>
          <div>4,000</div>
        </div>
        <div class="menuItem">
          <div>메뉴사진</div>
          <div>잔치국수</div>
          <div></div>
          <div>4,000</div>
        </div>
        <div class="menuItem">
          <div>메뉴사진</div>
          <div>비빔국수</div>
          <div></div>
          <div>4,500</div>
        </div>
        <div class="menuItem">
          <div>메뉴사진</div>
          <div>쫄면</div>
          <div></div>
          <div>4,500</div>
        </div>
        <div class="menuItem">
          <div>메뉴사진</div>
          <div>비빔만두</div>
          <div></div>
          <div>4,500</div>
        </div>
        <div class="menuItem">
          <div>메뉴사진</div>
          <div>떡볶이</div>
          <div></div>
          <div>4,500</div>
        </div>

        <div class="menuItem">
          <div>메뉴사진</div>
          <div>등심돈가스</div>
          <div></div>
          <div>6,000</div>
        </div>
        <div class="menuItem">
          <div>메뉴사진</div>
          <div>제육덮밥</div>
          <div></div>
          <div>6,000</div>
        </div>
        <div class="menuItem">
          <div>메뉴사진</div>
          <div>오므라이스</div>
          <div></div>
          <div>5,500</div>
        </div>
        <div class="menuItem">
          <div>메뉴사진</div>
          <div>낙지볶음밥</div>
          <div></div>
          <div>5,500</div>
        </div>
        <div class="menuItem">
          <div>메뉴사진</div>
          <div>새우볶음밥</div>
          <div></div>
          <div>5,500</div>
        </div>

        <div class="menuItem">
          <div>메뉴사진</div>
          <div>(계절)콩국수</div>
          <div></div>
          <div>5,500</div>
        </div>

      </div>
    </div>
    <!--정담아 김밥 끝-->

    <!--영천식당-->
    <div class="storeItem font-sans" v-if="selectedStoreInfo.id == 3">

      <div class="storeInfo">
        <div class="title">영천식당</div>
        <div>053-963-1994</div>
        <div>동구 안심로 55길 26</div>
        <div></div>
      </div>

      <div class="menuWrapper flex">

        <div class="menuItem w-72 shadow-md">
          <div class="flex-none w-48 relative">메뉴사진</div>
          <div>된장찌개</div>
          <div></div>
          <div></div>
        </div>
        <div class="menuItem w-72 shadow-md">
          <div class="flex-none w-48 relative">메뉴사진</div>
          <div>김치찌개</div>
          <div></div>
          <div></div>
        </div>
        <div class="menuItem w-72 shadow-md">
          <div class="flex-none w-48 relative">메뉴사진</div>
          <div>참치찌개</div>
          <div></div>
          <div></div>
        </div>
        <div class="menuItem w-72 shadow-md">
          <div class="flex-none w-48 relative">메뉴사진</div>
          <div>제육볶음</div>
          <div></div>
          <div></div>
        </div>

      </div>
    </div>
    <!--영천식당 끝-->

    <!--진시황-->
    <div class="storeItem" v-if="selectedStoreInfo.id == 4">

      <div class="storeInfo">
        <div class="title">진시황</div>
        <div>053-963-1994</div>
        <div>동구 안심로 55길 26</div>
        <div>설명</div>
      </div>

      <div class="menuWrapper flex">

        <div class="menuItem">
          <div>메뉴사진</div>
          <div>메뉴이름</div>
          <div>가격</div>
          <div>설명</div>
        </div>

      </div>
    </div>
    <!--진시황 끝-->

    <!--한빵울-->
    <div class="storeItem" v-if="selectedStoreInfo.id == 5">

      <div class="storeInfo">
        <div class="title">한빵울</div>
        <div>053-963-1994</div>
        <div>동구 안심로 55길 26</div>
        <div>설명</div>
      </div>

      <div class="menuWrapper flex">

        <div class="menuItem">
          <div>메뉴사진</div>
          <div>메뉴이름</div>
          <div>가격</div>
          <div>설명</div>
        </div>

      </div>
    </div>
    <!--한빵울 끝-->

</div>
</template>
<script>
export default {
    name: 'StoreComponent',
    components: {},
    props: {
        selectedStoreInfo : Object
    },
    data() {
        return {
            example: '',
        }
    },
    setup() {},
    created() {},
    mounted() {},
    updated() {},
    unmounted() {},
    methods: {}
}
</script>
<style>

</style>