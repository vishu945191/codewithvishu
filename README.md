
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CodeCraft Tutorials | Master Coding Skills</title>
    <!-- Load Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Configure Tailwind for Inter font -->
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        'primary': '#4f46e5', // Indigo
                        'secondary': '#10b981', // Emerald
                        'dark-bg': '#1f2937', // Gray-800
                        'dark-card': '#374151', // Gray-700
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                }
            }
        }
    </script>
    <!-- Load Inter font from Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700;800&display=swap" rel="stylesheet">
    <style>
        /* Custom styles for smooth scrolling and minimal reset */
        html {
            scroll-behavior: smooth;
        }
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f3f4f6; /* Light gray background */
        }
        /* Custom gradient for the hero CTA button */
        .cta-gradient {
            background-image: linear-gradient(to right, #4f46e5, #10b981);
        }
    </style>
</head>
<body class="antialiased">

    <!-- Navigation Bar -->
    <nav class="sticky top-0 z-50 bg-white shadow-lg">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center h-16">
                <!-- Logo/Channel Name -->
                <a href="#hero" class="text-xl font-bold text-primary flex items-center">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 mr-2 text-secondary" viewBox="0 0 24 24" fill="currentColor">
                        <path d="M10 20l4-16m4 16l4-16M6 16.5l-2 3.5m4 0l-2-3.5" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                    </svg>
                    CodewithVishu
                </a>
                <!-- Desktop Navigation Links -->
                <div class="hidden sm:ml-6 sm:flex sm:space-x-8">
                    <a href="#topics" class="text-gray-500 hover:text-primary px-3 py-2 rounded-md text-sm font-medium transition duration-150">Topics</a>
                    <a href="#about" class="text-gray-500 hover:text-primary px-3 py-2 rounded-md text-sm font-medium transition duration-150">About</a>
                    <a href="https://youtube.com/@codewithvishu0?si=OR3SZ_TYcyfIg4eW" target="_blank" class="text-gray-500 hover:text-primary px-3 py-2 rounded-md text-sm font-medium transition duration-150">YouTube</a>
                    <a href="#contact" class="text-gray-500 hover:text-primary px-3 py-2 rounded-md text-sm font-medium transition duration-150">Contact</a>
                </div>
                <!-- Mobile Menu Button (Hamburger) -->
                <button id="menu-button" class="sm:hidden p-2 rounded-md text-gray-500 hover:text-primary hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-inset focus:ring-primary" aria-expanded="false">
                    <svg class="h-6 w-6" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
                    </svg>
                </button>
            </div>
        </div>
        
        <!-- Mobile Menu (Hidden by default) -->
        <div id="mobile-menu" class="hidden sm:hidden transition duration-300 ease-in-out">
            <div class="px-2 pt-2 pb-3 space-y-1">
                <a href="#topics" class="text-gray-700 hover:bg-primary hover:text-white block px-3 py-2 rounded-md text-base font-medium">Topics</a>
                <a href="#about" class="text-gray-700 hover:bg-primary hover:text-white block px-3 py-2 rounded-md text-base font-medium">About</a>
                <a href="https://www.youtube.com/@YourChannelHandle" target="_blank" class="text-gray-700 hover:bg-primary hover:text-white block px-3 py-2 rounded-md text-base font-medium">YouTube</a>
                <a href="#contact" class="text-gray-700 hover:bg-primary hover:text-white block px-3 py-2 rounded-md text-base font-medium">Contact</a>
            </div>
        </div>
    </nav>
    <!-- End Navigation Bar -->

    <!-- Hero Section -->
    <header id="hero" class="bg-dark-bg text-white py-16 md:py-24">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <p class="text-secondary text-lg font-semibold mb-2 uppercase tracking-wider">Start Your Coding Journey</p>
            <h1 class="text-4xl sm:text-5xl lg:text-6xl font-extrabold leading-tight mb-6">
                Master Development <span class="text-primary block lg:inline">From Zero to Hero.</span>
            </h1>
            <p class="text-gray-300 text-lg max-w-3xl mx-auto mb-8">
                Welcome to CodewithVishu ! We provide free, comprehensive, and project-based video tutorials on the most in-demand programming languages and frameworks.
            </p>
            <div class="flex flex-col sm:flex-row justify-center space-y-4 sm:space-y-0 sm:space-x-4">
                <a href="https://youtube.com/@codewithvishu0?si=OR3SZ_TYcyfIg4eW" target="_blank" class="cta-gradient text-white font-bold py-3 px-8 rounded-xl shadow-lg hover:shadow-xl transform hover:scale-105 transition duration-300 ease-in-out">
                    Subscribe on YouTube
                </a>
                <a href="#topics" class="bg-white text-primary font-bold py-3 px-8 rounded-xl shadow-lg hover:shadow-xl transform hover:scale-105 transition duration-300 ease-in-out border border-transparent hover:border-primary">
                    Explore Tutorials
                </a>
            </div>
        </div>
    </header>
    <!-- End Hero Section -->

    <!-- Topics/Tutorial Categories Section -->
    <section id="topics" class="py-16 md:py-24 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-3xl sm:text-4xl font-extrabold text-gray-900 text-center mb-4">Core Tutorial Paths</h2>
            <p class="text-xl text-gray-600 text-center mb-12 max-w-3xl mx-auto">Dive into our organized playlists covering essential programming concepts and modern technologies.</p>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                
                <!-- Topic Card 1: Python -->
                <div class="bg-white rounded-xl shadow-2xl p-6 transform hover:scale-[1.02] transition duration-300 border-t-4 border-primary">
                    <div class="flex items-center justify-center h-12 w-12 rounded-full bg-primary/10 text-primary mb-4">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" viewBox="0 0 24 24" fill="currentColor">
                             <path d="M12 2a10 10 0 1 0 0 20 10 10 0 0 0 0-20zM9.5 16h-2c-.82 0-1.5-.68-1.5-1.5v-3c0-.82.68-1.5 1.5-1.5h2c.82 0 1.5.68 1.5 1.5v3c0 .82-.68 1.5-1.5 1.5zm7-2h-2c-.82 0-1.5-.68-1.5-1.5v-3c0-.82.68-1.5 1.5-1.5h2c.82 0 1.5.68 1.5 1.5v3c0 .82-.68 1.5-1.5 1.5z"/>
                        </svg>
                    </div>
                    <h3 class="text-xl font-bold text-gray-900 mb-2">Complete Python Bootcamp</h3>
                    <p class="text-gray-600 mb-4">Start here! Learn the fundamentals of Python, from variables and loops to functions and object-oriented programming.</p>
                    <a href="https://youtube.com/@codewithvishu0?si=OR3SZ_TYcyfIg4eW" target="_blank" class="text-primary hover:text-secondary font-semibold text-sm">View Playlist &rarr;</a>
                </div>

                <!-- Topic Card 2: Web Development -->
                <div class="bg-white rounded-xl shadow-2xl p-6 transform hover:scale-[1.02] transition duration-300 border-t-4 border-secondary">
                    <div class="flex items-center justify-center h-12 w-12 rounded-full bg-secondary/10 text-secondary mb-4">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" viewBox="0 0 24 24" fill="currentColor">
                            <path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-1 15.5V8.5h2v9h-2z"/>
                        </svg>
                    </div>
                    <h3 class="text-xl font-bold text-gray-900 mb-2">Modern Web Design (HTML, CSS, JS)</h3>
                    <p class="text-gray-600 mb-4">Build beautiful, responsive, and interactive websites. Covers HTML5, CSS3 (with Tailwind), and modern JavaScript ES6+.</p>
                    <a href="https://youtube.com/@codewithvishu0?si=OR3SZ_TYcyfIg4eW" target="_blank" class="text-primary hover:text-secondary font-semibold text-sm">View Playlist &rarr;</a>
                </div>

                <!-- Topic Card 3: Data Science -->
                <div class="bg-white rounded-xl shadow-2xl p-6 transform hover:scale-[1.02] transition duration-300 border-t-4 border-primary">
                    <div class="flex items-center justify-center h-12 w-12 rounded-full bg-primary/10 text-primary mb-4">
                         <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" viewBox="0 0 24 24" fill="currentColor">
                            <path d="M13 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V9h-7V2zM12 18H6v-2h6v2zm0-4H6v-2h6v2zm-2-8h6V5h-6v1z"/>
                        </svg>
                    </div>
                    <h3 class="text-xl font-bold text-gray-900 mb-2">Introduction to Machine Learning</h3>
                    <p class="text-gray-600 mb-4">A practical series using Python (Pandas, NumPy, Scikit-learn) to build and understand basic ML models.</p>
                    <a href="https://youtube.com/@codewithvishu0?si=OR3SZ_TYcyfIg4eW" target="_blank" class="text-primary hover:text-secondary font-semibold text-sm">View Playlist &rarr;</a>
                </div>
                
            </div>
            
        </div>
    </section>
    <!-- End Topics Section -->

    <!-- Featured Content/Video Section -->
    <section class="py-16 md:py-24 bg-gray-100">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-3xl sm:text-4xl font-extrabold text-gray-900 text-center mb-12">Featured Tutorial: Build a Full-Stack App</h2>
            
            <div class="bg-white rounded-xl shadow-2xl overflow-hidden p-6 md:p-8 flex flex-col lg:flex-row items-center">
                <!-- Video Placeholder (Replace with actual YouTube embed later) -->
                <div class="w-full lg:w-2/3 lg:mr-8 mb-6 lg:mb-0 aspect-video rounded-lg overflow-hidden shadow-xl border-4 border-primary">
                    <!-- Placeholder using an image URL. Replace this iframe with your actual YouTube embed code! -->
                    <div class="w-full h-full bg-dark-card flex items-center justify-center">
                        <span class="text-white text-lg p-4 text-center">
                            Video Placeholder <br> (Embed your latest YouTube video here!)
                            <a href="https://youtube.com/@codewithvishu0?si=OR3SZ_TYcyfIg4eW" target="_blank" class="text-secondary block mt-2 text-sm underline">Example Link</a>
                        </span>
                    </div>
                    <!-- Example of an actual embed:
                    <iframe width="100%" height="100%" src="YOUR_YOUTUBE_EMBED_URL" title="Featured Video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                    -->
                </div>

                <!-- Video Description -->
                <div class="w-full lg:w-1/3">
                    <h3 class="text-2xl font-bold text-gray-900 mb-3">Project: React & Node.js E-commerce</h3>
                    <p class="text-gray-600 mb-4">In this massive, free tutorial, you will learn how to set up a modern full-stack development environment, connect a database, handle user authentication, and deploy your finished application to the cloud.</p>
                    <ul class="text-gray-700 space-y-2 mb-6 text-sm">
                        <li class="flex items-center"><span class="text-primary mr-2">&check;</span> Backend API with Node & Express</li>
                        <li class="flex items-center"><span class="text-primary mr-2">&check;</span> Frontend using React Hooks & Context</li>
                        <li class="flex items-center"><span class="text-primary mr-2">&check;</span> Database integration (PostgreSQL or MongoDB)</li>
                    </ul>
                    <a href="https://youtube.com/@codewithvishu0?si=OR3SZ_TYcyfIg4eW" target="_blank" class="bg-primary text-white font-bold py-2 px-6 rounded-lg shadow-md hover:bg-indigo-600 transition duration-300">
                        Watch Full Video
                    </a>
                </div>
            </div>
        </div>
    </section>
    <!-- End Featured Content/Video Section -->

    <!-- About Section -->
    <section id="about" class="py-16 md:py-24 bg-dark-bg text-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <h2 class="text-3xl sm:text-4xl font-extrabold text-secondary mb-4">Our Philosophy</h2>
            <p class="text-gray-400 text-xl max-w-4xl mx-auto mb-8">
                Coding shouldn't be expensive or complicated. We focus on teaching by building real-world projects, ensuring you gain practical experience you can use immediately in your career.
            </p>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-8 text-left">
                <!-- Value Prop 1 -->
                <div class="p-6 bg-dark-card rounded-xl shadow-lg border-b-4 border-secondary">
                    <h3 class="text-xl font-bold mb-2">Project-Based Learning</h3>
                    <p class="text-gray-400">Forget dry theory. Every course is centered around creating a functional, portfolio-ready application or solution.</p>
                </div>
                <!-- Value Prop 2 -->
                <div class="p-6 bg-dark-card rounded-xl shadow-lg border-b-4 border-primary">
                    <h3 class="text-xl font-bold mb-2">Modern Technology Stack</h3>
                    <p class="text-gray-400">We teach the frameworks and languages actually being used by companies today, focusing on efficiency and best practices.</p>
                </div>
                <!-- Value Prop 3 -->
                <div class="p-6 bg-dark-card rounded-xl shadow-lg border-b-4 border-secondary">
                    <h3 class="text-xl font-bold mb-2">Community & Support</h3>
                    <p class="text-gray-400">Join our community (mention Discord/GitHub) to ask questions, share your work, and collaborate with fellow learners.</p>
                </div>
            </div>

        </div>
    </section>
    <!-- End About Section -->
    
    <!-- Footer/Contact Section -->
    <footer id="contact" class="bg-gray-900 py-12">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            
            <h3 class="text-2xl font-bold text-white mb-4">Ready to Code?</h3>
            <p class="text-gray-400 mb-6">Join thousands of students and transform your career today. Don't forget to hit that subscribe button!</p>
            
            <a href="https://www.youtube.com/@YourChannelHandle" target="_blank" class="cta-gradient text-white font-bold py-3 px-10 rounded-full shadow-lg hover:shadow-xl transform hover:scale-105 transition duration-300 ease-in-out">
                Subscribe Now!
            </a>
            
            <!-- Social Icons (Placeholder) -->
            <div class="mt-8 space-x-6">
                <a href="https://youtube.com/@codewithvishu0?si=OR3SZ_TYcyfIg4eW" target="_blank" class="text-gray-400 hover:text-red-500 transition duration-150">
                    <svg class="w-8 h-8 inline" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm4.3 11.95l-5 2.5C11.19 16.51 11 16.36 11 16V8c0-.36.19-.51.3-.44l5 2.5c.18.09.18.39 0 .48z"/></svg>
                </a>
                <a href="#" target="_blank" class="text-gray-400 hover:text-white transition duration-150">
                    <svg class="w-8 h-8 inline" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor"><path d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.082-.742.083-.727.083-.727 1.205.084 1.839 1.237 1.839 1.237 1.07 1.838 2.809 1.305 3.495.998.108-.77.418-1.305.762-1.604-2.665-.3-5.466-1.332-5.466-5.93 0-1.31.467-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.046.138 3.003.404 2.292-1.552 3.3-1.23 3.3-1.23.653 1.652.242 2.873.118 3.176.77.84 1.233 1.911 1.233 3.221 0 4.609-2.803 5.624-5.474 5.92.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.796.574C20.565 21.797 24 17.309 24 12 24 5.373 18.627 0 12 0z"/></svg>
                </a>
            </div>

            <p class="text-gray-500 text-sm mt-8">&copy; <span id="year"></span> CodewithVishu. All Rights Reserved. Built for the coding community.</p>
        </div>
    </footer>
    <!-- End Footer Section -->

    <script>
        // Get the current year for the copyright
        document.getElementById('year').textContent = new Date().getFullYear();

        // Mobile Menu Toggle Functionality
        const menuButton = document.getElementById('menu-button');
        const mobileMenu = document.getElementById('mobile-menu');

        menuButton.addEventListener('click', () => {
            const isExpanded = menuButton.getAttribute('aria-expanded') === 'true' || false;
            menuButton.setAttribute('aria-expanded', !isExpanded);
            mobileMenu.classList.toggle('hidden');
        });

        // Close mobile menu when a link is clicked
        const mobileLinks = mobileMenu.querySelectorAll('a');
        mobileLinks.forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.add('hidden');
                menuButton.setAttribute('aria-expanded', 'false');
            });
        });
        
        // This is where you would handle any dynamic content loading if you were using an API
        // For a static site, this is mainly for UI behavior.

        // Smooth scroll for all hash links (e.g., #topics)
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>

</body>
</html>


