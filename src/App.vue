<script setup>
  import Header from './components/layouts/Header.vue'
  import Footer from './components/layouts/Footer.vue'
  import ColorSwatch from './components/design/ColorSwatch.vue'
</script>

<template>
  <div id="app">
    <Header />
    <section class="px-4 lg:px-6 pt-12 pb-24 bg-gray-800">
      <div class="relative mx-auto max-w-2xl md:max-w-3xl">
        <div class="space-y-12">
          <div class="e-content">
            <div class="prose lg:prose-lg prose-base prose-invert prose-chungking">
              <h2 class="font-bold text-2xl text-gray-200 mb-5">Colors</h2>
              <h3 class="mb-4 text-xl text-gray-300">Shimmer</h3>
              <ColorSwatch colorName="#C2C2C2" style="background-color:#C2C2C2" />
              <h3 class="mb-4 text-xl text-gray-300">Red</h3>
              <ColorSwatch colorName="#F87171" style="background-color:#F87171" />
              <ColorSwatch colorName="#EF4444" style="background-color:#EF4444" />
              <ColorSwatch colorName="#DC2626" style="background-color:#DC2626" />
              <ColorSwatch colorName="#B91C1C" style="background-color:#B91C1C" />
              <h3 class="mb-4 text-xl text-gray-300">Yellow</h3>
              <ColorSwatch colorName="#FFAD46" style="background-color:#FFAD46" />
              <ColorSwatch colorName="#FBBF24" style="background-color:#FBBF24" />
              <ColorSwatch colorName="#F59E0B" style="background-color:#F59E0B" />
              <ColorSwatch colorName="#D97706" style="background-color:#D97706" />
              <ColorSwatch colorName="#B45309" style="background-color:#B45309" />
              <ColorSwatch colorName="#92400E" style="background-color:#92400E" />
              <h3 class="mb-4 text-xl text-gray-300">Gray</h3>
              <ColorSwatch colorName="#FAFAFA" style="background-color:#FAFAFA" />
              <ColorSwatch colorName="#F5F5F5" style="background-color:#F5F5F5" />
              <ColorSwatch colorName="#F3F4F6" style="background-color:#F3F4F6" />
              <ColorSwatch colorName="#EEEEEE" style="background-color:#EEEEEE" />
              <ColorSwatch colorName="#E5E7EB" style="background-color:#E5E7EB" />
              <ColorSwatch colorName="#E0E0E0" style="background-color:#E0E0E0" />
              <ColorSwatch colorName="#BDBDBD" style="background-color:#BDBDBD" />
              <ColorSwatch colorName="#9CA3AF" style="background-color:#9CA3AF" />
              <ColorSwatch colorName="#9E9E9E" style="background-color:#9E9E9E" />
              <ColorSwatch colorName="#757575" style="background-color:#757575" />
              <ColorSwatch colorName="#616161" style="background-color:#616161" />
              <ColorSwatch colorName="#6B7280" style="background-color:#6B7280" />
              <ColorSwatch colorName="#4B5563" style="background-color:#4B5563" />
              <ColorSwatch colorName="#374151" style="background-color:#374151" />
              <h3 class="mb-4 text-xl text-gray-300">Deep Orage</h3>
              <ColorSwatch colorName="#FF9E80" style="background-color:#FF9E80" />
              <ColorSwatch colorName="#FFAB91" style="background-color:#FFAB91" />
              <ColorSwatch colorName="#FF8A65" style="background-color:#FF8A65" />
              <ColorSwatch colorName="#FF7043" style="background-color:#FF7043" />
              <ColorSwatch colorName="#FF6E40" style="background-color:#FF6E40" />
              <ColorSwatch colorName="#FF5722" style="background-color:#FF5722" />
              <ColorSwatch colorName="#F4511E" style="background-color:#F4511E" />
              <ColorSwatch colorName="#E64A19" style="background-color:#E64A19" />
              <ColorSwatch colorName="#D84315" style="background-color:#D84315" />
              <ColorSwatch colorName="#BF360C" style="background-color:#BF360C" />
              <ColorSwatch colorName="#FF3D00" style="background-color:#FF3D00" />
              <ColorSwatch colorName="#DD2C00" style="background-color:#DD2C00" />
              <h3 class="mb-4 text-xl text-gray-300">Indigo</h3>
              <ColorSwatch colorName="#C5CAE9" style="background-color:#C5CAE9" />
              <ColorSwatch colorName="#9FA8DA" style="background-color:#9FA8DA" />
              <ColorSwatch colorName="#8C9EFF" style="background-color:#8C9EFF" />
              <ColorSwatch colorName="#7986CB" style="background-color:#7986CB" />
              <ColorSwatch colorName="#5C6BC0" style="background-color:#5C6BC0" />
              <ColorSwatch colorName="#536DFE" style="background-color:#536DFE" />
              <ColorSwatch colorName="#3F51B5" style="background-color:#3F51B5" />
              <ColorSwatch colorName="#3949AB" style="background-color:#3949AB" />
              <ColorSwatch colorName="#303F9F" style="background-color:#303F9F" />
              <ColorSwatch colorName="#283593" style="background-color:#283593" />
              <ColorSwatch colorName="#1A237E" style="background-color:#1A237E" />
              <h3 class="mb-4 text-xl text-gray-300">Cyan</h3>
              <ColorSwatch colorName="#E0F7FA" style="background-color:#E0F7FA" />
              <ColorSwatch colorName="#B2EBF2" style="background-color:#B2EBF2" />
              <ColorSwatch colorName="#B2EBF2" style="background-color:#B2EBF2" />
              <ColorSwatch colorName="#80DEEA" style="background-color:#80DEEA" />
              <ColorSwatch colorName="#84FFFF" style="background-color:#84FFFF" />
              <ColorSwatch colorName="#00E5FF" style="background-color:#00E5FF" />
              <ColorSwatch colorName="#26C6DA" style="background-color:#26C6DA" />
              <ColorSwatch colorName="#00B8D4" style="background-color:#00B8D4" />
              <ColorSwatch colorName="#00BCD4" style="background-color:#00BCD4" />
              <ColorSwatch colorName="#00ACC1" style="background-color:#00ACC1" />
              <ColorSwatch colorName="#0097A7" style="background-color:#0097A7" />
              <ColorSwatch colorName="#00838F" style="background-color:#00838F" />
            </div>
          </div>
        </div>
      </div>
    </section>
    <Footer />
  </div>
</template>

<style>
  #app {
    font-family: 'Poppins', sans-serif;
  }

  .bg-chungking-grey-800 {
    --tw-bg-opacity: 1;
    background-color: rgb(43 43 48/var(--tw-bg-opacity));
  }
</style>w