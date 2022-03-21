<template>
    <section id="footer-section" class="bg-gray-800">
        <div class="container mx-auto py-6">
            <footer class="footer-section" style="font-family: 'Poppins', sans-serif;">
                <div class="border-color mx-auto">
                    <div class="container mx-auto flex  pt-12 flex-col lg:flex-row items-center space-y-5 lg:space-y-0">
                        <div class="flex title-font font-medium items-center text-gray-600 mb-4 lg:mb-0 md:mb-0 space-x-5"
                            style="cursor: pointer;">
                        </div>
                        <nav class="mx-auto flex flex-wrap items-center text-base justify-center space-x-5">
                            <a href="" class=" text-gray-600"></a>
                            <a href="" class=" text-gray-600"></a>
                            <a href="" class=" text-gray-600"></a>
                        </nav>
                        <nav class="flex lg:flex-row flex-col items-center text-gray-600 text-base justify-center">
                            <p>Copyright © {{years}} Zainal21.</p>
                        </nav>
                    </div>
                </div>
            </footer>
        </div>
    </section>
</template>


<script>
    export default {
        name: 'Footer',
        computed: {
            years() {
                return new Date().getFullYear()
            }
        }
    }
</script>

<style scoped>

</style>