<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
  <title>V&K TRAVEL AGENCY - Chuyên Xe Du Lịch Đà Nẵng Hội An 4-7-16 Chỗ | vktravel.com</title>
  <meta name="description" content="CÔNG TY TNHH V&K TRAVEL AGENCY (vktravel.com) - Chuyên xe du lịch Đà Nẵng - Hội An 4-7-16 chỗ đời mới. Hỗ trợ xuất VAT công ty. Miễn phí vé ra vào sân bay. Hotline: 0905 92 0638.">

  <!-- Open Graph Thumbnail là Logo trang web khi gửi link chia sẻ -->
  <meta property="og:type" content="website">
  <meta property="og:url" content="https://vktravel.com/">
  <meta property="og:site_name" content="vktravel.com - CÔNG TY TNHH V&K TRAVEL AGENCY">
  <meta property="og:title" content="CÔNG TY TNHH V&K TRAVEL AGENCY | Xe Du Lịch Đà Nẵng - Hội An 4-7-16 Chỗ">
  <meta property="og:description" content="Chuyên xe du lịch Đà Nẵng - Hội An 4-7-16 chỗ. Hỗ trợ xuất VAT công ty. Miễn phí vé ra vào sân bay. Địa chỉ: 29 Cao Sơn Pháo, Phường Điện Bàn, TP Đà Nẵng. ĐT: 0905 92 0638.">
  <meta property="og:image" content="https://lh3.googleusercontent.com/d/1aqth1Q9LiMr-ENw135ygs9CA04IpGUoY">
  <meta name="twitter:card" content="summary_large_image">
  <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1aqth1Q9LiMr-ENw135ygs9CA04IpGUoY">
  <link rel="icon" href="https://lh3.googleusercontent.com/d/1aqth1Q9LiMr-ENw135ygs9CA04IpGUoY">

  <!-- Tailwind CSS & Font Awesome & Google Fonts -->
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

  <style>
    :root {
      --vk-primary: #0b3d78;       /* Xanh chủ đạo theo tông logo du lịch */
      --vk-secondary: #0077b6;     /* Xanh lam điểm nhấn */
      --vk-accent: #f59e0b;        /* Vàng cam nổi bật cho nút đặt xe */
      --vk-accent-hover: #d97706;
      --vk-bg-light: #f4f7fb;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    html, body {
      width: 100%;
      max-width: 100vw;
      overflow-x: hidden;
      font-family: 'Inter', sans-serif;
      background-color: #f8fafc;
      color: #1e293b;
      scroll-behavior: smooth;
    }

    /* Chiều ngang giao diện trên máy tính bằng 95% kích thước màn hình máy tính, căn giữa chuẩn xác, không tràn viền */
    .flatsome-container {
      width: 100%;
      max-width: 100%;
      margin-left: auto;
      margin-right: auto;
      padding-left: 10px;
      padding-right: 10px;
    }

    @media (min-width: 1024px) {
      .flatsome-container {
        width: 95%;
        max-width: 95%;
        padding-left: 0;
        padding-right: 0;
      }
    }

    /* Tối ưu tên danh mục trên máy tính: viết liền trên 1 hàng, chữ nhỏ gọn, không xuống dòng từng chữ */
    .nav-cat-item {
      white-space: nowrap;
      display: inline-flex;
      align-items: center;
      font-size: 12.5px;
      font-weight: 600;
      line-height: 1.2;
      transition: all 0.2s ease;
    }

    /* Thanh danh mục ở trang chủ nhỏ gọn, đẹp trên cả máy tính và điện thoại */
    .home-cat-pill {
      white-space: nowrap;
      font-size: 12px;
      font-weight: 600;
      padding: 6px 11px;
      border-radius: 6px;
      transition: all 0.2s ease;
      display: inline-flex;
      align-items: center;
      justify-content: center;
      gap: 5px;
    }

    /* Tên sản phẩm không bị tràn ra ngoài hoặc thiếu chữ */
    .product-title-full {
      white-space: normal;
      word-break: break-word;
      overflow-wrap: anywhere;
      line-height: 1.35;
      display: block;
    }

    /* Dropdown menu chuẩn Flatsome trên máy tính */
    .has-dropdown {
      position: relative;
    }
    .has-dropdown .sub-menu {
      display: none;
      position: absolute;
      top: 100%;
      left: 0;
      min-width: 230px;
      background: #ffffff;
      box-shadow: 0 10px 25px rgba(0, 0, 0, 0.12);
      border-top: 3px solid var(--vk-primary);
      border-radius: 0 0 8px 8px;
      z-index: 100;
      padding: 6px 0;
    }
    .has-dropdown:hover .sub-menu {
      display: block;
    }
    .sub-menu a {
      display: block;
      padding: 7px 14px;
      font-size: 12.5px;
      color: #334155;
      white-space: nowrap;
      border-bottom: 1px solid #f1f5f9;
    }
    .sub-menu a:last-child {
      border-bottom: none;
    }
    .sub-menu a:hover {
      background-color: #f0f7ff;
      color: var(--vk-primary);
      padding-left: 18px;
    }

    /* Kích thước cố định bằng nhau cho 2 slide banner trên máy tính và điện thoại */
    .desktop-banner-slide {
      height: 350px;
      width: 100%;
    }
    .mobile-banner-slide {
      height: 225px;
      width: 100%;
    }

    /* Nút liên hệ nổi bật hiệu ứng rung nhẹ */
    @keyframes pulse-ring {
      0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(220, 38, 38, 0.6); }
      70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(220, 38, 38, 0); }
      100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(220, 38, 38, 0); }
    }
    .pulse-btn {
      animation: pulse-ring 2s infinite;
    }
  </style>
</head>
<body>

  <!-- ================= WRAPPER CHUẨN FLATSOME ================= -->
  <div id="wrapper" class="w-full overflow-x-hidden">

    <!-- ================= HEADER (FLATSOME HEADER) ================= -->
    <header id="header" class="w-full bg-white shadow-sm sticky top-0 z-50">
      
      <!-- Top Bar (Flatsome Top Bar) -->
      <div class="bg-[#0b3d78] text-white text-[11px] sm:text-xs py-1.5">
        <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
          <div class="flex items-center gap-2 font-medium truncate max-w-full">
            <i class="fa-solid fa-building-shield text-amber-400 shrink-0"></i>
            <span class="truncate">CÔNG TY TNHH V&K TRAVEL AGENCY | MST: 4001277058 | Miễn phí vé sân bay & Hỗ trợ xuất VAT</span>
          </div>
          <div class="hidden md:flex items-center gap-4 text-[11.5px] shrink-0">
            <span><i class="fa-solid fa-location-dot text-amber-400 mr-1"></i>29 Cao Sơn Pháo, Phường Điện Bàn, TP Đà Nẵng</span>
            <span><i class="fa-solid fa-globe text-amber-400 mr-1"></i>vktravel.com</span>
          </div>
        </div>
      </div>

      <!-- Header Main (Logo gọn nhỏ + Menu danh mục viết liền trên 1 hàng, không có nút gọi ngay trên header) -->
      <div class="border-b border-slate-200 bg-white">
        <div class="flatsome-container py-2 flex items-center justify-between gap-2">
          
          <!-- Logo chỉnh gọn nhỏ lại -->
          <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 group">
            <div class="w-10 h-10 sm:w-11 sm:h-11 rounded-lg border border-slate-200 bg-white p-0.5 flex items-center justify-center overflow-hidden shadow-xs shrink-0">
              <img 
                src="https://lh3.googleusercontent.com/d/1aqth1Q9LiMr-ENw135ygs9CA04IpGUoY" 
                data-drive-id="1aqth1Q9LiMr-ENw135ygs9CA04IpGUoY"
                alt="Logo V&K Travel Agency" 
                class="w-full h-full object-contain"
                onerror="handleDriveImgError(this, 'VK LOGO')"
              >
            </div>
            <div class="leading-tight">
              <div class="text-xs sm:text-sm font-extrabold text-[#0b3d78] tracking-tight">V&K TRAVEL AGENCY</div>
              <div class="text-[10px] sm:text-[11px] font-semibold text-amber-600">vktravel.com • Xe 4-7-16 Chỗ</div>
            </div>
          </a>

          <!-- Danh mục trên máy tính: chữ nhỏ gọn, viết liền không xuống dòng tên danh mục -->
          <nav class="hidden lg:flex flex-wrap items-center justify-end gap-x-1 gap-y-1 flex-1 pl-2">
            <a href="#trang-chu" class="nav-cat-item px-2 py-1.5 rounded text-[#0b3d78] bg-blue-50">Trang chủ</a>
            <a href="#gioi-thieu" class="nav-cat-item px-2 py-1.5 rounded text-slate-700 hover:text-[#0b3d78] hover:bg-slate-100">Giới thiệu</a>
            
            <!-- Dropdown Thuê xe Đà Nẵng (giống web mẫu) -->
            <div class="has-dropdown">
              <a href="#tuyen-da-nang" class="nav-cat-item px-2 py-1.5 rounded text-slate-700 hover:text-[#0b3d78] hover:bg-slate-100">
                Thuê xe Đà Nẵng <i class="fa-solid fa-chevron-down text-[9px] ml-1"></i>
              </a>
              <div class="sub-menu">
                <a href="#tuyen-da-nang" onclick="filterCategory('da-nang')">Xe từ Đà Nẵng đi Hội An</a>
                <a href="#tuyen-da-nang" onclick="filterCategory('da-nang')">Xe từ Đà Nẵng đi Bà Nà Hills</a>
                <a href="#tuyen-da-nang" onclick="filterCategory('da-nang')">Xe từ Đà Nẵng đi VinWonders</a>
                <a href="#tuyen-da-nang" onclick="filterCategory('da-nang')">Xe từ Đà Nẵng đi Cố đô Huế</a>
                <a href="#tuyen-da-nang" onclick="filterCategory('da-nang')">Xe Đà Nẵng đi Tam Kỳ, Chu Lai</a>
                <a href="#tuyen-da-nang" onclick="filterCategory('da-nang')">Xe Đà Nẵng đi Quảng Ngãi</a>
                <a href="#tuyen-da-nang" onclick="filterCategory('da-nang')">Xe Đà Nẵng đi Quy Nhơn</a>
              </div>
            </div>

            <!-- Dropdown Thuê xe Hội An (giống web mẫu) -->
            <div class="has-dropdown">
              <a href="#tuyen-da-nang" class="nav-cat-item px-2 py-1.5 rounded text-slate-700 hover:text-[#0b3d78] hover:bg-slate-100">
                Thuê xe Hội An <i class="fa-solid fa-chevron-down text-[9px] ml-1"></i>
              </a>
              <div class="sub-menu">
                <a href="#tuyen-da-nang" onclick="filterCategory('hoi-an')">Xe từ Hội An đi Đà Nẵng</a>
                <a href="#tuyen-da-nang" onclick="filterCategory('hoi-an')">Xe từ Hội An đi Bà Nà Hills</a>
                <a href="#tuyen-da-nang" onclick="filterCategory('hoi-an')">Xe từ Hội An đi VinWonders</a>
                <a href="#tuyen-da-nang" onclick="filterCategory('hoi-an')">Xe từ Hội An đi Cố đô Huế</a>
                <a href="#tuyen-da-nang" onclick="filterCategory('hoi-an')">Xe Hội An đi Mỹ Sơn</a>
                <a href="#tuyen-da-nang" onclick="filterCategory('hoi-an')">Xe Hội An đi Tam Kỳ, Chu Lai</a>
                <a href="#tuyen-da-nang" onclick="filterCategory('hoi-an')">Xe Hội An đi Quảng Ngãi</a>
                <a href="#tuyen-da-nang" onclick="filterCategory('hoi-an')">Xe Hội An đi Quy Nhơn</a>
              </div>
            </div>

            <a href="#doi-xe-thuc-te" class="nav-cat-item px-2 py-1.5 rounded text-slate-700 hover:text-[#0b3d78] hover:bg-slate-100">Thuê xe Du lịch</a>
            <a href="#bang-gia-chi-tiet" class="nav-cat-item px-2 py-1.5 rounded text-slate-700 hover:text-[#0b3d78] hover:bg-slate-100">Bảng giá</a>
            <a href="#form-bao-gia" class="nav-cat-item px-2 py-1.5 rounded text-slate-700 hover:text-[#0b3d78] hover:bg-slate-100">Đặt xe & Báo giá</a>
            <a href="#bai-viet-kinh-nghiem" class="nav-cat-item px-2 py-1.5 rounded text-slate-700 hover:text-[#0b3d78] hover:bg-slate-100">Kinh nghiệm</a>
            <a href="#doi-tac" class="nav-cat-item px-2 py-1.5 rounded text-slate-700 hover:text-[#0b3d78] hover:bg-slate-100">Đối tác</a>
            <a href="#lien-he-map" class="nav-cat-item px-2 py-1.5 rounded text-slate-700 hover:text-[#0b3d78] hover:bg-slate-100">Liên hệ</a>
          </nav>

          <!-- Nút mở menu trên điện thoại -->
          <button id="mobile-menu-btn" onclick="toggleMobileMenu()" class="lg:hidden p-2 rounded-lg border border-slate-200 text-[#0b3d78] hover:bg-slate-100 shrink-0" aria-label="Menu">
            <i class="fa-solid fa-bars text-lg"></i>
          </button>
        </div>
      </div>

      <!-- Menu danh mục trên điện thoại -->
      <div id="mobile-menu-drawer" class="hidden lg:hidden bg-white border-b border-slate-200 shadow-lg">
        <div class="flatsome-container py-3 grid grid-cols-2 gap-1.5 text-xs font-semibold">
          <a href="#trang-chu" onclick="toggleMobileMenu()" class="px-3 py-2 rounded bg-blue-50 text-[#0b3d78]">Trang chủ</a>
          <a href="#gioi-thieu" onclick="toggleMobileMenu()" class="px-3 py-2 rounded bg-slate-50 text-slate-700">Giới thiệu</a>
          <a href="#tuyen-da-nang" onclick="filterCategory('da-nang'); toggleMobileMenu()" class="px-3 py-2 rounded bg-slate-50 text-slate-700">Thuê xe Đà Nẵng</a>
          <a href="#tuyen-da-nang" onclick="filterCategory('hoi-an'); toggleMobileMenu()" class="px-3 py-2 rounded bg-slate-50 text-slate-700">Thuê xe Hội An</a>
          <a href="#doi-xe-thuc-te" onclick="toggleMobileMenu()" class="px-3 py-2 rounded bg-slate-50 text-slate-700">Thuê xe Du lịch</a>
          <a href="#bang-gia-chi-tiet" onclick="toggleMobileMenu()" class="px-3 py-2 rounded bg-slate-50 text-slate-700">Bảng giá trọn gói</a>
          <a href="#form-bao-gia" onclick="toggleMobileMenu()" class="px-3 py-2 rounded bg-slate-50 text-slate-700">Form Báo giá</a>
          <a href="#bai-viet-kinh-nghiem" onclick="toggleMobileMenu()" class="px-3 py-2 rounded bg-slate-50 text-slate-700">Bài viết kinh nghiệm</a>
          <a href="#doi-tac" onclick="toggleMobileMenu()" class="px-3 py-2 rounded bg-slate-50 text-slate-700">Đối tác</a>
          <a href="#lien-he-map" onclick="toggleMobileMenu()" class="px-3 py-2 rounded bg-slate-50 text-slate-700">Bản đồ & Fanpage</a>
        </div>
      </div>
    </header>

    <!-- ================= MAIN CONTENT (FLATSOME MAIN) ================= -->
    <main id="main" class="w-full">

      <!-- SECTION 1: SLIDER 2 BANNER TỰ TRƯỢT KÍCH THƯỚC BẰNG NHAU (THIẾT KẾ RIÊNG CHO MÁY TÍNH & ĐIỆN THOẠI) -->
      <section id="trang-chu" class="py-2.5 sm:py-3">
        <div class="flatsome-container">
          
          <!-- ===== BANNER MÁY TÍNH (Chỉ hiển thị trên màn hình >= 768px) ===== -->
          <div class="hidden md:block relative rounded-xl overflow-hidden shadow-md bg-[#0b3d78]">
            <div id="desktop-slider" class="relative w-full desktop-banner-slide">
              
              <!-- Slide 1 Máy tính -->
              <div class="desktop-slide absolute inset-0 transition-opacity duration-700 opacity-100 z-10 flex items-center">
                <img 
                  src="https://lh3.googleusercontent.com/d/1foYiiDIwHVYSsQ_pxyXizPoW1GNfIrWI" 
                  data-drive-id="1foYiiDIwHVYSsQ_pxyXizPoW1GNfIrWI"
                  alt="Banner V&K Travel 1" 
                  class="absolute inset-0 w-full h-full object-cover object-center"
                  onerror="handleDriveImgError(this, 'Banner 1')"
                >
                <div class="absolute inset-0 bg-gradient-to-r from-[#07264d]/95 via-[#0b3d78]/85 to-[#0b3d78]/40"></div>
                
                <!-- Nội dung chữ chỉnh nhỏ gọn nằm hoàn toàn bên trong ảnh banner -->
                <div class="relative z-20 w-full px-12 py-6 flex items-center justify-between gap-6">
                  <div class="max-w-xl text-white space-y-2.5">
                    <div class="inline-block bg-amber-500 text-slate-950 text-xs font-bold px-3 py-1 rounded">
                      VKTRAVEL.COM • CÔNG TY TNHH V&K TRAVEL AGENCY
                    </div>
                    <h1 class="text-xl lg:text-2xl font-extrabold leading-snug text-white">
                      CHUYÊN XE DU LỊCH ĐÀ NẴNG - HỘI AN 4 - 7 - 16 CHỖ ĐỜI MỚI
                    </h1>
                    <p class="text-xs lg:text-sm text-blue-100 leading-relaxed">
                      • Hỗ trợ xuất hóa đơn VAT công ty nhanh chóng, hợp lệ<br>
                      • Miễn phí 100% vé ra vào Cảng hàng không Quốc tế Đà Nẵng<br>
                      • Đón tiễn tận nơi 24/7 tại Sân bay, Khách sạn, Resort – Giá trọn gói từ 200.000đ
                    </p>
                    <div class="pt-1 flex items-center gap-3">
                      <a href="#form-bao-gia" class="bg-amber-500 hover:bg-amber-600 text-slate-950 font-bold text-xs px-4 py-2 rounded-lg shadow transition">
                        NHẬN BÁO GIÁ NGAY
                      </a>
                      <a href="tel:0905920638" class="bg-white/15 hover:bg-white/25 border border-white/40 text-white font-semibold text-xs px-4 py-2 rounded-lg transition">
                        HOTLINE: 0905 92 0638
                      </a>
                    </div>
                  </div>

                  <!-- Khung thông tin nhanh bên phải trong banner máy tính -->
                  <div class="bg-white/95 text-slate-800 p-4 rounded-xl shadow-lg w-72 shrink-0 border-t-4 border-amber-500">
                    <div class="text-xs font-extrabold text-[#0b3d78] uppercase border-b pb-1.5 mb-2">
                      Bảng Giá Đà Nẵng - Hội An
                    </div>
                    <ul class="space-y-1.5 text-xs">
                      <li class="flex justify-between"><span>Xe 4 Chỗ Sedan:</span><strong class="text-red-600">230.000đ</strong></li>
                      <li class="flex justify-between"><span>Xe 7 Chỗ SUV/MPV:</span><strong class="text-red-600">280.000đ</strong></li>
                      <li class="flex justify-between"><span>Xe 16 Chỗ Du Lịch:</span><strong class="text-red-600">450.000đ</strong></li>
                    </ul>
                    <div class="mt-2.5 pt-2 border-t text-[11px] text-slate-600 font-medium">
                      <i class="fa-solid fa-circle-check text-emerald-600 mr-1"></i>Đã bao gồm phí sân bay & cầu đường
                    </div>
                  </div>
                </div>
              </div>

              <!-- Slide 2 Máy tính (Kích thước bằng nhau 100%) -->
              <div class="desktop-slide absolute inset-0 transition-opacity duration-700 opacity-0 z-0 flex items-center">
                <img 
                  src="https://lh3.googleusercontent.com/d/1xdoUJRbykW5DQTjXXsTZQgbTnn_0TJmY" 
                  data-drive-id="1xdoUJRbykW5DQTjXXsTZQgbTnn_0TJmY"
                  alt="Banner V&K Travel 2" 
                  class="absolute inset-0 w-full h-full object-cover object-center"
                  onerror="handleDriveImgError(this, 'Banner 2')"
                >
                <div class="absolute inset-0 bg-gradient-to-r from-[#062b59]/95 via-[#0b3d78]/85 to-[#0b3d78]/45"></div>
                
                <div class="relative z-20 w-full px-12 py-6 flex items-center justify-between gap-6">
                  <div class="max-w-xl text-white space-y-2.5">
                    <div class="inline-block bg-sky-400 text-slate-950 text-xs font-bold px-3 py-1 rounded">
                      DỊCH VỤ XE RIÊNG ĐỜI MỚI • KHÔNG GẮN BIỂN TAXI
                    </div>
                    <h2 class="text-xl lg:text-2xl font-extrabold leading-snug text-white">
                      ĐẶT XE ĐI BÀ NÀ HILLS - VINWONDERS - HUẾ - MỸ SƠN - CHU LAI
                    </h2>
                    <p class="text-xs lg:text-sm text-blue-100 leading-relaxed">
                      • Phục vụ khách lẻ, gia đình, đoàn công tác, hội nghị chuyên nghiệp<br>
                      • Hợp đồng rõ ràng, hỗ trợ xuất VAT công ty theo yêu cầu<br>
                      • Địa chỉ: 29 Cao Sơn Pháo, Phường Điện Bàn, TP Đà Nẵng
                    </p>
                    <div class="pt-1 flex items-center gap-3">
                      <a href="#tuyen-da-nang" class="bg-amber-500 hover:bg-amber-600 text-slate-950 font-bold text-xs px-4 py-2 rounded-lg shadow transition">
                        XEM CÁC TUYẾN XE
                      </a>
                      <a href="https://zalo.me/0905920638" target="_blank" rel="noopener noreferrer" class="bg-white/15 hover:bg-white/25 border border-white/40 text-white font-semibold text-xs px-4 py-2 rounded-lg transition">
                        ZALO: 0905 92 0638
                      </a>
                    </div>
                  </div>

                  <div class="bg-white/95 text-slate-800 p-4 rounded-xl shadow-lg w-72 shrink-0 border-t-4 border-sky-500">
                    <div class="text-xs font-extrabold text-[#0b3d78] uppercase border-b pb-1.5 mb-2">
                      Cam Kết Từ V&K Travel
                    </div>
                    <ul class="space-y-1.5 text-xs text-slate-700">
                      <li><i class="fa-solid fa-check text-emerald-600 mr-1.5"></i>Miễn phí vé ra vào sân bay</li>
                      <li><i class="fa-solid fa-check text-emerald-600 mr-1.5"></i>Hỗ trợ xuất hóa đơn VAT</li>
                      <li><i class="fa-solid fa-check text-emerald-600 mr-1.5"></i>Tài xế lịch sự, đón đúng giờ</li>
                    </ul>
                    <div class="mt-2.5 pt-2 border-t text-[11px] font-bold text-[#0b3d78]">
                      Đặt xe nhanh: 0905 92 0638
                    </div>
                  </div>
                </div>
              </div>

              <!-- Nút điều hướng Slider Máy tính -->
              <button onclick="changeSlide(-1)" class="absolute left-3 top-1/2 -translate-y-1/2 z-30 w-8 h-8 rounded-full bg-black/40 hover:bg-black/60 text-white flex items-center justify-center" aria-label="Slide trước">
                <i class="fa-solid fa-chevron-left text-xs"></i>
              </button>
              <button onclick="changeSlide(1)" class="absolute right-3 top-1/2 -translate-y-1/2 z-30 w-8 h-8 rounded-full bg-black/40 hover:bg-black/60 text-white flex items-center justify-center" aria-label="Slide tiếp">
                <i class="fa-solid fa-chevron-right text-xs"></i>
              </button>
            </div>
          </div>

          <!-- ===== BANNER ĐIỆN THOẠI THIẾT KẾ MỚI RIÊNG BIỆT (Chỉ hiển thị trên màn hình < 768px) ===== -->
          <!-- Tối ưu chữ nhỏ gọn nằm hết bên trong ảnh banner, không tràn viền -->
          <div class="block md:hidden relative rounded-xl overflow-hidden shadow-md bg-[#0b3d78]">
            <div id="mobile-slider" class="relative w-full mobile-banner-slide">
              
              <!-- Slide 1 Điện thoại -->
              <div class="mobile-slide absolute inset-0 transition-opacity duration-700 opacity-100 z-10 flex items-center justify-center">
                <img 
                  src="https://lh3.googleusercontent.com/d/1foYiiDIwHVYSsQ_pxyXizPoW1GNfIrWI" 
                  data-drive-id="1foYiiDIwHVYSsQ_pxyXizPoW1GNfIrWI"
                  alt="Mobile Banner 1" 
                  class="absolute inset-0 w-full h-full object-cover object-center"
                  onerror="handleDriveImgError(this, 'Mobile Banner 1')"
                >
                <div class="absolute inset-0 bg-[#07264d]/85"></div>
                
                <!-- Khung chữ điện thoại căn gọn bên trong, cách viền an toàn -->
                <div class="relative z-20 w-full px-5 py-3 text-center text-white space-y-1.5">
                  <div class="inline-block bg-amber-500 text-slate-950 text-[10px] font-extrabold px-2.5 py-0.5 rounded">
                    CÔNG TY TNHH V&K TRAVEL AGENCY
                  </div>
                  <h2 class="text-sm font-extrabold leading-snug text-white">
                    XE DU LỊCH ĐÀ NẴNG - HỘI AN 4-7-16 CHỖ
                  </h2>
                  <p class="text-[11px] text-blue-100 leading-tight">
                    Miễn phí vé ra vào sân bay • Hỗ trợ xuất VAT công ty<br>
                    4 chỗ: 230k | 7 chỗ: 280k | 16 chỗ: 450k
                  </p>
                  <div class="pt-1 flex items-center justify-center gap-2">
                    <a href="#form-bao-gia" class="bg-amber-500 text-slate-950 font-bold text-[11px] px-3 py-1.5 rounded">
                      Đặt Xe Ngay
                    </a>
                    <a href="tel:0905920638" class="bg-white/20 border border-white/40 text-white font-bold text-[11px] px-3 py-1.5 rounded">
                      0905 92 0638
                    </a>
                  </div>
                </div>
              </div>

              <!-- Slide 2 Điện thoại (Kích thước bằng nhau) -->
              <div class="mobile-slide absolute inset-0 transition-opacity duration-700 opacity-0 z-0 flex items-center justify-center">
                <img 
                  src="https://lh3.googleusercontent.com/d/1xdoUJRbykW5DQTjXXsTZQgbTnn_0TJmY" 
                  data-drive-id="1xdoUJRbykW5DQTjXXsTZQgbTnn_0TJmY"
                  alt="Mobile Banner 2" 
                  class="absolute inset-0 w-full h-full object-cover object-center"
                  onerror="handleDriveImgError(this, 'Mobile Banner 2')"
                >
                <div class="absolute inset-0 bg-[#062b59]/85"></div>
                
                <div class="relative z-20 w-full px-5 py-3 text-center text-white space-y-1.5">
                  <div class="inline-block bg-sky-400 text-slate-950 text-[10px] font-extrabold px-2.5 py-0.5 rounded">
                    VKTRAVEL.COM • XE RIÊNG ĐỜI MỚI 24/7
                  </div>
                  <h2 class="text-sm font-extrabold leading-snug text-white">
                    ĐÀ NẴNG - HỘI AN - BÀ NÀ - HUẾ - CHU LAI
                  </h2>
                  <p class="text-[11px] text-blue-100 leading-tight">
                    Đón đúng giờ • Giá trọn gói • Không phát sinh chi phí<br>
                    ĐC: 29 Cao Sơn Pháo, P. Điện Bàn, TP Đà Nẵng
                  </p>
                  <div class="pt-1 flex items-center justify-center gap-2">
                    <a href="#tuyen-da-nang" class="bg-amber-500 text-slate-950 font-bold text-[11px] px-3 py-1.5 rounded">
                      Xem Bảng Giá
                    </a>
                    <a href="https://zalo.me/0905920638" target="_blank" rel="noopener noreferrer" class="bg-white/20 border border-white/40 text-white font-bold text-[11px] px-3 py-1.5 rounded">
                      Chat Zalo
                    </a>
                  </div>
                </div>
              </div>

            </div>
          </div>

          <!-- Chấm chỉ báo Slide (Dùng chung cho cả máy tính & điện thoại) -->
          <div class="flex items-center justify-center gap-2 mt-2">
            <button onclick="goToSlide(0)" id="dot-0" class="w-6 h-2 rounded-full bg-[#0b3d78] transition-all" aria-label="Slide 1"></button>
            <button onclick="goToSlide(1)" id="dot-1" class="w-2.5 h-2 rounded-full bg-slate-300 transition-all" aria-label="Slide 2"></button>
          </div>

        </div>
      </section>

      <!-- SECTION 2: THANH DANH MỤC TRANG CHỦ NHỎ GỌN (TỐI ƯU ĐẸP TRÊN MÁY TÍNH & ĐIỆN THOẠI) -->
      <!-- Trên máy tính: chữ nhỏ gọn, tên danh mục viết liền trên 1 hàng không xuống dòng lẻ -->
      <section class="py-2">
        <div class="flatsome-container">
          <div class="bg-white rounded-xl border border-slate-200 p-2.5 shadow-xs">
            <div class="text-[11px] font-bold text-slate-500 uppercase tracking-wider mb-2 text-center sm:text-left">
              <i class="fa-solid fa-layer-group text-[#0b3d78] mr-1"></i>Danh mục dịch vụ xe du lịch V&K Travel
            </div>
            <!-- Desktop: nằm trên 1 hàng hoặc xuống hàng 2 nguyên cụm, không bao giờ gãy chữ trong tên danh mục -->
            <!-- Mobile: chia 2 cột gọn đẹp -->
            <div class="grid grid-cols-2 sm:flex sm:flex-wrap items-center justify-start gap-1.5">
              <button onclick="filterCategory('all')" id="cat-btn-all" class="home-cat-pill bg-[#0b3d78] text-white border border-[#0b3d78]">
                <i class="fa-solid fa-grip text-[10px]"></i>Tất cả tuyến xe
              </button>
              <button onclick="filterCategory('da-nang')" id="cat-btn-da-nang" class="home-cat-pill bg-slate-50 hover:bg-blue-50 text-slate-700 border border-slate-200">
                <i class="fa-solid fa-plane-arrival text-[10px] text-[#0b3d78]"></i>Thuê xe Đà Nẵng
              </button>
              <button onclick="filterCategory('hoi-an')" id="cat-btn-hoi-an" class="home-cat-pill bg-slate-50 hover:bg-blue-50 text-slate-700 border border-slate-200">
                <i class="fa-solid fa-lantern text-[10px] text-amber-600"></i>Thuê xe Hội An
              </button>
              <button onclick="filterCategory('xe-4-cho')" id="cat-btn-xe-4-cho" class="home-cat-pill bg-slate-50 hover:bg-blue-50 text-slate-700 border border-slate-200">
                <i class="fa-solid fa-car-side text-[10px] text-[#0b3d78]"></i>Xe 4 chỗ Sedan
              </button>
              <button onclick="filterCategory('xe-7-cho')" id="cat-btn-xe-7-cho" class="home-cat-pill bg-slate-50 hover:bg-blue-50 text-slate-700 border border-slate-200">
                <i class="fa-solid fa-van-shuttle text-[10px] text-[#0b3d78]"></i>Xe 7 chỗ SUV
              </button>
              <button onclick="filterCategory('xe-16-cho')" id="cat-btn-xe-16-cho" class="home-cat-pill bg-slate-50 hover:bg-blue-50 text-slate-700 border border-slate-200">
                <i class="fa-solid fa-bus-simple text-[10px] text-[#0b3d78]"></i>Xe 16 chỗ Du lịch
              </button>
              <a href="#doi-xe-thuc-te" class="home-cat-pill bg-slate-50 hover:bg-blue-50 text-slate-700 border border-slate-200">
                <i class="fa-solid fa-camera text-[10px] text-emerald-600"></i>Ảnh xe thực tế
              </a>
              <a href="#form-bao-gia" class="home-cat-pill bg-amber-50 hover:bg-amber-100 text-amber-900 border border-amber-300">
                <i class="fa-solid fa-file-invoice-dollar text-[10px] text-amber-600"></i>Báo giá & Xuất VAT
              </a>
            </div>
          </div>
        </div>
      </section>

      <!-- SECTION 3: CAM KẾT DỊCH VỤ (FLATSOME 4 ICON BOXES) -->
      <section id="gioi-thieu" class="py-2.5">
        <div class="flatsome-container">
          <div class="grid grid-cols-2 lg:grid-cols-4 gap-2.5">
            <div class="bg-white p-3 rounded-xl border border-slate-200 flex items-start gap-2.5">
              <div class="w-9 h-9 rounded-lg bg-blue-50 text-[#0b3d78] flex items-center justify-center shrink-0">
                <i class="fa-solid fa-ticket-simple text-base"></i>
              </div>
              <div>
                <h3 class="text-xs sm:text-sm font-bold text-slate-800">Miễn Phí Vé Sân Bay</h3>
                <p class="text-[11px] text-slate-600 mt-0.5">Miễn phí 100% vé ra vào sân bay Đà Nẵng khi đặt xe đón tiễn.</p>
              </div>
            </div>
            <div class="bg-white p-3 rounded-xl border border-slate-200 flex items-start gap-2.5">
              <div class="w-9 h-9 rounded-lg bg-amber-50 text-amber-600 flex items-center justify-center shrink-0">
                <i class="fa-solid fa-file-invoice text-base"></i>
              </div>
              <div>
                <h3 class="text-xs sm:text-sm font-bold text-slate-800">Hỗ Trợ Xuất VAT Công Ty</h3>
                <p class="text-[11px] text-slate-600 mt-0.5">Hợp đồng vận chuyển đầy đủ, xuất hóa đơn điện tử VAT nhanh chóng.</p>
              </div>
            </div>
            <div class="bg-white p-3 rounded-xl border border-slate-200 flex items-start gap-2.5">
              <div class="w-9 h-9 rounded-lg bg-emerald-50 text-emerald-600 flex items-center justify-center shrink-0">
                <i class="fa-solid fa-car-Rear text-base"></i>
              </div>
              <div>
                <h3 class="text-xs sm:text-sm font-bold text-slate-800">Xe 4-7-16 Chỗ Đời Mới</h3>
                <p class="text-[11px] text-slate-600 mt-0.5">Xe riêng gia đình sạch sẽ, không gắn mào taxi, điều hòa mát lạnh.</p>
              </div>
            </div>
            <div class="bg-white p-3 rounded-xl border border-slate-200 flex items-start gap-2.5">
              <div class="w-9 h-9 rounded-lg bg-purple-50 text-purple-600 flex items-center justify-center shrink-0">
                <i class="fa-solid fa-clock-rotate-left text-base"></i>
              </div>
              <div>
                <h3 class="text-xs sm:text-sm font-bold text-slate-800">Giá Trọn Gói Rẻ Nhất</h3>
                <p class="text-[11px] text-slate-600 mt-0.5">Cam kết đúng giá niêm yết, phục vụ 24/7 kể cả chuyến đêm muộn.</p>
              </div>
            </div>
          </div>
        </div>
      </section>

      <!-- SECTION 4: DANH MỤC SẢN PHẨM / TUYẾN XE (GIỐNG WEB MẪU XEDANANGHOIANGIARE.COM) -->
      <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính. Không có nhãn dán. Tên sản phẩm đầy đủ không tràn viền -->
      <section id="tuyen-da-nang" class="py-4">
        <div class="flatsome-container">
          
          <div class="flex flex-col sm:flex-row sm:items-end justify-between mb-3 pb-2 border-b-2 border-[#0b3d78] gap-1">
            <div>
              <h2 class="text-base sm:text-lg font-extrabold text-[#0b3d78] uppercase">
                ĐẶT XE GIÁ RẺ ĐÀ NẴNG – HỘI AN – BÀ NÀ – HUẾ
              </h2>
              <p class="text-xs text-slate-600">
                Giá trọn gói 1 chiều & khứ hồi • Miễn phí vé ra vào sân bay • Hỗ trợ xuất VAT công ty
              </p>
            </div>
            <div class="text-xs font-bold text-amber-700">
              Hotline đặt xe: <a href="tel:0905920638" class="underline">0905 92 0638</a>
            </div>
          </div>

          <!-- Grid sản phẩm: 2 cột trên điện thoại (grid-cols-2), 3 cột tablet, 4 cột máy tính -->
          <div id="product-grid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 sm:gap-4">
            
            <!-- Sản phẩm 1: Đà Nẵng - Hội An (Ảnh thực tế 1) -->
            <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-xs flex flex-col justify-between" data-category="da-nang hoi-an xe-4-cho xe-7-cho xe-16-cho">
              <div>
                <div class="w-full aspect-4/3 bg-slate-100 overflow-hidden">
                  <img 
                    src="https://lh3.googleusercontent.com/d/1foYiiDIwHVYSsQ_pxyXizPoW1GNfIrWI" 
                    data-drive-id="1foYiiDIwHVYSsQ_pxyXizPoW1GNfIrWI"
                    alt="Xe Đà Nẵng đi Hội An" 
                    class="w-full h-full object-cover hover:scale-105 transition duration-300"
                    onerror="handleDriveImgError(this, 'Xe Đà Nẵng - Hội An')"
                  >
                </div>
                <div class="p-2.5 sm:p-3.5">
                  <h3 class="product-title-full text-xs sm:text-sm font-extrabold text-[#0b3d78] mb-1.5">
                    Xe Đà Nẵng – Hội An (Đón Sân Bay / Khách Sạn)
                  </h3>
                  <div class="space-y-1 text-[11px] sm:text-xs text-slate-700 border-t border-slate-100 pt-1.5">
                    <div class="flex justify-between"><span>Xe 4 chỗ 1 chiều:</span><strong class="text-red-600">230.000đ</strong></div>
                    <div class="flex justify-between"><span>Xe 7 chỗ 1 chiều:</span><strong class="text-red-600">280.000đ</strong></div>
                    <div class="flex justify-between"><span>Xe 16 chỗ 1 chiều:</span><strong class="text-red-600">450.000đ</strong></div>
                  </div>
                </div>
              </div>
              <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1">
                <button onclick="selectRouteForQuote('Đà Nẵng – Hội An')" class="w-full bg-[#0b3d78] hover:bg-amber-500 hover:text-slate-950 text-white font-bold text-[11px] sm:text-xs py-2 rounded-lg transition">
                  Đặt xe ngay
                </button>
              </div>
            </div>

            <!-- Sản phẩm 2: Hội An - Đà Nẵng (Ảnh thực tế 2) -->
            <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-xs flex flex-col justify-between" data-category="hoi-an da-nang xe-4-cho xe-7-cho xe-16-cho">
              <div>
                <div class="w-full aspect-4/3 bg-slate-100 overflow-hidden">
                  <img 
                    src="https://lh3.googleusercontent.com/d/1J0-9ejOjVO4E7Sm8Z9X9Lj0qwnUjr7jL" 
                    data-drive-id="1J0-9ejOjVO4E7Sm8Z9X9Lj0qwnUjr7jL"
                    alt="Xe Hội An đi Sân bay Đà Nẵng" 
                    class="w-full h-full object-cover hover:scale-105 transition duration-300"
                    onerror="handleDriveImgError(this, 'Xe Hội An - Đà Nẵng')"
                  >
                </div>
                <div class="p-2.5 sm:p-3.5">
                  <h3 class="product-title-full text-xs sm:text-sm font-extrabold text-[#0b3d78] mb-1.5">
                    Xe Hội An – Sân Bay Đà Nẵng (Miễn Vé Sân Bay)
                  </h3>
                  <div class="space-y-1 text-[11px] sm:text-xs text-slate-700 border-t border-slate-100 pt-1.5">
                    <div class="flex justify-between"><span>Xe 4 chỗ 1 chiều:</span><strong class="text-red-600">230.000đ</strong></div>
                    <div class="flex justify-between"><span>Xe 7 chỗ 1 chiều:</span><strong class="text-red-600">280.000đ</strong></div>
                    <div class="flex justify-between"><span>Xe 16 chỗ 1 chiều:</span><strong class="text-red-600">450.000đ</strong></div>
                  </div>
                </div>
              </div>
              <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1">
                <button onclick="selectRouteForQuote('Hội An – Sân Bay Đà Nẵng')" class="w-full bg-[#0b3d78] hover:bg-amber-500 hover:text-slate-950 text-white font-bold text-[11px] sm:text-xs py-2 rounded-lg transition">
                  Đặt xe ngay
                </button>
              </div>
            </div>

            <!-- Sản phẩm 3: Đà Nẵng - Bà Nà Hills (Ảnh thực tế 3) -->
            <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-xs flex flex-col justify-between" data-category="da-nang xe-4-cho xe-7-cho xe-16-cho">
              <div>
                <div class="w-full aspect-4/3 bg-slate-100 overflow-hidden">
                  <img 
                    src="https://lh3.googleusercontent.com/d/1xdoUJRbykW5DQTjXXsTZQgbTnn_0TJmY" 
                    data-drive-id="1xdoUJRbykW5DQTjXXsTZQgbTnn_0TJmY"
                    alt="Xe Đà Nẵng đi Bà Nà Hills" 
                    class="w-full h-full object-cover hover:scale-105 transition duration-300"
                    onerror="handleDriveImgError(this, 'Đà Nẵng - Bà Nà Hills')"
                  >
                </div>
                <div class="p-2.5 sm:p-3.5">
                  <h3 class="product-title-full text-xs sm:text-sm font-extrabold text-[#0b3d78] mb-1.5">
                    Xe Đà Nẵng – Bà Nà Hills (1 Chiều & 2 Chiều)
                  </h3>
                  <div class="space-y-1 text-[11px] sm:text-xs text-slate-700 border-t border-slate-100 pt-1.5">
                    <div class="flex justify-between"><span>4 chỗ (1C / 2C):</span><strong class="text-red-600">300k / 600k</strong></div>
                    <div class="flex justify-between"><span>7 chỗ (1C / 2C):</span><strong class="text-red-600">350k / 700k</strong></div>
                    <div class="flex justify-between"><span>16 chỗ (1C / 2C):</span><strong class="text-red-600">550k / 1.000k</strong></div>
                  </div>
                </div>
              </div>
              <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1">
                <button onclick="selectRouteForQuote('Đà Nẵng – Bà Nà Hills')" class="w-full bg-[#0b3d78] hover:bg-amber-500 hover:text-slate-950 text-white font-bold text-[11px] sm:text-xs py-2 rounded-lg transition">
                  Đặt xe ngay
                </button>
              </div>
            </div>

            <!-- Sản phẩm 4: Hội An - Bà Nà Hills (Ảnh thực tế 4) -->
            <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-xs flex flex-col justify-between" data-category="hoi-an xe-4-cho xe-7-cho xe-16-cho">
              <div>
                <div class="w-full aspect-4/3 bg-slate-100 overflow-hidden">
                  <img 
                    src="https://lh3.googleusercontent.com/d/1ywg46EA_TzDTRe4B8NU-HWCudA4LjANj" 
                    data-drive-id="1ywg46EA_TzDTRe4B8NU-HWCudA4LjANj"
                    alt="Xe Hội An đi Bà Nà Hills" 
                    class="w-full h-full object-cover hover:scale-105 transition duration-300"
                    onerror="handleDriveImgError(this, 'Hội An - Bà Nà Hills')"
                  >
                </div>
                <div class="p-2.5 sm:p-3.5">
                  <h3 class="product-title-full text-xs sm:text-sm font-extrabold text-[#0b3d78] mb-1.5">
                    Xe Hội An – Bà Nà Hills (Đón Tận Khách Sạn)
                  </h3>
                  <div class="space-y-1 text-[11px] sm:text-xs text-slate-700 border-t border-slate-100 pt-1.5">
                    <div class="flex justify-between"><span>4 chỗ (1C / 2C):</span><strong class="text-red-600">500k / 900k</strong></div>
                    <div class="flex justify-between"><span>7 chỗ (1C / 2C):</span><strong class="text-red-600">600k / 1.000k</strong></div>
                    <div class="flex justify-between"><span>16 chỗ (1C / 2C):</span><strong class="text-red-600">800k / 1.400k</strong></div>
                  </div>
                </div>
              </div>
              <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1">
                <button onclick="selectRouteForQuote('Hội An – Bà Nà Hills')" class="w-full bg-[#0b3d78] hover:bg-amber-500 hover:text-slate-950 text-white font-bold text-[11px] sm:text-xs py-2 rounded-lg transition">
                  Đặt xe ngay
                </button>
              </div>
            </div>

            <!-- Sản phẩm 5: Hội An - VinWonders Nam Hội An (Ảnh thực tế 5) -->
            <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-xs flex flex-col justify-between" data-category="hoi-an xe-4-cho xe-7-cho xe-16-cho">
              <div>
                <div class="w-full aspect-4/3 bg-slate-100 overflow-hidden">
                  <img 
                    src="https://lh3.googleusercontent.com/d/1Ipn3jLVPY99rqmEhzjten1o39eexE-__" 
                    data-drive-id="1Ipn3jLVPY99rqmEhzjten1o39eexE-__"
                    alt="Xe Hội An đi VinWonders Nam Hội An" 
                    class="w-full h-full object-cover hover:scale-105 transition duration-300"
                    onerror="handleDriveImgError(this, 'Hội An - VinWonders')"
                  >
                </div>
                <div class="p-2.5 sm:p-3.5">
                  <h3 class="product-title-full text-xs sm:text-sm font-extrabold text-[#0b3d78] mb-1.5">
                    Xe Hội An – Vinpearl / VinWonders Nam Hội An
                  </h3>
                  <div class="space-y-1 text-[11px] sm:text-xs text-slate-700 border-t border-slate-100 pt-1.5">
                    <div class="flex justify-between"><span>Xe 4 chỗ 1 chiều:</span><strong class="text-red-600">200.000đ</strong></div>
                    <div class="flex justify-between"><span>Xe 7 chỗ 1 chiều:</span><strong class="text-red-600">250.000đ</strong></div>
                    <div class="flex justify-between"><span>Xe 16 chỗ 1 chiều:</span><strong class="text-red-600">350.000đ</strong></div>
                  </div>
                </div>
              </div>
              <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1">
                <button onclick="selectRouteForQuote('Hội An – VinWonders Nam Hội An')" class="w-full bg-[#0b3d78] hover:bg-amber-500 hover:text-slate-950 text-white font-bold text-[11px] sm:text-xs py-2 rounded-lg transition">
                  Đặt xe ngay
                </button>
              </div>
            </div>

            <!-- Sản phẩm 6: Đà Nẵng - VinWonders Nam Hội An (Ảnh thực tế 1) -->
            <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-xs flex flex-col justify-between" data-category="da-nang xe-4-cho xe-7-cho xe-16-cho">
              <div>
                <div class="w-full aspect-4/3 bg-slate-100 overflow-hidden">
                  <img 
                    src="https://lh3.googleusercontent.com/d/1foYiiDIwHVYSsQ_pxyXizPoW1GNfIrWI" 
                    data-drive-id="1foYiiDIwHVYSsQ_pxyXizPoW1GNfIrWI"
                    alt="Xe Đà Nẵng đi VinWonders Nam Hội An" 
                    class="w-full h-full object-cover hover:scale-105 transition duration-300"
                    onerror="handleDriveImgError(this, 'Đà Nẵng - VinWonders')"
                  >
                </div>
                <div class="p-2.5 sm:p-3.5">
                  <h3 class="product-title-full text-xs sm:text-sm font-extrabold text-[#0b3d78] mb-1.5">
                    Xe Đà Nẵng – Vinpearl / VinWonders Nam Hội An
                  </h3>
                  <div class="space-y-1 text-[11px] sm:text-xs text-slate-700 border-t border-slate-100 pt-1.5">
                    <div class="flex justify-between"><span>Xe 4 chỗ 1 chiều:</span><strong class="text-red-600">400.000đ</strong></div>
                    <div class="flex justify-between"><span>Xe 7 chỗ 1 chiều:</span><strong class="text-red-600">450.000đ</strong></div>
                    <div class="flex justify-between"><span>Xe 16 chỗ 1 chiều:</span><strong class="text-red-600">650.000đ</strong></div>
                  </div>
                </div>
              </div>
              <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1">
                <button onclick="selectRouteForQuote('Đà Nẵng – VinWonders Nam Hội An')" class="w-full bg-[#0b3d78] hover:bg-amber-500 hover:text-slate-950 text-white font-bold text-[11px] sm:text-xs py-2 rounded-lg transition">
                  Đặt xe ngay
                </button>
              </div>
            </div>

            <!-- Sản phẩm 7: Đà Nẵng / Hội An - Cố Đô Huế (Ảnh thực tế 2) -->
            <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-xs flex flex-col justify-between" data-category="da-nang hoi-an xe-4-cho xe-7-cho xe-16-cho">
              <div>
                <div class="w-full aspect-4/3 bg-slate-100 overflow-hidden">
                  <img 
                    src="https://lh3.googleusercontent.com/d/1J0-9ejOjVO4E7Sm8Z9X9Lj0qwnUjr7jL" 
                    data-drive-id="1J0-9ejOjVO4E7Sm8Z9X9Lj0qwnUjr7jL"
                    alt="Xe Đà Nẵng Hội An đi Huế" 
                    class="w-full h-full object-cover hover:scale-105 transition duration-300"
                    onerror="handleDriveImgError(this, 'Đà Nẵng / Hội An - Huế')"
                  >
                </div>
                <div class="p-2.5 sm:p-3.5">
                  <h3 class="product-title-full text-xs sm:text-sm font-extrabold text-[#0b3d78] mb-1.5">
                    Xe Đà Nẵng / Hội An – Cố Đô Huế (1C & 2C)
                  </h3>
                  <div class="space-y-1 text-[11px] sm:text-xs text-slate-700 border-t border-slate-100 pt-1.5">
                    <div class="flex justify-between"><span>4 chỗ (1C / 2C):</span><strong class="text-red-600">1.400k / 2.000k</strong></div>
                    <div class="flex justify-between"><span>7 chỗ (1C / 2C):</span><strong class="text-red-600">1.600k / 2.200k</strong></div>
                    <div class="flex justify-between"><span>16 chỗ (1C / 2C):</span><strong class="text-red-600">2.200k / 2.900k</strong></div>
                  </div>
                </div>
              </div>
              <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1">
                <button onclick="selectRouteForQuote('Đà Nẵng / Hội An – Cố Đô Huế')" class="w-full bg-[#0b3d78] hover:bg-amber-500 hover:text-slate-950 text-white font-bold text-[11px] sm:text-xs py-2 rounded-lg transition">
                  Đặt xe ngay
                </button>
              </div>
            </div>

            <!-- Sản phẩm 8: Đà Nẵng / Hội An - Tam Kỳ, Chu Lai, Quảng Ngãi (Ảnh thực tế 3) -->
            <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-xs flex flex-col justify-between" data-category="da-nang hoi-an xe-4-cho xe-7-cho xe-16-cho">
              <div>
                <div class="w-full aspect-4/3 bg-slate-100 overflow-hidden">
                  <img 
                    src="https://lh3.googleusercontent.com/d/1xdoUJRbykW5DQTjXXsTZQgbTnn_0TJmY" 
                    data-drive-id="1xdoUJRbykW5DQTjXXsTZQgbTnn_0TJmY"
                    alt="Xe đi Tam Kỳ Chu Lai Quảng Ngãi" 
                    class="w-full h-full object-cover hover:scale-105 transition duration-300"
                    onerror="handleDriveImgError(this, 'Tam Kỳ - Chu Lai')"
                  >
                </div>
                <div class="p-2.5 sm:p-3.5">
                  <h3 class="product-title-full text-xs sm:text-sm font-extrabold text-[#0b3d78] mb-1.5">
                    Xe Đi Tam Kỳ – Sân Bay Chu Lai – Quảng Ngãi
                  </h3>
                  <div class="space-y-1 text-[11px] sm:text-xs text-slate-700 border-t border-slate-100 pt-1.5">
                    <div class="flex justify-between"><span>Xe 4 chỗ trọn gói:</span><strong class="text-red-600">Từ 650.000đ</strong></div>
                    <div class="flex justify-between"><span>Xe 7 chỗ trọn gói:</span><strong class="text-red-600">Từ 750.000đ</strong></div>
                    <div class="flex justify-between"><span>Xe 16 chỗ trọn gói:</span><strong class="text-red-600">Từ 1.100.000đ</strong></div>
                  </div>
                </div>
              </div>
              <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1">
                <button onclick="selectRouteForQuote('Đà Nẵng / Hội An – Tam Kỳ / Chu Lai')" class="w-full bg-[#0b3d78] hover:bg-amber-500 hover:text-slate-950 text-white font-bold text-[11px] sm:text-xs py-2 rounded-lg transition">
                  Đặt xe ngay
                </button>
              </div>
            </div>

          </div>
        </div>
      </section>

      <!-- SECTION 5: DỊCH VỤ XE RIÊNG ĐỜI MỚI 4-7-16 CHỖ (5 ẢNH THỰC TẾ TỪ GOOGLE DRIVE) -->
      <!-- Chia 2 cột trên điện thoại, hiển thị đầy đủ 5 ảnh thực tế trong file Google Drive -->
      <section id="doi-xe-thuc-te" class="py-4 bg-white border-y border-slate-200">
        <div class="flatsome-container">
          <div class="mb-3 pb-2 border-b-2 border-[#0b3d78]">
            <h2 class="text-base sm:text-lg font-extrabold text-[#0b3d78] uppercase">
              DỊCH VỤ XE RIÊNG ĐỜI MỚI 4 - 7 - 16 CHỖ (HÌNH ẢNH XE THỰC TẾ)
            </h2>
            <p class="text-xs text-slate-600">
              Cung cấp dịch vụ vận chuyển bằng xe cá nhân đời mới, không gắn biển Taxi • Hỗ trợ xuất hóa đơn VAT công ty
            </p>
          </div>

          <!-- Chia 2 cột trên điện thoại, 5 cột trên máy tính cho 5 ảnh thực tế -->
          <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-2.5 sm:gap-3.5">
            
            <!-- Ảnh thực tế 1 -->
            <div class="bg-slate-50 rounded-xl border border-slate-200 overflow-hidden flex flex-col justify-between">
              <div>
                <div class="w-full aspect-4/3 bg-slate-200 overflow-hidden">
                  <img 
                    src="https://lh3.googleusercontent.com/d/1foYiiDIwHVYSsQ_pxyXizPoW1GNfIrWI" 
                    data-drive-id="1foYiiDIwHVYSsQ_pxyXizPoW1GNfIrWI"
                    alt="Xe 4 Chỗ Sedan V&K Travel" 
                    class="w-full h-full object-cover"
                    onerror="handleDriveImgError(this, 'Xe 4 Chỗ Sedan')"
                  >
                </div>
                <div class="p-2.5">
                  <h3 class="product-title-full text-xs sm:text-sm font-bold text-[#0b3d78]">
                    Xe Du Lịch 4 Chỗ Sedan Đời Mới
                  </h3>
                  <p class="text-[11px] text-slate-600 mt-1">
                    Đà Nẵng – Hội An: <strong class="text-red-600">230.000đ</strong> (1 chiều). Miễn phí vé sân bay.
                  </p>
                </div>
              </div>
              <div class="p-2.5 pt-0">
                <a href="tel:0905920638" class="block text-center bg-amber-500 hover:bg-amber-600 text-slate-950 font-bold text-[11px] py-1.5 rounded">
                  Gọi 0905 92 0638
                </a>
              </div>
            </div>

            <!-- Ảnh thực tế 2 -->
            <div class="bg-slate-50 rounded-xl border border-slate-200 overflow-hidden flex flex-col justify-between">
              <div>
                <div class="w-full aspect-4/3 bg-slate-200 overflow-hidden">
                  <img 
                    src="https://lh3.googleusercontent.com/d/1J0-9ejOjVO4E7Sm8Z9X9Lj0qwnUjr7jL" 
                    data-drive-id="1J0-9ejOjVO4E7Sm8Z9X9Lj0qwnUjr7jL"
                    alt="Xe 7 Chỗ SUV MPV V&K Travel" 
                    class="w-full h-full object-cover"
                    onerror="handleDriveImgError(this, 'Xe 7 Chỗ SUV')"
                  >
                </div>
                <div class="p-2.5">
                  <h3 class="product-title-full text-xs sm:text-sm font-bold text-[#0b3d78]">
                    Xe Du Lịch 7 Chỗ SUV Rộng Rãi
                  </h3>
                  <p class="text-[11px] text-slate-600 mt-1">
                    Đà Nẵng – Hội An: <strong class="text-red-600">280.000đ</strong> (1 chiều). Phù hợp gia đình.
                  </p>
                </div>
              </div>
              <div class="p-2.5 pt-0">
                <a href="tel:0905920638" class="block text-center bg-amber-500 hover:bg-amber-600 text-slate-950 font-bold text-[11px] py-1.5 rounded">
                  Gọi 0905 92 0638
                </a>
              </div>
            </div>

            <!-- Ảnh thực tế 3 -->
            <div class="bg-slate-50 rounded-xl border border-slate-200 overflow-hidden flex flex-col justify-between">
              <div>
                <div class="w-full aspect-4/3 bg-slate-200 overflow-hidden">
                  <img 
                    src="https://lh3.googleusercontent.com/d/1xdoUJRbykW5DQTjXXsTZQgbTnn_0TJmY" 
                    data-drive-id="1xdoUJRbykW5DQTjXXsTZQgbTnn_0TJmY"
                    alt="Xe 16 Chỗ Shuttle V&K Travel" 
                    class="w-full h-full object-cover"
                    onerror="handleDriveImgError(this, 'Xe 16 Chỗ Du Lịch')"
                  >
                </div>
                <div class="p-2.5">
                  <h3 class="product-title-full text-xs sm:text-sm font-bold text-[#0b3d78]">
                    Xe Du Lịch 16 Chỗ Ford Transit / Solati
                  </h3>
                  <p class="text-[11px] text-slate-600 mt-1">
                    Đà Nẵng – Hội An: <strong class="text-red-600">450.000đ</strong> (1 chiều). Phù hợp đoàn khách.
                  </p>
                </div>
              </div>
              <div class="p-2.5 pt-0">
                <a href="tel:0905920638" class="block text-center bg-amber-500 hover:bg-amber-600 text-slate-950 font-bold text-[11px] py-1.5 rounded">
                  Gọi 0905 92 0638
                </a>
              </div>
            </div>

            <!-- Ảnh thực tế 4 -->
            <div class="bg-slate-50 rounded-xl border border-slate-200 overflow-hidden flex flex-col justify-between">
              <div>
                <div class="w-full aspect-4/3 bg-slate-200 overflow-hidden">
                  <img 
                    src="https://lh3.googleusercontent.com/d/1ywg46EA_TzDTRe4B8NU-HWCudA4LjANj" 
                    data-drive-id="1ywg46EA_TzDTRe4B8NU-HWCudA4LjANj"
                    alt="Xe Đón Tiễn Sân Bay Đà Nẵng" 
                    class="w-full h-full object-cover"
                    onerror="handleDriveImgError(this, 'Xe Đón Sân Bay')"
                  >
                </div>
                <div class="p-2.5">
                  <h3 class="product-title-full text-xs sm:text-sm font-bold text-[#0b3d78]">
                    Xe Đón Tiễn Sân Bay Đà Nẵng 24/7
                  </h3>
                  <p class="text-[11px] text-slate-600 mt-1">
                    Miễn phí vé vào cổng sân bay. Tài xế举 bảng đón tận sảnh.
                  </p>
                </div>
              </div>
              <div class="p-2.5 pt-0">
                <a href="tel:0905920638" class="block text-center bg-amber-500 hover:bg-amber-600 text-slate-950 font-bold text-[11px] py-1.5 rounded">
                  Gọi 0905 92 0638
                </a>
              </div>
            </div>

            <!-- Ảnh thực tế 5 -->
            <div class="bg-slate-50 rounded-xl border border-slate-200 overflow-hidden flex flex-col justify-between col-span-2 md:col-span-1">
              <div>
                <div class="w-full aspect-4/3 bg-slate-200 overflow-hidden">
                  <img 
                    src="https://lh3.googleusercontent.com/d/1Ipn3jLVPY99rqmEhzjten1o39eexE-__" 
                    data-drive-id="1Ipn3jLVPY99rqmEhzjten1o39eexE-__"
                    alt="Xe Hợp Đồng Công Ty Xuất VAT" 
                    class="w-full h-full object-cover"
                    onerror="handleDriveImgError(this, 'Xe Hợp Đồng VAT')"
                  >
                </div>
                <div class="p-2.5">
                  <h3 class="product-title-full text-xs sm:text-sm font-bold text-[#0b3d78]">
                    Xe Hợp Đồng Tour & Công Tác (Xuất VAT)
                  </h3>
                  <p class="text-[11px] text-slate-600 mt-1">
                    Hợp đồng vận chuyển minh bạch, xuất hóa đơn VAT công ty đầy đủ.
                  </p>
                </div>
              </div>
              <div class="p-2.5 pt-0">
                <a href="tel:0905920638" class="block text-center bg-amber-500 hover:bg-amber-600 text-slate-950 font-bold text-[11px] py-1.5 rounded">
                  Gọi 0905 92 0638
                </a>
              </div>
            </div>

          </div>
        </div>
      </section>

      <!-- SECTION 6: BẢNG GIÁ TỔNG HỢP & FORM YÊU CẦU BÁO GIÁ TRANG CHỦ -->
      <section id="form-bao-gia" class="py-5">
        <div class="flatsome-container">
          <div class="grid grid-cols-1 lg:grid-cols-12 gap-4 items-start">
            
            <!-- Cột trái: Bảng giá chi tiết 1 chiều / Khứ hồi (7 cột) -->
            <div id="bang-gia-chi-tiet" class="lg:col-span-7 bg-white rounded-xl border border-slate-200 p-3.5 sm:p-5 shadow-xs">
              <h2 class="text-base sm:text-lg font-extrabold text-[#0b3d78] uppercase border-b pb-2 mb-3">
                BẢNG GIÁ THUÊ XE DU LỊCH ĐÀ NẴNG - HỘI AN NIÊM YẾT
              </h2>
              <div class="overflow-x-auto">
                <table class="w-full text-left border-collapse text-xs">
                  <thead>
                    <tr class="bg-[#0b3d78] text-white">
                      <th class="p-2 border border-slate-200">Lộ Trình Di Chuyển</th>
                      <th class="p-2 border border-slate-200 text-center">Xe 4 Chỗ</th>
                      <th class="p-2 border border-slate-200 text-center">Xe 7 Chỗ</th>
                      <th class="p-2 border border-slate-200 text-center">Xe 16 Chỗ</th>
                    </tr>
                  </thead>
                  <tbody class="divide-y divide-slate-200 text-slate-700">
                    <tr class="hover:bg-blue-50/50">
                      <td class="p-2 font-semibold">Đà Nẵng ⇄ Hội An (1 chiều)</td>
                      <td class="p-2 text-center font-bold text-red-600">230.000đ</td>
                      <td class="p-2 text-center font-bold text-red-600">280.000đ</td>
                      <td class="p-2 text-center font-bold text-red-600">450.000đ</td>
                    </tr>
                    <tr class="hover:bg-blue-50/50">
                      <td class="p-2 font-semibold">Hội An ⇄ VinWonders Nam Hội An (1 chiều)</td>
                      <td class="p-2 text-center font-bold text-red-600">200.000đ</td>
                      <td class="p-2 text-center font-bold text-red-600">250.000đ</td>
                      <td class="p-2 text-center font-bold text-red-600">350.000đ</td>
                    </tr>
                    <tr class="hover:bg-blue-50/50">
                      <td class="p-2 font-semibold">Đà Nẵng ⇄ VinWonders Nam Hội An (1 chiều)</td>
                      <td class="p-2 text-center font-bold text-red-600">400.000đ</td>
                      <td class="p-2 text-center font-bold text-red-600">450.000đ</td>
                      <td class="p-2 text-center font-bold text-red-600">650.000đ</td>
                    </tr>
                    <tr class="hover:bg-blue-50/50">
                      <td class="p-2 font-semibold">Đà Nẵng ⇄ Bà Nà Hills (1 chiều / 2 chiều)</td>
                      <td class="p-2 text-center font-bold text-red-600">300k / 600k</td>
                      <td class="p-2 text-center font-bold text-red-600">350k / 700k</td>
                      <td class="p-2 text-center font-bold text-red-600">550k / 1.000k</td>
                    </tr>
                    <tr class="hover:bg-blue-50/50">
                      <td class="p-2 font-semibold">Hội An ⇄ Bà Nà Hills (1 chiều / 2 chiều)</td>
                      <td class="p-2 text-center font-bold text-red-600">500k / 900k</td>
                      <td class="p-2 text-center font-bold text-red-600">600k / 1.000k</td>
                      <td class="p-2 text-center font-bold text-red-600">800k / 1.400k</td>
                    </tr>
                    <tr class="hover:bg-blue-50/50">
                      <td class="p-2 font-semibold">Đà Nẵng / Hội An ⇄ Cố Đô Huế (1C / 2C)</td>
                      <td class="p-2 text-center font-bold text-red-600">1.4tr / 2.0tr</td>
                      <td class="p-2 text-center font-bold text-red-600">1.6tr / 2.2tr</td>
                      <td class="p-2 text-center font-bold text-red-600">2.2tr / 2.9tr</td>
                    </tr>
                  </tbody>
                </table>
              </div>
              <div class="mt-3 p-2.5 rounded-lg bg-blue-50 text-xs text-[#0b3d78] space-y-1">
                <div><i class="fa-solid fa-circle-check mr-1.5"></i><strong>Miễn phí vé ra vào sân bay Đà Nẵng</strong> cho mọi chuyến đón/tiễn sân bay.</div>
                <div><i class="fa-solid fa-circle-check mr-1.5"></i><strong>Hỗ trợ xuất hóa đơn VAT công ty</strong> (vui lòng báo trước khi đặt xe).</div>
              </div>
            </div>

            <!-- Cột phải: Form yêu cầu và báo giá trang chủ (5 cột) -->
            <div class="lg:col-span-5 bg-white rounded-xl border-2 border-[#0b3d78] p-3.5 sm:p-5 shadow-sm">
              <div class="bg-[#0b3d78] text-white p-3 rounded-lg mb-3 text-center">
                <h3 class="text-sm sm:text-base font-extrabold uppercase">FORM YÊU CẦU & BÁO GIÁ ĐẶT XE</h3>
                <p class="text-[11px] text-blue-100 mt-0.5">Nhận báo giá nhanh qua Điện thoại / Zalo trong 2 phút</p>
              </div>

              <form id="quote-form" onsubmit="submitQuoteForm(event)" class="space-y-2.5 text-xs">
                <div class="grid grid-cols-2 gap-2">
                  <div>
                    <label class="block font-semibold text-slate-700 mb-1">Loại chuyến đi *</label>
                    <select id="trip-type" class="w-full border border-slate-300 rounded-lg px-2.5 py-2 bg-white focus:outline-none focus:border-[#0b3d78]">
                      <option value="Một chiều">Một chiều</option>
                      <option value="Khứ hồi 2 chiều">Khứ hồi (2 chiều)</option>
                      <option value="Thuê xe theo ngày">Thuê theo ngày / Hợp đồng</option>
                    </select>
                  </div>
                  <div>
                    <label class="block font-semibold text-slate-700 mb-1">Loại xe yêu cầu *</label>
                    <select id="car-type" class="w-full border border-slate-300 rounded-lg px-2.5 py-2 bg-white focus:outline-none focus:border-[#0b3d78]">
                      <option value="Xe 4 chỗ Sedan">Xe 4 chỗ Sedan</option>
                      <option value="Xe 7 chỗ SUV/MPV">Xe 7 chỗ SUV/MPV</option>
                      <option value="Xe 16 chỗ Du lịch">Xe 16 chỗ Du lịch</option>
                    </select>
                  </div>
                </div>

                <div>
                  <label class="block font-semibold text-slate-700 mb-1">Tuyến đường / Điểm đón - Điểm đến *</label>
                  <input type="text" id="route-input" required placeholder="VD: Đón Sân bay Đà Nẵng đi Phố cổ Hội An" class="w-full border border-slate-300 rounded-lg px-3 py-2 focus:outline-none focus:border-[#0b3d78]">
                </div>

                <div class="grid grid-cols-2 gap-2">
                  <div>
                    <label class="block font-semibold text-slate-700 mb-1">Họ và tên *</label>
                    <input type="text" id="customer-name" required placeholder="Nhập họ tên" class="w-full border border-slate-300 rounded-lg px-3 py-2 focus:outline-none focus:border-[#0b3d78]">
                  </div>
                  <div>
                    <label class="block font-semibold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                    <input type="tel" id="customer-phone" required placeholder="VD: 0905920638" class="w-full border border-slate-300 rounded-lg px-3 py-2 focus:outline-none focus:border-[#0b3d78]">
                  </div>
                </div>

                <div class="grid grid-cols-2 gap-2">
                  <div>
                    <label class="block font-semibold text-slate-700 mb-1">Ngày đón</label>
                    <input type="date" id="pickup-date" class="w-full border border-slate-300 rounded-lg px-2.5 py-2 focus:outline-none focus:border-[#0b3d78]">
                  </div>
                  <div>
                    <label class="block font-semibold text-slate-700 mb-1">Giờ đón</label>
                    <input type="time" id="pickup-time" class="w-full border border-slate-300 rounded-lg px-2.5 py-2 focus:outline-none focus:border-[#0b3d78]">
                  </div>
                </div>

                <div class="flex items-center gap-2 pt-1">
                  <input type="checkbox" id="need-vat" class="w-4 h-4 text-[#0b3d78] rounded">
                  <label for="need-vat" class="text-slate-700 font-medium">Yêu cầu xuất hóa đơn VAT công ty</label>
                </div>

                <button type="submit" class="w-full bg-amber-500 hover:bg-amber-600 text-slate-950 font-extrabold text-xs sm:text-sm py-2.5 rounded-lg shadow transition uppercase">
                  GỬI YÊU CẦU BÁO GIÁ NGAY
                </button>
              </form>

              <div id="quote-success-msg" class="hidden mt-3 p-3 rounded-lg bg-emerald-50 border border-emerald-300 text-emerald-900 text-xs"></div>
            </div>

          </div>
        </div>
      </section>

      <!-- SECTION 7: DANH MỤC CÁC BÀI VIẾT / KINH NGHIỆM TRANG CHỦ -->
      <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
      <section id="bai-viet-kinh-nghiem" class="py-4 bg-white border-t border-slate-200">
        <div class="flatsome-container">
          <div class="mb-3 pb-2 border-b-2 border-[#0b3d78]">
            <h2 class="text-base sm:text-lg font-extrabold text-[#0b3d78] uppercase">
              DANH MỤC BÀI VIẾT & KINH NGHIỆM THUÊ XE DU LỊCH
            </h2>
            <p class="text-xs text-slate-600">
              Cẩm nang di chuyển Đà Nẵng – Hội An – Bà Nà Hills – Huế tiết kiệm và an toàn
            </p>
          </div>

          <div class="grid grid-cols-2 lg:grid-cols-4 gap-2.5 sm:gap-4">
            <!-- Bài viết 1 -->
            <article class="bg-slate-50 rounded-xl border border-slate-200 overflow-hidden flex flex-col justify-between">
              <div>
                <div class="w-full aspect-16/10 bg-slate-200 overflow-hidden">
                  <img 
                    src="https://lh3.googleusercontent.com/d/1foYiiDIwHVYSsQ_pxyXizPoW1GNfIrWI" 
                    data-drive-id="1foYiiDIwHVYSsQ_pxyXizPoW1GNfIrWI"
                    alt="Kinh nghiệm thuê xe sân bay Đà Nẵng đi Hội An" 
                    class="w-full h-full object-cover"
                    onerror="handleDriveImgError(this, 'Bài viết 1')"
                  >
                </div>
                <div class="p-2.5 sm:p-3">
                  <h3 class="product-title-full text-xs sm:text-sm font-bold text-[#0b3d78] mb-1">
                    Kinh Nghiệm Thuê Xe Sân Bay Đà Nẵng Đi Hội An Miễn Phí Vé Cổng
                  </h3>
                  <p class="text-[11px] text-slate-600 line-clamp-3">
                    Đặt xe riêng 4-7-16 chỗ tại V&K Travel giúp bạn tiết kiệm toàn bộ phí ra vào sân bay Đà Nẵng và không phải chờ đợi.
                  </p>
                </div>
              </div>
              <div class="px-2.5 pb-2.5 sm:px-3 text-[11px] font-semibold text-amber-700">
                Xem chi tiết <i class="fa-solid fa-arrow-right ml-1"></i>
              </div>
            </article>

            <!-- Bài viết 2 -->
            <article class="bg-slate-50 rounded-xl border border-slate-200 overflow-hidden flex flex-col justify-between">
              <div>
                <div class="w-full aspect-16/10 bg-slate-200 overflow-hidden">
                  <img 
                    src="https://lh3.googleusercontent.com/d/1J0-9ejOjVO4E7Sm8Z9X9Lj0qwnUjr7jL" 
                    data-drive-id="1J0-9ejOjVO4E7Sm8Z9X9Lj0qwnUjr7jL"
                    alt="Thủ tục xuất hóa đơn VAT thuê xe du lịch" 
                    class="w-full h-full object-cover"
                    onerror="handleDriveImgError(this, 'Bài viết 2')"
                  >
                </div>
                <div class="p-2.5 sm:p-3">
                  <h3 class="product-title-full text-xs sm:text-sm font-bold text-[#0b3d78] mb-1">
                    Hướng Dẫn Đặt Xe Du Lịch Cho Công Ty Có Xuất Hóa Đơn VAT Hợp Lệ
                  </h3>
                  <p class="text-[11px] text-slate-600 line-clamp-3">
                    CÔNG TY TNHH V&K TRAVEL AGENCY (MST: 4001277058) cung cấp hợp đồng và hóa đơn VAT điện tử nhanh chóng cho doanh nghiệp.
                  </p>
                </div>
              </div>
              <div class="px-2.5 pb-2.5 sm:px-3 text-[11px] font-semibold text-amber-700">
                Xem chi tiết <i class="fa-solid fa-arrow-right ml-1"></i>
              </div>
            </article>

            <!-- Bài viết 3 -->
            <article class="bg-slate-50 rounded-xl border border-slate-200 overflow-hidden flex flex-col justify-between">
              <div>
                <div class="w-full aspect-16/10 bg-slate-200 overflow-hidden">
                  <img 
                    src="https://lh3.googleusercontent.com/d/1xdoUJRbykW5DQTjXXsTZQgbTnn_0TJmY" 
                    data-drive-id="1xdoUJRbykW5DQTjXXsTZQgbTnn_0TJmY"
                    alt="Kinh nghiệm đi Bà Nà Hills từ Hội An và Đà Nẵng" 
                    class="w-full h-full object-cover"
                    onerror="handleDriveImgError(this, 'Bài viết 3')"
                  >
                </div>
                <div class="p-2.5 sm:p-3">
                  <h3 class="product-title-full text-xs sm:text-sm font-bold text-[#0b3d78] mb-1">
                    Bảng Giá Xe Khứ Hồi Đi Bà Nà Hills Trong Ngày Tiết Kiệm Nhất
                  </h3>
                  <p class="text-[11px] text-slate-600 line-clamp-3">
                    Nên thuê xe 2 chiều Đà Nẵng hoặc Hội An đi Bà Nà Hills để tài xế chờ đón về bất cứ lúc nào mà không lo hết xe chiều muộn.
                  </p>
                </div>
              </div>
              <div class="px-2.5 pb-2.5 sm:px-3 text-[11px] font-semibold text-amber-700">
                Xem chi tiết <i class="fa-solid fa-arrow-right ml-1"></i>
              </div>
            </article>

            <!-- Bài viết 4 -->
            <article class="bg-slate-50 rounded-xl border border-slate-200 overflow-hidden flex flex-col justify-between">
              <div>
                <div class="w-full aspect-16/10 bg-slate-200 overflow-hidden">
                  <img 
                    src="https://lh3.googleusercontent.com/d/1ywg46EA_TzDTRe4B8NU-HWCudA4LjANj" 
                    data-drive-id="1ywg46EA_TzDTRe4B8NU-HWCudA4LjANj"
                    alt="Lịch trình Đà Nẵng Ngũ Hành Sơn Rừng Dừa Hội An" 
                    class="w-full h-full object-cover"
                    onerror="handleDriveImgError(this, 'Bài viết 4')"
                  >
                </div>
                <div class="p-2.5 sm:p-3">
                  <h3 class="product-title-full text-xs sm:text-sm font-bold text-[#0b3d78] mb-1">
                    Gợi Ý Lịch Trình Đà Nẵng – Ngũ Hành Sơn – Rừng Dừa – Phố Cổ Hội An
                  </h3>
                  <p class="text-[11px] text-slate-600 line-clamp-3">
                    Kết hợp tham quan các điểm nổi tiếng trên cung đường từ Đà Nẵng vào Hội An bằng xe riêng 4-7-16 chỗ tiện lợi.
                  </p>
                </div>
              </div>
              <div class="px-2.5 pb-2.5 sm:px-3 text-[11px] font-semibold text-amber-700">
                Xem chi tiết <i class="fa-solid fa-arrow-right ml-1"></i>
              </div>
            </article>
          </div>
        </div>
      </section>

      <!-- SECTION 8: DANH MỤC CÁC ĐỐI TÁC -->
      <section id="doi-tac" class="py-4">
        <div class="flatsome-container">
          <div class="bg-white rounded-xl border border-slate-200 p-3.5 sm:p-5 shadow-xs">
            <div class="mb-3 pb-2 border-b border-slate-200 flex items-center justify-between">
              <h2 class="text-sm sm:text-base font-extrabold text-[#0b3d78] uppercase">
                ĐỐI TÁC ĐỒNG HÀNH CÙNG V&K TRAVEL AGENCY
              </h2>
              <span class="text-[11px] text-slate-500">Hợp tác vận chuyển du lịch uy tín</span>
            </div>

            <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-2.5">
              <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 text-center flex flex-col items-center justify-center">
                <i class="fa-solid fa-plane-departure text-xl text-[#0b3d78] mb-1"></i>
                <div class="text-xs font-bold text-slate-800">Sân Bay Quốc Tế Đà Nẵng</div>
                <div class="text-[10px] text-slate-500">Đối tác đón tiễn</div>
              </div>
              <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 text-center flex flex-col items-center justify-center">
                <i class="fa-solid fa-mountain-sun text-xl text-amber-600 mb-1"></i>
                <div class="text-xs font-bold text-slate-800">Sun World Bà Nà Hills</div>
                <div class="text-[10px] text-slate-500">Đối tác lữ hành</div>
              </div>
              <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 text-center flex flex-col items-center justify-center">
                <i class="fa-solid fa-ferris-wheel text-xl text-blue-600 mb-1"></i>
                <div class="text-xs font-bold text-slate-800">VinWonders Nam Hội An</div>
                <div class="text-[10px] text-slate-500">Đối tác vận chuyển</div>
              </div>
              <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 text-center flex flex-col items-center justify-center">
                <i class="fa-solid fa-hotel text-xl text-emerald-600 mb-1"></i>
                <div class="text-xs font-bold text-slate-800">Khách Sạn Phố Cổ Hội An</div>
                <div class="text-[10px] text-slate-500">Hệ thống Resort</div>
              </div>
              <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 text-center flex flex-col items-center justify-center">
                <i class="fa-solid fa-umbrella-beach text-xl text-sky-600 mb-1"></i>
                <div class="text-xs font-bold text-slate-800">Rừng Dừa Bảy Mẫu</div>
                <div class="text-[10px] text-slate-500">Khu du lịch sinh thái</div>
              </div>
              <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 text-center flex flex-col items-center justify-center">
                <i class="fa-solid fa-building-columns text-xl text-purple-600 mb-1"></i>
                <div class="text-xs font-bold text-slate-800">Khối Doanh Nghiệp VAT</div>
                <div class="text-[10px] text-slate-500">Hợp đồng công ty</div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <!-- SECTION 9: ĐƯA FANPAGE FACEBOOK & GOOGLE MAP RA NGOÀI TRANG CHỦ -->
      <section id="lien-he-map" class="py-4">
        <div class="flatsome-container">
          <div class="grid grid-cols-1 lg:grid-cols-12 gap-4">
            
            <!-- Bản đồ Google Map ngoài trang chủ (7 cột) -->
            <div class="lg:col-span-7 bg-white rounded-xl border border-slate-200 p-3.5 sm:p-4 shadow-xs flex flex-col justify-between">
              <div>
                <div class="flex flex-wrap items-center justify-between gap-2 mb-2.5 pb-2 border-b border-slate-200">
                  <div>
                    <h2 class="text-sm sm:text-base font-extrabold text-[#0b3d78] uppercase">
                      <i class="fa-solid fa-map-location-dot text-red-600 mr-1.5"></i>BẢN ĐỒ GOOGLE MAP V&K TRAVEL AGENCY
                    </h2>
                    <p class="text-xs text-slate-600">
                      Địa chỉ: 29 Cao Sơn Pháo, Phường Điện Bàn, TP Đà Nẵng
                    </p>
                  </div>
                  <a href="https://www.google.com/maps/search/?api=1&query=29+Cao+S%C6%A1n+Ph%C3%A1o,+%C4%90i%E1%BB%87n+B%C3%A0n,+%C4%90%C3%A0+N%E1%BA%B5ng" target="_blank" rel="noopener noreferrer" class="text-xs font-bold text-[#0b3d78] bg-blue-50 hover:bg-blue-100 px-3 py-1.5 rounded-lg">
                    Mở Google Maps <i class="fa-solid fa-up-right-from-square ml-1 text-[10px]"></i>
                  </a>
                </div>

                <!-- Khung Google Map trực tiếp ngoài trang chủ -->
                <div class="w-full h-64 sm:h-72 rounded-lg overflow-hidden border border-slate-200 bg-slate-100">
                  <iframe 
                    title="Bản đồ 29 Cao Sơn Pháo, Phường Điện Bàn, TP Đà Nẵng"
                    src="https://maps.google.com/maps?q=29%20Cao%20S%C6%A1n%20Ph%C3%A1o,%20%C4%90i%E1%BB%87n%20B%C3%A0n,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=15&ie=UTF8&iwloc=&output=embed" 
                    width="100%" 
                    height="100%" 
                    style="border:0;" 
                    allowfullscreen="" 
                    loading="lazy" 
                    referrerpolicy="no-referrer-when-downgrade">
                  </iframe>
                </div>
              </div>

              <div class="mt-3 pt-2 border-t border-slate-100 flex flex-wrap items-center justify-between gap-2 text-xs text-slate-700">
                <span><i class="fa-solid fa-location-dot text-red-600 mr-1"></i><strong>Trụ sở:</strong> 29 Cao Sơn Pháo, Phường Điện Bàn, TP Đà Nẵng</span>
                <span><i class="fa-solid fa-phone-volume text-emerald-600 mr-1"></i><strong>SĐT:</strong> 0905 92 0638</span>
              </div>
            </div>

            <!-- Fanpage Facebook ngoài trang chủ (5 cột) -->
            <div class="lg:col-span-5 bg-white rounded-xl border border-slate-200 p-3.5 sm:p-4 shadow-xs flex flex-col justify-between">
              <div>
                <div class="flex items-center justify-between gap-2 mb-2.5 pb-2 border-b border-slate-200">
                  <div>
                    <h2 class="text-sm sm:text-base font-extrabold text-[#0b3d78] uppercase">
                      <i class="fa-brands fa-facebook text-blue-600 mr-1.5"></i>FANPAGE CHÍNH THỨC
                    </h2>
                    <p class="text-xs text-slate-600">Xe Đà Nẵng Đi Hội An Giá Rẻ - V&K Travel</p>
                  </div>
                  <a href="https://www.facebook.com/xedanangdihoiangiare/" target="_blank" rel="noopener noreferrer" class="text-xs font-bold text-white bg-blue-600 hover:bg-blue-700 px-3 py-1.5 rounded-lg">
                    Theo dõi Page
                  </a>
                </div>

                <!-- Thẻ Fanpage trực quan kết hợp khung nhúng Facebook -->
                <div class="rounded-lg border border-slate-200 overflow-hidden bg-slate-50 p-3 space-y-2.5">
                  <div class="flex items-center gap-3">
                    <img 
                      src="https://lh3.googleusercontent.com/d/1aqth1Q9LiMr-ENw135ygs9CA04IpGUoY" 
                      data-drive-id="1aqth1Q9LiMr-ENw135ygs9CA04IpGUoY"
                      alt="Avatar Fanpage V&K Travel" 
                      class="w-12 h-12 rounded-lg object-contain bg-white border border-slate-200 p-0.5 shrink-0"
                      onerror="handleDriveImgError(this, 'VK')"
                    >
                    <div class="min-w-0">
                      <a href="https://www.facebook.com/xedanangdihoiangiare/" target="_blank" rel="noopener noreferrer" class="text-xs sm:text-sm font-extrabold text-blue-700 hover:underline block truncate">
                        Xe Đà Nẵng Đi Hội An Giá Rẻ - V&K Travel
                      </a>
                      <div class="text-[11px] text-slate-600">CÔNG TY TNHH V&K TRAVEL AGENCY</div>
                      <div class="text-[11px] text-emerald-700 font-semibold"><i class="fa-solid fa-circle-check mr-1"></i>Đang hoạt động 24/7 • ĐT: 0905 92 0638</div>
                    </div>
                  </div>

                  <!-- Facebook Page Plugin Iframe -->
                  <div class="w-full overflow-hidden rounded border border-slate-200 bg-white flex justify-center">
                    <iframe 
                      title="Fanpage Xe Đà Nẵng Đi Hội An Giá Rẻ"
                      src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fxedanangdihoiangiare%2F&tabs=timeline&width=340&height=180&small_header=true&adapt_container_width=true&hide_cover=false&show_facepile=true" 
                      width="340" 
                      height="180" 
                      style="border:none;overflow:hidden;max-width:100%;" 
                      scrolling="no" 
                      frameborder="0" 
                      allowfullscreen="true" 
                      allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share">
                    </iframe>
                  </div>
                </div>
              </div>

              <div class="mt-3 pt-2 border-t border-slate-100 flex items-center justify-between text-xs">
                <a href="https://www.facebook.com/xedanangdihoiangiare/" target="_blank" rel="noopener noreferrer" class="font-bold text-blue-600 hover:underline">
                  <i class="fa-brands fa-facebook-messenger mr-1"></i>Nhắn tin qua Fanpage Facebook
                </a>
                <a href="https://zalo.me/0905920638" target="_blank" rel="noopener noreferrer" class="font-bold text-[#0b3d78] hover:underline">
                  Zalo: 0905 92 0638
                </a>
              </div>
            </div>

          </div>
        </div>
      </section>

    </main>

    <!-- ================= FOOTER (FLATSOME FOOTER) ================= -->
    <footer id="footer" class="bg-[#082c57] text-white pt-8 pb-20 md:pb-8 mt-4">
      <div class="flatsome-container">
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6 pb-6 border-b border-blue-800/70 text-xs">
          
          <!-- Cột 1: Thông tin công ty -->
          <div class="space-y-2">
            <div class="flex items-center gap-2.5">
              <div class="w-9 h-9 rounded bg-white p-0.5 flex items-center justify-center shrink-0">
                <img 
                  src="https://lh3.googleusercontent.com/d/1aqth1Q9LiMr-ENw135ygs9CA04IpGUoY" 
                  data-drive-id="1aqth1Q9LiMr-ENw135ygs9CA04IpGUoY"
                  alt="Logo V&K Travel Footer" 
                  class="w-full h-full object-contain"
                  onerror="handleDriveImgError(this, 'VK')"
                >
              </div>
              <div>
                <div class="font-extrabold text-sm text-amber-400">CÔNG TY TNHH V&K TRAVEL AGENCY</div>
                <div class="text-[11px] text-blue-200">Website: vktravel.com</div>
              </div>
            </div>
            <p class="text-blue-100 leading-relaxed">
              Chuyên xe du lịch Đà Nẵng - Hội An 4-7-16 chỗ đời mới. Hỗ trợ xuất VAT công ty. Miễn phí vé ra vào sân bay.
            </p>
            <div class="space-y-1 text-blue-100 pt-1">
              <div><i class="fa-solid fa-location-dot text-amber-400 mr-1.5"></i><strong>Địa chỉ:</strong> 29 Cao Sơn Pháo, Phường Điện Bàn, TP Đà Nẵng</div>
              <div><i class="fa-solid fa-phone text-amber-400 mr-1.5"></i><strong>Hotline / Zalo:</strong> <a href="tel:0905920638" class="text-amber-300 font-bold">0905 92 0638</a></div>
              <div><i class="fa-solid fa-hashtag text-amber-400 mr-1.5"></i><strong>Mã số thuế:</strong> 4001277058</div>
            </div>
          </div>

          <!-- Cột 2: Thuê xe Đà Nẵng -->
          <div>
            <h4 class="font-extrabold text-sm text-amber-400 uppercase mb-2.5">Thuê Xe Đà Nẵng</h4>
            <ul class="space-y-1.5 text-blue-100">
              <li><a href="#tuyen-da-nang" class="hover:text-amber-300">• Xe từ Đà Nẵng đi Hội An</a></li>
              <li><a href="#tuyen-da-nang" class="hover:text-amber-300">• Xe từ Đà Nẵng đi Bà Nà Hills</a></li>
              <li><a href="#tuyen-da-nang" class="hover:text-amber-300">• Xe từ Đà Nẵng đi VinWonders</a></li>
              <li><a href="#tuyen-da-nang" class="hover:text-amber-300">• Xe từ Đà Nẵng đi Cố đô Huế</a></li>
              <li><a href="#tuyen-da-nang" class="hover:text-amber-300">• Xe Đà Nẵng đi Tam Kỳ, Chu Lai</a></li>
              <li><a href="#tuyen-da-nang" class="hover:text-amber-300">• Xe Đà Nẵng đi Quảng Ngãi, Quy Nhơn</a></li>
            </ul>
          </div>

          <!-- Cột 3: Thuê xe Hội An -->
          <div>
            <h4 class="font-extrabold text-sm text-amber-400 uppercase mb-2.5">Thuê Xe Hội An</h4>
            <ul class="space-y-1.5 text-blue-100">
              <li><a href="#tuyen-da-nang" class="hover:text-amber-300">• Xe từ Hội An đi Sân bay Đà Nẵng</a></li>
              <li><a href="#tuyen-da-nang" class="hover:text-amber-300">• Xe từ Hội An đi Bà Nà Hills</a></li>
              <li><a href="#tuyen-da-nang" class="hover:text-amber-300">• Xe từ Hội An đi VinWonders</a></li>
              <li><a href="#tuyen-da-nang" class="hover:text-amber-300">• Xe từ Hội An đi Cố đô Huế</a></li>
              <li><a href="#tuyen-da-nang" class="hover:text-amber-300">• Xe Hội An đi Thánh địa Mỹ Sơn</a></li>
              <li><a href="#tuyen-da-nang" class="hover:text-amber-300">• Xe Hội An đi Tam Kỳ, Chu Lai</a></li>
            </ul>
          </div>

          <!-- Cột 4: Cam kết khách hàng -->
          <div>
            <h4 class="font-extrabold text-sm text-amber-400 uppercase mb-2.5">Chính Sách & Hỗ Trợ</h4>
            <ul class="space-y-1.5 text-blue-100">
              <li><i class="fa-solid fa-check text-emerald-400 mr-1.5"></i>Miễn phí vé ra vào sân bay Đà Nẵng</li>
              <li><i class="fa-solid fa-check text-emerald-400 mr-1.5"></i>Hỗ trợ xuất hóa đơn VAT công ty</li>
              <li><i class="fa-solid fa-check text-emerald-400 mr-1.5"></i>Xe riêng đời mới 4 - 7 - 16 chỗ</li>
              <li><i class="fa-solid fa-check text-emerald-400 mr-1.5"></i>Đón đúng giờ 24/7, giá trọn gói</li>
              <li class="pt-1">
                <a href="https://www.facebook.com/xedanangdihoiangiare/" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-1.5 bg-blue-700 hover:bg-blue-600 text-white px-3 py-1.5 rounded font-semibold">
                  <i class="fa-brands fa-facebook"></i> Fanpage Facebook
                </a>
              </li>
            </ul>
          </div>

        </div>

        <div class="pt-4 text-center text-[11px] text-blue-200">
          © Bản quyền thuộc về <strong>CÔNG TY TNHH V&K TRAVEL AGENCY (vktravel.com)</strong> • Địa chỉ: 29 Cao Sơn Pháo, Phường Điện Bàn, TP Đà Nẵng • Hotline: 0905 92 0638
        </div>
      </div>
    </footer>

    <!-- ================= CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE) TƯƠNG THÍCH MÁY TÍNH & ĐIỆN THOẠI ================= -->
    <div class="fixed right-3 bottom-4 z-50 flex flex-col items-end gap-2.5">
      
      <!-- Nút Facebook Fanpage -->
      <a 
        href="https://www.facebook.com/xedanangdihoiangiare/" 
        target="_blank" 
        rel="noopener noreferrer"
        class="flex items-center gap-2 bg-[#1877F2] hover:bg-blue-700 text-white px-3 py-2 rounded-full shadow-lg transition transform hover:scale-105"
        title="Fanpage Facebook V&K Travel"
      >
        <i class="fa-brands fa-facebook-f text-sm w-4 text-center"></i>
        <span class="text-xs font-bold pr-1">Facebook</span>
      </a>

      <!-- Nút Chat Zalo -->
      <a 
        href="https://zalo.me/0905920638" 
        target="_blank" 
        rel="noopener noreferrer"
        class="flex items-center gap-2 bg-[#0068FF] hover:bg-blue-600 text-white px-3 py-2 rounded-full shadow-lg transition transform hover:scale-105"
        title="Chat Zalo 0905 92 0638"
      >
        <span class="bg-white text-[#0068FF] font-extrabold text-[10px] px-1.5 py-0.5 rounded-full leading-none">Zalo</span>
        <span class="text-xs font-bold pr-1">0905 92 0638</span>
      </a>

      <!-- Nút Gọi Hotline Nổi Bật -->
      <a 
        href="tel:0905920638" 
        class="pulse-btn flex items-center gap-2 bg-red-600 hover:bg-red-700 text-white px-3.5 py-2.5 rounded-full shadow-xl transition"
        title="Gọi ngay 0905 92 0638"
      >
        <i class="fa-solid fa-phone-volume text-sm"></i>
        <span class="text-xs sm:text-sm font-extrabold">0905 92 0638</span>
      </a>

    </div>

  </div>

  <!-- ================= JAVASCRIPT XỬ LÝ SLIDER, BỘ LỌC DANH MỤC, FORM & ẢNH GOOGLE DRIVE ================= -->
  <script>
    // 1. Tự động chuyển đổi dự phòng link ảnh Google Drive nếu trình duyệt chặn 1 trong các định dạng
    function handleDriveImgError(imgEl, labelText) {
      const fileId = imgEl.getAttribute('data-drive-id');
      const step = parseInt(imgEl.getAttribute('data-fallback-step') || '0', 10);

      if (fileId && step === 0) {
        imgEl.setAttribute('data-fallback-step', '1');
        imgEl.src = 'https://drive.google.com/thumbnail?id=' + fileId + '&sz=w1200';
      } else if (fileId && step === 1) {
        imgEl.setAttribute('data-fallback-step', '2');
        imgEl.src = 'https://drive.google.com/uc?export=view&id=' + fileId;
      } else {
        imgEl.onerror = null;
        imgEl.src = 'https://placehold.co/600x400/0b3d78/ffffff?text=' + encodeURIComponent(labelText || 'V&K Travel');
      }
    }

    // 2. Xử lý 2 Banner tự trượt chuyên nghiệp (Đồng bộ cả Máy tính & Điện thoại)
    let currentSlideIndex = 0;
    const totalSlides = 2;
    let slideInterval = null;

    function renderSlides() {
      const desktopSlides = document.querySelectorAll('.desktop-slide');
      const mobileSlides = document.querySelectorAll('.mobile-slide');
      const dot0 = document.getElementById('dot-0');
      const dot1 = document.getElementById('dot-1');

      desktopSlides.forEach((slide, idx) => {
        if (idx === currentSlideIndex) {
          slide.classList.remove('opacity-0', 'z-0');
          slide.classList.add('opacity-100', 'z-10');
        } else {
          slide.classList.remove('opacity-100', 'z-10');
          slide.classList.add('opacity-0', 'z-0');
        }
      });

      mobileSlides.forEach((slide, idx) => {
        if (idx === currentSlideIndex) {
          slide.classList.remove('opacity-0', 'z-0');
          slide.classList.add('opacity-100', 'z-10');
        } else {
          slide.classList.remove('opacity-100', 'z-10');
          slide.classList.add('opacity-0', 'z-0');
        }
      });

      if (dot0 && dot1) {
        if (currentSlideIndex === 0) {
          dot0.className = 'w-6 h-2 rounded-full bg-[#0b3d78] transition-all';
          dot1.className = 'w-2.5 h-2 rounded-full bg-slate-300 transition-all';
        } else {
          dot0.className = 'w-2.5 h-2 rounded-full bg-slate-300 transition-all';
          dot1.className = 'w-6 h-2 rounded-full bg-[#0b3d78] transition-all';
        }
      }
    }

    function changeSlide(step) {
      currentSlideIndex = (currentSlideIndex + step + totalSlides) % totalSlides;
      renderSlides();
      resetSlideTimer();
    }

    function goToSlide(index) {
      currentSlideIndex = index;
      renderSlides();
      resetSlideTimer();
    }

    function resetSlideTimer() {
      if (slideInterval) clearInterval(slideInterval);
      slideInterval = setInterval(() => {
        currentSlideIndex = (currentSlideIndex + 1) % totalSlides;
        renderSlides();
      }, 4500);
    }

    // 3. Đóng/Mở Menu trên điện thoại
    function toggleMobileMenu() {
      const drawer = document.getElementById('mobile-menu-drawer');
      if (drawer) {
        drawer.classList.toggle('hidden');
      }
    }

    // 4. Lọc danh mục sản phẩm trang chủ
    function filterCategory(catKey) {
      const cards = document.querySelectorAll('.product-card');
      cards.forEach(card => {
        const cats = card.getAttribute('data-category') || '';
        if (catKey === 'all' || cats.includes(catKey)) {
          card.classList.remove('hidden');
        } else {
          card.classList.add('hidden');
        }
      });

      const allBtns = ['all', 'da-nang', 'hoi-an', 'xe-4-cho', 'xe-7-cho', 'xe-16-cho'];
      allBtns.forEach(key => {
        const btn = document.getElementById('cat-btn-' + key);
        if (btn) {
          if (key === catKey) {
            btn.className = 'home-cat-pill bg-[#0b3d78] text-white border border-[#0b3d78]';
          } else {
            btn.className = 'home-cat-pill bg-slate-50 hover:bg-blue-50 text-slate-700 border border-slate-200';
          }
        }
      });
    }

    // 5. Chọn nhanh tuyến xe xuống Form Báo Giá
    function selectRouteForQuote(routeName) {
      const routeInput = document.getElementById('route-input');
      if (routeInput) {
        routeInput.value = routeName;
      }
      const formSection = document.getElementById('form-bao-gia');
      if (formSection) {
        formSection.scrollIntoView({ behavior: 'smooth' });
      }
    }

    // 6. Xử lý gửi Form Yêu Cầu & Báo Giá
    function submitQuoteForm(e) {
      e.preventDefault();
      const tripType = document.getElementById('trip-type').value;
      const carType = document.getElementById('car-type').value;
      const route = document.getElementById('route-input').value;
      const name = document.getElementById('customer-name').value;
      const phone = document.getElementById('customer-phone').value;
      const date = document.getElementById('pickup-date').value || 'Hôm nay';
      const time = document.getElementById('pickup-time').value || 'Linh hoạt';
      const needVat = document.getElementById('need-vat').checked ? 'Có xuất VAT công ty' : 'Không';

      const msgBox = document.getElementById('quote-success-msg');
      if (msgBox) {
        msgBox.classList.remove('hidden');
        msgBox.innerHTML = `
          <div class="font-bold text-emerald-800 mb-1"><i class="fa-solid fa-circle-check mr-1"></i>Đã ghi nhận yêu cầu báo giá của ${name}!</div>
          <div>• <strong>Lộ trình:</strong> ${route} (${tripType} - ${carType})</div>
          <div>• <strong>Thời gian đón:</strong> ${time} ngày ${date} | <strong>VAT:</strong> ${needVat}</div>
          <div class="mt-2 pt-2 border-t border-emerald-200 flex flex-wrap gap-2">
            <a href="tel:0905920638" class="bg-red-600 text-white font-bold px-3 py-1 rounded">Gọi 0905 92 0638</a>
            <a href="https://zalo.me/0905920638" target="_blank" rel="noopener noreferrer" class="bg-[#0068FF] text-white font-bold px-3 py-1 rounded">Gửi qua Zalo</a>
          </div>
        `;
      }
    }

    window.onload = function() {
      resetSlideTimer();
    };
  </script>
</body>
</html>
