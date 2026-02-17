<script lang="ts">
  import Navbar from '$lib/Components/Navbar.svelte';
  import Footer from '$lib/Components/Footer.svelte';
</script>

<Navbar />

<main class="bg-gray-50 min-h-screen">
  <div class="max-w-4xl mx-auto px-4 py-10">
    <h1 class="text-3xl md:text-4xl font-bold text-gray-800 mb-8 text-center">
      Administrative Staff
    </h1>
    <div class="bg-white rounded-xl shadow-sm border border-gray-200 p-6 mb-10">
      <h2 class="text-xl font-semibold text-gray-700 mb-4">Administrative Staff</h2>
      <div class="overflow-x-auto">
        <table class="min-w-full border text-sm md:text-base">
          <thead class="bg-gray-100">
            <tr>
              <th class="px-4 py-2 border">S.No</th>
              <th class="px-4 py-2 border">Name of staff</th>
              <th class="px-4 py-2 border">Designation</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td class="px-4 py-2 border">1</td>
              <td class="px-4 py-2 border">HARENDRA kumar</td>
              <td class="px-4 py-2 border">Administrative Officer</td>
            </tr>
            <tr>
              <td class="px-4 py-2 border">2</td>
              <td class="px-4 py-2 border">Rakesh kumar</td>
              <td class="px-4 py-2 border">Office Assistant</td>
            </tr>
            <tr>
              <td class="px-4 py-2 border">3</td>
              <td class="px-4 py-2 border">Brajesh kumar</td>
              <td class="px-4 py-2 border">Guard</td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>

    <div class="text-center mt-8">
      <a href="#" class="inline-block bg-blue-600 hover:bg-blue-700 text-white font-semibold px-6 py-3 rounded-lg shadow transition">
        Apply for instructor job - Online Apply for ITI instructor job
      </a>
    </div>
  </div>
</main>

<Footer />
