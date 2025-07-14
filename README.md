
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kalaivani Ramani | Laravel Developer</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <link href="https://cdn.jsdelivr.net/npm/flowbite@3.1.2/dist/flowbite.min.css" rel="stylesheet" />
  
    <link rel="stylesheet" href="assets/css/style.css">

</head>
<body class="font-sans bg-gray-900 text-gray-100">
    <!-- Navigation -->
    <nav class="fixed w-full bg-gray-800 shadow-md z-50">
        <div class="container mx-auto px-4 sm:px-6 py-3 flex justify-between items-center">
            <a href="#" class="text-xl sm:text-2xl font-bold gradient-text">My Portfolio</a>
            <div class="hidden md:flex space-x-6">
                <a href="#home" class="hover:text-blue-400 transition">Home</a>
                <a href="#about" class="hover:text-blue-400 transition">About</a>
                <a href="#skills" class="hover:text-blue-400 transition">Skills</a>
                <a href="#projects" class="hover:text-blue-400 transition">Projects</a>
                <a href="#contact" class="hover:text-blue-400 transition">Contact</a>
            </div>
            <button class="md:hidden focus:outline-none" id="menu-toggle">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path>
                </svg>
            </button>
        </div>
        <!-- Mobile menu -->
        <div class="md:hidden hidden bg-gray-800 w-full px-6 py-3" id="mobile-menu">
            <div class="flex flex-col space-y-3">
                <a href="#home" class="hover:text-blue-400 transition">Home</a>
                <a href="#about" class="hover:text-blue-400 transition">About</a>
                <a href="#skills" class="hover:text-blue-400 transition">Skills</a>
                <a href="#projects" class="hover:text-blue-400 transition">Projects</a>
                <a href="#contact" class="hover:text-blue-400 transition">Contact</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="pt-28 pb-16 px-4 sm:px-6 bg-gray-900">
        <div class="container mx-auto flex flex-col md:flex-row items-center">
            <div class="md:w-1/2 animate-fadeIn" style="animation-delay: 0.2s;">
                <h1 class="text-3xl sm:text-4xl md:text-5xl font-bold mb-3 sm:mb-4">Hi, I'm <span class="gradient-text">Kalaivani Ramani</span></h1>
                <h2 class="text-xl sm:text-2xl md:text-3xl text-gray-400 mb-4 sm:mb-6">Laravel & Full Stack Developer</h2>
                <p class="text-base sm:text-lg text-gray-300 mb-6 sm:mb-8 leading-relaxed">
                    I build robust, scalable web applications with Laravel. With over 1.5 years of experience,
                    I help businesses transform their ideas into powerful digital solutions.
                </p>
                <div class="flex flex-col sm:flex-row space-y-3 sm:space-y-0 sm:space-x-4">
                    <a href="#contact" class="bg-blue-600 hover:bg-blue-700 text-white px-4 sm:px-6 py-2 sm:py-3 rounded-lg font-medium transition transform hover:-translate-y-1 shadow-lg text-center">
                        Contact Me
                    </a>
                    <a href="assets/resume/Kalaivani_Ramani_Laravel_Developer_Resume_2025.pdf" download="Kalaivani_Ramani_Laravel_Developer_Resume_2025" target="_blank" class="border-2 border-blue-600 text-blue-400 hover:bg-gray-800 px-4 sm:px-6 py-2 sm:py-3 rounded-lg font-medium transition transform hover:-translate-y-1 text-center">
                        Download Resume
                    </a>
                </div>
            </div>
            <div class="md:w-1/2 mt-10 md:mt-0 flex justify-center animate-fadeIn" style="animation-delay: 0.4s;">
                <div class="relative w-56 h-56 sm:w-64 sm:h-64 md:w-72 md:h-72 rounded-full overflow-hidden border-4 border-gray-800 shadow-2xl hover-zoom">
                    <img src="assets/images/profile.png" 
                         alt="Profile Image" 
                         class="w-full h-full object-cover">
                    <div class="absolute inset-0 bg-blue-600 opacity-10"></div>
                </div>
            </div>
        </div>
    </section>

      <!-- About Section -->
      <section id="about" class="py-16 sm:py-20 bg-gray-800 px-4 sm:px-6">
        <div class="container mx-auto">
            <div class="flex flex-col md:flex-row items-center">
                <div class="md:w-1/2 mb-10 md:mb-0 animate-fadeIn" style="animation-delay: 0.2s;">
                    <div class="relative w-full h-full mx-auto rounded-xl overflow-hidden shadow-2xl hover-zoom">
                        <img src="assets/images/about-me.png" 
                             alt="About Me" 
                             class="w-full h-full object-cover">
                        <div class="absolute inset-0 bg-blue-600 opacity-10"></div>
                    </div>
                </div>
                <div class="md:w-1/2 md:pl-8 lg:pl-12 animate-fadeIn" style="animation-delay: 0.4s;">
                    <h2 class="text-2xl sm:text-3xl md:text-4xl font-bold mb-4 sm:mb-6">About <span class="gradient-text">Me</span></h2>
                    <p class="text-sm sm:text-base text-gray-300 mb-4 sm:mb-5 leading-relaxed">
                        Passionate Laravel developer with expertise in building scalable web applications. 
                        I specialize in clean code and efficient solutions.
                    </p>
                    <p class="text-sm sm:text-base text-gray-300 mb-4 sm:mb-5 leading-relaxed">
                        My toolkit includes Laravel, WordPress, and modern frontend technologies.
                    </p>
                    <div class="flex flex-wrap gap-3 sm:gap-4">
                        <div class="bg-gray-700 px-4 sm:px-6 py-3 sm:py-4 rounded-lg shadow-md text-center">
                            <div class="text-xl sm:text-2xl font-bold text-blue-400 mb-1 sm:mb-2">5+</div>
                            <div class="text-xs sm:text-sm text-gray-400">Projects</div>
                        </div>
                        <div class="bg-gray-700 px-4 sm:px-6 py-3 sm:py-4 rounded-lg shadow-md text-center">
                            <div class="text-xl sm:text-2xl font-bold text-blue-400 mb-1 sm:mb-2">1.5</div>
                            <div class="text-xs sm:text-sm text-gray-400">Years Experience</div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="py-16 sm:py-20 bg-gray-800 px-4 sm:px-6">
        <div class="container mx-auto">
            <div class="text-center mb-12 sm:mb-16 animate-fadeIn">
                <h2 class="text-2xl sm:text-3xl md:text-4xl font-bold mb-3 sm:mb-4">My <span class="gradient-text">Skills</span></h2>
                <p class="text-base sm:text-lg text-gray-400 max-w-2xl mx-auto">
                    Technologies I’ve worked with and continue to explore in my projects.
                </p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                <div class="space-y-5 animate-fadeIn" style="animation-delay: 0.2s;">
                    <div class="bg-gray-700 p-5 rounded-xl shadow-md hover-zoom">
                        <div class="flex items-center mb-2">
                            <div class="bg-blue-900 p-2 rounded-lg mr-3">
                                <i class="fab fa-laravel text-blue-400 text-xl"></i>
                            </div>
                            <h3 class="text-lg sm:text-xl font-semibold">Laravel</h3>
                        </div>
                        <p class="text-sm sm:text-base text-gray-300 mb-3">
                            Eloquent ORM, Authentication, Packages.
                        </p>
                    </div>
                    
                    <div class="bg-gray-700 p-5 rounded-xl shadow-md hover-zoom">
                        <div class="flex items-center mb-2">
                            <div class="bg-blue-900 p-2 rounded-lg mr-3">
                                <i class="fas fa-code text-blue-400 text-xl"></i>
                            </div>
                            <h3 class="text-lg sm:text-xl font-semibold">Frontend</h3>
                        </div>
                        <p class="text-sm sm:text-base text-gray-300 mb-3">
                            HTML, CSS, JavaScript, jQuery, Tailwind, Bootstrap.
                        </p>
                    </div>
                    
                    <div class="bg-gray-700 p-5 rounded-xl shadow-md hover-zoom">
                        <div class="flex items-center mb-2">
                            <div class="bg-indigo-900 p-2 rounded-lg mr-3">
                                <i class="fab fa-wordpress text-indigo-400 text-xl"></i>
                            </div>
                            <h3 class="text-lg sm:text-xl font-semibold">WordPress</h3>
                        </div>
                        <p class="text-sm sm:text-base text-gray-300 mb-3">
                            Theme development, Custom plugins, WooCommerce.
                        </p>
                    </div>
                </div>
                
                <div class="space-y-5 animate-fadeIn" style="animation-delay: 0.4s;">
                    <div class="bg-gray-700 p-5 rounded-xl shadow-md hover-zoom">
                        <div class="flex items-center mb-2">
                            <div class="bg-green-900 p-2 rounded-lg mr-3">
                                <i class="fas fa-database text-green-400 text-xl"></i>
                            </div>
                            <h3 class="text-lg sm:text-xl font-semibold">Databases</h3>
                        </div>
                        <p class="text-sm sm:text-base text-gray-300 mb-3">
                            MySQL, PostgreSQL, Query optimization.
                        </p>
                    </div>
                    
                    <div class="bg-gray-700 p-5 rounded-xl shadow-md hover-zoom">
                        <div class="flex items-center mb-2">
                            <div class="bg-yellow-900 p-2 rounded-lg mr-3">
                                <i class="fas fa-tools text-yellow-400 text-xl"></i>
                            </div>
                            <h3 class="text-lg sm:text-xl font-semibold">Tools</h3>
                        </div>
                        <p class="text-sm sm:text-base text-gray-300 mb-3">
                            Git, GitHub, GitLab, Postman, SourceTree, RESTful APIs, Linux.
                        </p>
                    </div>
                    
                    <div class="bg-gray-700 p-5 rounded-xl shadow-md hover-zoom">
                        <div class="flex items-center mb-2">
                            <div class="bg-pink-900 p-2 rounded-lg mr-3">
                                <i class="fas fa-pencil-alt text-pink-400 text-xl"></i>
                            </div>
                            <h3 class="text-lg sm:text-xl font-semibold">CMS</h3>
                        </div>
                        <p class="text-sm sm:text-base text-gray-300 mb-3">
                            WordPress, Twill (Laravel CMS).
                        </p>
                    </div>
                </div>
            </div>
            
            <div class="mt-10 animate-fadeIn" style="animation-delay: 0.6s;">
                <h3 class="text-lg sm:text-xl font-semibold text-center mb-5">Other Proficiencies</h3>
                <div class="flex flex-wrap justify-center gap-3">
                    <div class="bg-gray-700 px-3 py-1.5 rounded-full shadow-sm flex items-center">
                        <i class="fab fa-php text-blue-400 mr-1.5"></i>
                        <span class="text-sm sm:text-base">PHP</span>
                    </div>
                    <div class="bg-gray-700 px-3 py-1.5 rounded-full shadow-sm flex items-center">
                        <i class="fab fa-js text-yellow-400 mr-1.5"></i>
                        <span class="text-sm sm:text-base">JavaScript</span>
                    </div>
                    <div class="bg-gray-700 px-3 py-1.5 rounded-full shadow-sm flex items-center">
                        <i class="fab fa-git-alt text-orange-400 mr-1.5"></i>
                        <span class="text-sm sm:text-base">Git</span>
                    </div>
                    <div class="bg-gray-700 px-3 py-1.5 rounded-full shadow-sm flex items-center">
                        <i class="fab fa-github text-gray-300 mr-1.5"></i>
                        <span class="text-sm sm:text-base">GitHub</span>
                    </div>
                    <div class="bg-gray-700 px-3 py-1.5 rounded-full shadow-sm flex items-center">
                        <i class="fab fa-gitlab text-red-400 mr-1.5"></i>
                        <span class="text-sm sm:text-base">GitLab</span>
                    </div>
                    <div class="bg-gray-700 px-3 py-1.5 rounded-full shadow-sm flex items-center">
                        <i class="fas fa-server text-green-400 mr-1.5"></i>
                        <span class="text-sm sm:text-base">Linux</span>
                    </div>
                    <div class="bg-gray-700 px-3 py-1.5 rounded-full shadow-sm flex items-center">
                        <i class="fas fa-cloud text-blue-400 mr-1.5"></i>
                        <span class="text-sm sm:text-base">RESTful APIs</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="experience" class="py-16 bg-gray-800 px-6">
        <div class="container mx-auto">
            <div class="text-center mb-12">
                <h2 class="text-3xl md:text-4xl font-bold mb-3">Work <span class="gradient-text">Experience</span></h2>
                <p class="text-gray-400 max-w-2xl mx-auto">Key roles and contributions at a glance</p>
            </div>
    
            <div class="max-w-3xl mx-auto space-y-2" x-data="{ openItem: 1 }">
                <div class="bg-gray-700 rounded-lg overflow-hidden" 
                     @click="openItem !== 1 ? openItem = 1 : openItem = null">
                    <div class="flex justify-between items-center p-4 cursor-pointer">
                        <div>
                            <h3 class="font-bold text-lg">4 Thirteen Group</h3>
                            <p class="text-blue-300 text-sm">Web Developer</p>
                        </div>
                        <div class="flex items-center">
                            <span class="text-blue-400 text-sm mr-3">Oct 2023 - Present</span>
                            <svg class="w-5 h-5 text-gray-400 transition-transform duration-200" 
                                 :class="{ 'rotate-180': openItem === 1 }" 
                                 fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"/>
                            </svg>
                        </div>
                    </div>
                    <div class="px-4 pb-4 pt-2 text-sm space-y-2" x-show="openItem === 1" x-collapse>
                        <p class="text-gray-300 flex items-start">
                            <span class="inline-block w-1.5 h-1.5 bg-blue-400 rounded-full mt-1.5 mr-2 flex-shrink-0"></span>
                            Maintained and enhanced Laravel-based projects, implementing new features and bug fixes
                        </p>
                        <p class="text-gray-300 flex items-start">
                            <span class="inline-block w-1.5 h-1.5 bg-blue-400 rounded-full mt-1.5 mr-2 flex-shrink-0"></span>
                            Developed custom WordPress solutions tailored to business needs including custom themes and plugins
                        </p>
                        <p class="text-gray-300 flex items-start">
                            <span class="inline-block w-1.5 h-1.5 bg-blue-400 rounded-full mt-1.5 mr-2 flex-shrink-0"></span>
                            Managed WordPress website maintenance, updates, and performance optimizations
                        </p>
                    </div>
                </div>
    
                <div class="bg-gray-700 rounded-lg overflow-hidden" 
                     @click="openItem !== 2 ? openItem = 2 : openItem = null">
                    <div class="flex justify-between items-center p-4 cursor-pointer">
                        <div>
                            <h3 class="font-bold text-lg">Filmplace</h3>
                            <p class="text-blue-300 text-sm">Software Developer Intern</p>
                        </div>
                        <div class="flex items-center">
                            <span class="text-blue-400 text-sm mr-3">Mar 2023 - Aug 2023</span>
                            <svg class="w-5 h-5 text-gray-400 transition-transform duration-200" 
                                 :class="{ 'rotate-180': openItem === 2 }" 
                                 fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"/>
                            </svg>
                        </div>
                    </div>
                    <div class="px-4 pb-4 pt-2 text-sm space-y-2" x-show="openItem === 2" x-collapse>
                        <p class="text-gray-300 flex items-start">
                            <span class="inline-block w-1.5 h-1.5 bg-blue-400 rounded-full mt-1.5 mr-2 flex-shrink-0"></span>
                            Fixed bugs and improved Laravel application performance
                        </p>
                        <p class="text-gray-300 flex items-start">
                            <span class="inline-block w-1.5 h-1.5 bg-blue-400 rounded-full mt-1.5 mr-2 flex-shrink-0"></span>
                            Conducted SEO analysis and edited WordPress blogs
                        </p>
                        <p class="text-gray-300 flex items-start">
                            <span class="inline-block w-1.5 h-1.5 bg-blue-400 rounded-full mt-1.5 mr-2 flex-shrink-0"></span>
                            Enhanced frontend designs and performed manual testing across multiple devices and browsers
                        </p>
                    </div>
                </div>
                <div class="bg-gray-700 rounded-lg overflow-hidden" 
                     @click="openItem !== 3 ? openItem = 3 : openItem = null">
                    <div class="flex justify-between items-center p-4 cursor-pointer">
                        <div>
                            <h3 class="font-bold text-lg">Mahiran Digital</h3>
                            <p class="text-blue-300 text-sm">Part-Time Web Developer</p>
                        </div>
                        <div class="flex items-center">
                            <span class="text-blue-400 text-sm mr-3">2022 - 2023</span>
                            <svg class="w-5 h-5 text-gray-400 transition-transform duration-200" 
                                 :class="{ 'rotate-180': openItem === 3 }" 
                                 fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"/>
                            </svg>
                        </div>
                    </div>
                    <div class="px-4 pb-4 pt-2 text-sm space-y-2" x-show="openItem === 3" x-collapse>
                        <p class="text-gray-300 flex items-start">
                            <span class="inline-block w-1.5 h-1.5 bg-blue-400 rounded-full mt-1.5 mr-2 flex-shrink-0"></span>
                            Worked on projects as both backend and frontend developer using modern web technologies
                        </p>
                        <p class="text-gray-300 flex items-start">
                            <span class="inline-block w-1.5 h-1.5 bg-blue-400 rounded-full mt-1.5 mr-2 flex-shrink-0"></span>
                            Ensured seamless integration between frontend and backend systems through API development
                        </p>
                        <p class="text-gray-300 flex items-start">
                            <span class="inline-block w-1.5 h-1.5 bg-blue-400 rounded-full mt-1.5 mr-2 flex-shrink-0"></span>
                            Collaborated with designers to implement responsive and accessible user interfaces
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="education" class="py-20 px-6 bg-gray-900">
        <div class="container mx-auto">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold mb-4">My <span class="gradient-text">Education</span></h2>
                <p class="text-lg text-gray-400 max-w-2xl mx-auto">
                    Academic journey in brief
                </p>
            </div>
    
            <div class="grid grid-cols-1 md:grid-cols-2 gap-6 max-w-6xl mx-auto">
                <div class="bg-gray-800 rounded-xl p-6 border-l-4 border-blue-400 hover:translate-y-1 transition-transform">
                    <div class="flex justify-between items-start mb-3">
                        <div>
                            <h3 class="text-xl font-bold">Bachelor of Computer Science</h3>
                            <p class="text-blue-300">University Malaysia Pahang</p>
                        </div>
                        <span class="bg-blue-900 text-blue-300 text-sm px-3 py-1 rounded-full">2019 - 2023</span>
                    </div>
                    <div class="mt-4">
                        <p class="text-gray-300 mb-2">Specialization in Software Development & Web Technologies</p>
                        <div class="bg-gray-700 p-3 rounded-lg">
                            <p class="text-sm text-gray-300 font-medium">Thesis: House Rental Management System for UMP</p>
                            <p class="text-sm text-gray-300 font-medium"><b>Award</b> : Gold medalist in Final Year Project.</p>
                        </div>
                    </div>
                </div>
    
                <div class="bg-gray-800 rounded-xl p-6 border-l-4 border-purple-400 hover:translate-y-1 transition-transform">
                    <div class="flex justify-between items-start mb-3">
                        <div>
                            <h3 class="text-xl font-bold">Science Stream</h3>
                            <p class="text-purple-300">Kelantan Matriculation College</p>
                        </div>
                        <span class="bg-purple-900 text-purple-300 text-sm px-3 py-1 rounded-full">2018 - 2019</span>
                    </div>
                    <div class="mt-4">
                        <p class="text-gray-300">Foundation in Pure Science subjects</p>
                        <p class="text-gray-300">Developed strong analytical, problem-solving, and logical thinking skills.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="py-16 sm:py-20 px-4 sm:px-6 bg-gray-900">
        <div class="container mx-auto">
            <div class="text-center mb-12 sm:mb-16 animate-fadeIn">
                <h2 class="text-2xl sm:text-3xl md:text-4xl font-bold mb-3 sm:mb-4">My <span class="gradient-text">Projects</span></h2>
                <p class="text-base sm:text-lg text-gray-400 max-w-2xl mx-auto">
                    Selected work showcasing my expertise.
                </p>
            </div>

            <div x-data="{
                activeTab: 'laravel',
                projects: {
                    laravel: [
                        { name: 'Modenas', description: 'Maintained and improved an existing Laravel website by debugging issues and optimizing performance for better user experience.', link: 'https://modenas.my/', icon: 'fab fa-laravel' },
                        { name: 'Kawasaki', description: 'Maintained and improved an existing Laravel website by debugging issues, optimizing performance, and revamping selected pages for better user experience.', link: 'https://kawasaki.com.my/', icon: 'fab fa-laravel' },
                        { name: 'House Rental Management System for UMP', description: 'University thesis project for UMP housing management.', link: '#', button: 'Demo', icon: 'fab fa-laravel' }
                    ],
                    wordpress: [
                        { name: 'RedOne Mobile Website', description: 'Maintain and expand a client’s WordPress website by managing updates, fixing issues, and designing new web pages for better functionality and user experience.', link: 'https://www.redonemobile.com.my/en/', icon: 'fab fa-wordpress' },
                        { name: 'Poxy Clinical V2', description: 'Currently developing a clinical web application locally, focusing on robust features and performance optimization. Due to company policy, images cannot be shared before deployment.', link: '#', button: 'Demo', icon: 'fab fa-wordpress' }
                    ],
                    design: [
                        { name: 'Practice 1', description: 'A modern and visually appealing restaurant website featuring a clean layout, intuitive navigation, and engaging visuals to enhance user experience. Designed for optimal responsiveness and accessibility.', link: 'https://tinyurl.com/23osnvsm', button: 'Demo', icon: 'fas fa-home' },
                        { name: 'Practice 2', description: 'A sleek and responsive business website with a flexible layout and smooth animation effects. This project highlights my skills in building structured UI components and enhancing user interaction.', link: 'https://tinyurl.com/24et8xhn', button: 'Demo', icon: 'fas fa-home' },
                        { name: 'Practice 3', description: 'A dynamic real estate website with interactive listings, detailed property views, and smooth animation effects', link: 'https://tinyurl.com/2ddk7qzu', button: 'Demo', icon: 'fas fa-home' }
                    ]
                }
            }" class="animate-fadeIn" style="animation-delay: 0.2s;">
                <!-- Tab Buttons -->
                <div class="max-w-md mx-auto mb-10">
                    <div class="flex flex-wrap justify-center mb-4 space-x-4 p-2 bg-white rounded-lg shadow-md">
                        <button @click="activeTab = 'laravel'" 
                                :class="{ 'bg-blue-600 text-white': activeTab === 'laravel', 'text-blue-400': activeTab !== 'laravel' }" 
                                class="flex-1 py-2 px-4 rounded-md focus:outline-none focus:shadow-outline-blue transition-all duration-300">
                            Laravel
                        </button>
                        <button @click="activeTab = 'wordpress'" 
                                :class="{ 'bg-blue-600 text-white': activeTab === 'wordpress', 'text-blue-400': activeTab !== 'wordpress' }" 
                                class="flex-1 py-2 px-4 rounded-md focus:outline-none focus:shadow-outline-blue transition-all duration-300">
                            WordPress
                        </button>
                        <button @click="activeTab = 'design'" 
                                :class="{ 'bg-blue-600 text-white': activeTab === 'design', 'text-blue-400': activeTab !== 'design' }" 
                                class="flex-1 py-2 px-4 rounded-md focus:outline-none focus:shadow-outline-blue transition-all duration-300">
                            Designs
                        </button>
                    </div>
                </div>

                <!-- Tab Contents -->
                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
                    <template x-for="project in projects[activeTab]" :key="project.name">
                        <div class="tab-content">
                            <div class="bg-gray-800 rounded-xl overflow-hidden shadow-lg hover-zoom">
                                <div class="h-40 sm:h-48 bg-gradient-to-r from-blue-600 to-indigo-700 flex items-center justify-center">
                                    <i :class="project.icon + ' text-white text-5xl sm:text-6xl'"></i>
                                </div>
                                <div class="p-5 sm:p-6">
                                    <h3 class="text-lg sm:text-xl font-bold mb-2" x-text="project.name"></h3>
                                    <p class="text-sm sm:text-base text-gray-300 mb-4" x-text="project.description"></p>
                                    <template x-if="project.name !== 'Poxy Clinical V2'">
                                        <div class="flex space-x-3">
                                            <a :href="project.link" target="_blank" 
                                            class="bg-blue-600 hover:bg-blue-700 text-white px-3 sm:px-4 py-1.5 rounded-lg text-xs sm:text-sm">
                                            <span x-text="project.button || 'Live Site'"></span>
                                            </a>
                                            <template x-if="project.button">
                                                <button @click="openModal(project.name)" class="border border-gray-600 hover:bg-gray-700 px-3 sm:px-4 py-1.5 rounded-lg text-xs sm:text-sm">
                                                    Screenshots
                                                </button>
                                            </template>
                                        </div>
                                    </template>
                                </div>
                            </div>
                        </div>
                    </template>
                </div>
                <p x-show="activeTab === 'design'" class="text-gray-400 text-center mt-6">
                    <b>Disclaimer</b>: This design is a practice project based on a concept I found through Google, created to refine my frontend development skills.
                </p>
            </div>
        </div>

         <!-- Image Modal -->
        <div id="imageModal" class="fixed inset-0 bg-gray-400 bg-opacity-90 z-50 hidden flex items-center justify-center p-4">
            <div class="bg-gray-800 rounded-lg max-w-4xl max-h-screen overflow-auto w-full">
                <div class="flex justify-between items-center p-4 border-b border-gray-700">
                    <h3 class="text-lg sm:text-xl font-bold">Project Screenshots</h3>
                    <button onclick="closeModal()" class="text-gray-400 hover:text-white">
                        <i class="fas fa-times"></i>
                    </button>
                </div>
                <div class="p-4" id="modalContent">
                    <!-- Images injected via JS -->
                </div>
            </div>
        </div>
    </section>
    

    <!-- Contact Section -->
    <section id="contact" class="py-16 sm:py-20 px-4 sm:px-6 bg-gray-900">
        <div class="container mx-auto max-w-2xl">
            <div class="text-center mb-10 sm:mb-12 animate-fadeIn">
                <h2 class="text-2xl sm:text-3xl md:text-4xl font-bold mb-3 sm:mb-4">Let's <span class="gradient-text">Connect</span></h2>
                <p class="text-base sm:text-lg text-gray-400 max-w-lg mx-auto">
                    Have a project in mind? Reach out via WhatsApp!
                </p>
            </div>
            
            <div class="bg-gray-800 rounded-xl shadow-xl overflow-hidden animate-fadeIn" style="animation-delay: 0.2s;">
                <div class="p-8 sm:p-10 text-center">
                    <div class="bg-blue-900 bg-opacity-20 p-6 sm:p-8 rounded-lg mb-6">
                        <i class="fas fa-comment-dots text-blue-400 text-4xl sm:text-5xl mb-4"></i>
                        <h3 class="text-xl sm:text-2xl font-bold mb-2">Chat Directly</h3>
                        <p class="text-sm sm:text-base text-gray-400 mb-4">
                            I'm just one message away on WhatsApp.
                        </p>
                        <a href="https://wa.me/601161601650" target="_blank" 
                           class="inline-block bg-green-600 hover:bg-green-700 text-white font-medium py-2 sm:py-3 px-6 sm:px-8 rounded-lg transition transform hover:-translate-y-1 shadow-lg">
                           <i class="fab fa-whatsapp mr-2"></i> Message Me
                        </a>
                    </div>
                    <div class="flex justify-center space-x-4">
                        <a href="#" class="text-gray-400 hover:text-blue-400 transition">
                            <i class="fab fa-github text-xl sm:text-2xl"></i>
                        </a>
                        <a href="https://www.linkedin.com/in/kalaivaniramani-4a4102250" class="text-gray-400 hover:text-blue-400 transition">
                            <i class="fab fa-linkedin-in text-xl sm:text-2xl"></i>
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-gray-400 py-8 sm:py-10 px-4 sm:px-6">
        <div class="container mx-auto">
            <div class="flex flex-col md:flex-row justify-between items-center">
                <div class="mb-4 md:mb-0 text-center md:text-left">
                    <a href="#" class="text-xl sm:text-2xl font-bold gradient-text">Kalaivani Ramani</a>
                    <p class="mt-1 text-xs sm:text-sm">Laravel & Full Stack Developer</p>
                </div>
                <div class="flex space-x-4">
                    <a href="#" class="hover:text-blue-400 transition text-sm sm:text-base">
                        <i class="fab fa-github mr-1"></i> GitHub
                    </a>
                    <a href="https://www.linkedin.com/in/kalaivaniramani-4a4102250" class="hover:text-blue-400 transition text-sm sm:text-base">
                        <i class="fab fa-linkedin-in mr-1"></i> LinkedIn
                    </a>
                </div>
            </div>
            <div class="border-t border-gray-700 mt-6 pt-6 text-center text-xs sm:text-sm">
                <p>&copy; 2025 Kalaivani Ramani. All rights reserved.</p>
            </div>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/alpinejs@3.x.x/dist/cdn.min.js" defer></script>
    <script src="https://cdn.jsdelivr.net/npm/flowbite@3.1.2/dist/flowbite.min.js"></script>
   
    <script src="assets/js/script.js"></script>

</body>
</html>