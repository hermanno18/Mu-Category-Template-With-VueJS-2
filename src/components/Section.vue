<template>
    <div class="section py-2 px-9 ">
        <div class="py-2 mb-2 text-gray-400 font-semibold">
            <div>
                <span class ="text-xl capitalize"> <i v-if="icon" :class="icon"></i> {{title}} </span>
            </div>
        </div>
        <div class=" swiper " v-if="id == 'Tendances_section'">
            <div class=" flex place-content-between space-x-10 overflow-hidden swiper-wrapper snap-x">
                <VideoItem v-for="inch in count" :key="inch" class="swiper-slide snap-center" :id="4"></VideoItem>
                <VideoItem v-for="inch in countMore" :key="inch" class="swiper-slide snap-center"    :id="4"></VideoItem>
            </div>
        </div>
        <div class="flex place-content-between" v-if="id != 'Tendances_section'">
            <VideoItem v-for="inch in count" :key="inch" id="4"></VideoItem>
        </div>

    </div>
</template>

<script>
import VideoItem from './VideoItem.vue'
export default {
    name: "Section",
    components:{
        VideoItem
    },
    props:
    {
        title: String,
        icon:String,
        id: String
    },
    data:function(){
        return {
            count : [1,2,3,4],
            countMore : [1,2],
        }
    }
}
</script>
