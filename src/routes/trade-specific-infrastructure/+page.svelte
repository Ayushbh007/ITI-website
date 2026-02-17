<script lang="ts">
  import Navbar from '$lib/Components/Navbar.svelte';
  import Footer from '$lib/Components/Footer.svelte';
</script>

<Navbar />

<main class="bg-gray-50 min-h-screen">
  <div class="max-w-3xl mx-auto px-4 py-10">
    <h1 class="text-3xl md:text-4xl font-bold text-gray-800 mb-8 text-center">
      Trade Specific Infrastructure
    </h1>
    <div class="bg-white rounded-xl shadow-sm border border-gray-200 p-6 mb-8 flex flex-col md:flex-row gap-6">
      <div class="flex-1">
        <h2 class="text-xl font-semibold text-gray-700 mb-4">ELECTRICIAN</h2>
        <table class="min-w-full border text-sm md:text-base mb-6">
          <tbody>
            <tr>
              <td class="px-4 py-2 border font-medium">Unit</td>
              <td class="px-4 py-2 border">4+4</td>
            </tr>
            <tr>
              <td class="px-4 py-2 border font-medium">Shift</td>
              <td class="px-4 py-2 border">1st and 2nd</td>
            </tr>
            <tr>
              <td class="px-4 py-2 border font-medium">Seating capacity per unit</td>
              <td class="px-4 py-2 border">20</td>
            </tr>
            <tr>
              <td class="px-4 py-2 border font-medium">Total seating capacity</td>
              <td class="px-4 py-2 border">80</td>
            </tr>
          </tbody>
        </table>
        <h2 class="text-xl font-semibold text-gray-700 mb-4 mt-8">FITTER</h2>
        <table class="min-w-full border text-sm md:text-base">
          <tbody>
            <tr>
              <td class="px-4 py-2 border font-medium">Unit</td>
              <td class="px-4 py-2 border">2+2</td>
            </tr>
            <tr>
              <td class="px-4 py-2 border font-medium">Shift</td>
              <td class="px-4 py-2 border">1st and 2nd</td>
            </tr>
            <tr>
              <td class="px-4 py-2 border font-medium">Seating capacity per unit</td>
              <td class="px-4 py-2 border">20</td>
            </tr>
            <tr>
              <td class="px-4 py-2 border font-medium">Total seating capacity</td>
              <td class="px-4 py-2 border">40</td>
            </tr>
          </tbody>
        </table>
      </div>
      <div class="md:w-64 flex-shrink-0 flex flex-col items-end justify-between gap-4">
        <div class="bg-gray-100 rounded-lg px-4 py-3 text-right w-full">
          <div class="font-semibold text-gray-700">DGETST-12-01/2009-JC</div>
          <div class="text-gray-600">DGET code - 11/09/2009</div>
        </div>
      </div>
    </div>
  </div>
</main>

<Footer />
