<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
    <title>CÔNG TY TNHH THƯƠNG MẠI VÀ DỊCH VỤ DANTECHCO | Thiết Kế & Thi Công Xây Dựng Đà Nẵng</title>
    <meta name="description" content="CÔNG TY TNHH THƯƠNG MẠI VÀ DỊCH VỤ DANTECHCO - Chuyên thiết kế kiến trúc, thi công phần thô, thi công hoàn thiện, nội thất và xây dựng trọn gói uy tín tại Đà Nẵng. Hotline: 0905.294.687.">
    <meta name="keywords" content="DANTECHCO, dantechco.com, xây dựng Đà Nẵng, thiết kế kiến trúc Đà Nẵng, thi công phần thô, thi công trọn gói Đà Nẵng, Sơn Trà Đà Nẵng">

    <!-- Open Graph & Social Thumbnail (Logo công ty khi chia sẻ link dantechco.com lên Zalo/Facebook) -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://dantechco.com/">
    <meta property="og:site_name" content="CÔNG TY TNHH THƯƠNG MẠI VÀ DỊCH VỤ DANTECHCO">
    <meta property="og:title" content="DANTECHCO - Thiết Kế & Thi Công Xây Dựng Trọn Gói Tại Đà Nẵng">
    <meta property="og:description" content="Địa chỉ: 54 Mân Quang 4, Phường Sơn Trà, TP Đà Nẵng | Hotline: 0905.294.687 | Website: dantechco.com">
    <meta property="og:image" content="https://dantechco.com/wp-content/uploads/dantechco-logo-og.png">
    <meta property="og:image:width" content="1200">
    <meta property="og:image:height" content="630">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="CÔNG TY TNHH THƯƠNG MẠI VÀ DỊCH VỤ DANTECHCO">
    <meta name="twitter:description" content="Thiết kế & Thi công xây dựng uy tín tại Đà Nẵng - Hotline: 0905.294.687">
    <meta name="twitter:image" content="https://dantechco.com/wp-content/uploads/dantechco-logo-og.png">

    <!-- Favicon SVG Logo DANTECHCO -->
    <link rel="icon" type="image/svg+xml" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 64 64'%3E%3Crect width='64' height='64' rx='12' fill='%230F3D66'/%3E%3Cpath d='M16 46V24L32 14L48 24V46H38V30H26V46H16Z' fill='%23FFFFFF'/%3E%3Cpath d='M32 14L48 24V30L32 20L16 30V24L32 14Z' fill='%23D98A1C'/%3E%3Crect x='29' y='34' width='6' height='12' fill='%23D98A1C'/%3E%3C/svg%3E">

    <!-- Google Fonts: Inter -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            navy: '#0F3D66',
                            navyDark: '#0A2945',
                            navyLight: '#1A568C',
                            gold: '#D98A1C',
                            goldDark: '#B87112',
                            goldSoft: '#FDF6EC',
                            surface: '#F7F9FC',
                        }
                    }
                }
            }
        }
    </script>

    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <style>
        /* Cài đặt gốc chống tràn viền & lệch trang trên mọi thiết bị */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html {
            scroll-behavior: smooth;
            overflow-x: hidden;
            width: 100%;
            max-width: 100%;
            font-size: 16px;
        }
        body {
            margin: 0;
            padding: 0;
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
            color: #1E293B;
            background-color: #FFFFFF;
            overflow-x: hidden;
            width: 100%;
            max-width: 100%;
            -webkit-font-smoothing: antialiased;
        }

        /* Chiều ngang giao diện trên máy tính chuẩn 95% màn hình, điện thoại căn đều không tràn viền */
        .dantech-container {
            width: 100%;
            max-width: 100%;
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }
        @media (min-width: 640px) {
            .dantech-container {
                padding-left: 16px;
                padding-right: 16px;
            }
        }
        @media (min-width: 1024px) {
            .dantech-container {
                width: 95%;
                max-width: 95vw;
                padding-left: 0;
                padding-right: 0;
            }
        }

        /* Tiêu đề section chuẩn phong cách Flatsome UX Builder */
        .flatsome-title-wrap {
            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
            margin-bottom: 1.75rem;
        }
        .flatsome-title-line {
            width: 56px;
            height: 3px;
            background: linear-gradient(90deg, #0F3D66 0%, #D98A1C 100%);
            border-radius: 999px;
            margin-top: 10px;
        }

        /* Menu dropdown Flatsome đơn giản, gọn trên 1 hàng */
        .nav-dropdown {
            position: relative;
        }
        .nav-dropdown-menu {
            opacity: 0;
            visibility: hidden;
            transform: translateY(8px);
            transition: all 0.2s ease;
            position: absolute;
            top: 100%;
            left: 0;
            min-width: 230px;
            background: #FFFFFF;
            border: 1px solid #E2E8F0;
            border-top: 2px solid #D98A1C;
            border-radius: 0 0 8px 8px;
            box-shadow: 0 12px 28px rgba(15, 61, 102, 0.12);
            z-index: 60;
            padding: 6px 0;
        }
        .nav-dropdown:hover .nav-dropdown-menu,
        .nav-dropdown:focus-within .nav-dropdown-menu {
            opacity: 1;
            visibility: visible;
            transform: translateY(0);
        }

        /* Banner tự trượt kích thước bằng nhau tuyệt đối */
        .hero-slider-viewport {
            position: relative;
            width: 100%;
            overflow: hidden;
        }
        .hero-slides-track {
            display: flex;
            width: 100%;
            transition: transform 0.65s cubic-bezier(0.25, 0.8, 0.25, 1);
        }
        .hero-slide-item {
            min-width: 100%;
            width: 100%;
            flex-shrink: 0;
            height: 320px;
            position: relative;
            overflow: hidden;
        }
        @media (min-width: 640px) {
            .hero-slide-item {
                height: 390px;
            }
        }
        @media (min-width: 1024px) {
            .hero-slide-item {
                height: 460px;
            }
        }
        @media (min-width: 1280px) {
            .hero-slide-item {
                height: 500px;
            }
        }

        /* Card hover tinh tế chuẩn Flatsome */
        .ux-card {
            transition: transform 0.25s ease, box-shadow 0.25s ease, border-color 0.25s ease;
        }
        .ux-card:hover {
            transform: translateY(-3px);
            box-shadow: 0 12px 24px rgba(15, 61, 102, 0.1);
            border-color: #CBD5E1;
        }
        .ux-card img {
            transition: transform 0.45s ease;
        }
        .ux-card:hover img {
            transform: scale(1.04);
        }

        /* Tab danh mục trang chủ gọn gàng, không xuống dòng từng tên danh mục */
        .cat-tab-btn {
            white-space: nowrap;
            transition: all 0.2s ease;
        }
        .cat-tab-btn.active {
            background-color: #0F3D66;
            color: #FFFFFF;
            border-color: #0F3D66;
        }

        /* Nút liên hệ nổi bật Zalo, Facebook, Hotline */
        @keyframes pulseRing {
            0% {
                transform: scale(0.95);
                box-shadow: 0 0 0 0 rgba(217, 138, 28, 0.65);
            }
            70% {
                transform: scale(1);
                box-shadow: 0 0 0 12px rgba(217, 138, 28, 0);
            }
            100% {
                transform: scale(0.95);
                box-shadow: 0 0 0 0 rgba(217, 138, 28, 0);
            }
        }
        .hotline-pulse {
            animation: pulseRing 2s infinite;
        }
    </style>
</head>
<body class="bg-white text-slate-800">

    <!-- UX Builder: Top Bar thông tin liên hệ tinh gọn -->
    <div class="bg-brand-navy text-white text-xs border-b border-white/10">
        <div class="dantech-container py-2 flex items-center justify-between gap-2">
            <div class="flex items-center gap-3 sm:gap-5 min-w-0 truncate">
                <a href="tel:0905294687" class="inline-flex items-center gap-1.5 hover:text-brand-gold transition-colors whitespace-nowrap">
                    <i class="fa-solid fa-phone text-brand-gold text-[11px]"></i>
                    <span class="font-medium">0905.294.687</span>
                </a>
                <span class="hidden sm:inline text-white/30">|</span>
                <span class="hidden sm:inline-flex items-center gap-1.5 text-slate-200 truncate">
                    <i class="fa-solid fa-location-dot text-brand-gold text-[11px]"></i>
                    <span class="truncate">54 Mân Quang 4, Phường Sơn Trà, TP Đà Nẵng</span>
                </span>
            </div>
            <div class="flex items-center gap-3 shrink-0">
                <span class="hidden md:inline text-slate-200">dantechco.com</span>
                <a href="https://www.facebook.com/" target="_blank" rel="noopener noreferrer" aria-label="Facebook DANTECHCO" class="hover:text-brand-gold transition-colors">
                    <i class="fa-brands fa-facebook-f text-xs"></i>
                </a>
                <a href="https://zalo.me/0905294687" target="_blank" rel="noopener noreferrer" aria-label="Zalo DANTECHCO" class="hover:text-brand-gold transition-colors font-bold text-[11px]">
                    Zalo
                </a>
            </div>
        </div>
    </div>

    <!-- UX Builder: Header chính (Logo gọn nhỏ, Menu 1 hàng không xuống dòng, KHÔNG nút gọi ngay để chống tràn viền) -->
    <header id="main-header" class="sticky top-0 z-40 bg-white/95 backdrop-blur border-b border-slate-200 shadow-sm w-full">
        <div class="dantech-container h-16 lg:h-[72px] flex items-center justify-between gap-3">

            <!-- Logo Công ty DANTECHCO chỉnh gọn nhỏ, sắc nét -->
            <a href="#trang-chu" class="flex items-center gap-2 shrink-0 group focus:outline-none" aria-label="Trang chủ DANTECHCO">
                <svg class="w-9 h-9 lg:w-10 lg:h-10 shrink-0" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Logo DANTECHCO">
                    <rect width="64" height="64" rx="12" fill="#0F3D66"/>
                    <!-- Biểu tượng mái kiến trúc & kết cấu chữ D hiện đại -->
                    <path d="M14 48V24.5L32 13L50 24.5V48H41.5V29.5H22.5V48H14Z" fill="#FFFFFF"/>
                    <path d="M32 13L50 24.5V30.5L32 19L14 30.5V24.5L32 13Z" fill="#D98A1C"/>
                    <rect x="28.5" y="34" width="7" height="14" rx="1" fill="#D98A1C"/>
                    <rect x="26" y="24" width="4" height="4" rx="0.5" fill="#FFFFFF"/>
                    <rect x="34" y="24" width="4" height="4" rx="0.5" fill="#FFFFFF"/>
                </svg>
                <div class="flex flex-col leading-none">
                    <span class="text-base lg:text-[17px] font-extrabold tracking-tight text-brand-navy group-hover:text-brand-gold transition-colors whitespace-nowrap">
                        DAN<span class="text-brand-gold">TECH</span>CO
                    </span>
                    <span class="text-[9px] lg:text-[9.5px] font-semibold tracking-wider text-slate-500 uppercase mt-0.5 whitespace-nowrap">
                        Xây Dựng & Thương Mại
                    </span>
                </div>
            </a>

            <!-- Menu Desktop: Chữ gọn, viết liền trên đúng 1 hàng, tuyệt đối không xuống dòng -->
            <nav class="hidden lg:flex items-center justify-end flex-nowrap gap-3.5 xl:gap-5 min-w-0" aria-label="Menu chính">
                <a href="#trang-chu" class="text-[12px] xl:text-[13px] font-semibold text-brand-navy hover:text-brand-gold whitespace-nowrap transition-colors py-2">
                    Trang chủ
                </a>
                <a href="#gioi-thieu" class="text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-gold whitespace-nowrap transition-colors py-2">
                    Giới thiệu
                </a>

                <!-- Dropdown Lĩnh vực / Sản phẩm theo web mẫu tintruongthinh.com -->
                <div class="nav-dropdown">
                    <a href="#san-pham-thi-cong" class="inline-flex items-center gap-1 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-gold whitespace-nowrap transition-colors py-2">
                        <span>Lĩnh vực hoạt động</span>
                        <i class="fa-solid fa-chevron-down text-[9px] text-slate-400"></i>
                    </a>
                    <div class="nav-dropdown-menu">
                        <a href="#san-pham-thi-cong" onclick="filterProducts('thiet-ke-kien-truc')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-surface hover:text-brand-navy font-medium">Thiết kế Kiến trúc – Nội thất</a>
                        <a href="#san-pham-thi-cong" onclick="filterProducts('thi-cong-phan-tho')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-surface hover:text-brand-navy font-medium">Thi công phần thô</a>
                        <a href="#san-pham-thi-cong" onclick="filterProducts('thi-cong-hoan-thien')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-surface hover:text-brand-navy font-medium">Thi công hoàn thiện</a>
                        <a href="#san-pham-thi-cong" onclick="filterProducts('thi-cong-noi-that')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-surface hover:text-brand-navy font-medium">Thi công nội thất</a>
                    </div>
                </div>

                <!-- Dropdown Công trình thực tế tại Đà Nẵng -->
                <div class="nav-dropdown">
                    <a href="#du-an-da-nang" class="inline-flex items-center gap-1 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-gold whitespace-nowrap transition-colors py-2">
                        <span>Công trình thực tế</span>
                        <i class="fa-solid fa-chevron-down text-[9px] text-slate-400"></i>
                    </a>
                    <div class="nav-dropdown-menu">
                        <a href="#du-an-da-nang" onclick="filterProjects('khach-san-can-ho')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-surface hover:text-brand-navy font-medium">Khách sạn – Căn hộ</a>
                        <a href="#du-an-da-nang" onclick="filterProjects('biet-thu')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-surface hover:text-brand-navy font-medium">Biệt thự</a>
                        <a href="#du-an-da-nang" onclick="filterProjects('nha-pho')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-surface hover:text-brand-navy font-medium">Nhà phố</a>
                        <a href="#du-an-da-nang" onclick="filterProjects('van-phong')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-surface hover:text-brand-navy font-medium">Văn phòng</a>
                    </div>
                </div>

                <a href="#bao-gia" class="text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-gold whitespace-nowrap transition-colors py-2">
                    Báo giá
                </a>
                <a href="#doi-tac" class="text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-gold whitespace-nowrap transition-colors py-2">
                    Đối tác
                </a>
                <a href="#tin-tuc" class="text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-gold whitespace-nowrap transition-colors py-2">
                    Tin tức
                </a>
                <a href="#lien-he" class="text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-gold whitespace-nowrap transition-colors py-2">
                    Liên hệ
                </a>
            </nav>

            <!-- Nút mở menu trên điện thoại / máy tính bảng -->
            <button id="mobile-menu-btn" type="button" onclick="toggleMobileMenu()" class="lg:hidden inline-flex items-center justify-center w-10 h-10 rounded-lg border border-slate-200 text-brand-navy hover:bg-slate-50 focus:outline-none" aria-label="Mở danh mục điều hướng">
                <i id="mobile-menu-icon" class="fa-solid fa-bars text-lg"></i>
            </button>
        </div>

        <!-- Menu Mobile dạng Drawer trượt xuống gọn gàng -->
        <div id="mobile-menu" class="hidden lg:hidden bg-white border-t border-slate-200 shadow-lg w-full">
            <div class="dantech-container py-3 flex flex-col divide-y divide-slate-100">
                <a href="#trang-chu" onclick="closeMobileMenu()" class="py-2.5 text-sm font-semibold text-brand-navy">Trang chủ</a>
                <a href="#gioi-thieu" onclick="closeMobileMenu()" class="py-2.5 text-sm font-semibold text-slate-700">Giới thiệu</a>
                <a href="#san-pham-thi-cong" onclick="closeMobileMenu()" class="py-2.5 text-sm font-semibold text-slate-700">Lĩnh vực hoạt động & Sản phẩm</a>
                <a href="#du-an-da-nang" onclick="closeMobileMenu()" class="py-2.5 text-sm font-semibold text-slate-700">Công trình thực tế Đà Nẵng</a>
                <a href="#bao-gia" onclick="closeMobileMenu()" class="py-2.5 text-sm font-semibold text-slate-700">Yêu cầu & Báo giá</a>
                <a href="#doi-tac" onclick="closeMobileMenu()" class="py-2.5 text-sm font-semibold text-slate-700">Đối tác chiến lược</a>
                <a href="#tin-tuc" onclick="closeMobileMenu()" class="py-2.5 text-sm font-semibold text-slate-700">Bài viết & Tin tức</a>
                <a href="#lien-he" onclick="closeMobileMenu()" class="py-2.5 text-sm font-semibold text-slate-700">Bản đồ & Liên hệ</a>
            </div>
        </div>
    </header>

    <main id="trang-chu" class="w-full overflow-x-hidden">

        <!-- UX Builder: UX Slider - 2 Banner tự trượt chuyên nghiệp, kích thước bằng nhau, chữ nằm trọn bên trong cách xa viền -->
        <section aria-label="Banner nổi bật DANTECHCO" class="w-full bg-brand-navyDark">
            <div class="dantech-container py-0 lg:py-3">
                <div class="hero-slider-viewport lg:rounded-xl shadow-md bg-brand-navyDark">
                    <div id="hero-track" class="hero-slides-track">

                        <!-- Banner 1 -->
                        <div class="hero-slide-item">
                            <img src="https://lh3.googleusercontent.com/d/13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz=w1600"
                                 data-drive-id="13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz"
                                 onerror="handleDriveImageError(this, 'Thi công xây dựng DANTECHCO')"
                                 alt="Thi công xây dựng thực tế DANTECHCO tại Đà Nẵng"
                                 class="absolute inset-0 w-full h-full object-cover object-center">
                            <!-- Lớp phủ màu đồng bộ logo giúp chữ luôn rõ nét -->
                            <div class="absolute inset-0" style="background: linear-gradient(90deg, rgba(10,41,69,0.92) 0%, rgba(15,61,102,0.78) 58%, rgba(15,61,102,0.45) 100%);"></div>

                            <!-- Vùng an toàn cho chữ: cách xa viền trên/dưới/trái/phải trên cả điện thoại và máy tính -->
                            <div class="relative z-10 w-full h-full flex items-center px-11 sm:px-16 md:px-20 lg:px-24 py-8 sm:py-10">
                                <div class="max-w-xl lg:max-w-2xl text-white">
                                    <p class="text-[11px] sm:text-xs md:text-sm font-bold tracking-widest uppercase text-brand-gold mb-2">
                                        CÔNG TY TNHH TM & DV DANTECHCO
                                    </p>
                                    <h1 class="text-lg sm:text-2xl md:text-3xl lg:text-4xl font-extrabold leading-snug mb-2.5 sm:mb-3">
                                        Thiết Kế & Thi Công Xây Dựng Trọn Gói Tại Đà Nẵng
                                    </h1>
                                    <p class="text-xs sm:text-sm md:text-base text-slate-100 leading-relaxed mb-4 sm:mb-6">
                                        Chuyên thiết kế kiến trúc, thi công phần thô, hoàn thiện nội thất và cơ điện công trình. Cam kết chuẩn kỹ thuật, đúng tiến độ và chi phí minh bạch.
                                    </p>
                                    <div class="flex flex-wrap items-center gap-2.5 sm:gap-3">
                                        <a href="#bao-gia" class="inline-flex items-center justify-center px-4 sm:px-6 py-2 sm:py-2.5 rounded-lg bg-brand-gold hover:bg-brand-goldDark text-white text-xs sm:text-sm font-semibold transition-colors shadow">
                                            Nhận báo giá ngay
                                        </a>
                                        <a href="#du-an-da-nang" class="inline-flex items-center justify-center px-4 sm:px-6 py-2 sm:py-2.5 rounded-lg bg-white/15 hover:bg-white/25 border border-white/40 text-white text-xs sm:text-sm font-semibold transition-colors">
                                            Xem dự án thực tế
                                        </a>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <!-- Banner 2 (Cùng kích thước và vùng an toàn chữ tuyệt đối bằng Banner 1) -->
                        <div class="hero-slide-item">
                            <img src="https://lh3.googleusercontent.com/d/157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT=w1600"
                                 data-drive-id="157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT"
                                 onerror="handleDriveImageError(this, 'Dự án kiến trúc Đà Nẵng')"
                                 alt="Dự án nhà phố biệt thự DANTECHCO Đà Nẵng"
                                 class="absolute inset-0 w-full h-full object-cover object-center">
                            <div class="absolute inset-0" style="background: linear-gradient(90deg, rgba(10,41,69,0.92) 0%, rgba(15,61,102,0.78) 58%, rgba(15,61,102,0.45) 100%);"></div>

                            <div class="relative z-10 w-full h-full flex items-center px-11 sm:px-16 md:px-20 lg:px-24 py-8 sm:py-10">
                                <div class="max-w-xl lg:max-w-2xl text-white">
                                    <p class="text-[11px] sm:text-xs md:text-sm font-bold tracking-widest uppercase text-brand-gold mb-2">
                                        KIẾN TẠO GIÁ TRỊ BỀN VỮNG
                                    </p>
                                    <h2 class="text-lg sm:text-2xl md:text-3xl lg:text-4xl font-extrabold leading-snug mb-2.5 sm:mb-3">
                                        Nhà Phố, Biệt Thự, Khách Sạn & Văn Phòng Chuyên Nghiệp
                                    </h2>
                                    <p class="text-xs sm:text-sm md:text-base text-slate-100 leading-relaxed mb-4 sm:mb-6">
                                        Đội ngũ kỹ sư giám sát tận tâm tại Sơn Trà và toàn TP Đà Nẵng. Bảo hành kết cấu dài hạn, hỗ trợ tư vấn kỹ thuật hoàn toàn miễn phí.
                                    </p>
                                    <div class="flex flex-wrap items-center gap-2.5 sm:gap-3">
                                        <a href="#san-pham-thi-cong" class="inline-flex items-center justify-center px-4 sm:px-6 py-2 sm:py-2.5 rounded-lg bg-brand-gold hover:bg-brand-goldDark text-white text-xs sm:text-sm font-semibold transition-colors shadow">
                                            Khám phá dịch vụ
                                        </a>
                                        <a href="#lien-he" class="inline-flex items-center justify-center px-4 sm:px-6 py-2 sm:py-2.5 rounded-lg bg-white/15 hover:bg-white/25 border border-white/40 text-white text-xs sm:text-sm font-semibold transition-colors">
                                            Liên hệ tư vấn
                                        </a>
                                    </div>
                                </div>
                            </div>
                        </div>

                    </div>

                    <!-- Nút chuyển slide trái/phải gọn gàng, không che chữ -->
                    <button type="button" onclick="prevSlide()" aria-label="Banner trước"
                            class="absolute left-2 sm:left-4 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-brand-gold text-white flex items-center justify-center transition-colors">
                        <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
                    </button>
                    <button type="button" onclick="nextSlide()" aria-label="Banner tiếp theo"
                            class="absolute right-2 sm:right-4 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-brand-gold text-white flex items-center justify-center transition-colors">
                        <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
                    </button>

                    <!-- Chấm chỉ báo 2 slide -->
                    <div class="absolute bottom-3 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                        <button type="button" onclick="goToSlide(0)" id="dot-0" aria-label="Chuyển banner 1" class="w-6 h-2 rounded-full bg-brand-gold transition-all"></button>
                        <button type="button" onclick="goToSlide(1)" id="dot-1" aria-label="Chuyển banner 2" class="w-2.5 h-2 rounded-full bg-white/60 transition-all"></button>
                    </div>
                </div>
            </div>
        </section>

        <!-- UX Builder: Section Dịch vụ tiêu biểu (3 khối chủ lực giống tintruongthinh.com) -->
        <section class="py-10 lg:py-12 bg-white">
            <div class="dantech-container">
                <div class="flatsome-title-wrap">
                    <h2 class="text-xl sm:text-2xl font-extrabold text-brand-navy uppercase tracking-tight">
                        Dịch Vụ Tiêu Biểu
                    </h2>
                    <div class="flatsome-title-line"></div>
                </div>

                <div class="grid grid-cols-1 md:grid-cols-3 gap-4 sm:gap-6">
                    <!-- Dịch vụ 1 -->
                    <a href="#san-pham-thi-cong" onclick="filterProducts('thiet-ke-kien-truc')" class="ux-card group relative rounded-xl overflow-hidden border border-slate-200 aspect-[16/10] block">
                        <img src="https://lh3.googleusercontent.com/d/1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv=w1000"
                             data-drive-id="1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv"
                             onerror="handleDriveImageError(this, 'Thiết kế kiến trúc')"
                             alt="Thiết kế kiến trúc DANTECHCO"
                             class="w-full h-full object-cover">
                        <div class="absolute inset-0 bg-gradient-to-t from-brand-navyDark/90 via-brand-navy/35 to-transparent flex flex-col justify-end p-5">
                            <h3 class="text-base sm:text-lg font-bold text-white uppercase tracking-wide">Thiết Kế Kiến Trúc</h3>
                            <p class="text-xs sm:text-sm text-slate-200 mt-1">Tối ưu công năng, thẩm mỹ hiện đại, hồ sơ kỹ thuật chi tiết</p>
                        </div>
                    </a>

                    <!-- Dịch vụ 2 -->
                    <a href="#san-pham-thi-cong" onclick="filterProducts('thi-cong-phan-tho')" class="ux-card group relative rounded-xl overflow-hidden border border-slate-200 aspect-[16/10] block">
                        <img src="https://lh3.googleusercontent.com/d/1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_=w1000"
                             data-drive-id="1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_"
                             onerror="handleDriveImageError(this, 'Thi công xây dựng')"
                             alt="Thi công xây dựng DANTECHCO"
                             class="w-full h-full object-cover">
                        <div class="absolute inset-0 bg-gradient-to-t from-brand-navyDark/90 via-brand-navy/35 to-transparent flex flex-col justify-end p-5">
                            <h3 class="text-base sm:text-lg font-bold text-white uppercase tracking-wide">Thi Công Xây Dựng</h3>
                            <p class="text-xs sm:text-sm text-slate-200 mt-1">Thi công phần thô, kết cấu thép, hoàn thiện công trình trọn gói</p>
                        </div>
                    </a>

                    <!-- Dịch vụ 3 -->
                    <a href="#san-pham-thi-cong" onclick="filterProducts('thi-cong-noi-that')" class="ux-card group relative rounded-xl overflow-hidden border border-slate-200 aspect-[16/10] block">
                        <img src="https://lh3.googleusercontent.com/d/1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO=w1000"
                             data-drive-id="1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO"
                             onerror="handleDriveImageError(this, 'Thi công nội thất')"
                             alt="Thi công nội thất DANTECHCO"
                             class="w-full h-full object-cover">
                        <div class="absolute inset-0 bg-gradient-to-t from-brand-navyDark/90 via-brand-navy/35 to-transparent flex flex-col justify-end p-5">
                            <h3 class="text-base sm:text-lg font-bold text-white uppercase tracking-wide">Thi Công Nội Thất</h3>
                            <p class="text-xs sm:text-sm text-slate-200 mt-1">Hoàn thiện nội thất tinh tế cho nhà phố, căn hộ, khách sạn & văn phòng</p>
                        </div>
                    </a>
                </div>
            </div>
        </section>

        <!-- UX Builder: Section Giới thiệu công ty & Thế mạnh của chúng tôi -->
        <section id="gioi-thieu" class="py-10 lg:py-14 bg-brand-surface border-y border-slate-200/80">
            <div class="dantech-container">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center mb-10">
                    <div class="lg:col-span-6">
                        <h2 class="text-xl sm:text-2xl font-extrabold text-brand-navy uppercase leading-snug mb-3">
                            CÔNG TY TNHH THƯƠNG MẠI VÀ DỊCH VỤ DANTECHCO
                        </h2>
                        <div class="w-14 h-1 bg-brand-gold rounded-full mb-4"></div>
                        <p class="text-sm sm:text-[15px] text-slate-600 leading-relaxed mb-3">
                            <strong>DANTECHCO</strong> (MST: 0402168482) là đơn vị chuyên sâu trong lĩnh vực <strong>Thiết kế – Thi công Xây dựng – Hoàn thiện Nội thất – Lắp đặt cơ điện M&amp;E</strong> các công trình Nhà phố, Biệt thự, Khách sạn, Căn hộ và Văn phòng tại khu vực TP Đà Nẵng và miền Trung.
                        </p>
                        <p class="text-sm sm:text-[15px] text-slate-600 leading-relaxed mb-5">
                            Đặt chữ <strong>“Tâm”</strong> và chuẩn mực kỹ thuật lên hàng đầu, mỗi công trình do DANTECHCO thực hiện đều đảm bảo tiêu chí <strong>An Toàn – Chất Lượng – Đúng Tiến Độ – Chi Phí Tối Ưu</strong>, mang lại sự an tâm trọn vẹn cho Quý Chủ đầu tư.
                        </p>
                        <div class="grid grid-cols-3 gap-3 text-center">
                            <div class="bg-white rounded-lg p-3 border border-slate-200">
                                <div class="text-lg sm:text-2xl font-extrabold text-brand-navy">100%</div>
                                <div class="text-[11px] sm:text-xs text-slate-500 mt-0.5">Vật tư chuẩn hãng</div>
                            </div>
                            <div class="bg-white rounded-lg p-3 border border-slate-200">
                                <div class="text-lg sm:text-2xl font-extrabold text-brand-gold">Đà Nẵng</div>
                                <div class="text-[11px] sm:text-xs text-slate-500 mt-0.5">Thi công toàn khu vực</div>
                            </div>
                            <div class="bg-white rounded-lg p-3 border border-slate-200">
                                <div class="text-lg sm:text-2xl font-extrabold text-brand-navy">24/7</div>
                                <div class="text-[11px] sm:text-xs text-slate-500 mt-0.5">Hỗ trợ & bảo hành</div>
                            </div>
                        </div>
                    </div>

                    <div class="lg:col-span-6">
                        <div class="rounded-xl overflow-hidden shadow-md border border-slate-200 aspect-[16/10] bg-white">
                            <img src="https://lh3.googleusercontent.com/d/1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR=w1200"
                                 data-drive-id="1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR"
                                 onerror="handleDriveImageError(this, 'Công trình thực tế DANTECHCO')"
                                 alt="Thi công công trình thực tế DANTECHCO"
                                 class="w-full h-full object-cover">
                        </div>
                    </div>
                </div>

                <!-- 6 Thế mạnh của chúng tôi (Giống bố cục icon-box Flatsome trên tintruongthinh.com) -->
                <div class="flatsome-title-wrap">
                    <h3 class="text-lg sm:text-xl font-extrabold text-brand-navy uppercase">
                        Thế Mạnh Của Chúng Tôi
                    </h3>
                    <div class="flatsome-title-line"></div>
                </div>

                <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4 sm:gap-5">
                    <div class="bg-white rounded-xl p-5 border border-slate-200 flex items-start gap-3.5">
                        <div class="w-11 h-11 rounded-lg bg-brand-navy text-brand-gold flex items-center justify-center shrink-0">
                            <i class="fa-solid fa-helmet-safety text-lg"></i>
                        </div>
                        <div>
                            <h4 class="text-sm sm:text-[15px] font-bold text-brand-navy mb-1">Đội ngũ kỹ sư chuyên nghiệp</h4>
                            <p class="text-xs sm:text-[13px] text-slate-600 leading-relaxed">Kiến trúc sư sáng tạo cùng đội ngũ kỹ sư giám sát và thợ thi công giàu kinh nghiệm thực tế.</p>
                        </div>
                    </div>

                    <div class="bg-white rounded-xl p-5 border border-slate-200 flex items-start gap-3.5">
                        <div class="w-11 h-11 rounded-lg bg-brand-navy text-brand-gold flex items-center justify-center shrink-0">
                            <i class="fa-solid fa-compass-drafting text-lg"></i>
                        </div>
                        <div>
                            <h4 class="text-sm sm:text-[15px] font-bold text-brand-navy mb-1">Giải pháp thiết kế hiện đại</h4>
                            <p class="text-xs sm:text-[13px] text-slate-600 leading-relaxed">Cập nhật xu hướng kiến trúc, vật liệu mới và quy trình thi công chuẩn kỹ thuật.</p>
                        </div>
                    </div>

                    <div class="bg-white rounded-xl p-5 border border-slate-200 flex items-start gap-3.5">
                        <div class="w-11 h-11 rounded-lg bg-brand-navy text-brand-gold flex items-center justify-center shrink-0">
                            <i class="fa-solid fa-clipboard-check text-lg"></i>
                        </div>
                        <div>
                            <h4 class="text-sm sm:text-[15px] font-bold text-brand-navy mb-1">Giám sát tiến độ chuẩn xác</h4>
                            <p class="text-xs sm:text-[13px] text-slate-600 leading-relaxed">Báo cáo tiến độ từng hạng mục định kỳ, bàn giao công trình đúng cam kết hợp đồng.</p>
                        </div>
                    </div>

                    <div class="bg-white rounded-xl p-5 border border-slate-200 flex items-start gap-3.5">
                        <div class="w-11 h-11 rounded-lg bg-brand-navy text-brand-gold flex items-center justify-center shrink-0">
                            <i class="fa-solid fa-shield-halved text-lg"></i>
                        </div>
                        <div>
                            <h4 class="text-sm sm:text-[15px] font-bold text-brand-navy mb-1">Bảo hành công trình lâu dài</h4>
                            <p class="text-xs sm:text-[13px] text-slate-600 leading-relaxed">Chính sách bảo hành kết cấu và hoàn thiện rõ ràng, có mặt xử lý nhanh chóng khi khách hàng cần.</p>
                        </div>
                    </div>

                    <div class="bg-white rounded-xl p-5 border border-slate-200 flex items-start gap-3.5">
                        <div class="w-11 h-11 rounded-lg bg-brand-navy text-brand-gold flex items-center justify-center shrink-0">
                            <i class="fa-solid fa-file-invoice-dollar text-lg"></i>
                        </div>
                        <div>
                            <h4 class="text-sm sm:text-[15px] font-bold text-brand-navy mb-1">Báo giá minh bạch, tối ưu</h4>
                            <p class="text-xs sm:text-[13px] text-slate-600 leading-relaxed">Dự toán chi tiết từng hạng mục, cam kết không phát sinh chi phí bất hợp lý trong thi công.</p>
                        </div>
                    </div>

                    <div class="bg-white rounded-xl p-5 border border-slate-200 flex items-start gap-3.5">
                        <div class="w-11 h-11 rounded-lg bg-brand-navy text-brand-gold flex items-center justify-center shrink-0">
                            <i class="fa-solid fa-headset text-lg"></i>
                        </div>
                        <div>
                            <h4 class="text-sm sm:text-[15px] font-bold text-brand-navy mb-1">Tư vấn kỹ thuật miễn phí</h4>
                            <p class="text-xs sm:text-[13px] text-slate-600 leading-relaxed">Hỗ trợ khảo sát thực địa, tư vấn phương án thiết kế và khái toán chi phí hoàn toàn miễn phí.</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- UX Builder: Section Danh mục Sản phẩm & Thi công xây dựng thực tế (9 ảnh thực tế từ Google Drive, 2 cột trên điện thoại, KHÔNG nhãn dán) -->
        <section id="san-pham-thi-cong" class="py-10 lg:py-14 bg-white">
            <div class="dantech-container">
                <div class="flatsome-title-wrap">
                    <h2 class="text-xl sm:text-2xl font-extrabold text-brand-navy uppercase tracking-tight">
                        Sản Phẩm &amp; Dịch Vụ Thi Công Thực Tế
                    </h2>
                    <div class="flatsome-title-line"></div>
                </div>

                <!-- Thanh danh mục trang chủ chữ nhỏ gọn, từng tên danh mục không bị xuống dòng -->
                <div id="product-tabs" class="flex flex-wrap items-center justify-center gap-1.5 sm:gap-2 mb-7">
                    <button type="button" onclick="filterProducts('all')" data-cat="all" class="cat-tab-btn active px-3 py-1.5 rounded-lg border border-slate-200 text-xs sm:text-[13px] font-semibold">
                        Tất cả
                    </button>
                    <button type="button" onclick="filterProducts('thiet-ke-kien-truc')" data-cat="thiet-ke-kien-truc" class="cat-tab-btn px-3 py-1.5 rounded-lg border border-slate-200 text-slate-700 hover:border-brand-navy text-xs sm:text-[13px] font-semibold">
                        Thiết kế Kiến trúc – Nội thất
                    </button>
                    <button type="button" onclick="filterProducts('thi-cong-phan-tho')" data-cat="thi-cong-phan-tho" class="cat-tab-btn px-3 py-1.5 rounded-lg border border-slate-200 text-slate-700 hover:border-brand-navy text-xs sm:text-[13px] font-semibold">
                        Thi công phần thô
                    </button>
                    <button type="button" onclick="filterProducts('thi-cong-hoan-thien')" data-cat="thi-cong-hoan-thien" class="cat-tab-btn px-3 py-1.5 rounded-lg border border-slate-200 text-slate-700 hover:border-brand-navy text-xs sm:text-[13px] font-semibold">
                        Thi công hoàn thiện
                    </button>
                    <button type="button" onclick="filterProducts('thi-cong-noi-that')" data-cat="thi-cong-noi-that" class="cat-tab-btn px-3 py-1.5 rounded-lg border border-slate-200 text-slate-700 hover:border-brand-navy text-xs sm:text-[13px] font-semibold">
                        Thi công nội thất
                    </button>
                </div>

                <!-- Lưới sản phẩm: 2 cột trên điện thoại, 3 cột trên desktop vừa, 3 cột/4 cột cân đối; tên sản phẩm rõ ràng không tràn viền -->
                <div id="products-grid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-3 xl:grid-cols-4 gap-3 sm:gap-5">
                    <!-- Được render tự động bằng JavaScript với đầy đủ 9 ảnh thực tế từ Google Drive -->
                </div>
            </div>
        </section>

        <!-- UX Builder: Section Các Dự Án Tại Đà Nẵng (10 ảnh thực tế từ Google Drive, 2 cột trên điện thoại, KHÔNG nhãn dán) -->
        <section id="du-an-da-nang" class="py-10 lg:py-14 bg-brand-surface border-t border-slate-200/80">
            <div class="dantech-container">
                <div class="flatsome-title-wrap">
                    <h2 class="text-xl sm:text-2xl font-extrabold text-brand-navy uppercase tracking-tight">
                        Các Dự Án Tiêu Biểu Tại Đà Nẵng
                    </h2>
                    <div class="flatsome-title-line"></div>
                </div>

                <!-- Bộ lọc danh mục dự án theo web mẫu tintruongthinh.com, chữ nhỏ gọn, không xuống dòng tên danh mục -->
                <div id="project-tabs" class="flex flex-wrap items-center justify-center gap-1.5 sm:gap-2 mb-7">
                    <button type="button" onclick="filterProjects('all')" data-cat="all" class="cat-tab-btn active px-3 py-1.5 rounded-lg border border-slate-200 text-xs sm:text-[13px] font-semibold">
                        Tất cả
                    </button>
                    <button type="button" onclick="filterProjects('khach-san-can-ho')" data-cat="khach-san-can-ho" class="cat-tab-btn px-3 py-1.5 rounded-lg border border-slate-200 text-slate-700 hover:border-brand-navy text-xs sm:text-[13px] font-semibold">
                        Khách sạn – Căn hộ
                    </button>
                    <button type="button" onclick="filterProjects('biet-thu')" data-cat="biet-thu" class="cat-tab-btn px-3 py-1.5 rounded-lg border border-slate-200 text-slate-700 hover:border-brand-navy text-xs sm:text-[13px] font-semibold">
                        Biệt thự
                    </button>
                    <button type="button" onclick="filterProjects('nha-pho')" data-cat="nha-pho" class="cat-tab-btn px-3 py-1.5 rounded-lg border border-slate-200 text-slate-700 hover:border-brand-navy text-xs sm:text-[13px] font-semibold">
                        Nhà phố
                    </button>
                    <button type="button" onclick="filterProjects('van-phong')" data-cat="van-phong" class="cat-tab-btn px-3 py-1.5 rounded-lg border border-slate-200 text-slate-700 hover:border-brand-navy text-xs sm:text-[13px] font-semibold">
                        Văn phòng
                    </button>
                </div>

                <!-- Lưới 10 dự án thực tế Đà Nẵng: 2 cột trên điện thoại, 4-5 cột trên desktop -->
                <div id="projects-grid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 xl:grid-cols-5 gap-3 sm:gap-5">
                    <!-- Được render tự động bằng JavaScript với đầy đủ 10 ảnh thực tế từ Google Drive -->
                </div>
            </div>
        </section>

        <!-- UX Builder: Section Danh mục Các Đối Tác -->
        <section id="doi-tac" class="py-10 lg:py-12 bg-white border-t border-slate-200/80">
            <div class="dantech-container">
                <div class="flatsome-title-wrap">
                    <h2 class="text-xl sm:text-2xl font-extrabold text-brand-navy uppercase tracking-tight">
                        Đối Tác &amp; Nhà Cung Cấp Vật Tư
                    </h2>
                    <div class="flatsome-title-line"></div>
                </div>

                <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-6 gap-3 sm:gap-4">
                    <!-- Đối tác 1 -->
                    <div class="rounded-xl border border-slate-200 bg-brand-surface hover:bg-white hover:border-brand-navy/40 transition-all p-4 flex flex-col items-center justify-center text-center min-h-[88px]">
                        <span class="text-sm sm:text-base font-extrabold tracking-tight text-brand-navy">HÒA PHÁT</span>
                        <span class="text-[11px] text-slate-500 mt-0.5">Thép xây dựng</span>
                    </div>
                    <!-- Đối tác 2 -->
                    <div class="rounded-xl border border-slate-200 bg-brand-surface hover:bg-white hover:border-brand-navy/40 transition-all p-4 flex flex-col items-center justify-center text-center min-h-[88px]">
                        <span class="text-sm sm:text-base font-extrabold tracking-tight text-brand-navy">VICEM HẢI VÂN</span>
                        <span class="text-[11px] text-slate-500 mt-0.5">Xi măng công trình</span>
                    </div>
                    <!-- Đối tác 3 -->
                    <div class="rounded-xl border border-slate-200 bg-brand-surface hover:bg-white hover:border-brand-navy/40 transition-all p-4 flex flex-col items-center justify-center text-center min-h-[88px]">
                        <span class="text-sm sm:text-base font-extrabold tracking-tight text-brand-navy">JOTUN</span>
                        <span class="text-[11px] text-slate-500 mt-0.5">Sơn &amp; Chống thấm</span>
                    </div>
                    <!-- Đối tác 4 -->
                    <div class="rounded-xl border border-slate-200 bg-brand-surface hover:bg-white hover:border-brand-navy/40 transition-all p-4 flex flex-col items-center justify-center text-center min-h-[88px]">
                        <span class="text-sm sm:text-base font-extrabold tracking-tight text-brand-navy">AN CƯỜNG</span>
                        <span class="text-[11px] text-slate-500 mt-0.5">Vật liệu nội thất</span>
                    </div>
                    <!-- Đối tác 5 -->
                    <div class="rounded-xl border border-slate-200 bg-brand-surface hover:bg-white hover:border-brand-navy/40 transition-all p-4 flex flex-col items-center justify-center text-center min-h-[88px]">
                        <span class="text-sm sm:text-base font-extrabold tracking-tight text-brand-navy">PANASONIC</span>
                        <span class="text-[11px] text-slate-500 mt-0.5">Thiết bị điện M&amp;E</span>
                    </div>
                    <!-- Đối tác 6 -->
                    <div class="rounded-xl border border-slate-200 bg-brand-surface hover:bg-white hover:border-brand-navy/40 transition-all p-4 flex flex-col items-center justify-center text-center min-h-[88px]">
                        <span class="text-sm sm:text-base font-extrabold tracking-tight text-brand-navy">ĐỒNG TÂM</span>
                        <span class="text-[11px] text-slate-500 mt-0.5">Gạch ốp lát &amp; Sứ</span>
                    </div>
                </div>
            </div>
        </section>

        <!-- UX Builder: Section Form Yêu Cầu Tư Vấn & Báo Giá trên trang chủ (Giống form mẫu tintruongthinh.com) -->
        <section id="bao-gia" class="py-10 lg:py-14 bg-brand-navy text-white">
            <div class="dantech-container">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center">
                    <!-- Cột trái: Thông tin tư vấn & Cam kết báo giá -->
                    <div class="lg:col-span-5">
                        <h2 class="text-xl sm:text-2xl lg:text-3xl font-extrabold uppercase leading-snug mb-3">
                            Đăng Ký Tư Vấn &amp; Nhận Báo Giá Miễn Phí
                        </h2>
                        <div class="w-14 h-1 bg-brand-gold rounded-full mb-4"></div>
                        <p class="text-sm sm:text-[15px] text-slate-200 leading-relaxed mb-5">
                            Quý khách đang chuẩn bị xây dựng nhà phố, biệt thự, khách sạn, căn hộ hay cải tạo văn phòng tại Đà Nẵng? Hãy gửi thông tin yêu cầu, kỹ sư DANTECHCO sẽ liên hệ khảo sát và lập bảng dự toán chi tiết trong vòng 24 giờ.
                        </p>
                        <ul class="space-y-2.5 text-sm text-slate-100">
                            <li class="flex items-center gap-2.5">
                                <i class="fa-solid fa-circle-check text-brand-gold"></i>
                                <span>Báo giá thiết kế kiến trúc &amp; nội thất chi tiết</span>
                            </li>
                            <li class="flex items-center gap-2.5">
                                <i class="fa-solid fa-circle-check text-brand-gold"></i>
                                <span>Báo giá thi công phần thô &amp; nhân công hoàn thiện</span>
                            </li>
                            <li class="flex items-center gap-2.5">
                                <i class="fa-solid fa-circle-check text-brand-gold"></i>
                                <span>Báo giá thi công xây dựng trọn gói chìa khóa trao tay</span>
                            </li>
                            <li class="flex items-center gap-2.5">
                                <i class="fa-solid fa-phone-volume text-brand-gold"></i>
                                <span>Hotline hỗ trợ trực tiếp: <a href="tel:0905294687" class="font-bold text-brand-gold hover:underline">0905.294.687</a></span>
                            </li>
                        </ul>
                    </div>

                    <!-- Cột phải: Form nhập yêu cầu & báo giá -->
                    <div class="lg:col-span-7">
                        <form id="quote-form" onsubmit="submitQuoteForm(event)" class="bg-white text-slate-800 rounded-xl p-5 sm:p-7 shadow-xl">
                            <h3 class="text-base sm:text-lg font-bold text-brand-navy mb-4">
                                Thông Tin Yêu Cầu Báo Giá
                            </h3>
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5 sm:gap-4">
                                <div>
                                    <label for="q-name" class="block text-xs font-semibold text-slate-700 mb-1">Họ và tên *</label>
                                    <input id="q-name" type="text" required placeholder="Nhập họ tên của bạn"
                                           class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-brand-navy focus:ring-1 focus:ring-brand-navy">
                                </div>
                                <div>
                                    <label for="q-phone" class="block text-xs font-semibold text-slate-700 mb-1">Số điện thoại *</label>
                                    <input id="q-phone" type="tel" required placeholder="VD: 0905.294.687"
                                           class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-brand-navy focus:ring-1 focus:ring-brand-navy">
                                </div>
                                <div>
                                    <label for="q-type" class="block text-xs font-semibold text-slate-700 mb-1">Loại công trình</label>
                                    <select id="q-type" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm bg-white focus:outline-none focus:border-brand-navy focus:ring-1 focus:ring-brand-navy">
                                        <option value="Nhà phố">Nhà phố</option>
                                        <option value="Biệt thự">Biệt thự</option>
                                        <option value="Khách sạn – Căn hộ cho thuê">Khách sạn – Căn hộ cho thuê</option>
                                        <option value="Văn phòng – Showroom">Văn phòng – Showroom</option>
                                        <option value="Thi công phần thô">Thi công phần thô</option>
                                        <option value="Thi công hoàn thiện / Nội thất">Thi công hoàn thiện / Nội thất</option>
                                        <option value="Cải tạo sửa chữa công trình">Cải tạo sửa chữa công trình</option>
                                    </select>
                                </div>
                                <div>
                                    <label for="q-budget" class="block text-xs font-semibold text-slate-700 mb-1">Mức đầu tư dự kiến</label>
                                    <select id="q-budget" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm bg-white focus:outline-none focus:border-brand-navy focus:ring-1 focus:ring-brand-navy">
                                        <option value="Chưa xác định">Chưa xác định</option>
                                        <option value="Dưới 500 triệu">Dưới 500 triệu</option>
                                        <option value="500 triệu - 1 tỷ">500 triệu - 1 tỷ</option>
                                        <option value="1 tỷ - 2 tỷ">1 tỷ - 2 tỷ</option>
                                        <option value="2 tỷ - 3 tỷ">2 tỷ - 3 tỷ</option>
                                        <option value="Trên 3 tỷ">Trên 3 tỷ</option>
                                    </select>
                                </div>
                                <div class="sm:col-span-2">
                                    <label for="q-note" class="block text-xs font-semibold text-slate-700 mb-1">Mô tả diện tích, địa điểm hoặc yêu cầu cụ thể</label>
                                    <textarea id="q-note" rows="3" placeholder="VD: Xây nhà phố 3 tầng diện tích 5x20m tại Sơn Trà, Đà Nẵng..."
                                              class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-brand-navy focus:ring-1 focus:ring-brand-navy"></textarea>
                                </div>
                            </div>

                            <!-- Thông báo gửi form thành công (không dùng alert) -->
                            <div id="quote-feedback" class="hidden mt-4 p-3.5 rounded-lg bg-emerald-50 border border-emerald-200 text-emerald-800 text-sm flex items-start gap-2.5">
                                <i class="fa-solid fa-circle-check text-emerald-600 mt-0.5"></i>
                                <span id="quote-feedback-text"></span>
                            </div>

                            <div class="mt-4 flex flex-col sm:flex-row sm:items-center justify-between gap-3">
                                <span class="text-xs text-slate-500">Thông tin của Quý khách được bảo mật tuyệt đối.</span>
                                <button type="submit" class="px-6 py-2.5 rounded-lg bg-brand-gold hover:bg-brand-goldDark text-white font-bold text-sm transition-colors shadow cursor-pointer">
                                    Gửi Yêu Cầu Báo Giá
                                </button>
                            </div>
                        </form>
                    </div>
                </div>
            </div>
        </section>

        <!-- UX Builder: Section Danh mục Các Bài Viết / Tin Tức trên trang chủ -->
        <section id="tin-tuc" class="py-10 lg:py-14 bg-white">
            <div class="dantech-container">
                <div class="flatsome-title-wrap">
                    <h2 class="text-xl sm:text-2xl font-extrabold text-brand-navy uppercase tracking-tight">
                        Tin Tức &amp; Kinh Nghiệm Xây Dựng
                    </h2>
                    <div class="flatsome-title-line"></div>
                </div>

                <div id="articles-grid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4 sm:gap-5">
                    <!-- Render bởi JavaScript -->
                </div>
            </div>
        </section>

        <!-- UX Builder: Section Google Map & Fanpage Facebook ngay ngoài trang chủ -->
        <section id="lien-he" class="py-10 lg:py-14 bg-brand-surface border-t border-slate-200/80">
            <div class="dantech-container">
                <div class="flatsome-title-wrap">
                    <h2 class="text-xl sm:text-2xl font-extrabold text-brand-navy uppercase tracking-tight">
                        Bản Đồ Chỉ Đường &amp; Kết Nối Fanpage
                    </h2>
                    <div class="flatsome-title-line"></div>
                </div>

                <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 lg:gap-6 items-stretch">
                    <!-- Cột trái: Google Map địa chỉ 54 Mân Quang 4, Phường Sơn Trà, TP Đà Nẵng -->
                    <div class="lg:col-span-7 bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm flex flex-col">
                        <div class="px-4 py-3 border-b border-slate-100 flex flex-wrap items-center justify-between gap-2">
                            <div class="flex items-center gap-2 min-w-0">
                                <i class="fa-solid fa-location-dot text-brand-gold"></i>
                                <span class="text-xs sm:text-sm font-bold text-brand-navy truncate">
                                    54 Mân Quang 4, Phường Sơn Trà, TP Đà Nẵng
                                </span>
                            </div>
                            <a href="https://maps.google.com/?q=54+M%C3%A2n+Quang+4,+S%C6%A1n+Tr%C3%A0,+%C4%90%C3%A0+N%E1%BA%B5ng"
                               target="_blank" rel="noopener noreferrer"
                               class="text-xs font-semibold text-brand-navy hover:text-brand-gold whitespace-nowrap">
                                Mở Google Maps <i class="fa-solid fa-arrow-up-right-from-square text-[10px] ml-0.5"></i>
                            </a>
                        </div>
                        <div class="w-full h-[300px] sm:h-[340px] flex-1 bg-slate-100">
                            <iframe
                                title="Bản đồ vị trí CÔNG TY TNHH TM & DV DANTECHCO - 54 Mân Quang 4, Sơn Trà, Đà Nẵng"
                                src="https://maps.google.com/maps?q=54+M%C3%A2n+Quang+4,+S%C6%A1n+Tr%C3%A0,+%C4%90%C3%A0+N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                                class="w-full h-full border-0"
                                loading="lazy"
                                referrerpolicy="no-referrer-when-downgrade"
                                allowfullscreen>
                            </iframe>
                        </div>
                    </div>

                    <!-- Cột phải: Fanpage Facebook DANTECHCO hiển thị trực quan trên trang chủ -->
                    <div class="lg:col-span-5 bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm flex flex-col">
                        <div class="px-4 py-3 border-b border-slate-100 flex items-center justify-between">
                            <div class="flex items-center gap-2">
                                <i class="fa-brands fa-facebook text-[#1877F2] text-base"></i>
                                <span class="text-xs sm:text-sm font-bold text-brand-navy">Fanpage Chính Thức</span>
                            </div>
                            <span class="text-xs text-slate-500">Facebook</span>
                        </div>

                        <!-- Khung giao diện Fanpage Facebook chuẩn đẹp, tương thích mọi trình duyệt -->
                        <div class="relative h-36 bg-brand-navy overflow-hidden">
                            <img src="https://lh3.googleusercontent.com/d/1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff=w1000"
                                 data-drive-id="1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff"
                                 onerror="handleDriveImageError(this, 'Fanpage DANTECHCO')"
                                 alt="Ảnh bìa Fanpage DANTECHCO"
                                 class="w-full h-full object-cover opacity-75">
                            <div class="absolute inset-0 bg-gradient-to-t from-brand-navyDark/90 via-brand-navyDark/35 to-transparent"></div>
                            <div class="absolute bottom-3 left-4 right-4 flex items-center gap-3">
                                <div class="w-12 h-12 rounded-lg bg-white p-1 shadow shrink-0 flex items-center justify-center">
                                    <svg class="w-full h-full" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                                        <rect width="64" height="64" rx="10" fill="#0F3D66"/>
                                        <path d="M14 48V24.5L32 13L50 24.5V48H41.5V29.5H22.5V48H14Z" fill="#FFFFFF"/>
                                        <path d="M32 13L50 24.5V30.5L32 19L14 30.5V24.5L32 13Z" fill="#D98A1C"/>
                                        <rect x="28.5" y="34" width="7" height="14" rx="1" fill="#D98A1C"/>
                                    </svg>
                                </div>
                                <div class="min-w-0 text-white">
                                    <h3 class="text-sm font-bold truncate">CÔNG TY TNHH TM &amp; DV DANTECHCO</h3>
                                    <p class="text-[11px] text-slate-200 truncate">Thiết Kế &amp; Thi Công Xây Dựng Đà Nẵng</p>
                                </div>
                            </div>
                        </div>

                        <div class="p-4 flex-1 flex flex-col justify-between gap-4">
                            <div class="space-y-2 text-xs sm:text-[13px] text-slate-600">
                                <p class="leading-relaxed">
                                    Theo dõi Fanpage DANTECHCO để cập nhật hình ảnh thực tế các công trình đang thi công tại Đà Nẵng, mẫu nhà đẹp và bảng báo giá xây dựng mới nhất.
                                </p>
                                <div class="pt-2 border-t border-slate-100 space-y-1.5 text-xs text-slate-600">
                                    <div class="flex items-center gap-2">
                                        <i class="fa-solid fa-globe text-brand-navy w-4 text-center"></i>
                                        <span>dantechco.com</span>
                                    </div>
                                    <div class="flex items-center gap-2">
                                        <i class="fa-solid fa-phone text-brand-navy w-4 text-center"></i>
                                        <span>0905.294.687</span>
                                    </div>
                                    <div class="flex items-center gap-2">
                                        <i class="fa-solid fa-clock text-brand-navy w-4 text-center"></i>
                                        <span>Thứ 2 – Thứ 7: 07:30 – 17:30</span>
                                    </div>
                                </div>
                            </div>

                            <div class="grid grid-cols-2 gap-2.5">
                                <a href="https://www.facebook.com/" target="_blank" rel="noopener noreferrer"
                                   class="inline-flex items-center justify-center gap-1.5 px-3 py-2.5 rounded-lg bg-[#1877F2] hover:bg-[#1464CC] text-white text-xs sm:text-sm font-semibold transition-colors">
                                    <i class="fa-brands fa-facebook-f"></i>
                                    <span>Thích Trang</span>
                                </a>
                                <a href="https://zalo.me/0905294687" target="_blank" rel="noopener noreferrer"
                                   class="inline-flex items-center justify-center gap-1.5 px-3 py-2.5 rounded-lg bg-brand-navy hover:bg-brand-navyDark text-white text-xs sm:text-sm font-semibold transition-colors">
                                    <i class="fa-solid fa-comments"></i>
                                    <span>Nhắn Tin Ngay</span>
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

    </main>

    <!-- UX Builder: Footer 3 cột chuẩn Flatsome đồng bộ màu thương hiệu -->
    <footer class="bg-brand-navyDark text-slate-300 pt-10 pb-6 border-t-4 border-brand-gold">
        <div class="dantech-container">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-7 pb-8 border-b border-white/10">
                <!-- Cột 1: Thông tin doanh nghiệp -->
                <div class="lg:col-span-5 space-y-3">
                    <div class="flex items-center gap-2.5">
                        <svg class="w-9 h-9 shrink-0" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <rect width="64" height="64" rx="12" fill="#0F3D66"/>
                            <path d="M14 48V24.5L32 13L50 24.5V48H41.5V29.5H22.5V48H14Z" fill="#FFFFFF"/>
                            <path d="M32 13L50 24.5V30.5L32 19L14 30.5V24.5L32 13Z" fill="#D98A1C"/>
                            <rect x="28.5" y="34" width="7" height="14" rx="1" fill="#D98A1C"/>
                        </svg>
                        <div>
                            <div class="text-base font-extrabold text-white tracking-tight">
                                DAN<span class="text-brand-gold">TECH</span>CO
                            </div>
                            <div class="text-[11px] text-slate-400">CÔNG TY TNHH THƯƠNG MẠI VÀ DỊCH VỤ DANTECHCO</div>
                        </div>
                    </div>
                    <ul class="space-y-2 text-xs sm:text-[13px]">
                        <li class="flex items-start gap-2.5">
                            <i class="fa-solid fa-location-dot text-brand-gold mt-1"></i>
                            <span>Trụ sở: 54 Mân Quang 4, Phường Sơn Trà, TP Đà Nẵng</span>
                        </li>
                        <li class="flex items-center gap-2.5">
                            <i class="fa-solid fa-phone text-brand-gold"></i>
                            <span>Hotline: <a href="tel:0905294687" class="text-white font-semibold hover:text-brand-gold">0905.294.687</a></span>
                        </li>
                        <li class="flex items-center gap-2.5">
                            <i class="fa-solid fa-globe text-brand-gold"></i>
                            <span>Website: <a href="https://dantechco.com" class="text-white hover:text-brand-gold">dantechco.com</a></span>
                        </li>
                        <li class="flex items-center gap-2.5">
                            <i class="fa-solid fa-file-contract text-brand-gold"></i>
                            <span>Mã số thuế: 0402168482</span>
                        </li>
                    </ul>
                </div>

                <!-- Cột 2: Lĩnh vực hoạt động -->
                <div class="lg:col-span-4">
                    <h3 class="text-sm font-bold text-white uppercase tracking-wider mb-3">Lĩnh Vực Hoạt Động</h3>
                    <ul class="space-y-2 text-xs sm:text-[13px]">
                        <li><a href="#san-pham-thi-cong" onclick="filterProducts('thiet-ke-kien-truc')" class="hover:text-brand-gold transition-colors">Thiết kế Kiến trúc – Nội thất</a></li>
                        <li><a href="#san-pham-thi-cong" onclick="filterProducts('thi-cong-phan-tho')" class="hover:text-brand-gold transition-colors">Thi công phần thô công trình</a></li>
                        <li><a href="#san-pham-thi-cong" onclick="filterProducts('thi-cong-hoan-thien')" class="hover:text-brand-gold transition-colors">Thi công hoàn thiện &amp; Cơ điện M&amp;E</a></li>
                        <li><a href="#san-pham-thi-cong" onclick="filterProducts('thi-cong-noi-that')" class="hover:text-brand-gold transition-colors">Thi công nội thất &amp; Cải tạo nhà</a></li>
                        <li><a href="#bao-gia" class="hover:text-brand-gold transition-colors">Báo giá thi công xây dựng trọn gói</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Công trình & Liên kết nhanh -->
                <div class="lg:col-span-3">
                    <h3 class="text-sm font-bold text-white uppercase tracking-wider mb-3">Công Trình Đà Nẵng</h3>
                    <ul class="space-y-2 text-xs sm:text-[13px]">
                        <li><a href="#du-an-da-nang" onclick="filterProjects('nha-pho')" class="hover:text-brand-gold transition-colors">Thi công Nhà phố Đà Nẵng</a></li>
                        <li><a href="#du-an-da-nang" onclick="filterProjects('biet-thu')" class="hover:text-brand-gold transition-colors">Thi công Biệt thự cao cấp</a></li>
                        <li><a href="#du-an-da-nang" onclick="filterProjects('khach-san-can-ho')" class="hover:text-brand-gold transition-colors">Khách sạn – Căn hộ cho thuê</a></li>
                        <li><a href="#du-an-da-nang" onclick="filterProjects('van-phong')" class="hover:text-brand-gold transition-colors">Văn phòng – Showroom</a></li>
                        <li><a href="#tin-tuc" class="hover:text-brand-gold transition-colors">Kinh nghiệm &amp; Tin tức xây dựng</a></li>
                    </ul>
                </div>
            </div>

            <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-slate-400 text-center sm:text-left">
                <p>Copyright © 2026 CÔNG TY TNHH THƯƠNG MẠI VÀ DỊCH VỤ DANTECHCO (dantechco.com).</p>
                <p>Thiết kế chuẩn giao diện Flatsome UX Builder.</p>
            </div>
        </div>
    </footer>

    <!-- Các nút liên hệ nổi bật Zalo, Facebook, Hotline tương thích mượt mà trên Máy tính và Điện thoại -->
    <div class="fixed bottom-4 right-3 sm:bottom-6 sm:right-5 z-50 flex flex-col items-end gap-2.5">
        <!-- Nút Facebook -->
        <a href="https://www.facebook.com/" target="_blank" rel="noopener noreferrer" aria-label="Liên hệ Facebook DANTECHCO"
           class="group flex items-center gap-2 bg-[#1877F2] hover:bg-[#1464CC] text-white rounded-full shadow-lg px-3 py-2.5 sm:px-3.5 transition-all">
            <i class="fa-brands fa-facebook-messenger text-base sm:text-lg w-5 text-center"></i>
            <span class="hidden sm:inline text-xs font-bold pr-0.5">Facebook</span>
        </a>

        <!-- Nút Zalo -->
        <a href="https://zalo.me/0905294687" target="_blank" rel="noopener noreferrer" aria-label="Chat Zalo 0905.294.687"
           class="group flex items-center gap-2 bg-[#0068FF] hover:bg-[#0054CC] text-white rounded-full shadow-lg px-3 py-2.5 sm:px-3.5 transition-all">
            <span class="inline-flex items-center justify-center w-5 h-5 rounded-full bg-white text-[#0068FF] font-extrabold text-[10px]">Zalo</span>
            <span class="hidden sm:inline text-xs font-bold pr-0.5">Chat Zalo</span>
        </a>

        <!-- Nút Hotline nổi bật -->
        <a href="tel:0905294687" aria-label="Gọi Hotline 0905.294.687"
           class="hotline-pulse flex items-center gap-2 bg-brand-gold hover:bg-brand-goldDark text-white rounded-full shadow-lg px-3 py-2.5 sm:px-4 transition-all">
            <i class="fa-solid fa-phone-volume text-sm sm:text-base w-5 text-center"></i>
            <span class="text-xs sm:text-[13px] font-extrabold whitespace-nowrap">0905.294.687</span>
        </a>
    </div>

    <!-- Modal Xem Chi Tiết Sản Phẩm / Dự Án / Bài Viết -->
    <div id="detail-modal" class="hidden fixed inset-0 z-50 bg-black/65 backdrop-blur-xs flex items-center justify-center p-3 sm:p-5" onclick="closeDetailModal(event)">
        <div class="bg-white rounded-xl max-w-2xl w-full max-h-[90vh] overflow-y-auto shadow-2xl border border-slate-200" onclick="event.stopPropagation()">
            <div class="sticky top-0 bg-white px-4 sm:px-5 py-3.5 border-b border-slate-200 flex items-center justify-between gap-3 z-10">
                <h3 id="modal-title" class="text-sm sm:text-base font-bold text-brand-navy leading-snug"></h3>
                <button type="button" onclick="hideDetailModal()" aria-label="Đóng cửa sổ"
                        class="w-8 h-8 rounded-full bg-slate-100 hover:bg-slate-200 text-slate-600 flex items-center justify-center shrink-0">
                    <i class="fa-solid fa-xmark"></i>
                </button>
            </div>
            <div class="p-4 sm:p-5">
                <div id="modal-image-wrap" class="rounded-lg overflow-hidden mb-4 bg-slate-100 aspect-[16/10]">
                    <img id="modal-image" src="" alt="" class="w-full h-full object-cover">
                </div>
                <p id="modal-meta" class="text-xs font-semibold text-brand-gold uppercase tracking-wide mb-2"></p>
                <div id="modal-desc" class="text-sm text-slate-600 leading-relaxed space-y-2.5"></div>
                <div class="mt-5 pt-4 border-t border-slate-100 flex flex-wrap items-center justify-between gap-3">
                    <a href="tel:0905294687" class="inline-flex items-center gap-2 text-sm font-bold text-brand-navy hover:text-brand-gold">
                        <i class="fa-solid fa-phone"></i> Hotline: 0905.294.687
                    </a>
                    <button type="button" onclick="requestQuoteFromModal()" class="px-5 py-2 rounded-lg bg-brand-gold hover:bg-brand-goldDark text-white text-xs sm:text-sm font-semibold transition-colors">
                        Nhận báo giá hạng mục này
                    </button>
                </div>
            </div>
        </div>
    </div>

    <script>
        /* =========================================================================
           1. HÀM XỬ LÝ TẢI ẢNH THỰC TẾ TỪ GOOGLE DRIVE AN TOÀN (ĐA TẦNG FALLBACK)
           ========================================================================= */
        function getDriveImageUrl(fileId) {
            return 'https://lh3.googleusercontent.com/d/' + fileId + '=w1000';
        }

        function handleDriveImageError(imgEl, fallbackLabel) {
            const step = parseInt(imgEl.getAttribute('data-fallback-step') || '0', 10);
            const fileId = imgEl.getAttribute('data-drive-id');
            if (step === 0 && fileId) {
                imgEl.setAttribute('data-fallback-step', '1');
                imgEl.src = 'https://drive.google.com/thumbnail?id=' + fileId + '&sz=w1000';
            } else if (step === 1 && fileId) {
                imgEl.setAttribute('data-fallback-step', '2');
                imgEl.src = 'https://drive.google.com/uc?export=view&id=' + fileId;
            } else {
                imgEl.onerror = null;
                const text = encodeURIComponent(fallbackLabel || 'DANTECHCO');
                imgEl.src = 'https://placehold.co/800x600/0F3D66/FFFFFF?text=' + text;
            }
        }

        /* =========================================================================
           2. DỮ LIỆU 9 ẢNH THỰC TẾ THI CÔNG XÂY DỰNG (TỪ LINK GOOGLE DRIVE CỦA BẠN)
           ========================================================================= */
        const productsData = [
            {
                id: 'sp-1',
                category: 'thi-cong-phan-tho',
                categoryName: 'Thi công phần thô',
                title: 'Thi công phần thô nhà phố trọn gói',
                driveId: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
                summary: 'Thi công móng, cột, dầm, sàn bê tông cốt thép và tường xây đúng tiêu chuẩn kỹ thuật.',
                details: 'Hạng mục thi công phần thô của DANTECHCO bao gồm đào móng, gia công lắp dựng cốt thép, đổ bê tông tươi đúng mác thiết kế, xây tô tường chuẩn phẳng và đi âm hệ thống điện nước cơ bản. Sử dụng thép Hòa Phát và xi măng Vicem Hải Vân chính hãng.'
            },
            {
                id: 'sp-2',
                category: 'thi-cong-hoan-thien',
                categoryName: 'Thi công hoàn thiện',
                title: 'Thi công hoàn thiện mặt tiền & ngoại thất',
                driveId: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
                summary: 'Ốp đá mặt tiền, lắp cửa nhôm kính, lan can và sơn ngoại thất bền đẹp với khí hậu biển Đà Nẵng.',
                details: 'Dịch vụ thi công hoàn thiện mặt tiền và ngoại thất chú trọng khả năng chống thấm, chống ăn mòn muối biển tại Đà Nẵng. Bao gồm ốp lát gạch đá cao cấp, lắp đặt hệ cửa nhôm kính đồng bộ, trần thạch cao và sơn phủ ngoại thất Jotun.'
            },
            {
                id: 'sp-3',
                category: 'thiet-ke-kien-truc',
                categoryName: 'Thiết kế Kiến trúc – Nội thất',
                title: 'Thiết kế kiến trúc nhà phố hiện đại',
                driveId: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
                summary: 'Hồ sơ thiết kế kiến trúc, kết cấu, điện nước và phối cảnh 3D tối ưu ánh sáng tự nhiên.',
                details: 'Bộ hồ sơ thiết kế đầy đủ gồm bản vẽ kiến trúc, bản vẽ kết cấu chi tiết, sơ đồ hệ thống cơ điện M&E, phối cảnh 3D ngoại thất và hỗ trợ hồ sơ xin phép xây dựng nhanh chóng tại TP Đà Nẵng.'
            },
            {
                id: 'sp-4',
                category: 'thi-cong-phan-tho',
                categoryName: 'Thi công phần thô',
                title: 'Thi công kết cấu thép & nhà xưởng',
                driveId: '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_',
                summary: 'Gia công, lắp dựng khung kèo thép tiền chế, nhà kho và công trình công nghiệp bền vững.',
                details: 'DANTECHCO trực tiếp thiết kế, gia công cấu kiện kim loại và lắp dựng kết cấu thép cho nhà xưởng, showroom, nhà kho và nhà thép tiền chế dân dụng với độ chính xác và an toàn lao động cao nhất.'
            },
            {
                id: 'sp-5',
                category: 'thi-cong-noi-that',
                categoryName: 'Thi công nội thất',
                title: 'Thi công nội thất căn hộ & nhà ở',
                driveId: '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO',
                summary: 'Sản xuất và lắp đặt tủ bếp, giường tủ, vách trang trí đồng bộ theo bản vẽ thiết kế.',
                details: 'Thi công hoàn thiện nội thất gỗ công nghiệp chống ẩm An Cường và gỗ tự nhiên cao cấp. Đảm bảo chuẩn kích thước, phụ kiện giảm chấn chính hãng và hoàn thiện sắc nét từng đường nét.'
            },
            {
                id: 'sp-6',
                category: 'thi-cong-hoan-thien',
                categoryName: 'Thi công hoàn thiện',
                title: 'Lắp đặt hệ thống cơ điện M&E công trình',
                driveId: '1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t',
                summary: 'Thi công điện chiếu sáng, cấp thoát nước, điều hòa không khí, camera và chống sét.',
                details: 'Hạng mục M&E được triển khai đồng bộ theo tiêu chuẩn an toàn điện Việt Nam: tủ điện phân phối, hệ thống cấp thoát nước áp lực ổn định, ống đồng điều hòa âm tường, hệ thống báo cháy và chống sét tiếp địa.'
            },
            {
                id: 'sp-7',
                category: 'thi-cong-hoan-thien',
                categoryName: 'Thi công hoàn thiện',
                title: 'Thi công sơn nước & chống thấm chuyên dụng',
                driveId: '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_',
                summary: 'Xử lý chống thấm sàn mái, nhà vệ sinh, tường ngoài và thi công sơn nước hoàn thiện.',
                details: 'Quy trình chống thấm nhiều lớp kết hợp phụ gia chuyên dụng cho sân thượng, ban công, bể nước và tường tiếp giáp, giúp công trình khô ráo tuyệt đối qua mùa mưa bão miền Trung.'
            },
            {
                id: 'sp-8',
                category: 'thiet-ke-kien-truc',
                categoryName: 'Thiết kế Kiến trúc – Nội thất',
                title: 'Thiết kế nội thất biệt thự & văn phòng',
                driveId: '1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT',
                summary: 'Không gian sang trọng, bố trí khoa học, tối ưu công năng sử dụng và nhận diện thương hiệu.',
                details: 'Tư vấn phong cách thiết kế nội thất hiện đại, tối giản hoặc tân cổ điển phù hợp ngân sách chủ đầu tư. Lập bảng bóc tách vật liệu chi tiết giúp kiểm soát chi phí ngay từ đầu.'
            },
            {
                id: 'sp-9',
                category: 'thi-cong-noi-that',
                categoryName: 'Thi công nội thất',
                title: 'Cải tạo & nâng cấp công trình dân dụng',
                driveId: '1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn',
                summary: 'Cải tạo nhà phố cũ, nâng tầng, thay đổi công năng mặt bằng và làm mới nội thất.',
                details: 'Khảo sát hiện trạng kết cấu kỹ lưỡng trước khi đề xuất phương án cải tạo, nâng tầng, xử lý nứt thấm và làm mới toàn diện không gian sống với thời gian thi công nhanh gọn.'
            }
        ];

        /* =========================================================================
           3. DỮ LIỆU 10 ẢNH DỰ ÁN THỰC TẾ TẠI ĐÀ NẴNG (TỪ LINK GOOGLE DRIVE CỦA BẠN)
           ========================================================================= */
        const projectsData = [
            {
                id: 'da-1',
                category: 'nha-pho',
                categoryName: 'Nhà phố',
                title: 'Nhà phố hiện đại 3 tầng – Sơn Trà',
                location: 'Quận Sơn Trà, TP Đà Nẵng',
                driveId: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
                details: 'Công trình nhà phố 3 tầng thiết kế tối ưu thông gió và ánh sáng tự nhiên, thi công trọn gói từ phần thô đến hoàn thiện nội thất bởi đội ngũ DANTECHCO.'
            },
            {
                id: 'da-2',
                category: 'biet-thu',
                categoryName: 'Biệt thự',
                title: 'Biệt thự phố ven biển – Mỹ Khê',
                location: 'Khu vực Mỹ Khê, TP Đà Nẵng',
                driveId: '1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff',
                details: 'Thiết kế và thi công biệt thự phố hiện đại gần biển Mỹ Khê, sử dụng vật liệu chống ăn mòn cao cấp và không gian sân vườn thoáng đãng.'
            },
            {
                id: 'da-3',
                category: 'khach-san-can-ho',
                categoryName: 'Khách sạn – Căn hộ',
                title: 'Căn hộ dịch vụ cao cấp – An Thượng',
                location: 'Phố Tây An Thượng, TP Đà Nẵng',
                driveId: '1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz',
                details: 'Dự án tổ hợp căn hộ cho thuê cao cấp gồm 6 tầng, thi công hoàn thiện trọn gói kết cấu, hệ thống M&E và nội thất đồng bộ.'
            },
            {
                id: 'da-4',
                category: 'nha-pho',
                categoryName: 'Nhà phố',
                title: 'Nhà phố 2 mặt tiền – KĐT Hòa Xuân',
                location: 'Khu đô thị Hòa Xuân, TP Đà Nẵng',
                driveId: '1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k',
                details: 'Công trình nhà phố 2 mặt tiền diện tích 120m², thiết kế tinh gọn kết hợp không gian sinh hoạt gia đình và gara ô tô rộng rãi.'
            },
            {
                id: 'da-5',
                category: 'van-phong',
                categoryName: 'Văn phòng',
                title: 'Tòa nhà văn phòng thương mại – Hải Châu',
                location: 'Quận Hải Châu, TP Đà Nẵng',
                driveId: '1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N',
                details: 'Thi công phần thô, mặt dựng kính cường lực và hệ thống cơ điện trung tâm cho tòa nhà văn phòng tại khu vực trung tâm Hải Châu.'
            },
            {
                id: 'da-6',
                category: 'khach-san-can-ho',
                categoryName: 'Khách sạn – Căn hộ',
                title: 'Khách sạn Boutique – Phạm Văn Đồng',
                location: 'Biển Phạm Văn Đồng, Sơn Trà, Đà Nẵng',
                driveId: '1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML',
                details: 'Thi công hoàn thiện kiến trúc và nội thất khách sạn Boutique phục vụ du lịch, đảm bảo tiêu chuẩn phòng cháy chữa cháy và thẩm mỹ cao.'
            },
            {
                id: 'da-7',
                category: 'biet-thu',
                categoryName: 'Biệt thự',
                title: 'Biệt thự sân vườn – Ngũ Hành Sơn',
                location: 'Quận Ngũ Hành Sơn, TP Đà Nẵng',
                driveId: '1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF',
                details: 'Biệt thự 2 tầng mái Nhật kết hợp cảnh quan sân vườn, hồ cá và không gian mở chan hòa thiên nhiên do DANTECHCO thi công hoàn thiện.'
            },
            {
                id: 'da-8',
                category: 'nha-pho',
                categoryName: 'Nhà phố',
                title: 'Nhà phố kết hợp kinh doanh – Mân Thái',
                location: 'Mân Thái, Sơn Trà, TP Đà Nẵng',
                driveId: '1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A',
                details: 'Công trình nhà phố 4 tầng tối ưu mặt bằng tầng 1 cho kinh doanh và các tầng trên cho không gian ở tiện nghi, yên tĩnh.'
            },
            {
                id: 'da-9',
                category: 'van-phong',
                categoryName: 'Văn phòng',
                title: 'Showroom & Văn phòng đại diện – Thanh Khê',
                location: 'Quận Thanh Khê, TP Đà Nẵng',
                driveId: '1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80',
                details: 'Cải tạo và thi công hoàn thiện không gian văn phòng trưng bày hiện đại, hệ thống chiếu sáng chuyên nghiệp và vách kính cách âm.'
            },
            {
                id: 'da-10',
                category: 'khach-san-can-ho',
                categoryName: 'Khách sạn – Căn hộ',
                title: 'Tổ hợp căn hộ cho thuê – Liên Chiểu',
                location: 'Quận Liên Chiểu, TP Đà Nẵng',
                driveId: '1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4',
                details: 'Thi công trọn gói dãy căn hộ dịch vụ tối ưu chi phí đầu tư, bàn giao đúng tiến độ giúp chủ đầu tư sớm đưa vào khai thác vận hành.'
            }
        ];

        /* =========================================================================
           4. DỮ LIỆU BÀI VIẾT / TIN TỨC TRANG CHỦ
           ========================================================================= */
        const articlesData = [
            {
                id: 'bv-1',
                date: '15/11/2026',
                title: 'Báo giá thi công xây dựng trọn gói tại Đà Nẵng mới nhất',
                driveId: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
                excerpt: 'Tổng hợp đơn giá thiết kế, thi công phần thô và hoàn thiện nhà phố, biệt thự tại Đà Nẵng giúp chủ đầu tư chủ động dự trù ngân sách.',
                content: 'Chi phí xây dựng nhà tại Đà Nẵng phụ thuộc vào quy mô tầng cao, điều kiện địa chất khu vực (Sơn Trà, Hòa Xuân, Hải Châu...), chủng loại vật tư hoàn thiện và phong cách kiến trúc. DANTECHCO luôn lập bảng dự toán bóc tách rõ ràng từng hạng mục trước khi ký hợp đồng để khách hàng dễ dàng đối chiếu và kiểm soát chi phí không phát sinh.'
            },
            {
                id: 'bv-2',
                date: '08/11/2026',
                title: 'Hướng dẫn bảo dưỡng bê tông móng và sàn đúng kỹ thuật',
                driveId: '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_',
                excerpt: 'Quy trình tưới nước giữ ẩm cho bê tông sau khi đổ giúp kết cấu đạt cường độ tối đa và hạn chế tối đa tình trạng rạn nứt chân chim.',
                content: 'Trong 7 ngày đầu sau khi đổ bê tông móng, cột và sàn, việc cấp ẩm liên tục là yếu tố quyết định độ bền vững của công trình. Kỹ sư DANTECHCO luôn kiểm soát chặt chẽ độ sụt bê tông, che phủ bạt chống mất nước khi trời nắng gắt tại miền Trung và thực hiện tưới bảo dưỡng đúng chu kỳ kỹ thuật.'
            },
            {
                id: 'bv-3',
                date: '29/10/2026',
                title: 'Giải pháp chống thấm hiệu quả cho nhà phố ven biển Đà Nẵng',
                driveId: '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_',
                excerpt: 'Những lưu ý quan trọng khi xử lý chống thấm sân thượng, tường hông và khu vực nhà vệ sinh trong điều kiện mưa bão kéo dài.',
                content: 'Khí hậu ven biển Đà Nẵng có độ ẩm cao và mưa bão lớn vào cuối năm. Để ngôi nhà bền đẹp lâu dài, cần thi công chống thấm đồng bộ từ khâu đổ bê tông sàn mái, bo góc chân tường, sử dụng màng hoặc hóa chất chống thấm gốc xi măng polymer 2 thành phần và thử nước nghiệm thu tối thiểu 48 giờ.'
            },
            {
                id: 'bv-4',
                date: '18/10/2026',
                title: '5 Kinh nghiệm chọn nhà thầu xây dựng uy tín không phát sinh',
                driveId: '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO',
                excerpt: 'Cách đánh giá năng lực nhà thầu qua công trình thực tế, hợp đồng minh bạch chủng loại vật tư và cam kết bảo hành sau bàn giao.',
                content: 'Khi lựa chọn đơn vị thiết kế và thi công trọn gói, chủ đầu tư nên tham quan trực tiếp các công trình đang thi công của nhà thầu, kiểm tra kỹ bảng phụ lục vật tư (thép, xi măng, dây điện, ống nước, sơn), tiến độ thanh toán theo từng giai đoạn nghiệm thu và điều khoản bảo hành kết cấu rõ ràng.'
            }
        ];

        /* =========================================================================
           5. RENDER SẢN PHẨM, DỰ ÁN, BÀI VIẾT & LỌC DANH MỤC
           ========================================================================= */
        let currentModalItemTitle = '';

        function renderProducts(filterCat = 'all') {
            const container = document.getElementById('products-grid');
            const list = filterCat === 'all'
                ? productsData
                : productsData.filter(item => item.category === filterCat);

            container.innerHTML = list.map(item => `
                <article onclick="openProductModal('${item.id}')"
                         class="ux-card cursor-pointer bg-white rounded-xl border border-slate-200 overflow-hidden flex flex-col h-full">
                    <div class="w-full aspect-[4/3] overflow-hidden bg-slate-100">
                        <img src="${getDriveImageUrl(item.driveId)}"
                             data-drive-id="${item.driveId}"
                             onerror="handleDriveImageError(this, '${item.title.replace(/'/g, '')}')"
                             alt="${item.title}"
                             loading="lazy"
                             class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="text-[13px] sm:text-[15px] font-bold text-brand-navy leading-snug break-words mb-1.5">
                                ${item.title}
                            </h3>
                            <p class="hidden sm:block text-xs text-slate-600 leading-relaxed line-clamp-2">
                                ${item.summary}
                            </p>
                        </div>
                        <div class="mt-2.5 pt-2 border-t border-slate-100 flex items-center justify-between gap-1">
                            <span class="text-[11px] sm:text-xs font-semibold text-brand-gold">Liên hệ báo giá</span>
                            <span class="text-[11px] text-slate-400">Chi tiết <i class="fa-solid fa-angle-right text-[10px]"></i></span>
                        </div>
                    </div>
                </article>
            `).join('');
        }

        function filterProducts(cat) {
            renderProducts(cat);
            document.querySelectorAll('#product-tabs .cat-tab-btn').forEach(btn => {
                if (btn.getAttribute('data-cat') === cat) {
                    btn.classList.add('active');
                    btn.classList.remove('text-slate-700');
                } else {
                    btn.classList.remove('active');
                    btn.classList.add('text-slate-700');
                }
            });
        }

        function renderProjects(filterCat = 'all') {
            const container = document.getElementById('projects-grid');
            const list = filterCat === 'all'
                ? projectsData
                : projectsData.filter(item => item.category === filterCat);

            container.innerHTML = list.map(item => `
                <article onclick="openProjectModal('${item.id}')"
                         class="ux-card cursor-pointer bg-white rounded-xl border border-slate-200 overflow-hidden flex flex-col h-full">
                    <div class="w-full aspect-[4/3] overflow-hidden bg-slate-100">
                        <img src="${getDriveImageUrl(item.driveId)}"
                             data-drive-id="${item.driveId}"
                             onerror="handleDriveImageError(this, '${item.title.replace(/'/g, '')}')"
                             alt="${item.title}"
                             loading="lazy"
                             class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <h3 class="text-[13px] sm:text-sm font-bold text-brand-navy leading-snug break-words">
                            ${item.title}
                        </h3>
                        <p class="text-[11px] sm:text-xs text-slate-500 mt-1.5 flex items-center gap-1">
                            <i class="fa-solid fa-location-dot text-brand-gold text-[10px] shrink-0"></i>
                            <span class="truncate">${item.location}</span>
                        </p>
                    </div>
                </article>
            `).join('');
        }

        function filterProjects(cat) {
            renderProjects(cat);
            document.querySelectorAll('#project-tabs .cat-tab-btn').forEach(btn => {
                if (btn.getAttribute('data-cat') === cat) {
                    btn.classList.add('active');
                    btn.classList.remove('text-slate-700');
                } else {
                    btn.classList.remove('active');
                    btn.classList.add('text-slate-700');
                }
            });
        }

        function renderArticles() {
            const container = document.getElementById('articles-grid');
            container.innerHTML = articlesData.map(article => `
                <article onclick="openArticleModal('${article.id}')"
                         class="ux-card cursor-pointer bg-white rounded-xl border border-slate-200 overflow-hidden flex flex-col h-full">
                    <div class="w-full aspect-[16/10] overflow-hidden bg-slate-100">
                        <img src="${getDriveImageUrl(article.driveId)}"
                             data-drive-id="${article.driveId}"
                             onerror="handleDriveImageError(this, 'Tin tức DANTECHCO')"
                             alt="${article.title}"
                             loading="lazy"
                             class="w-full h-full object-cover">
                    </div>
                    <div class="p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] text-slate-400 mb-1.5 flex items-center gap-1.5">
                                <i class="fa-regular fa-calendar text-brand-gold"></i>
                                <span>${article.date}</span>
                            </div>
                            <h3 class="text-sm sm:text-[15px] font-bold text-brand-navy leading-snug mb-2 break-words">
                                ${article.title}
                            </h3>
                            <p class="text-xs text-slate-600 leading-relaxed line-clamp-3">
                                ${article.excerpt}
                            </p>
                        </div>
                        <div class="mt-3 pt-2.5 border-t border-slate-100 text-xs font-semibold text-brand-gold">
                            Đọc chi tiết <i class="fa-solid fa-arrow-right text-[10px] ml-0.5"></i>
                        </div>
                    </div>
                </article>
            `).join('');
        }

        /* =========================================================================
           6. MODAL CHI TIẾT SẢN PHẨM / DỰ ÁN / BÀI VIẾT
           ========================================================================= */
        function showDetailModal(title, meta, driveId, descText) {
            currentModalItemTitle = title;
            document.getElementById('modal-title').textContent = title;
            document.getElementById('modal-meta').textContent = meta;
            const img = document.getElementById('modal-image');
            img.removeAttribute('data-fallback-step');
            img.setAttribute('data-drive-id', driveId);
            img.onerror = function () { handleDriveImageError(img, title); };
            img.src = getDriveImageUrl(driveId);
            img.alt = title;
            document.getElementById('modal-desc').innerHTML = `<p>${descText}</p>`;
            document.getElementById('detail-modal').classList.remove('hidden');
            document.body.style.overflow = 'hidden';
        }

        function openProductModal(id) {
            const item = productsData.find(p => p.id === id);
            if (!item) return;
            showDetailModal(item.title, 'Danh mục: ' + item.categoryName, item.driveId, item.details);
        }

        function openProjectModal(id) {
            const item = projectsData.find(p => p.id === id);
            if (!item) return;
            showDetailModal(item.title, item.categoryName + ' • ' + item.location, item.driveId, item.details);
        }

        function openArticleModal(id) {
            const item = articlesData.find(a => a.id === id);
            if (!item) return;
            showDetailModal(item.title, 'Bài viết xây dựng • ' + item.date, item.driveId, item.content);
        }

        function hideDetailModal() {
            document.getElementById('detail-modal').classList.add('hidden');
            document.body.style.overflow = '';
        }

        function closeDetailModal(event) {
            if (event.target.id === 'detail-modal') {
                hideDetailModal();
            }
        }

        function requestQuoteFromModal() {
            hideDetailModal();
            const noteEl = document.getElementById('q-note');
            if (noteEl && currentModalItemTitle) {
                noteEl.value = 'Tôi cần tư vấn & báo giá hạng mục: ' + currentModalItemTitle;
            }
            const formSection = document.getElementById('bao-gia');
            if (formSection) {
                formSection.scrollIntoView({ behavior: 'smooth' });
            }
        }

        /* =========================================================================
           7. SLIDER 2 BANNER TỰ TRƯỢT CHUYÊN NGHIỆP (HỖ TRỢ VUỐT CẢM ỨNG MOBILE)
           ========================================================================= */
        let currentSlide = 0;
        const totalSlides = 2;
        let sliderTimer = null;

        function updateSliderUI() {
            const track = document.getElementById('hero-track');
            if (!track) return;
            track.style.transform = `translateX(-${currentSlide * 100}%)`;

            for (let i = 0; i < totalSlides; i++) {
                const dot = document.getElementById('dot-' + i);
                if (!dot) continue;
                if (i === currentSlide) {
                    dot.classList.add('w-6', 'bg-brand-gold');
                    dot.classList.remove('w-2.5', 'bg-white/60');
                } else {
                    dot.classList.remove('w-6', 'bg-brand-gold');
                    dot.classList.add('w-2.5', 'bg-white/60');
                }
            }
        }

        function nextSlide() {
            currentSlide = (currentSlide + 1) % totalSlides;
            updateSliderUI();
            resetAutoSlide();
        }

        function prevSlide() {
            currentSlide = (currentSlide - 1 + totalSlides) % totalSlides;
            updateSliderUI();
            resetAutoSlide();
        }

        function goToSlide(index) {
            currentSlide = index;
            updateSliderUI();
            resetAutoSlide();
        }

        function startAutoSlide() {
            sliderTimer = setInterval(() => {
                currentSlide = (currentSlide + 1) % totalSlides;
                updateSliderUI();
            }, 5500);
        }

        function resetAutoSlide() {
            if (sliderTimer) clearInterval(sliderTimer);
            startAutoSlide();
        }

        // Hỗ trợ vuốt trái/phải banner trên điện thoại
        let touchStartX = 0;
        let touchEndX = 0;
        function initBannerTouch() {
            const track = document.getElementById('hero-track');
            if (!track) return;
            track.addEventListener('touchstart', e => {
                touchStartX = e.changedTouches[0].screenX;
            }, { passive: true });
            track.addEventListener('touchend', e => {
                touchEndX = e.changedTouches[0].screenX;
                const diff = touchStartX - touchEndX;
                if (Math.abs(diff) > 40) {
                    if (diff > 0) nextSlide();
                    else prevSlide();
                }
            }, { passive: true });
        }

        /* =========================================================================
           8. MENU MOBILE & XỬ LÝ FORM YÊU CẦU BÁO GIÁ
           ========================================================================= */
        function toggleMobileMenu() {
            const menu = document.getElementById('mobile-menu');
            const icon = document.getElementById('mobile-menu-icon');
            const isHidden = menu.classList.contains('hidden');
            if (isHidden) {
                menu.classList.remove('hidden');
                icon.classList.remove('fa-bars');
                icon.classList.add('fa-xmark');
            } else {
                menu.classList.add('hidden');
                icon.classList.remove('fa-xmark');
                icon.classList.add('fa-bars');
            }
        }

        function closeMobileMenu() {
            const menu = document.getElementById('mobile-menu');
            const icon = document.getElementById('mobile-menu-icon');
            menu.classList.add('hidden');
            icon.classList.remove('fa-xmark');
            icon.classList.add('fa-bars');
        }

        function submitQuoteForm(event) {
            event.preventDefault();
            const name = document.getElementById('q-name').value.trim();
            const phone = document.getElementById('q-phone').value.trim();
            const type = document.getElementById('q-type').value;
            const budget = document.getElementById('q-budget').value;
            const feedback = document.getElementById('quote-feedback');
            const feedbackText = document.getElementById('quote-feedback-text');

            if (!name || !phone) return;

            feedbackText.textContent = `Cảm ơn anh/chị ${name}! DANTECHCO đã tiếp nhận yêu cầu báo giá (${type} - ${budget}) qua SĐT ${phone}. Kỹ sư phụ trách sẽ liên hệ tư vấn sớm nhất hoặc gọi trực tiếp Hotline 0905.294.687.`;
            feedback.classList.remove('hidden');
            event.target.reset();
        }

        /* =========================================================================
           9. KHỞI TẠO KHI TẢI TRANG
           ========================================================================= */
        window.addEventListener('DOMContentLoaded', () => {
            renderProducts('all');
            renderProjects('all');
            renderArticles();
            updateSliderUI();
            startAutoSlide();
            initBannerTouch();
        });
    </script>
</body>
</html>
