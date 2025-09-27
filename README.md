
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Riverside Records | Lakeview's Premier Record Store</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
    </style>
</head>
<body class="bg-slate-900 text-white">

    <!-- Header & Navigation -->
    <header class="py-6 px-4 md:px-8">
        <nav class="flex justify-between items-center max-w-7xl mx-auto">
            <a href="#" class="text-3xl font-bold text-pink-500">Riverside Records</a>
            <div class="hidden md:flex space-x-8">
                <a href="#about" class="hover:text-pink-500 transition-colors">About Us</a>
                <a href="#staff" class="hover:text-pink-500 transition-colors">Staff</a>
                <a href="#contact" class="hover:text-pink-500 transition-colors">Contact</a>
            </div>
            <!-- Mobile Menu Button -->
            <button id="menu-button" class="md:hidden text-white focus:outline-none">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-4 6h4"></path></svg>
            </button>
        </nav>
        <!-- Mobile Menu -->
        <div id="mobile-menu" class="hidden md:hidden mt-4 text-center">
            <a href="#about" class="block py-2 hover:text-pink-500 transition-colors">About Us</a>
            <a href="#staff" class="block py-2 hover:text-pink-500 transition-colors">Staff</a>
            <a href="#contact" class="block py-2 hover:text-pink-500 transition-colors">Contact</a>
        </div>
    </header>

    <main class="max-w-7xl mx-auto px-4 md:px-8">
        
        <!-- Hero Section -->
        <section class="py-20 text-center">
            <h1 class="text-5xl md:text-7xl font-bold leading-tight">Your Soundtrack to Lakeview.</h1>
            <p class="mt-4 text-xl md:text-2xl text-slate-400">Vinyl records, good vibes, and a community that loves music as much as you do.</p>
            <a href="#about" class="mt-8 inline-block bg-pink-500 text-white font-semibold py-3 px-8 rounded-full shadow-lg hover:bg-pink-600 transition-colors">Learn More</a>
        </section>

        <!-- About Us Section -->
        <section id="about" class="py-20">
            <div class="grid md:grid-cols-2 gap-12 items-center">
                <div>
                    <h2 class="text-4xl font-bold text-pink-500">About Our Store</h2>
                    <p class="mt-4 text-lg text-slate-300">
                        Riverside Records is more than just a place to buy music; it's a community hub for Lakeview's music lovers. Nestled in the heart of the city, we're dedicated to bringing you the best in classic, new, and independent vinyl. Our mission is to provide a place where you can discover your next favorite album, connect with fellow enthusiasts, and experience music the way it was meant to be heard.
                    </p>
                    <p class="mt-4 text-lg text-slate-300">
                        We pride ourselves on a curated selection, knowledgeable staff, and a vibe that's all about passion for music. Come by, put on a pair of headphones, and lose yourself in the sound.
                    </p>
                </div>
                <!-- Placeholder Image -->
                <div class="rounded-2xl overflow-hidden shadow-2xl">
                    <img src="https://placehold.co/800x600/1e293b/d1d5db?text=Riverside+Records+Vibe" alt="Placeholder image of a record store" class="w-full h-auto object-cover">
                </div>
            </div>
        </section>

        <!-- Staff Section -->
        <section id="staff" class="py-20">
            <h2 class="text-4xl font-bold text-center text-pink-500">Our Team</h2>
            <p class="text-center mt-2 text-lg text-slate-400">Meet the passionate people behind the counter.</p>
            <div class="mt-12 text-center text-lg text-slate-300 space-y-4">
                <p>
                    **Store Manager:** The head of our team, responsible for the day-to-day operations and overall success of the store.
                </p>
                <p>
                    **Assistant Manager:** The manager's right-hand person, ready to lead and support the team.
                </p>
                <p>
                    **Music Curator / Genre Specialist:** Our experts, ready to guide you to your next favorite album and host special events.
                </p>
                <p>
                    **Sales Associate / Cashier:** The heart of the store, here to help you find what you need and handle all your transactions.
                </p>
                <p>
                    **Security:** Our team's watchful eyes, ensuring the safety of our staff, customers, and merchandise.
                </p>
            </div>
        </section>

        <!-- Contact Us Section -->
        <section id="contact" class="py-20">
            <h2 class="text-4xl font-bold text-center text-pink-500">Get In Touch</h2>
            <p class="text-center mt-2 text-lg text-slate-400">Whether you're looking for a specific album or want to join the team, we'd love to hear from you.</p>

            <div class="mt-12 flex flex-col md:flex-row items-center justify-center space-y-8 md:space-y-0 md:space-x-12">
                <div class="text-center md:text-left">
                    <h3 class="text-2xl font-semibold">Visit Us</h3>
                    <p class="mt-2 text-lg text-slate-300">
                        Building Number 2085, Freedom Ave.<br>
                        Lakeview City
                    </p>
                </div>
                <div class="text-center md:text-left">
                    <h3 class="text-2xl font-semibold">Connect with Us</h3>
                    <p class="mt-2 text-lg text-slate-300">
                        Join our Discord server to connect with the community and staff!
                    </p>
                    <a href="https://discord.gg/4MPJh335GK" class="mt-4 inline-block bg-pink-500 text-white font-semibold py-2 px-6 rounded-full hover:bg-pink-600 transition-colors">Join Discord</a>
                </div>
            </div>
        </section>
        
    </main>

    <!-- Footer -->
    <footer class="py-8 text-center text-slate-500">
        &copy; 2025 Riverside Records. All Rights Reserved.
    </footer>

    <!-- JavaScript for mobile menu -->
    <script>
        document.getElementById('menu-button').addEventListener('click', function() {
            var mobileMenu = document.getElementById('mobile-menu');
            if (mobileMenu.classList.contains('hidden')) {
                mobileMenu.classList.remove('hidden');
            } else {
                mobileMenu.classList.add('hidden');
            }
        });
    </script>
</body>
</html>
