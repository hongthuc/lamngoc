<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
    <title>CÔNG TY TNHH XÂY DỰNG - THƯƠNG MẠI LÂM NGỌC | Thiết Kế & Thi Công Trọn Gói Đà Nẵng</title>
    <meta name="description" content="CÔNG TY TNHH XÂY DỰNG - THƯƠNG MẠI LÂM NGỌC (lamngoc.com) - Chuyên thiết kế kiến trúc, thi công phần thô, hoàn thiện, xây nhà trọn gói uy tín tại Đà Nẵng. Hotline: 0937.533.505.">
    <meta name="keywords" content="xây dựng Lâm Ngọc, lamngoc.com, xây nhà trọn gói Đà Nẵng, thiết kế kiến trúc Đà Nẵng, thi công phần thô Ngũ Hành Sơn">

    <!-- Meta Open Graph & Thumbnail chia sẻ link sử dụng Logo công ty -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://lamngoc.com/">
    <meta property="og:site_name" content="lamngoc.com - Xây Dựng Lâm Ngọc">
    <meta property="og:title" content="CÔNG TY TNHH XÂY DỰNG - THƯƠNG MẠI LÂM NGỌC | lamngoc.com">
    <meta property="og:description" content="Chuyên Thiết Kế Kiến Trúc – Thi Công Phần Thô – Hoàn Thiện – Xây Nhà Trọn Gói tại Đà Nẵng. Hotline: 0937.533.505">
    <meta property="og:image" content="https://drive.google.com/thumbnail?id=1uHnQ0w68nFe-QMYcDYOS5oyClevmwZkj&sz=w1200">
    <meta property="og:image:secure_url" content="https://drive.google.com/thumbnail?id=1uHnQ0w68nFe-QMYcDYOS5oyClevmwZkj&sz=w1200">
    <meta property="og:image:alt" content="Logo Công Ty TNHH Xây Dựng - Thương Mại Lâm Ngọc">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="CÔNG TY TNHH XÂY DỰNG - THƯƠNG MẠI LÂM NGỌC | lamngoc.com">
    <meta name="twitter:description" content="Chuyên Thiết Kế & Thi Công Xây Dựng Trọn Gói tại Đà Nẵng. Hotline: 0937.533.505">
    <meta name="twitter:image" content="https://drive.google.com/thumbnail?id=1uHnQ0w68nFe-QMYcDYOS5oyClevmwZkj&sz=w1200">

    <!-- Favicon sử dụng Logo công ty -->
    <link rel="icon" type="image/png" href="https://drive.google.com/thumbnail?id=1uHnQ0w68nFe-QMYcDYOS5oyClevmwZkj&sz=w128">
    <link rel="apple-touch-icon" href="https://drive.google.com/thumbnail?id=1uHnQ0w68nFe-QMYcDYOS5oyClevmwZkj&sz=w256">

    <!-- Font Inter & Font Awesome Icons -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'system-ui', '-apple-system', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            DEFAULT: '#0E5E49',   /* Xanh ngọc lục bảo đậm - đồng bộ nhận diện Lâm Ngọc */
                            dark: '#094233',
                            light: '#167A60',
                            soft: '#EDF6F3',
                        },
                        accent: {
                            DEFAULT: '#C9932B',   /* Vàng đồng xây dựng sang trọng */
                            hover: '#B07D1E',
                            light: '#FBF5E8',
                        }
                    }
                }
            }
        }
    </script>

    <style>
        /* Cài đặt gốc chống tràn viền ngang và chống lệch phải tuyệt đối */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            width: 100%;
            max-width: 100%;
            overflow-x: hidden;
            margin: 0;
            padding: 0;
            scroll-behavior: smooth;
            font-family: 'Inter', sans-serif;
            color: #222222;
            background-color: #FFFFFF;
            -webkit-font-smoothing: antialiased;
        }

        /* Container chuẩn 95% màn hình trên máy tính, gọn gàng cân đối 2 bên trên điện thoại */
        .flatsome-container {
            width: 100%;
            max-width: 100%;
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }
        @media (min-width: 1024px) {
            .flatsome-container {
                width: 95%;
                max-width: 95%;
                padding-left: 0;
                padding-right: 0;
            }
        }

        /* Tối ưu thanh menu trên máy tính: chữ nhỏ gọn, viết liền không xuống dòng bên trong tên danh mục */
        .nav-item-link {
            white-space: nowrap;
            display: inline-flex;
            align-items: center;
            gap: 4px;
            transition: color 0.2s ease, border-color 0.2s ease;
        }

        /* Dropdown Flatsome mượt mà */
        .has-dropdown {
            position: relative;
        }
        .has-dropdown .dropdown-menu {
            opacity: 0;
            visibility: hidden;
            transform: translateY(8px);
            transition: all 0.2s ease;
            pointer-events: none;
        }
        .has-dropdown:hover .dropdown-menu,
        .has-dropdown:focus-within .dropdown-menu {
            opacity: 1;
            visibility: visible;
            transform: translateY(0);
            pointer-events: auto;
        }

        /* Đường kẻ tiêu đề phong cách Flatsome UX Builder */
        .section-heading-line {
            width: 56px;
            height: 3px;
            background: linear-gradient(90deg, #0E5E49 0%, #C9932B 100%);
            border-radius: 999px;
            margin: 10px auto 0;
        }

        /* Slider 2 banner kích thước bằng nhau */
        .hero-slider-track {
            display: flex;
            transition: transform 0.65s cubic-bezier(0.22, 1, 0.36, 1);
            width: 100%;
        }
        .hero-slide-item {
            min-width: 100%;
            width: 100%;
            flex-shrink: 0;
        }

        /* Hiệu ứng ảnh hover mềm mại chuẩn Flatsome */
        .img-zoom-wrap {
            overflow: hidden;
            position: relative;
            background-color: #f1f5f4;
        }
        .img-zoom-wrap img {
            transition: transform 0.45s ease;
        }
        .img-zoom-wrap:hover img {
            transform: scale(1.05);
        }

        /* Hiệu ứng rung nhẹ cho nút Hotline nổi */
        @keyframes pulseRing {
            0% {
                box-shadow: 0 0 0 0 rgba(220, 38, 38, 0.55);
            }
            70% {
                box-shadow: 0 0 0 12px rgba(220, 38, 38, 0);
            }
            100% {
                box-shadow: 0 0 0 0 rgba(220, 38, 38, 0);
            }
        }
        .hotline-pulse {
            animation: pulseRing 2s infinite;
        }

        /* Ẩn thanh cuộn phụ nhưng vẫn vuốt mượt khi cần */
        .no-scrollbar::-webkit-scrollbar {
            display: none;
        }
        .no-scrollbar {
            -ms-overflow-style: none;
            scrollbar-width: none;
        }
    </style>
</head>
<body class="bg-white text-slate-800">

    <!-- ========================================================= -->
    <!-- TOP BAR THÔNG TIN LIÊN HỆ (CHUẨN FLATSOME HEADER TOP)     -->
    <!-- ========================================================= -->
    <div class="bg-brand text-white text-[11px] sm:text-xs py-2 border-b border-brand-dark">
        <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
            <div class="flex items-center flex-wrap gap-x-4 gap-y-1">
                <a href="tel:0937533505" class="inline-flex items-center gap-1.5 hover:text-accent-light transition">
                    <i class="fa-solid fa-phone text-accent"></i>
                    <span class="font-semibold">0937.533.505</span>
                </a>
                <span class="hidden sm:inline opacity-40">|</span>
                <span class="hidden sm:inline-flex items-center gap-1.5">
                    <i class="fa-solid fa-globe text-accent"></i>
                    <span>lamngoc.com</span>
                </span>
                <span class="hidden md:inline opacity-40">|</span>
                <span class="hidden md:inline-flex items-center gap-1.5">
                    <i class="fa-solid fa-location-dot text-accent"></i>
                    <span>Thửa đất số 151, tờ bản đồ 82, Phường Ngũ Hành Sơn, TP Đà Nẵng</span>
                </span>
            </div>
            <div class="flex items-center gap-3">
                <a href="https://www.facebook.com/xay.dung.lam.ngoc" target="_blank" rel="noopener noreferrer" aria-label="Facebook Lâm Ngọc" class="hover:text-accent transition">
                    <i class="fa-brands fa-facebook-f"></i>
                </a>
                <a href="https://zalo.me/0937533505" target="_blank" rel="noopener noreferrer" aria-label="Zalo Lâm Ngọc" class="hover:text-accent transition font-bold text-[11px]">
                    Zalo
                </a>
            </div>
        </div>
    </div>

    <!-- ========================================================= -->
    <!-- HEADER CHÍNH: LOGO GỌN NHỎ + MENU 1 HÀNG (KHÔNG NÚT GỌI)  -->
    <!-- ========================================================= -->
    <header id="main-header" class="sticky top-0 z-40 bg-white/95 backdrop-blur-md shadow-sm border-b border-slate-100 w-full">
        <div class="flatsome-container py-2 md:py-2.5 flex items-center justify-between gap-2 lg:gap-4">

            <!-- Logo Công Ty (chỉnh gọn nhỏ thanh lịch) -->
            <a href="#trang-chu" class="flex items-center gap-2 shrink-0 group">
                <img
                    id="brand-logo"
                    src="https://drive.google.com/thumbnail?id=1uHnQ0w68nFe-QMYcDYOS5oyClevmwZkj&sz=w400"
                    data-drive-id="1uHnQ0w68nFe-QMYcDYOS5oyClevmwZkj"
                    alt="Logo Công Ty TNHH Xây Dựng - Thương Mại Lâm Ngọc"
                    class="h-10 sm:h-11 lg:h-12 w-auto max-w-[130px] object-contain rounded"
                    onerror="handleDriveImageError(this, 'LOGO LAM NGOC')"
                >
                <div class="leading-tight">
                    <div class="text-xs sm:text-[13px] lg:text-sm font-extrabold text-brand tracking-tight uppercase whitespace-nowrap">
                        XÂY DỰNG LÂM NGỌC
                    </div>
                    <div class="text-[10px] text-slate-500 font-medium tracking-wide whitespace-nowrap">
                        lamngoc.com
                    </div>
                </div>
            </a>

            <!-- Menu Danh Mục Máy Tính: chữ nhỏ gọn, viết liền 1 hàng, tuyệt đối không xuống dòng tên danh mục -->
            <nav aria-label="Menu chính" class="hidden lg:flex items-center justify-end flex-wrap gap-x-1 xl:gap-x-2 gap-y-1 flex-1 min-w-0">
                <a href="#trang-chu" class="nav-item-link px-2 xl:px-2.5 py-2 text-[11.5px] xl:text-[12.5px] font-semibold uppercase text-brand hover:text-accent rounded">
                    Trang chủ
                </a>
                <a href="#gioi-thieu" class="nav-item-link px-2 xl:px-2.5 py-2 text-[11.5px] xl:text-[12.5px] font-semibold uppercase text-slate-700 hover:text-brand rounded">
                    Giới thiệu
                </a>

                <!-- Dropdown Công trình thực tế -->
                <div class="has-dropdown">
                    <a href="#cong-trinh-thuc-te" class="nav-item-link px-2 xl:px-2.5 py-2 text-[11.5px] xl:text-[12.5px] font-semibold uppercase text-slate-700 hover:text-brand rounded">
                        <span>Công trình thực tế</span>
                        <i class="fa-solid fa-chevron-down text-[9px] opacity-60"></i>
                    </a>
                    <div class="dropdown-menu absolute left-0 top-full pt-1 w-56 z-50">
                        <div class="bg-white rounded-lg shadow-lg border border-slate-100 py-1.5 text-xs">
                            <a href="#cong-trinh-thuc-te" onclick="filterWorks('khach-san')" class="block px-4 py-2 text-slate-700 hover:bg-brand-soft hover:text-brand font-medium">Khách sạn – Căn hộ – Phòng trọ</a>
                            <a href="#cong-trinh-thuc-te" onclick="filterWorks('biet-thu')" class="block px-4 py-2 text-slate-700 hover:bg-brand-soft hover:text-brand font-medium">Biệt thự</a>
                            <a href="#cong-trinh-thuc-te" onclick="filterWorks('nha-pho')" class="block px-4 py-2 text-slate-700 hover:bg-brand-soft hover:text-brand font-medium">Nhà phố</a>
                            <a href="#cong-trinh-thuc-te" onclick="filterWorks('van-phong')" class="block px-4 py-2 text-slate-700 hover:bg-brand-soft hover:text-brand font-medium">Văn phòng</a>
                        </div>
                    </div>
                </div>

                <!-- Dropdown Lĩnh vực hoạt động -->
                <div class="has-dropdown">
                    <a href="#dich-vu" class="nav-item-link px-2 xl:px-2.5 py-2 text-[11.5px] xl:text-[12.5px] font-semibold uppercase text-slate-700 hover:text-brand rounded">
                        <span>Lĩnh vực hoạt động</span>
                        <i class="fa-solid fa-chevron-down text-[9px] opacity-60"></i>
                    </a>
                    <div class="dropdown-menu absolute left-0 top-full pt-1 w-56 z-50">
                        <div class="bg-white rounded-lg shadow-lg border border-slate-100 py-1.5 text-xs">
                            <a href="#dich-vu" class="block px-4 py-2 text-slate-700 hover:bg-brand-soft hover:text-brand font-medium">Thiết kế Kiến trúc – Nội thất</a>
                            <a href="#dich-vu" class="block px-4 py-2 text-slate-700 hover:bg-brand-soft hover:text-brand font-medium">Thi công phần thô</a>
                            <a href="#dich-vu" class="block px-4 py-2 text-slate-700 hover:bg-brand-soft hover:text-brand font-medium">Thi công hoàn thiện</a>
                            <a href="#dich-vu" class="block px-4 py-2 text-slate-700 hover:bg-brand-soft hover:text-brand font-medium">Thi công nội thất</a>
                        </div>
                    </div>
                </div>

                <a href="#du-an-da-nang" class="nav-item-link px-2 xl:px-2.5 py-2 text-[11.5px] xl:text-[12.5px] font-semibold uppercase text-slate-700 hover:text-brand rounded">
                    Dự án Đà Nẵng
                </a>

                <!-- Dropdown Báo giá -->
                <div class="has-dropdown">
                    <a href="#bao-gia" class="nav-item-link px-2 xl:px-2.5 py-2 text-[11.5px] xl:text-[12.5px] font-semibold uppercase text-slate-700 hover:text-brand rounded">
                        <span>Báo giá</span>
                        <i class="fa-solid fa-chevron-down text-[9px] opacity-60"></i>
                    </a>
                    <div class="dropdown-menu absolute left-0 top-full pt-1 w-56 z-50">
                        <div class="bg-white rounded-lg shadow-lg border border-slate-100 py-1.5 text-xs">
                            <a href="#bao-gia" class="block px-4 py-2 text-slate-700 hover:bg-brand-soft hover:text-brand font-medium">Báo giá thiết kế kiến trúc</a>
                            <a href="#bao-gia" class="block px-4 py-2 text-slate-700 hover:bg-brand-soft hover:text-brand font-medium">Báo giá thi công phần thô</a>
                            <a href="#bao-gia" class="block px-4 py-2 text-slate-700 hover:bg-brand-soft hover:text-brand font-medium">Báo giá thi công hoàn thiện</a>
                            <a href="#bao-gia" class="block px-4 py-2 text-slate-700 hover:bg-brand-soft hover:text-brand font-medium">Báo giá thi công trọn gói</a>
                        </div>
                    </div>
                </div>

                <a href="#doi-tac" class="nav-item-link px-2 xl:px-2.5 py-2 text-[11.5px] xl:text-[12.5px] font-semibold uppercase text-slate-700 hover:text-brand rounded">
                    Đối tác
                </a>
                <a href="#bai-viet" class="nav-item-link px-2 xl:px-2.5 py-2 text-[11.5px] xl:text-[12.5px] font-semibold uppercase text-slate-700 hover:text-brand rounded">
                    Tin tức
                </a>
                <a href="#lien-he" class="nav-item-link px-2 xl:px-2.5 py-2 text-[11.5px] xl:text-[12.5px] font-semibold uppercase text-slate-700 hover:text-brand rounded">
                    Liên hệ
                </a>
            </nav>

            <!-- Nút Mở Menu Mobile (Không đặt nút Gọi ngay trên Header) -->
            <button
                id="mobile-menu-open"
                type="button"
                aria-label="Mở danh mục"
                class="lg:hidden inline-flex items-center justify-center w-10 h-10 rounded-lg border border-slate-200 text-brand hover:bg-brand-soft transition shrink-0"
            >
                <i class="fa-solid fa-bars text-lg"></i>
            </button>
        </div>
    </header>

    <!-- ========================================================= -->
    <!-- DRAWER MENU MOBILE CHUẨN FLATSOME                         -->
    <!-- ========================================================= -->
    <div id="mobile-drawer-overlay" class="fixed inset-0 bg-black/50 z-50 hidden opacity-0 transition-opacity duration-300"></div>
    <aside id="mobile-drawer" class="fixed top-0 left-0 h-full w-[280px] max-w-[85vw] bg-white z-50 shadow-2xl transform -translate-x-full transition-transform duration-300 flex flex-col">
        <div class="flex items-center justify-between px-4 py-3.5 border-b border-slate-100 bg-brand-soft">
            <div class="flex items-center gap-2">
                <img
                    src="https://drive.google.com/thumbnail?id=1uHnQ0w68nFe-QMYcDYOS5oyClevmwZkj&sz=w200"
                    data-drive-id="1uHnQ0w68nFe-QMYcDYOS5oyClevmwZkj"
                    alt="Logo Lâm Ngọc"
                    class="h-8 w-auto object-contain rounded"
                    onerror="handleDriveImageError(this, 'LAM NGOC')"
                >
                <span class="font-bold text-xs text-brand uppercase">LÂM NGỌC CONS</span>
            </div>
            <button id="mobile-menu-close" type="button" aria-label="Đóng danh mục" class="w-8 h-8 rounded-full flex items-center justify-center text-slate-600 hover:bg-white">
                <i class="fa-solid fa-xmark text-lg"></i>
            </button>
        </div>

        <nav class="flex-1 overflow-y-auto py-3 px-3 space-y-1 text-sm">
            <a href="#trang-chu" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg font-semibold text-brand bg-brand-soft/70">Trang chủ</a>
            <a href="#gioi-thieu" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg font-medium text-slate-700 hover:bg-slate-50">Giới thiệu công ty</a>

            <div class="border-t border-slate-100 pt-1">
                <button type="button" onclick="toggleMobileSub('sub-works')" class="w-full flex items-center justify-between px-3 py-2.5 rounded-lg font-medium text-slate-700 hover:bg-slate-50">
                    <span>Công trình thực tế</span>
                    <i class="fa-solid fa-chevron-down text-xs text-slate-400"></i>
                </button>
                <div id="sub-works" class="hidden pl-4 pr-2 pb-1 space-y-1 text-xs text-slate-600">
                    <a href="#cong-trinh-thuc-te" onclick="filterWorks('all'); closeMobileMenu()" class="block py-2 hover:text-brand">Tất cả công trình</a>
                    <a href="#cong-trinh-thuc-te" onclick="filterWorks('khach-san'); closeMobileMenu()" class="block py-2 hover:text-brand">Khách sạn – Căn hộ – Phòng trọ</a>
                    <a href="#cong-trinh-thuc-te" onclick="filterWorks('biet-thu'); closeMobileMenu()" class="block py-2 hover:text-brand">Biệt thự</a>
                    <a href="#cong-trinh-thuc-te" onclick="filterWorks('nha-pho'); closeMobileMenu()" class="block py-2 hover:text-brand">Nhà phố</a>
                    <a href="#cong-trinh-thuc-te" onclick="filterWorks('van-phong'); closeMobileMenu()" class="block py-2 hover:text-brand">Văn phòng</a>
                </div>
            </div>

            <div>
                <button type="button" onclick="toggleMobileSub('sub-services')" class="w-full flex items-center justify-between px-3 py-2.5 rounded-lg font-medium text-slate-700 hover:bg-slate-50">
                    <span>Lĩnh vực hoạt động</span>
                    <i class="fa-solid fa-chevron-down text-xs text-slate-400"></i>
                </button>
                <div id="sub-services" class="hidden pl-4 pr-2 pb-1 space-y-1 text-xs text-slate-600">
                    <a href="#dich-vu" onclick="closeMobileMenu()" class="block py-2 hover:text-brand">Thiết kế Kiến trúc – Nội thất</a>
                    <a href="#dich-vu" onclick="closeMobileMenu()" class="block py-2 hover:text-brand">Thi công phần thô</a>
                    <a href="#dich-vu" onclick="closeMobileMenu()" class="block py-2 hover:text-brand">Thi công hoàn thiện</a>
                    <a href="#dich-vu" onclick="closeMobileMenu()" class="block py-2 hover:text-brand">Thi công nội thất</a>
                </div>
            </div>

            <a href="#du-an-da-nang" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg font-medium text-slate-700 hover:bg-slate-50">Dự án Đà Nẵng</a>
            <a href="#bao-gia" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg font-medium text-slate-700 hover:bg-slate-50">Bảng báo giá thi công</a>
            <a href="#doi-tac" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg font-medium text-slate-700 hover:bg-slate-50">Đối tác chiến lược</a>
            <a href="#bai-viet" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg font-medium text-slate-700 hover:bg-slate-50">Tin tức & Kinh nghiệm</a>
            <a href="#lien-he" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg font-medium text-slate-700 hover:bg-slate-50">Liên hệ & Bản đồ</a>
        </nav>

        <div class="p-4 border-t border-slate-100 bg-slate-50 text-xs text-slate-600 space-y-1.5">
            <div class="font-bold text-brand">CÔNG TY TNHH XD - TM LÂM NGỌC</div>
            <div><i class="fa-solid fa-phone text-accent mr-1.5"></i>0937.533.505</div>
            <div><i class="fa-solid fa-location-dot text-accent mr-1.5"></i>Phường Ngũ Hành Sơn, TP Đà Nẵng</div>
        </div>
    </aside>

    <!-- ========================================================= -->
    <!-- MAIN CONTENT WRAPPER                                      -->
    <!-- ========================================================= -->
    <main id="trang-chu" class="w-full">

        <!-- ===================================================== -->
        <!-- SECTION 1: 2 BANNER TỰ TRƯỢT CHUYÊN NGHIỆP BẰNG NHAU  -->
        <!-- Chữ nằm gọn bên trong, cách xa viền ảnh trên mọi máy  -->
        <!-- ===================================================== -->
        <section class="w-full pt-3 pb-4 md:py-5 bg-slate-50">
            <div class="flatsome-container">
                <div
                    id="hero-slider"
                    class="relative w-full overflow-hidden rounded-xl shadow-md bg-brand-dark select-none"
                >
                    <!-- Track chứa đúng 2 slide có chiều cao hoàn toàn bằng nhau -->
                    <div id="hero-track" class="hero-slider-track">

                        <!-- BANNER 1 -->
                        <div class="hero-slide-item relative h-[300px] sm:h-[380px] md:h-[450px] lg:h-[520px] flex items-center">
                            <img
                                src="https://drive.google.com/thumbnail?id=1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR&sz=w1600"
                                data-drive-id="1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR"
                                alt="Thiết kế & Thi công xây dựng trọn gói Đà Nẵng - Lâm Ngọc"
                                class="absolute inset-0 w-full h-full object-cover object-center"
                                onerror="handleDriveImageError(this, 'XAY DUNG LAM NGOC')"
                            >
                            <!-- Lớp phủ tối tạo độ tương phản chữ sắc nét -->
                            <div class="absolute inset-0 bg-gradient-to-r from-[#062E23]/92 via-[#094233]/75 to-[#062E23]/45"></div>

                            <!-- Khung chữ đặt cách xa viền ảnh 4 phía (padding lớn) -->
                            <div class="relative z-10 w-full h-full flex items-center px-10 sm:px-14 md:px-20 lg:px-24 py-8 sm:py-10">
                                <div class="max-w-2xl text-white">
                                    <p class="text-[10px] sm:text-xs md:text-sm font-semibold uppercase tracking-[0.18em] text-amber-300 mb-2 sm:mb-3">
                                        CÔNG TY TNHH XÂY DỰNG - THƯƠNG MẠI LÂM NGỌC
                                    </p>
                                    <h1 class="text-lg sm:text-2xl md:text-3xl lg:text-4xl font-extrabold leading-snug sm:leading-tight mb-2.5 sm:mb-4">
                                        THIẾT KẾ &amp; THI CÔNG XÂY DỰNG TRỌN GÓI TẠI ĐÀ NẴNG
                                    </h1>
                                    <p class="text-[11px] sm:text-sm md:text-base text-slate-100 leading-relaxed mb-4 sm:mb-6 max-w-xl">
                                        Kiến tạo Nhà phố, Biệt thự, Căn hộ, Khách sạn chuẩn kỹ thuật – Cam kết chất lượng, tiến độ và minh bạch chi phí.
                                    </p>
                                    <div class="flex flex-wrap items-center gap-2.5 sm:gap-3">
                                        <a href="#form-bao-gia" class="inline-flex items-center gap-2 bg-accent hover:bg-accent-hover text-white font-semibold text-xs sm:text-sm px-4 sm:px-6 py-2.5 sm:py-3 rounded-lg shadow transition">
                                            <span>Nhận Báo Giá Miễn Phí</span>
                                            <i class="fa-solid fa-arrow-right text-[11px]"></i>
                                        </a>
                                        <a href="#cong-trinh-thuc-te" class="inline-flex items-center gap-2 bg-white/15 hover:bg-white/25 border border-white/40 text-white font-semibold text-xs sm:text-sm px-4 sm:px-5 py-2.5 sm:py-3 rounded-lg backdrop-blur-sm transition">
                                            <span>Xem Công Trình</span>
                                        </a>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <!-- BANNER 2 -->
                        <div class="hero-slide-item relative h-[300px] sm:h-[380px] md:h-[450px] lg:h-[520px] flex items-center">
                            <img
                                src="https://drive.google.com/thumbnail?id=1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv&sz=w1600"
                                data-drive-id="1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv"
                                alt="Thi công phần thô và hoàn thiện nội thất chuyên nghiệp - Lâm Ngọc"
                                class="absolute inset-0 w-full h-full object-cover object-center"
                                onerror="handleDriveImageError(this, 'LAM NGOC CONS')"
                            >
                            <!-- Lớp phủ tối đồng nhất kích thước và chiều sâu -->
                            <div class="absolute inset-0 bg-gradient-to-r from-[#062E23]/92 via-[#094233]/75 to-[#062E23]/45"></div>

                            <!-- Khung chữ đặt cách xa viền ảnh 4 phía -->
                            <div class="relative z-10 w-full h-full flex items-center px-10 sm:px-14 md:px-20 lg:px-24 py-8 sm:py-10">
                                <div class="max-w-2xl text-white">
                                    <p class="text-[10px] sm:text-xs md:text-sm font-semibold uppercase tracking-[0.18em] text-amber-300 mb-2 sm:mb-3">
                                        UY TÍN TẠO DỰNG NIỀM TIN • LAMNGOC.COM
                                    </p>
                                    <h2 class="text-lg sm:text-2xl md:text-3xl lg:text-4xl font-extrabold leading-snug sm:leading-tight mb-2.5 sm:mb-4">
                                        VỮNG CHẮC PHẦN THÔ – TINH TẾ HOÀN THIỆN NỘI THẤT
                                    </h2>
                                    <p class="text-[11px] sm:text-sm md:text-base text-slate-100 leading-relaxed mb-4 sm:mb-6 max-w-xl">
                                        Đội ngũ kỹ sư giám sát trực tiếp tại công trình – Vật tư chính hãng – Bảo hành kết cấu dài hạn tại khu vực Đà Nẵng.
                                    </p>
                                    <div class="flex flex-wrap items-center gap-2.5 sm:gap-3">
                                        <a href="#du-an-da-nang" class="inline-flex items-center gap-2 bg-accent hover:bg-accent-hover text-white font-semibold text-xs sm:text-sm px-4 sm:px-6 py-2.5 sm:py-3 rounded-lg shadow transition">
                                            <span>Dự Án Tại Đà Nẵng</span>
                                            <i class="fa-solid fa-arrow-right text-[11px]"></i>
                                        </a>
                                        <a href="tel:0937533505" class="inline-flex items-center gap-2 bg-white/15 hover:bg-white/25 border border-white/40 text-white font-semibold text-xs sm:text-sm px-4 sm:px-5 py-2.5 sm:py-3 rounded-lg backdrop-blur-sm transition">
                                            <i class="fa-solid fa-phone text-xs"></i>
                                            <span>0937.533.505</span>
                                        </a>
                                    </div>
                                </div>
                            </div>
                        </div>

                    </div>

                    <!-- Nút điều hướng trái / phải gọn gàng -->
                    <button
                        type="button"
                        id="slider-prev"
                        aria-label="Banner trước"
                        class="absolute left-2 sm:left-4 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/35 hover:bg-brand text-white flex items-center justify-center transition"
                    >
                        <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
                    </button>
                    <button
                        type="button"
                        id="slider-next"
                        aria-label="Banner tiếp theo"
                        class="absolute right-2 sm:right-4 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/35 hover:bg-brand text-white flex items-center justify-center transition"
                    >
                        <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
                    </button>

                    <!-- Chấm chỉ báo 2 banner -->
                    <div class="absolute bottom-3 sm:bottom-4 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                        <button type="button" class="slider-dot w-6 h-2 rounded-full bg-accent transition-all" data-slide="0" aria-label="Slide 1"></button>
                        <button type="button" class="slider-dot w-2.5 h-2 rounded-full bg-white/60 hover:bg-white transition-all" data-slide="1" aria-label="Slide 2"></button>
                    </div>
                </div>
            </div>
        </section>

        <!-- ===================================================== -->
        <!-- SECTION 2: DỊCH VỤ TIÊU BIỂU (GIỐNG MẪU FLATSOME)     -->
        <!-- ===================================================== -->
        <section id="dich-vu" class="py-10 md:py-14 bg-white">
            <div class="flatsome-container">
                <div class="text-center mb-7 md:mb-10">
                    <h2 class="text-lg sm:text-xl md:text-2xl font-extrabold text-brand uppercase tracking-wide">
                        Dịch Vụ Tiêu Biểu
                    </h2>
                    <div class="section-heading-line"></div>
                    <p class="text-xs sm:text-sm text-slate-500 mt-3 max-w-2xl mx-auto">
                        Giải pháp toàn diện từ tư vấn thiết kế, thi công phần thô đến hoàn thiện nội thất và thương mại vật liệu xây dựng.
                    </p>
                </div>

                <!-- 3 cột dịch vụ chủ lực -->
                <div class="grid grid-cols-1 md:grid-cols-3 gap-4 md:gap-6">
                    <!-- Dịch vụ 1 -->
                    <a href="#form-bao-gia" onclick="selectServiceInForm('Thiết kế Kiến trúc - Nội thất')" class="group relative rounded-xl overflow-hidden shadow-sm border border-slate-100 block bg-brand-dark">
                        <div class="img-zoom-wrap aspect-[16/10] w-full">
                            <img
                                src="https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w900"
                                data-drive-id="13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz"
                                alt="Thiết kế Kiến trúc"
                                class="w-full h-full object-cover"
                                onerror="handleDriveImageError(this, 'THIET KE')"
                            >
                            <div class="absolute inset-0 bg-gradient-to-t from-brand-dark/90 via-brand-dark/35 to-transparent"></div>
                            <div class="absolute inset-x-0 bottom-0 p-4 sm:p-5 text-white">
                                <h3 class="text-base sm:text-lg font-extrabold tracking-wide uppercase group-hover:text-amber-300 transition">
                                    THIẾT KẾ KIẾN TRÚC
                                </h3>
                                <p class="text-xs text-slate-200 mt-1">
                                    Tối ưu công năng, thẩm mỹ hiện đại cho nhà phố, biệt thự, căn hộ, khách sạn.
                                </p>
                            </div>
                        </div>
                    </a>

                    <!-- Dịch vụ 2 -->
                    <a href="#form-bao-gia" onclick="selectServiceInForm('Thi công Phần thô & Trọn gói')" class="group relative rounded-xl overflow-hidden shadow-sm border border-slate-100 block bg-brand-dark">
                        <div class="img-zoom-wrap aspect-[16/10] w-full">
                            <img
                                src="https://drive.google.com/thumbnail?id=1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t&sz=w900"
                                data-drive-id="1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t"
                                alt="Thi công xây dựng"
                                class="w-full h-full object-cover"
                                onerror="handleDriveImageError(this, 'THI CONG')"
                            >
                            <div class="absolute inset-0 bg-gradient-to-t from-brand-dark/90 via-brand-dark/35 to-transparent"></div>
                            <div class="absolute inset-x-0 bottom-0 p-4 sm:p-5 text-white">
                                <h3 class="text-base sm:text-lg font-extrabold tracking-wide uppercase group-hover:text-amber-300 transition">
                                    THI CÔNG XÂY DỰNG
                                </h3>
                                <p class="text-xs text-slate-200 mt-1">
                                    Thi công phần thô và trọn gói chuẩn kết cấu, đúng bản vẽ, không phát sinh chi phí.
                                </p>
                            </div>
                        </div>
                    </a>

                    <!-- Dịch vụ 3 -->
                    <a href="#form-bao-gia" onclick="selectServiceInForm('Hoàn thiện & Thi công Nội thất')" class="group relative rounded-xl overflow-hidden shadow-sm border border-slate-100 block bg-brand-dark">
                        <div class="img-zoom-wrap aspect-[16/10] w-full">
                            <img
                                src="https://drive.google.com/thumbnail?id=1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_&sz=w900"
                                data-drive-id="1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_"
                                alt="Hoàn thiện nội thất"
                                class="w-full h-full object-cover"
                                onerror="handleDriveImageError(this, 'NOI THAT')"
                            >
                            <div class="absolute inset-0 bg-gradient-to-t from-brand-dark/90 via-brand-dark/35 to-transparent"></div>
                            <div class="absolute inset-x-0 bottom-0 p-4 sm:p-5 text-white">
                                <h3 class="text-base sm:text-lg font-extrabold tracking-wide uppercase group-hover:text-amber-300 transition">
                                    HOÀN THIỆN &amp; NỘI THẤT
                                </h3>
                                <p class="text-xs text-slate-200 mt-1">
                                    Hoàn thiện tinh tế từng chi tiết, cung cấp vật liệu xây dựng &amp; trang thiết bị chính hãng.
                                </p>
                            </div>
                        </div>
                    </a>
                </div>
            </div>
        </section>

        <!-- ===================================================== -->
        <!-- SECTION 3: GIỚI THIỆU & THẾ MẠNH CÔNG TY LÂM NGỌC     -->
        <!-- ===================================================== -->
        <section id="gioi-thieu" class="py-10 md:py-14 bg-brand-soft/60 border-y border-slate-100">
            <div class="flatsome-container">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center mb-10">
                    <!-- Nội dung giới thiệu -->
                    <div class="lg:col-span-7">
                        <p class="text-xs font-bold uppercase tracking-widest text-accent mb-1.5">Về Chúng Tôi</p>
                        <h2 class="text-lg sm:text-xl md:text-2xl font-extrabold text-brand uppercase leading-snug mb-3">
                            CÔNG TY TNHH XÂY DỰNG - THƯƠNG MẠI LÂM NGỌC
                        </h2>
                        <p class="text-xs sm:text-sm text-slate-600 leading-relaxed mb-3">
                            <strong>Xây Dựng Lâm Ngọc (lamngoc.com)</strong> chuyên Tư vấn Thiết kế – Thi công Xây dựng – Hoàn thiện Nội thất và Thương mại vật liệu xây dựng cho các công trình Nhà phố, Biệt thự, Căn hộ cho thuê, Khách sạn, Văn phòng tại khu vực <strong>Đà Nẵng và miền Trung</strong>.
                        </p>
                        <p class="text-xs sm:text-sm text-slate-600 leading-relaxed mb-5">
                            Đặt chữ <strong>“TÂM”</strong> và chữ <strong>“TÍN”</strong> lên hàng đầu, mỗi công trình do Lâm Ngọc thực hiện luôn đảm bảo 4 tiêu chí cốt lõi: <strong>AN TOÀN – CHẤT LƯỢNG – TIẾN ĐỘ – TIẾT KIỆM CHI PHÍ</strong>. Đội ngũ kỹ sư và thợ lành nghề trực tiếp bám sát công trường giúp khách hàng hoàn toàn an tâm khi giao gửi tổ ấm.
                        </p>
                        <div class="grid grid-cols-3 gap-3 text-center">
                            <div class="bg-white rounded-lg p-3 border border-slate-100 shadow-sm">
                                <div class="text-lg sm:text-2xl font-extrabold text-brand">100%</div>
                                <div class="text-[11px] sm:text-xs text-slate-500 mt-0.5">Vật tư chuẩn cam kết</div>
                            </div>
                            <div class="bg-white rounded-lg p-3 border border-slate-100 shadow-sm">
                                <div class="text-lg sm:text-2xl font-extrabold text-accent">50+</div>
                                <div class="text-[11px] sm:text-xs text-slate-500 mt-0.5">Công trình tại Đà Nẵng</div>
                            </div>
                            <div class="bg-white rounded-lg p-3 border border-slate-100 shadow-sm">
                                <div class="text-lg sm:text-2xl font-extrabold text-brand">5 Năm</div>
                                <div class="text-[11px] sm:text-xs text-slate-500 mt-0.5">Bảo hành kết cấu</div>
                            </div>
                        </div>
                    </div>

                    <!-- Ảnh công trình đại diện -->
                    <div class="lg:col-span-5">
                        <div class="rounded-xl overflow-hidden shadow-md border border-white bg-white p-2">
                            <div class="img-zoom-wrap aspect-[4/3] rounded-lg">
                                <img
                                    src="https://drive.google.com/thumbnail?id=1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO&sz=w1000"
                                    data-drive-id="1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO"
                                    alt="Đội ngũ thi công Công ty TNHH Xây Dựng - Thương Mại Lâm Ngọc"
                                    class="w-full h-full object-cover"
                                    onerror="handleDriveImageError(this, 'LAM NGOC CONS')"
                                >
                            </div>
                        </div>
                    </div>
                </div>

                <!-- 6 Thế mạnh của chúng tôi (Cấu trúc Icon Box chuẩn Flatsome giống web mẫu) -->
                <div class="text-center mb-6">
                    <h3 class="text-base sm:text-lg md:text-xl font-extrabold text-brand uppercase">
                        Thế Mạnh Của Chúng Tôi
                    </h3>
                    <div class="section-heading-line"></div>
                </div>

                <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4">
                    <div class="bg-white rounded-xl p-4 sm:p-5 border border-slate-100 shadow-sm flex items-start gap-3.5">
                        <div class="w-10 h-10 rounded-lg bg-brand-soft text-brand flex items-center justify-center shrink-0">
                            <i class="fa-solid fa-helmet-safety text-lg"></i>
                        </div>
                        <div>
                            <h4 class="text-xs sm:text-sm font-bold text-slate-800 mb-1">Đội ngũ KTS, kỹ sư chuyên nghiệp</h4>
                            <p class="text-xs text-slate-500 leading-relaxed">Kiến trúc sư sáng tạo cùng đội ngũ kỹ sư giàu kinh nghiệm thực chiến và tổ đội thợ tay nghề cao.</p>
                        </div>
                    </div>

                    <div class="bg-white rounded-xl p-4 sm:p-5 border border-slate-100 shadow-sm flex items-start gap-3.5">
                        <div class="w-10 h-10 rounded-lg bg-brand-soft text-brand flex items-center justify-center shrink-0">
                            <i class="fa-solid fa-compass-drafting text-lg"></i>
                        </div>
                        <div>
                            <h4 class="text-xs sm:text-sm font-bold text-slate-800 mb-1">Cập nhật xu hướng thiết kế mới</h4>
                            <p class="text-xs text-slate-500 leading-relaxed">Ứng dụng giải pháp kiến trúc tối ưu ánh sáng, thông gió tự nhiên và vật liệu bền vững hiện đại.</p>
                        </div>
                    </div>

                    <div class="bg-white rounded-xl p-4 sm:p-5 border border-slate-100 shadow-sm flex items-start gap-3.5">
                        <div class="w-10 h-10 rounded-lg bg-brand-soft text-brand flex items-center justify-center shrink-0">
                            <i class="fa-solid fa-clipboard-check text-lg"></i>
                        </div>
                        <div>
                            <h4 class="text-xs sm:text-sm font-bold text-slate-800 mb-1">Giám sát tiến độ chuẩn xác</h4>
                            <p class="text-xs text-slate-500 leading-relaxed">Báo cáo tiến độ công trường minh bạch theo từng giai đoạn, đảm bảo bàn giao đúng cam kết hợp đồng.</p>
                        </div>
                    </div>

                    <div class="bg-white rounded-xl p-4 sm:p-5 border border-slate-100 shadow-sm flex items-start gap-3.5">
                        <div class="w-10 h-10 rounded-lg bg-brand-soft text-brand flex items-center justify-center shrink-0">
                            <i class="fa-solid fa-shield-halved text-lg"></i>
                        </div>
                        <div>
                            <h4 class="text-xs sm:text-sm font-bold text-slate-800 mb-1">Bảo hành công trình lâu dài</h4>
                            <p class="text-xs text-slate-500 leading-relaxed">Chế độ bảo hành kết cấu và chống thấm rõ ràng, hỗ trợ kiểm tra bảo trì nhanh chóng khi khách cần.</p>
                        </div>
                    </div>

                    <div class="bg-white rounded-xl p-4 sm:p-5 border border-slate-100 shadow-sm flex items-start gap-3.5">
                        <div class="w-10 h-10 rounded-lg bg-brand-soft text-brand flex items-center justify-center shrink-0">
                            <i class="fa-solid fa-file-invoice-dollar text-lg"></i>
                        </div>
                        <div>
                            <h4 class="text-xs sm:text-sm font-bold text-slate-800 mb-1">Chi phí hợp lý, không phát sinh</h4>
                            <p class="text-xs text-slate-500 leading-relaxed">Dự toán bóc tách rõ từng hạng mục vật tư, tối ưu ngân sách nhưng vẫn giữ vững chất lượng thi công.</p>
                        </div>
                    </div>

                    <div class="bg-white rounded-xl p-4 sm:p-5 border border-slate-100 shadow-sm flex items-start gap-3.5">
                        <div class="w-10 h-10 rounded-lg bg-brand-soft text-brand flex items-center justify-center shrink-0">
                            <i class="fa-solid fa-headset text-lg"></i>
                        </div>
                        <div>
                            <h4 class="text-xs sm:text-sm font-bold text-slate-800 mb-1">Hỗ trợ tư vấn miễn phí 24/7</h4>
                            <p class="text-xs text-slate-500 leading-relaxed">Tư vấn pháp lý giấy phép xây dựng, phong thủy và dự toán sơ bộ hoàn toàn miễn phí cho chủ đầu tư.</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- ===================================================== -->
        <!-- SECTION 4: CÔNG TRÌNH THỰC TẾ (9 ẢNH DRIVE THỰC TẾ)   -->
        <!-- Mobile 2 cột, không nhãn dán, tên hiển thị đầy đủ     -->
        <!-- ===================================================== -->
        <section id="cong-trinh-thuc-te" class="py-10 md:py-14 bg-white">
            <div class="flatsome-container">
                <div class="text-center mb-6">
                    <h2 class="text-lg sm:text-xl md:text-2xl font-extrabold text-brand uppercase tracking-wide">
                        Công Trình Thực Tế
                    </h2>
                    <div class="section-heading-line"></div>
                    <p class="text-xs sm:text-sm text-slate-500 mt-3">
                        Hình ảnh thực tế các công trình thi công xây dựng và hoàn thiện do Lâm Ngọc trực tiếp triển khai.
                    </p>
                </div>

                <!-- Thanh danh mục lọc gọn đẹp trên máy tính & điện thoại -->
                <div id="works-filter-bar" class="flex items-center justify-center flex-wrap gap-1.5 sm:gap-2 mb-6 md:mb-8">
                    <button type="button" data-filter="all" onclick="filterWorks('all')" class="work-tab-btn px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11px] sm:text-xs font-semibold whitespace-nowrap bg-brand text-white transition">
                        Tất cả
                    </button>
                    <button type="button" data-filter="khach-san" onclick="filterWorks('khach-san')" class="work-tab-btn px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11px] sm:text-xs font-semibold whitespace-nowrap bg-slate-100 text-slate-700 hover:bg-brand-soft hover:text-brand transition">
                        Khách sạn - Căn hộ
                    </button>
                    <button type="button" data-filter="biet-thu" onclick="filterWorks('biet-thu')" class="work-tab-btn px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11px] sm:text-xs font-semibold whitespace-nowrap bg-slate-100 text-slate-700 hover:bg-brand-soft hover:text-brand transition">
                        Biệt thự
                    </button>
                    <button type="button" data-filter="nha-pho" onclick="filterWorks('nha-pho')" class="work-tab-btn px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11px] sm:text-xs font-semibold whitespace-nowrap bg-slate-100 text-slate-700 hover:bg-brand-soft hover:text-brand transition">
                        Nhà phố
                    </button>
                    <button type="button" data-filter="van-phong" onclick="filterWorks('van-phong')" class="work-tab-btn px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11px] sm:text-xs font-semibold whitespace-nowrap bg-slate-100 text-slate-700 hover:bg-brand-soft hover:text-brand transition">
                        Văn phòng
                    </button>
                </div>

                <!-- Lưới 9 ảnh thực tế thi công: 2 cột trên điện thoại, 3 cột trên máy tính -->
                <div id="works-grid" class="grid grid-cols-2 md:grid-cols-3 gap-3 sm:gap-4 md:gap-5">
                    <!-- Được render tự động bằng JS từ dữ liệu thực tế chuẩn -->
                </div>
            </div>
        </section>

        <!-- ===================================================== -->
        <!-- SECTION 5: CÁC DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG (10 ẢNH)   -->
        <!-- Mobile 2 cột, không nhãn dán, tên không bị thiếu chữ  -->
        <!-- ===================================================== -->
        <section id="du-an-da-nang" class="py-10 md:py-14 bg-slate-50 border-y border-slate-100">
            <div class="flatsome-container">
                <div class="text-center mb-7 md:mb-9">
                    <h2 class="text-lg sm:text-xl md:text-2xl font-extrabold text-brand uppercase tracking-wide">
                        Các Dự Án Tại Đà Nẵng
                    </h2>
                    <div class="section-heading-line"></div>
                    <p class="text-xs sm:text-sm text-slate-500 mt-3 max-w-2xl mx-auto">
                        Tổng hợp các công trình nhà ở, biệt thự, căn hộ và dự án xây dựng Lâm Ngọc đã thực hiện trên địa bàn TP. Đà Nẵng.
                    </p>
                </div>

                <!-- Lưới 10 ảnh dự án Đà Nẵng: 2 cột mobile, 4 cột desktop -->
                <div id="danang-projects-grid" class="grid grid-cols-2 md:grid-cols-4 lg:grid-cols-5 gap-3 sm:gap-4">
                    <!-- Được render tự động bằng JS -->
                </div>
            </div>
        </section>

        <!-- ===================================================== -->
        <!-- SECTION 6: BÁO GIÁ DỊCH VỤ (CHUẨN DANH MỤC WEB MẪU)   -->
        <!-- ===================================================== -->
        <section id="bao-gia" class="py-10 md:py-14 bg-white">
            <div class="flatsome-container">
                <div class="text-center mb-7 md:mb-9">
                    <h2 class="text-lg sm:text-xl md:text-2xl font-extrabold text-brand uppercase tracking-wide">
                        Báo Giá Thiết Kế &amp; Thi Công
                    </h2>
                    <div class="section-heading-line"></div>
                    <p class="text-xs sm:text-sm text-slate-500 mt-3">
                        Đơn giá tham khảo minh bạch, tối ưu chi phí theo nhu cầu thực tế của từng công trình.
                    </p>
                </div>

                <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-4 md:gap-5">
                    <!-- Gói 1 -->
                    <div class="rounded-xl border border-slate-200 bg-white p-3.5 sm:p-5 flex flex-col justify-between hover:border-brand hover:shadow-md transition">
                        <div>
                            <h3 class="text-xs sm:text-sm font-bold text-brand uppercase leading-snug mb-2">
                                Thiết Kế Kiến Trúc &amp; Nội Thất
                            </h3>
                            <div class="text-base sm:text-xl font-extrabold text-accent mb-3">
                                Từ 150.000đ<span class="text-[11px] font-medium text-slate-500">/m²</span>
                            </div>
                            <ul class="space-y-1.5 text-[11px] sm:text-xs text-slate-600 mb-4">
                                <li class="flex items-start gap-1.5"><i class="fa-solid fa-check text-brand mt-0.5"></i><span>Hồ sơ 3D mặt tiền &amp; nội thất</span></li>
                                <li class="flex items-start gap-1.5"><i class="fa-solid fa-check text-brand mt-0.5"></i><span>Bản vẽ kết cấu, điện nước MEP</span></li>
                                <li class="flex items-start gap-1.5"><i class="fa-solid fa-check text-brand mt-0.5"></i><span>Giảm phí khi thi công trọn gói</span></li>
                            </ul>
                        </div>
                        <a href="#form-bao-gia" onclick="selectServiceInForm('Báo giá thiết kế kiến trúc')" class="w-full text-center py-2 px-3 rounded-lg bg-brand-soft text-brand hover:bg-brand hover:text-white text-xs font-semibold transition">
                            Nhận báo giá
                        </a>
                    </div>

                    <!-- Gói 2 -->
                    <div class="rounded-xl border border-slate-200 bg-white p-3.5 sm:p-5 flex flex-col justify-between hover:border-brand hover:shadow-md transition">
                        <div>
                            <h3 class="text-xs sm:text-sm font-bold text-brand uppercase leading-snug mb-2">
                                Thi Công Phần Thô &amp; Nhân Công
                            </h3>
                            <div class="text-base sm:text-xl font-extrabold text-accent mb-3">
                                Từ 3.550.000đ<span class="text-[11px] font-medium text-slate-500">/m²</span>
                            </div>
                            <ul class="space-y-1.5 text-[11px] sm:text-xs text-slate-600 mb-4">
                                <li class="flex items-start gap-1.5"><i class="fa-solid fa-check text-brand mt-0.5"></i><span>Thép Hòa Phát / Việt Nhật chuẩn</span></li>
                                <li class="flex items-start gap-1.5"><i class="fa-solid fa-check text-brand mt-0.5"></i><span>Xi măng Sông Gianh, bê tông tươi</span></li>
                                <li class="flex items-start gap-1.5"><i class="fa-solid fa-check text-brand mt-0.5"></i><span>Kỹ sư giám sát thường trực</span></li>
                            </ul>
                        </div>
                        <a href="#form-bao-gia" onclick="selectServiceInForm('Báo giá thi công phần thô')" class="w-full text-center py-2 px-3 rounded-lg bg-brand-soft text-brand hover:bg-brand hover:text-white text-xs font-semibold transition">
                            Nhận báo giá
                        </a>
                    </div>

                    <!-- Gói 3 -->
                    <div class="rounded-xl border border-slate-200 bg-white p-3.5 sm:p-5 flex flex-col justify-between hover:border-brand hover:shadow-md transition">
                        <div>
                            <h3 class="text-xs sm:text-sm font-bold text-brand uppercase leading-snug mb-2">
                                Thi Công Hoàn Thiện Công Trình
                            </h3>
                            <div class="text-base sm:text-xl font-extrabold text-accent mb-3">
                                Từ 2.400.000đ<span class="text-[11px] font-medium text-slate-500">/m²</span>
                            </div>
                            <ul class="space-y-1.5 text-[11px] sm:text-xs text-slate-600 mb-4">
                                <li class="flex items-start gap-1.5"><i class="fa-solid fa-check text-brand mt-0.5"></i><span>Ốp lát gạch, sơn nước Dulux/Jotun</span></li>
                                <li class="flex items-start gap-1.5"><i class="fa-solid fa-check text-brand mt-0.5"></i><span>Cửa nhôm Xingfa, trần thạch cao</span></li>
                                <li class="flex items-start gap-1.5"><i class="fa-solid fa-check text-brand mt-0.5"></i><span>Thiết bị điện &amp; vệ sinh chính hãng</span></li>
                            </ul>
                        </div>
                        <a href="#form-bao-gia" onclick="selectServiceInForm('Báo giá thi công hoàn thiện')" class="w-full text-center py-2 px-3 rounded-lg bg-brand-soft text-brand hover:bg-brand hover:text-white text-xs font-semibold transition">
                            Nhận báo giá
                        </a>
                    </div>

                    <!-- Gói 4 -->
                    <div class="rounded-xl border-2 border-brand bg-brand-soft/40 p-3.5 sm:p-5 flex flex-col justify-between shadow-sm">
                        <div>
                            <h3 class="text-xs sm:text-sm font-bold text-brand uppercase leading-snug mb-2">
                                Xây Nhà Trọn Gói Chìa Khóa Trao Tay
                            </h3>
                            <div class="text-base sm:text-xl font-extrabold text-accent mb-3">
                                Từ 5.800.000đ<span class="text-[11px] font-medium text-slate-500">/m²</span>
                            </div>
                            <ul class="space-y-1.5 text-[11px] sm:text-xs text-slate-600 mb-4">
                                <li class="flex items-start gap-1.5"><i class="fa-solid fa-check text-brand mt-0.5"></i><span>Miễn phí xin giấy phép xây dựng</span></li>
                                <li class="flex items-start gap-1.5"><i class="fa-solid fa-check text-brand mt-0.5"></i><span>Cam kết không phát sinh chi phí</span></li>
                                <li class="flex items-start gap-1.5"><i class="fa-solid fa-check text-brand mt-0.5"></i><span>Bảo hành kết cấu lên đến 5 năm</span></li>
                            </ul>
                        </div>
                        <a href="#form-bao-gia" onclick="selectServiceInForm('Báo giá thi công trọn gói')" class="w-full text-center py-2 px-3 rounded-lg bg-brand text-white hover:bg-brand-dark text-xs font-semibold transition">
                            Đăng ký tư vấn ngay
                        </a>
                    </div>
                </div>
            </div>
        </section>

        <!-- ===================================================== -->
        <!-- SECTION 7: DANH MỤC CÁC ĐỐI TÁC                       -->
        <!-- ===================================================== -->
        <section id="doi-tac" class="py-10 md:py-12 bg-slate-50 border-y border-slate-100">
            <div class="flatsome-container">
                <div class="text-center mb-7">
                    <h2 class="text-lg sm:text-xl md:text-2xl font-extrabold text-brand uppercase tracking-wide">
                        Đối Tác Cung Ứng &amp; Đồng Hành
                    </h2>
                    <div class="section-heading-line"></div>
                    <p class="text-xs sm:text-sm text-slate-500 mt-3">
                        Hợp tác cùng các thương hiệu vật liệu xây dựng và thiết bị uy tín hàng đầu Việt Nam.
                    </p>
                </div>

                <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-5 gap-3 sm:gap-4">
                    <!-- Đối tác 1 -->
                    <div class="bg-white rounded-xl border border-slate-200/80 p-4 flex flex-col items-center justify-center text-center hover:border-brand hover:shadow-sm transition">
                        <div class="text-sm sm:text-base font-extrabold tracking-tight text-[#004A99]">HÒA PHÁT</div>
                        <div class="text-[10px] text-slate-500 mt-0.5">Thép xây dựng</div>
                    </div>
                    <!-- Đối tác 2 -->
                    <div class="bg-white rounded-xl border border-slate-200/80 p-4 flex flex-col items-center justify-center text-center hover:border-brand hover:shadow-sm transition">
                        <div class="text-sm sm:text-base font-extrabold tracking-tight text-[#0B6E4F]">SÔNG GIANH</div>
                        <div class="text-[10px] text-slate-500 mt-0.5">Xi măng cao cấp</div>
                    </div>
                    <!-- Đối tác 3 -->
                    <div class="bg-white rounded-xl border border-slate-200/80 p-4 flex flex-col items-center justify-center text-center hover:border-brand hover:shadow-sm transition">
                        <div class="text-sm sm:text-base font-extrabold tracking-tight text-[#C8102E]">DULUX</div>
                        <div class="text-[10px] text-slate-500 mt-0.5">Sơn nội ngoại thất</div>
                    </div>
                    <!-- Đối tác 4 -->
                    <div class="bg-white rounded-xl border border-slate-200/80 p-4 flex flex-col items-center justify-center text-center hover:border-brand hover:shadow-sm transition">
                        <div class="text-sm sm:text-base font-extrabold tracking-tight text-[#00338D]">JOTUN</div>
                        <div class="text-[10px] text-slate-500 mt-0.5">Sơn chống thấm</div>
                    </div>
                    <!-- Đối tác 5 -->
                    <div class="bg-white rounded-xl border border-slate-200/80 p-4 flex flex-col items-center justify-center text-center hover:border-brand hover:shadow-sm transition">
                        <div class="text-sm sm:text-base font-extrabold tracking-tight text-[#B91C1C]">CADIVI</div>
                        <div class="text-[10px] text-slate-500 mt-0.5">Dây cáp điện</div>
                    </div>
                    <!-- Đối tác 6 -->
                    <div class="bg-white rounded-xl border border-slate-200/80 p-4 flex flex-col items-center justify-center text-center hover:border-brand hover:shadow-sm transition">
                        <div class="text-sm sm:text-base font-extrabold tracking-tight text-[#0369A1]">BÌNH MINH</div>
                        <div class="text-[10px] text-slate-500 mt-0.5">Ống nhựa cấp thoát nước</div>
                    </div>
                    <!-- Đối tác 7 -->
                    <div class="bg-white rounded-xl border border-slate-200/80 p-4 flex flex-col items-center justify-center text-center hover:border-brand hover:shadow-sm transition">
                        <div class="text-sm sm:text-base font-extrabold tracking-tight text-[#1E3A8A]">VIGLACERA</div>
                        <div class="text-[10px] text-slate-500 mt-0.5">Gạch ốp lát &amp; sứ</div>
                    </div>
                    <!-- Đối tác 8 -->
                    <div class="bg-white rounded-xl border border-slate-200/80 p-4 flex flex-col items-center justify-center text-center hover:border-brand hover:shadow-sm transition">
                        <div class="text-sm sm:text-base font-extrabold tracking-tight text-[#0F172A]">TOTO</div>
                        <div class="text-[10px] text-slate-500 mt-0.5">Thiết bị vệ sinh</div>
                    </div>
                    <!-- Đối tác 9 -->
                    <div class="bg-white rounded-xl border border-slate-200/80 p-4 flex flex-col items-center justify-center text-center hover:border-brand hover:shadow-sm transition">
                        <div class="text-sm sm:text-base font-extrabold tracking-tight text-[#78350F]">AN CƯỜNG</div>
                        <div class="text-[10px] text-slate-500 mt-0.5">Gỗ nội thất công nghiệp</div>
                    </div>
                    <!-- Đối tác 10 -->
                    <div class="bg-white rounded-xl border border-slate-200/80 p-4 flex flex-col items-center justify-center text-center hover:border-brand hover:shadow-sm transition">
                        <div class="text-sm sm:text-base font-extrabold tracking-tight text-[#B45309]">XINGFA</div>
                        <div class="text-[10px] text-slate-500 mt-0.5">Hệ cửa nhôm kính</div>
                    </div>
                </div>
            </div>
        </section>

        <!-- ===================================================== -->
        <!-- SECTION 8: FORM YÊU CẦU & BÁO GIÁ MIỄN PHÍ TRANG CHỦ  -->
        <!-- ===================================================== -->
        <section id="form-bao-gia" class="py-10 md:py-14 bg-brand text-white relative overflow-hidden">
            <div class="flatsome-container relative z-10">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center">
                    <div class="lg:col-span-5 space-y-3">
                        <p class="text-xs font-bold uppercase tracking-widest text-amber-300">Tư Vấn Trực Tiếp</p>
                        <h2 class="text-xl sm:text-2xl md:text-3xl font-extrabold leading-snug uppercase">
                            Đăng Ký Nhận Tư Vấn &amp; Báo Giá Miễn Phí
                        </h2>
                        <p class="text-xs sm:text-sm text-emerald-100 leading-relaxed">
                            Để lại thông tin công trình dự kiến, kỹ sư trưởng của <strong>Xây Dựng Lâm Ngọc</strong> sẽ liên hệ khảo sát thực tế và gửi bảng dự toán chi tiết trong vòng 24 giờ.
                        </p>
                        <div class="pt-2 space-y-2 text-xs sm:text-sm">
                            <div class="flex items-center gap-2.5">
                                <span class="w-8 h-8 rounded-full bg-white/15 flex items-center justify-center shrink-0">
                                    <i class="fa-solid fa-phone text-amber-300 text-xs"></i>
                                </span>
                                <span>Hotline/Zalo: <strong class="text-amber-300">0937.533.505</strong></span>
                            </div>
                            <div class="flex items-center gap-2.5">
                                <span class="w-8 h-8 rounded-full bg-white/15 flex items-center justify-center shrink-0">
                                    <i class="fa-solid fa-location-dot text-amber-300 text-xs"></i>
                                </span>
                                <span>Thửa đất số 151, tờ bản đồ 82, Phường Ngũ Hành Sơn, TP Đà Nẵng</span>
                            </div>
                        </div>
                    </div>

                    <div class="lg:col-span-7">
                        <form id="quote-form" class="bg-white text-slate-800 rounded-xl p-5 sm:p-6 md:p-7 shadow-xl space-y-4">
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
                                <div>
                                    <label for="q-name" class="block text-xs font-semibold text-slate-700 mb-1">Họ và tên *</label>
                                    <input id="q-name" name="name" type="text" required placeholder="Nhập họ tên của bạn" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-200 text-xs sm:text-sm focus:outline-none focus:border-brand focus:ring-2 focus:ring-brand/15">
                                </div>
                                <div>
                                    <label for="q-phone" class="block text-xs font-semibold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                                    <input id="q-phone" name="phone" type="tel" required placeholder="Ví dụ: 0937.533.505" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-200 text-xs sm:text-sm focus:outline-none focus:border-brand focus:ring-2 focus:ring-brand/15">
                                </div>
                                <div>
                                    <label for="q-type" class="block text-xs font-semibold text-slate-700 mb-1">Loại công trình / Dịch vụ</label>
                                    <select id="q-type" name="type" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-200 text-xs sm:text-sm bg-white focus:outline-none focus:border-brand focus:ring-2 focus:ring-brand/15">
                                        <option value="Nhà phố">Nhà phố</option>
                                        <option value="Biệt thự">Biệt thự</option>
                                        <option value="Khách sạn - Căn hộ cho thuê - Phòng trọ">Khách sạn – Căn hộ cho thuê – Phòng trọ</option>
                                        <option value="Văn phòng - Showroom">Văn phòng – Showroom</option>
                                        <option value="Cải tạo sửa chữa">Cải tạo sửa chữa</option>
                                        <option value="Báo giá thiết kế kiến trúc">Báo giá thiết kế kiến trúc</option>
                                        <option value="Báo giá thi công phần thô">Báo giá thi công phần thô</option>
                                        <option value="Báo giá thi công hoàn thiện">Báo giá thi công hoàn thiện</option>
                                        <option value="Báo giá thi công trọn gói">Báo giá thi công trọn gói</option>
                                    </select>
                                </div>
                                <div>
                                    <label for="q-budget" class="block text-xs font-semibold text-slate-700 mb-1">Mức đầu tư dự kiến</label>
                                    <select id="q-budget" name="budget" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-200 text-xs sm:text-sm bg-white focus:outline-none focus:border-brand focus:ring-2 focus:ring-brand/15">
                                        <option value="Chưa xác định">Chưa xác định</option>
                                        <option value="Dưới 500 triệu">Dưới 500 triệu</option>
                                        <option value="500 triệu - 1 tỷ">500 triệu – 1 tỷ</option>
                                        <option value="1 tỷ - 2 tỷ">1 tỷ – 2 tỷ</option>
                                        <option value="2 tỷ - 3 tỷ">2 tỷ – 3 tỷ</option>
                                        <option value="Trên 3 tỷ">Trên 3 tỷ</option>
                                    </select>
                                </div>
                            </div>

                            <div>
                                <label for="q-note" class="block text-xs font-semibold text-slate-700 mb-1">Diện tích đất &amp; Yêu cầu chi tiết</label>
                                <textarea id="q-note" name="note" rows="3" placeholder="Ví dụ: Diện tích 5x20m tại Ngũ Hành Sơn, xây nhà 3 tầng trọn gói..." class="w-full px-3.5 py-2.5 rounded-lg border border-slate-200 text-xs sm:text-sm focus:outline-none focus:border-brand focus:ring-2 focus:ring-brand/15"></textarea>
                            </div>

                            <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-3 pt-1">
                                <p class="text-[11px] text-slate-500">
                                    <i class="fa-solid fa-lock text-brand mr-1"></i>Thông tin của Quý khách được bảo mật tuyệt đối.
                                </p>
                                <button type="submit" class="inline-flex items-center justify-center gap-2 bg-accent hover:bg-accent-hover text-white font-bold text-xs sm:text-sm px-6 py-3 rounded-lg shadow transition">
                                    <i class="fa-solid fa-paper-plane text-xs"></i>
                                    <span>Gửi Yêu Cầu Báo Giá</span>
                                </button>
                            </div>
                        </form>
                    </div>
                </div>
            </div>
        </section>

        <!-- ===================================================== -->
        <!-- SECTION 9: DANH MỤC CÁC BÀI VIẾT / TIN TỨC TRANG CHỦ  -->
        <!-- ===================================================== -->
        <section id="bai-viet" class="py-10 md:py-14 bg-white">
            <div class="flatsome-container">
                <div class="text-center mb-7 md:mb-9">
                    <h2 class="text-lg sm:text-xl md:text-2xl font-extrabold text-brand uppercase tracking-wide">
                        Tin Tức &amp; Kinh Nghiệm Xây Dựng
                    </h2>
                    <div class="section-heading-line"></div>
                    <p class="text-xs sm:text-sm text-slate-500 mt-3">
                        Cẩm nang xây nhà, quy trình kỹ thuật và các chia sẻ hữu ích từ đội ngũ kỹ sư Lâm Ngọc.
                    </p>
                </div>

                <!-- 2 cột mobile, 4 cột desktop -->
                <div id="articles-grid" class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-4 md:gap-5">
                    <!-- Render tự động bằng JS -->
                </div>
            </div>
        </section>

        <!-- ===================================================== -->
        <!-- SECTION 10: FANPAGE FACEBOOK & GOOGLE MAP TRANG CHỦ   -->
        <!-- ===================================================== -->
        <section id="lien-he" class="py-10 md:py-14 bg-slate-50 border-t border-slate-100">
            <div class="flatsome-container">
                <div class="text-center mb-7 md:mb-9">
                    <h2 class="text-lg sm:text-xl md:text-2xl font-extrabold text-brand uppercase tracking-wide">
                        Kết Nối Fanpage &amp; Bản Đồ Chỉ Đường
                    </h2>
                    <div class="section-heading-line"></div>
                </div>

                <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 md:gap-6 items-stretch">
                    <!-- Cột trái: Fanpage Facebook chính thức ngoài trang chủ -->
                    <div class="lg:col-span-5 bg-white rounded-xl border border-slate-200 shadow-sm p-4 sm:p-5 flex flex-col justify-between">
                        <div>
                            <div class="flex items-center gap-3 pb-3 mb-3 border-b border-slate-100">
                                <img
                                    src="https://drive.google.com/thumbnail?id=1uHnQ0w68nFe-QMYcDYOS5oyClevmwZkj&sz=w200"
                                    data-drive-id="1uHnQ0w68nFe-QMYcDYOS5oyClevmwZkj"
                                    alt="Avatar Fanpage Xây Dựng Lâm Ngọc"
                                    class="w-11 h-11 rounded-lg object-contain border border-slate-100 p-0.5 bg-white shrink-0"
                                    onerror="handleDriveImageError(this, 'LN')"
                                >
                                <div class="min-w-0">
                                    <h3 class="text-sm font-bold text-slate-800 leading-snug">
                                        Xây Dựng Lâm Ngọc - Đà Nẵng
                                    </h3>
                                    <a href="https://www.facebook.com/xay.dung.lam.ngoc" target="_blank" rel="noopener noreferrer" class="text-xs text-[#1877F2] hover:underline break-all">
                                        facebook.com/xay.dung.lam.ngoc
                                    </a>
                                </div>
                            </div>

                            <!-- Nhúng Facebook Page Plugin chuẩn -->
                            <div class="w-full overflow-hidden rounded-lg border border-slate-100 bg-slate-50">
                                <iframe
                                    title="Fanpage Công Ty TNHH Xây Dựng - Thương Mại Lâm Ngọc"
                                    src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fxay.dung.lam.ngoc&tabs=timeline&width=480&height=310&small_header=false&adapt_container_width=true&hide_cover=false&show_facepile=true"
                                    class="w-full h-[310px] border-0"
                                    scrolling="no"
                                    frameborder="0"
                                    allowfullscreen="true"
                                    allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share"
                                    loading="lazy"
                                ></iframe>
                            </div>
                        </div>

                        <div class="mt-4 flex flex-wrap items-center justify-between gap-2 pt-3 border-t border-slate-100">
                            <span class="text-xs text-slate-500">Cập nhật tiến độ công trình mỗi ngày</span>
                            <a href="https://www.facebook.com/xay.dung.lam.ngoc" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-2 bg-[#1877F2] hover:bg-[#145DBF] text-white text-xs font-semibold px-4 py-2 rounded-lg transition">
                                <i class="fa-brands fa-facebook"></i>
                                <span>Truy cập Fanpage</span>
                            </a>
                        </div>
                    </div>

                    <!-- Cột phải: Bản đồ Google Map thực tế ngoài trang chủ -->
                    <div class="lg:col-span-7 bg-white rounded-xl border border-slate-200 shadow-sm p-4 sm:p-5 flex flex-col justify-between">
                        <div>
                            <div class="flex flex-wrap items-center justify-between gap-2 pb-3 mb-3 border-b border-slate-100">
                                <div>
                                    <h3 class="text-sm font-bold text-brand uppercase">
                                        Trụ Sở Công Ty TNHH Xây Dựng - Thương Mại Lâm Ngọc
                                    </h3>
                                    <p class="text-xs text-slate-600 mt-0.5">
                                        <i class="fa-solid fa-location-dot text-accent mr-1"></i>
                                        Thửa đất số 151, tờ bản đồ 82, Phường Ngũ Hành Sơn, TP Đà Nẵng
                                    </p>
                                </div>
                                <a
                                    href="https://www.google.com/maps/search/?api=1&query=Ph%C6%B0%E1%BB%9Dng+Ng%C5%A9+H%C3%A0nh+S%C6%A1n,+%C4%90%C3%A0+N%E1%BA%B5ng"
                                    target="_blank"
                                    rel="noopener noreferrer"
                                    class="inline-flex items-center gap-1.5 text-xs font-semibold text-brand hover:text-accent transition"
                                >
                                    <i class="fa-solid fa-diamond-turn-right"></i>
                                    <span>Mở Google Maps</span>
                                </a>
                            </div>

                            <!-- Nhúng Google Map tương tác -->
                            <div class="w-full overflow-hidden rounded-lg border border-slate-200">
                                <iframe
                                    title="Bản đồ Google Map Công ty TNHH Xây Dựng - Thương Mại Lâm Ngọc Đà Nẵng"
                                    src="https://maps.google.com/maps?q=Ph%C6%B0%E1%BB%9Dng+Ng%C5%A9+H%C3%A0nh+S%C6%A1n,+%C4%90%C3%A0+N%E1%BA%B5ng,+Vietnam&t=&z=14&ie=UTF8&iwloc=&output=embed"
                                    class="w-full h-[310px] sm:h-[330px] border-0"
                                    allowfullscreen=""
                                    loading="lazy"
                                    referrerpolicy="no-referrer-when-downgrade"
                                ></iframe>
                            </div>
                        </div>

                        <div class="mt-3 pt-3 border-t border-slate-100 flex flex-wrap items-center justify-between gap-2 text-xs text-slate-600">
                            <span><i class="fa-regular fa-clock text-brand mr-1"></i>Giờ làm việc: Thứ 2 – Thứ 7 (07:30 – 17:30)</span>
                            <a href="tel:0937533505" class="font-bold text-brand hover:text-accent">
                                <i class="fa-solid fa-phone mr-1"></i>Hotline: 0937.533.505
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </section>

    </main>

    <!-- ========================================================= -->
    <!-- FOOTER CHUẨN FLATSOME                                     -->
    <!-- ========================================================= -->
    <footer class="bg-[#083529] text-slate-200 pt-10 pb-20 md:pb-8">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-7 pb-8 border-b border-white/10">
                <!-- Cột 1: Thông tin doanh nghiệp -->
                <div class="lg:col-span-5 space-y-3">
                    <div class="flex items-center gap-2.5">
                        <img
                            src="https://drive.google.com/thumbnail?id=1uHnQ0w68nFe-QMYcDYOS5oyClevmwZkj&sz=w300"
                            data-drive-id="1uHnQ0w68nFe-QMYcDYOS5oyClevmwZkj"
                            alt="Logo Xây Dựng Lâm Ngọc"
                            class="h-11 w-auto object-contain bg-white rounded p-1"
                            onerror="handleDriveImageError(this, 'LAM NGOC')"
                        >
                        <div>
                            <div class="text-sm font-extrabold text-white uppercase leading-snug">
                                CÔNG TY TNHH XÂY DỰNG - THƯƠNG MẠI LÂM NGỌC
                            </div>
                            <div class="text-[11px] text-amber-300 font-medium">LAM NGOC CONS CO.,LTD</div>
                        </div>
                    </div>
                    <ul class="space-y-2 text-xs text-slate-300 pt-1">
                        <li class="flex items-start gap-2">
                            <i class="fa-solid fa-location-dot text-accent mt-0.5 shrink-0"></i>
                            <span><strong>Địa chỉ:</strong> Thửa đất số 151, tờ bản đồ 82, Phường Ngũ Hành Sơn, TP Đà Nẵng</span>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-solid fa-phone text-accent shrink-0"></i>
                            <span><strong>Hotline / Zalo:</strong> <a href="tel:0937533505" class="text-white font-semibold hover:text-amber-300">0937.533.505</a></span>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-solid fa-globe text-accent shrink-0"></i>
                            <span><strong>Website:</strong> <a href="https://lamngoc.com" class="hover:text-amber-300">lamngoc.com</a></span>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-brands fa-facebook text-accent shrink-0"></i>
                            <span><strong>Fanpage:</strong> <a href="https://www.facebook.com/xay.dung.lam.ngoc" target="_blank" rel="noopener noreferrer" class="hover:text-amber-300">facebook.com/xay.dung.lam.ngoc</a></span>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-solid fa-building-shield text-accent shrink-0"></i>
                            <span><strong>Mã số thuế:</strong> 0402078817</span>
                        </li>
                    </ul>
                </div>

                <!-- Cột 2: Lĩnh vực hoạt động -->
                <div class="lg:col-span-3">
                    <h4 class="text-xs sm:text-sm font-bold text-white uppercase tracking-wide mb-3 pb-2 border-b border-white/15">
                        Lĩnh Vực Hoạt Động
                    </h4>
                    <ul class="space-y-2 text-xs text-slate-300">
                        <li><a href="#dich-vu" class="hover:text-amber-300 transition">Thiết kế Kiến trúc – Nội thất</a></li>
                        <li><a href="#dich-vu" class="hover:text-amber-300 transition">Thi công xây dựng phần thô</a></li>
                        <li><a href="#dich-vu" class="hover:text-amber-300 transition">Thi công hoàn thiện công trình</a></li>
                        <li><a href="#dich-vu" class="hover:text-amber-300 transition">Xây nhà trọn gói Đà Nẵng</a></li>
                        <li><a href="#dich-vu" class="hover:text-amber-300 transition">Cải tạo, sửa chữa nhà ở &amp; văn phòng</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Danh mục nhanh -->
                <div class="lg:col-span-4">
                    <h4 class="text-xs sm:text-sm font-bold text-white uppercase tracking-wide mb-3 pb-2 border-b border-white/15">
                        Danh Mục Nổi Bật
                    </h4>
                    <div class="grid grid-cols-2 gap-2 text-xs text-slate-300">
                        <a href="#cong-trinh-thuc-te" class="hover:text-amber-300 transition">Công trình thực tế</a>
                        <a href="#du-an-da-nang" class="hover:text-amber-300 transition">Dự án Đà Nẵng</a>
                        <a href="#bao-gia" class="hover:text-amber-300 transition">Bảng giá thi công</a>
                        <a href="#doi-tac" class="hover:text-amber-300 transition">Đối tác cung ứng</a>
                        <a href="#bai-viet" class="hover:text-amber-300 transition">Tin tức xây dựng</a>
                        <a href="#form-bao-gia" class="hover:text-amber-300 transition">Yêu cầu báo giá</a>
                    </div>
                </div>
            </div>

            <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-[11px] sm:text-xs text-slate-400">
                <div>Copyright 2026 © <strong class="text-slate-200">CÔNG TY TNHH XÂY DỰNG - THƯƠNG MẠI LÂM NGỌC</strong> (lamngoc.com)</div>
                <div>Thiết kế chuẩn giao diện Flatsome tối ưu đa thiết bị</div>
            </div>
        </div>
    </footer>

    <!-- ========================================================= -->
    <!-- CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE)         -->
    <!-- Tương thích hoàn hảo trên máy tính & điện thoại           -->
    <!-- ========================================================= -->

    <!-- Cụm nút nổi cho Máy Tính & Tablet (góc dưới phải gọn gàng) -->
    <div class="hidden md:flex fixed right-4 bottom-6 z-40 flex-col items-end gap-2.5">
        <!-- Facebook Messenger / Fanpage -->
        <a
            href="https://www.facebook.com/xay.dung.lam.ngoc"
            target="_blank"
            rel="noopener noreferrer"
            aria-label="Liên hệ Facebook Xây Dựng Lâm Ngọc"
            class="group flex items-center gap-2 bg-[#1877F2] hover:bg-[#145DBF] text-white px-3.5 py-2.5 rounded-full shadow-lg transition-all"
        >
            <i class="fa-brands fa-facebook-f text-sm w-4 text-center"></i>
            <span class="text-xs font-bold whitespace-nowrap">Facebook</span>
        </a>

        <!-- Zalo -->
        <a
            href="https://zalo.me/0937533505"
            target="_blank"
            rel="noopener noreferrer"
            aria-label="Chat Zalo Xây Dựng Lâm Ngọc"
            class="group flex items-center gap-2 bg-[#0068FF] hover:bg-[#0052CC] text-white px-3.5 py-2.5 rounded-full shadow-lg transition-all"
        >
            <span class="font-extrabold text-xs tracking-tight bg-white text-[#0068FF] rounded-full px-1.5 py-0.5 leading-none">Zalo</span>
            <span class="text-xs font-bold whitespace-nowrap">Chat Zalo</span>
        </a>

        <!-- Hotline nổi bật có hiệu ứng vòng sáng -->
        <a
            href="tel:0937533505"
            aria-label="Gọi Hotline 0937.533.505"
            class="hotline-pulse flex items-center gap-2 bg-red-600 hover:bg-red-700 text-white px-4 py-2.5 rounded-full shadow-xl transition-all"
        >
            <i class="fa-solid fa-phone-volume text-sm"></i>
            <span class="text-xs font-extrabold whitespace-nowrap">0937.533.505</span>
        </a>
    </div>

    <!-- Thanh liên hệ nổi bật dưới cùng cho Điện Thoại (không tràn viền, dễ bấm ngón cái) -->
    <div class="md:hidden fixed bottom-0 left-0 right-0 z-40 bg-white border-t border-slate-200 shadow-[0_-4px_15px_rgba(0,0,0,0.08)] px-2 py-2">
        <div class="grid grid-cols-3 gap-2">
            <a
                href="tel:0937533505"
                class="flex items-center justify-center gap-1.5 bg-red-600 active:bg-red-700 text-white py-2.5 px-2 rounded-lg text-xs font-bold shadow-sm"
            >
                <i class="fa-solid fa-phone-volume"></i>
                <span>Hotline</span>
            </a>
            <a
                href="https://zalo.me/0937533505"
                target="_blank"
                rel="noopener noreferrer"
                class="flex items-center justify-center gap-1.5 bg-[#0068FF] active:bg-[#0052CC] text-white py-2.5 px-2 rounded-lg text-xs font-bold shadow-sm"
            >
                <span class="bg-white text-[#0068FF] rounded px-1 text-[10px] font-extrabold">Zalo</span>
                <span>Chat Zalo</span>
            </a>
            <a
                href="https://www.facebook.com/xay.dung.lam.ngoc"
                target="_blank"
                rel="noopener noreferrer"
                class="flex items-center justify-center gap-1.5 bg-[#1877F2] active:bg-[#145DBF] text-white py-2.5 px-2 rounded-lg text-xs font-bold shadow-sm"
            >
                <i class="fa-brands fa-facebook"></i>
                <span>Facebook</span>
            </a>
        </div>
    </div>

    <!-- ========================================================= -->
    <!-- MODAL XEM CHI TIẾT CÔNG TRÌNH / DỰ ÁN / BÀI VIẾT          -->
    <!-- ========================================================= -->
    <div id="detail-modal" class="fixed inset-0 z-50 hidden items-center justify-center bg-black/70 p-3 sm:p-5 backdrop-blur-xs">
        <div class="bg-white rounded-xl max-w-2xl w-full max-h-[90vh] overflow-y-auto shadow-2xl relative">
            <button
                type="button"
                onclick="closeDetailModal()"
                aria-label="Đóng cửa sổ"
                class="absolute top-3 right-3 z-10 w-8 h-8 rounded-full bg-black/55 hover:bg-brand text-white flex items-center justify-center transition"
            >
                <i class="fa-solid fa-xmark"></i>
            </button>
            <div id="modal-body-content"></div>
        </div>
    </div>

    <!-- ========================================================= -->
    <!-- HỘP THÔNG BÁO THÀNH CÔNG (THAY THẾ HOÀN TOÀN ALERT)       -->
    <!-- ========================================================= -->
    <div id="toast-message" class="fixed top-20 right-4 z-50 hidden max-w-xs sm:max-w-sm bg-white border-l-4 border-brand rounded-lg shadow-xl p-4 transition-all">
        <div class="flex items-start gap-3">
            <div class="w-8 h-8 rounded-full bg-brand-soft text-brand flex items-center justify-center shrink-0">
                <i class="fa-solid fa-circle-check text-lg"></i>
            </div>
            <div>
                <h4 id="toast-title" class="text-xs sm:text-sm font-bold text-slate-800">Gửi yêu cầu thành công!</h4>
                <p id="toast-desc" class="text-xs text-slate-600 mt-0.5 leading-relaxed"></p>
            </div>
        </div>
    </div>

    <!-- ========================================================= -->
    <!-- JAVASCRIPT XỬ LÝ TƯƠNG TÁC, DỮ LIỆU & SLIDER              -->
    <!-- ========================================================= -->
    <script>
        /* =========================================================
           1. HÀM DỰ PHÒNG LOAD ẢNH GOOGLE DRIVE ỔN ĐỊNH CAO
           ========================================================= */
        function driveThumbUrl(fileId, width) {
            return 'https://drive.google.com/thumbnail?id=' + fileId + '&sz=w' + (width || 1000);
        }

        function handleDriveImageError(imgEl, fallbackText) {
            try {
                const fileId = imgEl.getAttribute('data-drive-id');
                const retryCount = parseInt(imgEl.getAttribute('data-retry') || '0', 10);

                if (fileId && retryCount === 0) {
                    imgEl.setAttribute('data-retry', '1');
                    imgEl.src = 'https://lh3.googleusercontent.com/d/' + fileId + '=w1000';
                    return;
                }
                if (fileId && retryCount === 1) {
                    imgEl.setAttribute('data-retry', '2');
                    imgEl.src = 'https://drive.google.com/uc?export=view&id=' + fileId;
                    return;
                }

                imgEl.onerror = null;
                const safeText = encodeURIComponent(fallbackText || 'XAY DUNG LAM NGOC');
                imgEl.src = 'https://placehold.co/800x600/0E5E49/FFFFFF?text=' + safeText;
            } catch (e) {
                imgEl.onerror = null;
            }
        }

        /* =========================================================
           2. DỮ LIỆU 9 ẢNH THI CÔNG THỰC TẾ TỪ GOOGLE DRIVE
           ========================================================= */
        const constructionWorks = [
            {
                id: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
                title: 'Thi Công Phần Thô Nhà Phố Hiện Đại',
                category: 'nha-pho',
                categoryLabel: 'Nhà phố',
                location: 'TP. Đà Nẵng',
                scope: 'Thi công phần thô & nhân công hoàn thiện',
                desc: 'Công trình nhà phố hiện đại được đội ngũ kỹ sư Lâm Ngọc triển khai thi công kết cấu móng, cột, dầm, sàn bê tông cốt thép đạt tiêu chuẩn kỹ thuật nghiêm ngặt.'
            },
            {
                id: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
                title: 'Xây Nhà Trọn Gói Nhà Phố 3 Tầng',
                category: 'nha-pho',
                categoryLabel: 'Nhà phố',
                location: 'Quận Ngũ Hành Sơn, Đà Nẵng',
                scope: 'Thiết kế & Thi công trọn gói chìa khóa trao tay',
                desc: 'Thi công trọn gói nhà phố 3 tầng phong cách tối giản hiện đại, tối ưu công năng lấy sáng và thông gió tự nhiên cho gia đình trẻ.'
            },
            {
                id: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
                title: 'Thi Công Biệt Thự Sân Vườn Cao Cấp',
                category: 'biet-thu',
                categoryLabel: 'Biệt thự',
                location: 'Khu Đô Thị Hòa Xuân, Đà Nẵng',
                scope: 'Thi công phần thô & hoàn thiện ngoại thất',
                desc: 'Hạng mục biệt thự sân vườn với hệ kết cấu vượt nhịp kiên cố, đường nét kiến trúc sang trọng cùng hệ vật tư hoàn thiện cao cấp.'
            },
            {
                id: '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_',
                title: 'Thi Công Căn Hộ Cho Thuê Tiêu Chuẩn',
                category: 'khach-san',
                categoryLabel: 'Khách sạn - Căn hộ',
                location: 'Khu vực Mỹ An, Đà Nẵng',
                scope: 'Thi công trọn gói & lắp đặt hệ thống MEP',
                desc: 'Mô hình căn hộ dịch vụ cho thuê khai thác tối đa diện tích sử dụng, thi công điện nước âm tường an toàn và chống thấm toàn diện.'
            },
            {
                id: '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO',
                title: 'Thi Công Hoàn Thiện Khách Sạn Mini',
                category: 'khach-san',
                categoryLabel: 'Khách sạn - Căn hộ',
                location: 'Quận Sơn Trà, Đà Nẵng',
                scope: 'Thi công hoàn thiện mặt tiền & nội thất',
                desc: 'Hoàn thiện tổ hợp phòng lưu trú tiêu chuẩn với vật liệu cách âm, sơn ngoại thất chống muối biển bền đẹp theo thời gian.'
            },
            {
                id: '1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t',
                title: 'Thi Công Kết Cấu & Đổ Bê Tông Sàn',
                category: 'biet-thu',
                categoryLabel: 'Biệt thự',
                location: 'Quận Cẩm Lệ, Đà Nẵng',
                scope: 'Thi công phần thô kết cấu chịu lực',
                desc: 'Công tác lắp dựng cốt thép, cốp pha và đổ bê tông tươi được giám sát trực tiếp từng công đoạn nhằm đảm bảo tuổi thọ công trình.'
            },
            {
                id: '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_',
                title: 'Hoàn Thiện Mặt Tiền & Nội Thất Nhà Phố',
                category: 'nha-pho',
                categoryLabel: 'Nhà phố',
                location: 'Quận Hải Châu, Đà Nẵng',
                scope: 'Thi công hoàn thiện & nội thất gỗ',
                desc: 'Tỉ mỉ từ khâu ốp lát gạch, sơn bả hoàn thiện đến lắp đặt cửa nhôm kính và hệ tủ nội thất sắc nét đúng bản vẽ 3D.'
            },
            {
                id: '1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT',
                title: 'Thi Công Văn Phòng & Showroom Thương Mại',
                category: 'van-phong',
                categoryLabel: 'Văn phòng',
                location: 'TP. Đà Nẵng',
                scope: 'Thiết kế & Thi công hoàn thiện văn phòng',
                desc: 'Không gian làm việc chuyên nghiệp, bố trí hệ thống chiếu sáng, điều hòa và vách ngăn khoa học giúp tối ưu hiệu suất vận hành.'
            },
            {
                id: '1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn',
                title: 'Thi Công Nhà Phố 2 Mặt Tiền Hiện Đại',
                category: 'van-phong',
                categoryLabel: 'Văn phòng',
                location: 'Phường Ngũ Hành Sơn, Đà Nẵng',
                scope: 'Thi công xây dựng trọn gói',
                desc: 'Công trình nhà phố kết hợp kinh doanh văn phòng sở hữu 2 mặt tiền thông thoáng, tiến độ thi công nhanh gọn và thẩm mỹ nổi bật.'
            }
        ];

        /* =========================================================
           3. DỮ LIỆU 10 DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG TỪ DRIVE
           ========================================================= */
        const daNangProjects = [
            {
                id: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
                title: 'Dự Án Nhà Phố Ngũ Hành Sơn Đà Nẵng',
                location: 'Phường Ngũ Hành Sơn, TP. Đà Nẵng',
                desc: 'Thi công trọn gói nhà phố hiện đại tại khu vực Ngũ Hành Sơn với thiết kế không gian mở, đón nắng gió tự nhiên.'
            },
            {
                id: '1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff',
                title: 'Dự Án Biệt Thự Ven Sông Hòa Xuân Đà Nẵng',
                location: 'Khu Đô Thị Hòa Xuân, Đà Nẵng',
                desc: 'Biệt thự gia đình mang phong cách kiến trúc hiện đại, kết hợp sân vườn xanh mát và hệ cửa kính lớn view sông.'
            },
            {
                id: '1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz',
                title: 'Dự Án Căn Hộ Dịch Vụ Mỹ Khê Đà Nẵng',
                location: 'Khu vực biển Mỹ Khê, Đà Nẵng',
                desc: 'Công trình căn hộ dịch vụ cho thuê nhiều tầng được thi công đồng bộ phần thô, hệ thống điện nước và hoàn thiện nội thất.'
            },
            {
                id: '1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k',
                title: 'Dự Án Nhà Phố Hiện Đại Hòa Quý Đà Nẵng',
                location: 'Khu Đô Thị Hòa Quý, Đà Nẵng',
                desc: 'Nhà phố 3 tầng trẻ trung, bố trí công năng hợp lý cho gia đình đa thế hệ, bàn giao đúng tiến độ cam kết.'
            },
            {
                id: '1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N',
                title: 'Dự Án Khách Sạn Boutique Sơn Trà Đà Nẵng',
                location: 'Quận Sơn Trà, TP. Đà Nẵng',
                desc: 'Thi công kết cấu và hoàn thiện mặt tiền sang trọng, sử dụng vật liệu bền bỉ với khí hậu ven biển miền Trung.'
            },
            {
                id: '1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML',
                title: 'Dự Án Biệt Thự Khu Đô Thị FPT City Đà Nẵng',
                location: 'Khu Đô Thị FPT City, Ngũ Hành Sơn',
                desc: 'Biệt thự liền kề hoàn thiện chuẩn mực với đường nét kiến trúc sắc sảo, tối ưu tiện ích sinh hoạt hiện đại.'
            },
            {
                id: '1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF',
                title: 'Dự Án Nhà Phố Thương Mại Hải Châu Đà Nẵng',
                location: 'Quận Hải Châu, TP. Đà Nẵng',
                desc: 'Nhà ở kết hợp mặt bằng kinh doanh ngay trung tâm thành phố, đảm bảo tiêu chuẩn an toàn thi công khu dân cư.'
            },
            {
                id: '1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A',
                title: 'Dự Án Cải Tạo Văn Phòng Cẩm Lệ Đà Nẵng',
                location: 'Quận Cẩm Lệ, TP. Đà Nẵng',
                desc: 'Cải tạo nâng cấp toàn diện không gian làm việc, mở rộng diện tích sử dụng với chi phí đầu tư tiết kiệm.'
            },
            {
                id: '1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80',
                title: 'Dự Án Biệt Thự Nghỉ Dưỡng Non Nước Đà Nẵng',
                location: 'Khu vực Non Nước, Ngũ Hành Sơn',
                desc: 'Biệt thự nghỉ dưỡng cao cấp thi công tỉ mỉ từ phần thô kết cấu đến hoàn thiện ốp đá tự nhiên và cảnh quan.'
            },
            {
                id: '1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4',
                title: 'Dự Án Nhà Phố 3 Tầng Nam Việt Á Đà Nẵng',
                location: 'Khu Đô Thị Nam Việt Á, Đà Nẵng',
                desc: 'Thi công nhà phố 3 tầng chìa khóa trao tay, thiết kế mặt tiền thông thoáng cùng vật tư hoàn thiện chính hãng.'
            }
        ];

        /* =========================================================
           4. DỮ LIỆU DANH MỤC BÀI VIẾT / TIN TỨC TRANG CHỦ
           ========================================================= */
        const articlesData = [
            {
                imgId: '1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t',
                date: '15/11/2026',
                title: 'Hướng Dẫn Bảo Dưỡng Bê Tông Móng Đúng Kỹ Thuật Khi Xây Nhà',
                excerpt: 'Bảo dưỡng bê tông đúng thời điểm giúp kết cấu móng đạt cường độ tối đa, hạn chế rạn nứt bề mặt về lâu dài.',
                content: 'Sau khi đổ bê tông móng, việc giữ ẩm liên tục trong 7 ngày đầu đóng vai trò quyết định đến độ bền kết cấu toàn ngôi nhà. Kỹ sư Lâm Ngọc luôn tiến hành che phủ bao bố ướt, tưới nước giữ ẩm định kỳ theo khung giờ nắng nóng tại Đà Nẵng để đảm bảo bê tông thủy hóa hoàn toàn, tránh nứt chân chim.'
            },
            {
                imgId: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
                date: '08/11/2026',
                title: 'Kinh Nghiệm Chọn Nhà Thầu Xây Nhà Trọn Gói Uy Tín Tại Đà Nẵng',
                excerpt: 'Những tiêu chí quan trọng giúp gia chủ đánh giá năng lực nhà thầu, bảng vật tư và hợp đồng minh bạch.',
                content: 'Khi lựa chọn đơn vị xây nhà trọn gói, chủ đầu tư nên kiểm tra rõ giấy phép kinh doanh, các công trình thực tế đã thi công tại Đà Nẵng, bảng quy cách chủng loại vật tư ghi rõ thương hiệu và chính sách bảo hành kết cấu. Hợp đồng rõ ràng ngay từ đầu sẽ giúp bạn kiểm soát 100% chi phí.'
            },
            {
                imgId: '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_',
                date: '29/10/2026',
                title: 'Giải Pháp Chống Thấm Nhà Phố Hiệu Quả Cho Khí Hậu Miền Trung',
                excerpt: 'Quy trình chống thấm sân thượng, nhà vệ sinh và tường ngoài giúp ngôi nhà luôn bền đẹp qua mùa mưa bão.',
                content: 'Khí hậu nắng gắt xen kẽ mưa bão kéo dài tại miền Trung đòi hỏi quy trình chống thấm đa lớp ngay từ giai đoạn thi công phần thô. Lâm Ngọc áp dụng vữa chống thấm gốc xi măng polyme cho sàn mái, cổ ống xuyên sàn và sơn lót kháng kiềm cao cấp cho toàn bộ tường bao.'
            },
            {
                imgId: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
                date: '18/10/2026',
                title: 'Xu Hướng Thiết Kế Nhà Phố Hiện Đại Tối Ưu Không Gian Sống',
                excerpt: 'Kết hợp giếng trời, mảng xanh ban công và vật liệu thân thiện để tạo nên tổ ấm thoáng mát quanh năm.',
                content: 'Thiết kế nhà phố hiện đại tập trung vào sự đơn giản tinh tế, loại bỏ chi tiết rườm rà và ưu tiên không gian mở kết nối phòng khách với khu bếp. Việc bố trí giếng trời hợp lý giúp đối lưu không khí, giảm nhiệt độ trong nhà và tiết kiệm đáng kể điện năng chiếu sáng.'
            }
        ];

        /* =========================================================
           5. RENDER CÔNG TRÌNH THỰC TẾ (KHÔNG NHÃN DÁN, FULL TÊN)
           ========================================================= */
        function renderWorks(filterKey) {
            const grid = document.getElementById('works-grid');
            if (!grid) return;

            const filtered = filterKey === 'all'
                ? constructionWorks
                : constructionWorks.filter(item => item.category === filterKey);

            grid.innerHTML = filtered.map((item) => {
                const origIndex = constructionWorks.indexOf(item);
                return `
                    <article
                        onclick="openWorkModal(${origIndex})"
                        class="group bg-white rounded-xl border border-slate-200/80 overflow-hidden shadow-sm hover:shadow-md hover:border-brand/40 transition cursor-pointer flex flex-col"
                    >
                        <div class="img-zoom-wrap aspect-[4/3] w-full">
                            <img
                                src="${driveThumbUrl(item.id, 900)}"
                                data-drive-id="${item.id}"
                                alt="${item.title}"
                                loading="lazy"
                                class="w-full h-full object-cover"
                                onerror="handleDriveImageError(this, 'LAM NGOC CONS')"
                            >
                        </div>
                        <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                            <h3 class="text-[12px] sm:text-sm font-bold text-slate-800 group-hover:text-brand leading-snug break-words">
                                ${item.title}
                            </h3>
                            <p class="text-[11px] text-slate-500 mt-1.5 break-words">
                                <i class="fa-solid fa-location-dot text-accent mr-1"></i>${item.location}
                            </p>
                        </div>
                    </article>
                `;
            }).join('');
        }

        function filterWorks(category) {
            renderWorks(category);
            const buttons = document.querySelectorAll('.work-tab-btn');
            buttons.forEach(btn => {
                const isActive = btn.getAttribute('data-filter') === category;
                if (isActive) {
                    btn.className = 'work-tab-btn px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11px] sm:text-xs font-semibold whitespace-nowrap bg-brand text-white transition';
                } else {
                    btn.className = 'work-tab-btn px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11px] sm:text-xs font-semibold whitespace-nowrap bg-slate-100 text-slate-700 hover:bg-brand-soft hover:text-brand transition';
                }
            });
        }

        /* =========================================================
           6. RENDER 10 DỰ ÁN TẠI ĐÀ NẴNG (MOBILE 2 CỘT, FULL TÊN)
           ========================================================= */
        function renderDaNangProjects() {
            const grid = document.getElementById('danang-projects-grid');
            if (!grid) return;

            grid.innerHTML = daNangProjects.map((proj, idx) => `
                <article
                    onclick="openProjectModal(${idx})"
                    class="group bg-white rounded-xl border border-slate-200/80 overflow-hidden shadow-sm hover:shadow-md hover:border-brand/40 transition cursor-pointer flex flex-col"
                >
                    <div class="img-zoom-wrap aspect-[4/3] w-full">
                        <img
                            src="${driveThumbUrl(proj.id, 800)}"
                            data-drive-id="${proj.id}"
                            alt="${proj.title}"
                            loading="lazy"
                            class="w-full h-full object-cover"
                            onerror="handleDriveImageError(this, 'DU AN DA NANG')"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                        <h3 class="text-[12px] sm:text-[13px] font-bold text-slate-800 group-hover:text-brand leading-snug break-words">
                            ${proj.title}
                        </h3>
                        <p class="text-[11px] text-slate-500 mt-1.5 break-words">
                            ${proj.location}
                        </p>
                    </div>
                </article>
            `).join('');
        }

        /* =========================================================
           7. RENDER DANH MỤC BÀI VIẾT TRANG CHỦ
           ========================================================= */
        function renderArticles() {
            const grid = document.getElementById('articles-grid');
            if (!grid) return;

            grid.innerHTML = articlesData.map((art, idx) => `
                <article
                    onclick="openArticleModal(${idx})"
                    class="group bg-white rounded-xl border border-slate-200/80 overflow-hidden shadow-sm hover:shadow-md hover:border-brand/40 transition cursor-pointer flex flex-col"
                >
                    <div class="img-zoom-wrap aspect-[16/10] w-full">
                        <img
                            src="${driveThumbUrl(art.imgId, 700)}"
                            data-drive-id="${art.imgId}"
                            alt="${art.title}"
                            loading="lazy"
                            class="w-full h-full object-cover"
                            onerror="handleDriveImageError(this, 'TIN TUC')"
                        >
                    </div>
                    <div class="p-2.5 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[10px] sm:text-[11px] text-slate-400 mb-1">
                                <i class="fa-regular fa-calendar mr-1"></i>${art.date}
                            </div>
                            <h3 class="text-[12px] sm:text-sm font-bold text-slate-800 group-hover:text-brand leading-snug break-words mb-1.5">
                                ${art.title}
                            </h3>
                            <p class="hidden sm:block text-xs text-slate-500 leading-relaxed">
                                ${art.excerpt}
                            </p>
                        </div>
                        <div class="mt-2.5 text-[11px] sm:text-xs font-semibold text-brand group-hover:text-accent inline-flex items-center gap-1">
                            <span>Xem chi tiết</span>
                            <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </div>
                    </div>
                </article>
            `).join('');
        }

        /* =========================================================
           8. MODAL CHI TIẾT CÔNG TRÌNH, DỰ ÁN & BÀI VIẾT
           ========================================================= */
        function openDetailModal(htmlContent) {
            const modal = document.getElementById('detail-modal');
            const body = document.getElementById('modal-body-content');
            body.innerHTML = htmlContent;
            modal.classList.remove('hidden');
            modal.classList.add('flex');
            document.body.style.overflow = 'hidden';
        }

        function closeDetailModal() {
            const modal = document.getElementById('detail-modal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
            document.body.style.overflow = '';
        }

        function openWorkModal(index) {
            const item = constructionWorks[index];
            if (!item) return;
            openDetailModal(`
                <div class="w-full bg-slate-100">
                    <img src="${driveThumbUrl(item.id, 1200)}" data-drive-id="${item.id}" alt="${item.title}" class="w-full max-h-[380px] object-cover" onerror="handleDriveImageError(this, 'LAM NGOC')">
                </div>
                <div class="p-5 sm:p-6 space-y-3">
                    <h3 class="text-base sm:text-lg font-extrabold text-brand">${item.title}</h3>
                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-2 text-xs bg-slate-50 p-3 rounded-lg border border-slate-100">
                        <div><strong>Hạng mục:</strong> ${item.categoryLabel}</div>
                        <div><strong>Địa điểm:</strong> ${item.location}</div>
                        <div class="sm:col-span-2"><strong>Phạm vi:</strong> ${item.scope}</div>
                    </div>
                    <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">${item.desc}</p>
                    <div class="pt-2 flex flex-wrap gap-2.5">
                        <a href="#form-bao-gia" onclick="closeDetailModal(); selectServiceInForm('${item.title}')" class="inline-flex items-center gap-2 bg-brand hover:bg-brand-dark text-white text-xs font-semibold px-4 py-2.5 rounded-lg transition">
                            Nhận báo giá mẫu này
                        </a>
                        <a href="tel:0937533505" class="inline-flex items-center gap-2 bg-accent hover:bg-accent-hover text-white text-xs font-semibold px-4 py-2.5 rounded-lg transition">
                            <i class="fa-solid fa-phone"></i> Gọi 0937.533.505
                        </a>
                    </div>
                </div>
            `);
        }

        function openProjectModal(index) {
            const proj = daNangProjects[index];
            if (!proj) return;
            openDetailModal(`
                <div class="w-full bg-slate-100">
                    <img src="${driveThumbUrl(proj.id, 1200)}" data-drive-id="${proj.id}" alt="${proj.title}" class="w-full max-h-[380px] object-cover" onerror="handleDriveImageError(this, 'DU AN DA NANG')">
                </div>
                <div class="p-5 sm:p-6 space-y-3">
                    <h3 class="text-base sm:text-lg font-extrabold text-brand">${proj.title}</h3>
                    <div class="text-xs text-slate-600 bg-slate-50 p-3 rounded-lg border border-slate-100">
                        <i class="fa-solid fa-location-dot text-accent mr-1.5"></i><strong>Khu vực:</strong> ${proj.location}
                    </div>
                    <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">${proj.desc}</p>
                    <div class="pt-2 flex flex-wrap gap-2.5">
                        <a href="#form-bao-gia" onclick="closeDetailModal()" class="inline-flex items-center gap-2 bg-brand hover:bg-brand-dark text-white text-xs font-semibold px-4 py-2.5 rounded-lg transition">
                            Tư vấn dự án tương tự
                        </a>
                        <a href="https://zalo.me/0937533505" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-2 bg-[#0068FF] hover:bg-[#0052CC] text-white text-xs font-semibold px-4 py-2.5 rounded-lg transition">
                            Chat Zalo kỹ sư
                        </a>
                    </div>
                </div>
            `);
        }

        function openArticleModal(index) {
            const art = articlesData[index];
            if (!art) return;
            openDetailModal(`
                <div class="w-full bg-slate-100">
                    <img src="${driveThumbUrl(art.imgId, 1200)}" data-drive-id="${art.imgId}" alt="${art.title}" class="w-full max-h-[320px] object-cover" onerror="handleDriveImageError(this, 'TIN TUC')">
                </div>
                <div class="p-5 sm:p-6 space-y-3">
                    <div class="text-xs text-slate-400"><i class="fa-regular fa-calendar mr-1"></i>${art.date} • Xây Dựng Lâm Ngọc</div>
                    <h3 class="text-base sm:text-lg font-extrabold text-brand leading-snug">${art.title}</h3>
                    <p class="text-xs sm:text-sm text-slate-700 font-medium leading-relaxed">${art.excerpt}</p>
                    <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">${art.content}</p>
                    <div class="pt-3 border-t border-slate-100 flex items-center justify-between">
                        <span class="text-xs text-slate-500">Hotline tư vấn: <strong>0937.533.505</strong></span>
                        <a href="#form-bao-gia" onclick="closeDetailModal()" class="text-xs font-bold text-brand hover:text-accent">Đăng ký báo giá &rarr;</a>
                    </div>
                </div>
            `);
        }

        document.getElementById('detail-modal').addEventListener('click', function (e) {
            if (e.target === this) closeDetailModal();
        });

        /* =========================================================
           9. BANNER SLIDER TỰ TRƯỢT 2 ẢNH (HỖ TRỢ VUỐT TOUCH)
           ========================================================= */
        let currentSlide = 0;
        const totalSlides = 2;
        let autoSlideTimer = null;

        function updateSlider() {
            const track = document.getElementById('hero-track');
            const dots = document.querySelectorAll('.slider-dot');
            if (!track) return;

            track.style.transform = 'translateX(-' + (currentSlide * 100) + '%)';
            dots.forEach((dot, idx) => {
                if (idx === currentSlide) {
                    dot.classList.remove('w-2.5', 'bg-white/60');
                    dot.classList.add('w-6', 'bg-accent');
                } else {
                    dot.classList.remove('w-6', 'bg-accent');
                    dot.classList.add('w-2.5', 'bg-white/60');
                }
            });
        }

        function goToSlide(index) {
            currentSlide = (index + totalSlides) % totalSlides;
            updateSlider();
            resetAutoSlide();
        }

        function resetAutoSlide() {
            if (autoSlideTimer) clearInterval(autoSlideTimer);
            autoSlideTimer = setInterval(() => {
                currentSlide = (currentSlide + 1) % totalSlides;
                updateSlider();
            }, 5200);
        }

        /* =========================================================
           10. MENU MOBILE DRAWER & FORM BÁO GIÁ
           ========================================================= */
        function openMobileMenu() {
            const drawer = document.getElementById('mobile-drawer');
            const overlay = document.getElementById('mobile-drawer-overlay');
            overlay.classList.remove('hidden');
            requestAnimationFrame(() => {
                overlay.classList.remove('opacity-0');
                drawer.classList.remove('-translate-x-full');
            });
            document.body.style.overflow = 'hidden';
        }

        function closeMobileMenu() {
            const drawer = document.getElementById('mobile-drawer');
            const overlay = document.getElementById('mobile-drawer-overlay');
            overlay.classList.add('opacity-0');
            drawer.classList.add('-translate-x-full');
            setTimeout(() => {
                overlay.classList.add('hidden');
            }, 300);
            document.body.style.overflow = '';
        }

        function toggleMobileSub(id) {
            const el = document.getElementById(id);
            if (el) el.classList.toggle('hidden');
        }

        function selectServiceInForm(serviceText) {
            const selectEl = document.getElementById('q-type');
            const noteEl = document.getElementById('q-note');
            if (selectEl) {
                let matched = false;
                for (let i = 0; i < selectEl.options.length; i++) {
                    if (selectEl.options[i].value.toLowerCase() === serviceText.toLowerCase()) {
                        selectEl.selectedIndex = i;
                        matched = true;
                        break;
                    }
                }
                if (!matched && noteEl) {
                    noteEl.value = 'Tôi cần tư vấn & báo giá hạng mục: ' + serviceText;
                }
            }
        }

        function showToast(title, description) {
            const toast = document.getElementById('toast-message');
            document.getElementById('toast-title').textContent = title;
            document.getElementById('toast-desc').textContent = description;
            toast.classList.remove('hidden');
            setTimeout(() => {
                toast.classList.add('hidden');
            }, 5000);
        }

        /* =========================================================
           11. KHỞI TẠO KHI TẢI TRANG
           ========================================================= */
        document.addEventListener('DOMContentLoaded', function () {
            renderWorks('all');
            renderDaNangProjects();
            renderArticles();

            // Khởi động slider 2 banner tự trượt
            updateSlider();
            resetAutoSlide();

            document.getElementById('slider-prev').addEventListener('click', () => goToSlide(currentSlide - 1));
            document.getElementById('slider-next').addEventListener('click', () => goToSlide(currentSlide + 1));
            document.querySelectorAll('.slider-dot').forEach(dot => {
                dot.addEventListener('click', () => goToSlide(parseInt(dot.getAttribute('data-slide'), 10)));
            });

            // Hỗ trợ vuốt cảm ứng trên điện thoại cho Banner Slider
            const heroEl = document.getElementById('hero-slider');
            let touchStartX = 0;
            let touchEndX = 0;
            heroEl.addEventListener('touchstart', (e) => {
                touchStartX = e.changedTouches[0].screenX;
            }, { passive: true });
            heroEl.addEventListener('touchend', (e) => {
                touchEndX = e.changedTouches[0].screenX;
                if (touchStartX - touchEndX > 40) goToSlide(currentSlide + 1);
                if (touchEndX - touchStartX > 40) goToSlide(currentSlide - 1);
            }, { passive: true });

            // Gắn sự kiện mở/đóng Mobile Drawer
            document.getElementById('mobile-menu-open').addEventListener('click', openMobileMenu);
            document.getElementById('mobile-menu-close').addEventListener('click', closeMobileMenu);
            document.getElementById('mobile-drawer-overlay').addEventListener('click', closeMobileMenu);

            // Xử lý gửi Form Báo Giá
            document.getElementById('quote-form').addEventListener('submit', function (e) {
                e.preventDefault();
                const name = document.getElementById('q-name').value.trim();
                const phone = document.getElementById('q-phone').value.trim();
                if (!name || !phone) {
                    showToast('Thiếu thông tin', 'Vui lòng nhập đầy đủ Họ tên và Số điện thoại để kỹ sư liên hệ.');
                    return;
                }
                showToast(
                    'Đã nhận yêu cầu báo giá!',
                    'Cảm ơn ' + name + '. Xây Dựng Lâm Ngọc sẽ liên hệ SĐT ' + phone + ' trong thời gian sớm nhất.'
                );
                this.reset();
            });
        });
    </script>
</body>
</html>
