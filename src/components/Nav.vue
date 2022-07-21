<template>
<div>
    <ul>
        <li value="1" @click="selectStore($event)">충무 국수</li>
        <li value="2" @click="selectStore($event)">정담아 김밥</li>
        <li value="3" @click="selectStore($event)">영천식당</li>
        <li value="4" @click="selectStore($event)">진시황</li>
        <li value="5" @click="selectStore($event)">한빵울</li>
    </ul>
</div>
</template>
<script>

export default {
    name: 'NavComponent',
    components: {

    },
    data() {
        return {
            
        }
    },
    methods: {
        selectStore(event) { 

            let storeInfo = { 
                id : event.target.value, 
                name : event.target.innerText
            };

            this.$emit('selectedStore',storeInfo);
        }
    }
}
</script>