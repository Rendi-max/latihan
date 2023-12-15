<template>
    <div>
        <div id="profile" class="px-10 flex justify-evenly flex-wrap lg:pt-10 md:pt-5" >
            <div class="font-sans text-white py-10 lg:py-28 px-8">
                <p class="font-semibold lg:text-[32px] md:text-[20px]"> Hello, i'm</p>
                <p class="font-bold lg:text-[50px] md:text-[30px] shadow-lg"> Rendi Firman Syah</p>
                <p class="lg:text-md w-[380px] md:text-[11px]">Freelance UI designer, Fullstack developer, & Data Miner. I create seamless web experiences for end-users.</p>
                <div class="flex mt-2">
                    <div class="space-x-2">
                        <button class="cursor-pointer rounded-lg bg-indigo-500 text-md font-bold px-8 py-2 hover:bg-fuchsia-700">About me <i class="ml-2 bi bi-person"></i></button>
                        <button class="cursor-pointer rounded-lg border border-indigo-500 text-md font-bold px-8 py-2 hover:bg-fuchsia-700">Project <i class="ml-2 bi bi-eye"></i></button>
                    </div>
                </div>
            </div>
            <div class="pb-10 ">
                <img src="../image/profile.jpg" class="rounded-full lg:h-[444px] lg:w-[444px] w-[300px] h-[300px]" alt="">
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name : 'MyProfile',
    }
</script>