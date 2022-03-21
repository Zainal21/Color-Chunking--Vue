<template>
    <section id="header-section" class="w-full px-6 bg-gray-800 border-b border-gray-600 antialiased">
        <div class="mx-auto max-w-7xl">
            <nav class="relative z-50 h-24 select-none" x-data="{ showMenu: false }">
                <div
                    class="container relative flex flex-wrap items-center justify-between h-24 mx-auto overflow-hidden font-medium  md:overflow-visible lg:justify-center sm:px-4 md:px-2">
                    <div class="flex items-center justify-start w-1/4 h-full pr-4">
                        <a href="#" class="inline-block py-4 md:py-0">
                            <span class="p-1 text-xl font-black leading-none text-gray-200"><span>Chunking Design
                                    System</span><span class="text-gray-200">.</span></span>
                        </a>
                    </div>
                    <div class="top-0 left-0 items-start hidden w-full h-full p-4 text-sm bg-gray-900 bg-opacity-50 md:items-center md:w-3/4 md:absolute lg:text-base md:bg-transparent md:p-0 md:relative md:flex"
                        :class="{'flex fixed': showMenu, 'hidden': !showMenu }">
                        <div
                            class="flex-col w-full h-auto overflow-hidden bg-white rounded-lg md:bg-transparent md:overflow-visible md:rounded-none md:relative md:flex md:flex-row">
                            <a href="#"
                                class="inline-flex items-center block w-auto h-16 px-6 text-xl font-black leading-none text-gray-900 md:hidden">Fundraising
                                System<span class="text-indigo-600">.</span></a>
                        </div>
                    </div>
                </div>
            </nav>
        </div>
    </section>
</template>

<style scoped>

</style>

<script>
    export default {
        name: 'Header',
        data: () => {
            return {
                showMenu: false
            }
        }
    }
</script>