<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PHÚC KHANG THỊNH PHÁT - Giải Pháp Quà Tặng Doanh Nghiệp | phuckhangthinhphat.com</title>
    <meta name="description" content="CÔNG TY TNHH THƯƠNG MẠI & DỊCH VỤ PHÚC KHANG THỊNH PHÁT - Chuyên cung cấp giải pháp quà tặng doanh nghiệp in logo theo yêu cầu tại Đà Nẵng và toàn quốc. Hotline: 0938.613.943">
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts: Inter & Montserrat chuẩn giao diện Flatsome hiện đại -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=Montserrat:wght@600;700;800&display=swap" rel="stylesheet">
    <!-- Font Awesome 6 -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                        heading: ['Montserrat', 'sans-serif'],
                    },
                    colors: {
                        pk: {
                            gold: '#C69320',
                            goldLight: '#E5B84B',
                            goldDark: '#9A6F0B',
                            navy: '#1E2433',
                            navyDark: '#141824',
                            cream: '#FDFBF7',
                            sand: '#F5EFE6'
                        }
                    }
                }
            }
        }
    </script>

    <style>
        /* Cấu trúc CSS chuẩn Flatsome (Section -> Row -> Col -> Col-inner -> Box) để dễ dàng dựng lại trên UX Builder */
        body {
            font-family: 'Inter', sans-serif;
            background-color: #F8F9FA;
            color: #222222;
            overflow-x: hidden;
        }

        .flatsome-container {
            max-width: 1230px;
            margin-left: auto;
            margin-right: auto;
            padding-left: 15px;
            padding-right: 15px;
        }

        /* Section Title chuẩn Flatsome (section-title-normal / section-title-center) */
        .section-title-container {
            margin-bottom: 1.25rem;
        }
        .section-title {
            display: flex;
            align-items: center;
            justify-content: space-between;
            border-bottom: 2px solid #E5E7EB;
            padding-bottom: 10px;
            position: relative;
        }
        .section-title-main {
            font-family: 'Montserrat', sans-serif;
            font-weight: 800;
            text-transform: uppercase;
            color: #1E2433;
            position: relative;
            display: inline-flex;
            align-items: center;
            gap: 10px;
        }
        .section-title-main::after {
            content: '';
            position: absolute;
            bottom: -12px;
            left: 0;
            width: 100%;
            height: 3px;
            background: linear-gradient(90deg, #C69320, #E5B84B);
        }

        /* Box Category & Box Product chuẩn Flatsome */
        .box-category, .product-small.box {
            transition: all 0.25s ease;
        }
        .box-category:hover {
            transform: translateY(-4px);
            box-shadow: 0 10px 20px -5px rgba(198, 147, 32, 0.2);
            border-color: #C69320;
        }
        .product-small.box:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 25px -5px rgba(0, 0, 0, 0.08);
            border-color: #D1D5DB;
        }

        /* Nút liên hệ nổi (Zalo, Facebook, Gọi điện, Bản đồ) */
        @keyframes pulse-ring {
            0% { transform: scale(0.9); opacity: 0.8; }
            70% { transform: scale(1.35); opacity: 0; }
            100% { transform: scale(1.35); opacity: 0; }
        }
        .contact-pulse::before {
            content: '';
            position: absolute;
            inset: 0;
            border-radius: 9999px;
            background: inherit;
            animation: pulse-ring 2s infinite;
            z-index: -1;
        }

        /* Ẩn thanh cuộn ngang cho danh mục nhanh trên điện thoại */
        .no-scrollbar::-webkit-scrollbar {
            display: none;
        }
        .no-scrollbar {
            -ms-overflow-style: none;
            scrollbar-width: none;
        }
    </style>
</head>
<body class="antialiased selection:bg-pk-gold selection:text-white">

    <!-- ==========================================
         HEADER WRAPPER (CHUẨN FLATSOME HEADER)
         Không hiển thị thanh công cụ UX Builder ở dòng trên
         ========================================== -->
    <header id="header" class="sticky top-0 z-40 bg-white shadow-sm">
        
        <!-- 1. TOP BAR (Chỉ hiển thị thông tin công ty, địa chỉ, SĐT khách hàng) -->
        <div id="top-bar" class="bg-pk-navy text-white text-xs py-2 border-b border-white/10">
            <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
                <div class="flex items-center gap-2 font-medium truncate">
                    <span class="text-pk-goldLight"><i class="fa-solid fa-award"></i></span>
                    <span class="truncate">CÔNG TY TNHH TM & DV PHÚC KHANG THỊNH PHÁT – Giải Pháp Quà Tặng Doanh Nghiệp</span>
                </div>
                <div class="hidden md:flex items-center gap-5 text-gray-200">
                    <a href="https://maps.app.goo.gl/JNZ3N1iF34Te4HBW7" target="_blank" rel="noopener noreferrer" class="hover:text-pk-goldLight transition flex items-center gap-1.5">
                        <i class="fa-solid fa-location-dot text-pk-goldLight"></i>
                        <span>252 Tô Hiệu, P. Hòa Khánh, TP. Đà Nẵng</span>
                    </a>
                    <span class="text-white/20">|</span>
                    <a href="https://www.facebook.com/nguyen.thu.trang.854486/" target="_blank" rel="noopener noreferrer" class="hover:text-pk-goldLight transition flex items-center gap-1.5">
                        <i class="fa-brands fa-facebook text-blue-400"></i>
                        <span>Facebook Chính Thức</span>
                    </a>
                    <span class="text-white/20">|</span>
                    <a href="tel:0938613943" class="hover:text-pk-goldLight transition font-semibold text-pk-goldLight flex items-center gap-1.5">
                        <i class="fa-solid fa-phone-volume"></i>
                        <span>0938.613.943</span>
                    </a>
                </div>
            </div>
        </div>

        <!-- 2. HEADER MAIN (Logo PK trong ảnh + Tìm kiếm + Hotline + Zalo) -->
        <div id="masthead" class="py-3 md:py-4 bg-white">
            <div class="flatsome-container flex items-center justify-between gap-3 md:gap-6">
                
                <!-- Nút mở Menu trên Điện thoại -->
                <button onclick="toggleMobileMenu()" aria-label="Mở danh mục" class="lg:hidden p-2.5 rounded-lg border border-gray-200 text-pk-navy hover:bg-gray-50">
                    <i class="fa-solid fa-bars text-xl"></i>
                </button>

                <!-- LOGO PHÚC KHANG THỊNH PHÁT (Vẽ chuẩn từ ảnh gốc) -->
                <a href="#" onclick="filterCategory('all'); return false;" class="flex items-center gap-3 group shrink-0">
                    <div class="w-12 h-12 md:w-14 md:h-14 flex items-center justify-center shrink-0">
                        <!-- SVG Logo PK Vàng Kim & Xanh Đen chuẩn theo ảnh -->
                        <svg viewBox="0 0 120 110" class="w-full h-full drop-shadow-sm" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <defs>
                                <linearGradient id="pkGoldGrad" x1="0%" y1="0%" x2="100%" y2="100%">
                                    <stop offset="0%" stop-color="#E6C35C"/>
                                    <stop offset="45%" stop-color="#C69320"/>
                                    <stop offset="100%" stop-color="#8F6505"/>
                                </linearGradient>
                                <linearGradient id="pkNavyGrad" x1="0%" y1="0%" x2="100%" y2="100%">
                                    <stop offset="0%" stop-color="#2B3245"/>
                                    <stop offset="100%" stop-color="#141824"/>
                                </linearGradient>
                            </defs>
                            <!-- Chữ P cách điệu màu vàng kim -->
                            <path d="M25 12 H75 C94 12 106 23 106 40 C106 57 94 68 75 68 H44 V96 L25 84 V32 H72 C81 32 86 35 86 40 C86 45 81 48 72 48 H25 V12 Z" fill="url(#pkGoldGrad)"/>
                            <path d="M16 32 H34 V96 L16 84 V32 Z" fill="url(#pkGoldGrad)"/>
                            <!-- Phần chân chữ K hình tam giác màu xanh đen đậm -->
                            <path d="M46 68 H67 L80 56 L108 96 H46 V68 Z" fill="url(#pkNavyGrad)"/>
                            <polygon points="62,72 76,72 84,83 62,83" fill="#FFFFFF"/>
                        </svg>
                    </div>
                    <div class="flex flex-col">
                        <span class="font-heading font-extrabold text-sm sm:text-base md:text-lg lg:text-xl tracking-tight text-pk-navy leading-tight">
                            PHÚC KHANG THỊNH PHÁT
                        </span>
                        <span class="text-[10px] sm:text-xs font-semibold tracking-widest uppercase text-pk-gold">
                            GIẢI PHÁP QUÀ TẶNG DOANH NGHIỆP
                        </span>
                    </div>
                </a>

                <!-- Ô tìm kiếm sản phẩm (Desktop) -->
                <div class="hidden lg:flex flex-1 max-w-md mx-4">
                    <div class="relative w-full flex">
                        <input 
                            id="desktopSearchInput"
                            type="text" 
                            oninput="handleSearch(this.value)"
                            placeholder="Tìm kiếm: Bình giữ nhiệt, ly sứ, áo mưa, quà Tết..." 
                            class="w-full pl-4 pr-10 py-2.5 text-sm bg-gray-50 border border-gray-300 rounded-l-lg focus:outline-none focus:border-pk-gold focus:bg-white transition"
                        >
                        <button onclick="handleSearch(document.getElementById('desktopSearchInput').value)" class="px-5 bg-pk-gold hover:bg-pk-goldDark text-white rounded-r-lg transition flex items-center justify-center">
                            <i class="fa-solid fa-magnifying-glass"></i>
                        </button>
                    </div>
                </div>

                <!-- Cụm nút Liên hệ nhanh trên Header -->
                <div class="flex items-center gap-2 sm:gap-3">
                    <a href="tel:0938613943" class="hidden sm:flex items-center gap-2.5 px-3.5 py-2 rounded-lg bg-amber-50 border border-amber-200 hover:bg-amber-100 transition">
                        <div class="w-8 h-8 rounded-full bg-pk-gold text-white flex items-center justify-center shrink-0">
                            <i class="fa-solid fa-phone text-xs"></i>
                        </div>
                        <div class="leading-tight">
                            <div class="text-[10px] uppercase text-gray-500 font-semibold">Hotline / Zalo 24/7</div>
                            <div class="text-sm font-extrabold text-pk-navy">0938.613.943</div>
                        </div>
                    </a>

                    <a href="https://zalo.me/0938613943" target="_blank" rel="noopener noreferrer" class="px-3.5 py-2.5 rounded-lg bg-blue-600 hover:bg-blue-700 text-white font-semibold text-xs sm:text-sm flex items-center gap-1.5 shadow-sm transition">
                        <i class="fa-solid fa-comment-dots"></i>
                        <span>Chat Zalo</span>
                    </a>
                </div>
            </div>

            <!-- Ô tìm kiếm trên Điện thoại -->
            <div class="flatsome-container mt-2.5 lg:hidden">
                <div class="relative flex w-full">
                    <input 
                        id="mobileSearchInput"
                        type="text" 
                        oninput="handleSearch(this.value)"
                        placeholder="Tìm sản phẩm quà tặng in logo..." 
                        class="w-full pl-3.5 pr-10 py-2 text-sm bg-gray-50 border border-gray-300 rounded-l-lg focus:outline-none focus:border-pk-gold"
                    >
                    <button onclick="handleSearch(document.getElementById('mobileSearchInput').value)" class="px-4 bg-pk-gold text-white rounded-r-lg">
                        <i class="fa-solid fa-magnifying-glass text-sm"></i>
                    </button>
                </div>
            </div>
        </div>

        <!-- 3. HEADER BOTTOM / NAVIGATION BAR (Menu Danh mục chuẩn Quà Tặng Quang Vũ + Flatsome) -->
        <div id="wide-nav" class="hidden lg:block bg-pk-navy text-white border-t border-white/10">
            <div class="flatsome-container flex items-center justify-between">
                
                <!-- Nút Mega Dropdown Danh Mục Sản Phẩm -->
                <div class="relative group">
                    <button class="bg-pk-gold hover:bg-pk-goldDark text-white font-heading font-bold text-sm uppercase px-5 py-3.5 flex items-center gap-3 tracking-wide transition">
                        <i class="fa-solid fa-bars-staggered"></i>
                        <span>DANH MỤC SẢN PHẨM</span>
                        <i class="fa-solid fa-chevron-down text-xs ml-2"></i>
                    </button>

                    <!-- Menu xổ xuống khi di chuột trên máy tính -->
                    <div class="absolute left-0 top-full w-72 bg-white text-gray-800 shadow-xl rounded-b-xl border border-gray-200 py-2 hidden group-hover:block z-50">
                        <a href="#danh-muc-san-pham" onclick="filterCategory('binh-giu-nhiet')" class="flex items-center justify-between px-4 py-2.5 hover:bg-amber-50 hover:text-pk-goldDark text-sm font-medium border-b border-gray-100">
                            <span class="flex items-center gap-2.5"><i class="fa-solid fa-bottle-water text-pk-gold w-4 text-center"></i> Bình Giữ Nhiệt & Bình Thủy Tinh</span>
                            <i class="fa-solid fa-angle-right text-xs text-gray-400"></i>
                        </a>
                        <a href="#danh-muc-san-pham" onclick="filterCategory('gom-su')" class="flex items-center justify-between px-4 py-2.5 hover:bg-amber-50 hover:text-pk-goldDark text-sm font-medium border-b border-gray-100">
                            <span class="flex items-center gap-2.5"><i class="fa-solid fa-mug-hot text-pk-gold w-4 text-center"></i> Ly Sứ & Ấm Chén In Logo</span>
                            <i class="fa-solid fa-angle-right text-xs text-gray-400"></i>
                        </a>
                        <a href="#danh-muc-san-pham" onclick="filterCategory('quang-cao')" class="flex items-center justify-between px-4 py-2.5 hover:bg-amber-50 hover:text-pk-goldDark text-sm font-medium border-b border-gray-100">
                            <span class="flex items-center gap-2.5"><i class="fa-solid fa-umbrella text-pk-gold w-4 text-center"></i> Ô Dù, Áo Mưa & Mũ Bảo Hiểm</span>
                            <i class="fa-solid fa-angle-right text-xs text-gray-400"></i>
                        </a>
                        <a href="#danh-muc-san-pham" onclick="filterCategory('van-phong')" class="flex items-center justify-between px-4 py-2.5 hover:bg-amber-50 hover:text-pk-goldDark text-sm font-medium border-b border-gray-100">
                            <span class="flex items-center gap-2.5"><i class="fa-solid fa-book-open text-pk-gold w-4 text-center"></i> Sổ Tay Da, Bút Ký & Balo</span>
                            <i class="fa-solid fa-angle-right text-xs text-gray-400"></i>
                        </a>
                        <a href="#danh-muc-san-pham" onclick="filterCategory('cong-nghe')" class="flex items-center justify-between px-4 py-2.5 hover:bg-amber-50 hover:text-pk-goldDark text-sm font-medium border-b border-gray-100">
                            <span class="flex items-center gap-2.5"><i class="fa-solid fa-battery-full text-pk-gold w-4 text-center"></i> Sạc Dự Phòng, Đồng Hồ, Quạt</span>
                            <i class="fa-solid fa-angle-right text-xs text-gray-400"></i>
                        </a>
                        <a href="#danh-muc-san-pham" onclick="filterCategory('mua-vu')" class="flex items-center justify-between px-4 py-2.5 hover:bg-amber-50 hover:text-pk-goldDark text-sm font-medium">
                            <span class="flex items-center gap-2.5"><i class="fa-solid fa-gift text-pk-gold w-4 text-center"></i> Quà Tết & Bánh Trung Thu</span>
                            <i class="fa-solid fa-angle-right text-xs text-gray-400"></i>
                        </a>
                    </div>
                </div>

                <!-- Các liên kết Menu ngang -->
                <nav class="flex items-center space-x-1 xl:space-x-2 text-xs xl:text-sm font-semibold uppercase tracking-wide">
                    <a href="#" onclick="filterCategory('all'); return false;" class="px-3 py-3.5 text-pk-goldLight hover:text-white transition">Trang chủ</a>
                    <a href="#danh-muc-visual" class="px-3 py-3.5 hover:text-pk-goldLight transition">Danh mục quà tặng</a>
                    <a href="#sec-binh-giu-nhiet" class="px-3 py-3.5 hover:text-pk-goldLight transition">Bình giữ nhiệt</a>
                    <a href="#sec-gom-su" class="px-3 py-3.5 hover:text-pk-goldLight transition">Quà tặng gốm sứ</a>
                    <a href="#sec-quang-cao" class="px-3 py-3.5 hover:text-pk-goldLight transition">Quà tặng quảng cáo</a>
                    <a href="#sec-van-phong" class="px-3 py-3.5 hover:text-pk-goldLight transition">Văn phòng & Công nghệ</a>
                    <a href="#sec-mua-vu" class="px-3 py-3.5 hover:text-pk-goldLight transition">Quà Tết & Trung Thu</a>
                    <a href="#lien-he-footer" class="px-3 py-3.5 hover:text-pk-goldLight transition">Liên hệ</a>
                </nav>
            </div>
        </div>
    </header>

    <!-- ==========================================
         MENU TRƯỢT TRÊN ĐIỆN THOẠI (MOBILE DRAWER)
         ========================================== -->
    <div id="mobileMenuBackdrop" onclick="toggleMobileMenu()" class="fixed inset-0 bg-black/60 z-50 hidden"></div>
    <aside id="mobileMenuDrawer" class="fixed top-0 left-0 bottom-0 w-80 max-w-[85vw] bg-white z-50 transform -translate-x-full transition-transform duration-300 flex flex-col shadow-2xl">
        <div class="p-4 bg-pk-navy text-white flex items-center justify-between">
            <div class="font-heading font-bold text-sm text-pk-goldLight">PHÚC KHANG THỊNH PHÁT</div>
            <button onclick="toggleMobileMenu()" class="w-8 h-8 rounded-lg bg-white/10 flex items-center justify-center text-white">
                <i class="fa-solid fa-xmark"></i>
            </button>
        </div>
        <div class="p-4 overflow-y-auto flex-1 space-y-4">
            <div class="text-xs font-bold uppercase text-gray-400 tracking-wider">Danh mục sản phẩm</div>
            <div class="grid grid-cols-2 gap-2 text-xs font-semibold text-pk-navy">
                <button onclick="filterCategory('all'); toggleMobileMenu();" class="p-2.5 rounded-lg bg-amber-50 border border-amber-200 text-left flex items-center gap-2 col-span-2">
                    <i class="fa-solid fa-border-all text-pk-gold"></i> Tất cả sản phẩm
                </button>
                <button onclick="filterCategory('binh-giu-nhiet'); toggleMobileMenu();" class="p-2.5 rounded-lg bg-gray-50 border border-gray-200 text-left">Bình giữ nhiệt</button>
                <button onclick="filterCategory('gom-su'); toggleMobileMenu();" class="p-2.5 rounded-lg bg-gray-50 border border-gray-200 text-left">Ly sứ & Ấm chén</button>
                <button onclick="filterCategory('quang-cao'); toggleMobileMenu();" class="p-2.5 rounded-lg bg-gray-50 border border-gray-200 text-left">Ô dù & Áo mưa</button>
                <button onclick="filterCategory('van-phong'); toggleMobileMenu();" class="p-2.5 rounded-lg bg-gray-50 border border-gray-200 text-left">Sổ da & Bút ký</button>
                <button onclick="filterCategory('cong-nghe'); toggleMobileMenu();" class="p-2.5 rounded-lg bg-gray-50 border border-gray-200 text-left">Balo & Công nghệ</button>
                <button onclick="filterCategory('mua-vu'); toggleMobileMenu();" class="p-2.5 rounded-lg bg-gray-50 border border-gray-200 text-left">Quà Tết & Trung Thu</button>
            </div>

            <div class="border-t border-gray-100 pt-4 space-y-2.5 text-sm">
                <div class="text-xs font-bold uppercase text-gray-400 tracking-wider">Thông tin liên hệ</div>
                <a href="tel:0938613943" class="flex items-center gap-2.5 text-pk-navy font-semibold">
                    <i class="fa-solid fa-phone text-pk-gold w-5"></i> 0938.613.943
                </a>
                <a href="https://zalo.me/0938613943" target="_blank" rel="noopener noreferrer" class="flex items-center gap-2.5 text-blue-600 font-semibold">
                    <i class="fa-solid fa-comment-dots w-5"></i> Chat Zalo: 0938.613.943
                </a>
                <a href="https://www.facebook.com/nguyen.thu.trang.854486/" target="_blank" rel="noopener noreferrer" class="flex items-center gap-2.5 text-blue-700 font-semibold">
                    <i class="fa-brands fa-facebook w-5"></i> Facebook Thu Trang
                </a>
                <a href="https://maps.app.goo.gl/JNZ3N1iF34Te4HBW7" target="_blank" rel="noopener noreferrer" class="flex items-start gap-2.5 text-gray-600 text-xs leading-relaxed">
                    <i class="fa-solid fa-location-dot text-red-500 w-5 mt-0.5"></i> 252 Tô Hiệu, Phường Hòa Khánh, Tp. Đà Nẵng
                </a>
            </div>
        </div>
    </aside>

    <!-- ==========================================
         MAIN CONTENT (CẤU TRÚC SECTION FLATSOME)
         ========================================== -->
    <main id="main">

        <!-- SECTION 1: BANNER CHÍNH TÁI HIỆN CHÍNH XÁC BỐ CỤC ẢNH GỐC -->
        <section class="section py-4 md:py-6 bg-gradient-to-b from-pk-sand/70 to-white">
            <div class="flatsome-container">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-4 items-stretch">
                    
                    <!-- Khối Trái (5 cột): Thương hiệu Phúc Khang Thịnh Phát + 4 Giá trị cốt lõi + SĐT/Địa chỉ đúng như ảnh -->
                    <div class="lg:col-span-5 bg-gradient-to-br from-[#FBF8F1] via-[#F5EFE2] to-[#EFE5D2] rounded-2xl p-5 sm:p-6 border border-amber-200/70 shadow-sm flex flex-col justify-between relative overflow-hidden">
                        <!-- Họa tiết sóng vàng góc trái trên giống trong ảnh -->
                        <div class="absolute -top-10 -left-10 w-40 h-40 rounded-full border-[14px] border-pk-gold/15 pointer-events-none"></div>

                        <div class="text-center relative z-10">
                            <!-- Logo PK Lớn chính giữa -->
                            <div class="w-24 h-20 mx-auto mb-2 flex items-center justify-center">
                                <svg viewBox="0 0 120 110" class="w-full h-full" fill="none" xmlns="http://www.w3.org/2000/svg">
                                    <path d="M25 12 H75 C94 12 106 23 106 40 C106 57 94 68 75 68 H44 V96 L25 84 V32 H72 C81 32 86 35 86 40 C86 45 81 48 72 48 H25 V12 Z" fill="url(#pkGoldGrad)"/>
                                    <path d="M16 32 H34 V96 L16 84 V32 Z" fill="url(#pkGoldGrad)"/>
                                    <path d="M46 68 H67 L80 56 L108 96 H46 V68 Z" fill="url(#pkNavyGrad)"/>
                                    <polygon points="62,72 76,72 84,83 62,83" fill="#FBF8F1"/>
                                </svg>
                            </div>
                            <h1 class="font-heading font-extrabold text-xl sm:text-2xl text-pk-navy tracking-tight">
                                PHÚC KHANG THỊNH PHÁT
                            </h1>
                            <div class="flex items-center justify-center gap-2 my-1.5">
                                <span class="h-[1px] w-8 bg-pk-gold"></span>
                                <p class="text-xs sm:text-sm font-bold uppercase tracking-widest text-pk-goldDark">
                                    GIẢI PHÁP QUÀ TẶNG DOANH NGHIỆP
                                </p>
                                <span class="h-[1px] w-8 bg-pk-gold"></span>
                            </div>
                        </div>

                        <!-- 4 Icon cam kết vàng kim y hệt trong ảnh -->
                        <div class="grid grid-cols-4 gap-2 my-5 pt-3 border-t border-amber-300/50 text-center">
                            <div class="px-1 border-r border-amber-300/60">
                                <div class="text-pk-gold text-xl sm:text-2xl mb-1.5"><i class="fa-solid fa-gift"></i></div>
                                <div class="text-[10px] sm:text-[11px] font-bold uppercase text-pk-navy leading-tight">Quà tặng<br>doanh nghiệp</div>
                            </div>
                            <div class="px-1 border-r border-amber-300/60">
                                <div class="text-pk-gold text-xl sm:text-2xl mb-1.5"><i class="fa-solid fa-shield-halved"></i></div>
                                <div class="text-[10px] sm:text-[11px] font-bold uppercase text-pk-navy leading-tight">Chất lượng<br>uy tín</div>
                            </div>
                            <div class="px-1 border-r border-amber-300/60">
                                <div class="text-pk-gold text-xl sm:text-2xl mb-1.5"><i class="fa-regular fa-lightbulb"></i></div>
                                <div class="text-[10px] sm:text-[11px] font-bold uppercase text-pk-navy leading-tight">Thiết kế<br>theo yêu cầu</div>
                            </div>
                            <div class="px-1">
                                <div class="text-pk-gold text-xl sm:text-2xl mb-1.5"><i class="fa-regular fa-handshake"></i></div>
                                <div class="text-[10px] sm:text-[11px] font-bold uppercase text-pk-navy leading-tight">Gắn kết<br>thương hiệu</div>
                            </div>
                        </div>

                        <!-- Thanh viên thuốc SĐT + Địa chỉ giống hệt ảnh -->
                        <div class="bg-white/90 rounded-xl p-3 border border-amber-200 flex flex-col sm:flex-row items-center justify-between gap-2 shadow-sm">
                            <a href="tel:0938613943" class="flex items-center gap-2 font-heading font-extrabold text-base sm:text-lg text-pk-navy hover:text-pk-gold transition shrink-0">
                                <span class="w-7 h-7 rounded-full bg-pk-gold text-white flex items-center justify-center text-xs">
                                    <i class="fa-solid fa-phone"></i>
                                </span>
                                <span>0938 613 943</span>
                            </a>
                            <span class="hidden sm:inline text-gray-300">|</span>
                            <a href="https://maps.app.goo.gl/JNZ3N1iF34Te4HBW7" target="_blank" rel="noopener noreferrer" class="flex items-center gap-2 text-xs text-gray-700 hover:text-pk-goldDark font-medium text-center sm:text-left">
                                <span class="w-6 h-6 rounded-full bg-pk-gold/20 text-pk-goldDark flex items-center justify-center shrink-0">
                                    <i class="fa-solid fa-location-dot"></i>
                                </span>
                                <span>252 Tô Hiệu, Phường Hòa Khánh, Thành phố Đà Nẵng</span>
                            </a>
                        </div>
                    </div>

                    <!-- Khối Phải (7 cột): 2 Banner lớn BÁNH TRUNG THU & QUÀ TẾT DOANH NGHIỆP giống ảnh -->
                    <div class="lg:col-span-7 grid grid-cols-1 sm:grid-cols-2 gap-4">
                        
                        <!-- Card 1: BÁNH TRUNG THU -->
                        <div onclick="filterCategory('mua-vu')" class="cursor-pointer group rounded-2xl bg-gradient-to-b from-[#F9F3E3] to-[#EAD9B5] p-5 border border-amber-200/80 shadow-sm flex flex-col justify-between relative overflow-hidden">
                            <div>
                                <h2 class="font-heading font-extrabold text-lg sm:text-xl text-amber-900 uppercase">BÁNH TRUNG THU</h2>
                                <p class="text-xs text-amber-800/90 mt-0.5 leading-relaxed">
                                    Hương vị truyền thống<br>Chất lượng tinh tuyển
                                </p>
                            </div>

                            <!-- Minh họa Hộp Bánh Trung Thu Xanh Dương in logo PK Vàng giống ảnh -->
                            <div class="my-3 flex items-center justify-center">
                                <svg viewBox="0 0 260 165" class="w-full max-w-[240px] h-auto group-hover:scale-105 transition duration-300">
                                    <!-- Hộp xanh dương sang trọng -->
                                    <rect x="35" y="18" width="160" height="105" rx="6" fill="#0F4C81" stroke="#D4AF37" stroke-width="2"/>
                                    <rect x="42" y="24" width="146" height="93" rx="4" fill="#165B96"/>
                                    <!-- Trăng rằm & Hoa mẫu đơn vàng trên hộp -->
                                    <circle cx="68" cy="52" r="18" fill="#F3E5AB" opacity="0.85"/>
                                    <circle cx="155" cy="95" r="10" fill="#E6A15C" opacity="0.8"/>
                                    <circle cx="135" cy="102" r="8" fill="#F3E5AB" opacity="0.9"/>
                                    <!-- Logo PK in nhũ vàng chính giữa hộp -->
                                    <text x="125" y="64" text-anchor="middle" fill="#F3E5AB" font-family="Montserrat" font-weight="800" font-size="18">PK</text>
                                    <text x="125" y="76" text-anchor="middle" fill="#F3E5AB" font-family="Inter" font-weight="600" font-size="6.5">PHÚC KHANG THỊNH PHÁT</text>
                                    <!-- Đĩa bánh nướng trung thu phía trước -->
                                    <ellipse cx="105" cy="138" rx="48" ry="15" fill="#FFFFFF" stroke="#D1D5DB"/>
                                    <rect x="82" y="114" width="44" height="22" rx="8" fill="#C87A28" stroke="#8F4E0E" stroke-width="1.5"/>
                                    <circle cx="104" cy="125" r="7" fill="#E5A93C"/>
                                    <!-- Bánh dẻo trà xanh bên cạnh -->
                                    <ellipse cx="205" cy="142" rx="32" ry="11" fill="#FFFFFF" stroke="#D1D5DB"/>
                                    <rect x="190" y="125" width="28" height="16" rx="6" fill="#769F3F"/>
                                </svg>
                            </div>

                            <div class="text-xs font-bold text-amber-900 flex items-center justify-between pt-2 border-t border-amber-800/15">
                                <span>In logo hộp quà theo yêu cầu</span>
                                <span class="group-hover:translate-x-1 transition"><i class="fa-solid fa-arrow-right"></i></span>
                            </div>
                        </div>

                        <!-- Card 2: QUÀ TẾT DOANH NGHIỆP -->
                        <div onclick="filterCategory('mua-vu')" class="cursor-pointer group rounded-2xl bg-gradient-to-b from-[#FDF4EC] to-[#F7DEC8] p-5 border border-red-200/80 shadow-sm flex flex-col justify-between relative overflow-hidden">
                            <div>
                                <h2 class="font-heading font-extrabold text-lg sm:text-xl text-red-800 uppercase">QUÀ TẾT DOANH NGHIỆP</h2>
                                <p class="text-xs text-red-900/80 mt-0.5 leading-relaxed">
                                    Tinh tế trong từng món quà<br>Gắn kết tri ân, đón xuân an khang
                                </p>
                            </div>

                            <!-- Minh họa Set Quà Tết Đỏ Vàng in logo PK giống ảnh -->
                            <div class="my-3 flex items-center justify-center">
                                <svg viewBox="0 0 260 165" class="w-full max-w-[240px] h-auto group-hover:scale-105 transition duration-300">
                                    <!-- Hộp quà đỏ lớn phía sau -->
                                    <rect x="55" y="16" width="115" height="95" rx="5" fill="#B91C1C" stroke="#F59E0B" stroke-width="2"/>
                                    <text x="112" y="45" text-anchor="middle" fill="#FDE68A" font-family="Montserrat" font-weight="800" font-size="14">PK</text>
                                    <!-- Hộp trà vàng đỏ ở giữa -->
                                    <rect x="95" y="55" width="48" height="65" rx="4" fill="#DC2626" stroke="#FDE047" stroke-width="1.5"/>
                                    <text x="119" y="82" text-anchor="middle" fill="#FEF08A" font-family="Montserrat" font-weight="800" font-size="11">PK</text>
                                    <!-- Chai rượu vang sang trọng bên phải -->
                                    <rect x="162" y="38" width="24" height="82" rx="4" fill="#27272A"/>
                                    <rect x="169" y="16" width="10" height="24" fill="#991B1B"/>
                                    <rect x="164" y="68" width="20" height="28" fill="#FEF3C7"/>
                                    <text x="174" y="85" text-anchor="middle" fill="#991B1B" font-family="Montserrat" font-weight="800" font-size="9">PK</text>
                                    <!-- Các hũ hạt dinh dưỡng in logo PK -->
                                    <rect x="42" y="75" width="38" height="52" rx="5" fill="#F59E0B" stroke="#B45309"/>
                                    <rect x="46" y="92" width="30" height="20" fill="#FFFBEB"/>
                                    <text x="61" y="105" text-anchor="middle" fill="#991B1B" font-weight="800" font-size="8">PK</text>
                                    <!-- Đế hộp quà đỏ & Hoa mai vàng -->
                                    <rect x="35" y="122" width="190" height="24" rx="4" fill="#991B1B"/>
                                    <circle cx="42" cy="118" r="14" fill="#FACC15" stroke="#CA8A04" stroke-width="2"/>
                                </svg>
                            </div>

                            <div class="text-xs font-bold text-red-800 flex items-center justify-between pt-2 border-t border-red-800/15">
                                <span>Set quà Tết thiết kế riêng</span>
                                <span class="group-hover:translate-x-1 transition"><i class="fa-solid fa-arrow-right"></i></span>
                            </div>
                        </div>

                    </div>
                </div>
            </div>
        </section>

        <!-- ==========================================
             SECTION 2: DANH MỤC SẢN PHẨM (TỐI ƯU ĐẸP TRÊN CẢ MÁY TÍNH & ĐIỆN THOẠI)
             Đầy đủ 13 danh mục trong ảnh + danh mục từ Quà Tặng Quang Vũ
             Không có nhãn dán (badge/sticker)
             ========================================== -->
        <section id="danh-muc-visual" class="section py-6 md:py-8 bg-white border-y border-gray-100">
            <div class="flatsome-container">
                
                <div class="section-title-container">
                    <div class="section-title">
                        <h2 class="section-title-main text-base sm:text-lg md:text-xl">
                            <i class="fa-solid fa-layer-group text-pk-gold"></i>
                            <span>DANH MỤC QUÀ TẶNG DOANH NGHIỆP</span>
                        </h2>
                        <button onclick="filterCategory('all')" class="text-xs sm:text-sm font-semibold text-pk-goldDark hover:underline flex items-center gap-1">
                            <span>Xem tất cả</span>
                            <i class="fa-solid fa-angle-right text-xs"></i>
                        </button>
                    </div>
                </div>

                <!-- Grid danh mục: Điện thoại 3 cột gọn đẹp, Tablet 4 cột, Máy tính 7 cột giống đúng bố cục 2 hàng trên ảnh -->
                <div id="categoryGridContainer" class="grid grid-cols-3 sm:grid-cols-4 md:grid-cols-5 lg:grid-cols-7 gap-2.5 sm:gap-3.5">
                    <!-- Được render tự động bằng JS từ mảng 14 danh mục chuẩn trong ảnh & web mẫu -->
                </div>

            </div>
        </section>

        <!-- Thanh thông báo khi đang lọc tìm kiếm / danh mục -->
        <div id="filterStatusBar" class="hidden bg-amber-50 border-b border-amber-200 py-3">
            <div class="flatsome-container flex items-center justify-between">
                <div class="text-sm font-medium text-pk-navy">
                    Đang hiển thị: <span id="filterStatusText" class="font-bold text-pk-goldDark">Tất cả sản phẩm</span>
                </div>
                <button onclick="filterCategory('all')" class="px-3 py-1 rounded-lg bg-white border border-amber-300 text-xs font-semibold text-pk-navy hover:bg-amber-100">
                    <i class="fa-solid fa-rotate-left mr-1"></i> Bỏ lọc
                </button>
            </div>
        </div>

        <!-- ==========================================
             CÁC SECTION SẢN PHẨM THEO NHÓM DANH MỤC (CHUẨN FLATSOME)
             - Trên điện thoại: Chia thành 2 cột (grid-cols-2)
             - Trên máy tính: Chia thành 4 cột (lg:grid-cols-4)
             - Hoàn toàn KHÔNG để nhãn dán (Sale/Hot/New) ở trang chủ
             ========================================== -->
        <div id="danh-muc-san-pham" class="space-y-8 py-6 md:py-10">
            <!-- Các Section sản phẩm được render tự động từ dữ liệu bên dưới để code gọn, dễ copy sang UX Builder -->
        </div>

        <!-- ==========================================
             SECTION QUY TRÌNH ĐẶT QUÀ TẶNG (CHUẨN QUÀ TẶNG QUANG VŨ)
             ========================================== -->
        <section class="section py-8 md:py-12 bg-white border-t border-gray-200">
            <div class="flatsome-container">
                <div class="section-title-container">
                    <div class="section-title">
                        <h2 class="section-title-main text-base sm:text-lg md:text-xl">
                            <i class="fa-solid fa-clipboard-check text-pk-gold"></i>
                            <span>QUY TRÌNH ĐẶT QUÀ TẶNG IN LOGO TẠI PHÚC KHANG THỊNH PHÁT</span>
                        </h2>
                    </div>
                </div>

                <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                    <div class="p-4 sm:p-5 rounded-xl bg-pk-cream border border-amber-200/80">
                        <div class="w-10 h-10 rounded-lg bg-pk-gold text-white font-heading font-bold flex items-center justify-center mb-3">01</div>
                        <h3 class="font-heading font-bold text-sm sm:text-base text-pk-navy mb-1">Tư Vấn & Chọn Mẫu</h3>
                        <p class="text-xs text-gray-600 leading-relaxed">Tiếp nhận nhu cầu, ngân sách và gợi ý mẫu quà tặng doanh nghiệp tối ưu nhất.</p>
                    </div>
                    <div class="p-4 sm:p-5 rounded-xl bg-pk-cream border border-amber-200/80">
                        <div class="w-10 h-10 rounded-lg bg-pk-gold text-white font-heading font-bold flex items-center justify-center mb-3">02</div>
                        <h3 class="font-heading font-bold text-sm sm:text-base text-pk-navy mb-1">Thiết Kế Demo Miễn Phí</h3>
                        <p class="text-xs text-gray-600 leading-relaxed">Lên maket in/khắc logo thương hiệu lên sản phẩm để khách hàng duyệt trước.</p>
                    </div>
                    <div class="p-4 sm:p-5 rounded-xl bg-pk-cream border border-amber-200/80">
                        <div class="w-10 h-10 rounded-lg bg-pk-gold text-white font-heading font-bold flex items-center justify-center mb-3">03</div>
                        <h3 class="font-heading font-bold text-sm sm:text-base text-pk-navy mb-1">Sản Xuất & In Ấn</h3>
                        <p class="text-xs text-gray-600 leading-relaxed">Gia công in ấn sắc nét, kiểm tra chất lượng nghiêm ngặt từng sản phẩm.</p>
                    </div>
                    <div class="p-4 sm:p-5 rounded-xl bg-pk-cream border border-amber-200/80">
                        <div class="w-10 h-10 rounded-lg bg-pk-gold text-white font-heading font-bold flex items-center justify-center mb-3">04</div>
                        <h3 class="font-heading font-bold text-sm sm:text-base text-pk-navy mb-1">Giao Hàng Đúng Hẹn</h3>
                        <p class="text-xs text-gray-600 leading-relaxed">Bàn giao tận nơi tại Đà Nẵng và vận chuyển toàn quốc, đầy đủ hóa đơn VAT.</p>
                    </div>
                </div>
            </div>
        </section>

    </main>

    <!-- ==========================================
         FOOTER (ĐẦY ĐỦ THÔNG TIN CÔNG TY, BẢN ĐỒ, FACEBOOK, SĐT)
         ========================================== -->
    <footer id="lien-he-footer" class="bg-pk-navy text-gray-300 pt-10 pb-20 md:pb-10 border-t-4 border-pk-gold">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-8 pb-8 border-b border-white/10">
                
                <!-- Cột 1: Thông tin công ty (5 cột) -->
                <div class="lg:col-span-5 space-y-3">
                    <div class="flex items-center gap-3">
                        <div class="w-11 h-11 bg-white rounded-lg p-1.5 flex items-center justify-center shrink-0">
                            <svg viewBox="0 0 120 110" class="w-full h-full" fill="none">
                                <path d="M25 12 H75 C94 12 106 23 106 40 C106 57 94 68 75 68 H44 V96 L25 84 V32 H72 C81 32 86 35 86 40 C86 45 81 48 72 48 H25 V12 Z" fill="#C69320"/>
                                <path d="M16 32 H34 V96 L16 84 V32 Z" fill="#C69320"/>
                                <path d="M46 68 H67 L80 56 L108 96 H46 V68 Z" fill="#1E2433"/>
                            </svg>
                        </div>
                        <div>
                            <div class="text-xs text-pk-goldLight font-semibold uppercase">Giải Pháp Quà Tặng Doanh Nghiệp</div>
                            <h3 class="font-heading font-extrabold text-white text-sm sm:text-base leading-snug">
                                CÔNG TY TNHH THƯƠNG MẠI & DỊCH VỤ PHÚC KHANG THỊNH PHÁT
                            </h3>
                        </div>
                    </div>

                    <ul class="space-y-2.5 text-sm pt-2">
                        <li class="flex items-start gap-2.5">
                            <i class="fa-solid fa-location-dot text-pk-goldLight mt-1 w-4 text-center"></i>
                            <span><strong>Địa chỉ:</strong> 252 Tô Hiệu, Phường Hòa Khánh, Tp. Đà Nẵng</span>
                        </li>
                        <li class="flex items-center gap-2.5">
                            <i class="fa-solid fa-phone text-pk-goldLight w-4 text-center"></i>
                            <span><strong>Hotline / Zalo:</strong> <a href="tel:0938613943" class="text-pk-goldLight font-bold hover:underline">0938.613.943</a></span>
                        </li>
                        <li class="flex items-center gap-2.5">
                            <i class="fa-solid fa-globe text-pk-goldLight w-4 text-center"></i>
                            <span><strong>Website:</strong> <a href="https://phuckhangthinhphat.com" class="hover:text-white">phuckhangthinhphat.com</a></span>
                        </li>
                        <li class="flex items-center gap-2.5">
                            <i class="fa-brands fa-facebook text-pk-goldLight w-4 text-center"></i>
                            <span><strong>Facebook:</strong> <a href="https://www.facebook.com/nguyen.thu.trang.854486/" target="_blank" rel="noopener noreferrer" class="hover:text-white underline">facebook.com/nguyen.thu.trang.854486</a></span>
                        </li>
                    </ul>
                </div>

                <!-- Cột 2: Danh mục sản phẩm chính (3 cột) -->
                <div class="lg:col-span-3 space-y-3">
                    <h4 class="font-heading font-bold text-white uppercase text-sm tracking-wider border-l-4 border-pk-gold pl-2.5">
                        Danh Mục Quà Tặng
                    </h4>
                    <ul class="grid grid-cols-2 lg:grid-cols-1 gap-2 text-sm">
                        <li><a href="#sec-binh-giu-nhiet" class="hover:text-pk-goldLight transition"><i class="fa-solid fa-angle-right text-xs mr-1.5 text-pk-gold"></i>Bình giữ nhiệt in logo</a></li>
                        <li><a href="#sec-gom-su" class="hover:text-pk-goldLight transition"><i class="fa-solid fa-angle-right text-xs mr-1.5 text-pk-gold"></i>Ly sứ & Ấm chén Bát Tràng</a></li>
                        <li><a href="#sec-quang-cao" class="hover:text-pk-goldLight transition"><i class="fa-solid fa-angle-right text-xs mr-1.5 text-pk-gold"></i>Ô dù, Áo mưa, Mũ bảo hiểm</a></li>
                        <li><a href="#sec-van-phong" class="hover:text-pk-goldLight transition"><i class="fa-solid fa-angle-right text-xs mr-1.5 text-pk-gold"></i>Sổ tay bìa da & Bút kim loại</a></li>
                        <li><a href="#sec-van-phong" class="hover:text-pk-goldLight transition"><i class="fa-solid fa-angle-right text-xs mr-1.5 text-pk-gold"></i>Balo, Sạc dự phòng, Đồng hồ</a></li>
                        <li><a href="#sec-mua-vu" class="hover:text-pk-goldLight transition"><i class="fa-solid fa-angle-right text-xs mr-1.5 text-pk-gold"></i>Bánh Trung Thu & Quà Tết</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Kết nối Google Maps & Mạng xã hội (4 cột) -->
                <div class="lg:col-span-4 space-y-3">
                    <h4 class="font-heading font-bold text-white uppercase text-sm tracking-wider border-l-4 border-pk-gold pl-2.5">
                        Bản Đồ & Kết Nối Nhanh
                    </h4>
                    <div class="bg-white/5 rounded-xl p-4 border border-white/10 space-y-3">
                        <div class="flex items-start gap-3">
                            <div class="w-10 h-10 rounded-lg bg-red-500/20 text-red-400 flex items-center justify-center shrink-0 text-lg">
                                <i class="fa-solid fa-map-location-dot"></i>
                            </div>
                            <div class="text-xs leading-relaxed">
                                <div class="font-bold text-white text-sm">Văn phòng Đà Nẵng</div>
                                <div>252 Tô Hiệu, Phường Hòa Khánh, Tp. Đà Nẵng</div>
                            </div>
                        </div>
                        <div class="grid grid-cols-2 gap-2 pt-1">
                            <a href="https://maps.app.goo.gl/JNZ3N1iF34Te4HBW7" target="_blank" rel="noopener noreferrer" class="py-2 px-3 rounded-lg bg-pk-gold hover:bg-pk-goldDark text-white font-semibold text-xs text-center flex items-center justify-center gap-1.5 transition">
                                <i class="fa-solid fa-diamond-turn-right"></i> Chỉ đường Map
                            </a>
                            <a href="https://www.facebook.com/nguyen.thu.trang.854486/" target="_blank" rel="noopener noreferrer" class="py-2 px-3 rounded-lg bg-blue-600 hover:bg-blue-700 text-white font-semibold text-xs text-center flex items-center justify-center gap-1.5 transition">
                                <i class="fa-brands fa-facebook-f"></i> Trang Facebook
                            </a>
                        </div>
                    </div>
                </div>

            </div>

            <div class="pt-5 flex flex-col sm:flex-row items-center justify-between text-xs text-gray-400 gap-2">
                <div>© Bản quyền thuộc về <strong class="text-white">phuckhangthinhphat.com</strong> – Công ty TNHH TM & DV Phúc Khang Thịnh Phát.</div>
                <div>Giao diện chuẩn Flatsome UX Builder</div>
            </div>
        </div>
    </footer>

    <!-- ==========================================
         CỤM NÚT LIÊN HỆ NỔI (ZALO, FACEBOOK, BẢN ĐỒ, GỌI ĐIỆN)
         ========================================== -->
    <div class="fixed right-3 sm:right-5 bottom-4 sm:bottom-6 z-40 flex flex-col items-end gap-3">
        
        <!-- Nút Google Maps -->
        <a href="https://maps.app.goo.gl/JNZ3N1iF34Te4HBW7" target="_blank" rel="noopener noreferrer" title="Xem bản đồ 252 Tô Hiệu" class="group flex items-center gap-2 bg-white hover:bg-red-50 text-gray-800 p-1.5 pr-3 rounded-full shadow-lg border border-gray-200 transition">
            <span class="w-9 h-9 rounded-full bg-red-500 text-white flex items-center justify-center text-base">
                <i class="fa-solid fa-location-dot"></i>
            </span>
            <span class="text-xs font-bold hidden sm:inline">Chỉ đường</span>
        </a>

        <!-- Nút Facebook -->
        <a href="https://www.facebook.com/nguyen.thu.trang.854486/" target="_blank" rel="noopener noreferrer" title="Chat Facebook" class="group flex items-center gap-2 bg-white hover:bg-blue-50 text-gray-800 p-1.5 pr-3 rounded-full shadow-lg border border-gray-200 transition">
            <span class="w-9 h-9 rounded-full bg-[#1877F2] text-white flex items-center justify-center text-base contact-pulse relative">
                <i class="fa-brands fa-facebook-f"></i>
            </span>
            <span class="text-xs font-bold text-[#1877F2] hidden sm:inline">Facebook</span>
        </a>

        <!-- Nút Zalo -->
        <a href="https://zalo.me/0938613943" target="_blank" rel="noopener noreferrer" title="Chat Zalo 0938.613.943" class="group flex items-center gap-2 bg-white hover:bg-blue-50 text-gray-800 p-1.5 pr-3 rounded-full shadow-lg border border-gray-200 transition">
            <span class="w-9 h-9 rounded-full bg-[#0068FF] text-white flex items-center justify-center font-heading font-extrabold text-xs contact-pulse relative">
                Zalo
            </span>
            <span class="text-xs font-bold text-[#0068FF] hidden sm:inline">0938.613.943</span>
        </a>

        <!-- Nút Gọi Hotline -->
        <a href="tel:0938613943" title="Gọi ngay 0938.613.943" class="flex items-center gap-2 bg-pk-gold hover:bg-pk-goldDark text-white p-1.5 pr-4 rounded-full shadow-xl transition">
            <span class="w-9 h-9 rounded-full bg-white text-pk-goldDark flex items-center justify-center text-base contact-pulse relative">
                <i class="fa-solid fa-phone-volume"></i>
            </span>
            <div class="leading-tight">
                <div class="text-[10px] uppercase opacity-90">Gọi báo giá</div>
                <div class="text-xs sm:text-sm font-extrabold">0938.613.943</div>
            </div>
        </a>
    </div>

    <!-- ==========================================
         MODAL TƯ VẤN / BÁO GIÁ NHANH SẢN PHẨM
         ========================================== -->
    <div id="productModal" class="fixed inset-0 bg-black/60 z-50 hidden items-center justify-center p-4">
        <div class="bg-white rounded-2xl max-w-md w-full p-5 sm:p-6 shadow-2xl relative">
            <button onclick="closeProductModal()" class="absolute top-4 right-4 w-8 h-8 rounded-full bg-gray-100 hover:bg-gray-200 flex items-center justify-center text-gray-600">
                <i class="fa-solid fa-xmark"></i>
            </button>
            <div class="text-xs font-bold uppercase text-pk-gold tracking-wider">Yêu cầu báo giá & Thiết kế logo</div>
            <h3 id="modalProductName" class="font-heading font-extrabold text-lg text-pk-navy mt-1 pr-6">Bình Giữ Nhiệt In Logo PK</h3>
            <p class="text-xs text-gray-600 mt-1">Liên hệ trực tiếp với <strong>Phúc Khang Thịnh Phát</strong> để nhận báo giá sỉ tận xưởng và bản thiết kế in logo miễn phí:</p>
            
            <div class="mt-4 space-y-2.5">
                <a href="https://zalo.me/0938613943" target="_blank" rel="noopener noreferrer" class="w-full py-3 px-4 rounded-xl bg-[#0068FF] hover:bg-blue-700 text-white font-bold text-sm flex items-center justify-center gap-2 transition">
                    <i class="fa-solid fa-comment-dots"></i> Nhắn Zalo Nhận Báo Giá (0938.613.943)
                </a>
                <a href="https://www.facebook.com/nguyen.thu.trang.854486/" target="_blank" rel="noopener noreferrer" class="w-full py-3 px-4 rounded-xl bg-[#1877F2] hover:bg-blue-800 text-white font-bold text-sm flex items-center justify-center gap-2 transition">
                    <i class="fa-brands fa-facebook"></i> Nhắn Tin Qua Facebook
                </a>
                <a href="tel:0938613943" class="w-full py-3 px-4 rounded-xl bg-amber-50 hover:bg-amber-100 text-pk-navy border border-amber-300 font-bold text-sm flex items-center justify-center gap-2 transition">
                    <i class="fa-solid fa-phone text-pk-gold"></i> Gọi Trực Tiếp: 0938.613.943
                </a>
            </div>
        </div>
    </div>

    <!-- ==========================================
         JAVASCRIPT: DỮ LIỆU DANH MỤC & SẢN PHẨM + HÌNH ẢNH SVG IN LOGO PK
         ========================================== -->
    <script>
        // Hàm tạo hình minh họa SVG sắc nét có in logo "PK" vàng kim giống hệt phong cách ảnh chụp của khách
        function getPKProductGraphic(type) {
            const pkBadge = `<text x="100" y="96" text-anchor="middle" fill="#D4AF37" font-family="Montserrat" font-weight="800" font-size="12">PK</text>`;
            switch (type) {
                case 'binh-giu-nhiet':
                    return `<svg viewBox="0 0 200 160" class="w-full h-full">
                        <rect x="42" y="25" width="32" height="110" rx="6" fill="#F9FAFB" stroke="#D1D5DB" stroke-width="1.5"/>
                        <rect x="42" y="25" width="32" height="14" rx="3" fill="#D1D5DB"/>
                        <text x="58" y="88" text-anchor="middle" fill="#C69320" font-weight="800" font-size="11">PK</text>
                        <rect x="84" y="22" width="34" height="113" rx="6" fill="#1E3A8A"/>
                        <rect x="84" y="22" width="34" height="14" rx="3" fill="#172554"/>
                        <text x="101" y="86" text-anchor="middle" fill="#FDE047" font-weight="800" font-size="11">PK</text>
                        <rect x="128" y="25" width="32" height="110" rx="6" fill="#14532D"/>
                        <rect x="128" y="25" width="32" height="14" rx="3" fill="#052E16"/>
                        <text x="144" y="88" text-anchor="middle" fill="#FDE047" font-weight="800" font-size="11">PK</text>
                    </svg>`;
                case 'ly-su':
                    return `<svg viewBox="0 0 200 160" class="w-full h-full">
                        <path d="M108 65 H125 C133 65 133 95 125 95 H108" fill="none" stroke="#B91C1C" stroke-width="6"/>
                        <rect x="65" y="52" width="48" height="58" rx="5" fill="#B91C1C"/>
                        <text x="89" y="86" text-anchor="middle" fill="#FDE047" font-weight="800" font-size="12">PK</text>
                        <path d="M62 72 H76 C82 72 82 102 76 102 H62" fill="none" stroke="#E5E7EB" stroke-width="5"/>
                        <rect x="28" y="60" width="42" height="52" rx="5" fill="#FFFFFF" stroke="#D1D5DB" stroke-width="1.5"/>
                        <text x="49" y="90" text-anchor="middle" fill="#C69320" font-weight="800" font-size="11">PK</text>
                        <rect x="125" y="58" width="42" height="52" rx="5" fill="#1E3A8A"/>
                        <text x="146" y="88" text-anchor="middle" fill="#FDE047" font-weight="800" font-size="11">PK</text>
                    </svg>`;
                case 'binh-thuy-tinh':
                    return `<svg viewBox="0 0 200 160" class="w-full h-full">
                        <rect x="78" y="30" width="44" height="105" rx="8" fill="#E0F2FE" fill-opacity="0.7" stroke="#93C5FD" stroke-width="2"/>
                        <rect x="85" y="16" width="30" height="14" rx="3" fill="#9CA3AF"/>
                        <path d="M115 22 C132 22 135 55 122 65" fill="none" stroke="#6B7280" stroke-width="2"/>
                        <text x="100" y="88" text-anchor="middle" fill="#C69320" font-weight="800" font-size="13">PK</text>
                        <circle cx="142" cy="120" r="14" fill="#FDE047" stroke="#CA8A04" stroke-width="1.5"/>
                    </svg>`;
                case 'so-tay':
                    return `<svg viewBox="0 0 200 160" class="w-full h-full">
                        <rect x="42" y="28" width="65" height="98" rx="5" transform="rotate(-6 42 28)" fill="#9A3412" stroke="#7C2D12" stroke-width="1.5"/>
                        <text x="72" y="72" text-anchor="middle" fill="#FDE047" font-weight="800" font-size="12">PK</text>
                        <rect x="98" y="32" width="65" height="98" rx="5" transform="rotate(5 98 32)" fill="#1E293B"/>
                        <text x="128" y="78" text-anchor="middle" fill="#FDE047" font-weight="800" font-size="12">PK</text>
                    </svg>`;
                case 'but-kim-loai':
                    return `<svg viewBox="0 0 200 160" class="w-full h-full">
                        <rect x="65" y="20" width="8" height="115" rx="4" transform="rotate(14 65 20)" fill="#94A3B8"/>
                        <rect x="102" y="20" width="8" height="115" rx="4" transform="rotate(14 102 20)" fill="#1D4ED8"/>
                        <rect x="138" y="20" width="8" height="115" rx="4" transform="rotate(14 138 20)" fill="#1E293B" stroke="#D4AF37"/>
                    </svg>`;
                case 'dong-ho':
                    return `<svg viewBox="0 0 200 160" class="w-full h-full">
                        <rect x="86" y="14" width="28" height="132" rx="4" fill="#451A03"/>
                        <circle cx="100" cy="80" r="34" fill="#1E3A8A" stroke="#D4AF37" stroke-width="4"/>
                        <line x1="100" y1="80" x2="100" y2="58" stroke="#FDE047" stroke-width="2.5"/>
                        <line x1="100" y1="80" x2="118" y2="80" stroke="#FDE047" stroke-width="2"/>
                        <text x="100" y="70" text-anchor="middle" fill="#FDE047" font-weight="800" font-size="9">PK</text>
                    </svg>`;
                case 'o-du':
                    return `<svg viewBox="0 0 200 160" class="w-full h-full">
                        <path d="M25 75 Q65 25 105 75 Z" fill="#B91C1C"/>
                        <path d="M65 95 Q115 35 168 95 L116 112 Z" fill="#1E3A8A"/>
                        <line x1="116" y1="95" x2="105" y2="138" stroke="#374151" stroke-width="3"/>
                        <text x="122" y="88" text-anchor="middle" fill="#FDE047" font-weight="800" font-size="11">PK</text>
                    </svg>`;
                case 'gau-bong':
                    return `<svg viewBox="0 0 200 160" class="w-full h-full">
                        <circle cx="62" cy="46" r="10" fill="#E5E7EB"/><circle cx="98" cy="46" r="10" fill="#E5E7EB"/>
                        <circle cx="80" cy="60" r="22" fill="#F3F4F6"/>
                        <rect x="58" y="80" width="44" height="42" rx="16" fill="#FFFFFF" stroke="#E5E7EB"/>
                        <text x="80" y="104" text-anchor="middle" fill="#C69320" font-weight="800" font-size="10">PK</text>
                        <circle cx="115" cy="52" r="10" fill="#D97706"/><circle cx="149" cy="52" r="10" fill="#D97706"/>
                        <circle cx="132" cy="66" r="20" fill="#F59E0B"/>
                        <rect x="112" y="84" width="40" height="40" rx="14" fill="#FFFFFF" stroke="#FDE68A"/>
                        <text x="132" y="106" text-anchor="middle" fill="#C69320" font-weight="800" font-size="10">PK</text>
                    </svg>`;
                case 'ao-mua':
                    return `<svg viewBox="0 0 200 160" class="w-full h-full">
                        <rect x="44" y="45" width="52" height="82" rx="6" fill="#1D4ED8"/>
                        <circle cx="70" cy="36" r="12" fill="#1D4ED8"/>
                        <text x="70" y="88" text-anchor="middle" fill="#FDE047" font-weight="800" font-size="13">PK</text>
                        <rect x="104" y="45" width="52" height="82" rx="6" fill="#EAB308"/>
                        <circle cx="130" cy="36" r="12" fill="#EAB308"/>
                        <text x="130" y="88" text-anchor="middle" fill="#1E293B" font-weight="800" font-size="13">PK</text>
                    </svg>`;
                case 'balo':
                    return `<svg viewBox="0 0 200 160" class="w-full h-full">
                        <rect x="36" y="38" width="52" height="86" rx="14" fill="#1F2937"/>
                        <text x="62" y="78" text-anchor="middle" fill="#FDE047" font-weight="800" font-size="11">PK</text>
                        <rect x="82" y="36" width="50" height="86" rx="14" fill="#9CA3AF"/>
                        <text x="107" y="76" text-anchor="middle" fill="#C69320" font-weight="800" font-size="11">PK</text>
                        <rect x="122" y="38" width="50" height="86" rx="14" fill="#1E3A8A"/>
                        <text x="147" y="78" text-anchor="middle" fill="#FDE047" font-weight="800" font-size="11">PK</text>
                    </svg>`;
                case 'the-hanh-ly':
                    return `<svg viewBox="0 0 200 160" class="w-full h-full">
                        <rect x="42" y="48" width="34" height="72" rx="6" fill="#9A3412"/>
                        <text x="59" y="88" text-anchor="middle" fill="#FDE047" font-weight="800" font-size="10">PK</text>
                        <rect x="84" y="48" width="34" height="72" rx="6" fill="#1E293B"/>
                        <text x="101" y="88" text-anchor="middle" fill="#FDE047" font-weight="800" font-size="10">PK</text>
                        <rect x="126" y="48" width="34" height="72" rx="6" fill="#6B7280"/>
                        <text x="143" y="88" text-anchor="middle" fill="#FDE047" font-weight="800" font-size="10">PK</text>
                    </svg>`;
                case 'sac-du-phong':
                    return `<svg viewBox="0 0 200 160" class="w-full h-full">
                        <rect x="48" y="34" width="52" height="86" rx="8" transform="rotate(15 48 34)" fill="#1F2937"/>
                        <text x="64" y="82" text-anchor="middle" fill="#FDE047" font-weight="800" font-size="11">PK</text>
                        <rect x="108" y="42" width="52" height="86" rx="8" transform="rotate(15 108 42)" fill="#F9FAFB" stroke="#D1D5DB" stroke-width="2"/>
                        <text x="124" y="90" text-anchor="middle" fill="#C69320" font-weight="800" font-size="11">PK</text>
                    </svg>`;
                case 'quat-cam-tay':
                    return `<svg viewBox="0 0 200 160" class="w-full h-full">
                        <circle cx="70" cy="56" r="28" fill="#E0F2FE" stroke="#7DD3FC" stroke-width="3"/>
                        <rect x="62" y="84" width="16" height="46" rx="6" fill="#BAE6FD"/>
                        <text x="70" y="108" text-anchor="middle" fill="#C69320" font-weight="800" font-size="8">PK</text>
                        <circle cx="132" cy="56" r="28" fill="#FCE7F3" stroke="#F9A8D4" stroke-width="3"/>
                        <rect x="124" y="84" width="16" height="46" rx="6" fill="#FBCFE8"/>
                        <text x="132" y="108" text-anchor="middle" fill="#C69320" font-weight="800" font-size="8">PK</text>
                    </svg>`;
                case 'mu-bao-hiem':
                    return `<svg viewBox="0 0 200 160" class="w-full h-full">
                        <path d="M45 95 C45 45 155 45 155 95 Z" fill="#1E3A8A"/>
                        <path d="M40 92 H162 L152 106 H48 Z" fill="#D4AF37"/>
                        <text x="100" y="78" text-anchor="middle" fill="#FDE047" font-weight="800" font-size="15">PK</text>
                    </svg>`;
                case 'am-chen':
                    return `<svg viewBox="0 0 200 160" class="w-full h-full">
                        <ellipse cx="95" cy="88" rx="34" ry="26" fill="#FFFFFF" stroke="#D4AF37" stroke-width="2"/>
                        <path d="M128 82 C142 72 146 88 128 96" fill="none" stroke="#D4AF37" stroke-width="3"/>
                        <path d="M62 76 C48 76 48 98 62 98" fill="none" stroke="#D4AF37" stroke-width="3"/>
                        <text x="95" y="92" text-anchor="middle" fill="#C69320" font-weight="800" font-size="12">PK</text>
                        <rect x="35" y="98" width="22" height="20" rx="4" fill="#FFFFFF" stroke="#D4AF37" stroke-width="1.5"/>
                        <rect x="142" y="98" width="22" height="20" rx="4" fill="#FFFFFF" stroke="#D4AF37" stroke-width="1.5"/>
                    </svg>`;
                default:
                    return `<svg viewBox="0 0 200 160" class="w-full h-full">
                        <rect x="45" y="35" width="110" height="90" rx="8" fill="#991B1B" stroke="#D4AF37" stroke-width="2"/>
                        ${pkBadge}
                    </svg>`;
            }
        }

        // 14 Danh mục kết hợp chính xác từ ảnh chụp của bạn + Quà Tặng Quang Vũ
        const categoriesData = [
            { id: 'binh-giu-nhiet', name: 'BÌNH GIỮ NHIỆT', group: 'binh-giu-nhiet', graphic: 'binh-giu-nhiet' },
            { id: 'ly-su', name: 'LY SỨ', group: 'gom-su', graphic: 'ly-su' },
            { id: 'binh-thuy-tinh', name: 'BÌNH THỦY TINH', group: 'binh-giu-nhiet', graphic: 'binh-thuy-tinh' },
            { id: 'so-tay', name: 'SỔ TAY BÌA DA', group: 'van-phong', graphic: 'so-tay' },
            { id: 'but-kim-loai', name: 'BÚT KIM LOẠI', group: 'van-phong', graphic: 'but-kim-loai' },
            { id: 'dong-ho', name: 'ĐỒNG HỒ', group: 'cong-nghe', graphic: 'dong-ho' },
            { id: 'mu-bao-hiem', name: 'MŨ BẢO HIỂM', group: 'quang-cao', graphic: 'mu-bao-hiem' },
            { id: 'o-du', name: 'Ô DÙ', group: 'quang-cao', graphic: 'o-du' },
            { id: 'gau-bong', name: 'GẤU BÔNG', group: 'quang-cao', graphic: 'gau-bong' },
            { id: 'ao-mua', name: 'ÁO MƯA', group: 'quang-cao', graphic: 'ao-mua' },
            { id: 'balo', name: 'BALO', group: 'van-phong', graphic: 'balo' },
            { id: 'the-hanh-ly', name: 'THẺ HÀNH LÝ', group: 'cong-nghe', graphic: 'the-hanh-ly' },
            { id: 'sac-du-phong', name: 'SẠC DỰ PHÒNG', group: 'cong-nghe', graphic: 'sac-du-phong' },
            { id: 'quat-cam-tay', name: 'QUẠT CẦM TAY', group: 'cong-nghe', graphic: 'quat-cam-tay' }
        ];

        // Dữ liệu các Section sản phẩm (Lấy theo danh mục mẫu quatangquangvu.com + ảnh chụp)
        const productSections = [
            {
                id: 'sec-binh-giu-nhiet',
                group: 'binh-giu-nhiet',
                title: 'BÌNH GIỮ NHIỆT & BÌNH THỦY TINH IN LOGO',
                products: [
                    { code: 'PK-BGN01', name: 'Bình Giữ Nhiệt Inox 304 Hiển Thị Nhiệt Độ In Logo PK', graphic: 'binh-giu-nhiet' },
                    { code: 'PK-BGN02', name: 'Bình Giữ Nhiệt Vỏ Tre Khắc Laser Theo Yêu Cầu', graphic: 'binh-giu-nhiet' },
                    { code: 'PK-BGN03', name: 'Bình Giữ Nhiệt Lock&Lock In Logo Doanh Nghiệp', graphic: 'binh-giu-nhiet' },
                    { code: 'PK-BTT04', name: 'Bình Thủy Tinh Có Dây Xách In Logo Phúc Khang Thịnh Phát', graphic: 'binh-thuy-tinh' }
                ]
            },
            {
                id: 'sec-gom-su',
                group: 'gom-su',
                title: 'QUÀ TẶNG GỐM SỨ: LY SỨ & ẤM CHÉN BÁT TRÀNG',
                products: [
                    { code: 'PK-LS01', name: 'Ly Sứ Trắng Quai C In Logo Theo Yêu Cầu', graphic: 'ly-su' },
                    { code: 'PK-LS02', name: 'Bộ Ly Sứ Màu Cao Cấp In Nhũ Vàng Thương Hiệu', graphic: 'ly-su' },
                    { code: 'PK-AC01', name: 'Bộ Ấm Chén Bát Tràng Men Trắng Kẻ Chỉ Vàng In Logo', graphic: 'am-chen' },
                    { code: 'PK-AC02', name: 'Bộ Ấm Trà Dáng Bưởi Cành Quà Tặng Đại Hội, Đối Tác', graphic: 'am-chen' }
                ]
            },
            {
                id: 'sec-quang-cao',
                group: 'quang-cao',
                title: 'QUÀ TẶNG QUẢNG CÁO: Ô DÙ, ÁO MƯA, MŨ BẢO HIỂM, GẤU BÔNG',
                products: [
                    { code: 'PK-OD01', name: 'Ô Dù Cầm Tay Gấp 3 Tự Động 1 Chiều In Logo', graphic: 'o-du' },
                    { code: 'PK-AM01', name: 'Áo Mưa Cánh Dơi Vải Dù Siêu Nhẹ In Logo Công Ty', graphic: 'ao-mua' },
                    { code: 'PK-MBH01', name: 'Mũ Bảo Hiểm Quảng Cáo Nửa Đầu Đạt Chuẩn In Logo', graphic: 'mu-bao-hiem' },
                    { code: 'PK-GB01', name: 'Gấu Bông Thêu Logo Áo Thun Quà Tặng Sự Kiện', graphic: 'gau-bong' }
                ]
            },
            {
                id: 'sec-van-phong',
                group: 'van-phong',
                title: 'QUÀ TẶNG VĂN PHÒNG: SỔ TAY BÌA DA, BÚT KIM LOẠI, BALO',
                products: [
                    { code: 'PK-ST01', name: 'Sổ Tay Bìa Da Cao Cấp Dập Chìm / Ép Nhũ Vàng Logo', graphic: 'so-tay' },
                    { code: 'PK-BKL01', name: 'Bút Ký Kim Loại Khắc Tên & Logo Doanh Nghiệp', graphic: 'but-kim-loai' },
                    { code: 'PK-BL01', name: 'Balo Laptop Công Sở Chống Thấm Nước Thêu Logo', graphic: 'balo' },
                    { code: 'PK-GS01', name: 'Giftset Sổ Tay Bìa Da + Bút Ký + Bình Giữ Nhiệt Đồng Bộ', graphic: 'so-tay' }
                ]
            },
            {
                id: 'sec-cong-nghe',
                group: 'cong-nghe',
                title: 'PHỤ KIỆN & CÔNG NGHỆ: SẠC DỰ PHÒNG, ĐỒNG HỒ, QUẠT, THẺ HÀNH LÝ',
                products: [
                    { code: 'PK-SDP01', name: 'Pin Sạc Dự Phòng 10.000mAh In Logo Theo Yêu Cầu', graphic: 'sac-du-phong' },
                    { code: 'PK-DH01', name: 'Đồng Hồ Đeo Tay & Đồng Hồ Treo Tường In Logo', graphic: 'dong-ho' },
                    { code: 'PK-THL01', name: 'Thẻ Đeo Hành Lý Bằng Da In Logo Quà Tặng Du Lịch', graphic: 'the-hanh-ly' },
                    { code: 'PK-QCT01', name: 'Quạt Cầm Tay Mini Sạc Pin In Logo Sự Kiện Mùa Hè', graphic: 'quat-cam-tay' }
                ]
            },
            {
                id: 'sec-mua-vu',
                group: 'mua-vu',
                title: 'QUÀ TẾT DOANH NGHIỆP & HỘP BÁNH TRUNG THU CAO CẤP',
                products: [
                    { code: 'PK-TT01', name: 'Hộp Bánh Trung Thu Phú Quý In Logo Phúc Khang Thịnh Phát', graphic: 'default' },
                    { code: 'PK-TT02', name: 'Set Bánh Trung Thu 4 Bánh Kết Hợp Trà Thượng Hạng', graphic: 'default' },
                    { code: 'PK-QT01', name: 'Hộp Quà Tết Doanh Nghiệp An Khang (Rượu Vang & Hạt Dinh Dưỡng)', graphic: 'default' },
                    { code: 'PK-QT02', name: 'Giỏ Quà Tết Thịnh Vượng Thiết Kế Riêng Theo Ngân Sách', graphic: 'default' }
                ]
            }
        ];

        // Render Danh mục (Category Grid) đẹp mắt trên cả Desktop & Điện thoại
        function renderCategories() {
            const container = document.getElementById('categoryGridContainer');
            container.innerHTML = categoriesData.map(cat => `
                <div onclick="filterCategory('${cat.group}')" class="box-category cursor-pointer rounded-xl bg-gradient-to-b from-[#FAF7F2] to-[#F3EDE2] border border-gray-200/90 p-2.5 sm:p-3 flex flex-col items-center justify-between text-center">
                    <div class="w-full h-20 sm:h-24 flex items-center justify-center">
                        ${getPKProductGraphic(cat.graphic)}
                    </div>
                    <div class="mt-2 pt-1.5 border-t border-amber-900/10 w-full">
                        <h3 class="font-heading font-bold text-[11px] sm:text-xs text-pk-navy uppercase tracking-tight line-clamp-1">
                            ${cat.name}
                        </h3>
                    </div>
                </div>
            `).join('');
        }

        // Render các Section sản phẩm (Điện thoại 2 cột: grid-cols-2, Máy tính 4 cột: lg:grid-cols-4, KHÔNG nhãn dán)
        function renderProducts(activeGroup = 'all', searchKeyword = '') {
            const wrapper = document.getElementById('danh-muc-san-pham');
            const kw = searchKeyword.trim().toLowerCase();

            const filteredSections = productSections.map(sec => {
                if (activeGroup !== 'all' && sec.group !== activeGroup) return null;
                const matchedProducts = sec.products.filter(p => 
                    !kw || p.name.toLowerCase().includes(kw) || p.code.toLowerCase().includes(kw)
                );
                if (matchedProducts.length === 0) return null;
                return { ...sec, products: matchedProducts };
            }).filter(Boolean);

            if (filteredSections.length === 0) {
                wrapper.innerHTML = `
                    <div class="flatsome-container text-center py-12 bg-white rounded-xl border border-gray-200">
                        <p class="text-base font-semibold text-gray-700">Không tìm thấy sản phẩm phù hợp với từ khóa "${searchKeyword}".</p>
                        <button onclick="filterCategory('all')" class="mt-3 px-4 py-2 bg-pk-gold text-white rounded-lg text-sm font-semibold">Xem tất cả sản phẩm</button>
                    </div>
                `;
                return;
            }

            wrapper.innerHTML = filteredSections.map(sec => `
                <section id="${sec.id}" class="section">
                    <div class="flatsome-container">
                        <!-- Tiêu đề danh mục chuẩn Flatsome -->
                        <div class="section-title-container">
                            <div class="section-title">
                                <h2 class="section-title-main text-sm sm:text-base md:text-lg">
                                    <span>${sec.title}</span>
                                </h2>
                                <a href="https://zalo.me/0938613943" target="_blank" rel="noopener noreferrer" class="text-xs font-semibold text-pk-goldDark hover:underline shrink-0">
                                    Nhận catalogue <i class="fa-solid fa-angle-right"></i>
                                </a>
                            </div>
                        </div>

                        <!-- Lưới sản phẩm: 2 cột trên điện thoại (grid-cols-2), 4 cột trên máy tính (lg:grid-cols-4), KHÔNG có nhãn dán -->
                        <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-5">
                            ${sec.products.map(prod => `
                                <div class="col">
                                    <div class="col-inner h-full">
                                        <div class="product-small box bg-white rounded-xl border border-gray-200 overflow-hidden h-full flex flex-col justify-between">
                                            <!-- Box Image (Không có bất kỳ nhãn dán/sticker nào) -->
                                            <div onclick="openProductModal('${prod.name}')" class="box-image cursor-pointer bg-[#FAF7F2] p-3 sm:p-5 h-36 sm:h-48 flex items-center justify-center border-b border-gray-100">
                                                ${getPKProductGraphic(prod.graphic)}
                                            </div>
                                            <!-- Box Text -->
                                            <div class="box-text p-3 sm:p-4 flex-1 flex flex-col justify-between">
                                                <div>
                                                    <div class="text-[11px] text-gray-400 font-medium mb-1">Mã SP: ${prod.code}</div>
                                                    <h3 onclick="openProductModal('${prod.name}')" class="cursor-pointer font-semibold text-xs sm:text-sm text-pk-navy hover:text-pk-goldDark line-clamp-2 leading-snug">
                                                        ${prod.name}
                                                    </h3>
                                                </div>
                                                <div class="mt-3 pt-2.5 border-t border-gray-100 flex items-center justify-between gap-2">
                                                    <span class="text-xs sm:text-sm font-bold text-pk-goldDark">Giá: Liên hệ</span>
                                                    <button onclick="openProductModal('${prod.name}')" class="px-2.5 py-1.5 rounded-lg bg-pk-navy hover:bg-pk-gold text-white text-[11px] sm:text-xs font-semibold transition">
                                                        Báo giá
                                                    </button>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            `).join('')}
                        </div>
                    </div>
                </section>
            `).join('');
        }

        // Lọc theo danh mục
        function filterCategory(group) {
            const statusBar = document.getElementById('filterStatusBar');
            const statusText = document.getElementById('filterStatusText');
            const desktopInput = document.getElementById('desktopSearchInput');
            const mobileInput = document.getElementById('mobileSearchInput');
            if (desktopInput) desktopInput.value = '';
            if (mobileInput) mobileInput.value = '';

            if (group === 'all') {
                statusBar.classList.add('hidden');
            } else {
                const sec = productSections.find(s => s.group === group);
                statusText.textContent = sec ? sec.title : 'Danh mục đã chọn';
                statusBar.classList.remove('hidden');
            }
            renderProducts(group, '');
        }

        // Tìm kiếm trực tiếp
        function handleSearch(value) {
            const statusBar = document.getElementById('filterStatusBar');
            const statusText = document.getElementById('filterStatusText');
            if (value.trim() === '') {
                statusBar.classList.add('hidden');
                renderProducts('all', '');
            } else {
                statusText.textContent = `Từ khóa "${value}"`;
                statusBar.classList.remove('hidden');
                renderProducts('all', value);
            }
        }

        // Bật/tắt Menu trên điện thoại
        function toggleMobileMenu() {
            const drawer = document.getElementById('mobileMenuDrawer');
            const backdrop = document.getElementById('mobileMenuBackdrop');
            const isHidden = drawer.classList.contains('-translate-x-full');
            if (isHidden) {
                drawer.classList.remove('-translate-x-full');
                backdrop.classList.remove('hidden');
            } else {
                drawer.classList.add('-translate-x-full');
                backdrop.classList.add('hidden');
            }
        }

        // Mở/Đóng Modal Báo giá sản phẩm
        function openProductModal(productName) {
            document.getElementById('modalProductName').textContent = productName;
            const modal = document.getElementById('productModal');
            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        function closeProductModal() {
            const modal = document.getElementById('productModal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
        }

        // Khởi chạy khi tải trang
        window.onload = function() {
            renderCategories();
            renderProducts('all', '');
        };
    </script>
</body>
</html>
