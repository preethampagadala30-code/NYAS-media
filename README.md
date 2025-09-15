<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Digital Marketing Agency</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Font (Inter is professional and clean) -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <!-- Phosphor Icons for a clean, modern look -->
    <script src="https://unpkg.com/@phosphor-icons/web@2.1.1/dist/phosphor.js"></script>
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
        .text-gradient {
            background-clip: text;
            -webkit-background-clip: text;
            color: transparent;
            background-image: linear-gradient(to right, var(--tw-gradient-stops));
        }
        .animated-text {
            background: linear-gradient(135deg, #1e293b, #4b5563, #a5f3fc, #4f46e5, #1e293b);
            background-size: 400% 400%;
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            animation: background-slide 15s ease infinite;
        }

        @keyframes background-slide {
            0% {
                background-position: 0% 50%;
            }
            50% {
                background-position: 100% 50%;
            }
            100% {
                background-position: 0% 50%;
            }
        }
    </style>
</head>
<body class="bg-slate-900 text-slate-200">

    <!-- Navigation Bar - All Destinations Available at the Top -->
    <header class="bg-slate-800 shadow-xl rounded-b-3xl mx-2 md:mx-4 lg:mx-8 mt-2 sticky top-0 z-50">
        <nav class="container mx-auto px-6 py-4 flex items-center justify-between">
            
            <!-- Logo -->
            <a href="#hero">
                <img src="https://i.postimg.cc/cL68b0hr/nyasmedia.jpg" alt="NYAS MEDIA Agency Logo" class="w-32 h-auto">
            </a>
            
            <!-- Desktop Menu -->
            <div class="hidden md:flex space-x-8 items-center">
                <a href="#hero" class="text-white hover:text-cyan-400 transition-colors duration-300">Home</a>
                <a href="#about" class="text-white hover:text-cyan-400 transition-colors duration-300">About Me</a>
                <a href="#services" class="text-white hover:text-cyan-400 transition-colors duration-300">Services</a>
                <a href="#support" class="text-white hover:text-cyan-400 transition-colors duration-300">Support</a>
                <a href="#contact" class="bg-cyan-500 text-slate-900 font-semibold px-6 py-2 rounded-full hover:bg-cyan-400 transition-colors duration-300 transform hover:scale-105">Contact</a>
            </div>

            <!-- Mobile Menu Button -->
            <div class="md:hidden">
                <button id="mobile-menu-button" class="text-slate-400 hover:text-cyan-400 focus:outline-none">
                    <i class="ph ph-list text-3xl"></i>
                </button>
            </div>
        </nav>

        <!-- Mobile Menu -->
        <div id="mobile-menu" class="hidden md:hidden bg-slate-800">
            <a href="#hero" class="block py-3 px-6 text-white hover:bg-slate-700">Home</a>
            <a href="#services" class="block py-3 px-6 text-white hover:bg-slate-700">Services</a>
            <a href="#about" class="block py-3 px-6 text-white hover:bg-slate-700">About Me</a>
            <a href="#support" class="block py-3 px-6 text-white hover:bg-slate-700">Support</a>
            <a href="#contact" class="block py-3 px-6 text-white hover:bg-slate-700">Contact</a>
        </div>
    </header>

    <main class="container mx-auto px-4 lg:px-8 py-12">

        <!-- Hero Section -->
        <section id="hero" class="bg-slate-800 rounded-3xl p-8 md:p-16 shadow-xl mb-12 relative overflow-hidden text-center">
            <!-- To change the main title text, edit the content below. -->
            <h1 class="animated-text text-6xl md:text-8xl lg:text-[10rem] font-black tracking-widest leading-none select-none mb-4">NYAS MEDIA</h1>
            <!-- To change the tagline, edit the content below. -->
            <p class="text-lg md:text-xl text-slate-400 mb-8 max-w-lg mx-auto">
                Ignite, grow, and succeed with strategic digital marketing.
            </p>
            <a href="#services" class="bg-cyan-500 text-slate-900 font-semibold py-4 px-10 rounded-full hover:bg-cyan-400 transition-colors duration-300 transform hover:scale-105 inline-block shadow-lg">
                View Our Services
            </a>
        </section>

        <!-- About Me Section -->
        <section id="about" class="bg-slate-800 rounded-3xl p-8 md:p-16 shadow-xl mb-12">
            <!-- To change the section title, edit the content below. -->
            <h2 class="text-3xl md:text-5xl font-bold text-center mb-2 text-cyan-400">About the Founder</h2>
            <!-- To change your name, edit the content below. -->
            <h3 class="text-xl md:text-2xl font-semibold text-center mb-6 text-slate-300">PREETHAMPAGADALA</h3>
            <div class="grid md:grid-cols-2 gap-12 items-center">
                <div class="flex justify-center">
                    <!-- To change your profile photo, replace the "src" URL below with the URL of your new photo. -->
                    <!-- The current image is a placeholder. -->
                    <img src="https://i.postimg.cc/x1jYn3FZ/nsyimage.jpg" alt="My Image" class="rounded-3xl shadow-2xl">
                </div>
                <div>
                    <!-- To change the descriptive text, edit the content below. -->
                    <p class="text-lg text-slate-400 leading-relaxed mb-6">
                        As a passionate digital strategist, my mission is to help businesses of all sizes find their voice and reach their audience. I believe in transparency, creativity, and delivering data-driven results that make a real impact.
                    </p>
                    <ul class="space-y-4 text-slate-300">
                        <li class="flex items-center space-x-3">
                            <i class="ph ph-check-circle text-2xl text-cyan-400"></i>
                            <!-- To change this bullet point, edit the content below. -->
                            <span>Dedicated to your business growth and success.</span>
                        </li>
                        <li class="flex items-center space-x-3">
                            <i class="ph ph-check-circle text-2xl text-cyan-400"></i>
                            <!-- To change this bullet point, edit the content below. -->
                            <span>Tailored strategies for every client and every goal.</span>
                        </li>
                        <li class="flex items-center space-x-3">
                            <i class="ph ph-check-circle text-2xl text-cyan-400"></i>
                            <!-- To change this bullet point, edit the content below. -->
                            <span>Continuous learning to stay ahead of market trends.</span>
                        </li>
                    </ul>
                </div>
            </div>
        </section>

        <!-- Services Section -->
        <section id="services" class="bg-slate-800 rounded-3xl p-8 md:p-16 shadow-xl mb-12">
            <!-- To change the section title, edit the content below. -->
            <h2 class="text-3xl md:text-5xl font-bold text-center mb-6 text-cyan-400">Our Services</h2>
            <!-- To change the section description, edit the content below. -->
            <p class="text-lg text-slate-400 text-center mb-12 max-w-3xl mx-auto">We offer a full suite of digital marketing services to build your brand and engage your audience.</p>
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- To edit the services, change the title and description within each of these divs. -->
                <div class="bg-slate-900 rounded-2xl p-8 text-center shadow-lg transform transition-transform duration-300 hover:scale-105 hover:bg-slate-700">
                    <div class="text-cyan-500 text-5xl mb-4"><i class="ph ph-magnifying-glass"></i></div>
                    <h3 class="text-2xl font-semibold mb-2 text-slate-50">Search Engine Optimization (SEO)</h3>
                    <p class="text-slate-400">Improve your website's ranking and visibility on search engines to attract organic traffic.</p>
                </div>
                <!-- Service Card: Social Media Marketing -->
                <div class="bg-slate-900 rounded-2xl p-8 text-center shadow-lg transform transition-transform duration-300 hover:scale-105 hover:bg-slate-700">
                    <div class="text-cyan-500 text-5xl mb-4"><i class="ph ph-share-network"></i></div>
                    <h3 class="text-2xl font-semibold mb-2 text-slate-50">Social Media Marketing</h3>
                    <p class="text-slate-400">Build brand loyalty, drive engagement, and generate leads on platforms like Instagram and Facebook.</p>
                </div>
                <!-- Service Card: Content Marketing -->
                <div class="bg-slate-900 rounded-2xl p-8 text-center shadow-lg transform transition-transform duration-300 hover:scale-105 hover:bg-slate-700">
                    <div class="text-cyan-500 text-5xl mb-4"><i class="ph ph-note-pencil"></i></div>
                    <h3 class="text-2xl font-semibold mb-2 text-slate-50">Content Marketing</h3>
                    <p class="text-slate-400">Create valuable and relevant content to attract and retain a clearly defined audience.</p>
                </div>
                <!-- Service Card: Paid Advertising -->
                <div class="bg-slate-900 rounded-2xl p-8 text-center shadow-lg transform transition-transform duration-300 hover:scale-105 hover:bg-slate-700">
                    <div class="text-cyan-500 text-5xl mb-4"><i class="ph ph-megaphone"></i></div>
                    <h3 class="text-2xl font-semibold mb-2 text-slate-50">Paid Advertising (PPC)</h3>
                    <p class="text-slate-400">Run targeted ad campaigns on Google, social media, and other channels to generate immediate results.</p>
                </div>
                <!-- Service Card: Email Marketing -->
                <div class="bg-slate-900 rounded-2xl p-8 text-center shadow-lg transform transition-transform duration-300 hover:scale-105 hover:bg-slate-700">
                    <div class="text-cyan-500 text-5xl mb-4"><i class="ph ph-envelope"></i></div>
                    <h3 class="text-2xl font-semibold mb-2 text-slate-50">Email Marketing</h3>
                    <p class="text-slate-400">Nurture leads and build lasting customer relationships with automated and personalized email campaigns.</p>
                </div>
                <!-- Service Card: Website Design -->
                <div class="bg-slate-900 rounded-2xl p-8 text-center shadow-lg transform transition-transform duration-300 hover:scale-105 hover:bg-slate-700">
                    <div class="text-cyan-500 text-5xl mb-4"><i class="ph ph-laptop"></i></div>
                    <h3 class="text-2xl font-semibold mb-2 text-slate-50">Website Design & Development</h3>
                    <p class="text-slate-400">Create a fast, responsive, and visually stunning website that converts visitors into customers.</p>
                </div>
            </div>
        </section>
        
        <!-- Gemini API-powered features -->
        <section id="gemini-tools" class="bg-slate-800 rounded-3xl p-8 md:p-16 shadow-xl mb-12">
            <h2 class="text-3xl md:text-5xl font-bold text-center mb-6 text-cyan-400">Our Digital Tools</h2>
            <p class="text-lg text-slate-400 text-center mb-12 max-w-3xl mx-auto">
                Try out our powerful AI-driven tools to get a taste of what we can do for your business.
            </p>

            <div class="flex flex-col lg:flex-row gap-8">
                <!-- Ad Copy Generator -->
                <div class="flex-1 bg-slate-900 rounded-3xl p-8 shadow-lg">
                    <h3 class="text-2xl font-semibold text-center mb-4 text-slate-50">✨ Ad Copy Generator</h3>
                    <p class="text-slate-400 mb-6 text-center">Enter a brief product description and let our AI generate compelling ad copy for you!</p>
                    <div class="space-y-4">
                        <textarea id="ad-copy-input" class="w-full h-32 p-4 bg-slate-700 text-slate-200 rounded-lg placeholder-slate-400 focus:outline-none focus:ring-2 focus:ring-cyan-500" placeholder="e.g., A new line of eco-friendly sneakers made from recycled plastic."></textarea>
                        <button id="generate-ad-copy-btn" class="w-full bg-cyan-500 text-slate-900 font-semibold py-3 rounded-full hover:bg-cyan-400 transition-colors duration-300 transform hover:scale-105">
                            Generate Ad Copy
                        </button>
                    </div>
                    <div id="ad-copy-output" class="mt-6 p-4 bg-slate-700 rounded-lg hidden">
                        <h4 class="font-bold text-slate-300 mb-2">Generated Ad Copy:</h4>
                        <div id="ad-copy-result" class="text-slate-200 whitespace-pre-line"></div>
                    </div>
                </div>

                <!-- Keyword Suggestion Tool -->
                <div class="flex-1 bg-slate-900 rounded-3xl p-8 shadow-lg">
                    <h3 class="text-2xl font-semibold text-center mb-4 text-slate-50">✨ Keyword Suggestion Tool</h3>
                    <p class="text-slate-400 mb-6 text-center">Enter a topic and get a list of high-impact SEO keywords to target.</p>
                    <div class="space-y-4">
                        <input type="text" id="keyword-input" class="w-full p-4 bg-slate-700 text-slate-200 rounded-lg placeholder-slate-400 focus:outline-none focus:ring-2 focus:ring-cyan-500" placeholder="e.g., sustainable fashion">
                        <button id="generate-keywords-btn" class="w-full bg-cyan-500 text-slate-900 font-semibold py-3 rounded-full hover:bg-cyan-400 transition-colors duration-300 transform hover:scale-105">
                            Suggest Keywords
                        </button>
                    </div>
                    <div id="keyword-output" class="mt-6 p-4 bg-slate-700 rounded-lg hidden">
                        <h4 class="font-bold text-slate-300 mb-2">Suggested Keywords:</h4>
                        <ul id="keyword-result" class="text-slate-200 list-disc list-inside"></ul>
                    </div>
                </div>
            </div>
        </section>
        
        <!-- Support/FAQ Section -->
        <section id="support" class="bg-slate-800 rounded-3xl p-8 md:p-16 shadow-xl mb-12">
            <h2 class="text-3xl md:text-5xl font-bold text-center mb-6 text-cyan-400">Support & FAQ</h2>
            <p class="text-lg text-slate-400 text-center mb-12 max-w-3xl mx-auto">Find answers to the most common questions about our services and process.</p>
            <div class="max-w-4xl mx-auto space-y-6">
                <!-- To edit the FAQs, change the content within each of these divs. -->
                <div class="bg-slate-900 rounded-2xl p-6 shadow-lg">
                    <h3 class="text-xl font-semibold mb-2 text-slate-50">How long does a typical project take?</h3>
                    <p class="text-slate-300">Project timelines vary depending on the scope and complexity. We'll provide a detailed timeline after our initial consultation and proposal.</p>
                </div>
                <!-- FAQ 2 -->
                <div class="bg-slate-900 rounded-2xl p-6 shadow-lg">
                    <h3 class="text-xl font-semibold mb-2 text-slate-50">What is your pricing model?</h3>
                    <p class="text-slate-300">We offer customized pricing based on your specific needs and goals. We can discuss this in our initial consultation.</p>
                </div>
                <!-- FAQ 3 -->
                <div class="bg-slate-900 rounded-2xl p-6 shadow-lg">
                    <h3 class="text-xl font-semibold mb-2 text-slate-50">Can you help with my existing website?</h3>
                    <p class="text-slate-300">Yes, we specialize in revamping and optimizing existing websites to improve performance, design, and user experience.</p>
                </div>
            </div>
        </section>

        <!-- New Contact Section -->
        <section id="contact" class="bg-slate-800 rounded-3xl p-8 md:p-16 shadow-xl">
            <h2 class="text-3xl md:text-5xl font-bold text-center mb-6 text-cyan-400">Reach Out Directly</h2>
            <p class="text-lg text-slate-400 text-center mb-12 max-w-3xl mx-auto">Feel free to contact me directly for a free consultation. I'm here to help you get started.</p>
            <div class="max-w-xl mx-auto text-center space-y-6">
                 <!-- The WhatsApp link now includes the full message you requested. -->
                 <a href="https://wa.me/9573229677?text=Hi%20preetham,%20I%60m%20interested%20in%20your%20services!" class="block bg-slate-900 rounded-xl p-6 hover:bg-slate-700 transition-colors duration-300 shadow-lg" target="_blank">
                    <div class="flex items-center justify-center space-x-4">
                        <!-- A WhatsApp logo is already included here using Phosphor Icons. -->
                        <i class="ph ph-whatsapp-logo text-3xl text-green-400"></i>
                        <!-- To change the WhatsApp number text, edit the "span" content below. -->
                        <span class="text-lg text-slate-300">Message on WhatsApp</span>
                    </div>
                </a>
                <!-- To change the email link, edit the "href" and "span" content below. -->
                <a href="mailto:preethampagadala30@gmail.com" class="block bg-slate-900 rounded-xl p-6 hover:bg-slate-700 transition-colors duration-300 shadow-lg">
                    <div class="flex items-center justify-center space-x-4">
                        <i class="ph ph-envelope-simple text-3xl text-cyan-400"></i>
                        <span class="text-lg text-slate-300">preethampagadala30@gmail.com</span>
                    </div>
                </a>
                <p class="text-sm text-slate-500 mt-4">Just click on the links above to get in touch!</p>
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer class="bg-slate-800 text-slate-400 text-center py-8 mt-12 rounded-t-3xl mx-2 md:mx-4 lg:mx-8">
        <div class="container mx-auto px-6">
            <p>&copy; 2025 NYAS DIGITAL MARKETING AGENCY. All rights reserved.</p>
            <div class="flex justify-center mt-4 space-x-6 text-xl">
                <a href="#" class="hover:text-cyan-400 transition-colors duration-300"><i class="ph ph-twitter-logo"></i></a>
                <a href="#" class="hover:text-cyan-400 transition-colors duration-300"><i class="ph ph-linkedin-logo"></i></a>
                <a href="#" class="hover:text-cyan-400 transition-colors duration-300"><i class="ph ph-github-logo"></i></a>
            </div>
        </div>
    </footer>

    <!-- JavaScript for Mobile Menu Toggle and Gemini API calls -->
    <script>
        // API Key is required for the Gemini API call.
        const apiKey = "AIzaSyD8zjn5zr9xiyX99RpktXUlQwaYF2yx1v4";
        const API_URL = `https://generativelanguage.googleapis.com/v1beta/models/gemini-2.5-flash-preview-05-20:generateContent?key=${apiKey}`;

        // Utility function for exponential backoff
        async function fetchWithExponentialBackoff(url, options, retries = 5, delay = 1000) {
            for (let i = 0; i < retries; i++) {
                try {
                    const response = await fetch(url, options);
                    if (response.status === 429 && i < retries - 1) {
                        console.warn(`Rate limit hit. Retrying in ${delay}ms...`);
                        await new Promise(resolve => setTimeout(resolve, delay));
                        delay *= 2;
                        continue;
                    }
                    return response;
                } catch (error) {
                    if (i < retries - 1) {
                        console.error(`Fetch failed. Retrying in ${delay}ms...`, error);
                        await new Promise(resolve => setTimeout(resolve, delay));
                        delay *= 2;
                        continue;
                    }
                    throw error;
                }
            }
            throw new Error('Failed to fetch after multiple retries.');
        }

        // --- Ad Copy Generator Logic ---
        const adCopyInput = document.getElementById('ad-copy-input');
        const generateAdCopyBtn = document.getElementById('generate-ad-copy-btn');
        const adCopyOutput = document.getElementById('ad-copy-output');
        const adCopyResult = document.getElementById('ad-copy-result');

        generateAdCopyBtn.addEventListener('click', async () => {
            const productDescription = adCopyInput.value.trim();
            if (!productDescription) {
                adCopyResult.textContent = 'Please enter a product description.';
                adCopyOutput.classList.remove('hidden');
                return;
            }

            // Show loading state
            adCopyOutput.classList.remove('hidden');
            adCopyResult.textContent = 'Generating ad copy...';
            generateAdCopyBtn.disabled = true;

            const systemPrompt = "You are a world-class digital marketer. Your task is to write three short, compelling, and creative ad copy variations for a given product or service description. The ad copy should be concise, attention-grabbing, and suitable for social media platforms. Do not include titles or headings, just the ad copy variations. Use emojis and a friendly tone. Use Google Search to gather up-to-date information and market trends related to the user's query.";
            const userQuery = `Generate ad copy for this: "${productDescription}"`;

            const payload = {
                contents: [{ parts: [{ text: userQuery }] }],
                tools: [{ "google_search": {} }],
                systemInstruction: {
                    parts: [{ text: systemPrompt }]
                }
            };

            try {
                const response = await fetchWithExponentialBackoff(API_URL, {
                    method: 'POST',
                    headers: { 'Content-Type': 'application/json' },
                    body: JSON.stringify(payload)
                });
                const result = await response.json();
                const text = result?.candidates?.[0]?.content?.parts?.[0]?.text || 'No ad copy could be generated.';
                adCopyResult.textContent = text;
            } catch (error) {
                adCopyResult.textContent = 'Failed to generate ad copy. Please try again later.';
                console.error('API call failed:', error);
            } finally {
                generateAdCopyBtn.disabled = false;
            }
        });


        // --- Keyword Suggestion Logic ---
        const keywordInput = document.getElementById('keyword-input');
        const generateKeywordsBtn = document.getElementById('generate-keywords-btn');
        const keywordOutput = document.getElementById('keyword-output');
        const keywordResult = document.getElementById('keyword-result');

        generateKeywordsBtn.addEventListener('click', async () => {
            const topic = keywordInput.value.trim();
            if (!topic) {
                keywordResult.innerHTML = '<li>Please enter a topic.</li>';
                keywordOutput.classList.remove('hidden');
                return;
            }

            // Show loading state
            keywordOutput.classList.remove('hidden');
            keywordResult.innerHTML = '<li>Suggesting keywords...</li>';
            generateKeywordsBtn.disabled = true;

            const systemPrompt = "You are a professional SEO analyst. Your task is to generate a list of 10 relevant and high-impact long-tail keywords for a given topic. The keywords should be presented as a simple, comma-separated list. Do not include any other text, explanations, or headings.";
            const userQuery = `Generate a list of keywords for this topic: "${topic}"`;

            const payload = {
                contents: [{ parts: [{ text: userQuery }] }],
                tools: [{ "google_search": {} }],
                systemInstruction: {
                    parts: [{ text: systemPrompt }]
                }
            };

            try {
                const response = await fetchWithExponentialBackoff(API_URL, {
                    method: 'POST',
                    headers: { 'Content-Type': 'application/json' },
                    body: JSON.stringify(payload)
                });
                const result = await response.json();
                const text = result?.candidates?.[0]?.content?.parts?.[0]?.text || '';
                
                if (text) {
                    const keywords = text.split(',').map(keyword => keyword.trim());
                    const listItems = keywords.map(keyword => `<li>${keyword}</li>`).join('');
                    keywordResult.innerHTML = listItems;
                } else {
                    keywordResult.innerHTML = '<li>No keywords could be generated.</li>';
                }
            } catch (error) {
                keywordResult.innerHTML = '<li>Failed to suggest keywords. Please try again later.</li>';
                console.error('API call failed:', error);
            } finally {
                generateKeywordsBtn.disabled = false;
            }
        });

        // Mobile menu toggle logic
        const mobileMenuButton = document.getElementById('mobile-menu-button');
        const mobileMenu = document.getElementById('mobile-menu');
       
        mobileMenuButton.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });
    </script>
</body>
</html>
