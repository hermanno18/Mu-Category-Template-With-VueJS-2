<template>
    <div class="  text-white  h-full">
        <div>
        </div>
        
        <div class="  bg-opacity-100 px-3 py-1 grid grid-cols-3 w-full navBar items-center" >
            <div class=' flex place-content-start space-x-16 items-center font-bold'>  
                <div class="logo">
                    <i class="fas fa-qrcode"></i>
                </div>
                <div class=" pl-2">
                    <img src="../assets/img/logo.png" alt="" class="mx-6  h-7 w-7" />
                </div>
            </div>
        
            <div  class=' flex place-content-center items-center'>
                <div class=" w-80 text-center"> 
                    <form action="">
                        <div class="container  flex mx-auto">
                            <div class="flex overflow-hidden text-white rounded-full  bg-white bg-opacity-10">
                                <button class="flex items-center justify-center px-4 ">
                                    <svg class="w-4 h-4 " fill="currentColor" xmlns="http://www.w3.org/2000/svg"
                                        viewBox="0 0 24 24">
                                        <path
                                            d="M16.32 14.9l5.39 5.4a1 1 0 0 1-1.42 1.4l-5.38-5.38a8 8 0 1 1 1.41-1.41zM10 16a6 6 0 1 0 0-12 6 6 0 0 0 0 12z">
                                        </path>
                                    </svg>
                                </button>
                                <input type="text" class="px-4 py-1 w-80 focus:outline-none focus:border-none bg-transparent placeholder-gray-300" placeholder="Recherche..." />
                            </div>
                        </div>
                    </form>
                </div>
            </div>
        
            <div  class=' flex place-content-between items-center font-bold'>
                <div class="text-red-500">
                        <i class="fas fa-qrcode"></i>
                </div>
                <div class="user-info flex space-x-1 items-center">
                    <div class="">
                        <div class="h-5 w-5 overflow-hidden rounded-full">
                            <img src="" alt="" class="w-full h-full" />
                        </div>
                    </div>
                    <div class="pr-3">
                        Halimatou
                    </div>
                    <div class="">
                        <i class="fas fa-ellipsis-v"></i>
                    </div>
                </div>
            </div>
            
        </div> 
        <div class=" bg-black  py-0 grid grid-cols-12 w-full backdrop-filter backdrop-blur-sm   bg-opacity-90 font-bold">
            <div class=' flex place-content-center  items-center col-span-2'>  
                <div class="logo ">
                    Smuuse
                </div>
            </div>
        
            <div  class=' flex place-content-center col-span-7'>
                <div class=" w-72 place-content-center flex items-center space-x-20 uppercase"> 
                    <div class="ml-12">
                        flow
                    </div>
                    <div class="mx-2">
                        sista's
                    </div>
                </div>
            </div>
            <div class="col-span-1"></div>
            <div  class=' flex place-content-between col-span-2 px-7'>
                <div>
                </div>
                <div class="user-info flex items-center space-x-3 text-xl">
                    <div class="">
                        <i class="fas fa-cloud-upload-alt"></i>
                    </div>
                    <div class="">
                        <i class="fas fa-bell"></i>
                    </div>
                    <div class="">
                        <i class="fas fa-cog"></i>
                    </div>
                </div>
            </div>
            
        </div>              
    </div>
</template>
<script lang="ts">

export default {
    name:'NavBar'
}
</script>