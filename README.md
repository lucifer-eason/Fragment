<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fragment Wars | Competitive Growth Arena</title>
    <link rel="icon" type="image/x-icon" href="http://static.photos/gaming/200x200/7">
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/feather-icons/dist/feather.min.js"></script>
    <script src="https://unpkg.com/feather-icons"></script>
    <script src="https://cdn.jsdelivr.net/npm/vanta@latest/dist/vanta.globe.min.js"></script>
    <style>
        .gradient-text {
            background: linear-gradient(90deg, #3b82f6, #8b5cf6, #ec4899);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
        }
        .particle-bg {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -1;
        }
    </style>
</head>
<body class="bg-gray-900 text-white font-sans overflow-x-hidden">
    <!-- Vanta.js Background -->
    <div id="vanta-bg" class="particle-bg"></div>

    <!-- Navigation -->
    <nav class="container mx-auto px-6 py-4 flex justify-between items-center">
        <div class="flex items-center space-x-2">
            <div class="w-8 h-8 bg-blue-500 rounded-full animate-pulse"></div>
            <span class="text-xl font-bold gradient-text">Fragment Wars</span>
        </div>
        <div class="hidden md:flex space-x-8">
            <a href="#" class="hover:text-blue-400 transition">Features</a>
            <a href="#" class="hover:text-purple-400 transition">Gameplay</a>
            <a href="#" class="hover:text-pink-400 transition">Community</a>
            <a href="#" class="bg-gradient-to-r from-blue-500 to-purple-600 px-4 py-2 rounded-full hover:opacity-90 transition">Play Now</a>
        </div>
        <button class="md:hidden">
            <i data-feather="menu"></i>
        </button>
    </nav>

    <!-- Hero Section -->
    <section class="container mx-auto px-6 py-20 text-center">
        <div data-aos="fade-up">
            <h1 class="text-5xl md:text-7xl font-bold mb-6">
                <span class="gradient-text">Evolve. Compete.</span><br>
                <span class="text-white">Dominate.</span>
            </h1>
            <p class="text-xl md:text-2xl text-gray-300 max-w-3xl mx-auto mb-10">
                The ultimate arena where strategy meets survival. Grow your fragment core through cunning tactics and explosive showdowns.
            </p>
            <div class="flex flex-col sm:flex-row justify-center gap-4">
                <button class="bg-gradient-to-r from-blue-500 to-purple-600 px-8 py-4 rounded-full text-lg font-bold hover:opacity-90 transition transform hover:scale-105">
                    Play Free Now
                </button>
                <button class="border border-gray-600 px-8 py-4 rounded-full text-lg font-bold hover:bg-gray-800 transition transform hover:scale-105">
                    Watch Trailer
                </button>
            </div>
        </div>
    </section>

    <!-- Core Loop Section -->
    <section class="py-20 bg-gray-800/50 backdrop-blur-md">
        <div class="container mx-auto px-6">
            <div class="text-center mb-16" data-aos="fade-up">
                <h2 class="text-3xl md:text-4xl font-bold mb-4">The <span class="gradient-text">Fragment Cycle</span></h2>
                <p class="text-gray-300 max-w-2xl mx-auto">A dynamic gameplay loop that keeps every match fresh and intense</p>
            </div>
            
            <div class="grid md:grid-cols-4 gap-8">
                <!-- Birth -->
                <div class="bg-gray-900/50 p-6 rounded-xl border border-gray-700 hover:border-blue-500 transition" data-aos="fade-up" data-aos-delay="100">
                    <div class="w-16 h-16 bg-blue-900/30 rounded-full flex items-center justify-center mb-4 mx-auto">
                        <i data-feather="droplet" class="text-blue-400 w-8 h-8"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3 text-center">Birth</h3>
                    <p class="text-gray-400 text-center">Start as a small fragment core in a vast arena. Collect energy to grow your potential.</p>
                </div>
                
                <!-- Growth -->
                <div class="bg-gray-900/50 p-6 rounded-xl border border-gray-700 hover:border-purple-500 transition" data-aos="fade-up" data-aos-delay="200">
                    <div class="w-16 h-16 bg-purple-900/30 rounded-full flex items-center justify-center mb-4 mx-auto">
                        <i data-feather="activity" class="text-purple-400 w-8 h-8"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3 text-center">Growth</h3>
                    <p class="text-gray-400 text-center">Choose your path: brute size, specialized skills, or defensive structures.</p>
                </div>
                
                <!-- Combat -->
                <div class="bg-gray-900/50 p-6 rounded-xl border border-gray-700 hover:border-pink-500 transition" data-aos="fade-up" data-aos-delay="300">
                    <div class="w-16 h-16 bg-pink-900/30 rounded-full flex items-center justify-center mb-4 mx-auto">
                        <i data-feather="zap" class="text-pink-400 w-8 h-8"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3 text-center">Confrontation</h3>
                    <p class="text-gray-400 text-center">Engage in tactical battles using devour attacks, satellite defenses, or explosive collisions.</p>
                </div>
                
                <!-- Rebirth -->
                <div class="bg-gray-900/50 p-6 rounded-xl border border-gray-700 hover:border-indigo-500 transition" data-aos="fade-up" data-aos-delay="400">
                    <div class="w-16 h-16 bg-indigo-900/30 rounded-full flex items-center justify-center mb-4 mx-auto">
                        <i data-feather="refresh-cw" class="text-indigo-400 w-8 h-8"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3 text-center">Rebirth</h3>
                    <p class="text-gray-400 text-center">Death triggers explosive respawns, scattering fragments for others to claim.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Growth System -->
    <section class="py-20">
        <div class="container mx-auto px-6">
            <div class="flex flex-col md:flex-row items-center gap-12">
                <div class="md:w-1/2" data-aos="fade-right">
                    <img src="http://static.photos/technology/640x360/42" alt="Skill Tree" class="rounded-xl shadow-2xl border border-gray-700">
                </div>
                <div class="md:w-1/2" data-aos="fade-left">
                    <h2 class="text-3xl md:text-4xl font-bold mb-6">Dynamic <span class="gradient-text">Growth System</span></h2>
                    <p class="text-gray-300 mb-8">Every fragment you collect presents strategic choices that shape your playstyle and combat effectiveness.</p>
                    
                    <div class="space-y-6">
                        <div class="flex items-start">
                            <div class="bg-blue-500/20 p-2 rounded-lg mr-4">
                                <i data-feather="plus-circle" class="text-blue-400"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-lg mb-1">Energy Fragments</h4>
                                <p class="text-gray-400">Increase your core size and collision power at the cost of mobility.</p>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <div class="bg-purple-500/20 p-2 rounded-lg mr-4">
                                <i data-feather="cpu" class="text-purple-400"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-lg mb-1">Skill Fragments</h4>
                                <p class="text-gray-400">Unlock randomized skill trees with offensive, defensive, and utility branches.</p>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <div class="bg-pink-500/20 p-2 rounded-lg mr-4">
                                <i data-feather="shield" class="text-pink-400"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-lg mb-1">Structure Fragments</h4>
                                <p class="text-gray-400">Build defensive shells or offensive satellite fragments that orbit your core.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Social Features -->
    <section class="py-20 bg-gray-800/50 backdrop-blur-md">
        <div class="container mx-auto px-6">
            <div class="text-center mb-16" data-aos="fade-up">
                <h2 class="text-3xl md:text-4xl font-bold mb-4">Built for <span class="gradient-text">Social Play</span></h2>
                <p class="text-gray-300 max-w-2xl mx-auto">Share your epic moments and team up effortlessly</p>
            </div>
            
            <div class="grid md:grid-cols-3 gap-8">
                <div class="bg-gray-900/50 p-8 rounded-xl" data-aos="fade-up" data-aos-delay="100">
                    <div class="bg-gradient-to-br from-blue-500 to-purple-600 p-4 rounded-lg w-16 h-16 flex items-center justify-center mb-6 mx-auto">
                        <i data-feather="share-2" class="w-8 h-8"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3 text-center">Battle Tree Cards</h3>
                    <p class="text-gray-400 text-center mb-4">Automatically generated highlight cards of your best plays, ready for one-click sharing.</p>
                    <div class="flex justify-center space-x-4">
                        <i data-feather="twitter" class="text-blue-400"></i>
                        <i data-feather="instagram" class="text-pink-400"></i>
                        <i data-feather="youtube" class="text-red-400"></i>
                    </div>
                </div>
                
                <div class="bg-gray-900/50 p-8 rounded-xl" data-aos="fade-up" data-aos-delay="200">
                    <div class="bg-gradient-to-br from-purple-500 to-pink-600 p-4 rounded-lg w-16 h-16 flex items-center justify-center mb-6 mx-auto">
                        <i data-feather="users" class="w-8 h-8"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3 text-center">Instant Squad Up</h3>
                    <p class="text-gray-400 text-center mb-4">Share room links directly to your favorite platforms. No friend codes needed.</p>
                    <div class="flex justify-center space-x-4">
                        <i data-feather="message-square" class="text-green-400"></i>
                        <i data-feather="discord" class="text-indigo-400"></i>
                        <i data-feather="message-circle" class="text-blue-400"></i>
                    </div>
                </div>
                
                <div class="bg-gray-900/50 p-8 rounded-xl" data-aos="fade-up" data-aos-delay="300">
                    <div class="bg-gradient-to-br from-pink-500 to-red-600 p-4 rounded-lg w-16 h-16 flex items-center justify-center mb-6 mx-auto">
                        <i data-feather="smile" class="w-8 h-8"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3 text-center">Expressive Communication</h3>
                    <p class="text-gray-400 text-center mb-4">Quick emotes and shouts for fast social interaction without typing.</p>
                    <div class="flex justify-center space-x-4">
                        <i data-feather="thumbs-up" class="text-yellow-400"></i>
                        <i data-feather="heart" class="text-red-400"></i>
                        <i data-feather="alert-circle" class="text-orange-400"></i>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- CTA Section -->
    <section class="py-20">
        <div class="container mx-auto px-6 text-center" data-aos="zoom-in">
            <h2 class="text-3xl md:text-5xl font-bold mb-8">Ready for the <span class="gradient-text">Fragment Wars?</span></h2>
            <p class="text-xl text-gray-300 max-w-2xl mx-auto mb-10">Join millions of players in the ultimate competitive growth arena.</p>
            <button class="bg-gradient-to-r from-blue-500 to-purple-600 px-10 py-5 rounded-full text-xl font-bold hover:opacity-90 transition transform hover:scale-105 shadow-lg shadow-blue-500/30">
                Play Free Now
            </button>
            <p class="text-gray-500 mt-4">No downloads required • Browser-based • Cross-platform</p>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900/80 py-12 border-t border-gray-800">
        <div class="container mx-auto px-6">
            <div class="flex flex-col md:flex-row justify-between items-center">
                <div class="flex items-center space-x-2 mb-6 md:mb-0">
                    <div class="w-8 h-8 bg-blue-500 rounded-full animate-pulse"></div>
                    <span class="text-xl font-bold gradient-text">Fragment Wars</span>
                </div>
                <div class="flex space-x-6">
                    <a href="#" class="text-gray-400 hover:text-white transition">Terms</a>
                    <a href="#" class="text-gray-400 hover:text-white transition">Privacy</a>
                    <a href="#" class="text-gray-400 hover:text-white transition">Support</a>
                    <a href="#" class="text-gray-400 hover:text-white transition">Blog</a>
                </div>
            </div>
            <div class="border-t border-gray-800 mt-8 pt-8 flex flex-col md:flex-row justify-between items-center">
                <p class="text-gray-500 mb-4 md:mb-0">© 2023 Fragment Wars. All rights reserved.</p>
                <div class="flex space-x-4">
                    <a href="#" class="text-gray-400 hover:text-white transition"><i data-feather="twitter"></i></a>
                    <a href="#" class="text-gray-400 hover:text-white transition"><i data-feather="discord"></i></a>
                    <a href="#" class="text-gray-400 hover:text-white transition"><i data-feather="youtube"></i></a>
                    <a href="#" class="text-gray-400 hover:text-white transition"><i data-feather="twitch"></i></a>
                </div>
            </div>
        </div>
    </footer>

    <script>
        // Initialize Vanta.js background
        VANTA.GLOBE({
            el: "#vanta-bg",
            mouseControls: true,
            touchControls: true,
            gyroControls: false,
            minHeight: 200.00,
            minWidth: 200.00,
            scale: 1.00,
            scaleMobile: 1.00,
            color: 0x3b82f6,
            backgroundColor: 0x111827,
            size: 0.8
        });

        // Initialize AOS and Feather Icons
        document.addEventListener('DOMContentLoaded', function() {
            AOS.init({
                duration: 800,
                easing: 'ease-in-out',
                once: true
            });
            feather.replace();
        });
    </script>
</body>
</html>
