<template>
        <div class=" space-y-5">
            <Section v-for="(SectionTitle) in SectionTitles" :key="SectionTitle" :id="SectionTitle.title + '_section'" :title="SectionTitle.title" :icon="SectionTitle.icon"  />
        </div>
</template>
<script>
import Section from "./Section.vue"
export default {
    name: "PageContent",
    components:{
        Section
    },
    data:function() {
        return {
                SectionTitles: [
                    {
                        title:"Tendances",
                        icon:"fas fa-fire-alt text-red-500"
                    },
                    {
                        title:"Medecine Prophétique",
                    },
                    {
                        title:"Medecine",
                    },
                    {
                        title:"systeme immunitaire",
                    },
                    {
                        title:"bien être",
                    },

                ]
            };
    }
    
}
</script>