<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hafina Official | Premium Dropshipping Services</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        primary: {
                            light: '#4361EE',
                            DEFAULT: '#3A0CA3',
                            dark: '#240046'
                        },
                        secondary: {
                            light: '#4CC9F0',
                            DEFAULT: '#4895EF',
                            dark: '#4361EE'
                        },
                        accent: {
                            light: '#F72585',
                            DEFAULT: '#B5179E',
                            dark: '#7209B7'
                        },
                        neutral: {
                            lightest: '#F8F9FA',
                            light: '#E9ECEF',
                            medium: '#CED4DA',
                            dark: '#6C757D',
                            darkest: '#212529'
                        },
                        dark: {
                            light: '#343A40',
                            DEFAULT: '#212529',
                            dark: '#121416',
                            deeper: '#0A0B0C'
                        }
                    },
                    fontFamily: {
                        sans: ['Poppins', 'sans-serif']
                    }
                }
            }
        }
    </script>
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            scroll-behavior: smooth;
            background-color: #0A0B0C;
            color: #E9ECEF;
        }
        .gradient-bg {
            background: linear-gradient(135deg, #3A0CA3 0%, #4895EF 100%);
        }
        .gradient-text {
            background: linear-gradient(135deg, #4CC9F0 0%, #F72585 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }
        .service-card {
            transition: all 0.3s ease;
            border-radius: 16px;
            overflow: hidden;
            border-top: 4px solid transparent;
            background-color: #121416;
        }
        .service-card:hover {
            transform: translateY(-8px);
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.3), 0 10px 10px -5px rgba(0, 0, 0, 0.2);
            border-top: 4px solid #3A0CA3;
        }
        .step-card {
            transition: all 0.3s ease;
            border-radius: 16px;
            background: #121416;
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.2), 0 2px 4px -1px rgba(0, 0, 0, 0.1);
        }
        .step-card:hover {
            transform: scale(1.03);
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.3), 0 4px 6px -2px rgba(0, 0, 0, 0.2);
        }
        .whatsapp-button {
            position: fixed;
            bottom: 20px;
            right: 20px;
            z-index: 100;
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.3);
        }
        .blob {
            position: absolute;
            border-radius: 50%;
            filter: blur(40px);
            z-index: -1;
            opacity: 0.3;
        }
        .nav-link {
            position: relative;
        }
        .nav-link::after {
            content: '';
            position: absolute;
            width: 0;
            height: 2px;
            bottom: -4px;
            left: 0;
            background-color: #4895EF;
            transition: width 0.3s ease;
        }
        .nav-link:hover::after {
            width: 100%;
        }
        .btn-primary {
            transition: all 0.3s ease;
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.2);
        }
        .btn-primary:hover {
            transform: translateY(-2px);
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.3);
        }
        .input-field {
            transition: all 0.3s ease;
            border: 2px solid #343A40;
            background-color: #121416;
            color: #E9ECEF;
        }
        .input-field:focus {
            border-color: #3A0CA3;
            box-shadow: 0 0 0 3px rgba(58, 12, 163, 0.3);
        }
        .input-field::placeholder {
            color: #6C757D;
        }
        .success-message {
            display: none;
            animation: fadeIn 0.5s ease-in-out;
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(-10px); }
            to { opacity: 1; transform: translateY(0); }
        }
        .image-container {
            overflow: hidden;
            border-radius: 12px;
        }
        .image-container img {
            transition: transform 0.5s ease;
        }
        .image-container:hover img {
            transform: scale(1.05);
        }
        .feature-icon {
            transition: all 0.3s ease;
        }
        .feature-item:hover .feature-icon {
            transform: translateY(-5px);
        }
        
        /* Animation classes */
        @keyframes float {
            0% { transform: translateY(0px); }
            50% { transform: translateY(-10px); }
            100% { transform: translateY(0px); }
        }
        
        .float {
            animation: float 3s ease-in-out infinite;
        }
        
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.05); }
            100% { transform: scale(1); }
        }
        
        .pulse {
            animation: pulse 2s ease-in-out infinite;
        }
        
        @keyframes spin-slow {
            from { transform: rotate(0deg); }
            to { transform: rotate(360deg); }
        }
        
        .spin-slow {
            animation: spin-slow 15s linear infinite;
        }
        
        /* Progress bar animation */
        @keyframes progress {
            0% { width: 0%; }
            100% { width: 100%; }
        }
        
        .animate-progress {
            animation: progress 2s ease-out forwards;
        }
        
        /* Typing animation */
        .typing-container {
            display: inline-block;
            position: relative;
        }
        
        .typing-text {
            overflow: hidden;
            white-space: nowrap;
            border-right: 3px solid #4895EF;
            animation: typing 3.5s steps(40, end), blink-caret 0.75s step-end infinite;
            margin: 0 auto;
        }
        
        @keyframes typing {
            from { width: 0 }
            to { width: 100% }
        }
        
        @keyframes blink-caret {
            from, to { border-color: transparent }
            50% { border-color: #4895EF }
        }
        
        /* Interactive dashboard */
        .dashboard-card {
            transition: all 0.3s ease;
            border-radius: 16px;
            overflow: hidden;
            background-color: #121416;
        }
        
        .dashboard-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.3);
        }
        
        /* Testimonial carousel */
        .testimonial-container {
            overflow: hidden;
            position: relative;
        }
        
        .testimonial-track {
            display: flex;
            transition: transform 0.5s ease;
        }
        
        .testimonial-slide {
            flex: 0 0 100%;
        }
        
        .testimonial-dots {
            display: flex;
            justify-content: center;
            margin-top: 20px;
        }
        
        .testimonial-dot {
            width: 10px;
            height: 10px;
            border-radius: 50%;
            margin: 0 5px;
            background-color: #6C757D;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }
        
        .testimonial-dot.active {
            background-color: #3A0CA3;
        }
        
        /* Animated counter */
        .counter-value {
            transition: all 0.5s ease;
        }
        
        /* Dark theme adjustments */
        .table-row {
            border-bottom: 1px solid #343A40;
        }
        
        .table-row:last-child {
            border-bottom: none;
        }
        
        /* Glow effects */
        .glow {
            box-shadow: 0 0 15px rgba(76, 201, 240, 0.3);
        }
        
        .glow-accent {
            box-shadow: 0 0 15px rgba(247, 37, 133, 0.3);
        }
        
        /* Glass morphism */
        .glass {
            background: rgba(18, 20, 22, 0.7);
            backdrop-filter: blur(10px);
            -webkit-backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.05);
        }
        
        /* Neon borders */
        .neon-border {
            position: relative;
        }
        
        .neon-border::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            border-radius: inherit;
            padding: 2px;
            background: linear-gradient(135deg, #4CC9F0, #F72585);
            -webkit-mask: linear-gradient(#fff 0 0) content-box, linear-gradient(#fff 0 0);
            -webkit-mask-composite: xor;
            mask-composite: exclude;
            pointer-events: none;
        }
        
        /* 3D Button */
        .btn-3d {
            position: relative;
            transform-style: preserve-3d;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        
        .btn-3d::before {
            content: '';
            position: absolute;
            width: 100%;
            height: 100%;
            left: 0;
            bottom: -6px;
            background-color: rgba(0, 0, 0, 0.3);
            border-radius: inherit;
            transform: translateZ(-1px);
        }
        
        .btn-3d:hover {
            transform: translateY(-2px) translateZ(0);
        }
        
        .btn-3d:active {
            transform: translateY(0) translateZ(0);
        }
        
        /* Animated gradient border */
        @keyframes border-animation {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }
        
        .animated-border {
            position: relative;
            border-radius: 16px;
            overflow: hidden;
        }
        
        .animated-border::before {
            content: '';
            position: absolute;
            top: -2px;
            left: -2px;
            right: -2px;
            bottom: -2px;
            background: linear-gradient(45deg, #4CC9F0, #4895EF, #3A0CA3, #7209B7, #F72585, #4CC9F0);
            background-size: 400% 400%;
            animation: border-animation 6s ease infinite;
            border-radius: 16px;
            z-index: -1;
        }
        
        /* Scrollbar styling */
        ::-webkit-scrollbar {
            width: 10px;
        }
        
        ::-webkit-scrollbar-track {
            background: #121416;
        }
        
        ::-webkit-scrollbar-thumb {
            background: #343A40;
            border-radius: 5px;
        }
        
        ::-webkit-scrollbar-thumb:hover {
            background: #4361EE;
        }
        
        /* Particle background */
        .particles {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -1;
            overflow: hidden;
        }
        
        .particle {
            position: absolute;
            border-radius: 50%;
            opacity: 0.3;
            animation: float-particle 15s infinite linear;
        }
        
        @keyframes float-particle {
            0% {
                transform: translateY(0) rotate(0deg);
            }
            100% {
                transform: translateY(-100vh) rotate(360deg);
            }
        }
        
        /* Hover card effect */
        .hover-card {
            transition: all 0.3s ease;
            transform-style: preserve-3d;
            perspective: 1000px;
        }
        
        .hover-card:hover {
            transform: rotateY(5deg) rotateX(5deg);
        }
        
        .hover-card:hover .card-shine {
            opacity: 1;
        }
        
        .card-shine {
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: linear-gradient(135deg, rgba(255,255,255,0) 0%, rgba(255,255,255,0.1) 50%, rgba(255,255,255,0) 100%);
            opacity: 0;
            transition: opacity 0.3s ease;
            pointer-events: none;
        }
        
        /* Modal styles */
        .modal {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.7);
            z-index: 1000;
            overflow: auto;
            animation: fadeIn 0.3s ease-in-out;
        }
        
        .modal-content {
            position: relative;
            background-color: #121416;
            margin: 10% auto;
            padding: 30px;
            border-radius: 16px;
            max-width: 500px;
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.3);
            animation: slideIn 0.3s ease-in-out;
        }
        
        @keyframes slideIn {
            from { transform: translateY(-50px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }
        
        .close-modal {
            position: absolute;
            top: 15px;
            right: 15px;
            font-size: 24px;
            cursor: pointer;
            transition: all 0.3s ease;
        }
        
        .close-modal:hover {
            color: #F72585;
        }
    </style>
</head>
<body>
    <!-- Particle Background -->
    <div class="particles">
        <!-- Particles will be added via JavaScript -->
    </div>

    <!-- Navigation -->
    <nav class="bg-dark-deeper shadow-lg fixed w-full z-50 glass">
        <div class="container mx-auto px-6 py-4 flex justify-between items-center">
            <div class="flex items-center">
                <span class="text-2xl font-bold text-white">
                    <span class="gradient-text">Hafina</span> Official
                </span>
            </div>
            <div class="hidden md:flex space-x-8">
                <a href="#home" class="nav-link text-neutral-light hover:text-secondary transition">Home</a>
                <a href="#about" class="nav-link text-neutral-light hover:text-secondary transition">About</a>
                <a href="#services" class="nav-link text-neutral-light hover:text-secondary transition">Services</a>
                <a href="#how-it-works" class="nav-link text-neutral-light hover:text-secondary transition">How It Works</a>
                <a href="#dashboard" class="nav-link text-neutral-light hover:text-secondary transition">Dashboard</a>
                <a href="#contact" class="nav-link text-neutral-light hover:text-secondary transition">Contact</a>
            </div>
            <div class="md:hidden">
                <button id="menu-toggle" class="focus:outline-none">
                    <svg class="h-6 w-6 text-neutral-light" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path>
                    </svg>
                </button>
            </div>
        </div>
        <!-- Mobile menu -->
        <div id="mobile-menu" class="hidden md:hidden bg-dark-deeper border-t border-dark-light">
            <div class="container mx-auto px-6 py-2 flex flex-col space-y-3">
                <a href="#home" class="text-neutral-light hover:text-secondary transition py-2">Home</a>
                <a href="#about" class="text-neutral-light hover:text-secondary transition py-2">About</a>
                <a href="#services" class="text-neutral-light hover:text-secondary transition py-2">Services</a>
                <a href="#how-it-works" class="text-neutral-light hover:text-secondary transition py-2">How It Works</a>
                <a href="#dashboard" class="text-neutral-light hover:text-secondary transition py-2">Dashboard</a>
                <a href="#contact" class="text-neutral-light hover:text-secondary transition py-2">Contact</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="pt-28 md:pt-32 pb-16 md:pb-24 relative overflow-hidden bg-dark-deeper">
        <div class="blob bg-primary w-96 h-96 top-0 left-0"></div>
        <div class="blob bg-secondary w-96 h-96 bottom-0 right-0"></div>
        
        <div class="container mx-auto px-6 flex flex-col md:flex-row items-center relative z-10">
            <div class="md:w-1/2 text-center md:text-left">
                <div class="typing-container mb-6">
                    <h1 class="typing-text text-4xl md:text-5xl font-bold text-white">
                        Grow Your Business with <span class="gradient-text">Hafina</span>
                    </h1>
                </div>
                <p class="text-lg md:text-xl mb-8 text-neutral-light">We handle marketing and orders so you can focus on growing your business. Our premium dropshipping services connect suppliers with customers seamlessly.</p>
                <div class="flex flex-col sm:flex-row justify-center md:justify-start space-y-4 sm:space-y-0 sm:space-x-4">
                    <a href="mailto:hafina.groupmy@outlook.com" class="btn-primary btn-3d bg-primary text-white hover:bg-primary-dark font-semibold py-3 px-8 rounded-lg transition duration-300 text-center">Get Started</a>
                    <a href="#services" class="btn-primary bg-dark-light border-2 border-secondary text-secondary hover:bg-secondary hover:text-dark font-semibold py-3 px-8 rounded-lg transition duration-300 text-center">Our Services</a>
                </div>
            </div>
            <div class="md:w-1/2 mt-12 md:mt-0">
                <div class="image-container shadow-xl float glow">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 800 500" class="w-full h-auto">
                        <rect width="800" height="500" fill="#0A0B0C"/>
                        
                        <!-- Background elements -->
                        <circle cx="400" cy="250" r="200" fill="#121416" opacity="0.5"/>
                        <path d="M0 350 Q 400 300 800 350 L 800 500 L 0 500 Z" fill="#3A0CA3" opacity="0.2"/>
                        
                        <!-- Grid lines -->
                        <g opacity="0.1">
                            <line x1="0" y1="100" x2="800" y2="100" stroke="#4CC9F0" stroke-width="1"/>
                            <line x1="0" y1="200" x2="800" y2="200" stroke="#4CC9F0" stroke-width="1"/>
                            <line x1="0" y1="300" x2="800" y2="300" stroke="#4CC9F0" stroke-width="1"/>
                            <line x1="0" y1="400" x2="800" y2="400" stroke="#4CC9F0" stroke-width="1"/>
                            
                            <line x1="100" y1="0" x2="100" y2="500" stroke="#4CC9F0" stroke-width="1"/>
                            <line x1="200" y1="0" x2="200" y2="500" stroke="#4CC9F0" stroke-width="1"/>
                            <line x1="300" y1="0" x2="300" y2="500" stroke="#4CC9F0" stroke-width="1"/>
                            <line x1="400" y1="0" x2="400" y2="500" stroke="#4CC9F0" stroke-width="1"/>
                            <line x1="500" y1="0" x2="500" y2="500" stroke="#4CC9F0" stroke-width="1"/>
                            <line x1="600" y1="0" x2="600" y2="500" stroke="#4CC9F0" stroke-width="1"/>
                            <line x1="700" y1="0" x2="700" y2="500" stroke="#4CC9F0" stroke-width="1"/>
                        </g>
                        
                        <!-- Global Supply Chain Network -->
                        <g opacity="0.9">
                            <!-- World Map (simplified) -->
                            <path d="M100,200 C150,180 200,220 250,200 C300,180 350,220 400,200 C450,180 500,220 550,200 C600,180 650,220 700,200" 
                                  stroke="#4895EF" stroke-width="2" fill="none" opacity="0.5"/>
                            
                            <!-- Connection Points -->
                            <circle cx="150" cy="180" r="8" fill="#3A0CA3"/>
                            <circle cx="250" cy="200" r="8" fill="#3A0CA3"/>
                            <circle cx="350" cy="220" r="8" fill="#3A0CA3"/>
                            <circle cx="450" cy="180" r="8" fill="#3A0CA3"/>
                            <circle cx="550" cy="200" r="8" fill="#3A0CA3"/>
                            <circle cx="650" cy="220" r="8" fill="#3A0CA3"/>
                            
                            <!-- Connection Lines -->
                            <line x1="150" y1="180" x2="250" y2="200" stroke="#4CC9F0" stroke-width="2" opacity="0.7"/>
                            <line x1="250" y1="200" x2="350" y2="220" stroke="#4CC9F0" stroke-width="2" opacity="0.7"/>
                            <line x1="350" y1="220" x2="450" y2="180" stroke="#4CC9F0" stroke-width="2" opacity="0.7"/>
                            <line x1="450" y1="180" x2="550" y2="200" stroke="#4CC9F0" stroke-width="2" opacity="0.7"/>
                            <line x1="550" y1="200" x2="650" y2="220" stroke="#4CC9F0" stroke-width="2" opacity="0.7"/>
                            
                            <!-- Data Flow Animation -->
                            <circle cx="200" cy="190" r="4" fill="#F72585" class="pulse">
                                <animate attributeName="cx" from="150" to="250" dur="3s" repeatCount="indefinite"/>
                                <animate attributeName="cy" from="180" to="200" dur="3s" repeatCount="indefinite"/>
                            </circle>
                            
                            <circle cx="400" cy="200" r="4" fill="#F72585" class="pulse">
                                <animate attributeName="cx" from="350" to="450" dur="4s" repeatCount="indefinite"/>
                                <animate attributeName="cy" from="220" to="180" dur="4s" repeatCount="indefinite"/>
                            </circle>
                            
                            <circle cx="600" cy="210" r="4" fill="#F72585" class="pulse">
                                <animate attributeName="cx" from="550" to="650" dur="3.5s" repeatCount="indefinite"/>
                                <animate attributeName="cy" from="200" to="220" dur="3.5s" repeatCount="indefinite"/>
                            </circle>
                        </g>
                        
                        <!-- Warehouse -->
                        <rect x="100" y="280" width="150" height="100" fill="#121416"/>
                        <rect x="100" y="260" width="150" height="20" fill="#0A0B0C"/>
                        <polygon points="100,260 175,220 250,260" fill="#0A0B0C"/>
                        <rect x="120" y="300" width="30" height="40" fill="#4895EF" opacity="0.8"/>
                        <rect x="170" y="300" width="30" height="40" fill="#4895EF" opacity="0.8"/>
                        <rect x="120" y="350" width="30" height="30" fill="#0A0B0C"/>
                        
                        <!-- Shipping Container -->
                        <g transform="translate(300, 330)">
                            <rect width="80" height="50" fill="#3A0CA3"/>
                            <rect y="0" width="80" height="10" fill="#4895EF"/>
                            <rect y="40" width="80" height="10" fill="#4895EF"/>
                            <text x="40" y="30" font-family="Arial" font-size="12" fill="white" text-anchor="middle">HAFINA</text>
                        </g>
                        
                        <!-- Delivery Van -->
                        <g transform="translate(450, 320)" class="van">
                            <!-- Van body -->
                            <rect x="0" y="-30" width="120" height="50" rx="8" fill="#4895EF"/>
                            <rect x="120" y="-20" width="40" height="40" rx="5" fill="#4895EF"/>
                            
                            <!-- Windows -->
                            <rect x="130" y="-15" width="20" height="20" rx="3" fill="#0A0B0C"/>
                            
                            <!-- Wheels -->
                            <circle cx="30" cy="30" r="15" fill="#0A0B0C"/>
                            <circle cx="30" cy="30" r="8" fill="#121416"/>
                            <circle cx="130" cy="30" r="15" fill="#0A0B0C"/>
                            <circle cx="130" cy="30" r="8" fill="#121416"/>
                            
                            <!-- Logo -->
                            <rect x="50" y="-20" width="30" height="20" rx="4" fill="#F72585"/>
                            <text x="65" y="-5" font-family="Arial" font-size="10" fill="white" text-anchor="middle">Hafina</text>
                            
                            <!-- Motion lines -->
                            <line x1="170" y1="0" x2="190" y2="0" stroke="#4CC9F0" stroke-width="2" stroke-dasharray="4,4"/>
                            <line x1="170" y1="10" x2="200" y2="10" stroke="#4CC9F0" stroke-width="2" stroke-dasharray="4,4"/>
                            <line x1="170" y1="-10" x2="180" y2="-10" stroke="#4CC9F0" stroke-width="2" stroke-dasharray="4,4"/>
                        </g>
                        
                        <!-- Customer -->
                        <g transform="translate(650, 300)">
                            <!-- House -->
                            <rect x="0" y="0" width="100" height="80" fill="#121416"/>
                            <polygon points="0,0 50,-30 100,0" fill="#0A0B0C"/>
                            <rect x="40" y="30" width="30" height="50" fill="#0A0B0C"/>
                            <rect x="15" y="15" width="20" height="20" fill="#4895EF" opacity="0.7"/>
                            <rect x="65" y="15" width="20" height="20" fill="#4895EF" opacity="0.7"/>
                            
                            <!-- Package Delivery Animation -->
                            <rect x="-30" y="60" width="20" height="20" fill="#F72585" class="package">
                                <animate attributeName="x" from="-30" to="40" dur="2s" begin="1s" fill="freeze"/>
                            </rect>
                        </g>
                        
                        <!-- Digital Devices -->
                        <g transform="translate(550, 150)">
                            <!-- Laptop -->
                            <rect x="0" y="0" width="60" height="40" rx="3" fill="#0A0B0C" stroke="#4895EF" stroke-width="1"/>
                            <rect x="5" y="5" width="50" height="30" fill="#121416"/>
                            <rect x="20" y="40" width="20" height="5" fill="#0A0B0C"/>
                            
                            <!-- Phone -->
                            <rect x="70" y="10" width="20" height="35" rx="3" fill="#0A0B0C" stroke="#4895EF" stroke-width="1"/>
                            <rect x="72" y="15" width="16" height="25" fill="#121416"/>
                            <circle cx="80" cy="42" r="2" fill="#4895EF"/>
                            
                            <!-- Data Flow -->
                            <path d="M30,20 C40,0 60,40 80,25" stroke="#F72585" stroke-width="2" fill="none" stroke-dasharray="4,4">
                                <animate attributeName="stroke-dashoffset" from="16" to="0" dur="2s" repeatCount="indefinite"/>
                            </path>
                        </g>
                        
                        <!-- Holographic UI Elements -->
                        <g transform="translate(200, 100)">
                            <!-- Circular UI -->
                            <circle cx="0" cy="0" r="30" fill="none" stroke="#4CC9F0" stroke-width="1" opacity="0.7"/>
                            <circle cx="0" cy="0" r="20" fill="none" stroke="#4CC9F0" stroke-width="1" opacity="0.7"/>
                            
                            <!-- Radial Lines -->
                            <line x1="0" y1="-30" x2="0" y2="-40" stroke="#4CC9F0" stroke-width="1" opacity="0.7"/>
                            <line x1="21.21" y1="-21.21" x2="28.28" y2="-28.28" stroke="#4CC9F0" stroke-width="1" opacity="0.7"/>
                            <line x1="30" y1="0" x2="40" y2="0" stroke="#4CC9F0" stroke-width="1" opacity="0.7"/>
                            <line x1="21.21" y1="21.21" x2="28.28" y2="28.28" stroke="#4CC9F0" stroke-width="1" opacity="0.7"/>
                            <line x1="0" y1="30" x2="0" y2="40" stroke="#4CC9F0" stroke-width="1" opacity="0.7"/>
                            <line x1="-21.21" y1="21.21" x2="-28.28" y2="28.28" stroke="#4CC9F0" stroke-width="1" opacity="0.7"/>
                            <line x1="-30" y1="0" x2="-40" y2="0" stroke="#4CC9F0" stroke-width="1" opacity="0.7"/>
                            <line x1="-21.21" y1="-21.21" x2="-28.28" y2="-28.28" stroke="#4CC9F0" stroke-width="1" opacity="0.7"/>
                            
                            <!-- Rotating Element -->
                            <g class="spin-slow">
                                <circle cx="0" cy="-25" r="5" fill="#F72585" opacity="0.7"/>
                                <circle cx="25" cy="0" r="5" fill="#4895EF" opacity="0.7"/>
                                <circle cx="0" cy="25" r="5" fill="#F72585" opacity="0.7"/>
                                <circle cx="-25" cy="0" r="5" fill="#4895EF" opacity="0.7"/>
                            </g>
                        </g>
                        
                        <!-- Text -->
                        <text x="400" y="450" font-family="Arial" font-size="24" font-weight="bold" fill="#E9ECEF" text-anchor="middle">Global Dropshipping Network</text>
                    </svg>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-16 md:py-24 bg-dark relative">
        <div class="blob bg-secondary w-80 h-80 top-1/4 left-0 opacity-20"></div>
        
        <div class="container mx-auto px-6 relative z-10">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-white mb-4">About <span class="gradient-text">Hafina Official</span></h2>
                <div class="w-24 h-1 bg-secondary mx-auto"></div>
            </div>
            <div class="flex flex-col md:flex-row items-center">
                <div class="md:w-1/2 mb-8 md:mb-0">
                    <div class="relative">
                        <div class="absolute inset-0 bg-primary rounded-2xl transform -translate-x-6 translate-y-6 opacity-20"></div>
                        <div class="relative bg-dark-light p-4 rounded-2xl shadow-lg border-2 border-secondary-dark overflow-hidden hover-card">
                            <div class="card-shine"></div>
                            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 600 400" class="w-full h-auto">
                                <rect width="600" height="400" fill="#0A0B0C"/>
                                
                                <!-- Background -->
                                <rect x="50" y="50" width="500" height="300" fill="#121416" stroke="#4895EF" stroke-width="2"/>
                                
                                <!-- Chart Header -->
                                <rect x="50" y="50" width="500" height="60" fill="#3A0CA3" opacity="0.3"/>
                                <text x="100" y="85" font-family="Arial" font-size="18" font-weight="bold" fill="#E9ECEF">Dropshipping Business Growth</text>
                                
                                <!-- Chart Grid -->
                                <line x1="100" y1="150" x2="500" y2="150" stroke="#343A40" stroke-width="1" stroke-dasharray="5,5"/>
                                <line x1="100" y1="200" x2="500" y2="200" stroke="#343A40" stroke-width="1" stroke-dasharray="5,5"/>
                                <line x1="100" y1="250" x2="500" y2="250" stroke="#343A40" stroke-width="1" stroke-dasharray="5,5"/>
                                <line x1="100" y1="300" x2="500" y2="300" stroke="#343A40" stroke-width="1"/>
                                
                                <!-- Y-axis -->
                                <line x1="100" y1="120" x2="100" y2="300" stroke="#CED4DA" stroke-width="2"/>
                                <text x="80" y="150" font-family="Arial" font-size="12" fill="#CED4DA" text-anchor="end">High</text>
                                <text x="80" y="200" font-family="Arial" font-size="12" fill="#CED4DA" text-anchor="end">Medium</text>
                                <text x="80" y="250" font-family="Arial" font-size="12" fill="#CED4DA" text-anchor="end">Low</text>
                                <text x="80" y="300" font-family="Arial" font-size="12" fill="#CED4DA" text-anchor="end">0</text>
                                
                                <!-- X-axis -->
                                <line x1="100" y1="300" x2="500" y2="300" stroke="#CED4DA" stroke-width="2"/>
                                <text x="150" y="320" font-family="Arial" font-size="12" fill="#CED4DA" text-anchor="middle">Q1</text>
                                <text x="250" y="320" font-family="Arial" font-size="12" fill="#CED4DA" text-anchor="middle">Q2</text>
                                <text x="350" y="320" font-family="Arial" font-size="12" fill="#CED4DA" text-anchor="middle">Q3</text>
                                <text x="450" y="320" font-family="Arial" font-size="12" fill="#CED4DA" text-anchor="middle">Q4</text>
                                
                                <!-- Chart Lines -->
                                <polyline points="150,250 250,220 350,180 450,130" fill="none" stroke="#4895EF" stroke-width="3" class="chart-line"/>
                                <circle cx="150" cy="250" r="6" fill="#4895EF" class="chart-point"/>
                                <circle cx="250" cy="220" r="6" fill="#4895EF" class="chart-point"/>
                                <circle cx="350" cy="180" r="6" fill="#4895EF" class="chart-point"/>
                                <circle cx="450" cy="130" r="6" fill="#4895EF" class="chart-point"/>
                                
                                <polyline points="150,270 250,240 350,210 450,170" fill="none" stroke="#F72585" stroke-width="3" class="chart-line"/>
                                <circle cx="150" cy="270" r="6" fill="#F72585" class="chart-point"/>
                                <circle cx="250" cy="240" r="6" fill="#F72585" class="chart-point"/>
                                <circle cx="350" cy="210" r="6" fill="#F72585" class="chart-point"/>
                                <circle cx="450" cy="170" r="6" fill="#F72585" class="chart-point"/>
                                
                                <!-- Legend -->
                                <rect x="350" y="80" width="15" height="15" fill="#4895EF"/>
                                <text x="375" y="93" font-family="Arial" font-size="14" fill="#E9ECEF">Growth</text>
                                
                                <rect x="430" y="80" width="15" height="15" fill="#F72585"/>
                                <text x="455" y="93" font-family="Arial" font-size="14" fill="#E9ECEF">Sales</text>
                                
                                <!-- Data Points Animation -->
                                <circle cx="450" cy="130" r="8" fill="#4895EF" opacity="0.6">
                                    <animate attributeName="r" values="6;10;6" dur="2s" repeatCount="indefinite"/>
                                </circle>
                                <circle cx="450" cy="170" r="8" fill="#F72585" opacity="0.6">
                                    <animate attributeName="r" values="6;10;6" dur="2s" repeatCount="indefinite" begin="1s"/>
                                </circle>
                                
                                <!-- Trend Projection -->
                                <path d="M450,130 Q 475,110 500,100" stroke="#4895EF" stroke-width="2" stroke-dasharray="5,5"/>
                                <path d="M450,170 Q 475,150 500,140" stroke="#F72585" stroke-width="2" stroke-dasharray="5,5"/>
                                
                                <!-- Highlight Area -->
                                <path d="M350,180 L350,300 L450,300 L450,130 Z" fill="#4895EF" opacity="0.1"/>
                                <path d="M350,210 L350,300 L450,300 L450,170 Z" fill="#F72585" opacity="0.1"/>
                            </svg>
                        </div>
                    </div>
                </div>
                <div class="md:w-1/2 md:pl-12">
                    <h3 class="text-2xl font-semibold text-white mb-4">Your Partner in Dropshipping Success</h3>
                    <p class="text-neutral-light mb-6 leading-relaxed">
                        At Hafina Official, we bridge the gap between suppliers and customers through effective dropshipping solutions. We understand the challenges suppliers face in marketing their products and managing orders while trying to grow their business.
                    </p>
                    <p class="text-neutral-light mb-6 leading-relaxed">
                        Our team takes care of marketing your products to the right audience and handles all customer orders efficiently, allowing you to focus on what matters most - developing your product line and scaling your business.
                    </p>
                    <div class="grid grid-cols-2 gap-4">
                        <div class="bg-primary bg-opacity-10 rounded-lg p-4 feature-item neon-border">
                            <div class="flex items-center mb-2">
                                <div class="bg-primary rounded-full p-2 mr-3 feature-icon">
                                    <svg class="w-5 h-5 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 20h5v-2a3 3 0 00-5.356-1.857M17 20H7m10 0v-2c0-.656-.126-1.283-.356-1.857M7 20H2v-2a3 3 0 015.356-1.857M7 20v-2c0-.656.126-1.283.356-1.857m0 0a5.002 5.002 0 019.288 0M15 7a3 3 0 11-6 0 3 3 0 016 0zm6 3a2 2 0 11-4 0 2 2 0 014 0zM7 10a2 2 0 11-4 0 2 2 0 014 0z"></path>
                                    </svg>
                                </div>
                                <span class="text-white font-medium">Experienced Team</span>
                            </div>
                        </div>
                        <div class="bg-secondary bg-opacity-10 rounded-lg p-4 feature-item neon-border">
                            <div class="flex items-center mb-2">
                                <div class="bg-secondary rounded-full p-2 mr-3 feature-icon">
                                    <svg class="w-5 h-5 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M11 3.055A9.001 9.001 0 1020.945 13H11V3.055z"></path>
                                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M20.488 9H15V3.512A9.025 9.025 0 0120.488 9z"></path>
                                    </svg>
                                </div>
                                <span class="text-white font-medium">Targeted Marketing</span>
                            </div>
                        </div>
                        <div class="bg-primary bg-opacity-10 rounded-lg p-4 feature-item neon-border">
                            <div class="flex items-center mb-2">
                                <div class="bg-primary rounded-full p-2 mr-3 feature-icon">
                                    <svg class="w-5 h-5 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 11V7a4 4 0 00-8 0v4M5 9h14l1 12H4L5 9z"></path>
                                    </svg>
                                </div>
                                <span class="text-white font-medium">Order Processing</span>
                            </div>
                        </div>
                        <div class="bg-secondary bg-opacity-10 rounded-lg p-4 feature-item neon-border">
                            <div class="flex items-center mb-2">
                                <div class="bg-secondary rounded-full p-2 mr-3 feature-icon">
                                    <svg class="w-5 h-5 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 7h8m0 0v8m0-8l-8 8-4-4-6 6"></path>
                                    </svg>
                                </div>
                                <span class="text-white font-medium">Business Growth</span>
                            </div>
                        </div>
                    </div>
                    
                    <!-- Progress Bars -->
                    <div class="mt-8 space-y-4">
                        <div>
                            <div class="flex justify-between mb-1">
                                <span class="text-sm font-medium text-white">Customer Satisfaction</span>
                                <span class="text-sm font-medium text-white">99%</span>
                            </div>
                            <div class="w-full bg-dark-light rounded-full h-2.5">
                                <div class="bg-secondary h-2.5 rounded-full animate-progress glow" style="width: 99%"></div>
                            </div>
                        </div>
                        <div>
                            <div class="flex justify-between mb-1">
                                <span class="text-sm font-medium text-white">Order Accuracy</span>
                                <span class="text-sm font-medium text-white">99%</span>
                            </div>
                            <div class="w-full bg-dark-light rounded-full h-2.5">
                                <div class="bg-primary h-2.5 rounded-full animate-progress glow" style="width: 99%"></div>
                            </div>
                        </div>
                        <div>
                            <div class="flex justify-between mb-1">
                                <span class="text-sm font-medium text-white">On-time Delivery</span>
                                <span class="text-sm font-medium text-white">98%</span>
                            </div>
                            <div class="w-full bg-dark-light rounded-full h-2.5">
                                <div class="bg-accent h-2.5 rounded-full animate-progress glow-accent" style="width: 98%"></div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-16 md:py-24 bg-dark-deeper relative">
        <div class="blob bg-primary w-96 h-96 top-0 right-0 opacity-10"></div>
        <div class="blob bg-secondary w-64 h-64 bottom-0 left-1/4 opacity-10"></div>
        
        <div class="container mx-auto px-6 relative z-10">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-white mb-4">Our <span class="gradient-text">Services</span></h2>
                <p class="text-neutral-light max-w-2xl mx-auto">We offer comprehensive dropshipping services to help suppliers focus on growing their business while we handle marketing and orders.</p>
                <div class="w-24 h-1 bg-secondary mx-auto mt-4"></div>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Service 1 -->
                <div class="service-card p-8 animated-border">
                    <div class="bg-primary bg-opacity-20 rounded-full w-16 h-16 flex items-center justify-center mb-6 glow">
                        <svg class="w-8 h-8 text-primary-light" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M11 3.055A9.001 9.001 0 1020.945 13H11V3.055z"></path>
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M20.488 9H15V3.512A9.025 9.025 0 0120.488 9z"></path>
                        </svg>
                    </div>
                    <h3 class="text-xl font-semibold text-white mb-3">Product Marketing</h3>
                    <div class="mb-4 image-container">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 400 250" class="w-full h-auto">
                            <rect width="400" height="250" fill="#0A0B0C"/>
                            
                            <!-- Background elements -->
                            <circle cx="200" cy="125" r="100" fill="#3A0CA3" opacity="0.2"/>
                            
                            <!-- Digital Marketing Concept -->
                            <g transform="translate(200, 125)">
                                <!-- Central Hub -->
                                <circle cx="0" cy="0" r="40" fill="#121416"/>
                                <circle cx="0" cy="0" r="35" fill="#0A0B0C"/>
                                <circle cx="0" cy="0" r="30" fill="#4895EF" opacity="0.3"/>
                                
                                <!-- Marketing Channels -->
                                <!-- Social Media -->
                                <g transform="translate(-80, -60)">
                                    <circle cx="0" cy="0" r="25" fill="#121416"/>
                                    <text x="0" y="5" font-family="Arial" font-size="10" fill="#E9ECEF" text-anchor="middle">Social</text>
                                    <path d="M25,0 L55,30" stroke="#4CC9F0" stroke-width="2" stroke-dasharray="4,4"/>
                                </g>
                                
                                <!-- Email -->
                                <g transform="translate(80, -60)">
                                    <circle cx="0" cy="0" r="25" fill="#121416"/>
                                    <text x="0" y="5" font-family="Arial" font-size="10" fill="#E9ECEF" text-anchor="middle">Email</text>
                                    <path d="M-25,0 L-55,30" stroke="#4CC9F0" stroke-width="2" stroke-dasharray="4,4"/>
                                </g>
                                
                                <!-- SEO -->
                                <g transform="translate(-80, 60)">
                                    <circle cx="0" cy="0" r="25" fill="#121416"/>
                                    <text x="0" y="5" font-family="Arial" font-size="10" fill="#E9ECEF" text-anchor="middle">SEO</text>
                                    <path d="M25,0 L55,-30" stroke="#4CC9F0" stroke-width="2" stroke-dasharray="4,4"/>
                                </g>
                                
                                <!-- PPC -->
                                <g transform="translate(80, 60)">
                                    <circle cx="0" cy="0" r="25" fill="#121416"/>
                                    <text x="0" y="5" font-family="Arial" font-size="10" fill="#E9ECEF" text-anchor="middle">PPC</text>
                                    <path d="M-25,0 L-55,-30" stroke="#4CC9F0" stroke-width="2" stroke-dasharray="4,4"/>
                                </g>
                                
                                <!-- Data Flow Animation -->
                                <circle cx="0" cy="0" r="25" fill="none" stroke="#F72585" stroke-width="2">
                                    <animate attributeName="r" values="25;45;25" dur="3s" repeatCount="indefinite"/>
                                    <animate attributeName="opacity" values="0.7;0.2;0.7" dur="3s" repeatCount="indefinite"/>
                                </circle>
                                
                                <!-- Central Icon -->
                                <text x="0" y="5" font-family="Arial" font-size="12" font-weight="bold" fill="#E9ECEF" text-anchor="middle">HAFINA</text>
                            </g>
                            
                            <!-- Text -->
                            <text x="200" y="220" font-family="Arial" font-size="16" font-weight="bold" fill="#E9ECEF" text-anchor="middle">Targeted Marketing Strategies</text>
                            
                            <!-- Animated Data Points -->
                            <circle cx="120" cy="125" r="3" fill="#4CC9F0">
                                <animate attributeName="cx" values="120;200;120" dur="4s" repeatCount="indefinite"/>
                                <animate attributeName="cy" values="125;125;125" dur="4s" repeatCount="indefinite"/>
                                <animate attributeName="opacity" values="1;0;1" dur="4s" repeatCount="indefinite"/>
                            </circle>
                            
                            <circle cx="280" cy="125" r="3" fill="#4CC9F0">
                                <animate attributeName="cx" values="280;200;280" dur="3s" repeatCount="indefinite"/>
                                <animate attributeName="cy" values="125;125;125" dur="3s" repeatCount="indefinite"/>
                                <animate attributeName="opacity" values="1;0;1" dur="3s" repeatCount="indefinite"/>
                            </circle>
                            
                            <circle cx="200" cy="65" r="3" fill="#4CC9F0">
                                <animate attributeName="cx" values="200;200;200" dur="3.5s" repeatCount="indefinite"/>
                                <animate attributeName="cy" values="65;125;65" dur="3.5s" repeatCount="indefinite"/>
                                <animate attributeName="opacity" values="1;0;1" dur="3.5s" repeatCount="indefinite"/>
                            </circle>
                            
                            <circle cx="200" cy="185" r="3" fill="#4CC9F0">
                                <animate attributeName="cx" values="200;200;200" dur="4.5s" repeatCount="indefinite"/>
                                <animate attributeName="cy" values="185;125;185" dur="4.5s" repeatCount="indefinite"/>
                                <animate attributeName="opacity" values="1;0;1" dur="4.5s" repeatCount="indefinite"/>
                            </circle>
                        </svg>
                    </div>
                    <p class="text-neutral-light mb-4">We create and execute targeted marketing campaigns to promote your products to the right audience, increasing visibility and sales.</p>
                    <ul class="text-neutral-light space-y-3">
                        <li class="flex items-center">
                            <div class="bg-primary bg-opacity-20 rounded-full p-1 mr-3">
                                <svg class="w-4 h-4 text-primary-light" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
                                </svg>
                            </div>
                            Social media marketing
                        </li>
                        <li class="flex items-center">
                            <div class="bg-primary bg-opacity-20 rounded-full p-1 mr-3">
                                <svg class="w-4 h-4 text-primary-light" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
                                </svg>
                            </div>
                            Content creation
                        </li>
                        <li class="flex items-center">
                            <div class="bg-primary bg-opacity-20 rounded-full p-1 mr-3">
                                <svg class="w-4 h-4 text-primary-light" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
                                </svg>
                            </div>
                            Audience targeting
                        </li>
                    </ul>
                </div>
                
                <!-- Service 2 -->
                <div class="service-card p-8 animated-border">
                    <div class="bg-secondary bg-opacity-20 rounded-full w-16 h-16 flex items-center justify-center mb-6 glow">
                        <svg class="w-8 h-8 text-secondary-light" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 11V7a4 4 0 00-8 0v4M5 9h14l1 12H4L5 9z"></path>
                        </svg>
                    </div>
                    <h3 class="text-xl font-semibold text-white mb-3">Order Management</h3>
                    <div class="mb-4 image-container">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 400 250" class="w-full h-auto">
                            <rect width="400" height="250" fill="#0A0B0C"/>
                            
                            <!-- Background -->
                            <rect x="50" y="50" width="300" height="150" rx="10" fill="#121416" stroke="#4895EF" stroke-width="2"/>
                            
                            <!-- Header -->
                            <rect x="50" y="50" width="300" height="40" rx="10" fill="#4895EF" opacity="0.3"/>
                            <text x="80" y="75" font-family="Arial" font-size="16" font-weight="bold" fill="#E9ECEF">Order Management System</text>
                            
                            <!-- Order Items -->
                            <rect x="70" y="110" width="260" height="1" fill="#343A40"/>
                            <rect x="70" y="150" width="260" height="1" fill="#343A40"/>
                            
                            <text x="80" y="100" font-family="Arial" font-size="12" fill="#CED4DA">Order ID</text>
                            <text x="180" y="100" font-family="Arial" font-size="12" fill="#CED4DA">Status</text>
                            <text x="280" y="100" font-family="Arial" font-size="12" fill="#CED4DA">Action</text>
                            
                            <text x="80" y="130" font-family="Arial" font-size="12" fill="#E9ECEF">#12345</text>
                            <rect x="180" y="120" width="60" height="20" rx="10" fill="#3A0CA3" opacity="0.3"/>
                            <text x="210" y="133" font-family="Arial" font-size="10" fill="#4895EF" text-anchor="middle">Processing</text>
                            <circle cx="280" cy="130" r="10" fill="#4CC9F0" opacity="0.3"/>
                            <text x="280" y="134" font-family="Arial" font-size="14" fill="#4CC9F0" text-anchor="middle">✓</text>
                            
                            <text x="80" y="170" font-family="Arial" font-size="12" fill="#E9ECEF">#12346</text>
                            <rect x="180" y="160" width="60" height="20" rx="10" fill="#F72585" opacity="0.3"/>
                            <text x="210" y="173" font-family="Arial" font-size="10" fill="#F72585" text-anchor="middle">Shipped</text>
                            <circle cx="280" cy="170" r="10" fill="#4CC9F0" opacity="0.3"/>
                            <text x="280" y="174" font-family="Arial" font-size="14" fill="#4CC9F0" text-anchor="middle">✓</text>
                            
                            <!-- Order Flow Animation -->
                            <g>
                                <rect x="100" y="200" width="30" height="20" fill="#4895EF" opacity="0.8" rx="4">
                                    <animate attributeName="x" values="100;270;270" dur="4s" repeatCount="indefinite"/>
                                    <animate attributeName="fill" values="#4895EF;#F72585;#4CC9F0" dur="4s" repeatCount="indefinite"/>
                                </rect>
                                <text x="115" y="214" font-family="Arial" font-size="10" fill="#0A0B0C" text-anchor="middle">
                                    <animate attributeName="x" values="115;285;285" dur="4s" repeatCount="indefinite"/>
                                    <animate attributeName="textContent" values="Order;Shipped;Delivered" dur="4s" repeatCount="indefinite"/>
                                </text>
                            </g>
                            
                            <!-- Status Labels -->
                            <text x="100" y="240" font-family="Arial" font-size="10" fill="#CED4DA" text-anchor="middle">Received</text>
                            <text x="200" y="240" font-family="Arial" font-size="10" fill="#CED4DA" text-anchor="middle">Processing</text>
                            <text x="300" y="240" font-family="Arial" font-size="10" fill="#CED4DA" text-anchor="middle">Delivered</text>
                            
                            <!-- Progress Line -->
                            <line x1="100" y1="230" x2="300" y2="230" stroke="#343A40" stroke-width="2"/>
                            <circle cx="100" cy="230" r="5" fill="#4895EF"/>
                            <circle cx="200" cy="230" r="5" fill="#F72585"/>
                            <circle cx="300" cy="230" r="5" fill="#4CC9F0"/>
                            
                            <!-- Animated Progress -->
                            <circle cx="100" cy="230" r="8" fill="#4895EF" opacity="0.3">
                                <animate attributeName="cx" values="100;200;300;100" dur="6s" repeatCount="indefinite"/>
                                <animate attributeName="fill" values="#4895EF;#F72585;#4CC9F0;#4895EF" dur="6s" repeatCount="indefinite"/>
                            </circle>
                        </svg>
                    </div>
                    <p class="text-neutral-light mb-4">We handle the entire order process from receipt to coordination with suppliers, ensuring smooth fulfillment and customer satisfaction.</p>
                    <ul class="text-neutral-light space-y-3">
                        <li class="flex items-center">
                            <div class="bg-secondary bg-opacity-20 rounded-full p-1 mr-3">
                                <svg class="w-4 h-4 text-secondary-light" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
                                </svg>
                            </div>
                            Order processing
                        </li>
                        <li class="flex items-center">
                            <div class="bg-secondary bg-opacity-20 rounded-full p-1 mr-3">
                                <svg class="w-4 h-4 text-secondary-light" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
                                </svg>
                            </div>
                            Supplier coordination
                        </li>
                        <li class="flex items-center">
                            <div class="bg-secondary bg-opacity-20 rounded-full p-1 mr-3">
                                <svg class="w-4 h-4 text-secondary-light" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
                                </svg>
                            </div>
                            Tracking management
                        </li>
                    </ul>
                </div>
                
                <!-- Service 3 -->
                <div class="service-card p-8 animated-border">
                    <div class="bg-accent bg-opacity-20 rounded-full w-16 h-16 flex items-center justify-center mb-6 glow-accent">
                        <svg class="w-8 h-8 text-accent-light" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0V9a2 2 0 012-2h2a2 2 0 012 2v10m-6 0a2 2 0 002 2h2a2 2 0 002-2m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14a2 2 0 01-2 2h-2a2 2 0 01-2-2z"></path>
                        </svg>
                    </div>
                    <h3 class="text-xl font-semibold text-white mb-3">Business Growth Support</h3>
                    <div class="mb-4 image-container">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 400 250" class="w-full h-auto">
                            <rect width="400" height="250" fill="#0A0B0C"/>
                            
                            <!-- Background -->
                            <rect x="50" y="50" width="300" height="150" rx="10" fill="#121416" stroke="#F72585" stroke-width="2"/>
                            
                            <!-- Business Growth Visualization -->
                            <g transform="translate(200, 125)">
                                <!-- Central Business Icon -->
                                <circle cx="0" cy="0" r="30" fill="#0A0B0C" stroke="#F72585" stroke-width="2"/>
                                <text x="0" y="5" font-family="Arial" font-size="12" font-weight="bold" fill="#E9ECEF" text-anchor="middle">GROWTH</text>
                                
                                <!-- Growth Arrows -->
                                <g>
                                    <!-- Up Arrow -->
                                    <path d="M0,-40 L0,-80" stroke="#4895EF" stroke-width="3"/>
                                    <path d="M-10,-70 L0,-80 L10,-70" stroke="#4895EF" stroke-width="3" fill="none"/>
                                    <text x="0" y="-55" font-family="Arial" font-size="10" fill="#E9ECEF" text-anchor="middle">Revenue</text>
                                    
                                    <!-- Right Up Arrow -->
                                    <path d="M40,-20 L80,-40" stroke="#4CC9F0" stroke-width="3"/>
                                    <path d="M70,-45 L80,-40 L75,-30" stroke="#4CC9F0" stroke-width="3" fill="none"/>
                                    <text x="60" y="-25" font-family="Arial" font-size="10" fill="#E9ECEF" text-anchor="middle">Reach</text>
                                    
                                    <!-- Right Arrow -->
                                    <path d="M40,0 L80,0" stroke="#7209B7" stroke-width="3"/>
                                    <path d="M70,-10 L80,0 L70,10" stroke="#7209B7" stroke-width="3" fill="none"/>
                                    <text x="60" y="15" font-family="Arial" font-size="10" fill="#E9ECEF" text-anchor="middle">Products</text>
                                    
                                    <!-- Left Up Arrow -->
                                    <path d="M-40,-20 L-80,-40" stroke="#F72585" stroke-width="3"/>
                                    <path d="M-70,-45 L-80,-40 L-75,-30" stroke="#F72585" stroke-width="3" fill="none"/>
                                    <text x="-60" y="-25" font-family="Arial" font-size="10" fill="#E9ECEF" text-anchor="middle">Efficiency</text>
                                    
                                    <!-- Left Arrow -->
                                    <path d="M-40,0 L-80,0" stroke="#B5179E" stroke-width="3"/>
                                    <path d="M-70,-10 L-80,0 L-70,10" stroke="#B5179E" stroke-width="3" fill="none"/>
                                    <text x="-60" y="15" font-family="Arial" font-size="10" fill="#E9ECEF" text-anchor="middle">Markets</text>
                                </g>
                                
                                <!-- Animated Pulse -->
                                <circle cx="0" cy="0" r="40" fill="none" stroke="#F72585" stroke-width="2">
                                    <animate attributeName="r" values="40;60;40" dur="4s" repeatCount="indefinite"/>
                                    <animate attributeName="opacity" values="0.6;0.1;0.6" dur="4s" repeatCount="indefinite"/>
                                </circle>
                                
                                <!-- Animated Data Points -->
                                <circle cx="0" cy="-60" r="3" fill="#4895EF">
                                    <animate attributeName="cy" values="-40;-60;-40" dur="3s" repeatCount="indefinite"/>
                                    <animate attributeName="opacity" values="1;0.5;1" dur="3s" repeatCount="indefinite"/>
                                </circle>
                                
                                <circle cx="60" cy="-30" r="3" fill="#4CC9F0">
                                    <animate attributeName="cx" values="40;60;40" dur="4s" repeatCount="indefinite"/>
                                    <animate attributeName="cy" values="-20;-30;-20" dur="4s" repeatCount="indefinite"/>
                                    <animate attributeName="opacity" values="1;0.5;1" dur="4s" repeatCount="indefinite"/>
                                </circle>
                                
                                <circle cx="60" cy="0" r="3" fill="#7209B7">
                                    <animate attributeName="cx" values="40;60;40" dur="3.5s" repeatCount="indefinite"/>
                                    <animate attributeName="opacity" values="1;0.5;1" dur="3.5s" repeatCount="indefinite"/>
                                </circle>
                                
                                <circle cx="-60" cy="-30" r="3" fill="#F72585">
                                    <animate attributeName="cx" values="-40;-60;-40" dur="4.5s" repeatCount="indefinite"/>
                                    <animate attributeName="cy" values="-20;-30;-20" dur="4.5s" repeatCount="indefinite"/>
                                    <animate attributeName="opacity" values="1;0.5;1" dur="4.5s" repeatCount="indefinite"/>
                                </circle>
                                
                                <circle cx="-60" cy="0" r="3" fill="#B5179E">
                                    <animate attributeName="cx" values="-40;-60;-40" dur="3.2s" repeatCount="indefinite"/>
                                    <animate attributeName="opacity" values="1;0.5;1" dur="3.2s" repeatCount="indefinite"/>
                                </circle>
                            </g>
                            
                            <!-- Text -->
                            <text x="200" y="220" font-family="Arial" font-size="16" font-weight="bold" fill="#E9ECEF" text-anchor="middle">Business Growth Analytics</text>
                        </svg>
                    </div>
                    <p class="text-neutral-light mb-4">We provide insights and strategies to help suppliers grow their business while we handle the operational aspects of dropshipping.</p>
                    <ul class="text-neutral-light space-y-3">
                        <li class="flex items-center">
                            <div class="bg-accent bg-opacity-20 rounded-full p-1 mr-3">
                                <svg class="w-4 h-4 text-accent-light" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
                                </svg>
                            </div>
                            Performance analytics
                        </li>
                        <li class="flex items-center">
                            <div class="bg-accent bg-opacity-20 rounded-full p-1 mr-3">
                                <svg class="w-4 h-4 text-accent-light" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
                                </svg>
                            </div>
                            Product recommendations
                        </li>
                        <li class="flex items-center">
                            <div class="bg-accent bg-opacity-20 rounded-full p-1 mr-3">
                                <svg class="w-4 h-4 text-accent-light" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
                                </svg>
                            </div>
                            Market trend insights
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </section>
    
    <!-- How It Works Section -->
    <section id="how-it-works" class="py-16 md:py-24 bg-dark relative">
        <div class="blob bg-primary w-80 h-80 top-1/4 right-0 opacity-20"></div>
        
        <div class="container mx-auto px-6 relative z-10">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-white mb-4">How It <span class="gradient-text">Works</span></h2>
                <p class="text-neutral-light max-w-2xl mx-auto">Our simple process makes it easy for suppliers to start working with us and grow their business.</p>
                <div class="w-24 h-1 bg-secondary mx-auto mt-4"></div>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-4 gap-8">
                <!-- Step 1 -->
                <div class="step-card p-6 relative hover-card">
                    <div class="card-shine"></div>
                    <div class="absolute -top-5 -left-5 bg-primary rounded-full w-10 h-10 flex items-center justify-center text-white font-bold text-lg shadow-md glow">1</div>
                    <div class="bg-primary bg-opacity-10 rounded-full w-16 h-16 flex items-center justify-center mb-4 mx-auto">
                        <svg class="w-8 h-8 text-primary-light" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 12h.01M12 12h.01M16 12h.01M21 12c0 4.418-4.03 8-9 8a9.863 9.863 0 01-4.255-.949L3 20l1.395-3.72C3.512 15.042 3 13.574 3 12c0-4.418 4.03-8 9-8s9 3.582 9 8z"></path>
                        </svg>
                    </div>
                    <h3 class="text-xl font-semibold text-white mb-3 text-center">Initial Consultation</h3>
                    <p class="text-neutral-light text-center">We discuss your products, target market, and business goals to understand your needs.</p>
                </div>
                
                <!-- Step 2 -->
                <div class="step-card p-6 relative hover-card">
                    <div class="card-shine"></div>
                    <div class="absolute -top-5 -left-5 bg-secondary rounded-full w-10 h-10 flex items-center justify-center text-white font-bold text-lg shadow-md glow">2</div>
                    <div class="bg-secondary bg-opacity-10 rounded-full w-16 h-16 flex items-center justify-center mb-4 mx-auto">
                        <svg class="w-8 h-8 text-secondary-light" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5H7a2 2 0 00-2 2v12a2 2 0 002 2h10a2 2 0 002-2V7a2 2 0 00-2-2h-2M9 5a2 2 0 002 2h2a2 2 0 002-2M9 5a2 2 0 012-2h2a2 2 0 012 2m-3 7h3m-3 4h3m-6-4h.01M9 16h.01"></path>
                        </svg>
                    </div>
                    <h3 class="text-xl font-semibold text-white mb-3 text-center">Strategy Development</h3>
                    <p class="text-neutral-light text-center">We create a customized marketing and order management strategy for your products.</p>
                </div>
                
                <!-- Step 3 -->
                <div class="step-card p-6 relative hover-card">
                    <div class="card-shine"></div>
                    <div class="absolute -top-5 -left-5 bg-accent rounded-full w-10 h-10 flex items-center justify-center text-white font-bold text-lg shadow-md glow-accent">3</div>
                    <div class="bg-accent bg-opacity-10 rounded-full w-16 h-16 flex items-center justify-center mb-4 mx-auto">
                        <svg class="w-8 h-8 text-accent-light" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7 16a4 4 0 01-.88-7.903A5 5 0 1115.9 6L16 6a5 5 0 011 9.9M15 13l-3-3m0 0l-3 3m3-3v12"></path>
                        </svg>
                    </div>
                    <h3 class="text-xl font-semibold text-white mb-3 text-center">Implementation</h3>
                    <p class="text-neutral-light text-center">We set up marketing campaigns and order processing systems tailored to your business.</p>
                </div>
                
                <!-- Step 4 -->
                <div class="step-card p-6 relative hover-card">
                    <div class="card-shine"></div>
                    <div class="absolute -top-5 -left-5 bg-primary rounded-full w-10 h-10 flex items-center justify-center text-white font-bold text-lg shadow-md glow">4</div>
                    <div class="bg-primary bg-opacity-10 rounded-full w-16 h-16 flex items-center justify-center mb-4 mx-auto">
                        <svg class="w-8 h-8 text-primary-light" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0V9a2 2 0 012-2h2a2 2 0 012 2v10m-6 0a2 2 0 002 2h2a2 2 0 002-2m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14a2 2 0 01-2 2h-2a2 2 0 01-2-2z"></path>
                        </svg>
                    </div>
                    <h3 class="text-xl font-semibold text-white mb-3 text-center">Growth & Optimization</h3>
                    <p class="text-neutral-light text-center">We continuously monitor performance and optimize strategies to maximize your business growth.</p>
                </div>
            </div>
            
            <!-- Process Flow -->
            <div class="mt-16 relative">
                <div class="hidden md:block absolute top-1/2 left-0 right-0 h-1 bg-dark-light -translate-y-1/2 z-0"></div>
                <div class="flex flex-col md:flex-row justify-between items-center relative z-10">
                    <div class="bg-dark rounded-full w-16 h-16 flex items-center justify-center border-4 border-secondary mb-4 md:mb-0 glow">
                        <svg class="w-8 h-8 text-secondary" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 7V3m8 4V3m-9 8h10M5 21h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z"></path>
                        </svg>
                    </div>
                    <div class="hidden md:block w-full h-1 bg-secondary"></div>
                    <div class="bg-dark rounded-full w-16 h-16 flex items-center justify-center border-4 border-secondary mb-4 md:mb-0 glow">
                        <svg class="w-8 h-8 text-secondary" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M11 5.882V19.24a1.76 1.76 0 01-3.417.592l-2.147-6.15M18 13a3 3 0 100-6M5.436 13.683A4.001 4.001 0 017 6h1.832c4.1 0 7.625-1.234 9.168-3v14c-1.543-1.766-5.067-3-9.168-3H7a3.988 3.988 0 01-1.564-.317z"></path>
                        </svg>
                    </div>
                    <div class="hidden md:block w-full h-1 bg-secondary"></div>
                    <div class="bg-dark rounded-full w-16 h-16 flex items-center justify-center border-4 border-secondary mb-4 md:mb-0 glow">
                        <svg class="w-8 h-8 text-secondary" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 11V7a4 4 0 00-8 0v4M5 9h14l1 12H4L5 9z"></path>
                        </svg>
                    </div>
                    <div class="hidden md:block w-full h-1 bg-secondary"></div>
                    <div class="bg-dark rounded-full w-16 h-16 flex items-center justify-center border-4 border-secondary glow">
                        <svg class="w-8 h-8 text-secondary" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8c-1.657 0-3 .895-3 2s1.343 2 3 2 3 .895 3 2-1.343 2-3 2m0-8c1.11 0 2.08.402 2.599 1M12 8V7m0 1v8m0 0v1m0-1c-1.11 0-2.08-.402-2.599-1M21 12a9 9 0 11-18 0 9 9 0 0118 0z"></path>
                        </svg>
                    </div>
                </div>
                <div class="flex flex-col md:flex-row justify-between mt-4 text-center">
                    <div class="md:w-1/4 mb-4 md:mb-0">
                        <h4 class="font-semibold text-white">Onboarding</h4>
                    </div>
                    <div class="md:w-1/4 mb-4 md:mb-0">
                        <h4 class="font-semibold text-white">Marketing</h4>
                    </div>
                    <div class="md:w-1/4 mb-4 md:mb-0">
                        <h4 class="font-semibold text-white">Order Processing</h4>
                    </div>
                    <div class="md:w-1/4">
                        <h4 class="font-semibold text-white">Revenue Growth</h4>
                    </div>
                </div>
            </div>
            
            <!-- Dropshipping Process Visualization -->
            <div class="mt-20">
                <h3 class="text-2xl font-semibold text-white text-center mb-8">The Dropshipping <span class="gradient-text">Process</span></h3>
                <div class="relative">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1000 300" class="w-full h-auto">
                        <rect width="1000" height="300" fill="#0A0B0C"/>
                        
                        <!-- Grid lines -->
                        <g opacity="0.05">
                            <line x1="0" y1="50" x2="1000" y2="50" stroke="#4CC9F0" stroke-width="1"/>
                            <line x1="0" y1="100" x2="1000" y2="100" stroke="#4CC9F0" stroke-width="1"/>
                            <line x1="0" y1="150" x2="1000" y2="150" stroke="#4CC9F0" stroke-width="1"/>
                            <line x1="0" y1="200" x2="1000" y2="200" stroke="#4CC9F0" stroke-width="1"/>
                            <line x1="0" y1="250" x2="1000" y2="250" stroke="#4CC9F0" stroke-width="1"/>
                            
                            <line x1="100" y1="0" x2="100" y2="300" stroke="#4CC9F0" stroke-width="1"/>
                            <line x1="200" y1="0" x2="200" y2="300" stroke="#4CC9F0" stroke-width="1"/>
                            <line x1="300" y1="0" x2="300" y2="300" stroke="#4CC9F0" stroke-width="1"/>
                            <line x1="400" y1="0" x2="400" y2="300" stroke="#4CC9F0" stroke-width="1"/>
                            <line x1="500" y1="0" x2="500" y2="300" stroke="#4CC9F0" stroke-width="1"/>
                            <line x1="600" y1="0" x2="600" y2="300" stroke="#4CC9F0" stroke-width="1"/>
                            <line x1="700" y1="0" x2="700" y2="300" stroke="#4CC9F0" stroke-width="1"/>
                            <line x1="800" y1="0" x2="800" y2="300" stroke="#4CC9F0" stroke-width="1"/>
                            <line x1="900" y1="0" x2="900" y2="300" stroke="#4CC9F0" stroke-width="1"/>
                        </g>
                        
                        <!-- Process Flow Background -->
                        <path d="M100,150 C250,50 350,250 500,150 C650,50 750,250 900,150" stroke="#121416" stroke-width="10" fill="none"/>
                        
                        <!-- Customer -->
                        <g transform="translate(100, 150)">
                            <circle cx="0" cy="0" r="40" fill="#121416"/>
                            <circle cx="0" cy="0" r="35" fill="#0A0B0C"/>
                            <circle cx="0" cy="-15" r="12" fill="#4895EF"/>
                            <circle cx="-12" cy="10" r="12" fill="#4895EF"/>
                            <circle cx="12" cy="10" r="12" fill="#4895EF"/>
                            <text x="0" y="60" font-family="Arial" font-size="14" fill="#E9ECEF" text-anchor="middle">Customer</text>
                        </g>
                        
                        <!-- Hafina (Your Store) -->
                        <g transform="translate(300, 150)">
                            <circle cx="0" cy="0" r="50" fill="#121416"/>
                            <circle cx="0" cy="0" r="45" fill="#0A0B0C"/>
                            <text x="0" y="0" font-family="Arial" font-size="16" font-weight="bold" fill="#4895EF" text-anchor="middle">HAFINA</text>
                            <text x="0" y="20" font-family="Arial" font-size="12" fill="#E9ECEF" text-anchor="middle">Your Store</text>
                            <text x="0" y="70" font-family="Arial" font-size="14" fill="#E9ECEF" text-anchor="middle">Retailer</text>
                            
                            <!-- Animated Glow -->
                            <circle cx="0" cy="0" r="55" fill="none" stroke="#4895EF" stroke-width="2" opacity="0.3">
                                <animate attributeName="r" values="55;65;55" dur="3s" repeatCount="indefinite"/>
                                <animate attributeName="opacity" values="0.3;0.1;0.3" dur="3s" repeatCount="indefinite"/>
                            </circle>
                        </g>
                        
                        <!-- Supplier -->
                        <g transform="translate(700, 150)">
                            <rect x="-40" y="-40" width="80" height="80" fill="#121416"/>
                            <rect x="-35" y="-35" width="70" height="70" fill="#0A0B0C"/>
                            <rect x="-25" y="-25" width="50" height="50" fill="#F72585" opacity="0.3"/>
                            <text x="0" y="5" font-family="Arial" font-size="14" font-weight="bold" fill="#E9ECEF" text-anchor="middle">SUPPLIER</text>
                            <text x="0" y="60" font-family="Arial" font-size="14" fill="#E9ECEF" text-anchor="middle">Manufacturer</text>
                            
                            <!-- Animated Glow -->
                            <rect x="-50" y="-50" width="100" height="100" fill="none" stroke="#F72585" stroke-width="2" opacity="0.3">
                                <animate attributeName="x" values="-50;-55;-50" dur="3s" repeatCount="indefinite"/>
                                <animate attributeName="y" values="-50;-55;-50" dur="3s" repeatCount="indefinite"/>
                                <animate attributeName="width" values="100;110;100" dur="3s" repeatCount="indefinite"/>
                                <animate attributeName="height" values="100;110;100" dur="3s" repeatCount="indefinite"/>
                                <animate attributeName="opacity" values="0.3;0.1;0.3" dur="3s" repeatCount="indefinite"/>
                            </rect>
                        </g>
                        
                        <!-- Customer -->
                        <g transform="translate(900, 150)">
                            <circle cx="0" cy="0" r="40" fill="#121416"/>
                            <circle cx="0" cy="0" r="35" fill="#0A0B0C"/>
                            <circle cx="0" cy="-15" r="12" fill="#4895EF"/>
                            <circle cx="-12" cy="10" r="12" fill="#4895EF"/>
                            <circle cx="12" cy="10" r="12" fill="#4895EF"/>
                            <text x="0" y="60" font-family="Arial" font-size="14" fill="#E9ECEF" text-anchor="middle">Customer</text>
                        </g>
                        
                        <!-- Process Arrows -->
                        <!-- Order Flow -->
                        <g>
                            <path d="M150,150 L250,150" stroke="#4895EF" stroke-width="3" marker-end="url(#arrowhead)"/>
                            <text x="200" y="140" font-family="Arial" font-size="12" fill="#E9ECEF" text-anchor="middle">1. Places Order</text>
                            
                            <path d="M350,150 L650,150" stroke="#4895EF" stroke-width="3" marker-end="url(#arrowhead)"/>
                            <text x="500" y="140" font-family="Arial" font-size="12" fill="#E9ECEF" text-anchor="middle">2. Forwards Order</text>
                            
                            <path d="M750,150 L850,150" stroke="#F72585" stroke-width="3" marker-end="url(#arrowhead)"/>
                            <text x="800" y="140" font-family="Arial" font-size="12" fill="#E9ECEF" text-anchor="middle">3. Ships Product</text>
                            
                            <!-- Payment Flow -->
                            <path d="M150,170 L250,170" stroke="#4CC9F0" stroke-width="3" stroke-dasharray="5,5"/>
                            <text x="200" y="190" font-family="Arial" font-size="12" fill="#E9ECEF" text-anchor="middle">Payment</text>
                            
                            <path d="M350,170 L650,170" stroke="#4CC9F0" stroke-width="3" stroke-dasharray="5,5"/>
                            <text x="500" y="190" font-family="Arial" font-size="12" fill="#E9ECEF" text-anchor="middle">Payment (minus commission)</text>
                        </g>
                        
                        <!-- Moving Package Animation -->
                        <rect x="760" y="140" width="20" height="20" fill="#F72585" class="package">
                            <animate attributeName="x" values="760;840" dur="3s" repeatCount="indefinite"/>
                        </rect>
                        
                        <!-- Moving Payment Animation -->
                        <circle cx="160" cy="170" r="5" fill="#4CC9F0">
                            <animate attributeName="cx" values="160;240" dur="2s" repeatCount="indefinite"/>
                        </circle>
                        
                        <circle cx="360" cy="170" r="5" fill="#4CC9F0">
                            <animate attributeName="cx" values="360;640" dur="4s" repeatCount="indefinite"/>
                        </circle>
                        
                        <!-- Arrow Definitions -->
                        <defs>
                            <marker id="arrowhead" markerWidth="10" markerHeight="7" refX="9" refY="3.5" orient="auto">
                                <polygon points="0 0, 10 3.5, 0 7" fill="#4895EF"/>
                            </marker>
                        </defs>
                        
                        <!-- Digital Data Flow -->
                        <g opacity="0.7">
                            <path d="M200,100 C250,80 350,120 400,100" stroke="#4CC9F0" stroke-width="1" stroke-dasharray="3,3" fill="none"/>
                            <path d="M400,100 C450,80 550,120 600,100" stroke="#4CC9F0" stroke-width="1" stroke-dasharray="3,3" fill="none"/>
                            <path d="M600,100 C650,80 750,120 800,100" stroke="#4CC9F0" stroke-width="1" stroke-dasharray="3,3" fill="none"/>
                            
                            <circle cx="220" cy="95" r="2" fill="#4CC9F0">
                                <animate attributeName="cx" values="200;400;200" dur="6s" repeatCount="indefinite"/>
                                <animate attributeName="cy" values="100;100;100" dur="6s" repeatCount="indefinite"/>
                            </circle>
                            
                            <circle cx="420" cy="95" r="2" fill="#4CC9F0">
                                <animate attributeName="cx" values="400;600;400" dur="7s" repeatCount="indefinite"/>
                                <animate attributeName="cy" values="100;100;100" dur="7s" repeatCount="indefinite"/>
                            </circle>
                            
                            <circle cx="620" cy="95" r="2" fill="#4CC9F0">
                                <animate attributeName="cx" values="600;800;600" dur="8s" repeatCount="indefinite"/>
                                <animate attributeName="cy" values="100;100;100" dur="8s" repeatCount="indefinite"/>
                            </circle>
                        </g>
                    </svg>
                </div>
            </div>
        </div>
    </section>

    <!-- Dashboard Section -->
    <section id="dashboard" class="py-16 md:py-24 bg-dark-deeper relative">
        <div class="blob bg-secondary w-96 h-96 bottom-0 right-0 opacity-10"></div>
        
        <div class="container mx-auto px-6 relative z-10">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-white mb-4">Business <span class="gradient-text">Dashboard</span></h2>
                <p class="text-neutral-light max-w-2xl mx-auto">Track your business performance with our comprehensive dashboard that provides real-time insights.</p>
                <div class="w-24 h-1 bg-secondary mx-auto mt-4"></div>
            </div>
            
            <div class="bg-dark rounded-xl shadow-lg p-6 md:p-10 glass">
                <div class="grid grid-cols-1 md:grid-cols-3 gap-6 mb-8">
                    <!-- Dashboard Card 1 -->
                    <div class="dashboard-card p-6 shadow-md neon-border">
                        <div class="flex items-center justify-between mb-4">
                            <h3 class="text-lg font-semibold text-white">Sales Overview</h3>
                            <div class="bg-primary bg-opacity-20 rounded-full p-2">
                                <svg class="w-5 h-5 text-primary-light" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8c-1.657 0-3 .895-3 2s1.343 2 3 2 3 .895 3 2-1.343 2-3 2m0-8c1.11 0 2.08.402 2.599 1M12 8V7m0 1v8m0 0v1m0-1c-1.11 0-2.08-.402-2.599-1M21 12a9 9 0 11-18 0 9 9 0 0118 0z"></path>
                                </svg>
                            </div>
                        </div>
                        <div class="flex items-end justify-between">
                            <div>
                                <span class="text-neutral-light text-sm">Monthly Revenue</span>
                                <div class="text-2xl font-bold text-white">$24,500</div>
                                <div class="flex items-center mt-2 text-sm">
                                    <svg class="w-4 h-4 text-green-400 mr-1" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 7h8m0 0v8m0-8l-8 8-4-4-6 6"></path>
                                    </svg>
                                    <span class="text-green-400 font-medium">+12.5%</span>
                                    <span class="text-neutral-light ml-1">vs last month</span>
                                </div>
                            </div>
                            <div class="h-16 flex items-end">
                                <div class="w-4 h-8 bg-primary bg-opacity-20 rounded-t-sm mx-1"></div>
                                <div class="w-4 h-10 bg-primary bg-opacity-30 rounded-t-sm mx-1"></div>
                                <div class="w-4 h-12 bg-primary bg-opacity-50 rounded-t-sm mx-1"></div>
                                <div class="w-4 h-16 bg-primary-light rounded-t-sm mx-1"></div>
                            </div>
                        </div>
                    </div>
                    
                    <!-- Dashboard Card 2 -->
                    <div class="dashboard-card p-6 shadow-md neon-border">
                        <div class="flex items-center justify-between mb-4">
                            <h3 class="text-lg font-semibold text-white">Order Status</h3>
                            <div class="bg-secondary bg-opacity-20 rounded-full p-2">
                                <svg class="w-5 h-5 text-secondary-light" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 11V7a4 4 0 00-8 0v4M5 9h14l1 12H4L5 9z"></path>
                                </svg>
                            </div>
                        </div>
                        <div class="space-y-4">
                            <div>
                                <div class="flex justify-between mb-1">
                                    <span class="text-sm text-neutral-light">Processing</span>
                                    <span class="text-sm font-medium text-white">45</span>
                                </div>
                                <div class="w-full bg-dark-light rounded-full h-2">
                                    <div class="bg-secondary-light h-2 rounded-full animate-progress" style="width: 30%"></div>
                                </div>
                            </div>
                            <div>
                                <div class="flex justify-between mb-1">
                                    <span class="text-sm text-neutral-light">Shipped</span>
                                    <span class="text-sm font-medium text-white">87</span>
                                </div>
                                <div class="w-full bg-dark-light rounded-full h-2">
                                    <div class="bg-primary-light h-2 rounded-full animate-progress" style="width: 60%"></div>
                                </div>
                            </div>
                            <div>
                                <div class="flex justify-between mb-1">
                                    <span class="text-sm text-neutral-light">Delivered</span>
                                    <span class="text-sm font-medium text-white">124</span>
                                </div>
                                <div class="w-full bg-dark-light rounded-full h-2">
                                    <div class="bg-accent-light h-2 rounded-full animate-progress" style="width: 85%"></div>
                                </div>
                            </div>
                        </div>
                    </div>
                    
                    <!-- Dashboard Card 3 -->
                    <div class="dashboard-card p-6 shadow-md neon-border">
                        <div class="flex items-center justify-between mb-4">
                            <h3 class="text-lg font-semibold text-white">Customer Insights</h3>
                            <div class="bg-accent bg-opacity-20 rounded-full p-2">
                                <svg class="w-5 h-5 text-accent-light" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 20h5v-2a3 3 0 00-5.356-1.857M17 20H7m10 0v-2c0-.656-.126-1.283-.356-1.857M7 20H2v-2a3 3 0 015.356-1.857M7 20v-2c0-.656.126-1.283.356-1.857m0 0a5.002 5.002 0 019.288 0M15 7a3 3 0 11-6 0 3 3 0 016 0zm6 3a2 2 0 11-4 0 2 2 0 014 0zM7 10a2 2 0 11-4 0 2 2 0 014 0z"></path>
                                </svg>
                            </div>
                        </div>
                        <div class="flex items-center justify-center">
                            <div class="w-32 h-32 relative">
                                <svg viewBox="0 0 36 36" class="w-full h-full">
                                    <path d="M18 2.0845 a 15.9155 15.9155 0 0 1 0 31.831 a 15.9155 15.9155 0 0 1 0 -31.831" fill="none" stroke="#121416" stroke-width="3" stroke-dasharray="100, 100"/>
                                    <path d="M18 2.0845 a 15.9155 15.9155 0 0 1 0 31.831 a 15.9155 15.9155 0 0 1 0 -31.831" fill="none" stroke="#4361EE" stroke-width="3" stroke-dasharray="75, 100" class="animate-progress"/>
                                    <path d="M18 2.0845 a 15.9155 15.9155 0 0 1 0 31.831 a 15.9155 15.9155 0 0 1 0 -31.831" fill="none" stroke="#4CC9F0" stroke-width="3" stroke-dasharray="20, 100" stroke-dashoffset="-75" class="animate-progress"/>
                                    <path d="M18 2.0845 a 15.9155 15.9155 0 0 1 0 31.831 a 15.9155 15.9155 0 0 1 0 -31.831" fill="none" stroke="#F72585" stroke-width="3" stroke-dasharray="5, 100" stroke-dashoffset="-95" class="animate-progress"/>
                                </svg>
                                <div class="absolute inset-0 flex items-center justify-center flex-col">
                                    <span class="text-2xl font-bold text-white">1,250</span>
                                    <span class="text-xs text-neutral-light">Customers</span<script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'9624458a74140ea3',t:'MTc1MzAzMzUyMC4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script>
