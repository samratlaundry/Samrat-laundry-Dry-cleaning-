# Samrat-laundry-Dry-cleaning-
Laundry service 

<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Samrat Laundry & Drycleaning Service | DLF Phase 3 Gurgaon</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        brand: {
                            50: '#f0f7ff',
                            100: '#e0effe',
                            200: '#bae0fd',
                            500: '#0284c7',
                            600: '#026aa7',
                            700: '#0369a1',
                            800: '#075985',
                            900: '#0c4a6e',
                        },
                        accent: {
                            500: '#10b981',
                            600: '#059669',
                            yellow: '#f59e0b'
                        }
                    },
                    fontFamily: {
                        sans: ['Plus Jakarta Sans', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    <style>
        body { font-family: 'Plus Jakarta Sans', sans-serif; }
        .glass-card {
            background: rgba(255, 255, 255, 0.85);
            backdrop-filter: blur(12px);
            border: 1px solid rgba(255, 255, 255, 0.6);
        }
        .glass-nav {
            background: rgba(255, 255, 255, 0.92);
            backdrop-filter: blur(10px);
        }
        .hero-gradient {
            background: linear-gradient(135deg, #0f172a 0%, #0369a1 50%, #0284c7 100%);
        }
        .badge-pulse {
            animation: pulse-ring 2s cubic-bezier(0.4, 0, 0.6, 1) infinite;
        }
        @keyframes pulse-ring {
            0%, 100% { opacity: 1; transform: scale(1); }
            50% { opacity: 0.85; transform: scale(1.03); }
        }
        /* Custom scrollbar */
        ::-webkit-scrollbar { width: 8px; }
        ::-webkit-scrollbar-track { background: #f1f5f9; }
        ::-webkit-scrollbar-thumb { background: #0284c7; border-radius: 4px; }
    </style>
</head>
<body class="bg-slate-50 text-slate-800 antialiased selection:bg-brand-500 selection:text-white">

    <!-- Floating WhatsApp CTA -->
    <a href="https://wa.me/918527901289?text=Hello%20Samrat%20Laundry,%20I%20would%20like%20to%20book%20a%20pickup!"
       target="_blank"
       rel="noopener"
       aria-label="Chat on WhatsApp"
       class="fixed bottom-6 right-6 z-50 bg-emerald-500 hover:bg-emerald-600 text-white p-4 rounded-full shadow-2xl transition-all duration-300 hover:scale-110 flex items-center gap-2 group cursor-pointer border-2 border-white">
        <i class="fa-brands fa-whatsapp text-3xl"></i>
        <span class="max-w-0 overflow-hidden whitespace-nowrap group-hover:max-w-xs transition-all duration-500 ease-in-out text-sm font-bold pl-0 group-hover:pl-1">Book Pickup Now</span>
    </a>

    <!-- Top Announcement Bar -->
    <div class="bg-gradient-to-r from-amber-500 via-orange-500 to-amber-600 text-white text-xs sm:text-sm py-2 px-4 text-center font-medium shadow-sm flex items-center justify-center gap-2 flex-wrap">
        <span class="bg-white/20 text-white px-2 py-0.5 rounded-full text-xs uppercase font-extrabold tracking-wider">Tuesday Special</span>
        <span>🎉 Get <strong>15% OFF</strong> on Laundry (Min. 8 Kg) Every Tuesday!</span>
        <span class="hidden md:inline">|</span>
        <span class="hidden md:inline"><i class="fa-solid fa-truck-fast mr-1"></i> FREE Pickup & Delivery in DLF Phase 3</span>
    </div>

    <!-- Navigation Bar -->
    <header class="sticky top-0 z-40 glass-nav border-b border-slate-200/80 transition-all duration-300" id="main-header">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-20">
                <!-- Brand Logo -->
                <a href="#home" class="flex items-center gap-3 group">
                    <div class="w-12 h-12 bg-gradient-to-br from-brand-600 to-brand-800 rounded-xl flex items-center justify-center text-white shadow-lg shadow-brand-500/30 group-hover:scale-105 transition-transform">
                        <i class="fa-solid fa-shirt text-xl"></i>
                    </div>
                    <div>
                        <span class="text-xl sm:text-2xl font-black tracking-tight text-slate-900 block leading-tight">SAMRAT</span>
                        <span class="text-[10px] sm:text-xs font-bold text-brand-600 uppercase tracking-widest block">Laundry & Dry Cleaning</span>
                    </div>
                </a>

                <!-- Desktop Nav Links -->
                <nav class="hidden lg:flex items-center gap-1 xl:gap-2 text-sm font-semibold text-slate-700">
                    <a href="#home" class="px-3 py-2 rounded-lg hover:text-brand-600 hover:bg-brand-50 transition-colors">Home</a>
                    <a href="#services" class="px-3 py-2 rounded-lg hover:text-brand-600 hover:bg-brand-50 transition-colors">Services</a>
                    <a href="#rates" class="px-3 py-2 rounded-lg hover:text-brand-600 hover:bg-brand-50 transition-colors">Dry Cleaning</a>
                    <a href="#pricing" class="px-3 py-2 rounded-lg hover:text-brand-600 hover:bg-brand-50 transition-colors">Pricing</a>
                    <a href="#calculator" class="px-3 py-2 rounded-lg hover:text-brand-600 hover:bg-brand-50 transition-colors text-brand-600">Calculator</a>
                    <a href="#how-it-works" class="px-3 py-2 rounded-lg hover:text-brand-600 hover:bg-brand-50 transition-colors">Process</a>
                    <a href="#why-us" class="px-3 py-2 rounded-lg hover:text-brand-600 hover:bg-brand-50 transition-colors">Why Us</a>
                    <a href="#reviews" class="px-3 py-2 rounded-lg hover:text-brand-600 hover:bg-brand-50 transition-colors">Reviews</a>
                    <a href="#contact" class="px-3 py-2 rounded-lg hover:text-brand-600 hover:bg-brand-50 transition-colors">Contact</a>
                </nav>

                <!-- Call/WhatsApp CTA Button -->
                <div class="hidden sm:flex items-center gap-3">
                    <a href="tel:8527901289" class="p-2.5 text-brand-700 bg-brand-50 hover:bg-brand-100 rounded-xl transition-colors font-bold text-sm flex items-center gap-2">
                        <i class="fa-solid fa-phone"></i>
                        <span class="hidden xl:inline">8527901289</span>
                    </a>
                    <a href="https://wa.me/918527901289?text=Hi%20Samrat%20Laundry,%20I%20want%20to%20book%20a%20pickup."
                       target="_blank"
                       class="bg-emerald-600 hover:bg-emerald-700 text-white font-bold px-4 py-2.5 rounded-xl shadow-md shadow-emerald-600/20 transition-all flex items-center gap-2 text-sm">
                        <i class="fa-brands fa-whatsapp text-lg"></i>
                        <span>Book Pickup</span>
                    </a>
                </div>

                <!-- Mobile Menu Toggle Button -->
                <button id="mobile-menu-btn" class="lg:hidden p-2 rounded-lg text-slate-600 hover:bg-slate-100 focus:outline-none" aria-label="Toggle menu">
                    <i class="fa-solid fa-bars text-2xl"></i>
                </button>
            </div>
        </div>

        <!-- Mobile Drawer Menu -->
        <div id="mobile-menu" class="hidden lg:hidden bg-white border-b border-slate-200 px-4 pt-2 pb-6 space-y-1 shadow-xl">
            <a href="#home" class="mobile-nav-link block px-3 py-2.5 rounded-lg text-base font-semibold text-slate-800 hover:bg-brand-50 hover:text-brand-600">🏠 Home</a>
            <a href="#services" class="mobile-nav-link block px-3 py-2.5 rounded-lg text-base font-semibold text-slate-800 hover:bg-brand-50 hover:text-brand-600">👕 Services</a>
            <a href="#rates" class="mobile-nav-link block px-3 py-2.5 rounded-lg text-base font-semibold text-slate-800 hover:bg-brand-50 hover:text-brand-600">🧥 Dry Cleaning & Steam Press</a>
            <a href="#pricing" class="mobile-nav-link block px-3 py-2.5 rounded-lg text-base font-semibold text-slate-800 hover:bg-brand-50 hover:text-brand-600">💰 Pricing Plans</a>
            <a href="#calculator" class="mobile-nav-link block px-3 py-2.5 rounded-lg text-base font-semibold text-slate-800 hover:bg-brand-50 hover:text-brand-600">🧮 Estimate Calculator</a>
            <a href="#how-it-works" class="mobile-nav-link block px-3 py-2.5 rounded-lg text-base font-semibold text-slate-800 hover:bg-brand-50 hover:text-brand-600">🔄 How It Works</a>
            <a href="#why-us" class="mobile-nav-link block px-3 py-2.5 rounded-lg text-base font-semibold text-slate-800 hover:bg-brand-50 hover:text-brand-600">❓ Why Choose Us</a>
            <a href="#reviews" class="mobile-nav-link block px-3 py-2.5 rounded-lg text-base font-semibold text-slate-800 hover:bg-brand-50 hover:text-brand-600">⭐ Customer Reviews</a>
            <a href="#about" class="mobile-nav-link block px-3 py-2.5 rounded-lg text-base font-semibold text-slate-800 hover:bg-brand-50 hover:text-brand-600">ℹ️ About Us</a>
            <a href="#contact" class="mobile-nav-link block px-3 py-2.5 rounded-lg text-base font-semibold text-slate-800 hover:bg-brand-50 hover:text-brand-600">📞 Contact Us</a>
            <div class="pt-4 flex flex-col gap-2">
                <a href="https://wa.me/918527901289?text=Hello%20Samrat%20Laundry,%20I%20would%20like%20to%20book%20a%20pickup." target="_blank" class="w-full py-3 bg-emerald-600 text-white font-bold rounded-xl text-center flex items-center justify-center gap-2">
                    <i class="fa-brands fa-whatsapp text-xl"></i> Book Pickup via WhatsApp
                </a>
                <a href="tel:8527901289" class="w-full py-3 bg-slate-100 text-slate-800 font-bold rounded-xl text-center flex items-center justify-center gap-2 border border-slate-300">
                    <i class="fa-solid fa-phone text-brand-600"></i> Call 8527901289
                </a>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="home" class="relative hero-gradient text-white overflow-hidden py-16 lg:py-24">
        <!-- Background Decorative Bubbles/Shapes -->
        <div class="absolute -top-24 -right-24 w-96 h-96 bg-brand-500/20 rounded-full blur-3xl pointer-events-none"></div>
        <div class="absolute bottom-0 left-0 w-80 h-80 bg-cyan-400/10 rounded-full blur-2xl pointer-events-none"></div>

        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-center">
                <!-- Left Text Banner -->
                <div class="lg:col-span-7 space-y-6 text-center lg:text-left">
                    <div class="inline-flex items-center gap-2 px-3.5 py-1.5 rounded-full bg-white/10 backdrop-blur-md border border-white/20 text-emerald-300 text-xs sm:text-sm font-semibold">
                        <i class="fa-solid fa-circle-check text-emerald-400"></i>
                        <span>DLF Phase 3 & Nearby Gurgaon's #1 Care</span>
                    </div>

                    <h1 class="text-3xl sm:text-5xl lg:text-6xl font-black leading-tight tracking-tight">
                        Professional Laundry & <span class="text-transparent bg-clip-text bg-gradient-to-r from-sky-200 via-cyan-200 to-emerald-200">Dry Cleaning</span> Service
                    </h1>

                    <p class="text-base sm:text-xl text-sky-100 font-medium max-w-2xl mx-auto lg:mx-0">
                        "Your Clothes, Our Responsibility" — Experience fresh, crisp, wrinkle-free garments delivered right to your doorstep in DLF Phase 3, Gurgaon.
                    </p>

                    <!-- Key Selling Badges Grid -->
                    <div class="grid grid-cols-2 sm:grid-cols-4 gap-3 pt-2 text-left">
                        <div class="bg-white/10 backdrop-blur-md border border-white/10 p-3 rounded-xl">
                            <div class="text-xs text-sky-200 font-medium">Wash & Fold</div>
                            <div class="text-lg font-extrabold text-white">₹55 <span class="text-xs font-normal">/ Kg</span></div>
                        </div>
                        <div class="bg-white/10 backdrop-blur-md border border-white/10 p-3 rounded-xl">
                            <div class="text-xs text-sky-200 font-medium">Wash & Iron</div>
                            <div class="text-lg font-extrabold text-white">₹65 <span class="text-xs font-normal">/ Kg</span></div>
                        </div>
                        <div class="bg-white/10 backdrop-blur-md border border-white/10 p-3 rounded-xl">
                            <div class="text-xs text-sky-200 font-medium">Steam Press</div>
                            <div class="text-lg font-extrabold text-white">Starts ₹20</div>
                        </div>
                        <div class="bg-white/10 backdrop-blur-md border border-white/10 p-3 rounded-xl">
                            <div class="text-xs text-amber-300 font-medium">Tuesday Offer</div>
                            <div class="text-lg font-extrabold text-amber-300">15% OFF</div>
                        </div>
                    </div>

                    <!-- CTA Buttons -->
                    <div class="flex flex-col sm:flex-row items-center justify-center lg:justify-start gap-4 pt-4">
                        <a href="https://wa.me/918527901289?text=Hello%20Samrat%20Laundry,%20I%20would%20like%20to%20schedule%20a%20pickup!"
                           target="_blank"
                           class="w-full sm:w-auto bg-emerald-500 hover:bg-emerald-600 text-white font-extrabold px-8 py-4 rounded-xl shadow-xl shadow-emerald-900/30 hover:scale-105 transition-all text-center flex items-center justify-center gap-3 text-lg">
                            <i class="fa-brands fa-whatsapp text-2xl"></i>
                            <span>Instant WhatsApp Booking</span>
                        </a>
                        <a href="#calculator"
                           class="w-full sm:w-auto bg-white/15 hover:bg-white/25 text-white border border-white/30 font-bold px-8 py-4 rounded-xl backdrop-blur-md hover:scale-105 transition-all text-center flex items-center justify-center gap-2 text-lg">
                            <i class="fa-solid fa-calculator"></i>
                            <span>Calculate Your Price</span>
                        </a>
                    </div>

                    <!-- Service highlights list -->
                    <div class="flex items-center justify-center lg:justify-start gap-6 text-xs sm:text-sm text-sky-100 pt-2 flex-wrap">
                        <span class="flex items-center gap-1.5"><i class="fa-solid fa-truck text-emerald-400"></i> Free Doorstep Pickup</span>
                        <span class="flex items-center gap-1.5"><i class="fa-solid fa-bolt text-amber-400"></i> Same-Day Express Service</span>
                        <span class="flex items-center gap-1.5"><i class="fa-solid fa-gem text-cyan-300"></i> Softener & Antiseptic Care</span>
                    </div>
                </div>

                <!-- Right Visual Card / Feature Banner -->
                <div class="lg:col-span-5">
                    <div class="bg-white text-slate-800 rounded-3xl p-6 sm:p-8 shadow-2xl relative border border-slate-100">
                        <div class="absolute -top-3 -right-3 bg-gradient-to-r from-amber-500 to-orange-500 text-white font-black text-xs px-3 py-1.5 rounded-full shadow-lg uppercase tracking-wider badge-pulse">
                            <i class="fa-solid fa-star mr-1"></i> Top Rated Laundry
                        </div>

                        <div class="space-y-5">
                            <div class="flex items-center gap-4 border-b border-slate-100 pb-4">
                                <div class="w-14 h-14 bg-brand-50 rounded-2xl flex items-center justify-center text-brand-600 font-bold text-2xl shrink-0">
                                    <i class="fa-solid fa-location-dot"></i>
                                </div>
                                <div>
                                    <h2 class="font-extrabold text-slate-900 text-lg">DLF Phase 3 Hub</h2>
                                    <p class="text-xs text-slate-500">U-42/8, U Block, Sector 24, Gurugram</p>
                                    <div class="mt-1 text-xs text-emerald-600 font-bold flex items-center gap-1">
                                        <span class="w-2 h-2 rounded-full bg-emerald-500 inline-block animate-ping"></span>
                                        <span>Open Today: 10:30 AM – 10:30 PM</span>
                                    </div>
                                </div>
                            </div>

                            <!-- Highlights list -->
                            <div class="space-y-3 text-sm">
                                <div class="flex items-start gap-3 p-2.5 rounded-xl bg-slate-50">
                                    <i class="fa-solid fa-check-circle text-brand-600 text-lg mt-0.5"></i>
                                    <div>
                                        <div class="font-bold text-slate-800">Separate Hygienic Wash</div>
                                        <div class="text-xs text-slate-500">Your clothes are never mixed with other customers' items.</div>
                                    </div>
                                </div>
                                <div class="flex items-start gap-3 p-2.5 rounded-xl bg-slate-50">
                                    <i class="fa-solid fa-check-circle text-brand-600 text-lg mt-0.5"></i>
                                    <div>
                                        <div class="font-bold text-slate-800">Steam Pressing & Neat Folding</div>
                                        <div class="text-xs text-slate-500">Wrinkle-free crisp standard with premium shirt hangers or packing.</div>
                                    </div>
                                </div>
                                <div class="flex items-start gap-3 p-2.5 rounded-xl bg-slate-50">
                                    <i class="fa-solid fa-check-circle text-brand-600 text-lg mt-0.5"></i>
                                    <div>
                                        <div class="font-bold text-slate-800">Free Pickup & Delivery</div>
                                        <div class="text-xs text-slate-500">Available across DLF Phase 3 & surrounding sectors.</div>
                                    </div>
                                </div>
                            </div>

                            <!-- Phone Banner Callout -->
                            <div class="bg-gradient-to-r from-brand-600 to-brand-800 rounded-2xl p-4 text-white flex items-center justify-between">
                                <div>
                                    <div class="text-xs text-brand-200 uppercase font-semibold">Direct Booking Line</div>
                                    <div class="text-xl font-black">8527901289</div>
                                </div>
                                <a href="tel:8527901289" class="bg-white text-brand-800 px-4 py-2 rounded-xl text-xs font-black uppercase hover:bg-brand-50 transition-colors">
            
xt-sm sm:text-base mt-2">Select your items below to calculate estimated costs instantly according to our rate list and order directly on WhatsApp.</p> </div> <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-start"> <!-- Calculator Controls Left --> <div class="lg:col-span-7 bg-white/10 backdrop-blur-xl p-6 sm:p-8 rounded-3xl border border-white/10 space-y-8"> <!-- Tab Selector --> <div class="flex p-1 bg-slate-800/80 rounded-xl gap-1"> <button id="calc-tab-laundry" onclick="switchCalcTab('laundry')" class="flex-1 py-2.5 rounded-lg text-xs sm:text-sm font-bold transition-all bg-brand-600 text-white shadow-md"> ⚖️ Laundry by Weight (Kg) </button> <button id="calc-tab-press" onclick="switchCalcTab('press')" class="flex-1 py-2.5 rounded-lg text-xs sm:text-sm font-bold transition-all text-slate-400 hover:text-white"> 💨 Steam Press </button> <button id="calc-tab-dryclean" onclick="switchCalcTab('dryclean')" class="flex-1 py-2.5 rounded-lg text-xs sm:text-sm font-bold transition-all text-slate-400 hover:text-white"> 🧥 Dry Cleaning </button> </div> <!-- TAB 1: Laundry by Weight --> <div id="calc-panel-laundry" class="space-y-6"> <div> <div class="flex justify-between items-center mb-2"> <label class="text-sm font-semibold text-slate-200">Select Laundry Service Type:</label> </div> <select id="laundry-type" onchange="calculateTotal()" class="w-full bg-slate-800 border border-slate-700 text-white text-sm rounded-xl p-3 focus:outline-none focus:ring-2 focus:ring-brand-500"> <option value="55" data-name="Wash, Dry & Fold">Wash, Dry & Fold — ₹55 / Kg</option> <option value="65" data-name="Wash & Iron">Wash & Iron — ₹65 / Kg</option> <option value="100" data-name="Winter Woolen Clothes">Winter Woolen Clothes — ₹100 / Kg</option> <option value="145" data-name="Premium Laundry">Premium Laundry Care — ₹145 / Kg</option> </select> </div> <div> <div class="flex justify-between items-center mb-2"> <label class="text-sm font-semibold text-slate-200">Estimated Weight (Kg):</label> <span class="text-2xl font-black text-brand-400"><span id="weight-val">4</span> Kg</span> </div> <input type="range" id="laundry-weight" min="1" max="25" value="4" oninput="updateWeightDisplay(this.value)" class="w-full h-2 bg-slate-700 rounded-lg appearance-none cursor-pointer accent-brand-500"> <div class="flex justify-between text-xs text-slate-400 mt-1"> <span>1 Kg</span> <span>4 Kg (Min delivery)</span> <span>15 Kg</span> <span>25 Kg</span> </div> </div> <!-- Checkbox for Express turnaround --> <div class="flex items-center gap-3 bg-slate-800/50 p-3 rounded-xl border border-slate-700"> <input type="checkbox" id="express-charge" onchange="calculateTotal()" class="w-4 h-4 text-brand-600 rounded bg-slate-700 border-slate-600 focus:ring-brand-500"> <label for="express-charge" class="text-xs sm:text-sm text-slate-200 cursor-pointer"> Add Express Urgent Service (+₹150 Flat Charge) </label> </div> </div> <!-- TAB 2: Steam Press Itemized --> <div id="calc-panel-press" class="hidden space-y-4"> <p class="text-xs text-slate-300">Select garment counts for professional vacuum steam press:</p> <div class="grid grid-cols-1 sm:grid-cols-2 gap-3 max-h-64 overflow-y-auto pr-2"> <div class="flex items-center justify-between bg-slate-800/60 p-2.5 rounded-xl border border-slate-700"> <div><div class="text-sm font-bold">Shirt / T-Shirt</div><div class="text-xs text-brand-400">₹20 / pc</div></div> <input type="number" min="0" value="0" id="sp-shirt" onchange="calculateTotal()" class="w-16 bg-slate-900 text-center border border-slate-700 rounded-lg py-1 text-sm font-bold"> </div> <div class="flex items-center justify-between bg-slate-800/60 p-2.5 rounded-xl border border-slate-700"> <div><div class="text-sm font-bold">Pant / Jeans</div><div class="text-xs text-brand-400">₹20 / pc</div></div> <input type="number" min="0" value="0" id="sp-pant" onchange="calculateTotal()" class="w-16 bg-slate-900 text-center border border-slate-700 rounded-lg py-1 text-sm font-bold"> </div> <div class="flex items-center justify-between bg-slate-800/60 p-2.5 rounded-xl border border-slate-700"> <div><div class="text-sm font-bold">Kurta / Pyjama</div><div class="text-xs text-brand-400">₹25 / pc</div></div> <input type="number" min="0" value="0" id="sp-kurta" onchange="calculateTotal()" class="w-16 bg-slate-900 text-center border border-slate-700 rounded-lg py-1 text-sm font-bold"> </div> <div class="flex items-center justify-between bg-slate-800/60 p-2.5 rounded-xl border border-slate-700"> <div><div class="text-sm font-bold">Cotton Saree</div><div class="text-xs text-brand-400">₹50 / pc</div></div> <input type="number" min="0" value="0" id="sp-saree" onchange="calculateTotal()" class="w-16 bg-slate-900 text-center border border-slate-700 rounded-lg py-1 text-sm font-bold"> </div> <div class="flex items-center justify-between bg-slate-800/60 p-2.5 rounded-xl border border-slate-700"> <div><div class="text-sm font-bold">Blazer / Coat</div><div class="text-xs text-brand-400">₹80 / pc</div></div> <input type="number" min="0" value="0" id="sp-blazer" onchange="calculateTotal()" class="w-16 bg-slate-900 text-center border border-slate-700 rounded-lg py-1 text-sm font-bold"> </div> <div class="flex items-center justify-between bg-slate-800/60 p-2.5 rounded-xl border border-slate-700"> <div><div class="text-sm font-bold">Bedsheet (Double)</div><div class="text-xs text-brand-400">₹60 / pc</div></div> <input type="number" min="0" value="0" id="sp-bedsheet" onchange="calculateTotal()" class="w-16 bg-slate-900 text-center border border-slate-700 rounded-lg py-1 text-sm font-bold"> </div> </div> </div> <!-- TAB 3: Dry Cleaning Itemized --> <div id="calc-panel-dryclean" class="hidden space-y-4"> <p class="text-xs text-slate-300">Select garments for premium chemical dry cleaning:</p> <div class="grid grid-cols-1 sm:grid-cols-2 gap-3 max-h-64 overflow-y-auto pr-2"> <div class="flex items-center justify-between bg-slate-800/60 p-2.5 rounded-xl border border-slate-700"> <div><div class="text-sm font-bold">Blazer / Jacket</div><div class="text-xs text-brand-400">₹200 / pc</div></div> <input type="number" min="0" value="0" id="dc-blazer" onchange="calculateTotal()" class="w-16 bg-slate-900 text-center border border-slate-700 rounded-lg py-1 text-sm font-bold"> </div> <div class="flex items-center justify-between bg-slate-800/60 p-2.5 rounded-xl border border-slate-700"> <div><div class="text-sm font-bold">Coat Pant (2 Pcs)</div><div class="text-xs text-brand-400">₹300 / set</div></div> <input type="number" min="0" value="0" id="dc-suit2" onchange="calculateTotal()" class="w-16 bg-slate-900 text-center border border-slate-700 rounded-lg py-1 text-sm font-bold"> </div> <div class="flex items-center justify-between bg-slate-800/60 p-2.5 rounded-xl border border-slate-700"> <div><div class="text-sm font-bold">3 Pcs Suit</div><div class="text-xs text-brand-400">₹350 / set</div></div> <input type="number" min="0" value="0" id="dc-suit3" onchange="calculateTotal()" class="w-16 bg-slate-900 text-center border border-slate-700 rounded-lg py-1 text-sm font-bold"> </div> <div class="flex items-center justify-between bg-slate-800/60 p-2.5 rounded-xl border border-slate-700"> <div><div class="text-sm font-bold">Designer Saree</div><div class="text-xs text-brand-400">₹350 / pc</div></div> <input type="number" min="0" value="0" id="dc-saree" onchange="calculateTotal()" class="w-16 bg-slate-900 text-center border border-slate-700 rounded-lg py-1 text-sm font-bold"> </div> <div class="flex items-center justify-between bg-slate-800/60 p-2.5 rounded-xl border border-slate-700"> <div><div class="text-sm font-bold">Blanket Wash</div><div class="text-xs text-brand-400">₹250 / pc</div></div> <input type="number" min="0" value="0" id="dc-blanket" onchange="calculateTotal()" class="w-16 bg-slate-900 text-center border border-slate-700 rounded-lg py-1 text-sm font-bold"> </div> <div class="flex items-center justify-between bg-slate-800/60 p-2.5 rounded-xl border border-slate-700"> <div><div class="text-sm font-bold">Shoe Dryclean</div><div class="text-xs text-brand-400">₹250 / pair</div></div> <input type="number" min="0" value="0" id="dc-shoes" onchange="calculateTotal()" class="w-16 bg-slate-900 text-center border border-slate-700 rounded-lg py-1 text-sm font-bold"> </div> </div> </div> </div> <!-- Calculator Summary Card Right --> <div class="lg:col-span-5 bg-white text-slate-900 p-6 sm:p-8 rounded-3xl shadow-2xl space-y-6"> <div class="border-b border-slate-200 pb-4 flex justify-between items-center"> <h3 class="text-lg font-extrabold text-slate-900">Estimated Summary</h3> <span class="text-xs font-semibold px-2.5 py-1 bg-emerald-100 text-emerald-800 rounded-full">Transparent Pricing</span> </div> <!-- Breakdown items --> <div id="calc-summary-list" class="space-y-3 text-sm min-h-[140px] max-h-48 overflow-y-auto"> <!-- Populated via JS --> </div> <!-- Tuesday Discount Banner inside calc if applicable --> <div id="tuesday-discount-row" class="hidden bg-amber-50 border border-amber-200 rounded-xl p-3 text-amber-900 text-xs flex justify-between items-center"> <span>🎉 Tuesday Discount (15% OFF):</span> <span id="tuesday-discount-val" class="font-bold text-amber-700">-₹0</span> </div> <div class="bg-slate-100 p-4 rounded-2xl flex justify-between items-center"> <div> <span class="text-xs text-slate-500 uppercase font-bold block">Grand Total</span> <span class="text-xs text-slate-400">Taxes included</span> </div> <div class="text-3xl font-black text-brand-700" id="grand-total-display">₹220</div> </div> <!-- User Details for WhatsApp Submission --> <div class="space-y-3 pt-2"> <input type="text" id="c<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Samrat Laundry & Drycleaning Service | DLF Phase 3 Gurgaon</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        brand: {
                            50: '#f0f7ff',
                            100: '#e0effe',
                            200: '#bae0fd',
                            500: '#0284c7',
                            600: '#026aa7',
                            700: '#0369a1',
                            800: '#075985',
                            900: '#0c4a6e',
                        },
                        accent: {
                            500: '#10b981',
                            600: '#059669',
                            yellow: '#f59e0b'
                        }
                    },
                    fontFamily: {
                        sans: ['Plus Jakarta Sans', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    <style>
        body { font-family: 'Plus Jakarta Sans', sans-serif; }
        .glass-card {
            background: rgba(255, 255, 255, 0.85);
            backdrop-filter: blur(12px);
            border: 1px solid rgba(255, 255, 255, 0.6);
        }
        .glass-nav {
            background: rgba(255, 255, 255, 0.92);
            backdrop-filter: blur(10px);
        }
        .hero-gradient {
            background: linear-gradient(135deg, #0f172a 0%, #0369a1 50%, #0284c7 100%);
        }
        .badge-pulse {
            animation: pulse-ring 2s cubic-bezier(0.4, 0, 0.6, 1) infinite;
        }
        @keyframes pulse-ring {
            0%, 100% { opacity: 1; transform: scale(1); }
            50% { opacity: 0.85; transform: scale(1.03); }
        }
        /* Custom scrollbar */
        ::-webkit-scrollbar { width: 8px; }
        ::-webkit-scrollbar-track { background: #f1f5f9; }
        ::-webkit-scrollbar-thumb { background: #0284c7; border-radius: 4px; }
    </style>
</head>
<body class="bg-slate-50 text-slate-800 antialiased selection:bg-brand-500 selection:text-white">

    <!-- Floating WhatsApp CTA -->
    <a href="https://wa.me/918527901289?text=Hello%20Samrat%20Laundry,%20I%20would%20like%20to%20book%20a%20pickup!"
       target="_blank"
       rel="noopener"
       aria-label="Chat on WhatsApp"
       class="fixed bottom-6 right-6 z-50 bg-emerald-500 hover:bg-emerald-600 text-white p-4 rounded-full shadow-2xl transition-all duration-300 hover:scale-110 flex items-center gap-2 group cursor-pointer border-2 border-white">
        <i class="fa-brands fa-whatsapp text-3xl"></i>
        <span class="max-w-0 overflow-hidden whitespace-nowrap group-hover:max-w-xs transition-all duration-500 ease-in-out text-sm font-bold pl-0 group-hover:pl-1">Book Pickup Now</span>
    </a>

    <!-- Top Announcement Bar -->
    <div class="bg-gradient-to-r from-amber-500 via-orange-500 to-amber-600 text-white text-xs sm:text-sm py-2 px-4 text-center font-medium shadow-sm flex items-center justify-center gap-2 flex-wrap">
        <span class="bg-white/20 text-white px-2 py-0.5 rounded-full text-xs uppercase font-extrabold tracking-wider">Tuesday Special</span>
        <span>🎉 Get <strong>15% OFF</strong> on Laundry (Min. 8 Kg) Every Tuesday!</span>
        <span class="hidden md:inline">|</span>
        <span class="hidden md:inline"><i class="fa-solid fa-truck-fast mr-1"></i> FREE Pickup & Delivery in DLF Phase 3</span>
    </div>

    <!-- Navigation Bar -->
    <header class="sticky top-0 z-40 glass-nav border-b border-slate-200/80 transition-all duration-300" id="main-header">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-20">
                <!-- Brand Logo -->
                <a href="#home" class="flex items-center gap-3 group">
                    <div class="w-12 h-12 bg-grad
