# kimi17-bot.github.io
<!DOCTYPE html>
<html lang="eng">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bespoke Boat | International website</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@300;400;500;700&display=swap');
        
        body {
            font-family: 'Noto Sans KR', sans-serif;
            scroll-behavior: smooth;
        }
        
        .model-card {
            transition: all 0.3s ease;
        }
        
        .model-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1), 0 10px 10px -5px rgba(0, 0, 0, 0.04);
        }
        
        .discover-card {
            transition: all 0.3s ease;
        }
        
        .discover-card:hover {
            transform: scale(1.03);
        }
        
        .nav-link {
            position: relative;
        }
        
        .nav-link::after {
            content: '';
            position: absolute;
            width: 0;
            height: 2px;
            bottom: -2px;
            left: 0;
            background-color: #d5001c;
            transition: width 0.3s ease;
        }
        
        .nav-link:hover::after {
            width: 100%;
        }
        
        .hamburger {
            transition: all 0.3s ease;
        }
        
        .hamburger.active {
            transform: rotate(90deg);
        }
    </style>
</head>
<body class="bg-gray-50">
    <!-- Navigation -->
    <nav class="bg-white shadow-md fixed w-full z-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-16">
                <div class="flex items-center">
                    <a href="#" class="flex-shrink-0">
            <img class="h-16 transition-all duration-300 hover:scale-110" src="https://github.com/kimi17-bot/picture_of_boat/raw/70ad332a02918ba1de4ee8e932a4c07448b771a8/navi.ico" 
            alt="Bpat Logo">
                    </a>
                    <div class="hidden md:block ml-10">
                        <div class="flex space-x-8">
                            <a href="#" class="nav-link text-gray-900 hover:text-red-600 px-3 py-2 text-sm font-medium">MODELS</a>
                            <a href="#" class="nav-link text-gray-900 hover:text-red-600 px-3 py-2 text-sm font-medium">OFFERS</a>
                            <a href="#" class="nav-link text-gray-900 hover:text-red-600 px-3 py-2 text-sm font-medium">CONTACTS</a>
                        </div>
                    </div>
                </div>
                <div class="hidden md:flex items-center space-x-4">
                    <a href="#" class="text-gray-900 hover:text-red-600">
                        <i class="fas fa-search"></i>
                    </a>
                    <a href="#" class="text-gray-900 hover:text-red-600">
                        <i class="fas fa-user"></i>
                    </a>
                    <a href="#" class="text-gray-900 hover:text-red-600">
                        <i class="fas fa-shopping-bag"></i>
                    </a>
                </div>
                <div class="md:hidden flex items-center">
                    <button id="mobile-menu-button" class="hamburger inline-flex items-center justify-center p-2 rounded-md text-gray-900 hover:text-red-600 focus:outline-none">
                        <i class="fas fa-bars text-xl"></i>
                    </button>
                </div>
            </div>
        </div>
        
        <!-- Mobile menu -->
        <div id="mobile-menu" class="hidden md:hidden bg-white shadow-lg">
            <div class="px-2 pt-2 pb-3 space-y-1 sm:px-3">
                <a href="#" class="block px-3 py-2 text-base font-medium text-gray-900 hover:text-red-600">Model</a>
                <a href="#" class="block px-3 py-2 text-base font-medium text-gray-900 hover:text-red-600">Service</a>
                <a href="#" class="block px-3 py-2 text-base font-medium text-gray-900 hover:text-red-600">Contacts</a>
                <div class="flex justify-center space-x-4 pt-2">
                    <a href="#" class="text-gray-900 hover:text-red-600">
                        <i class="fas fa-search"></i>
                    </a>
                    <a href="#" class="text-gray-900 hover:text-red-600">
                        <i class="fas fa-user"></i>
                    </a>
                    <a href="#" class="text-gray-900 hover:text-red-600">
                        <i class="fas fa-shopping-bag"></i>
                    </a>
                </div>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="relative h-screen flex items-center justify-center text-white pt-16 overflow-hidden">
        <div class="absolute inset-0 w-full h-full">
            <iframe 
                class="w-full h-full object-cover" 
                src="https://www.youtube.com/embed/81UoJsHUG4Q?autoplay=1&mute=1&loop=1&playlist=81UoJsHUG4Q&controls=0&modestbranding=1&rel=0" 
                frameborder="0" 
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
                allowfullscreen>
            </iframe>
            <div class="absolute inset-0 w-full h-full bg-black bg-opacity-30"></div>
        </div>
        <div class="text-center px-4 relative z-10">
            <h1 class="text-4xl md:text-6xl font-bold mb-6">Bespoke Boat Design.</h1>
            <p class="text-xl md:text-2xl mb-8">Your dream will be come true with BPAT </p>
            <a imag="" class="bg-transparent hover:bg-white hover:text-black text-white font-semibold py-3 px-8 border border-white rounded-full transition duration-300">
                Tell us your story
            </a>
        </div>
    </section>



    <!-- Video Grid Section -->
    <section class="grid grid-cols-1 md:grid-cols-3 gap-0 max-w-7xl mx-auto">
        <!-- 660 -->
        <div class="relative overflow-hidden h-96">
            <div class="w-full h-full">
                <iframe class="w-full h-full object-cover transition-transform duration-500 hover:scale-110"
                    src="https://www.youtube.com/embed/_mLShg3Ca8U?autoplay=1&mute=1&loop=1&playlist=_mLShg3Ca8U&controls=0"
                    frameborder="0"
                    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                    allowfullscreen>
                </iframe>
            </div>
            <div class="absolute inset-0 bg-black bg-opacity-30 flex items-center justify-center opacity-0 hover:opacity-100 transition-opacity duration-300">
                <a href="#" class="text-white text-xl font-bold border-b-2 border-white pb-1">660</a>
            </div>
        </div>
                
        <!-- Racer -->
        <div class="relative overflow-hidden h-96">
            <div class="w-full h-full">
                <iframe class="w-full h-full object-cover transition-transform duration-500 hover:scale-110"
                    src="https://www.youtube.com/embed/BfQaWqCZDMg?autoplay=1&mute=1&loop=1&playlist=BfQaWqCZDMg&controls=0"
                    frameborder="0"
                    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                    allowfullscreen>
                </iframe>
            </div>
            <div class="absolute inset-0 bg-black bg-opacity-30 flex items-center justify-center opacity-0 hover:opacity-100 transition-opacity duration-300">
                <a href="#" class="text-white text-xl font-bold border-b-2 border-white pb-1">Racer</a>
            </div>
        </div>
        
        <!-- Majestic -->
        <div class="relative overflow-hidden h-96">
            <div class="w-full h-full">
                <iframe class="w-full h-full object-cover transition-transform duration-500 hover:scale-110"
                    src="https://www.youtube.com/embed/lxnB2nM83BI?autoplay=1&mute=1&loop=1&playlist=lxnB2nM83BI&controls=0"
                    frameborder="0"
                    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
                    allowfullscreen>
                </iframe>
            </div>
            <div class="absolute inset-0 bg-black bg-opacity-30 flex items-center justify-center opacity-0 hover:opacity-100 transition-opacity duration-300">
                <a href="#" class="text-white text-xl font-bold border-b-2 border-white pb-1">Majestic</a>
            </div>
        </div>
    </section>



    <!-- Image Grid Section: 3-column layout -->
    <section class="py-12 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <h2 class="text-3xl md:text-4xl font-bold text-center mb-10">Models</h2>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-6">


            
            <!-- Majestic Card -->
            <div class="model-card bg-gray-50 rounded-lg overflow-hidden shadow-md">
                <img src="https://github.com/kimi17-bot/picture_of_boat/blob/30db4962b3b4716a96a0a67b2106dd67fde1aaf9/power%20boat.jpg?raw=true" 
                     alt="Majestic" 
                     class="w-full h-48 object-cover">
                <div class="p-6">
                    <h3 class="text-xl font-bold mb-2">Majestic</h3>
                    <p class="text-sm text-gray-500 mb-4">Inboard Diesel</p>
                    <p class="text-gray-700 mb-4">Our very first power boat design.</p>
                    Specification <i class="fas fa-chevron-right ml-1 text-sm"></i>
                    </a>
                </div>
            </div>
            
            <!-- Racer Card -->
            <div class="model-card bg-gray-50 rounded-lg overflow-hidden shadow-md">
                <img src="https://github.com/kimi17-bot/picture_of_boat/blob/30db4962b3b4716a96a0a67b2106dd67fde1aaf9/racing.jpg?raw=true" 
                         alt="Racer" 
                         class="w-full h-48 object-cover">
                <div class="p-6">
                    <h3 class="text-xl font-bold mb-2">Racer</h3>
                    <p class="text-sm text-gray-500 mb-4">Diesel/Ethanol</p>
                    <p class="text-gray-700 mb-4">Super fast racing boat.</p>
                                Specification<i class="fas fa-chevron-right ml-1 text-sm"></i>
                    </a>
                </div>
            </div>

            <!-- 660 Card -->
            <div class="model-card bg-gray-50 rounded-lg overflow-hidden shadow-md">
                <img src="https://github.com/kimi17-bot/picture_of_boat/blob/30db4962b3b4716a96a0a67b2106dd67fde1aaf9/power%20boat1.jpg?raw=true"
                     alt="660" 
                     class="w-full h-48 object-cover">
                <div class="p-6">
                    <h3 class="text-xl font-bold mb-2">660</h3>
                    <p class="text-sm text-gray-500 mb-4">Electric</p>
                    <p class="text-gray-700 mb-4">Compact electric boat.</p>
              Specification<i class="fas fa-chevron-right ml-1 text-sm"></i>
                    </a>
                </div>
            </div>
        </div>
    </section>
            
    <!-- Footer -->              
    <footer class="bg-gray-900 text-gray-200 py-12">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 grid grid-cols-1 md:grid-cols-3 gap-8">
            <div>
                <h3 class="text-lg font-semibold mb-4">Bespoke Boat</h3>
                <p class="text-gray-400 text-sm">Crafting your dreams into reality on water.</p>
                <div class="flex space-x-4 mt-4">
                    <a href="#" class="text-gray-400 hover:text-white"><i class="fab fa-facebook-f"></i></a>
                    <a href="#" class="text-gray-400 hover:text-white"><i class="fab fa-twitter"></i></a>
                    <a href="#" class="text-gray-400 hover:text-white"><i class="fab fa-instagram"></i></a>
                </div>
            </div>
            <div>
                <h3 class="text-lg font-semibold mb-4">Quick Links</h3>
                <ul class="space-y-2">
                    <li><a href="#" class="text-gray-400 hover:text-white">Models</a></li>
                    <li><a href="#" class="text-gray-400 hover:text-white">Offers</a></li>
                    <li><a href="#" class="text-gray-400 hover:text-white">About Us</a></li>
                    <li><a href="#" class="text-gray-400 hover:text-white">Contact</a></li>
                </ul>
            </div>
            <div>
                <h3 class="text-lg font-semibold mb-4">Legal Information</h3>
                <ul class="space-y-2">
                    <li><a href="#" class="text-gray-400 hover:text-white">Terms of Use</a></li>
                    <li><a href="#" class="text-gray-400 hover:text-white">Privacy Policy</a></li>
                    <li><a href="#" class="text-gray-400 hover:text-white">Cookie Policy</a></li>
                    <li><a href="#" class="text-gray-400 hover:text-white">Legal Disclaimer</a></li>
                </ul>
            </div>
        </div>
        <div class="text-center text-gray-500 text-sm mt-8 border-t border-gray-700 pt-6">
            &copy; 2025 Bespoke Boat. All rights reserved.
        </div>
    </footer>
            
    <script>
        // Mobile menu toggle
        const mobileMenuButton = document.getElementById('mobile-menu-button');
        const mobileMenu = document.getElementById('mobile-menu');
        
        mobileMenuButton.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
            mobileMenuButton.classList.toggle('active');
        });
        
        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
        
        // Scroll to top button
        const scrollToTopButton = document.createElement('button');
        scrollToTopButton.innerHTML = '<i class="fas fa-chevron-up"></i>';
        scrollToTopButton.className = 'fixed bottom-8 right-8 bg-red-600 text-white w-12 h-12 rounded-full shadow-lg flex items-center justify-center text-xl hover:bg-red-700 transition duration-300 opacity-0 invisible';
        document.body.appendChild(scrollToTopButton);
        
        window.addEventListener('scroll', () => {
            if (window.pageYOffset > 300) {
                scrollToTopButton.classList.remove('opacity-0', 'invisible');
                scrollToTopButton.classList.add('opacity-100', 'visible');
            } else {
                scrollToTopButton.classList.remove('opacity-100', 'visible');
                scrollToTopButton.classList.add('opacity-0', 'invisible');
            }
        });

        scrollToTopButton.addEventListener('click', () => {
            window.scrollTo({
                top: 0,
                behavior: 'smooth'
            });
        });
    </script>
</body>
</html>
