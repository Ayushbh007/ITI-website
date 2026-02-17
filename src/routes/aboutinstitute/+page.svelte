<script lang="ts">
  import Navbar from '$lib/Components/Navbar.svelte';
  import Footer from '$lib/Components/Footer.svelte';
</script>

<Navbar />

<main class="bg-gray-50">
  <div class="max-w-6xl mx-auto px-4 py-10">
    <!-- Page Title -->
    <h1 class="text-3xl md:text-4xl font-bold text-gray-800 mb-8">
      About Institute
    </h1>

    <!-- Institute Details Card -->
    <div class="bg-white rounded-xl shadow-sm border border-gray-200 mb-10 overflow-hidden">
      <div class="px-6 py-4 border-b bg-gray-100">
        <h2 class="text-xl font-semibold text-gray-700">
          Institute Information
        </h2>
      </div>

      <div class="overflow-x-auto">
        <table class="w-full text-sm md:text-base">
          <tbody class="divide-y">
            <tr>
              <td class="px-6 py-3 font-medium text-gray-700 w-1/3">
                Name of the Institute
              </td>
              <td class="px-6 py-3 text-gray-600">
                Siddharth Private Industrial Training Institute
              </td>
            </tr>

            <tr>
              <td class="px-6 py-3 font-medium text-gray-700">
                Address of the Institute
              </td>
              <td class="px-6 py-3 text-gray-600">
                Kharkhura main road Delha Gaya (823002)
              </td>
            </tr>

            <tr>
              <td class="px-6 py-3 font-medium text-gray-700">
                Date of Establishment
              </td>
              <td class="px-6 py-3 text-gray-600">
                18/09/2009
              </td>
            </tr>

            <tr>
              <td class="px-6 py-3 font-medium text-gray-700">
                DGET File Reference No.
              </td>
              <td class="px-6 py-3 text-gray-600">
                DGET-12/01/2009-TC
              </td>
            </tr>

            <tr>
              <td class="px-6 py-3 font-medium text-gray-700">
                Code Allocated by DGET
              </td>
              <td class="px-6 py-3 text-gray-600">
                PR10000235
              </td>
            </tr>

            <tr>
              <td class="px-6 py-3 font-medium text-gray-700">
                Mobile No.
              </td>
              <td class="px-6 py-3 text-gray-600">
                7004607280, 9934630175
              </td>
            </tr>

            <tr>
              <td class="px-6 py-3 font-medium text-gray-700">
                Email ID
              </td>
              <td class="px-6 py-3 text-gray-600">
                siddharthitcgaya967@gmail.com
              </td>
            </tr>

            <tr>
              <td class="px-6 py-3 font-medium text-gray-700">
                Location
              </td>
              <td class="px-6 py-3 text-gray-600">
                  <div class="w-full flex justify-center">
                    <iframe
                      src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3621.609613535115!2d84.9918041112695!3d24.80881784722954!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x39f32a7000ee644f%3A0x24d43be89cbeb59f!2sSiddharth%20ITI!5e0!3m2!1sen!2sin!4v1771348231251!5m2!1sen!2sin"
                      width="350"
                      height="200"
                      style="border:0;"
                      allowfullscreen=""
                      loading="lazy"
                      referrerpolicy="no-referrer-when-downgrade"
                    ></iframe>
                  </div>
              </td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>

    <!-- NCVT Section -->
    <div class="bg-white rounded-xl shadow-sm border border-gray-200 p-6">
      <h2 class="text-2xl font-semibold text-gray-800 mb-4">
        National Council for Vocational Training (NCVT)
      </h2>

      <div class="space-y-4 text-gray-700 leading-relaxed text-sm md:text-base">
        <p>
          In pursuance of the recommendation of the All India Council for Technical
          Education, the Government of India in the Ministry of Labour Resolution
          No. RTA-428 (5) dated 22nd May, 1951, appointed a committee called the
          National Trade Certification Investigation Committee with instructions
          to prepare a scheme for the establishment of an All India Trades Board.
        </p>

        <p>
          The report of this committee, along with the recommendations of the
          Training and Employment Services Organisation Committee (Shiva Rao
          Committee), was considered by the Government of India. It was agreed
          that a central agency was required to coordinate training programmes,
          maintain uniform standards, and award National Trade Certificates.
        </p>

        <p>
          These steps were considered essential in the interest of both industry
          and workers, ensuring that certificate holders possess a recognised
          degree of skill and enabling mobility of tradesmen and employment
          opportunities.
        </p>

        <p>
          The Government of India later transferred the administration of training
          organisations to the respective State Governments while retaining
          policy-level coordination at the central level. This led to the formal
          establishment of the National Council for Vocational Training (NCVT) in
          1956.
        </p>

        <p>
          The NCVT is responsible for prescribing training standards and
          curricula, advising the Government of India on training policies,
          conducting All India Trade Tests, and awarding National Trade
          Certificates. The council includes representatives from central and
          state governments, employers, workers’ organisations, professional
          bodies, and social groups.
        </p>

        <p>
          State Councils for Vocational Training and Trade Committees have also
          been established to assist the NCVT in fulfilling its responsibilities
          across the country.
        </p>
      </div>
    </div>
  </div>
</main>

<Footer />
