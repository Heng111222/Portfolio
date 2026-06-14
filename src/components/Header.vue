<template>
    <nav
        class="fixed top-0 left-0 right-0 z-50 bg-slate-950/80 backdrop-blur-lg border-b border-slate-800 font-[Battambang]">
        <div class="max-w-7xl mx-auto px-6">
            <div class="flex items-center justify-between h-20">
                <a href="#" class="flex items-center gap-2">
                    <div>
                        <h1 class="text-white font-bold text-lg">HENG</h1>
                    </div>
                </a>

                <ul class="hidden lg:flex items-center gap-8">
                    <li><a href="#home" class="text-slate-300 hover:text-indigo-400 transition duration-300">Home</a>
                    </li>
                    <li><a href="#about" class="text-slate-300 hover:text-indigo-400 transition duration-300">About</a>
                    </li>
                    <li><a href="#skills"
                            class="text-slate-300 hover:text-indigo-400 transition duration-300">Skills</a></li>
                    <li><a href="#projects"
                            class="text-slate-300 hover:text-indigo-400 transition duration-300">Projects</a></li>
                    <li><a href="#experience"
                            class="text-slate-300 hover:text-indigo-400 transition duration-300">Experience</a></li>
                    <li><a href="#services"
                            class="text-slate-300 hover:text-indigo-400 transition duration-300">Services</a></li>
                    <li><a href="#contact"
                            class="text-slate-300 hover:text-indigo-400 transition duration-300">Contact</a></li>
                </ul>

                <div class="hidden lg:flex items-center gap-4">
                    <a href="#"
                        class="w-11 h-11 rounded-xl border-2 border-slate-700 flex items-center justify-center text-slate-300 hover:border-indigo-500 hover:text-white transition">
                        <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 24 24" class="w-5 h-5">
                            <path
                                d="M12 .5C5.65.5.5 5.65.5 12A11.5 11.5 0 008.34 22.95c.58.1.79-.25.79-.56v-2.17c-3.19.69-3.87-1.37-3.87-1.37-.52-1.33-1.28-1.68-1.28-1.68-1.05-.71.08-.7.08-.7 1.16.08 1.77 1.2 1.77 1.2 1.04 1.78 2.72 1.27 3.38.97.1-.75.4-1.27.73-1.57-2.55-.29-5.24-1.28-5.24-5.68 0-1.25.45-2.28 1.19-3.08-.12-.29-.52-1.45.11-3.02 0 0 .97-.31 3.18 1.18a11.1 11.1 0 015.8 0c2.21-1.49 3.18-1.18 3.18-1.18.63 1.57.23 2.73.11 3.02.74.8 1.19 1.83 1.19 3.08 0 4.41-2.69 5.39-5.25 5.67.42.36.79 1.08.79 2.18v3.24c0 .31.21.67.8.56A11.5 11.5 0 0023.5 12C23.5 5.65 18.35.5 12 .5z" />
                        </svg>
                    </a>
                    <a href="#"
                        class="px-5 py-2.5 rounded-xl border-2 border-slate-700 text-slate-300 hover:border-2 hover:border-indigo-500 hover:text-white transition">Download
                        CV</a>
                </div>

                <button
                    class="lg:hidden w-11 h-11 rounded-xl border border-slate-700 text-white flex items-center justify-center">
                    <svg xmlns="http://www.w3.org/2000/svg" class="w-6 h-6" fill="none" viewBox="0 0 24 24"
                        stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                            d="M4 6h16M4 12h16M4 18h16" />
                    </svg>
                </button>
            </div>
        </div>
    </nav>

    <main class="bg-slate-950 text-slate-100 pt-20 overflow-x-hidden font-[Battambang]">

        <section id="home"
            class="min-h-[calc(100vh-5rem)] flex items-center relative py-16 overflow-hidden bg-slate-950">

            <div
                class="absolute inset-0 bg-[linear-gradient(to_right,#0f172a_1px,transparent_1px),linear-gradient(to_bottom,#0f172a_1px,transparent_1px)] bg-[size:4rem_4rem] [mask-image:radial-gradient(ellipse_60%_50%_at_50%_0%,#000_70%,transparent_100%)]">
            </div>

            <div class="absolute top-1/4 left-1/4 w-96 h-96 bg-indigo-600/10 rounded-full blur-[120px] animate-pulse">
            </div>

            <div
                class="absolute bottom-1/4 right-1/4 w-96 h-96 bg-purple-600/10 rounded-full blur-[120px] animate-[pulse_6s_infinite_2s]">
            </div>

            <div
                class="max-w-7xl mx-auto px-6 w-full grid grid-cols-1 lg:grid-cols-2 gap-16 items-center relative z-10">

                <div class="space-y-8 text-center lg:text-left order-2 lg:order-1">

                    <!-- Status Badge -->
                    <div class="flex justify-center lg:justify-start">
                        <div class="group relative inline-flex items-center gap-3 px-5 py-2.5 rounded-full
            border border-indigo-500/20 bg-slate-900/70 backdrop-blur-xl
            hover:border-indigo-500/50 transition-all duration-300">

                            <span class="relative flex h-3 w-3">
                                <span
                                    class="absolute inline-flex h-full w-full rounded-full bg-emerald-400 animate-ping opacity-75">
                                </span>

                                <span class="relative inline-flex h-3 w-3 rounded-full bg-emerald-500">
                                </span>
                            </span>

                            <span class="text-sm text-slate-300">
                                Available for Freelance & Full-Time
                            </span>
                        </div>
                    </div>

                    <!-- Heading -->
                    <div class="space-y-4">

                        <h4 class="text-indigo-400 font-semibold tracking-wider uppercase">
                            Full Stack Developer
                        </h4>

                        <h1 class="text-5xl sm:text-6xl lg:text-5xl font-black leading-tight">

                            Hi, I'm

                            <span class="text-white bg-clip-text">
                                Heng
                            </span>

                        </h1>

                    </div>

                    <!-- Description -->
                    <p class="text-slate-400 text-lg max-w-2xl mx-auto lg:mx-0 leading-relaxed">

                        I specialize in creating scalable web applications,
                        powerful backend systems, and modern user experiences
                        using Laravel, Vue.js, React, and Node.js.

                    </p>

                    <!-- Tech Stack -->
                    <div class="flex flex-wrap justify-center lg:justify-start gap-3">

                        <span class="px-4 py-2 rounded-full bg-slate-900 border border-slate-800 text-slate-300">
                            Laravel
                        </span>

                        <span class="px-4 py-2 rounded-full bg-slate-900 border border-slate-800 text-slate-300">
                            Vue.js
                        </span>

                        <span class="px-4 py-2 rounded-full bg-slate-900 border border-slate-800 text-slate-300">
                            React
                        </span>

                        <span class="px-4 py-2 rounded-full bg-slate-900 border border-slate-800 text-slate-300">
                            Node.js
                        </span>

                    </div>

                    <!-- Stats -->
                    <div class="flex justify-center lg:justify-start gap-8 pt-2">

                        <div>
                            <h3 class="text-3xl font-bold text-white">20+</h3>
                            <p class="text-slate-500 text-sm">Projects</p>
                        </div>

                        <div>
                            <h3 class="text-3xl font-bold text-white">3+</h3>
                            <p class="text-slate-500 text-sm">Years Learning</p>
                        </div>

                        <div>
                            <h3 class="text-3xl font-bold text-white">10+</h3>
                            <p class="text-slate-500 text-sm">Technologies</p>
                        </div>

                    </div>

                    <!-- CTA Buttons -->
                    <div class="flex flex-col sm:flex-row gap-4 justify-center lg:justify-start">

                        <a href="#projects" class="group px-8 py-4 rounded-xl
            bg-gradient-to-r from-indigo-600 to-purple-600
            text-white font-semibold
            hover:scale-105 transition-all duration-300">

                            View Projects
                            <i class="fa-solid fa-arrow-right ml-2 group-hover:translate-x-1 transition-transform">
                            </i>
                        </a>

                        <a href="#contact" class="px-8 py-4 rounded-xl
            border border-slate-700
            bg-slate-900/50
            text-slate-300
            hover:border-indigo-500
            hover:text-white
            transition-all duration-300">

                            Let's Talk

                        </a>

                    </div>

                </div>

                <div class="flex justify-center relative order-1 lg:order-2 mb-20 lg:mb-25">

                    <div class="relative animate-[floatAvatar_6s_ease-in-out_infinite]">

                        <!-- Outer Glow -->
                        <div class="absolute inset-0 rounded-full bg-gradient-to-r
        from-indigo-500/30 via-purple-500/30 to-pink-500/30
        blur-[80px]
        animate-[glowPulse_4s_ease-in-out_infinite]">
                        </div>

                        <!-- Rotating Ring -->
                        <div class="absolute -inset-4 rounded-full
        bg-gradient-to-r
        from-indigo-500 via-purple-500 to-pink-500
        opacity-30 blur-md
        animate-[rotateRing_12s_linear_infinite]">
                        </div>

                        <!-- Animated Border -->
                        <div class="relative p-[4px] rounded-full
        bg-gradient-to-r
        from-indigo-700 via-purple-600 to-pink-500
        bg-[length:300%_300%]
        animate-[gradient_6s_ease_infinite]">

                            <!-- Image -->
                            <div class="relative w-72 h-72 sm:w-80 sm:h-80
            rounded-full overflow-hidden
            bg-slate-900 border-4 border-slate-950">

                                <img src="@/assets/photo/mysafe.png" alt="Chhun Heng" class="w-full h-full object-cover
                hover:scale-110
                transition-all duration-700">

                                <!-- Overlay -->
                                <div class="absolute inset-0
                bg-gradient-to-t
                from-slate-950/60
                via-transparent
                to-transparent">
                                </div>

                            </div>

                        </div>

                    </div>
                    <!-- Vue -->
                    <div class="absolute top-5 -left-10 hidden lg:flex items-center gap-3
    px-4 py-3 rounded-2xl
    bg-slate-900/90 backdrop-blur-xl
    border border-slate-800
    animate-[float_2s_ease-in-out_infinite]
    hover:scale-105 hover:border-emerald-500/40
    transition-all duration-300">

                        <div
                            class="w-12 h-12 rounded-xl bg-emerald-500/10 border border-emerald-500/20 flex items-center justify-center">
                            <i class="fa-brands fa-vuejs text-3xl text-emerald-400"></i>
                        </div>

                        <div>
                            <h4 class="text-white text-sm font-semibold">Vue.js</h4>
                            <p class="text-slate-400 text-xs">Frontend Framework</p>
                        </div>

                    </div>

                    <!-- React -->
                    <div class="absolute top-5 right-0 hidden lg:flex items-center gap-3
    px-4 py-3 rounded-2xl
    bg-slate-900/90 backdrop-blur-xl
    border border-slate-800
    animate-[float_5s_ease-in-out_infinite]
    hover:scale-105 hover:border-cyan-500/40
    transition-all duration-300">

                        <div
                            class="w-12 h-12 rounded-xl bg-cyan-500/10 border border-cyan-500/20 flex items-center justify-center">
                            <i
                                class="fa-brands fa-react text-3xl text-cyan-400 animate-spin [animation-duration:8s]"></i>
                        </div>

                        <div>
                            <h4 class="text-white text-sm font-semibold">React</h4>
                            <p class="text-slate-400 text-xs">UI Library</p>
                        </div>

                    </div>

                    <!-- Laravel -->
                    <div class="absolute bottom-10 -left-10 hidden lg:flex items-center gap-3
    px-4 py-3 rounded-2xl
    bg-slate-900/90 backdrop-blur-xl
    border border-slate-800
    animate-[float_6s_ease-in-out_infinite]
    hover:scale-105 hover:border-red-500/40
    transition-all duration-300">

                        <div
                            class="w-12 h-12 rounded-xl bg-red-500/10 border border-red-500/20 flex items-center justify-center">
                            <i
                                class="fa-brands fa-laravel text-3xl text-red-500 animate-[swing_4s_ease-in-out_infinite]"></i>
                        </div>

                        <div>
                            <h4 class="text-white text-sm font-semibold">Laravel</h4>
                            <p class="text-slate-400 text-xs">Backend Framework</p>
                        </div>

                    </div>

                    <!-- Node.js -->
                    <div class="absolute bottom-10 -right-10 hidden lg:flex items-center gap-3
    px-4 py-3 rounded-2xl
    bg-slate-900/90 backdrop-blur-xl
    border border-slate-800
    animate-[float_2s_ease-in-out_infinite]
    hover:scale-105 hover:border-green-500/40
    transition-all duration-300">

                        <div
                            class="w-12 h-12 rounded-xl bg-green-500/10 border border-green-500/20 flex items-center justify-center">
                            <i class="fa-brands fa-node-js text-3xl text-green-500 animate-pulse"></i>
                        </div>

                        <div>
                            <h4 class="text-white text-sm font-semibold">Node.js</h4>
                            <p class="text-slate-400 text-xs">Runtime Environment</p>
                        </div>

                    </div>
                    <!-- Online Badge -->
                    <div
                        class="absolute bottom-0 left-1/2 -translate-x-1/2 translate-y-1/2 px-4 py-2 rounded-full bg-slate-900/90 backdrop-blur-md border border-slate-800 flex items-center gap-2">

                        <span class="relative flex h-3 w-3">
                            <span
                                class="animate-ping absolute inline-flex h-full w-full rounded-full bg-emerald-400 opacity-75"></span>
                            <span class="relative inline-flex rounded-full h-3 w-3 bg-green-500"></span>
                        </span>

                        <span class="text-sm text-slate-300">
                            Hello! I'm Heng
                        </span>

                    </div>

                    <!-- MOBILE TECH STACK -->
                    <div class="absolute -bottom-24 left-1/2 -translate-x-1/2 lg:hidden">

                        <div
                            class="flex items-center gap-4 px-5 py-3 rounded-full bg-slate-900/90 backdrop-blur-xl border border-slate-800">

                            <i class="fa-brands fa-laravel text-red-500 text-xl"></i>

                            <i class="fa-brands fa-vuejs text-emerald-400 text-xl"></i>

                            <i class="fa-brands fa-react text-cyan-400 text-xl"></i>

                            <i class="fa-brands fa-node-js text-green-500 text-xl"></i>

                        </div>

                    </div>

                </div>
            </div>
        </section>

        <section id="about" class="py-24 border-t border-slate-900/60 relative">
            <div class="max-w-7xl mx-auto px-6">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-12">
                    <div class="lg:col-span-4">
                        <p class="text-indigo-400 text-2xl font-semibold uppercase tracking-wider mb-4">1. About Me</p>
                        <h3 class="text-3xl font-bold text-white">Who is Chhun Heng?</h3>
                    </div>
                    <div class="lg:col-span-8 space-y-6 text-slate-400 text-lg leading-relaxed">
                        <p>
                            I am a software engineer driven by curiosity and a relentless commitment to writing clean,
                            maintainable code. Over the years, I've had the privilege of engineering clean architectures
                            for robust web platforms, real-time engines, and intricate database schemas.
                        </p>
                        <p>
                            My approach balances innovative design with pragmatic structure, ensuring that your
                            application doesn't just look modern, but operates smoothly under heavy workloads.
                        </p>
                        <div class="grid grid-cols-2 sm:grid-cols-3 gap-6 pt-6">
                            <div class="p-4 rounded-xl bg-slate-900/40 border border-slate-900">
                                <h4 class="text-2xl font-bold text-white">3+</h4>
                                <p class="text-xs text-slate-500">Years of Experience</p>
                            </div>
                            <div class="p-4 rounded-xl bg-slate-900/40 border border-slate-900">
                                <h4 class="text-2xl font-bold text-white">20+</h4>
                                <p class="text-xs text-slate-500">Projects Delivered</p>
                            </div>
                            <div class="p-4 rounded-xl bg-slate-900/40 border border-slate-900">
                                <h4 class="text-2xl font-bold text-white">99%</h4>
                                <p class="text-xs text-slate-500">Client Satisfaction</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <section id="skills" class="py-24 border-t border-slate-900/60 bg-slate-950/50">
            <div class="max-w-7xl mx-auto px-6">
                <div class="text-center max-w-xl mx-auto mb-16">
                    <p class="text-indigo-400 text-sm font-semibold uppercase tracking-wider mb-2">02. Core Expertise
                    </p>
                    <h3 class="text-3xl font-bold text-white">My Tech Stack</h3>
                </div>
                <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                    <div
                        class="p-8 rounded-2xl bg-slate-900/30 border border-slate-900 hover:border-indigo-500/20 transition group">
                        <h4 class="text-xl font-semibold text-white mb-6 flex items-center gap-2">
                            <span class="w-2 h-2 rounded-full bg-indigo-500"></span> Frontend Development
                        </h4>
                        <ul class="space-y-3 text-slate-400">
                            <li class="flex justify-between"><span>Vue.js / Nuxt</span> <span
                                    class="text-slate-600">Advanced</span></li>
                            <li class="flex justify-between"><span>React / Next.js</span> <span
                                    class="text-slate-600">Intermediate</span></li>
                            <li class="flex justify-between"><span>Tailwind CSS</span> <span
                                    class="text-slate-600">Expert</span></li>
                            <li class="flex justify-between"><span>TypeScript</span> <span
                                    class="text-slate-600">Advanced</span></li>
                        </ul>
                    </div>
                    <div
                        class="p-8 rounded-2xl bg-slate-900/30 border border-slate-900 hover:border-indigo-500/20 transition group">
                        <h4 class="text-xl font-semibold text-white mb-6 flex items-center gap-2">
                            <span class="w-2 h-2 rounded-full bg-emerald-500"></span> Backend Engineering
                        </h4>
                        <ul class="space-y-3 text-slate-400">
                            <li class="flex justify-between"><span>Node.js / Express</span> <span
                                    class="text-slate-600">Advanced</span></li>
                            <li class="flex justify-between"><span>Python / Django</span> <span
                                    class="text-slate-600">Intermediate</span></li>
                            <li class="flex justify-between"><span>GraphQL / REST APIs</span> <span
                                    class="text-slate-600">Expert</span></li>
                            <li class="flex justify-between"><span>PostgreSQL / MongoDB</span> <span
                                    class="text-slate-600">Advanced</span></li>
                        </ul>
                    </div>
                    <div
                        class="p-8 rounded-2xl bg-slate-900/30 border border-slate-900 hover:border-indigo-500/20 transition group">
                        <h4 class="text-xl font-semibold text-white mb-6 flex items-center gap-2">
                            <span class="w-2 h-2 rounded-full bg-purple-500"></span> DevOps & Operations
                        </h4>
                        <ul class="space-y-3 text-slate-400">
                            <li class="flex justify-between"><span>Docker</span> <span
                                    class="text-slate-600">Intermediate</span></li>
                            <li class="flex justify-between"><span>AWS (S3, EC2)</span> <span
                                    class="text-slate-600">Intermediate</span></li>
                            <li class="flex justify-between"><span>Git / GitHub Actions</span> <span
                                    class="text-slate-600">Advanced</span></li>
                            <li class="flex justify-between"><span>Linux / Nginx</span> <span
                                    class="text-slate-600">Advanced</span></li>
                        </ul>
                    </div>
                </div>
            </div>
        </section>

        <section id="projects" class="py-24 border-t border-slate-900/60">
            <div class="max-w-7xl mx-auto px-6">
                <div class="flex flex-col md:flex-row md:items-end justify-between mb-16 gap-4">
                    <div>
                        <p class="text-indigo-400 text-sm font-semibold uppercase tracking-wider mb-2">03. Selected Work
                        </p>
                        <h3 class="text-3xl font-bold text-white">Featured Projects</h3>
                    </div>
                    <a href="#"
                        class="text-indigo-400 hover:text-indigo-300 font-medium transition flex items-center gap-1 group">
                        View All Projects
                        <span class="transform group-hover:translate-x-1 transition-transform">&rarr;</span>
                    </a>
                </div>

                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                    <!-- Project Card 1 -->
                    <div
                        class="group relative overflow-hidden rounded-3xl border-2 border-slate-800/50 bg-slate-900/60 backdrop-blur-xl transition-all duration-500 hover:-translate-y-3 hover:border-indigo-500/30">

                        <!-- Glow Effect -->
                        <div
                            class="absolute inset-0 bg-gradient-to-br from-indigo-500/5 via-transparent to-purple-500/5 opacity-0 group-hover:opacity-100 transition-opacity duration-500">
                        </div>

                        <!-- Image Section -->
                        <div class="relative h-64 overflow-hidden">

                            <!-- Image -->
                            <img src="@/assets/photo/e-commerce.png" alt="E-Commerce Architecture Platform"
                                class="w-full h-full object-cover object-top transition-transform duration-700 group-hover:scale-110">

                            <!-- Overlay -->
                            <div
                                class="absolute inset-0 -z-10 bg-gradient-to-br from-indigo-500/10 via-transparent to-purple-500/10">
                            </div>

                            <!-- Live Badge -->
                            <div class="absolute top-4 left-4 z-20">

                                <span
                                    class="inline-flex items-center gap-2 px-3 py-1.5 rounded-full bg-emerald-500/15 backdrop-blur-md border border-emerald-500/30 text-emerald-400 text-xs font-semibold">

                                    <span class="w-2 h-2 rounded-full bg-emerald-400 animate-pulse"></span>

                                    Live Project

                                </span>

                            </div>

                            <!-- Featured Badge -->
                            <div class="absolute top-4 right-4 z-20">

                                <span
                                    class="px-3 py-1 rounded-full bg-indigo-500/15 backdrop-blur-md border border-indigo-500/30 text-indigo-400 text-xs font-semibold">

                                    Featured

                                </span>

                            </div>

                            <!-- Bottom Info -->
                            <div class="absolute bottom-4 left-4 right-4 z-20">

                                <div class="flex items-center justify-between">

                                    <span
                                        class="px-3 py-2 rounded-full bg-slate-900/10 backdrop-blur-md text-indigo-500 text-xs uppercase tracking-wider font-semibold">
                                        Web Application
                                    </span>

                                    <button
                                        class="w-10 h-10 rounded-xl bg-white/10 backdrop-blur-md border border-white/10 text-white flex items-center justify-center opacity-0 group-hover:opacity-100 transition-all duration-300">

                                        <svg xmlns="http://www.w3.org/2000/svg" class="w-5 h-5" fill="none"
                                            viewBox="0 0 24 24" stroke="currentColor">

                                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                                d="M14 3h7m0 0v7m0-7L10 14" />

                                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                                d="M5 5v14h14" />

                                        </svg>

                                    </button>

                                </div>

                            </div>

                        </div>

                        <!-- Content -->
                        <div class="relative p-6">

                            <h3 class="text-xl font-bold text-white mb-3 group-hover:text-indigo-400 transition-colors">
                                E-Commerce Architecture Platform
                            </h3>

                            <p class="text-slate-400 text-sm leading-relaxed mb-5">
                                A scalable multi-vendor commerce platform built with microservices,
                                serverless infrastructure, and cloud-native deployment architecture.
                            </p>

                            <!-- Tech Stack -->
                            <div class="flex flex-wrap gap-2 mb-5">

                                <span
                                    class="px-3 py-1 rounded-sm text-xs font-medium bg-indigo-500/10 text-indigo-300 border border-indigo-500/20">
                                    Vue.js
                                </span>

                                <span
                                    class="px-3 py-1 rounded-sm text-xs font-medium bg-green-500/10 text-green-300 border border-green-500/20">
                                    Node.js
                                </span>

                                <span
                                    class="px-3 py-1 rounded-sm text-xs font-medium bg-cyan-500/10 text-cyan-300 border border-cyan-500/20">
                                    PostgreSQL
                                </span>

                            </div>

                            <!-- Footer -->
                            <div class="flex items-center justify-between pt-4 border-t border-slate-800">

                                <div class="flex items-center gap-2 text-slate-400 text-sm">

                                    <svg xmlns="http://www.w3.org/2000/svg" class="w-4 h-4" fill="none"
                                        viewBox="0 0 24 24" stroke="currentColor">

                                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                            d="M9 12h6m-6 4h6m2 5H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z" />
                                    </svg>

                                    Portfolio Project

                                </div>

                                <a href="#"
                                    class="text-indigo-500 text-sm font-medium hover:text-indigo-300 transition-colors">
                                    Link Website →
                                </a>

                            </div>

                        </div>

                    </div>
                    <div
                        class="group relative overflow-hidden rounded-3xl border-2 border-slate-800/50 bg-slate-900/60 backdrop-blur-xl transition-all duration-500 hover:-translate-y-3 hover:border-indigo-500/30">

                        <!-- Glow Effect -->
                        <div
                            class="absolute inset-0 bg-gradient-to-br from-indigo-500/5 via-transparent to-purple-500/5 opacity-0 group-hover:opacity-100 transition-opacity duration-500">
                        </div>

                        <!-- Image Section -->
                        <div class="relative h-64 overflow-hidden">

                            <!-- Image -->
                            <img src="@/assets/photo/e-commerce.png" alt="E-Commerce Architecture Platform"
                                class="w-full h-full object-cover object-top transition-transform duration-700 group-hover:scale-110">

                            <!-- Overlay -->
                            <div
                                class="absolute inset-0 -z-10 bg-gradient-to-br from-indigo-500/10 via-transparent to-purple-500/10">
                            </div>

                            <!-- Live Badge -->
                            <div class="absolute top-4 left-4 z-20">

                                <span
                                    class="inline-flex items-center gap-2 px-3 py-1.5 rounded-full bg-emerald-500/15 backdrop-blur-md border border-emerald-500/30 text-emerald-400 text-xs font-semibold">

                                    <span class="w-2 h-2 rounded-full bg-emerald-400 animate-pulse"></span>

                                    Live Project

                                </span>

                            </div>

                            <!-- Featured Badge -->
                            <div class="absolute top-4 right-4 z-20">

                                <span
                                    class="px-3 py-1 rounded-full bg-indigo-500/15 backdrop-blur-md border border-indigo-500/30 text-indigo-400 text-xs font-semibold">

                                    Featured

                                </span>

                            </div>

                            <!-- Bottom Info -->
                            <div class="absolute bottom-4 left-4 right-4 z-20">

                                <div class="flex items-center justify-between">

                                    <span
                                        class="px-3 py-2 rounded-full bg-slate-900/10 backdrop-blur-md text-indigo-500 text-xs uppercase tracking-wider font-semibold">
                                        Web Application
                                    </span>

                                    <button
                                        class="w-10 h-10 rounded-xl bg-white/10 backdrop-blur-md border border-white/10 text-white flex items-center justify-center opacity-0 group-hover:opacity-100 transition-all duration-300">

                                        <svg xmlns="http://www.w3.org/2000/svg" class="w-5 h-5" fill="none"
                                            viewBox="0 0 24 24" stroke="currentColor">

                                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                                d="M14 3h7m0 0v7m0-7L10 14" />

                                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                                d="M5 5v14h14" />

                                        </svg>

                                    </button>

                                </div>

                            </div>

                        </div>

                        <!-- Content -->
                        <div class="relative p-6">

                            <h3 class="text-xl font-bold text-white mb-3 group-hover:text-indigo-400 transition-colors">
                                E-Commerce Architecture Platform
                            </h3>

                            <p class="text-slate-400 text-sm leading-relaxed mb-5">
                                A scalable multi-vendor commerce platform built with microservices,
                                serverless infrastructure, and cloud-native deployment architecture.
                            </p>

                            <!-- Tech Stack -->
                            <div class="flex flex-wrap gap-2 mb-5">

                                <span
                                    class="px-3 py-1 rounded-sm text-xs font-medium bg-indigo-500/10 text-indigo-300 border border-indigo-500/20">
                                    Vue.js
                                </span>

                                <span
                                    class="px-3 py-1 rounded-sm text-xs font-medium bg-green-500/10 text-green-300 border border-green-500/20">
                                    Node.js
                                </span>

                                <span
                                    class="px-3 py-1 rounded-sm text-xs font-medium bg-cyan-500/10 text-cyan-300 border border-cyan-500/20">
                                    PostgreSQL
                                </span>

                            </div>

                            <!-- Footer -->
                            <div class="flex items-center justify-between pt-4 border-t border-slate-800">

                                <div class="flex items-center gap-2 text-slate-400 text-sm">

                                    <svg xmlns="http://www.w3.org/2000/svg" class="w-4 h-4" fill="none"
                                        viewBox="0 0 24 24" stroke="currentColor">

                                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                            d="M9 12h6m-6 4h6m2 5H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z" />
                                    </svg>

                                    Portfolio Project

                                </div>

                                <a href="#"
                                    class="text-indigo-500 text-sm font-medium hover:text-indigo-300 transition-colors">
                                    Link Website →
                                </a>

                            </div>

                        </div>

                    </div>
                    <div
                        class="group relative overflow-hidden rounded-3xl border-2 border-slate-800/50 bg-slate-900/60 backdrop-blur-xl transition-all duration-500 hover:-translate-y-3 hover:border-indigo-500/30">

                        <!-- Glow Effect -->
                        <div
                            class="absolute inset-0 bg-gradient-to-br from-indigo-500/5 via-transparent to-purple-500/5 opacity-0 group-hover:opacity-100 transition-opacity duration-500">
                        </div>

                        <!-- Image Section -->
                        <div class="relative h-64 overflow-hidden">

                            <!-- Image -->
                            <img src="@/assets/photo/e-commerce.png" alt="E-Commerce Architecture Platform"
                                class="w-full h-full object-cover object-top transition-transform duration-700 group-hover:scale-110">

                            <!-- Overlay -->
                            <div
                                class="absolute inset-0 -z-10 bg-gradient-to-br from-indigo-500/10 via-transparent to-purple-500/10">
                            </div>

                            <!-- Live Badge -->
                            <div class="absolute top-4 left-4 z-20">

                                <span
                                    class="inline-flex items-center gap-2 px-3 py-1.5 rounded-full bg-emerald-500/15 backdrop-blur-md border border-emerald-500/30 text-emerald-400 text-xs font-semibold">

                                    <span class="w-2 h-2 rounded-full bg-emerald-400 animate-pulse"></span>

                                    Live Project

                                </span>

                            </div>

                            <!-- Featured Badge -->
                            <div class="absolute top-4 right-4 z-20">

                                <span
                                    class="px-3 py-1 rounded-full bg-indigo-500/15 backdrop-blur-md border border-indigo-500/30 text-indigo-400 text-xs font-semibold">

                                    Featured

                                </span>

                            </div>

                            <!-- Bottom Info -->
                            <div class="absolute bottom-4 left-4 right-4 z-20">

                                <div class="flex items-center justify-between">

                                    <span
                                        class="px-3 py-2 rounded-full bg-slate-900/10 backdrop-blur-md text-indigo-500 text-xs uppercase tracking-wider font-semibold">
                                        Web Application
                                    </span>

                                    <button
                                        class="w-10 h-10 rounded-xl bg-white/10 backdrop-blur-md border border-white/10 text-white flex items-center justify-center opacity-0 group-hover:opacity-100 transition-all duration-300">

                                        <svg xmlns="http://www.w3.org/2000/svg" class="w-5 h-5" fill="none"
                                            viewBox="0 0 24 24" stroke="currentColor">

                                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                                d="M14 3h7m0 0v7m0-7L10 14" />

                                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                                d="M5 5v14h14" />

                                        </svg>

                                    </button>

                                </div>

                            </div>

                        </div>

                        <!-- Content -->
                        <div class="relative p-6">

                            <h3 class="text-xl font-bold text-white mb-3 group-hover:text-indigo-400 transition-colors">
                                E-Commerce Architecture Platform
                            </h3>

                            <p class="text-slate-400 text-sm leading-relaxed mb-5">
                                A scalable multi-vendor commerce platform built with microservices,
                                serverless infrastructure, and cloud-native deployment architecture.
                            </p>

                            <!-- Tech Stack -->
                            <div class="flex flex-wrap gap-2 mb-5">

                                <span
                                    class="px-3 py-1 rounded-sm text-xs font-medium bg-indigo-500/10 text-indigo-300 border border-indigo-500/20">
                                    Vue.js
                                </span>

                                <span
                                    class="px-3 py-1 rounded-sm text-xs font-medium bg-green-500/10 text-green-300 border border-green-500/20">
                                    Node.js
                                </span>

                                <span
                                    class="px-3 py-1 rounded-sm text-xs font-medium bg-cyan-500/10 text-cyan-300 border border-cyan-500/20">
                                    PostgreSQL
                                </span>

                            </div>

                            <!-- Footer -->
                            <div class="flex items-center justify-between pt-4 border-t border-slate-800">

                                <div class="flex items-center gap-2 text-slate-400 text-sm">

                                    <svg xmlns="http://www.w3.org/2000/svg" class="w-4 h-4" fill="none"
                                        viewBox="0 0 24 24" stroke="currentColor">

                                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                            d="M9 12h6m-6 4h6m2 5H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z" />
                                    </svg>

                                    Portfolio Project

                                </div>

                                <a href="#"
                                    class="text-indigo-500 text-sm font-medium hover:text-indigo-300 transition-colors">
                                    Link Website →
                                </a>

                            </div>

                        </div>

                    </div>
                    <div
                        class="group relative overflow-hidden rounded-3xl border-2 border-slate-800/50 bg-slate-900/60 backdrop-blur-xl transition-all duration-500 hover:-translate-y-3 hover:border-indigo-500/30">

                        <!-- Glow Effect -->
                        <div
                            class="absolute inset-0 bg-gradient-to-br from-indigo-500/5 via-transparent to-purple-500/5 opacity-0 group-hover:opacity-100 transition-opacity duration-500">
                        </div>

                        <!-- Image Section -->
                        <div class="relative h-64 overflow-hidden">

                            <!-- Image -->
                            <img src="@/assets/photo/e-commerce.png" alt="E-Commerce Architecture Platform"
                                class="w-full h-full object-cover object-top transition-transform duration-700 group-hover:scale-110">

                            <!-- Overlay -->
                            <div
                                class="absolute inset-0 -z-10 bg-gradient-to-br from-indigo-500/10 via-transparent to-purple-500/10">
                            </div>

                            <!-- Live Badge -->
                            <div class="absolute top-4 left-4 z-20">

                                <span
                                    class="inline-flex items-center gap-2 px-3 py-1.5 rounded-full bg-emerald-500/15 backdrop-blur-md border border-emerald-500/30 text-emerald-400 text-xs font-semibold">

                                    <span class="w-2 h-2 rounded-full bg-emerald-400 animate-pulse"></span>

                                    Live Project

                                </span>

                            </div>

                            <!-- Featured Badge -->
                            <div class="absolute top-4 right-4 z-20">

                                <span
                                    class="px-3 py-1 rounded-full bg-indigo-500/15 backdrop-blur-md border border-indigo-500/30 text-indigo-400 text-xs font-semibold">

                                    Featured

                                </span>

                            </div>

                            <!-- Bottom Info -->
                            <div class="absolute bottom-4 left-4 right-4 z-20">

                                <div class="flex items-center justify-between">

                                    <span
                                        class="px-3 py-2 rounded-full bg-slate-900/10 backdrop-blur-md text-indigo-500 text-xs uppercase tracking-wider font-semibold">
                                        Web Application
                                    </span>

                                    <button
                                        class="w-10 h-10 rounded-xl bg-white/10 backdrop-blur-md border border-white/10 text-white flex items-center justify-center opacity-0 group-hover:opacity-100 transition-all duration-300">

                                        <svg xmlns="http://www.w3.org/2000/svg" class="w-5 h-5" fill="none"
                                            viewBox="0 0 24 24" stroke="currentColor">

                                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                                d="M14 3h7m0 0v7m0-7L10 14" />

                                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                                d="M5 5v14h14" />

                                        </svg>

                                    </button>

                                </div>

                            </div>

                        </div>

                        <!-- Content -->
                        <div class="relative p-6">

                            <h3 class="text-xl font-bold text-white mb-3 group-hover:text-indigo-400 transition-colors">
                                E-Commerce Architecture Platform
                            </h3>

                            <p class="text-slate-400 text-sm leading-relaxed mb-5">
                                A scalable multi-vendor commerce platform built with microservices,
                                serverless infrastructure, and cloud-native deployment architecture.
                            </p>

                            <!-- Tech Stack -->
                            <div class="flex flex-wrap gap-2 mb-5">

                                <span
                                    class="px-3 py-1 rounded-sm text-xs font-medium bg-indigo-500/10 text-indigo-300 border border-indigo-500/20">
                                    Vue.js
                                </span>

                                <span
                                    class="px-3 py-1 rounded-sm text-xs font-medium bg-green-500/10 text-green-300 border border-green-500/20">
                                    Node.js
                                </span>

                                <span
                                    class="px-3 py-1 rounded-sm text-xs font-medium bg-cyan-500/10 text-cyan-300 border border-cyan-500/20">
                                    PostgreSQL
                                </span>

                            </div>

                            <!-- Footer -->
                            <div class="flex items-center justify-between pt-4 border-t border-slate-800">

                                <div class="flex items-center gap-2 text-slate-400 text-sm">

                                    <svg xmlns="http://www.w3.org/2000/svg" class="w-4 h-4" fill="none"
                                        viewBox="0 0 24 24" stroke="currentColor">

                                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                            d="M9 12h6m-6 4h6m2 5H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z" />
                                    </svg>

                                    Portfolio Project

                                </div>

                                <a href="#"
                                    class="text-indigo-500 text-sm font-medium hover:text-indigo-300 transition-colors">
                                    Link Website →
                                </a>

                            </div>

                        </div>

                    </div>
                    <div
                        class="group relative overflow-hidden rounded-3xl border-2 border-slate-800/50 bg-slate-900/60 backdrop-blur-xl transition-all duration-500 hover:-translate-y-3 hover:border-indigo-500/30">

                        <!-- Glow Effect -->
                        <div
                            class="absolute inset-0 bg-gradient-to-br from-indigo-500/5 via-transparent to-purple-500/5 opacity-0 group-hover:opacity-100 transition-opacity duration-500">
                        </div>

                        <!-- Image Section -->
                        <div class="relative h-64 overflow-hidden">

                            <!-- Image -->
                            <img src="@/assets/photo/e-commerce.png" alt="E-Commerce Architecture Platform"
                                class="w-full h-full object-cover object-top transition-transform duration-700 group-hover:scale-110">

                            <!-- Overlay -->
                            <div
                                class="absolute inset-0 -z-10 bg-gradient-to-br from-indigo-500/10 via-transparent to-purple-500/10">
                            </div>

                            <!-- Live Badge -->
                            <div class="absolute top-4 left-4 z-20">

                                <span
                                    class="inline-flex items-center gap-2 px-3 py-1.5 rounded-full bg-emerald-500/15 backdrop-blur-md border border-emerald-500/30 text-emerald-400 text-xs font-semibold">

                                    <span class="w-2 h-2 rounded-full bg-emerald-400 animate-pulse"></span>

                                    Live Project

                                </span>

                            </div>

                            <!-- Featured Badge -->
                            <div class="absolute top-4 right-4 z-20">

                                <span
                                    class="px-3 py-1 rounded-full bg-indigo-500/15 backdrop-blur-md border border-indigo-500/30 text-indigo-400 text-xs font-semibold">

                                    Featured

                                </span>

                            </div>

                            <!-- Bottom Info -->
                            <div class="absolute bottom-4 left-4 right-4 z-20">

                                <div class="flex items-center justify-between">

                                    <span
                                        class="px-3 py-2 rounded-full bg-slate-900/10 backdrop-blur-md text-indigo-500 text-xs uppercase tracking-wider font-semibold">
                                        Web Application
                                    </span>

                                    <button
                                        class="w-10 h-10 rounded-xl bg-white/10 backdrop-blur-md border border-white/10 text-white flex items-center justify-center opacity-0 group-hover:opacity-100 transition-all duration-300">

                                        <svg xmlns="http://www.w3.org/2000/svg" class="w-5 h-5" fill="none"
                                            viewBox="0 0 24 24" stroke="currentColor">

                                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                                d="M14 3h7m0 0v7m0-7L10 14" />

                                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                                d="M5 5v14h14" />

                                        </svg>

                                    </button>

                                </div>

                            </div>

                        </div>

                        <!-- Content -->
                        <div class="relative p-6">

                            <h3 class="text-xl font-bold text-white mb-3 group-hover:text-indigo-400 transition-colors">
                                E-Commerce Architecture Platform
                            </h3>

                            <p class="text-slate-400 text-sm leading-relaxed mb-5">
                                A scalable multi-vendor commerce platform built with microservices,
                                serverless infrastructure, and cloud-native deployment architecture.
                            </p>

                            <!-- Tech Stack -->
                            <div class="flex flex-wrap gap-2 mb-5">

                                <span
                                    class="px-3 py-1 rounded-sm text-xs font-medium bg-indigo-500/10 text-indigo-300 border border-indigo-500/20">
                                    Vue.js
                                </span>

                                <span
                                    class="px-3 py-1 rounded-sm text-xs font-medium bg-green-500/10 text-green-300 border border-green-500/20">
                                    Node.js
                                </span>

                                <span
                                    class="px-3 py-1 rounded-sm text-xs font-medium bg-cyan-500/10 text-cyan-300 border border-cyan-500/20">
                                    PostgreSQL
                                </span>

                            </div>

                            <!-- Footer -->
                            <div class="flex items-center justify-between pt-4 border-t border-slate-800">

                                <div class="flex items-center gap-2 text-slate-400 text-sm">

                                    <svg xmlns="http://www.w3.org/2000/svg" class="w-4 h-4" fill="none"
                                        viewBox="0 0 24 24" stroke="currentColor">

                                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                            d="M9 12h6m-6 4h6m2 5H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z" />
                                    </svg>

                                    Portfolio Project

                                </div>

                                <a href="#"
                                    class="text-indigo-500 text-sm font-medium hover:text-indigo-300 transition-colors">
                                    Link Website →
                                </a>

                            </div>

                        </div>

                    </div>
                    <div
                        class="group relative overflow-hidden rounded-3xl border-2 border-slate-800/50 bg-slate-900/60 backdrop-blur-xl transition-all duration-500 hover:-translate-y-3 hover:border-indigo-500/30">

                        <!-- Glow Effect -->
                        <div
                            class="absolute inset-0 bg-gradient-to-br from-indigo-500/5 via-transparent to-purple-500/5 opacity-0 group-hover:opacity-100 transition-opacity duration-500">
                        </div>

                        <!-- Image Section -->
                        <div class="relative h-64 overflow-hidden">

                            <!-- Image -->
                            <img src="@/assets/photo/e-commerce.png" alt="E-Commerce Architecture Platform"
                                class="w-full h-full object-cover object-top transition-transform duration-700 group-hover:scale-110">

                            <!-- Overlay -->
                            <div
                                class="absolute inset-0 -z-10 bg-gradient-to-br from-indigo-500/10 via-transparent to-purple-500/10">
                            </div>

                            <!-- Live Badge -->
                            <div class="absolute top-4 left-4 z-20">

                                <span
                                    class="inline-flex items-center gap-2 px-3 py-1.5 rounded-full bg-emerald-500/15 backdrop-blur-md border border-emerald-500/30 text-emerald-400 text-xs font-semibold">

                                    <span class="w-2 h-2 rounded-full bg-emerald-400 animate-pulse"></span>

                                    Live Project

                                </span>

                            </div>

                            <!-- Featured Badge -->
                            <div class="absolute top-4 right-4 z-20">

                                <span
                                    class="px-3 py-1 rounded-full bg-indigo-500/15 backdrop-blur-md border border-indigo-500/30 text-indigo-400 text-xs font-semibold">

                                    Featured

                                </span>

                            </div>

                            <!-- Bottom Info -->
                            <div class="absolute bottom-4 left-4 right-4 z-20">

                                <div class="flex items-center justify-between">

                                    <span
                                        class="px-3 py-2 rounded-full bg-slate-900/10 backdrop-blur-md text-indigo-500 text-xs uppercase tracking-wider font-semibold">
                                        Web Application
                                    </span>

                                    <button
                                        class="w-10 h-10 rounded-xl bg-white/10 backdrop-blur-md border border-white/10 text-white flex items-center justify-center opacity-0 group-hover:opacity-100 transition-all duration-300">

                                        <svg xmlns="http://www.w3.org/2000/svg" class="w-5 h-5" fill="none"
                                            viewBox="0 0 24 24" stroke="currentColor">

                                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                                d="M14 3h7m0 0v7m0-7L10 14" />

                                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                                d="M5 5v14h14" />

                                        </svg>

                                    </button>

                                </div>

                            </div>

                        </div>

                        <!-- Content -->
                        <div class="relative p-6">

                            <h3 class="text-xl font-bold text-white mb-3 group-hover:text-indigo-400 transition-colors">
                                E-Commerce Architecture Platform
                            </h3>

                            <p class="text-slate-400 text-sm leading-relaxed mb-5">
                                A scalable multi-vendor commerce platform built with microservices,
                                serverless infrastructure, and cloud-native deployment architecture.
                            </p>

                            <!-- Tech Stack -->
                            <div class="flex flex-wrap gap-2 mb-5">

                                <span
                                    class="px-3 py-1 rounded-sm text-xs font-medium bg-indigo-500/10 text-indigo-300 border border-indigo-500/20">
                                    Vue.js
                                </span>

                                <span
                                    class="px-3 py-1 rounded-sm text-xs font-medium bg-green-500/10 text-green-300 border border-green-500/20">
                                    Node.js
                                </span>

                                <span
                                    class="px-3 py-1 rounded-sm text-xs font-medium bg-cyan-500/10 text-cyan-300 border border-cyan-500/20">
                                    PostgreSQL
                                </span>

                            </div>

                            <!-- Footer -->
                            <div class="flex items-center justify-between pt-4 border-t border-slate-800">

                                <div class="flex items-center gap-2 text-slate-400 text-sm">

                                    <svg xmlns="http://www.w3.org/2000/svg" class="w-4 h-4" fill="none"
                                        viewBox="0 0 24 24" stroke="currentColor">

                                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                            d="M9 12h6m-6 4h6m2 5H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z" />
                                    </svg>

                                    Portfolio Project

                                </div>

                                <a href="#"
                                    class="text-indigo-500 text-sm font-medium hover:text-indigo-300 transition-colors">
                                    Link Website →
                                </a>

                            </div>

                        </div>

                    </div>

                </div>

                <!-- Load More Button -->
                <div class="mt-12 text-center">
                    <button
                        class="px-8 py-3 rounded-xl border border-slate-800 text-slate-300 hover:border-indigo-500 hover:text-indigo-400 transition-all duration-300 hover:shadow-lg hover:shadow-indigo-500/10">
                        Load More Projects
                    </button>
                </div>
            </div>
        </section>

        <section id="experience" class="py-24 border-t border-slate-900/60 bg-slate-950/50">
            <div class="max-w-4xl mx-auto px-6">
                <div class="text-center mb-16">
                    <p class="text-indigo-400 text-sm font-semibold uppercase tracking-wider mb-2">04. Journey</p>
                    <h3 class="text-3xl font-bold text-white">Work Experience</h3>
                </div>

                <div
                    class="space-y-12 relative before:absolute before:inset-0 before:left-4 md:before:left-1/2 before:w-0.5 before:bg-slate-900">
                    <div
                        class="relative flex flex-col md:flex-row md:justify-between items-start md:items-center group">
                        <div
                            class="absolute left-4 md:left-1/2 w-4 h-4 rounded-full bg-indigo-600 border-4 border-slate-950 transform -translate-x-[7px] md:-translate-x-2 z-10">
                        </div>
                        <div class="w-full md:w-[45%] pl-12 md:pl-0 md:text-right">
                            <span class="text-xs font-semibold uppercase tracking-wider text-indigo-400">2024 -
                                Present</span>
                            <h4 class="text-lg font-bold text-white mt-1">Senior Full Stack Engineer</h4>
                            <p class="text-sm text-slate-400 font-medium">Tech Innovations Studio</p>
                            <p class="text-sm text-slate-500 mt-2">Spearheaded transition into composable modular
                                micro-frontends, increasing application efficiency significantly.</p>
                        </div>
                        <div class="hidden md:block w-[45%]"></div>
                    </div>

                    <div
                        class="relative flex flex-col md:flex-row md:justify-between items-start md:items-center group">
                        <div
                            class="absolute left-4 md:left-1/2 w-4 h-4 rounded-full bg-slate-800 border-4 border-slate-950 transform -translate-x-[7px] md:-translate-x-2 z-10 group-hover:bg-indigo-500 transition">
                        </div>
                        <div class="hidden md:block w-[45%]"></div>
                        <div class="w-full md:w-[45%] pl-12 md:pl-8">
                            <span class="text-xs font-semibold uppercase tracking-wider text-slate-500">2022 -
                                2024</span>
                            <h4 class="text-lg font-bold text-white mt-1">Full Stack Developer</h4>
                            <p class="text-sm text-slate-400 font-medium">Quantum Web Apps</p>
                            <p class="text-sm text-slate-500 mt-2">Developed core web features utilizing Node.js backend
                                networks alongside automated test assertions.</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <section id="services" class="py-24 border-t border-slate-900/60">
            <div class="max-w-7xl mx-auto px-6">
                <div class="text-center max-w-xl mx-auto mb-16">
                    <p class="text-indigo-400 text-sm font-semibold uppercase tracking-wider mb-2">05. Offerings</p>
                    <h3 class="text-3xl font-bold text-white">What I Provide</h3>
                </div>

                <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                    <div
                        class="p-8 rounded-2xl bg-slate-900/20 border border-slate-900 hover:bg-slate-900/40 transition">
                        <div
                            class="w-12 h-12 rounded-xl bg-indigo-600/10 text-indigo-400 flex items-center justify-center font-bold mb-6">
                            &lt;/&gt;
                        </div>
                        <h4 class="text-lg font-bold text-white mb-2">Web Application Development</h4>
                        <p class="text-sm text-slate-400 leading-relaxed">End-to-end engineered dynamic websites,
                            constructed carefully to support secure architectures and fluid user journeys.</p>
                    </div>

                    <div
                        class="p-8 rounded-2xl bg-slate-900/20 border border-slate-900 hover:bg-slate-900/40 transition">
                        <div
                            class="w-12 h-12 rounded-xl bg-indigo-600/10 text-indigo-400 flex items-center justify-center font-bold mb-6">
                            &lrhar;
                        </div>
                        <h4 class="text-lg font-bold text-white mb-2">API Design & Integration</h4>
                        <p class="text-sm text-slate-400 leading-relaxed">Designing explicit, typed, and securely
                            fortified RESTful endpoint patterns or flexible GraphQL endpoints.</p>
                    </div>

                    <div
                        class="p-8 rounded-2xl bg-slate-900/20 border border-slate-900 hover:bg-slate-900/40 transition">
                        <div
                            class="w-12 h-12 rounded-xl bg-indigo-600/10 text-indigo-400 flex items-center justify-center font-bold mb-6">
                            &ctdot;
                        </div>
                        <h4 class="text-lg font-bold text-white mb-2">Performance Optimization</h4>
                        <p class="text-sm text-slate-400 leading-relaxed">Auditing server loads, static structures,
                            query logic, and network payloads to achieve lightning-fast paint scores.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- ================= CONTACT SECTION ================= -->
        <section id="contact"
            class="py-24 border-t border-slate-900/60 bg-gradient-to-b from-slate-950 to-slate-900 relative">
            <!-- Decorative background blob -->
            <div
                class="absolute bottom-0 right-0 w-96 h-96 bg-indigo-600/5 blur-[120px] rounded-full pointer-events-none">
            </div>

            <div class="max-w-7xl mx-auto px-6 relative z-10">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-start">

                    <!-- Left Side: Contact Info & Social Cards -->
                    <div class="lg:col-span-5 space-y-8">
                        <div>
                            <p class="text-indigo-400 text-sm font-semibold uppercase tracking-wider mb-2">06. Contact
                            </p>
                            <h3 class="text-3xl sm:text-4xl font-bold text-white tracking-tight">Let's create something
                                exceptional together</h3>
                            <p class="text-slate-400 leading-relaxed mt-4">
                                Have an upcoming project concept or looking to expand your technical engineering unit?
                                Reach out through these communication channels.
                            </p>
                        </div>

                        <!-- Quick Chat Channels (Telegram & Messenger) -->
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                            <!-- Telegram Card -->
                            <a href="https://t.me/your_username" target="_blank"
                                class="flex items-center gap-4 p-4 rounded-2xl bg-slate-900/40 border border-slate-800 hover:border-sky-500/40 hover:bg-slate-900/80 transition-all duration-300 group shadow-lg">
                                <div
                                    class="w-12 h-12 rounded-xl bg-sky-500/10 text-sky-400 flex items-center justify-center font-bold text-xl group-hover:scale-110 transition-transform">
                                    <!-- Telegram Icon SVG -->
                                    <svg xmlns="http://www.w3.org/2000/svg" class="w-6 h-6" fill="currentColor"
                                        viewBox="0 0 24 24">
                                        <path
                                            d="M11.944 0C5.344 0 0 5.344 0 11.944c0 5.622 3.88 10.331 9.094 11.645.106.019.26-.04.29-.163.14-.565.414-1.803.565-2.383l.01-.038c.01-.03.007-.063-.01-.089-.028-.043-.377-.45-.632-.756-2.584-3.11-1.353-8.082 2.378-9.45 4.67-1.71 9.47 1.54 9.17 6.45-.19 3.102-1.892 5.565-4.526 6.305-.592.166-.994-.13-.994-.745v-2.072c0-.662-.244-1.144-.658-1.442 2.534-.287 5.195-1.251 5.195-5.698 0-1.265-.45-2.298-1.192-3.113.114-.29.516-1.468-.114-3.067 0 0-.97-.311-3.18 1.187a10.982 10.982 0 00-5.8 0c-2.21-1.498-3.181-1.187-3.181-1.187-.63 1.599-.228 2.778-.114 3.067-.742.815-1.192 1.848-1.192 3.113 0 4.437 2.651 5.411 5.185 5.698-.33.288-.632.793-.734 1.542-.66.297-2.333.805-3.363-.96-.65-1.127-1.782-1.218-1.782-1.218-1.139-.015-.08.711-.08.711.763.357 1.294 1.733 1.294 1.733.685 2.083 2.766 1.383 3.42 1.059v1.205c0 .487-.234.88-.732 1.015-4.225-1.341-7.268-5.308-7.268-9.972C.5 5.65 5.65.5 12 .5"
                                            class="hidden" /> <!-- fallback base -->
                                        <path
                                            d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm4.64 6.8c-.15 1.58-.8 5.42-1.13 7.19-.14.75-.42 1-.68 1.03-.58.05-1.02-.38-1.58-.75-.88-.58-1.38-.94-2.23-1.5-1-.65-.35-1 .22-1.58.15-.15 2.71-2.48 2.76-2.69.01-.03.01-.14-.07-.2-.08-.06-.19-.04-.27-.02-.12.02-1.96 1.24-5.54 3.65-.52.36-.99.53-1.41.52-.46-.01-1.36-.26-2.02-.48-.82-.27-1.47-.41-1.42-.87.03-.24.35-.49.97-.75 3.81-1.65 6.35-2.74 7.62-3.26 3.63-1.48 4.38-1.74 4.87-1.75.11 0 .35.03.51.16.13.11.17.26.19.37.02.1.03.3.01.51z" />
                                    </svg>
                                </div>
                                <div>
                                    <h4 class="text-white text-sm font-bold">Telegram</h4>
                                    <p class="text-xs text-slate-500 mt-0.5">Chat Directly</p>
                                </div>
                            </a>

                            <!-- Messenger Card -->
                            <a href="https://m.me/your_username" target="_blank"
                                class="flex items-center gap-4 p-4 rounded-2xl bg-slate-900/40 border border-slate-800 hover:border-blue-500/40 hover:bg-slate-900/80 transition-all duration-300 group shadow-lg">
                                <div
                                    class="w-12 h-12 rounded-xl bg-blue-500/10 text-blue-400 flex items-center justify-center font-bold text-xl group-hover:scale-110 transition-transform">
                                    <!-- Messenger Icon SVG -->
                                    <svg xmlns="http://www.w3.org/2000/svg" class="w-6 h-6" fill="currentColor"
                                        viewBox="0 0 24 24">
                                        <path
                                            d="M12 2C6.36 2 2 6.14 2 11.24c0 2.91 1.42 5.5 3.66 7.17.19.14.31.36.31.6l-.01 1.86c0 .4.41.69.77.51l2.08-.99c.17-.08.36-.09.54-.04 1.4.39 2.89.61 4.43.61 5.64 0 10-4.14 10-9.24C22 6.14 17.64 2 12 2zm1.03 11.51l-2.06-2.2c-.27-.29-.72-.29-.99 0l-2.73 2.9c-.44.47-1.12-.13-.73-.64l2.91-3.82c.27-.35.8-.35 1.07 0l2.06 2.2c.27.29.72.29.99 0l2.73-2.9c.44-.47 1.12.13.73.64l-2.91 3.82c-.27.35-.8.35-1.07 0z" />
                                    </svg>
                                </div>
                                <div>
                                    <h4 class="text-white text-sm font-bold">Messenger</h4>
                                    <p class="text-xs text-slate-500 mt-0.5">Facebook Chat</p>
                                </div>
                            </a>
                        </div>

                        <!-- Traditional Contact Details & Social Icons -->
                        <div class="p-6 rounded-2xl bg-slate-900/20 border border-slate-900/80 space-y-4">
                            <div class="flex items-center gap-4 text-slate-300 text-sm">
                                <span
                                    class="w-10 h-10 rounded-xl bg-slate-900 border border-slate-800 flex items-center justify-center text-indigo-400 font-bold">&#9993;</span>
                                <div>
                                    <p class="text-xs text-slate-500 mb-1">Email Address</p>
                                    <p class="font-medium text-slate-200">Pisethblogger@gmail.com</p>
                                </div>
                            </div>
                            <div class="flex items-center gap-4 text-slate-300 text-sm">
                                <span
                                    class="w-10 h-10 rounded-xl bg-slate-900 border border-slate-800 flex items-center justify-center text-indigo-400 font-bold">&#128222;</span>
                                <div>
                                    <p class="text-xs text-slate-500 mb-1">Phone Number</p>
                                    <p class="font-medium text-slate-200">+855 979 808 659</p>
                                </div>
                            </div>

                            <!-- Social Media Icons Row -->
                            <div class="pt-4 border-t border-slate-900 flex items-center gap-3">
                                <a href="#"
                                    class="w-10 h-10 rounded-xl border border-slate-800 bg-slate-900/50 flex items-center justify-center text-slate-400 hover:border-indigo-500 hover:text-white transition-all duration-200"
                                    title="LinkedIn">
                                    <svg xmlns="http://www.w3.org/2000/svg" class="w-5 h-5" fill="currentColor"
                                        viewBox="0 0 24 24">
                                        <path
                                            d="M19 3a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h14m-.5 15.5v-5.3a3.26 3.26 0 0 0-3.26-3.26c-.85 0-1.84.52-2.32 1.3v-1.11h-2.79v8.37h2.79v-4.93c0-.77.62-1.4 1.39-1.4a1.4 1.4 0 0 1 1.4 1.4v4.93h2.79M6.88 8.56a1.68 1.68 0 0 0 1.68-1.68c0-.93-.75-1.69-1.68-1.69a1.69 1.69 0 0 0-1.69 1.69c0 .93.76 1.68 1.69 1.68m1.39 9.94v-8.37H5.5v8.37h2.77z" />
                                    </svg>
                                </a>
                                <a href="#"
                                    class="w-10 h-10 rounded-xl border border-slate-800 bg-slate-900/50 flex items-center justify-center text-slate-400 hover:border-indigo-500 hover:text-white transition-all duration-200"
                                    title="GitHub">
                                    <svg xmlns="http://www.w3.org/2000/svg" class="w-5 h-5" fill="currentColor"
                                        viewBox="0 0 24 24">
                                        <path
                                            d="M12 .297c-6.63 0-12 5.373-12 12 0 5.303 3.438 9.8 8.205 11.385.6.113.82-.258.82-.577 0-.285-.01-1.04-.015-2.04-3.338.724-4.042-1.61-4.042-1.61C4.422 18.07 3.633 17.7 3.633 17.7c-1.087-.744.084-.729.084-.729 1.205.084 1.838 1.236 1.838 1.236 1.07 1.835 2.809 1.305 3.495.998.108-.776.417-1.305.76-1.605-2.665-.3-5.466-1.332-5.466-5.93 0-1.31.465-2.38 1.235-3.22-.135-.303-.54-1.523.105-3.176 0 0 1.005-.322 3.3 1.23.96-.267 1.98-.399 3-.405 1.02.006 2.04.138 3 .405 2.28-1.552 3.285-1.23 3.285-1.23.645 1.653.24 2.873.12 3.176.765.84 1.23 1.91 1.23 3.22 0 4.61-2.805 5.625-5.475 5.92.42.36.81 1.096.81 2.22 0 1.606-.015 2.896-.015 3.286 0 .315.21.69.825.57C20.565 22.092 24 17.592 24 12.297c0-6.627-5.373-12-12-12" />
                                    </svg>
                                </a>
                            </div>
                        </div>
                    </div>

                    <!-- Right Side: Email Form Portal -->
                    <div
                        class="lg:col-span-7 bg-slate-950/40 backdrop-blur-md border border-slate-800/80 p-8 rounded-3xl shadow-xl relative overflow-hidden group">
                        <!-- Card Border Highlight Layer -->
                        <div
                            class="absolute inset-0 border border-indigo-500/10 rounded-3xl pointer-events-none group-hover:border-indigo-500/20 transition-colors duration-300">
                        </div>

                        <form class="space-y-6 relative z-10">
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-6">
                                <div>
                                    <label
                                        class="block text-xs font-semibold text-slate-400 uppercase tracking-wide mb-2">Your
                                        Name</label>
                                    <input type="text" placeholder="Username" class="w-full px-4 py-3 rounded-xl border-2
                                        bg-slate-900/60
                                        border border-slate-800
                                        text-white
                                        placeholder-slate-600

                                        focus:outline-none
                                        focus:border-2
                                        focus:border-indigo-500
                                        focus:ring-indigo-500/20

                                        duration-300" />
                                </div>
                                <div>
                                    <label
                                        class="block text-xs font-semibold text-slate-400 uppercase tracking-wide mb-2">Email
                                        Address</label>
                                    <input type="email" placeholder="Email" class="w-full px-4 py-3 rounded-xl border-2
                                        bg-slate-900/60
                                        border border-slate-800
                                        text-white
                                        placeholder-slate-600

                                        focus:outline-none
                                        focus:border-2
                                        focus:border-indigo-500
                                        focus:ring-indigo-500/20

                                        duration-300" />
                                </div>
                            </div>
                            <div>
                                <label
                                    class="block text-xs font-semibold text-slate-400 uppercase tracking-wide mb-2">Message</label>
                                <textarea rows="8" placeholder="Tell me about your project details..." class="w-full px-4 py-3 rounded-xl bg-slate-900/60 border-2 border-slate-800 text-white placeholder-slate-600   focus:outline-none
                                        focus:border-2
                                        focus:border-indigo-500
                                        focus:ring-indigo-500/20 resize-y">
                                </textarea>
                            </div>
                            <button
                                class="w-full py-4 rounded-xl bg-indigo-600 text-white font-medium hover:bg-indigo-700 transition shadow-lg shadow-indigo-600/20 active:scale-[0.99] duration-150">
                                Send Message
                            </button>
                        </form>
                    </div>

                </div>
            </div>
        </section>

        <footer class="border-t border-slate-900/80 py-8 bg-slate-950 text-slate-500 text-center text-sm">
            <div class="max-w-7xl mx-auto px-6 flex flex-col sm:flex-row items-center justify-between gap-4">
                <p>&copy; 2026 Chhun Heng. All rights reserved.</p>
                <div class="flex gap-6">
                    <a href="#" class="hover:text-slate-300 transition">GitHub</a>
                    <a href="#" class="hover:text-slate-300 transition">LinkedIn</a>
                    <a href="#" class="hover:text-slate-300 transition">Twitter</a>
                </div>
            </div>
        </footer>

    </main>

</template>

<style>

@keyframes floatAvatar {

    0%,
    100% {
        transform: translateY(0px);
    }

    50% {
        transform: translateY(-0px);
    }
}

@keyframes rotateRing {
    from {
        transform: rotate(0deg);
    }

    to {
        transform: rotate(360deg);
    }
}

@keyframes glowPulse {

    0%,
    100% {
        opacity: .5;
        transform: scale(0);
    }

    50% {
        opacity: .9;
        transform: scale(0);
    }
}

@keyframes gradient {
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

/* Card Framework */
@keyframes float {

    0%,
    100% {
        transform: translateY(0px);
    }

    50% {
        transform: translateY(-12px);
    }
}

@keyframes glow {

    0%,
    100% {
        box-shadow: 0 0 15px rgba(99, 102, 241, 0.15);
    }

    50% {
        box-shadow: 0 0 35px rgba(99, 102, 241, 0.35);
    }
}

@keyframes swing {
    0% {
        transform: rotate(0deg);
    }

    20% {
        transform: rotate(-8deg);
    }

    40% {
        transform: rotate(8deg);
    }

    60% {
        transform: rotate(-4deg);
    }

    80% {
        transform: rotate(4deg);
    }

    100% {
        transform: rotate(0deg);
    }
}

@keyframes gradient {
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