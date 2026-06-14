Here is the updated code for **Themelios Construction Limited**.

I have seamlessly integrated your exact philosophy statement—**"Our solid foundation with reliable construction and desire towards excellence in the work done"**—into the primary content panel, alongside the logo graphic and the corporate motto.

### Updated Website Code (`index.html`)

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Themelios Construction Limited | Climb With Us</title>
    <!-- Tailwind CSS for modern, responsive styling -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        brandBlue: '#1e3a8a', // Deep Steel Blue
                        brandLightBlue: '#3b82f6', // Accent Blue
                        brandGray: '#4b5563', // Slate Gray
                        brandLightGray: '#f3f4f6' // Light Gray Background
                    }
                }
            }
        }
    </script>
    <!-- FontAwesome for professional icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body class="bg-brandLightGray text-gray-800 font-sans antialiased">

    <!-- Header / Navigation -->
    <header class="bg-white shadow-md fixed w-full z-50 transition-all duration-300">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-20 flex items-center justify-between">
            <!-- Logo Section utilizing the specified webp image -->
            <div class="flex items-center space-x-3">
                <img src="guy-worker-strong-figure-climb-carry-goal-white-sky-text-space-line-black-ink-hand-drawn-myth-male-hero-force-useless-vain-155580741.webp" 
                     alt="Themelios Construction Emblem" 
                     class="h-14 w-auto object-contain">
                <div class="flex flex-col">
                    <span class="text-xl font-black text-brandBlue tracking-tight leading-none">THEMELIOS</span>
                    <span class="text-[10px] font-bold text-brandGray tracking-widest uppercase mt-0.5">CONSTRUCTION</span>
                </div>
            </div>
            
            <!-- Desktop Nav -->
            <nav class="hidden md:flex space-x-8 text-sm font-semibold uppercase tracking-wider text-brandGray">
                <a href="#hero" class="hover:text-brandBlue transition">Home</a>
                <a href="#about" class="hover:text-brandBlue transition">About Us</a>
                <a href="#services" class="hover:text-brandBlue transition">Services</a>
                <a href="#contact" class="hover:text-brandBlue transition">Contact</a>
            </nav>

            <!-- Call to Action Button -->
            <div class="hidden md:flex">
                <a href="mailto:mbirimatibenga3@gmail.com?subject=Inquiry%20to%20Themelios%20Construction" class="bg-brandBlue text-white px-5 py-2.5 rounded shadow hover:bg-brandLightBlue transition text-sm font-medium">
                    Get a Quote
                </a>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="hero" class="relative pt-20 h-screen flex items-center justify-center bg-gradient-to-r from-slate-900 to-slate-700 text-white">
        <div class="absolute inset-0 opacity-20 bg-[radial-gradient(#3b82f6_1px,transparent_1px)] [background-size:16px_16px]"></div>
        
        <div class="relative max-w-4xl mx-auto text-center px-4">
            <span class="text-brandLightBlue uppercase tracking-widest font-semibold text-xs bg-brandBlue/40 px-3 py-1 rounded-full inline-block mb-4">
                Themelios Construction Limited
            </span>
            <h1 class="text-4xl md:text-6xl font-extrabold tracking-tight mb-4">
                Building Futures on <span class="text-transparent bg-clip-text bg-gradient-to-r from-blue-400 to-slate-300">Solid Foundations</span>
            </h1>
            <!-- Motto Integration -->
            <p class="text-2xl md:text-3xl font-light tracking-wide text-blue-300 italic mb-8">
                "Climb with us"
            </p>
            <p class="text-base md:text-lg text-gray-300 mb-8 max-w-xl mx-auto">
                No matter the scale or complexity of the summit, we bring engineering precision and unshakeable resilience to every project baseline.
            </p>
            <div class="flex flex-col sm:flex-row justify-center gap-4">
                <a href="#services" class="bg-brandBlue hover:bg-brandLightBlue px-8 py-3 rounded-md font-semibold transition text-center shadow-lg">Our Capabilities</a>
                <a href="#contact" class="bg-transparent border-2 border-white hover:bg-white hover:text-slate-900 px-8 py-3 rounded-md font-semibold transition text-center">Contact Our Team</a>
            </div>
        </div>
    </section>

    <!-- About / Philosophy Section -->
    <section id="about" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
                <div>
                    <span class="text-brandBlue font-bold uppercase tracking-wider text-xs block mb-2">Our Philosophy</span>
                    <!-- Updated Philosophy Statement -->
                    <h2 class="text-2xl md:text-3xl font-bold text-slate-900 mb-6 leading-tight">
                        "Our solid foundation with reliable construction and desire towards excellence in the work done"
                    </h2>
                    <p class="text-brandGray leading-relaxed mb-4">
                        Derived from the Greek term for "foundation," <strong>Themelios Construction Limited</strong> operates precisely on this standard. We pair structural dependability with an unyielding commitment to performance quality across every civil and structural asset we deliver.
                    </p>
                    <p class="text-brandGray leading-relaxed mb-6">
                        Like the powerful icon carrying immense weight uphill, our teams embrace challenging structural environments, robust timelines, and detailed engineering blueprints with deliberate execution and meticulous care.
                    </p>
                    <div class="grid grid-cols-2 gap-6 pt-4 border-t border-gray-100">
                        <div>
                            <h4 class="text-2xl font-bold text-brandBlue">100%</h4>
                            <p class="text-sm text-brandGray font-medium">Safety Compliance Record</p>
                        </div>
                        <div>
                            <h4 class="text-2xl font-bold text-brandBlue">Turnkey</h4>
                            <p class="text-sm text-brandGray font-medium">Project Delivery</p>
                        </div>
                    </div>
                </div>
                
                <!-- Graphic Representation showing the emblem with the Motto -->
                <div class="bg-brandLightGray p-8 rounded-2xl border border-gray-200 shadow-sm flex flex-col items-center justify-center text-center relative overflow-hidden">
                    <img src="guy-worker-strong-figure-climb-carry-goal-white-sky-text-space-line-black-ink-hand-drawn-myth-male-hero-force-useless-vain-155580741.webp" 
                         alt="Climb with us graphic" 
                         class="h-64 w-auto object-contain mix-blend-multiply mb-4">
                    <h3 class="text-2xl font-serif italic text-brandBlue font-semibold">Climb with us</h3>
                    <p class="text-xs text-brandGray mt-1 tracking-wider uppercase font-bold">The Core Motto of Themelios</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-20 bg-brandLightGray">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <span class="text-brandBlue font-bold uppercase tracking-wider text-xs block mb-2">Capabilities</span>
            <h2 class="text-3xl md:text-4xl font-bold text-slate-900 mb-12">Our Specialized Services</h2>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Card 1 -->
                <div class="bg-white p-8 rounded-xl shadow-sm border border-gray-100 hover:shadow-md transition text-left group">
                    <div class="w-12 h-12 rounded-lg bg-blue-50 text-brandBlue flex items-center justify-center text-xl font-bold mb-6 group-hover:bg-brandBlue group-hover:text-white transition">
                        <i class="fa-solid fa-building"></i>
                    </div>
                    <h3 class="text-xl font-bold text-slate-900 mb-3">Commercial & Civil Construction</h3>
                    <p class="text-brandGray text-sm leading-relaxed">
                        Full-scale construction of office complexes, industrial retail spots, logistical distribution hubs, and commercial developments.
                    </p>
                </div>
                <!-- Card 2 -->
                <div class="bg-white p-8 rounded-xl shadow-sm border border-gray-100 hover:shadow-md transition text-left group">
                    <div class="w-12 h-12 rounded-lg bg-blue-50 text-brandBlue flex items-center justify-center text-xl font-bold mb-6 group-hover:bg-brandBlue group-hover:text-white transition">
                        <i class="fa-solid fa-helmet-safety"></i>
                    </div>
                    <h3 class="text-xl font-bold text-slate-900 mb-3">Project Management</h3>
                    <p class="text-brandGray text-sm leading-relaxed">
                        End-to-end site oversight, procurement infrastructure, material logistics, and strict health and safety metric reporting.
                    </p>
                </div>
                <!-- Card 3 -->
                <div class="bg-white p-8 rounded-xl shadow-sm border border-gray-100 hover:shadow-md transition text-left group">
                    <div class="w-12 h-12 rounded-lg bg-blue-50 text-brandBlue flex items-center justify-center text-xl font-bold mb-6 group-hover:bg-brandBlue group-hover:text-white transition">
                        <i class="fa-solid fa-compass-drafting"></i>
                    </div>
                    <h3 class="text-xl font-bold text-slate-900 mb-3">Structural & Foundations</h3>
                    <p class="text-brandGray text-sm leading-relaxed">
                        Specialized excavation services, high-grade concrete casting, heavy earth retention engineering, and durable foundation bases.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-20 bg-white">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <h2 class="text-3xl md:text-4xl font-bold text-slate-900 mb-4">Start Your Next Ascent</h2>
            <p class="text-brandGray mb-10 max-w-xl mx-auto">
                Ready to take your structural requirements to the next peak? Connect with our technical bidding team directly.
            </p>
            
            <!-- Direct Email Link -->
            <div class="inline-flex flex-col sm:flex-row items-center justify-center bg-brandLightGray border border-gray-200 rounded-xl p-6 sm:p-8 w-full gap-6 shadow-inner">
                <div class="flex items-center justify-center w-12 h-12 rounded-full bg-brandBlue text-white text-xl">
                    <i class="fa-solid fa-envelope"></i>
                </div>
                <div class="text-left flex-1 text-center sm:text-left">
                    <p class="text-xs font-bold uppercase tracking-wider text-brandGray">Direct Project Communications</p>
                    <p class="text-xl font-mono font-bold text-brandBlue select-all">mbirimatibenga3@gmail.com</p>
                </div>
                <a href="mailto:mbirimatibenga3@gmail.com?subject=Project%20Inquiry%20-%20Themelios%20Construction" class="bg-brandBlue hover:bg-brandLightBlue text-white px-6 py-3 rounded-md font-medium tracking-wide transition shadow w-full sm:w-auto">
                    Launch Email Client
                </a>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-slate-900 text-gray-400 py-12 border-t border-slate-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex flex-col md:flex-row items-center justify-between gap-6">
            <div class="text-center md:text-left flex items-center space-x-3">
                <div class="text-white font-bold tracking-wider">
                    <p>THEMELIOS CONSTRUCTION LIMITED</p>
                    <p class="text-xs font-normal italic text-blue-400 mt-0.5">"Climb with us"</p>
                </div>
            </div>
            <div class="text-xs text-center md:text-right">
                <p>&copy; 2026 Themelios Construction Limited. All Rights Reserved.</p>
            </div>
        </div>
    </footer>

</body>
</html>

```
