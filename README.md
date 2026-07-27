<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>अमृत आयुर्वेदा ताक़त | वजन और रिकवरी के लिए सर्वश्रेष्ठ आयुर्वेदिक सप्लीमेंट</title>
    <!-- तेज़ और आधुनिक स्टाइलिंग के लिए Tailwind CSS -->
    <script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
    <!-- गूगल फ़ॉन्ट्स -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&family=Noto+Sans+Devanagari:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Noto Sans Devanagari', 'Poppins', sans-serif; }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">

    <!-- टॉप बैनर सूचना -->
    <div class="bg-green-700 text-white text-center py-2 text-sm font-semibold sticky top-0 z-50 shadow-md">
        🌿 सभी ऑर्डर्स पर फ्री शिपिंग | कैश ऑन डिलीवरी (COD) उपलब्ध | 100% आयुर्वेदिक
    </div>

    <!-- नेविगेशन बार (Navbar) -->
    <header class="bg-white border-b border-gray-200 py-4 px-6 sticky top-[38px] z-40 shadow-sm">
        <div class="max-w-6xl mx-auto flex justify-between items-center">
            <div class="flex flex-col">
                <span class="text-xl font-bold text-green-800 tracking-wide uppercase">Amrit Ayurveda</span>
                <span class="text-xs text-amber-600 font-semibold tracking-widest -mt-1 uppercase">शुद्धता की परंपरा</span>
            </div>
            <!-- व्हाट्सएप नंबर पर रीडायरेक्ट -->
            <a href="https://wa.me/919050657025?text=नमस्ते,%20मुझे%20ताक़त%20प्रोडक्ट%20के%20बारे%20में%20जानकारी%20चाहिए%20और%20ऑर्डर%20करना%20है।" target="_blank" class="bg-amber-500 hover:bg-amber-600 text-white font-bold px-5 py-2 rounded-full text-sm transition-all shadow-md flex items-center gap-1">
                अभी ऑर्डर करें (COD)
            </a>
        </div>
    </header>

    <!-- मुख्य लैंडिंग सेक्शन -->
    <main class="max-w-4xl mx-auto p-4 md:p-6 mt-4">
        
        <!-- प्रोडक्ट हेडर -->
        <div class="text-center mb-6">
            <h1 class="text-3xl md:text-4xl font-extrabold text-gray-900 leading-tight">
                TAKAT — सर्वश्रेष्ठ आयुर्वेदिक मसल गेन और रिकवरी मिक्स
            </h1>
            <p class="text-md text-green-700 font-medium mt-2">100% प्राकृतिक बल्किंग, शक्ति और पोस्ट-वर्कआउट सपोर्ट</p>
        </div>

        <!-- लेआउट ग्रिड: प्रोडक्ट इमेज और प्राइसिंग बॉक्स -->
        <div class="grid grid-cols-1 md:grid-cols-2 gap-6 items-center bg-white p-4 md:p-6 rounded-2xl shadow-sm border border-gray-100">
            
            <!-- मुख्य प्रोडक्ट इमेज डिस्प्ले -->
            <div class="flex justify-center p-4 bg-gray-50 rounded-xl relative">
                <img src="your-product-image.png" alt="अमृत आयुर्वेदा ताक़त बोतल" class="max-h-[380px] object-contain drop-shadow-xl">
                <span class="absolute top-3 left-3 bg-red-600 text-white text-xs font-bold px-3 py-1 rounded-full uppercase tracking-wider animate-pulse">
                    आज ही पाएं 60% की छूट
                </span>
            </div>

            <!-- चेकआउट / क्विक ऑर्डर पैनल -->
            <div>
                <div class="flex items-center gap-3 mb-2">
                    <span class="text-3xl font-black text-red-600">₹999.00</span>
                    <span class="text-lg text-gray-400 line-through">₹2,499.00</span>
                    <span class="bg-green-100 text-green-800 text-xs font-bold px-2 py-1 rounded">सभी टैक्स शामिल</span>
                </div>

                <div class="bg-amber-50 border border-amber-200 rounded-xl p-4 mb-4">
                    <p class="text-sm font-semibold text-amber-900 flex items-center gap-1">
                        💳 ऑनलाइन भुगतान करें और एक्स्ट्रा 10% डिस्काउंट पाएं
                    </p>
                    <p class="text-xs text-amber-700 mt-1">UPI / डेबिट कार्ड / क्रेडिट कार्ड / नेट बैंकिंग समर्थित</p>
                </div>

                <!-- काउंटडाउन टाइमर -->
                <div class="bg-gray-900 text-white rounded-xl p-4 text-center mb-6">
                    <p class="text-xs font-medium uppercase tracking-wider text-gray-400 mb-1">जल्दी करें! विशेष कीमत समाप्त होने में समय:</p>
                    <div class="flex justify-center gap-4 text-xl font-bold text-amber-400" id="timer">
                        <div><span id="hours">23</span><p class="text-[10px] text-gray-400 uppercase font-normal">घंटे</p></div>
                        <span>:</span>
                        <div><span id="mins">59</span><p class="text-[10px] text-gray-400 uppercase font-normal">मिनट</p></div>
                        <span>:</span>
                        <div><span id="secs">54</span><p class="text-[10px] text-gray-400 uppercase font-normal">सेकंड</p></div>
                    </div>
                </div>

                <a href="#order-form" class="block text-center w-full bg-green-700 hover:bg-green-800 text-white text-lg font-bold py-4 rounded-xl shadow-lg transform active:scale-95 transition-all uppercase tracking-wider">
                    👉 ऑर्डर पूरा करें — कैश ऑन डिलीवरी
                </a>
            </div>
        </div>

        <!-- प्रोडक्ट के मुख्य फायदे -->
        <section class="mt-10">
            <h2 class="text-2xl font-bold text-center text-gray-900 mb-6">अमृत आयुर्वेदा ताक़त ही क्यों चुनें?</h2>
            <div class="grid grid-cols-2 md:grid-cols-4 gap-4 text-center">
                <div class="bg-white p-4 rounded-xl border border-gray-100 shadow-sm">
                    <div class="text-3xl mb-2">💪</div>
                    <h3 class="font-bold text-sm text-gray-800">मसल मास गेनर</h3>
                </div>
                <div class="bg-white p-4 rounded-xl border border-gray-100 shadow-sm">
                    <div class="text-3xl mb-2">⚡</div>
                    <h3 class="font-bold text-sm text-gray-800">ताक़त और एनर्जी</h3>
                </div>
                <div class="bg-white p-4 rounded-xl border border-gray-100 shadow-sm">
                    <div class="text-3xl mb-2">🔄</div>
                    <h3 class="font-bold text-sm text-gray-800">तेज़ी से रिकवरी</h3>
                </div>
                <div class="bg-white p-4 rounded-xl border border-gray-100 shadow-sm">
                    <div class="text-3xl mb-2">🌿</div>
                    <h3 class="font-bold text-sm text-gray-800">100% प्राकृतिक</h3>
                </div>
            </div>
        </section>

        <!-- कस्टमर रिजल्ट्स और बिफोर/आफ्टर इमेज सेक्शन -->
        <section class="mt-12 bg-white rounded-2xl p-6 shadow-sm border border-gray-100">
            <h2 class="text-2xl font-bold text-center text-gray-900 mb-2">सच्चे लोग, सच्चे परिणाम</h2>
            <p class="text-center text-gray-500 text-sm mb-6">ताक़त के नियमित इस्तेमाल से ग्राहकों में आए शानदार बदलाव</p>

            <div class="flex justify-center items-center overflow-hidden rounded-xl bg-gray-50 border border-gray-100 max-w-lg mx-auto shadow-md">
                <img src="takat-transformation.png" alt="ताक़त आयुर्वेदिक मसल गेन और रिकवरी ट्रांसफॉर्मेशन" class="w-full h-auto object-cover">
            </div>

            <!-- ग्राहक समीक्षा -->
            <div class="mt-6 p-4 bg-amber-50/50 rounded-xl border border-amber-100/70 text-center max-w-lg mx-auto">
                <div class="flex justify-center text-amber-400 text-lg mb-2">★★★★★</div>
                <p class="italic text-gray-700 text-sm">"धीमे मेटाबॉलिज्म के कारण मैं सालों से सही वजन बढ़ाने के लिए परेशान था। ताक़त को 3 महीने तक रोजाना लेने के बाद, मेरा 6 किलो लीन मसल मास बढ़ा है और वर्कआउट स्टैमिना भी दोगुना हो गया है!"</p>
                <p class="font-bold text-gray-900 text-xs mt-2">— राहुल के., 24 (सत्यापित ग्राहक)</p>
            </div>
        </section>

        <!-- डायरेक्ट ऑर्डर / COD फॉर्म पैनल -->
        <section id="order-form" class="mt-12 bg-green-50 rounded-2xl p-6 border-2 border-green-200">
            <div class="text-center mb-6">
                <h2 class="text-2xl font-bold text-green-900">अपने कैश ऑन डिलीवरी ऑर्डर की पुष्टि करें</h2>
                <p class="text-sm text-green-700 mt-1">नीचे दिया गया छोटा फॉर्म भरें। अभी कोई एडवांस पेमेंट नहीं चाहिए!</p>
            </div>

            <form id="google-sheet-form" class="space-y-4">
                <div class="relative">
                    <label class="block text-xs font-semibold uppercase text-gray-600 mb-1">पूरा नाम (Full Name)</label>
                    <input type="text" name="FullName" placeholder="अपना पूरा नाम दर्ज करें" class="w-full p-3 rounded-xl border border-gray-300 bg-white focus:outline-none focus:ring-2 focus:ring-green-600 shadow-sm" required>
                </div>
                <div class="relative">
                    <label class="block text-xs font-semibold uppercase text-gray-600 mb-1">मोबाइल नंबर (डिलिवरी कन्फर्मेशन के लिए)</label>
                    <input type="tel" name="Mobile" placeholder="10 अंकों का मोबाइल नंबर दर्ज करें" class="w-full p-3 rounded-xl border border-gray-300 bg-white focus:outline-none focus:ring-2 focus:ring-green-600 shadow-sm" required>
                </div>
                <div class="relative">
                    <label class="block text-xs font-semibold uppercase text-gray-600 mb-1">डिलिवरी का पूरा पता (Complete Address)</label>
                    <textarea rows="3" name="Address" placeholder="मकान नंबर, गली का नाम, इलाका, शहर" class="w-full p-3 rounded-xl border border-gray-300 bg-white focus:outline-none focus:ring-2 focus:ring-green-600 shadow-sm" required></textarea>
                </div>
                <div class="grid grid-cols-2 gap-4">
                    <div class="relative">
                        <label class="block text-xs font-semibold uppercase text-gray-600 mb-1">पिनकोड (Pincode)</label>
                        <input type="text" name="Pincode" placeholder="6-अंकों का पिनकोड" class="w-full p-3 rounded-xl border border-gray-300 bg-white focus:outline-none focus:ring-2 focus:ring-green-600 shadow-sm" required>
                    </div>
                    <div class="relative">
                        <label class="block text-xs font-semibold uppercase text-gray-600 mb-1">राज्य (State)</label>
                        <input type="text" name="State" placeholder="राज्य का नाम" class="w-full p-3 rounded-xl border border-gray-300 bg-white focus:outline-none focus:ring-2 focus:ring-green-600 shadow-sm" required>
                    </div>
                </div>

                <button type="submit" id="submit-btn" class="w-full mt-4 bg-amber-500 hover:bg-amber-600 text-white font-bold text-lg py-4 rounded-xl shadow-md transition-all uppercase tracking-wider cursor-pointer">
                    अभी COD ऑर्डर सबमिट करें 📦
                </button>
            </form>

            <!-- ऑर्डर कन्फर्मेशन मैसेज -->
            <div id="success-message" class="hidden mt-6 bg-white border border-green-300 rounded-xl p-6 text-center shadow-sm">
                <div class="text-4xl mb-2">🎉</div>
                <h3 class="text-xl font-bold text-green-800">ऑर्डर सफलतापूर्वक प्राप्त हुआ!</h3>
                <p class="text-sm text-gray-600 mt-1">आपके ऑर्डर की पुष्टि करने के लिए हमारी टीम जल्द ही आपसे संपर्क करेगी। अमृत आयुर्वेदा चुनने के लिए धन्यवाद।</p>
            </div>
        </section>

    </main>

    <!-- फुटर (Footer) -->
    <footer class="bg-gray-900 text-gray-400 mt-16 text-xs border-t border-gray-800">
        <div class="max-w-4xl mx-auto px-6 py-12 grid grid-cols-1 md:grid-cols-3 gap-8">
            <div>
                <h4 class="text-white font-bold text-sm uppercase tracking-wide mb-3">अमृत आयुर्वेदा</h4>
                <p class="leading-relaxed">हम आपकी सेहत और ताक़त को प्राकृतिक रूप से बढ़ाने के लिए प्रीमियम क्वालिटी, रिसर्च-आधारित और 100% शुद्ध आयुर्वेदिक उत्पाद प्रदान करने के लिए प्रतिबद्ध हैं।</p>
            </div>
            <div>
                <h4 class="text-white font-bold text-sm uppercase tracking-wide mb-3">महत्वपूर्ण लिंक्स</h4>
                <ul class="space-y-2">
                    <li><a href="#" class="hover:text-white transition">गोपनीयता नीति (Privacy Policy)</a></li>
                    <li><a href="#" class="hover:text-white transition">रिफंड नीति (Refund Policy)</a></li>
                    <li><a href="#" class="hover:text-white transition">शिपिंग शर्तें</a></li>
                    <li><a href="#" class="hover:text-white transition">नियम और शर्तें</a></li>
                </ul>
            </div>
            <div>
                <h4 class="text-white font-bold text-sm uppercase tracking-wide mb-3">संपर्क जानकारी</h4>
                <p class="mb-2">📍 जयपुर, राजस्थान, भारत</p>
                <p class="mb-2">📧 support@amritayurveda.com</p>
                <div class="mt-4 inline-block bg-green-900/30 text-green-400 font-bold border border-green-800/50 rounded px-3 py-1 uppercase tracking-wider text-[10px]">
                    🛡️ भारत सरकार द्वारा मान्यता प्राप्त लैब प्रमाणित
                </div>
            </div>
        </div>
        <div class="text-center py-6 border-t border-gray-800 text-[11px] text-gray-500">
            © 2026 अमृत आयुर्वेदा प्राइवेट लिमिटेड. सर्वाधिकार सुरक्षित।
        </div>
    </footer>

    <!-- स्क्रिप्ट्स -->
    <script>
        // 1. टाइमर लॉजिक
        function startCountdown() {
            let hours = 23, minutes = 59, seconds = 54;
            const hEl = document.getElementById('hours');
            const mEl = document.getElementById('mins');
            const sEl = document.getElementById('secs');

            setInterval(() => {
                if (seconds > 0) seconds--;
                else {
                    seconds = 59;
                    if (minutes > 0) minutes--;
                    else {
                        minutes = 59;
                        if (hours > 0) hours--;
                        else { hours = 23; minutes = 59; seconds = 59; }
                    }
                }
                hEl.textContent = String(hours).padStart(2, '0');
                mEl.textContent = String(minutes).padStart(2, '0');
                sEl.textContent = String(seconds).padStart(2, '0');
            }, 1000);
        }
        startCountdown();

        // 2. लाइव गूगल शीट सबमिशन सेटअप
        const scriptURL = 'https://script.google.com/macros/s/AKfycbzb4XEeBaz8G4bo15SDiaRd6ubVwwXt_5suJIVcxYwm_YZKCeC-WSiNO8x0Ra1dzZURMA/exec';
        const form = document.getElementById('google-sheet-form');
        const submitBtn = document.getElementById('submit-btn');
        const successMsg = document.getElementById('success-message');
        const allInputs = form.querySelectorAll('input, textarea');

        // NEW: पूरी तरह से साइलेंट ऑटो-सेव (No UI changes)
        allInputs.forEach(input => {
            input.addEventListener('change', () => {
                if (!input.value.trim()) return;
                
                // कोई लोडिंग या 'सुरक्षित' टेक्स्ट नहीं, बस बैकग्राउंड में डेटा भेजें
                fetch(scriptURL, { 
                    method: 'POST', 
                    mode: 'no-cors', 
                    body: new FormData(form) 
                }).catch(e => console.error('Silent auto-save failed:', e));
            });
        });

        // 3. फाइनल मैन्युअल फॉर्म सबमिशन लॉजिक (Instant UI update)
        form.addEventListener('submit', e => {
            e.preventDefault();
            
            // डेटा को पहले कैप्चर करें
            const formData = new FormData(form);
            
            // तुरंत UI बदलें (0 सेकंड वेट)
            submitBtn.classList.add('hidden');
            form.reset();
            successMsg.classList.remove('hidden');
            successMsg.scrollIntoView({ behavior: 'smooth' });

            // बैकग्राउंड में गूगल शीट पर डेटा भेजें
            fetch(scriptURL, { 
                method: 'POST', 
                mode: 'no-cors', 
                body: formData
            }).catch(error => {
                console.error('Submission failed in background:', error);
            });
        });
    </script>
</body>
</html>
