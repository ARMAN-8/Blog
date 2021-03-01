<template>
    <div>
        <nav class="bg-white">
            <div class="max-w-7xl mx-auto px-2 sm:px-6 lg:px-8">
                <div class="flex items-center justify-content-between h-16">
                    <div class="flex items-center">
                        <div class="text-3xl font-extrabold mx-2 border-r border-black-300 pr-5">
                            Medium
                        </div>
                        <div class="font-medium text-xl mx-4">Good Morning</div>
                    </div>
                    <div class="flex items-center ml-auto">
                        <span class="mx-3">
                            <img class="img-fluid" src="../assets/icons/loupe.svg" alt="" width="17"/>
                        </span>
                        <span class="mx-3">
                            <img class="img-fluid" src="../assets/icons/saves.svg" alt="" width="17"/>
                        </span>
                        <span class="mx-3">
                            <img class="img-fluid" src="../assets/icons/bell.svg" alt="" width="17"/>
                        </span>
                        <button class="px-3 py-1 bg-green-400 text-white rounded">Upgrade</button>
                        <span class="mx-3">
                            <img class="img-fluid" src="../assets/icons/astronaut.svg" alt="" width="17"/>
                        </span>
                    </div>
                </div>
            </div>
        </nav>
        <div class="max-w-7xl mx-auto px-2 sm:px-6 lg:px-8 my-8">
            <div class="grid grid-flow-cols-1 md:grid-flow-cols-2 lg:grid-flow-cols-2 grid-cols-2 grid-rows-2 gap-4">
                <div class="grid-1 p-0">
                    <div>
                        <img src="../assets/atom.jpeg" alt=""/>
                    </div>
                    <div class="my-4">
                        <a class="flex items-center" href="#">
                            <img src="https://www.digiseller.ru/preview/828276/p1_2970176_e84d10cf.jpg" alt=""
                                 style="height: 30px; width: 30px;"/>
                            <span class="font-medium ml-2">Thomas Muller</span>
                        </a>
                    </div>
                    <div class="font-bold my-2">
                        <a href="#">
                            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aut eius illo optio
                            reprehenderit...
                        </a>
                    </div>
                    <div class="font-thin my-2">
                        Feb 27 . 25 min read
                    </div>
                </div>
                <div class="grid-2 border border-red-600">
                    <div class="">
                        <div class="flex justify-content-between">
                        <div class="flex-1">
                            <div class="my-4">
                                <a class="flex" href="#">
                                    <img src="https://www.digiseller.ru/preview/828276/p1_2970176_e84d10cf.jpg" alt=""
                                         style="height: 30px; width: 30px;"/>
                                    <span class="font-medium ml-2">Kevin De Bruyne</span>
                                </a>
                            </div>
                            <div class="font-bold my-2">
                                <a href="#">
                                    Lorem ipsum dolor sit amet, consectetur adipisicing elit...
                                </a>
                            </div>
                            <div class="font-thin my-2">
                                Feb 27 . 25 min read
                            </div>
                        </div>
                        <div class="flex-1">
                            <img src="https://miro.medium.com/fit/c/100/100/1*mqyZkH6wzrovXoUeVN-fxg.jpeg" alt="" style=""/>
                        </div>
                    </div>
                    </div>
                </div>
            </div>
        </div>
        <hr>
    </div>
</template>
<script>
    export default {
        name: 'mainNavbar',
    }
</script>
