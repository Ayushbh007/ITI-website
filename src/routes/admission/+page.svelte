<script lang="ts">
  import Navbar from '$lib/Components/Navbar.svelte';
  import Footer from '$lib/Components/Footer.svelte';
</script>

<Navbar />

<main class="bg-gray-50 min-h-screen">
  <div class="max-w-3xl mx-auto px-4 py-10">
    <h1 class="text-3xl md:text-4xl font-bold text-gray-800 mb-8 text-center">Admission</h1>
    <div class="bg-white rounded-xl shadow-sm border border-gray-200 p-6 mb-8">
      <h2 class="text-xl font-semibold text-gray-700 mb-4">Course</h2>
      <p class="mb-2">Electrician & Fitter, 2 years course</p>
      <h2 class="text-xl font-semibold text-gray-700 mb-4 mt-8">Admission Criteria</h2>
      <div class="space-y-4 text-gray-700 leading-relaxed text-base">
        <p>नमस्कार,<br>
        आईटीआई, ITI Admission 2026 में विद्यार्थियों को प्रवेश।</p>
        <p>सत्र - 2026-28 में नामांकन<br>
        <span class="font-semibold">15 फरवरी 2026 से प्रारंभ</span><br>
        <span class="font-semibold">Last date</span> - सीट उपलब्ध रहने पर 31 जुलाई 2026 तक (सीमित सीटें)</p>
        <p>सत्र 2026-28 का क्लास<br>
        <span class="font-semibold">01 सितंबर 2026 से प्रारंभ</span></p>
        <h3 class="font-semibold mt-6 mb-2">नामांकन प्रक्रिया:</h3>
        <ul class="list-disc pl-6">
          <li>एडमिशन टेस्ट सेंटर संस्था के कार्यालय से नामांकन फॉर्म प्राप्त करें, फोटो एवं अन्य आवश्यक शैक्षणिक प्रमाण पत्रों के साथ 10,800 रुपये संस्था के कार्यालय में भुगतान कर उसी समय प्रवेश प्राप्त करेंगे।</li>
        </ul>
        <h3 class="font-semibold mt-6 mb-2">नामांकन के लिए योग्यता:</h3>
        <div class="overflow-x-auto mb-4">
          <table class="min-w-full border text-sm md:text-base">
            <thead class="bg-gray-100">
              <tr>
                <th class="px-4 py-2 border">ट्रेड (Products)</th>
                <th class="px-4 py-2 border">प्रशिक्षण अवधि</th>
                <th class="px-4 py-2 border">शैक्षणिक योग्यता</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td class="px-4 py-2 border">ELECTRICIAN</td>
                <td class="px-4 py-2 border">2 years</td>
                <td class="px-4 py-2 border">किसी के साथ 10वीं उत्तीर्ण या इसके समकक्ष</td>
              </tr>
              <tr>
                <td class="px-4 py-2 border">FITTER</td>
                <td class="px-4 py-2 border">2 years</td>
                <td class="px-4 py-2 border">किसी के साथ 10वीं उत्तीर्ण या इसके समकक्ष</td>
              </tr>
            </tbody>
          </table>
        </div>
        <p>नियमित ट्रेनिंग प्राप्त करने इच्छुक छात्र/छात्राओं के लिए न्यूनतम 80% उपस्थिति अनिवार्य है।</p>
        <h3 class="font-semibold mt-6 mb-2">उम्र:</h3>
        <p>नामांकन करने के वर्ष में 1 अगस्त को 14 से कम एवं 32 से अधिक न हो।</p>
        <h3 class="font-semibold mt-6 mb-2">परीक्षा प्रक्रिया:</h3>
        <ul class="list-disc pl-6">
          <li>काउंसलिंग एवं लिखित परीक्षा: सभी working day में नामांकन के लिए संस्था में लिखित परीक्षा आयोजित किया जाता है।</li>
        </ul>
        <h3 class="font-semibold mt-6 mb-2">प्रश्न-पत्र:</h3>
        <p>9th एवं 10th स्तर के हिंदी, गणित, सामान्य ज्ञान, अंग्रेजी एवं विज्ञान से प्रश्न पूछे जाएंगे।</p>
        <h3 class="font-semibold mt-6 mb-2">परीक्षा की अवधि:</h3>
        <p>लिखित परीक्षा 1 घंटे की होगी।</p>
      </div>
    </div>
    <div class="bg-white rounded-xl shadow-sm border border-gray-200 p-6 mb-8">
      <h2 class="text-xl font-semibold text-gray-700 mb-4">नामांकन के समय संस्थान के कार्यालय में जमा होने वाले दस्तावेज-पत्र की सूची</h2>
      <ol class="list-decimal pl-6 text-gray-700 leading-relaxed text-base">
        <li>10वीं की मार्कशीट</li>
        <li>विद्यालय परित्याग प्रमाण-पत्र (SLC)</li>
        <li>आधार कार्ड</li>
        <li>पता प्रमाण-पत्र</li>
        <li>उपर्युक्त सभी प्रमाण-पत्रों का छायाप्रति (photocopy)</li>
        <li>5 पासपोर्ट साइज फोटो (हाल ही में खींचा गया)</li>
        <li>स्टूडेंट आईडी कार्ड</li>
        <li>विद्यार्थी एवं अभिभावक का स्थायी मोबाइल नं</li>
      </ol>
    </div>
  </div>
</main>

<Footer />
