<script lang="ts">
  import Navbar from '$lib/Components/Navbar.svelte';
  import Footer from '$lib/Components/Footer.svelte';
</script>

<Navbar />

<main class="bg-gray-50">
  <div class="max-w-6xl mx-auto px-4 py-10">
    <!-- Page Title -->
    <h1 class="text-3xl md:text-4xl font-bold text-gray-800 mb-8">
      Introduction of the Institute
    </h1>

    <!-- Introduction Section -->
    <div class="bg-white rounded-xl shadow-sm border border-gray-200 mb-8 overflow-hidden">
      <div class="px-6 py-4 border-b bg-red-50">
        <h2 class="text-xl font-semibold text-gray-800">
          About Siddharth Industrial Training Center
        </h2>
      </div>

      <div class="px-6 py-6 space-y-4 text-gray-700 leading-relaxed text-sm md:text-base">
        <p>
          <span class="font-semibold">Siddharth Industrial Training Center, Gaya Bihar,</span> is affiliated to NCVT (National Council for Vocational Training) and directed by Harendra Kumar, with Yamuna Yadav serving as Secretary.
        </p>

        <p>
          Siddharth Shiv Trust believes in going where there is no path and leaving a trail. As a founder, he started Siddharth ITC, Gaya, in the vicinity of Delha - Kharkhura main road at 1 km stone and Gaya Railway junction to Kharkhura main road 2 km stone.
        </p>
      </div>
    </div>

    <!-- Vision Section -->
    <div class="bg-white rounded-xl shadow-sm border border-gray-200 mb-8 overflow-hidden">
      <div class="px-6 py-4 border-b bg-blue-50">
        <h2 class="text-xl font-semibold text-gray-800">
          Vision
        </h2>
      </div>

      <div class="px-6 py-6 space-y-4 text-gray-700 leading-relaxed text-sm md:text-base">
        <p>
          The institute is envisioned to develop into a premier institute focusing on strenuous training, research and development, and consultancy. It has priorities for the economically poor section of society.
        </p>
      </div>
    </div>

    <!-- Mission Section -->
    <div class="bg-white rounded-xl shadow-sm border border-gray-200 mb-8 overflow-hidden">
      <div class="px-6 py-4 border-b bg-green-50">
        <h2 class="text-xl font-semibold text-gray-800">
          Mission
        </h2>
      </div>

      <div class="px-6 py-6 space-y-4 text-gray-700 leading-relaxed text-sm md:text-base">
        <p>
          The institute has a mission to contribute towards nation building by creating superior quality technicians and highly skilled human resources that meet industrial requirements and national needs.
        </p>
      </div>
    </div>

    <!-- Policy Section -->
    <div class="bg-white rounded-xl shadow-sm border border-gray-200 overflow-hidden">
      <div class="px-6 py-4 border-b bg-purple-50">
        <h2 class="text-xl font-semibold text-gray-800">
          Policy
        </h2>
      </div>

      <div class="px-6 py-6 space-y-4 text-gray-700 leading-relaxed text-sm md:text-base">
        <p>
          The policy of the institution is to develop human resources with the ability to thrive in a changing environment. This is achieved through the participating effort of the Trust, staff, students, and parents.
        </p>
      </div>
    </div>
  </div>
</main>

<Footer />
