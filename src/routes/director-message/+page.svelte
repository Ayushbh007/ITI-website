<script lang="ts">
  import Navbar from '$lib/Components/Navbar.svelte';
  import Footer from '$lib/Components/Footer.svelte';
</script>

<Navbar />

<main class="bg-gray-50 min-h-screen">
  <div class="max-w-3xl mx-auto px-4 py-10">
    <h1 class="text-3xl md:text-4xl font-bold text-gray-800 mb-8 text-center">
      Director's Message
    </h1>
    <div class="bg-white rounded-xl shadow-sm border border-gray-200 p-8 mb-8">
      <h2 class="text-xl font-semibold text-gray-700 mb-4">Message from the Director</h2>
      <p class="text-gray-700 leading-relaxed text-base md:text-lg">
        Welcome to Siddharth Industrial Training Center, Gaya. Our mission is to empower students with the skills, knowledge, and values needed to excel in the modern industrial world. We are committed to providing quality education and hands-on training, ensuring our students are well-prepared for the challenges and opportunities ahead.<br><br>
        As Director, I believe in fostering an environment of innovation, discipline, and continuous improvement. Our dedicated faculty and staff work tirelessly to support every student’s growth and success. We encourage you to make the most of the resources and opportunities available at our institute.<br><br>
        Together, let us strive for excellence and contribute to the progress of our society and nation.
      </p>
      <div class="mt-8 text-right">
        <span class="font-semibold text-gray-800">Harendra Kumar</span><br>
        <span class="text-gray-600">Director</span>
      </div>
    </div>
  </div>
</main>

<Footer />
