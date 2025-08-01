
<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Daniel Ha Trung Dung - Professional Portfolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@400;600;700&family=Inter:wght@300;400;500&display=swap" rel="stylesheet">
    <script src="https://unpkg.com/lucide@latest"></script>
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #1A1A1A; /* Slightly darker for more depth */
            color: #E5E5E5;
        }
        h1, h2, h3, h4, h5, h6, .nav-link {
            font-family: 'Cormorant Garamond', serif;
        }
        .text-gold {
            color: #FFD700;
        }
        .border-gold {
            border-color: #FFD700;
        }
        .bg-gold {
            background-color: #FFD700;
        }
        .royal-hr {
            border: 0;
            height: 1px;
            background-image: linear-gradient(to right, rgba(255, 255, 255, 0), rgba(255, 215, 0, 0.5), rgba(255, 255, 255, 0));
        }
        .photo {
            width: 200px;
            height: 200px;
            border: 3px solid #FFD700;
            object-fit: cover;
            border-radius: 9999px;
            box-shadow: 0 0 30px rgba(255, 215, 0, 0.3);
        }
        .timeline-item::before {
            content: '';
            position: absolute;
            width: 15px;
            height: 15px;
            border-radius: 50%;
            background-color: #1A1A1A;
            border: 3px solid #FFD700;
            top: 0;
            left: -8px;
            z-index: 1;
        }
        /* Animation for fade-in on scroll */
        .fade-in-section {
            opacity: 0;
            transform: translateY(20px);
            transition: opacity 0.6s ease-out, transform 0.6s ease-out;
        }
        .fade-in-section.is-visible {
            opacity: 1;
            transform: translateY(0);
        }
    </style>
</head>
<body class="antialiased">

    <!-- Header & Navigation -->
    <nav class="bg-black bg-opacity-50 backdrop-blur-sm sticky top-0 z-50">
        <div class="container mx-auto max-w-6xl px-6 py-3 flex justify-between items-center">
            <a href="#hero" class="text-2xl font-bold text-gold tracking-widest">DANIEL H.</a>
            <div class="hidden md:flex space-x-8">
                <a href="#summary" class="nav-link text-lg text-gray-300 hover:text-gold transition-colors duration-300">Summary</a>
                <a href="#skills" class="nav-link text-lg text-gray-300 hover:text-gold transition-colors duration-300">Skills</a>
                <a href="#experience" class="nav-link text-lg text-gray-300 hover:text-gold transition-colors duration-300">Experience</a>
                <a href="#contact" class="nav-link text-lg text-gray-300 hover:text-gold transition-colors duration-300">Contact</a>
            </div>
             <div class="md:hidden">
                <!-- Mobile menu can be added here if needed -->
            </div>
        </div>
    </nav>

    <!-- Main Content -->
    <main class="container mx-auto max-w-6xl p-6 md:p-12">

        <!-- Hero Section -->
        <section id="hero" class="text-center min-h-[80vh] flex flex-col justify-center items-center py-20 fade-in-section">
            <img src="http://googleusercontent.com/file_content/1" alt="Portrait of Daniel Ha Trung Dung" class="photo mx-auto mb-8">
            <h1 class="text-5xl md:text-7xl font-bold tracking-widest text-gold">MEET DANIEL.</h1>
            <p class="mt-4 text-xl md:text-2xl text-gray-300 max-w-3xl mx-auto" style="font-family: 'Cormorant Garamond', serif;">A storyteller in luxury retail, an e-commerce pioneer, and a leader in customer experience.</p>
        </section>

        <div class="royal-hr my-16"></div>

        <!-- Professional Summary Section -->
        <section id="summary" class="py-16 fade-in-section">
            <h2 class="text-4xl text-center font-semibold mb-10 tracking-widest">PROFESSIONAL SUMMARY</h2>
            <p class="text-center max-w-4xl mx-auto leading-relaxed text-lg text-gray-300">
                A dynamic, result-oriented professional with 10 years of international experience. Combines strong leadership, sales acumen, and customer experience expertise developed through managing successful businesses in Malaysia. From being promoted to Restaurant Manager within three months to launching and scaling an e-commerce venture during a global pandemic, Daniel excels at adapting to new challenges, streamlining operations, and driving growth. 
                <br><br>
                <strong class="text-gold">Since October 2024, Daniel has served as the very first Tom Ford Beauty Advisor in Vietnam under IPP Travel Retail in collaboration with The Estée Lauder Companies (ELC). He delivers premium consultations through storytelling and bespoke service, redefining the customer journey in luxury travel retail.</strong>
            </p>
        </section>

        <div class="royal-hr my-16"></div>

        <!-- Key Skills Section -->
        <section id="skills" class="py-16 fade-in-section">
            <h2 class="text-4xl text-center font-semibold mb-12 tracking-widest">KEY SKILLS</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-10 text-center">
                <div class="bg-gray-800 bg-opacity-40 p-8 rounded-lg border border-gray-700 hover:border-gold transition-all duration-300">
                    <h3 class="text-2xl mb-4 text-gold">Leadership & Management</h3>
                    <ul class="list-none space-y-2 text-gray-300">
                        <li>Staff Supervision & Training</li>
                        <li>Operations Optimization</li>
                        <li>Problem Resolution</li>
                        <li>Workflow Management</li>
                    </ul>
                </div>
                <div class="bg-gray-800 bg-opacity-40 p-8 rounded-lg border border-gray-700 hover:border-gold transition-all duration-300">
                    <h3 class="text-2xl mb-4 text-gold">Sales & Customer Experience</h3>
                    <ul class="list-none space-y-2 text-gray-300">
                        <li>E-commerce & Online Sales</li>
                        <li>Luxury Retail Consultation</li>
                        <li>Relationship Building</li>
                        <li>Bespoke Service & Storytelling</li>
                    </ul>
                </div>
                <div class="bg-gray-800 bg-opacity-40 p-8 rounded-lg border border-gray-700 hover:border-gold transition-all duration-300">
                    <h3 class="text-2xl mb-4 text-gold">Technical Proficiency</h3>
                    <ul class="list-none space-y-2 text-gray-300">
                        <li>Apple Ecosystem (macOS, iOS)</li>
                        <li>Photo Editing Software</li>
                        <li>Microsoft Excel</li>
                        <li>Tech-driven Process Improvement</li>
                    </ul>
                </div>
            </div>
            <div class="text-center mt-12">
                <h3 class="text-2xl mb-3 text-gold">Languages</h3>
                <p class="text-gray-300 text-lg">Fluent in English & Vietnamese; Basic Communication in Malay, Cantonese & Mandarin.</p>
            </div>
        </section>

        <div class="royal-hr my-16"></div>

        <!-- Professional Experience Timeline -->
        <section id="experience" class="py-16 fade-in-section">
            <h2 class="text-4xl text-center font-semibold mb-16 tracking-widest">PROFESSIONAL JOURNEY</h2>
            <div class="relative max-w-2xl mx-auto border-l-2 border-gold border-opacity-50">
                <!-- Timeline Item 1 -->
                <div class="timeline-item mb-16 ml-8">
                    <h3 class="text-2xl job-title text-gold">Tom Ford Beauty Advisor</h3>
                    <p class="company-info">IPP Travel Retail (in collaboration with Estée Lauder Companies) | Hanoi, Vietnam | Oct 2024 - Present</p>
                    <p class="mt-3 text-gray-300">Pioneering the role as Vietnam's first Tom Ford Beauty Advisor in travel retail, crafting bespoke luxury experiences through expert consultation and compelling storytelling.</p>
                </div>
                <!-- Timeline Item 2 -->
                <div class="timeline-item mb-16 ml-8">
                    <h3 class="text-2xl job-title text-gold">Founder / E-commerce Entrepreneur</h3>
                    <p class="company-info">Ở NHÀ CÁI GÌ CŨNG CÓ | Malaysia | 2019 - 2023</p>
                    <p class="mt-3 text-gray-300">Launched and scaled a successful e-commerce business from scratch using only an iPad, serving the Vietnamese community and beyond through targeted marketing and exceptional service.</p>
                </div>
                <!-- Timeline Item 3 -->
                <div class="timeline-item mb-16 ml-8">
                    <h3 class="text-2xl job-title text-gold">Restaurant Manager</h3>
                    <p class="company-info">Local Chinese Restaurant | Bentong, Pahang, Malaysia | 2016 - 2019</p>
                    <p class="mt-3 text-gray-300">Rapidly promoted from Waiter to Manager in 3 months. Directed all daily operations, managed staff, and streamlined workflows to enhance service speed and customer satisfaction.</p>
                </div>
                 <!-- Timeline Item 4 -->
                <div class="timeline-item ml-8">
                    <h3 class="text-2xl job-title text-gold">Kitchen Chief Assistant</h3>
                    <p class="company-info">Special Local Chinese Restaurant | Bentong, Pahang, Malaysia | 2014 - 2016</p>
                    <p class="mt-3 text-gray-300">Coordinated a high-volume kitchen, supporting two head chefs and mastering the foundational principles of professional culinary operations.</p>
                </div>
            </div>
        </section>
        
        <div class="royal-hr my-16"></div>

        <!-- Education & Contact -->
        <section id="contact" class="py-16 text-center fade-in-section">
            <h2 class="text-4xl text-center font-semibold mb-10 tracking-widest">GET IN TOUCH</h2>
            <p class="text-lg text-gray-400 mb-8 max-w-2xl mx-auto">I'm always open to discussing new opportunities and creative collaborations. Feel free to reach out.</p>
            <a href="mailto:hedevilbynight@icloud.com" class="inline-block bg-gold text-black font-bold py-3 px-8 rounded-lg text-lg uppercase tracking-wider hover:bg-yellow-300 transition-colors duration-300">
                Contact Me
            </a>
            <div class="flex justify-center space-x-6 mt-10 text-gray-400">
                <div class="flex items-center">
                    <i data-lucide="phone" class="w-5 h-5 mr-2"></i>
                    <a href="tel:+84777703357" class="hover:text-gold transition-colors duration-300">+84 777 703 357</a>
                </div>
                 <div class="flex items-center">
                    <i data-lucide="map-pin" class="w-5 h-5 mr-2"></i>
                    <span>Hanoi, Vietnam</span>
                </div>
            </div>
        </section>
    </main>

    <footer class="text-center py-6 border-t border-gray-800">
        <p class="text-gray-500">&copy; <span id="year"></span> Daniel Ha Trung Dung. All Rights Reserved.</p>
    </footer>

    <script>
        // Set current year in footer
        document.getElementById('year').textContent = new Date().getFullYear();

        // Initialize Lucide icons
        lucide.createIcons();

        // Fade-in animation on scroll
        const sections = document.querySelectorAll('.fade-in-section');
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('is-visible');
                }
            });
        }, {
            threshold: 0.1
        });

        sections.forEach(section => {
            observer.observe(section);
        });
    </script>
</body>
<Reserved
