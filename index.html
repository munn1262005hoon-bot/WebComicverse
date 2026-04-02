<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ComicVerse - Thế giới truyện tranh</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" xintegrity="sha512-iecdLmaskl7CVkqkXNQ/ZH/XLlvWZOJyj7Yy7tcenmpD1ypASozpmT/E0iPtmFIB46ZmdtAc9eNBvH0H/ZpiBw==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <style>
        :root {
            --primary-dark: #898AC4;
            --primary-medium: #A2AADB;
            --primary-light: #C0C9EE;
            --background: #FFF2E0;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: var(--background);
        }

        .comic-card {
            transition: all 0.3s ease;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            background: white;
        }

        .comic-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 15px rgba(0, 0, 0, 0.2);
        }

        .comic-tag {
            background-color: var(--primary-light);
        }

        .hero-section {
            background: linear-gradient(135deg, var(--primary-dark) 0%, var(--primary-medium) 100%);
        }

        .navbar {
            background-color: var(--primary-dark);
        }

        .pagination-container {
            gap: 0.5rem;
        }

        .pagination-btn {
            background-color: var(--primary-light);
            min-width: 2.5rem;
            height: 2.5rem;
        }

        .pagination-btn.active {
            background-color: var(--primary-dark);
            color: white;
        }

        .reading-page-container {
            max-width: 1200px;
        }

        .comment-avatar {
            width: 3rem;
            height: 3rem;
        }

        .page-turn-btn {
            position: fixed;
            top: 50%;
            transform: translateY(-50%);
            width: 50px;
            height: 50px;
            border-radius: 50%;
            background-color: rgba(162, 170, 219, 0.8);
            display: flex;
            align-items: center;
            justify-content: center;
            cursor: pointer;
            z-index: 100;
            transition: all 0.3s ease;
        }

        .page-turn-btn:hover {
            background-color: rgba(137, 138, 196, 0.9);
        }

        .prev-btn {
            left: 1rem;
        }

        .next-btn {
            right: 1rem;
        }

        @media (max-width: 768px) {
            .page-turn-btn {
                width: 40px;
                height: 40px;
            }

            .comic-image-container {
                padding: 0.5rem;
            }
        }

        /* Custom scrollbar */
        ::-webkit-scrollbar {
            width: 8px;
        }

        ::-webkit-scrollbar-track {
            background: #f1f1f1;
        }

        ::-webkit-scrollbar-thumb {
            background: var(--primary-medium);
            border-radius: 4px;
        }

        ::-webkit-scrollbar-thumb:hover {
            background: var(--primary-dark);
        }

        /* Animation */
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        .animate-fade-in {
            animation: fadeIn 0.5s ease-in-out;
        }

        /* Tooltip */
        .tooltip {
            position: relative;
            display: inline-block;
        }

        .tooltip .tooltiptext {
            visibility: hidden;
            width: 120px;
            background-color: var(--primary-dark);
            color: #fff;
            text-align: center;
            border-radius: 6px;
            padding: 5px;
            position: absolute;
            z-index: 1;
            bottom: 125%;
            left: 50%;
            transform: translateX(-50%);
            opacity: 0;
            transition: opacity 0.3s;
        }

        .tooltip:hover .tooltiptext {
            visibility: visible;
            opacity: 1;
        }

        .loading-spinner {
            border: 4px solid rgba(0, 0, 0, 0.1);
            border-left-color: #898AC4;
            border-radius: 50%;
            width: 24px;
            height: 24px;
            animation: spin 1s linear infinite;
            display: inline-block;
            vertical-align: middle;
        }

        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }
        
        /* Modal styles */
        .modal-overlay {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.7);
            display: none; /* Hidden by default */
            justify-content: center;
            align-items: center;
            z-index: 1000;
        }
        
        .modal-content {
            background-color: #fff;
            padding: 2rem;
            border-radius: 0.5rem;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);
            width: 90%;
            max-width: 400px;
            position: relative;
        }
        
        .modal-close-btn {
            position: absolute;
            top: 1rem;
            right: 1rem;
            color: #6B7280; /* gray-500 */
            transition: color 0.2s ease-in-out;
        }
        .modal-close-btn:hover {
            color: #1F2937; /* gray-800 */
        }
    </style>
</head>
<body class="min-h-screen">
    <!-- Navigation -->
    <nav class="navbar sticky top-0 z-50 shadow-md text-white">
        <div class="container mx-auto px-4 py-3 flex justify-between items-center">
            <a href="#home" class="text-2xl font-bold flex items-center" id="logo">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 mr-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 3v2m6-2v2M9 19v2m6-2v2M5 9h14M5 15h14m0-12H5a2 2 0 00-2 2v12a2 2 0 002 2h14a2 2 0 002-2V5a2 2 0 00-2-2z" />
                </svg>
                ComicVerse
            </a>

            <div class="hidden md:flex space-x-6">
                <a href="#home" class="hover:text-gray-200">Trang chủ</a>
                <a href="#comics" class="hover:text-gray-200">Thể loại</a>
                <a href="#reading" class="hover:text-gray-200">Đọc truyện</a>
                <a href="#community" class="hover:text-gray-200">Cộng đồng</a>
            </div>

            <div class="flex items-center space-x-4">
                <div id="search-toggle" class="cursor-pointer">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z" />
                    </svg>
                </div>
                <!-- Login/Register Buttons -->
                <button onclick="showModal('login-modal')" class="hidden md:block bg-purple-500 text-white px-4 py-2 rounded-full font-semibold hover:bg-purple-600 transition duration-200">Đăng nhập</button>
                <button onclick="showModal('register-modal')" class="hidden md:block bg-purple-500 text-white px-4 py-2 rounded-full font-semibold hover:bg-purple-600 transition duration-200">Đăng ký</button>

                <button id="mobile-menu-button" class="md:hidden">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
                    </svg>
                </button>
            </div>
        </div>

        <!-- Mobile menu -->
        <div id="mobile-menu" class="hidden md:hidden bg-gray-800 text-white px-4 py-2">
            <a href="#home" class="block py-2 hover:bg-gray-700 px-2 rounded">Trang chủ</a>
            <a href="#comics" class="block py-2 hover:bg-gray-700 px-2 rounded">Thể loại</a>
            <a href="#reading" class="block py-2 hover:bg-gray-700 px-2 rounded">Đọc truyện</a>
            <a href="#community" class="block py-2 hover:bg-gray-700 px-2 rounded">Cộng đồng</a>
            <button onclick="showModal('login-modal')" class="block w-full text-left py-2 hover:bg-gray-700 px-2 rounded mt-2">Đăng nhập</button>
            <button onclick="showModal('register-modal')" class="block w-full text-left py-2 hover:bg-gray-700 px-2 rounded">Đăng ký</button>
        </div>
    </nav>

    <!-- Search Bar -->
    <div id="search-bar" class="hidden bg-white shadow-md py-3">
        <div class="container mx-auto px-4">
            <div class="flex items-center">
                <input type="text" id="search-input" placeholder="Tìm kiếm truyện, tác giả hoặc thể loại..." class="w-full px-4 py-2 rounded-l-full border border-gray-300 focus:outline-none focus:ring-2 focus:ring-purple-500">
                <button id="search-button" class="bg-purple-500 hover:bg-purple-600 text-white px-6 py-2 rounded-r-full transition duration-200 flex items-center">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 mr-1" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z" />
                    </svg>
                    Tìm kiếm
                </button>
            </div>
            <div class="flex flex-wrap mt-2">
                <span class="text-sm text-gray-600 mr-2">Tìm nhanh:</span>
                <button class="search-tag bg-gray-100 hover:bg-gray-200 text-gray-800 text-xs px-2 py-1 rounded-full mr-1 mb-1">Hành động</button>
                <button class="search-tag bg-gray-100 hover:bg-gray-200 text-gray-800 text-xs px-2 py-1 rounded-full mr-1 mb-1">Tình cảm</button>
                <button class="search-tag bg-gray-100 hover:bg-gray-200 text-gray-800 text-xs px-2 py-1 rounded-full mr-1 mb-1">Học đường</button>
                <button class="search-tag bg-gray-100 hover:bg-gray-200 text-gray-800 text-xs px-2 py-1 rounded-full mr-1 mb-1">Phiêu lưu</button>
                <button class="search-tag bg-gray-100 hover:bg-gray-200 text-gray-800 text-xs px-2 py-1 rounded-full mr-1 mb-1">Siêu nhiên</button>
            </div>
        </div>
    </div>

    <!-- Hero Section -->
    <section id="home" class="hero-section text-white py-16">
        <div class="container mx-auto px-4">
            <div class="flex flex-col md:flex-row items-center">
                <div class="md:w-1/2 mb-8 md:mb-0">
                    <h1 class="text-4xl md:text-5xl font-bold mb-4">Khám phá thế giới truyện tranh</h1>
                    <p class="text-xl mb-6">Hàng ngàn truyện tranh đa dạng thể loại đang chờ bạn khám phá!</p>
                    <button id="explore-btn" class="bg-white text-purple-600 hover:bg-gray-100 px-6 py-3 rounded-full font-semibold shadow-lg transition duration-200">
                        Bắt đầu ngay
                    </button>
                </div>
                <div class="md:w-1/2 flex justify-center">
                    <div class="relative w-full max-w-lg">
                        <img src="https://kilala.vn/data/uploads/2025/1747800054-manga-hai-huoc.png" alt="" class="rounded-lg shadow-xl animate-fade-in">
                        <div class="absolute -bottom-4 -right-4 bg-yellow-400 text-purple-800 px-3 py-1 rounded-full font-bold text-sm shadow-md">
                            NEW CHAPTERS
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Main Content -->
    <main class="container mx-auto px-4 py-8">
        <!-- Featured Comics -->
        <section class="mb-12">
            <h2 class="text-2xl font-bold mb-6 flex items-center">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 mr-2 text-purple-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M11.049 2.927c.3-.921 1.603-.921 1.902 0l1.519 4.674a1 1 0 00.95.69h4.915c.969 0 1.371 1.24.588 1.81l-3.976 2.888a1 1 0 00-.363 1.118l1.518 4.674c.3.922-.755 1.688-1.538 1.118l-3.976-2.888a1 1 0 00-1.176 0l-3.976 2.888c-.783.57-1.838-.197-1.538-1.118l1.518-4.674a1 1 0 00-.363-1.118l-3.976-2.888c-.784-.57-.38-1.81.588-1.81h4.914a1 1 0 00.951-.69l1.519-4.674z" />
                </svg>
                Truyện nổi bật
            </h2>

            <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-5 gap-4" id="featured-comics-grid">
                <!-- Comic Cards will be dynamically loaded here -->
            </div>
        </section>

        <!-- Comic Categories -->
        <section id="comics" class="mb-12">
            <h2 class="text-2xl font-bold mb-6 flex items-center">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 mr-2 text-purple-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 3v4M3 5h4M6 17v4m-2-2h4m5-16l2.286 6.857L21 12l-5.714 2.143L13 21l-2.286-6.857L5 12l5.714-2.143L13 3z" />
                </svg>
                Thể loại truyện
            </h2>

            <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-5 gap-4" id="category-cards-container">
                <div class="category-card bg-white rounded-lg p-4 shadow-md hover:shadow-lg transition duration-200 cursor-pointer flex flex-col items-center" data-genre="all">
                    <div class="w-16 h-16 rounded-full bg-purple-100 mb-3 flex items-center justify-center">
                        <i class="fas fa-book text-purple-500 text-3xl"></i>
                    </div>
                    <h3 class="font-semibold text-center">Tất cả</h3>
                    <span class="text-xs text-gray-500 mt-1">Xem tất cả</span>
                </div>
                <div class="category-card bg-white rounded-lg p-4 shadow-md hover:shadow-lg transition duration-200 cursor-pointer flex flex-col items-center" data-genre="action">
                    <div class="w-16 h-16 rounded-full bg-purple-100 mb-3 flex items-center justify-center">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-purple-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z" />
                        </svg>
                    </div>
                    <h3 class="font-semibold text-center">Hành động</h3>
                    <span class="text-xs text-gray-500 mt-1">452 truyện</span>
                </div>

                <div class="category-card bg-white rounded-lg p-4 shadow-md hover:shadow-lg transition duration-200 cursor-pointer flex flex-col items-center" data-genre="romance">
                    <div class="w-16 h-16 rounded-full bg-purple-100 mb-3 flex items-center justify-center">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-purple-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 4.354a4 4 0 110 5.292M15 21H3v-1a6 6 0 0112 0v1zm0 0h6v-1a6 6 0 00-9-5.197M13 7a4 4 0 11-8 0 4 4 0 018 0z" />
                        </svg>
                    </div>
                    <h3 class="font-semibold text-center">Tình cảm</h3>
                    <span class="text-xs text-gray-500 mt-1">367 truyện</span>
                </div>

                <div class="category-card bg-white rounded-lg p-4 shadow-md hover:shadow-lg transition duration-200 cursor-pointer flex flex-col items-center" data-genre="school">
                    <div class="w-16 h-16 rounded-full bg-purple-100 mb-3 flex items-center justify-center">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-purple-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6.253v13m0-13C10.832 5.477 9.246 5 7.5 5S4.168 5.477 3 6.253v13C4.168 18.477 5.754 18 7.5 18s3.332.477 4.5 1.253m0-13C13.168 5.477 14.754 5 16.5 5c1.747 0 3.332.477 4.5 1.253v13C19.832 18.477 18.247 18 16.5 18c-1.746 0-3.332.477-4.5 1.253" />
                        </svg>
                    </div>
                    <h3 class="font-semibold text-center">Học đường</h3>
                    <span class="text-xs text-gray-500 mt-1">289 truyện</span>
                </div>

                <div class="category-card bg-white rounded-lg p-4 shadow-md hover:shadow-lg transition duration-200 cursor-pointer flex flex-col items-center" data-genre="adventure">
                    <div class="w-16 h-16 rounded-full bg-purple-100 mb-3 flex items-center justify-center">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-purple-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0V9a2 2 0 012-2h2a2 2 0 012 2v10m-6 0a2 2 0 002 2h2a2 2 0 002-2m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14a2 2 0 01-2 2h-2a2 2 0 01-2-2z" />
                        </svg>
                    </div>
                    <h3 class="font-semibold text-center">Phiêu lưu</h3>
                    <span class="text-xs text-gray-500 mt-1">324 truyện</span>
                </div>

                <div class="category-card bg-white rounded-lg p-4 shadow-md hover:shadow-lg transition duration-200 cursor-pointer flex flex-col items-center" data-genre="fantasy">
                    <div class="w-16 h-16 rounded-full bg-purple-100 mb-3 flex items-center justify-center">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-purple-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9.663 17h4.673M12 3v1m6.364 1.636l-.707.707M21 12h-1M4 12H3m3.343-5.657l-.707-.707m2.828 9.9a5 5 0 117.072 0l-.548.547A3.374 3.374 0 0014 18.469V19a2 2 0 11-4 0v-.531c0-.895-.356-1.754-.988-2.386l-.548-.547z" />
                        </svg>
                    </div>
                    <h3 class="font-semibold text-center">Kỳ ảo</h3>
                    <span class="text-xs text-gray-500 mt-1">413 truyện</span>
                </div>

                <div class="category-card bg-white rounded-lg p-4 shadow-md hover:shadow-lg transition duration-200 cursor-pointer flex flex-col items-center" data-genre="historical">
                    <div class="w-16 h-16 rounded-full bg-purple-100 mb-3 flex items-center justify-center">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-purple-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 7V3m8 4V3m-9 8h10M5 21h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z" />
                        </svg>
                    </div>
                    <h3 class="font-semibold text-center">Lịch sử</h3>
                    <span class="text-xs text-gray-500 mt-1">178 truyện</span>
                </div>

                <div class="category-card bg-white rounded-lg p-4 shadow-md hover:shadow-lg transition duration-200 cursor-pointer flex flex-col items-center" data-genre="detective">
                    <div class="w-16 h-16 rounded-full bg-purple-100 mb-3 flex items-center justify-center">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-purple-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19.428 15.428a2 2 0 00-1.022-.547l-2.387-.477a6 6 0 00-3.86.517l-.318.158a6 6 0 01-3.86.517L6.05 15.21a2 2 0 00-1.806.547M8 4h8l-1 1v5.172a2 2 0 00.586 1.414l5 5c1.26 1.26.367 3.414-1.415 3.414H4.828c-1.782 0-2.674-2.154-1.414-3.414l5-5A2 2 0 009 10.172V5L8 4z" />
                        </svg>
                    </div>
                    <h3 class="font-semibold text-center">Trinh thám</h3>
                    <span class="text-xs text-gray-500 mt-1">231 truyện</span>
                </div>

                <div class="category-card bg-white rounded-lg p-4 shadow-md hover:shadow-lg transition duration-200 cursor-pointer flex flex-col items-center" data-genre="comedy">
                    <div class="w-16 h-16 rounded-full bg-purple-100 mb-3 flex items-center justify-center">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-purple-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 12h.01M12 12h.01M16 12h.01M21 12c0 4.418-4.03 8-9 8a9.863 9.863 0 01-4.255-.949L3 20l1.395-3.72C3.512 15.042 3 13.574 3 12c0-4.418 4.03-8 9-8s9 3.582 9 8z" />
                        </svg>
                    </div>
                    <h3 class="font-semibold text-center">Hài hước</h3>
                    <span class="text-xs text-gray-500 mt-1">342 truyện</span>
                </div>
            </div>
        </section>

        <!-- Recently Updated -->
        <section class="mb-12">
            <h2 class="text-2xl font-bold mb-6 flex items-center">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 mr-2 text-purple-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z" />
                </svg>
                Mới cập nhật
            </h2>

            <div class="overflow-x-auto">
                <table class="min-w-full bg-white rounded-lg overflow-hidden">
                    <thead class="bg-purple-100 text-purple-800">
                        <tr>
                            <th class="py-3 px-4 text-left">Truyện</th>
                            <th class="py-3 px-4 text-left">Mới nhất</th>
                            <th class="py-3 px-4">Thể loại</th>
                            <th class="py-3 px-4">Lượt xem</th>
                            <th class="py-3 px-4"></th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr class="border-b border-gray-200 hover:bg-purple-50">
                            <td class="py-4 px-4">
                                <div class="flex items-center">
                                    <img src="https://upload.wikimedia.org/wikipedia/en/thumb/f/f4/Titans_01_2023_cover.jpg/250px-Titans_01_2023_cover.jpg" alt="" class="w-16 h-12 object-cover rounded mr-3">
                                    <div>
                                        <div class="font-medium">Teen Titans</div>
                                        <div class="text-sm text-gray-600">By Dương Huy</div>
                                    </div>
                                </div>
                            </td>
                            <td class="py-4 px-4">Ch. 45 - 2 giờ trước</td>
                            <td class="py-4 px-4 text-center">
                                <span class="comic-tag text-xs px-2 py-1 rounded-full">Hành động</span>
                            </td>
                            <td class="py-4 px-4 text-center">245K</td>
                            <td class="py-4 px-4 text-center">
                                <button class="bg-purple-500 hover:bg-purple-600 text-white px-3 py-1 rounded-full text-xs transition duration-200" onclick="openComic('teen-titans')">Đọc ngay</button>
                            </td>
                        </tr>

                        <tr class="border-b border-gray-200 hover:bg-purple-50">
                            <td class="py-4 px-4">
                                <div class="flex items-center">
                                    <img src="https://thumbs.wbm.im/pw/small/33b063d1f9e756dc92323cdbf93c85c5.jpg" alt="" class="w-16 h-12 object-cover rounded mr-3">
                                    <div>
                                        <div class="font-medium">Ngõ Nhỏ Hoa Nhài</div>
                                        <div class="text-sm text-gray-600">By Linh Chi</div>
                                    </div>
                                </div>
                            </td>
                            <td class="py-4 px-4">Ch. 12 - 5 giờ trước</td>
                            <td class="py-4 px-4 text-center">
                                <span class="comic-tag text-xs px-2 py-1 rounded-full">Tình cảm</span>
                            </td>
                            <td class="py-4 px-4 text-center">189K</td>
                            <td class="py-4 px-4 text-center">
                                <button class="bg-purple-500 hover:bg-purple-600 text-white px-3 py-1 rounded-full text-xs transition duration-200" onclick="openComic('jasmine-alley')">Đọc ngay</button>
                            </td>
                        </tr>

                        <tr class="border-b border-gray-200 hover:bg-purple-50">
                            <td class="py-4 px-4">
                                <div class="flex items-center">
                                    <img src="https://cdna.artstation.com/p/assets/images/images/034/977/170/20210219105518/smaller_square/luca-savini-artwork-fantasy.jpg?1613753719" alt="" class="w-16 h-12 object-cover rounded mr-3">
                                    <div>
                                        <div class="font-medium">Hành Trình Phương Đông</div>
                                        <div class="text-sm text-gray-600">By Team A3</div>
                                    </div>
                                </div>
                            </td>
                            <td class="py-4 px-4">Ch. 7 - Hôm nay</td>
                            <td class="py-4 px-4 text-center">
                                <span class="comic-tag text-xs px-2 py-1 rounded-full">Phiêu lưu</span>
                            </td>
                            <td class="py-4 px-4 text-center">102K</td>
                            <td class="py-4 px-4 text-center">
                                <button class="bg-purple-500 hover:bg-purple-600 text-white px-3 py-1 rounded-full text-xs transition duration-200" onclick="openComic('journey-to-the-east')">Đọc ngay</button>
                            </td>
                        </tr>

                        <tr class="border-b border-gray-200 hover:bg-purple-50">
                            <td class="py-4 px-4">
                                <div class="flex items-center">
                                    <img src="https://i.pinimg.com/736x/3d/cf/ea/3dcfeab00b7849979c34ae3f3664c5ac.jpg" alt="" class="w-16 h-12 object-cover rounded mr-3">
                                    <div>
                                        <div class="font-medium">Thời Đại Cơ Giới</div>
                                        <div class="text-sm text-gray-600">By Sci-Fi Team</div>
                                    </div>
                                </div>
                            </td>
                            <td class="py-4 px-4">Ch. 89 - Hôm qua</td>
                            <td class="py-4 px-4 text-center">
                                <span class="comic-tag text-xs px-2 py-1 rounded-full">Khoa học</span>
                            </td>
                            <td class="py-4 px-4 text-center">521K</td>
                            <td class="py-4 px-4 text-center">
                                <button class="bg-purple-500 hover:bg-purple-600 text-white px-3 py-1 rounded-full text-xs transition duration-200" onclick="openComic('mechanical-age')">Đọc ngay</button>
                            </td>
                        </tr>

                        <tr class="hover:bg-purple-50">
                            <td class="py-4 px-4">
                                <div class="flex items-center">
                                    <img src="https://i.pinimg.com/1200x/c7/81/ff/c781ffa143e3543523500aaf25d0f89b.jpg" alt="" class="w-16 h-12 object-cover rounded mr-3">
                                    <div>
                                        <div class="font-medium">Nữ Chưởng Môn</div>
                                        <div class="text-sm text-gray-600">By Minh Vũ</div>
                                    </div>
                                </div>
                            </td>
                            <td class="py-4 px-4">Ch. 34 - 3 ngày trước</td>
                            <td class="py-4 px-4 text-center">
                                <span class="comic-tag text-xs px-2 py-1 rounded-full">Cổ trang</span>
                            </td>
                            <td class="py-4 px-4 text-center">312K</td>
                            <td class="py-4 px-4 text-center">
                                <button class="bg-purple-500 hover:bg-purple-600 text-white px-3 py-1 rounded-full text-xs transition duration-200" onclick="openComic('female-master')">Đọc ngay</button>
                            </td>
                        </tr>
                    </tbody>
                </table>
            </div>
        </section>

        <!-- Popular Authors -->
        <section class="mb-12">
            <h2 class="text-2xl font-bold mb-6 flex items-center">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 mr-2 text-purple-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 7a4 4 0 11-8 0 4 4 0 018 0zM12 14a7 7 0 00-7 7h14a7 7 0 00-7-7z" />
                </svg>
                Tác giả nổi bật
            </h2>

            <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-5 gap-4">
                <div class="author-card bg-white rounded-lg p-4 shadow-md hover:shadow-lg transition duration-200 cursor-pointer flex flex-col items-center">
                    <img src="https://i.pinimg.com/736x/82/e2/e0/82e2e022bb8b8f985207d5a921c6e617.jpg" alt="" class="w-16 h-16 rounded-full mb-3 object-cover">
                    <h3 class="font-semibold text-center">Dương Huy</h3>
                    <span class="text-xs text-gray-500 mt-1">15 truyện</span>
                </div>

                <div class="author-card bg-white rounded-lg p-4 shadow-md hover:shadow-lg transition duration-200 cursor-pointer flex flex-col items-center">
                    <img src="https://i.pinimg.com/736x/1d/30/07/1d3007a726b68c10d1f0e005ac7a20bd.jpg" alt="" class="w-16 h-16 rounded-full mb-3 object-cover">
                    <h3 class="font-semibold text-center">Linh Chi</h3>
                    <span class="text-xs text-gray-500 mt-1">9 truyện</span>
                </div>

                <div class="author-card bg-white rounded-lg p-4 shadow-md hover:shadow-lg transition duration-200 cursor-pointer flex flex-col items-center">
                    <img src="https://i.pinimg.com/736x/c7/d8/ef/c7d8ef18d7f29ae9fd80b5dfc59591c6.jpg" alt="" class="w-16 h-16 rounded-full mb-3 object-cover">
                    <h3 class="font-semibold text-center">Team A3</h3>
                    <span class="text-xs text-gray-500 mt-1">7 truyện</span>
                </div>

                <div class="author-card bg-white rounded-lg p-4 shadow-md hover:shadow-lg transition duration-200 cursor-pointer flex flex-col items-center">
                    <img src="https://i.pinimg.com/736x/cb/88/0d/cb880dd8d5ece3d16dde516dcae35d5e.jpg" alt="" class="w-16 h-16 rounded-full mb-3 object-cover">
                    <h3 class="font-semibold text-center">Sci-Fi Team</h3>
                    <span class="text-xs text-gray-500 mt-1">11 truyện</span>
                </div>

                <div class="author-card bg-white rounded-lg p-4 shadow-md hover:shadow-lg transition duration-200 cursor-pointer flex flex-col items-center">
                    <img src="https://i.pinimg.com/736x/e6/4c/5c/e64c5c54677da929a6974e384bf1bf97.jpg" alt="" class="w-16 h-16 rounded-full mb-3 object-cover">
                    <h3 class="font-semibold text-center">Minh Vũ</h3>
                    <span class="text-xs text-gray-500 mt-1">8 truyện</span>
                </div>
            </div>
        </section>

        <!-- Reading Page Sample -->
        <section id="reading" class="bg-white rounded-lg shadow-lg p-6 mb-12">
            <h2 class="text-2xl font-bold mb-6 flex items-center">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 mr-2 text-purple-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6.253v13m0-13C10.832 5.477 9.246 5 7.5 5S4.168 5.477 3 6.253v13C4.168 18.477 5.754 18 7.5 18s3.332.477 4.5 1.253m0-13C13.168 5.477 14.754 5 16.5 5c1.747 0 3.332.477 4.5 1.253v13C19.832 18.477 18.247 18 16.5 18c-1.746 0-3.332.477-4.5 1.253" />
                </svg>
                Trang đọc truyện mẫu
            </h2>

            <div class="flex justify-between items-center mb-4">
                <div>
                    <h3 class="text-xl font-semibold" id="current-comic-title"></h3>
                    <p class="text-sm text-gray-600" id="current-comic-info"></p>
                </div>
                <div class="flex items-center">
                    <button id="prev-chapter-btn" class="bg-gray-200 hover:bg-gray-300 px-3 py-1 rounded-l-full text-sm mr-1">Chương trước</button>
                    <button id="next-chapter-btn" class="bg-gray-200 hover:bg-gray-300 px-3 py-1 rounded-r-full text-sm">Chương tiếp</button>
                </div>
            </div>

            <div class="flex justify-between items-center mb-4">
                <div class="flex space-x-2">
                    <button id="current-chapter-button" class="bg-purple-100 text-purple-600 px-3 py-1 rounded-full text-xs tooltip">
                        Chương X
                        <span class="tooltiptext">Danh sách chương</span>
                    </button>
                </div>

                <div>
                    <button id="bookmark-btn" class="bg-purple-500 hover:bg-purple-600 text-white px-3 py-1 rounded-full text-xs mr-2">Đánh dấu</button>
                    <button id="fullscreen-btn" class="bg-gray-100 px-3 py-1 rounded-full text-xs tooltip">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 8V4m0 0h4M4 4l5 5m11-1V4m0 0h-4m4 0l-5 5M4 16v4m0 0h4m-4 0l5-5m11 5l-5-5m5 5v-4m0 4h-4" />
                        </svg>
                        <span class="tooltiptext">Toàn màn hình</span>
                    </button>
                </div>
            </div>

            <div class="border-t border-gray-200 pt-4 relative">
                <!-- Page Turn Buttons -->
                <div id="prev-btn" class="page-turn-btn prev-btn">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 19l-7-7 7-7" />
                    </svg>
                </div>

                <div id="next-btn" class="page-turn-btn next-btn">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" />
                    </svg>
                </div>

                <!-- Comic Pages -->
                <div class="comic-image-container flex flex-col items-center" id="comic-pages-container">
                    <!-- Images will be loaded dynamically -->
                </div>

                <!-- Page Controls -->
                <div class="flex justify-between items-center mt-4 mb-6">
                    <button id="prev-page-btn-bottom" class="bg-gray-200 hover:bg-gray-300 px-3 py-1 rounded-full text-sm flex items-center">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4 mr-1" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 19l-7-7 7-7" />
                        </svg>
                        Trang trước
                    </button>
                    <span class="text-sm text-gray-600" id="page-number-display-bottom">Trang 1/3</span>
                    <button id="next-page-btn-bottom" class="bg-gray-200 hover:bg-gray-300 px-3 py-1 rounded-full text-sm flex items-center">
                        Trang sau
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4 ml-1" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" />
                        </svg>
                    </button>
                </div>

                <!-- Chapter Navigation -->
                <div class="bg-gray-100 rounded-lg p-4 mb-6">
                    <div class="flex justify-between items-center mb-3">
                        <h4 class="font-medium">Danh sách chương</h4>
                        <button id="toggle-chapters-btn" class="text-purple-600 text-sm">Thu gọn</button>
                    </div>
                    <div id="chapter-list" class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-5 gap-2">
                        <!-- Chapters will be loaded dynamically -->
                    </div>
                </div>
            </div>
        </section>

        <!-- Comments Section -->
        <section id="community" class="mb-12">
            <div class="bg-white rounded-lg shadow-lg p-6">
                <h2 class="text-2xl font-bold mb-6 flex items-center">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 mr-2 text-purple-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 12h.01M12 12h.01M16 12h.01M21 12c0 4.418-4.03 8-9 8a9.863 9.863 0 01-4.255-.949L3 20l1.395-3.72C3.512 15.042 3 13.574 3 12c0-4.418 4.03-8 9-8s9 3.582 9 8z" />
                    </svg>
                    Bình luận (<span id="comment-count">0</span>)
                </h2>

                <!-- Comment Form -->
                <div class="mb-8">
                    <div class="flex items-start mb-4">
                        <img id="user-avatar" src="https://api.dicebear.com/7.x/initials/svg?seed=Guest&backgroundColor=0080ff,00bfff,00ffff,ff00ff,ff0080&backgroundType=gradientLinear" alt="[User avatar]" class="w-10 h-10 rounded-full mr-3">
                        <div class="flex-grow">
                            <textarea id="comment-input" placeholder="Chia sẻ cảm nghĩ của bạn về chương này..." class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:ring-2 focus:ring-purple-500 focus:border-purple-500"></textarea>
                            <div class="flex justify-between items-center mt-2">
                                <div class="flex items-center" id="star-rating-input">
                                    <span class="text-sm text-gray-600 mr-1">Đánh giá:</span>
                                    <i class="fas fa-star text-gray-400 cursor-pointer" data-rating="1"></i>
                                    <i class="fas fa-star text-gray-400 cursor-pointer" data-rating="2"></i>
                                    <i class="fas fa-star text-gray-400 cursor-pointer" data-rating="3"></i>
                                    <i class="fas fa-star text-gray-400 cursor-pointer" data-rating="4"></i>
                                    <i class="fas fa-star text-gray-400 cursor-pointer" data-rating="5"></i>
                                </div>
                                <button id="post-comment-btn" class="bg-purple-500 hover:bg-purple-600 text-white px-6 py-2 rounded-full transition duration-200 flex items-center justify-center">
                                    Đăng bình luận
                                    <span class="loading-spinner ml-2 hidden" id="comment-loading-spinner"></span>
                                </button>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Comments List -->
                <div class="space-y-6" id="comments-list">
                    <p class="text-center text-gray-500" id="no-comments-message">Chưa có bình luận nào. Hãy là người đầu tiên!</p>
                    <p class="text-center text-purple-500 hidden" id="loading-comments-message">Đang tải bình luận...</p>
                </div>
                <div class="text-center mt-6">
                    <button class="bg-gray-100 hover:bg-gray-200 text-gray-800 px-4 py-2 rounded-full hidden" id="load-more-comments-btn">
                        <i class="fas fa-arrow-down mr-2"></i> Xem thêm bình luận
                    </button>
                </div>
            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-8">
        <div class="container mx-auto px-4">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-8">
                <div>
                    <h3 class="text-xl font-bold mb-4">ComicVerse</h3>
                    <p class="text-gray-400 text-sm">Nơi hội tụ những câu chuyện hấp dẫn. Đọc truyện tranh online miễn phí và cập nhật liên tục.</p>
                </div>
                <div>
                    <h4 class="font-bold mb-4">Liên kết nhanh</h4>
                    <ul class="space-y-2 text-sm">
                        <li><a href="#home" class="hover:text-purple-300">Trang chủ</a></li>
                        <li><a href="#comics" class="hover:text-purple-300">Thể loại</a></li>
                        <li><a href="#reading" class="hover:text-purple-300">Đọc truyện</a></li>
                        <li><a href="#community" class="hover:text-purple-300">Cộng đồng</a></li>
                    </ul>
                </div>
                <div>
                    <h4 class="font-bold mb-4">Hỗ trợ</h4>
                    <ul class="space-y-2 text-sm">
                        <li><a href="#" class="hover:text-purple-300">FAQ</a></li>
                        <li><a href="#" class="hover:text-purple-300">Chính sách bảo mật</a></li>
                        <li><a href="#" class="hover:text-purple-300">Điều khoản dịch vụ</a></li>
                        <li><a href="#" class="hover:text-purple-300">Liên hệ</a></li>
                    </ul>
                </div>
                <div>
                    <h4 class="font-bold mb-4">Theo dõi chúng tôi</h4>
                    <div class="flex space-x-3">
                        <a href="#" class="w-9 h-9 flex items-center justify-center rounded-full bg-gray-700 hover:bg-blue-600 transition duration-200">
                            <i class="fab fa-facebook-f"></i>
                        </a>
                        <a href="#" class="w-9 h-9 flex items-center justify-center rounded-full bg-gray-700 hover:bg-red-600 transition duration-200">
                            <i class="fab fa-youtube"></i>
                        </a>
                        <a href="#" class="w-9 h-9 flex items-center justify-center rounded-full bg-gray-700 hover:bg-blue-400 transition duration-200">
                            <i class="fab fa-twitter"></i>
                        </a>
                    </div>
                </div>
            </div>
            <div class="border-t border-gray-700 mt-8 pt-6 text-center text-gray-500 text-sm">
                &copy; 2025 ComicVerse. All rights reserved.
            </div>
        </div>
    </footer>

    <!-- Login Modal -->
    <div id="login-modal" class="modal-overlay">
        <div class="modal-content">
            <button class="modal-close-btn" onclick="closeModal('login-modal')">
                <i class="fas fa-times fa-lg"></i>
            </button>
            <h3 class="text-2xl font-bold text-center mb-6">Đăng nhập</h3>
            <form action="#" method="POST">
                <div class="mb-4">
                    <label for="login-email" class="block text-gray-700 font-semibold mb-2">Email</label>
                    <input type="email" id="login-email" name="login-email" class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-purple-500" placeholder="Nhập email của bạn" required>
                </div>
                <div class="mb-6">
                    <label for="login-password" class="block text-gray-700 font-semibold mb-2">Mật khẩu</label>
                    <input type="password" id="login-password" name="login-password" class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-purple-500" placeholder="Nhập mật khẩu" required>
                    <a href="#" class="text-sm text-purple-600 hover:underline mt-2 block text-right">Quên mật khẩu?</a>
                </div>
                <button type="submit" class="w-full bg-purple-600 text-white py-3 rounded-full font-bold hover:bg-purple-700 transition duration-200">Đăng nhập</button>
            </form>
            <p class="mt-4 text-center text-gray-600">Chưa có tài khoản? <a href="#" class="text-purple-600 hover:underline" onclick="closeModal('login-modal'); showModal('register-modal');">Đăng ký ngay</a></p>
        </div>
    </div>

    <!-- Register Modal -->
    <div id="register-modal" class="modal-overlay">
        <div class="modal-content">
            <button class="modal-close-btn" onclick="closeModal('register-modal')">
                <i class="fas fa-times fa-lg"></i>
            </button>
            <h3 class="text-2xl font-bold text-center mb-6">Đăng ký</h3>
            <form action="#" method="POST">
                <div class="mb-4">
                    <label for="register-username" class="block text-gray-700 font-semibold mb-2">Tên người dùng</label>
                    <input type="text" id="register-username" name="register-username" class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-purple-500" placeholder="Nhập tên người dùng" required>
                </div>
                <div class="mb-4">
                    <label for="register-email" class="block text-gray-700 font-semibold mb-2">Email</label>
                    <input type="email" id="register-email" name="register-email" class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-purple-500" placeholder="Nhập email của bạn" required>
                </div>
                <div class="mb-6">
                    <label for="register-password" class="block text-gray-700 font-semibold mb-2">Mật khẩu</label>
                    <input type="password" id="register-password" name="register-password" class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-purple-500" placeholder="Tạo mật khẩu" required>
                </div>
                <button type="submit" class="w-full bg-purple-600 text-white py-3 rounded-full font-bold hover:bg-purple-700 transition duration-200">Đăng ký</button>
            </form>
            <p class="mt-4 text-center text-gray-600">Đã có tài khoản? <a href="#" class="text-purple-600 hover:underline" onclick="closeModal('register-modal'); showModal('login-modal');">Đăng nhập ngay</a></p>
        </div>
    </div>

    <script>
        // Firebase SDK imports (removed as per user's implicit request to simplify by combining files)
        // import { initializeApp } from "https://www.gstatic.com/firebasejs/11.6.1/firebase-app.js";
        // import { getAuth, signInAnonymously, signInWithCustomToken, onAuthStateChanged } from "https://www.gstatic.com/firebasejs/11.6.1/firebase-auth.js";
        // import { getFirestore, collection, addDoc, query, orderBy, onSnapshot, serverTimestamp } from "https://www.gstatic.com/firebasejs/11.6.1/firebase-firestore.js";

        // Global Firebase variables (removed)
        let app, db, auth, userId, userDisplayName;
        let authReady = false;

        // --- Firebase Initialization (removed) ---
        // const firebaseConfig = typeof __firebase_config !== 'undefined' ? JSON.parse(__firebase_config) : {};
        // const appId = typeof __app_id !== 'undefined' ? __app_id : 'default-app-id';
        // const initialAuthToken = typeof __initial_auth_token !== 'undefined' ? initialAuthToken : null;

        // Function to initialize Firebase and authenticate (removed)
        // async function initializeFirebase() { /* ... */ }

        // Call Firebase initialization on window load (modified)
        window.addEventListener('load', () => {
            // If Firebase was initialized: initializeFirebase();
            if (comics.length > 0) {
                openComic(comics[0].id); // Open the first comic by default
            }
        });


        // --- Comic Data (Moved to JS for easier filtering) ---
        const comics = [
            {
                id: 'teen-titans',
                title: 'Teen Titans',
                genres: ['action', 'supernatural'],
                chapters: 45,
                views: '245K',
                rating: 4.8,
                image: 'https://upload.wikimedia.org/wikipedia/en/thumb/f/f4/Titans_01_2023_cover.jpg/250px-Titans_01_2023_cover.jpg',
                status: 'HOT',
                pages: [
                    'https://i0.wp.com/i1239.photobucket.com/albums/ff516/Henchman4Hire/Henchman4Hire016/NTT11%2006.jpg',
                    'https://i0.wp.com/i1239.photobucket.com/albums/ff516/Henchman4Hire/Henchman4Hire017/NTT304.jpg',
                    'https://comicvine.gamespot.com/a/uploads/scale_super/3/31666/3380338-vibe%202.jpg'
                ],
                publishDate: '15/06/2025'
            },
            {
                id: 'jasmine-alley',
                title: 'Ngõ Nhỏ Hoa Nhài',
                genres: ['romance', 'school'],
                chapters: 12,
                views: '189K',
                rating: 4.6,
                image: 'https://thumbs.wbm.im/pw/small/33b063d1f9e756dc92323cdbf93c85c5.jpg',
                status: null,
                pages: [
                    'https://encrypted-tbn1.gstatic.com/images?q=tbn:ANd9GcTk806Dx7lHWZf7S-j2vkcg04qeYUPgQl7j0DXXPNtAmlGaabnk',
                    'https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTpjx3NKMqAQScJHhrxF0rdQznk_Ejgj6fJUMvd9mFGpW8_K2EqSIDK5Rs-cr0orc86Kkg&usqp=CAU'
                ],
                publishDate: '10/06/2025'
            },
            {
                id: 'journey-to-the-east',
                title: 'Hành Trình Phương Đông',
                genres: ['adventure', 'fantasy'],
                chapters: 7,
                views: '102K',
                rating: 4.2,
                image: 'https://cdna.artstation.com/p/assets/images/images/034/977/170/20210219105518/smaller_square/luca-savini-artwork-fantasy.jpg?1613753719',
                status: 'NEW',
                pages: [
                    'https://gd-hbimg.huaban.com/75ebe7e622c431d72748fe662d301adfa614eeca2cc007-lIwYzG_fw240webp',
                    'https://ik.imagekit.io/storybird/images/0577e9e4-9de2-430a-ae09-f15a92f10e49/0_841191000.png?tr=q-80'
                ],
                publishDate: '01/07/2025'
            },
            {
                id: 'mechanical-age',
                title: 'Thời Đại Cơ Giới',
                genres: ['science', 'action'],
                chapters: 89,
                views: '521K',
                rating: 4.9,
                image: 'https://i.pinimg.com/736x/3d/cf/ea/3dcfeab00b7849979c34ae3f3664c5ac.jpg',
                status: null,
                pages: [
                    'https://i.pinimg.com/736x/6b/f7/e5/6bf7e50dff398a6f0db2eb800d1ada7c.jpg',
                    'https://i.pinimg.com/736x/54/05/54/540554e3fff75b79b0bd483b53c48546.jpg'
                ],
                publishDate: '28/06/2025'
            },
            {
                id: 'female-master',
                title: 'Nữ Chưởng Môn',
                genres: ['historical', 'martial-arts'],
                chapters: 34,
                views: '312K',
                rating: 4.7,
                image: 'https://i.pinimg.com/1200x/c7/81/ff/c781ffa143e3543523500aaf25d0f89b.jpg',
                status: 'TRENDING',
                pages: [
                    'https://i.pinimg.com/564x/c8/12/64/c81264a8c0caabbad0ccaac046d952e5.jpg',
                    'https://i.pinimg.com/1200x/17/f2/83/17f283f125af4726baa540dccfcc0598.jpg'
                ],
                publishDate: '25/06/2025'
            }
        ];

        const featuredComicsGrid = document.getElementById('featured-comics-grid');

        // Function to render comic cards
        function renderComics(filteredComics) {
            featuredComicsGrid.innerHTML = ''; // Clear existing comics
            if (filteredComics.length === 0) {
                featuredComicsGrid.innerHTML = '<p class="col-span-full text-center text-gray-600">Không tìm thấy truyện nào.</p>';
                return;
            }

            filteredComics.forEach(comic => {
                const comicCard = document.createElement('div');
                comicCard.className = 'comic-card rounded-lg overflow-hidden hover:shadow-lg transition duration-200';
                comicCard.onclick = () => openComic(comic.id);
                comicCard.innerHTML = `
                    <div class="relative">
                        <img src="${comic.image}" alt="${comic.title}" class="w-full h-48 object-cover">
                        ${comic.status ? `<div class="absolute top-2 right-2 bg-red-500 text-white text-xs px-2 py-1 rounded-full shadow-md">${comic.status}</div>` : ''}
                        <button class="absolute bottom-2 right-2 favorite-btn bg-white p-2 rounded-full shadow-md hover:bg-purple-100 transition duration-200">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-gray-500 hover:text-red-500 favorite-icon" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z" />
                            </svg>
                        </button>
                    </div>
                    <div class="p-3">
                        <h3 class="font-semibold mb-1 truncate">${comic.title}</h3>
                        <div class="flex justify-between items-center mb-2">
                            <span class="text-xs text-gray-500">Chương ${comic.chapters}</span>
                            <span class="text-xs text-gray-500">${comic.rating}★</span>
                        </div>
                        <div class="flex flex-wrap gap-1">
                            ${comic.genres.map(genre => `<span class="comic-tag text-xs px-2 py-1 rounded-full">${genre.charAt(0).toUpperCase() + genre.slice(1)}</span>`).join('')}
                        </div>
                    </div>
                `;
                featuredComicsGrid.appendChild(comicCard);
            });

            // Re-attach favorite button listeners after rendering
            document.querySelectorAll('.comic-card .favorite-btn').forEach(favBtn => {
                favBtn.addEventListener('click', function(event) {
                    event.stopPropagation(); // Prevent comic card click
                    const icon = this.querySelector('.favorite-icon');
                    if (icon.getAttribute('fill') === 'none') {
                        icon.setAttribute('fill', 'currentColor');
                        icon.classList.add('text-red-500');
                    } else {
                        icon.setAttribute('fill', 'none');
                        icon.classList.remove('text-red-500');
                    }
                });
            });
        }

        // Initial render of all comics
        renderComics(comics);

        // --- Search Functionality ---
        const searchInput = document.getElementById('search-input');
        const searchButton = document.getElementById('search-button');
        const searchToggle = document.getElementById('search-toggle');
        const searchBar = document.getElementById('search-bar');
        const searchTags = document.querySelectorAll('.search-tag');

        searchToggle.addEventListener('click', () => {
            searchBar.classList.toggle('hidden');
            if (!searchBar.classList.contains('hidden')) {
                searchInput.focus();
            }
        });

        function performSearch() {
            const query = searchInput.value.toLowerCase();
            const filtered = comics.filter(comic =>
                comic.title.toLowerCase().includes(query) ||
                comic.genres.some(genre => genre.toLowerCase().includes(query))
            );
            renderComics(filtered);
            console.log(`Searching for: ${query}`);
            // Optionally scroll to featured comics section
            document.getElementById('featured-comics-grid').scrollIntoView({ behavior: 'smooth' });
        }

        searchButton.addEventListener('click', performSearch);
        searchInput.addEventListener('keypress', function(e) {
            if (e.key === 'Enter') {
                performSearch();
            }
        });

        searchTags.forEach(tag => {
            tag.addEventListener('click', function() {
                searchInput.value = this.textContent.trim();
                performSearch();
            });
        });

        // --- Genre Filtering ---
        const categoryCards = document.querySelectorAll('#category-cards-container .category-card');
        categoryCards.forEach(card => {
            card.addEventListener('click', function() {
                const genre = this.dataset.genre;
                if (genre === 'all') {
                    renderComics(comics);
                } else {
                    const filtered = comics.filter(comic => comic.genres.includes(genre));
                    renderComics(filtered);
                }
                console.log(`Filtered by genre: ${genre}`);
                // Optionally scroll to featured comics section
                document.getElementById('featured-comics-grid').scrollIntoView({ behavior: 'smooth' });
            });
        });

        // --- Comic Reader ---
        let currentComicData = null;
        let currentChapterNumber = null; // Track the currently viewed chapter
        let currentPageIndex = 0; // Track the current page within the chapter

        const comicPagesContainer = document.getElementById('comic-pages-container');
        const currentComicTitle = document.getElementById('current-comic-title');
        const currentComicInfo = document.getElementById('current-comic-info');
        const pageNumberDisplayBottom = document.getElementById('page-number-display-bottom');
        
        // Remove prevPageBtnTop and nextPageBtnTop as they are no longer needed for single-page navigation
        // const prevPageBtnTop = document.getElementById('prev-btn');
        // const nextPageBtnTop = document.getElementById('next-btn');

        const prevPageBtnBottom = document.getElementById('prev-page-btn-bottom');
        const nextPageBtnBottom = document.getElementById('next-page-btn-bottom');
        const chapterListContainer = document.getElementById('chapter-list');
        const toggleChaptersBtn = document.getElementById('toggle-chapters-btn');
        const currentChapterButton = document.getElementById('current-chapter-button');


        function openComic(comicId) {
            currentComicData = comics.find(c => c.id === comicId);
            if (currentComicData) {
                // When opening a comic, default to the last chapter and first page of that chapter
                currentChapterNumber = currentComicData.chapters; 
                currentPageIndex = 0; 
                updateReader();
                updateChapterList();
                document.getElementById('reading').scrollIntoView({ behavior: 'smooth' });
            } else {
                console.error(`Comic with ID ${comicId} not found.`);
            }
        }

        function updateReader() {
            if (!currentComicData || currentChapterNumber === null) return;

            comicPagesContainer.innerHTML = ''; // Clear existing images
            
            // Display only the current page
            const pageSrc = currentComicData.pages[currentPageIndex];
            const img = document.createElement('img');
            img.src = pageSrc;
            img.alt = `Trang truyện ${currentComicData.title} - Chương ${currentChapterNumber} - Trang ${currentPageIndex + 1}`;
            img.className = 'mb-4 max-w-full h-auto rounded-lg shadow-md animate-fade-in';
            comicPagesContainer.appendChild(img);
            

            currentComicTitle.textContent = `${currentComicData.title} - Chương ${currentChapterNumber}`;
            currentComicInfo.textContent = `Đăng ngày: ${currentComicData.publishDate} | Lượt xem: ${currentComicData.views}`;
            pageNumberDisplayBottom.textContent = `Trang ${currentPageIndex + 1}/${currentComicData.pages.length}`;
            currentChapterButton.textContent = `Chương ${currentChapterNumber}`;

            // Update page navigation button states
            prevPageBtnBottom.disabled = currentPageIndex === 0;
            nextPageBtnBottom.disabled = currentPageIndex === currentComicData.pages.length - 1;

            // Hide the fixed page turn buttons (prev-btn and next-btn) as they are not used for single page navigation
            document.getElementById('prev-btn').style.display = 'none';
            document.getElementById('next-btn').style.display = 'none';
        }

        function navigateToPage(direction) {
            if (!currentComicData) return;

            if (direction === 'prev' && currentPageIndex > 0) {
                currentPageIndex--;
            } else if (direction === 'next' && currentPageIndex < currentComicData.pages.length - 1) {
                currentPageIndex++;
            }
            updateReader();
        }

        function updateChapterList() {
            chapterListContainer.innerHTML = '';
            // Example: Generate buttons for the last 10 chapters
            const totalChapters = currentComicData.chapters;
            const startChapter = Math.max(1, totalChapters - 9); // Show last 10 chapters
            for (let i = totalChapters; i >= startChapter; i--) {
                const chapterLink = document.createElement('a');
                chapterLink.href = "#"; // Placeholder
                chapterLink.className = `bg-white hover:bg-purple-50 px-3 py-2 rounded text-sm text-center chapter-link ${i === currentChapterNumber ? 'text-purple-600 font-bold' : ''}`;
                chapterLink.textContent = `Chương ${i}`;
                chapterLink.dataset.chapterNum = i; // Store chapter number
                chapterLink.addEventListener('click', (e) => {
                    e.preventDefault();
                    selectChapter(parseInt(e.target.dataset.chapterNum));
                });
                chapterListContainer.appendChild(chapterLink);
            }
        }

        function selectChapter(chapterNum) {
            currentChapterNumber = chapterNum;
            currentPageIndex = 0; // Reset to first page of the new chapter
            updateReader();
            // Update active class for chapter links
            document.querySelectorAll('.chapter-link').forEach(link => {
                if (parseInt(link.dataset.chapterNum) === chapterNum) {
                    link.classList.add('text-purple-600', 'font-bold');
                } else {
                    link.classList.remove('text-purple-600', 'font-bold');
                }
            });
        }


        toggleChaptersBtn.addEventListener('click', () => {
            chapterListContainer.classList.toggle('hidden');
            toggleChaptersBtn.textContent = chapterListContainer.classList.contains('hidden') ? 'Mở rộng' : 'Thu gọn';
        });

        // Event listeners for page navigation
        prevPageBtnBottom.addEventListener('click', () => { navigateToPage('prev'); });
        nextPageBtnBottom.addEventListener('click', () => { navigateToPage('next'); });
        
        // Event listeners for chapter navigation (these will simply update the displayed chapter number, not actual content without more data)
        document.getElementById('prev-chapter-btn').addEventListener('click', () => {
            if (currentComicData && currentChapterNumber > 1) {
                selectChapter(currentChapterNumber - 1);
            }
        });
        document.getElementById('next-chapter-btn').addEventListener('click', () => {
            if (currentComicData && currentChapterNumber < currentComicData.chapters) {
                selectChapter(currentChapterNumber + 1);
            }
        });


        // --- Comments Section ---
        const commentInput = document.getElementById('comment-input');
        const postCommentBtn = document.getElementById('post-comment-btn');
        const commentsList = document.getElementById('comments-list');
        const commentCountDisplay = document.getElementById('comment-count');
        const noCommentsMessage = document.getElementById('no-comments-message');
        const loadingCommentsMessage = document.getElementById('loading-comments-message');
        const commentLoadingSpinner = document.getElementById('comment-loading-spinner');
        const starRatingInput = document.getElementById('star-rating-input');

        let selectedRating = 0;

        // Star rating logic for input
        starRatingInput.addEventListener('mouseover', function(e) {
            if (e.target.classList.contains('fa-star')) {
                const hoveredRating = parseInt(e.target.dataset.rating);
                const stars = this.querySelectorAll('.fa-star');
                stars.forEach((s, index) => {
                    if (index < hoveredRating) {
                        s.classList.add('text-yellow-500');
                        s.classList.remove('text-gray-400');
                    } else {
                        s.classList.remove('text-yellow-500');
                        s.classList.add('text-gray-400');
                    }
                });
            }
        });

        starRatingInput.addEventListener('mouseout', function() {
            const stars = this.querySelectorAll('.fa-star');
            stars.forEach((s, index) => {
                if (index < selectedRating) {
                    s.classList.add('text-yellow-500');
                    s.classList.remove('text-gray-400');
                } else {
                    s.classList.remove('text-yellow-500');
                    s.classList.add('text-gray-400');
                }
            });
        });

        starRatingInput.addEventListener('click', function(e) {
            if (e.target.classList.contains('fa-star')) {
                selectedRating = parseInt(e.target.dataset.rating);
                const stars = this.querySelectorAll('.fa-star');
                stars.forEach((s, index) => {
                    if (index < selectedRating) {
                        s.classList.add('text-yellow-500');
                        s.classList.remove('text-gray-400');
                    } else {
                        s.classList.remove('text-yellow-500');
                        s.classList.add('text-gray-400');
                    }
                });
            }
        });

        // Function to render a single comment
        function renderComment(comment) {
            const commentDiv = document.createElement('div');
            commentDiv.className = 'flex items-start border-b border-gray-200 pb-4 animate-fade-in';
            // Placeholder for timestamp and avatar as Firebase is removed for this combined file
            const timestamp = 'Vừa xong'; // Placeholder
            const avatarUrl = `https://api.dicebear.com/7.x/initials/svg?seed=${comment.username || 'Guest'}&backgroundColor=0080ff,00bfff,00ffff,ff00ff,ff0080&backgroundType=gradientLinear`;

            let starsHtml = '';
            for (let i = 0; i < 5; i++) {
                if (i < Math.floor(comment.rating)) {
                    starsHtml += '<svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4 text-yellow-500" viewBox="0 0 20 20" fill="currentColor"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" /></svg>';
                } else if (i === Math.floor(comment.rating) && comment.rating % 1 !== 0) {
                    starsHtml += '<i class="fas fa-star-half-alt text-yellow-500"></i>';
                } else {
                    starsHtml += '<svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4 text-gray-400" viewBox="0 0 20 20" fill="currentColor"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" /></svg>';
                }
            }

            commentDiv.innerHTML = `
                <img src="${avatarUrl}" alt="[User avatar]" class="w-10 h-10 rounded-full mr-3">
                <div class="flex-grow">
                    <div class="flex justify-between items-center mb-1">
                        <span class="font-semibold">${comment.username || 'Người dùng ẩn danh'}</span>
                        <span class="text-xs text-gray-500">${timestamp}</span>
                    </div>
                    <div class="mb-2 flex">
                        ${starsHtml}
                    </div>
                    <p class="text-gray-700 mb-2">${comment.commentText}</p>
                    <div class="flex items-center">
                        <button class="text-gray-500 hover:text-purple-500 flex items-center mr-4">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4 mr-1" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 10h4.764a2 2 0 011.789 2.894l-3.5 7A2 2 0 0115.263 21h-4.017c-.163 0-.326-.02-.485-.06L7 20m7-10V5a2 2 0 00-2-2h-.095c-.5 0-.905.375-.905.833 0 .552.33.98.738 1.218L7 9m7-10v2.68a2 2 0 00-1.448 2.948l1.978 4.952a2 2 0 001.204.965L15 16.988V20m0-12H7" />
                            </svg>
                            0 Thích
                        </button>
                        <button class="text-gray-500 hover:text-purple-500 flex items-center mr-4">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4 mr-1" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 12h.01M12 12h.01M16 12h.01M21 12c0 4.418-4.03 8-9 8a9.863 9.863 0 01-4.255-.949L3 20l1.395-3.72C3.512 15.042 3 13.574 3 12c0-4.418 4.03-8 9-8s9 3.582 9 8z" />
                            </svg>
                            Trả lời
                        </button>
                    </div>
                </div>
            `;
            commentsList.prepend(commentDiv); // Add new comments to the top
        }

        // Dummy comments for demonstration since Firebase is removed
        const dummyComments = [
            { username: 'Ngọc Hân', commentText: 'Truyện này hay quá, hóng chương mới mỗi ngày luôn!', rating: 4.5 },
            { username: 'Văn Bình', commentText: 'Tác giả vẽ đẹp thật, cốt truyện cũng lôi cuốn. Vote 5 sao!', rating: 5 },
            { username: 'Tuyết Mai', commentText: 'Đồng ý luôn! Tình tiết hấp dẫn quá.', rating: 4 },
        ];

        // Function to load comments (now from dummy data)
        function loadComments() {
            loadingCommentsMessage.classList.add('hidden'); // Hide loading message
            if (dummyComments.length === 0) {
                noCommentsMessage.classList.remove('hidden');
            } else {
                noCommentsMessage.classList.add('hidden');
                commentsList.innerHTML = ''; // Clear existing comments
                dummyComments.forEach(comment => {
                    renderComment(comment);
                });
            }
            commentCountDisplay.textContent = dummyComments.length; // Update comment count
        }

        // Submit comment logic (now just adds to dummy data and re-renders)
        postCommentBtn.addEventListener('click', async function() {
            const commentText = commentInput.value.trim();
            if (!commentText) {
                console.log("Bình luận không được để trống.");
                return;
            }

            commentLoadingSpinner.classList.remove('hidden');
            postCommentBtn.disabled = true;

            // Simulate API call delay
            await new Promise(resolve => setTimeout(resolve, 1000));

            // Add new comment to dummy data
            dummyComments.unshift({
                username: 'Người dùng hiện tại', // Placeholder username
                commentText: commentText,
                rating: selectedRating
            });

            commentInput.value = ''; // Clear textarea
            selectedRating = 0; // Reset rating
            starRatingInput.querySelectorAll('.fa-star').forEach(s => {
                s.classList.remove('text-yellow-500');
                s.classList.add('text-gray-400');
            });
            loadComments(); // Re-render comments with the new one
            console.log("Bình luận đã được gửi thành công (dữ liệu giả lập)!");

            commentLoadingSpinner.classList.add('hidden');
            postCommentBtn.disabled = false;
        });

        // Initial load of comments when the page loads
        window.addEventListener('load', loadComments);


        // --- Mobile Menu Toggle ---
        const mobileMenuButton = document.getElementById('mobile-menu-button');
        const mobileMenu = document.getElementById('mobile-menu');

        mobileMenuButton.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        // Ensure initial comic is displayed in reader on load
        window.addEventListener('load', () => {
            if (comics.length > 0) {
                openComic(comics[0].id); // Open the first comic by default
            }
        });

        // Smooth scroll for navigation links
        document.querySelectorAll('nav a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
                // Close mobile menu if open
                if (!mobileMenu.classList.contains('hidden')) {
                    mobileMenu.classList.add('hidden');
                }
            });
        });

        document.getElementById('explore-btn').addEventListener('click', function() {
            document.getElementById('featured-comics-grid').scrollIntoView({ behavior: 'smooth' });
        });

        // Modal functions
        window.showModal = function(modalId) {
            document.getElementById(modalId).style.display = 'flex';
        }

        window.closeModal = function(modalId) {
            document.getElementById(modalId).style.display = 'none';
        }
    </script>
</body>
</html>
