<template>
    <div class="max-w-7xl mx-auto grid grid-cols-4 gap-4">
        <div class="main-left col-span-1">
            <div class="p-4 bg-white border border-gray-200 rounded-lg">
                <h3 class="mb-6 text-xl">Messages</h3>

                <div class="space-y-4">
                    <div class="flex items-center justify-between">
                        <div class="flex items-center space-x-2">
                            <img src="https://i.pravatar.cc/300?img=70" class="w-[40px] rounded-full">
                                    
                            <p class="text-xs"><strong>Code With Stein</strong></p>
                        </div>

                        <span class="text-xs text-gray-500">18 minutes ago</span>
                    
                    </div>
                </div>
                
            </div>

        </div>

        <div class="main-center col-span-3 space-y-4">
            <div class="p-4 bg-white border border-gray-200 rounded-lg">
                <div class="flex flex-col flex-frow p-4">
                    <div class="flex w-full mt-2 space-x-3 max-w-md ml-auto justify-end">
                        <div>
                            <div class="bg-blue-600 text-white p-3 rounded-l-lg rounded-br-lg">
                                <p class="text-sm">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod.</p>
                            </div>
                            <span class="text-xs text-gray-500 leading-none">2 min ago</span>
                        </div>
                        <div class="flex-shrink-0 h-10 w-10 rounded-full bg-gray-300">
                            <img src="https://i.pravatar.cc/300?img=70" class="w-[40px] rounded-full">
                        </div>
                    </div>
                </div>
            </div>

            <div class="p-4 bg-white border border-gray-200 rounded-lg">
                <div class="p-4">  
                    <textarea class="p-4 w-full bg-gray-100 rounded-lg" placeholder="What are you thinking about?"></textarea>
                </div>

                <div class="p-4 border-t border-gray-100 flex justify-between">

                    <a href="#" class="inline-block py-4 px-6 bg-purple-600 text-white rounded-lg">Sent</a>
                </div>
            </div>
        </div>
    </div>
</template>