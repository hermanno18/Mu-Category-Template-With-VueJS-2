<template>
        <div class="bg-gray-100 min-h-screen text-sm">
            <div class=" w-full fixed z-30 backdrop-filter backdrop-blur-sm  bg-opacity-90 h-16" id="NavBarContainer">
                <NavBar/>
            </div>
            <div class="grid grid-cols-12 pt-16" id="">
                <div class="bg-white h-full col-span-2  z-20  col-md-1" id="">
                    <SideNav/>
                </div>
                
                <div class=" bg-white h-full col-span-10 right-0   col-md-12" id="">
                    <div class="bg-white backdrop-filter backdrop-blur-sm  z-20 bg-opacity-20 h-28 fixed w-full" id="">
                        <SubNav/>
                    </div>
                    <div class=" mt-28 pb-4" id="">
                        <PageContent/>
                    </div>
                </div>
            </div>
        </div>
</template>

<script>
import NavBar from "./NavBar.vue"
import SideNav from "./SideNav"
import PageContent from "./PageContent"
import SubNav from "./SubNav"
export default {
  name: 'Page',
  props: {
    msg: String
  },
  components: {
      NavBar,
      SideNav,
      PageContent,
      SubNav
  }

}
</script>