<script type="text/javascript">
        var gk_isXlsx = false;
        var gk_xlsxFileLookup = {};
        var gk_fileData = {};
        function filledCell(cell) {
          return cell !== '' && cell != null;
        }
        function loadFileData(filename) {
        if (gk_isXlsx && gk_xlsxFileLookup[filename]) {
            try {
                var workbook = XLSX.read(gk_fileData[filename], { type: 'base64' });
                var firstSheetName = workbook.SheetNames[0];
                var worksheet = workbook.Sheets[firstSheetName];

                // Convert sheet to JSON to filter blank rows
                var jsonData = XLSX.utils.sheet_to_json(worksheet, { header: 1, blankrows: false, defval: '' });
                // Filter out blank rows (rows where all cells are empty, null, or undefined)
                var filteredData = jsonData.filter(row => row.some(filledCell));

                // Heuristic to find the header row by ignoring rows with fewer filled cells than the next row
                var headerRowIndex = filteredData.findIndex((row, index) =>
                  row.filter(filledCell).length >= filteredData[index + 1]?.filter(filledCell).length
                );
                // Fallback
                if (headerRowIndex === -1 || headerRowIndex > 25) {
                  headerRowIndex = 0;
                }

                // Convert filtered JSON back to CSV
                var csv = XLSX.utils.aoa_to_sheet(filteredData.slice(headerRowIndex)); // Create a new sheet from filtered array of arrays
                csv = XLSX.utils.sheet_to_csv(csv, { header: 1 });
                return csv;
            } catch (e) {
                console.error(e);
                return "";
            }
        }
        return gk_fileData[filename] || "";
        }
        </script><!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>XChun Media - Khóa Học & Dịch Vụ MXH</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Arial', sans-serif;
        }

        body {
            background-color: #111;
            color: #fff;
            scroll-behavior: smooth;
        }
header {
  position: sticky;
  top: 0;
  z-index: 100;
  display: grid;
  grid-template-columns: 1fr auto 1fr; /* 👈 3 cột: trái - giữa - phải */
  align-items: center;
  padding: 16px 0;
  background: transparent;
}

.logo-wrapper {
  display: flex;
  justify-content: flex-start;
  padding-left: 50px; /* 👈 tạo khoảng cách logo với mép trái */
}

.logo {
  height: 70px;
}

.nav-wrapper {
  display: flex;
  justify-content: center;
}

nav {
  background: rgba(0, 0, 0, 0.6);
  padding: 16px 40px;
  border-radius: 40px;
  display: flex;
  gap: 24px;
  box-shadow: 0 4px 20px rgba(0, 255, 187, 0.3);
  backdrop-filter: blur(6px);
}


nav a {
  color: #fff;
  margin: 0 1rem;
  text-decoration: none;
  font-weight: 500;
  transition: color 0.3s ease;
}

nav a:hover {
  color: #00ffc3;
}

        .banner {
            background: url('https://via.placeholder.com/1200x300?text=XCHUN+Media') center/cover;
            padding: 3rem;
            text-align: center;
            color: #fff;
            text-shadow: 0 0 10px #000;
            margin-bottom: 2rem;
        }

        .banner h2 {
            font-size: 2rem;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 1rem;
        }

        .section-title {
            text-align: center;
            font-size: 2rem;
            margin-bottom: 1.5rem;
            color: #00ff88;
            text-shadow: 0 0 5px #00ff88;
        }

        .category-title {
            font-size: 1.6rem;
            margin: 2rem 0 1rem;
            color: #00f0ff;
        }

        .course-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 1.5rem;
        }

        .course-card {
            background-color: #222;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 255, 136, 0.3);
            padding: 1.5rem;
            text-align: center;
            transition: transform 0.3s;
            opacity: 0;
            transform: translateY(20px);
            animation: fadeIn 0.5s forwards;
        }

        .course-card.visible {
            opacity: 1;
            transform: translateY(0);
        }

        @keyframes fadeIn {
            to { opacity: 1; transform: translateY(0); }
        }

        .course-card:hover {
            transform: scale(1.05);
        }

        .course-card img {
            width: 100%;
            height: 150px;
            object-fit: cover;
            border-radius: 5px;
            margin-bottom: 1rem;
        }

        .course-card h3 {
            font-size: 1.3rem;
            margin-bottom: 0.5rem;
            color: #fff;
        }

        .course-card p {
            font-size: 0.9rem;
            color: #ccc;
            margin-bottom: 1rem;
        }

        .course-card .price {
            font-size: 1.2rem;
            font-weight: bold;
            color: #00ff88;
            margin-bottom: 1rem;
        }

        .course-card button {
            background: linear-gradient(45deg, #00ff88, #00f0ff);
            color: #000;
            border: none;
            padding: 0.75rem 1.5rem;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1rem;
            font-weight: bold;
            margin: 0.5rem;
            transition: background 0.3s;
        }

        .course-card button:hover {
            background: linear-gradient(45deg, #00f0ff, #00ff88);
        }

        .cart, .contact-form, .blog-section {
            background-color: #222;
            padding: 2rem;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 255, 136, 0.3);
            margin-top: 2rem;
        }

        .cart h2, .contact-form h2, .blog-section h2 {
            font-size: 1.6rem;
            margin-bottom: 1rem;
            color: #00ff88;
        }

        .cart ul {
            list-style: none;
            margin-bottom: 1rem;
        }

        .cart li {
            font-size: 1rem;
            color: #ccc;
            margin-bottom: 0.5rem;
        }

        .contact-form input,
        .contact-form textarea {
            width: 100%;
            padding: 0.75rem;
            margin-bottom: 1rem;
            border: none;
            border-radius: 5px;
            background-color: #333;
            color: #fff;
        }

        .contact-form button, .zalo-btn, .cart button {
            background: linear-gradient(45deg, #00ff88, #00f0ff);
            color: #000;
            border: none;
            padding: 0.75rem 1.5rem;
            border-radius: 5px;
            cursor: pointer;
            font-weight: bold;
            transition: background 0.3s;
        }

        .contact-form button:hover, .zalo-btn:hover, .cart button:hover {
            background: linear-gradient(45deg, #00f0ff, #00ff88);
        }

        .modal {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.8);
            z-index: 200;
            transition: opacity 0.3s;
        }

        .modal-content {
            background-color: #222;
            margin: 10% auto;
            padding: 2rem;
            border-radius: 8px;
            max-width: 600px;
            color: #fff;
            animation: slideIn 0.3s ease-out;
        }

        @keyframes slideIn {
            from { transform: translateY(-20px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }

        .modal-content h2 {
            color: #00ff88;
            margin-bottom: 1rem;
        }

        .close-btn {
            float: right;
            font-size: 1.5rem;
            cursor: pointer;
            color: #00ff88;
            transition: color 0.3s;
        }

        .close-btn:hover {
            color: #00f0ff;
        }

        footer {
            background: linear-gradient(45deg, #00ff88, #00f0ff);
            color: #000;
            text-align: center;
            padding: 1rem;
            margin-top: 2rem;
        }

        .chat-support {
            position: fixed;
            bottom: 20px;
            right: 20px;
            z-index: 1000;
        }

        .zalo-btn {
            display: inline-block;
            background: linear-gradient(45deg, #00ff88, #00f0ff);
            color: #000;
            padding: 1rem 2rem;
            border-radius: 50%;
            text-align: center;
            font-size: 1.5rem;
            text-decoration: none;
            transition: background 0.3s;
        }

        .zalo-btn:hover {
            background: linear-gradient(45deg, #00f0ff, #00ff88);
        }

        @media (max-width: 600px) {
            header h1 {
                font-size: 1.8rem;
            }

            header .logo {
                height: 40px;
            }

            nav a {
                font-size: 1rem;
                margin: 0 0.5rem;
            }

            .course-card {
                padding: 1rem;
            }

            .modal-content {
                margin: 20% 1rem;
            }
        }
    
#particles-js {
    position: fixed;
    width: 100%;
    height: 100%;
    background: #0d0e2c;
    z-index: -1;
}

</style>
</head>
<body>
<div id="particles-js"></div>
    <header>
  <div class="logo-wrapper">
    <img src="https://images.cooltext.com/5737215.png" alt="XChun Logo" class="logo">
  </div>
  <nav>
    <a href="#home" onclick="scrollToSection('home')">Trang Chủ</a>
    <a href="#courses" onclick="scrollToSection('courses')">Khóa Học</a>
    <a href="#services" onclick="scrollToSection('services')">Dịch Vụ</a>
    <a href="#blog" onclick="scrollToSection('blog')">Blog</a>
    <a href="#contact" onclick="scrollToSection('contact')">Liên Hệ</a>
  </nav>
</header>



    <div class="banner" id="home">
        <h2>Chào mừng đến với XChun Media - Giải pháp kinh doanh online!</h2>
    </div>

    <div class="container">
        <h2 class="section-title">Khóa Học Nổi Bật</h2>

        <!-- Khóa Học -->
        <h3 class="category-title" id="courses">Khóa Học</h3>
        <div class="course-grid" id="course-grid">
            <div class="course-card" data-course="dame-fb-basic">
                <h3>Mẹo Dame Facebook Cơ Bản</h3>
                <p>Kiến thức cơ bản về Report, cung cấp Proxy/VPN.</p>
                <div class="price">399.000đ</div>
                <button onclick="showCourseDetails('dame-fb-basic')">Chi Tiết</button>
            </div>
            <div class="course-card" data-course="dame-fb-advanced">
                <h3>Mẹo Dame Facebook Nâng Cao</h3>
                <p>Kiến thức nâng cao về Report, có update khi fix.</p>
                <div class="price">699.000đ</div>
                <button onclick="showCourseDetails('dame-fb-advanced')">Chi Tiết</button>
            </div>
            <div class="course-card" data-course="full-dame-fb">
                
                <h3>Full Mẹo Dame FB</h3>
                <p>Full mẹo cơ bản & nâng cao, hỗ trợ 1:1, nhóm update.</p>
                <div class="price">950.000đ</div>
                <button onclick="showCourseDetails('full-dame-fb')">Chi Tiết</button>
            </div>
            <div class="course-card" data-course="dame-ig-threads">
                
                <h3>Mẹo dame Instagram </h3>
                <p>Kiến thức dame Instagram, phòng tránh report, hỗ trợ 1:1.</p>
                <div class="price">799.000đ</div>
                <button onclick="showCourseDetails('dame-ig-threads')">Chi Tiết</button>
            </div>
            <div class="course-card" data-course="tut-dame-faq">
                
                <h3>Tut Dame FAQ</h3>
                <p>Dame dạng FAQ, kèm video, hỗ trợ 1:1, nhóm update.</p>
                <div class="price">1.250.000đ</div>
                <button onclick="showCourseDetails('tut-dame-faq')">Chi Tiết</button>
            </div>
            <div class="course-card" data-course="unlock-282">
                
                <h3>Mẹo Unlock 282</h3>
                <p>Giải pháp mở khóa 282, tỉ lệ thành công 90%.</p>
                <div class="price">777.000đ</div>
                <button onclick="showCourseDetails('unlock-282')">Chi Tiết</button>
            </div>
            <div class="course-card" data-course="unlock-956">
                
                <h3>Mẹo Unlock 956</h3>
                <p>Giải pháp mở khóa 956, tỉ lệ thành công 90%.</p>
                <div class="price">650.000đ</div>
                <button onclick="showCourseDetails('unlock-956')">Chi Tiết</button>
            </div>
            <div class="course-card" data-course="unlock-956-282">
               
                <h3>Mẹo Unlock 956 + 282</h3>
                <p>Giải pháp mở khóa 956 & 282, hướng dẫn phòng tránh.</p>
                <div class="price">950.000đ</div>
                <button onclick="showCourseDetails('unlock-956-282')">Chi Tiết</button>
            </div>
            <div class="course-card" data-course="back-acc">
               
                <h3>Mẹo Back Acc</h3>
                <p>Phục hồi tài khoản bị hack, tỉ lệ thành công 100%.</p>
                <div class="price">550.000đ</div>
                <button onclick="showCourseDetails('back-acc')">Chi Tiết</button>
            </div>
            <div class="course-card" data-course="unlock-faq">
               
                <h3>Mẹo Unlock FAQ</h3>
                <p>Mở khóa các dạng FAQ (811, 035, 208,...), tỉ lệ 80%.</p>
                <div class="price">3.500.000đ</div>
                <button onclick="showCourseDetails('unlock-faq')">Chi Tiết</button>
            </div>
            <div class="course-card" data-course="full-unlock">
                
                <h3>Full Unlock Thường</h3>
                <p>Mở khóa hầu hết các dạng, tỉ lệ thành công cao.</p>
                <div class="price">4.500.000đ</div>
                <button onclick="showCourseDetails('full-unlock')">Chi Tiết</button>
            </div>
            <div class="course-card" data-course="ads-fb-basic">
                
                <h3>ADS Facebook Cơ Bản</h3>
                <p>8 bài học từ A-Z, tạo & tối ưu quảng cáo, 5 ngày.</p>
                <div class="price">8.800.000đ</div>
                <button onclick="showCourseDetails('ads-fb-basic')">Chi Tiết</button>
            </div>
            <div class="course-card" data-course="ads-fb-advanced">
              
                <h3>ADS Facebook Nâng Cao</h3>
                <p>Chiến lược nâng cao, tối ưu ROAS, CPA, 9 ngày.</p>
                <div class="price">12.800.000đ</div>
                <button onclick="showCourseDetails('ads-fb-advanced')">Chi Tiết</button>
            </div>
            <div class="course-card" data-course="ads-tiktok-basic">
               
                <h3>ADS TikTok Cơ Bản</h3>
                <p>8 bài học cơ bản, tạo & tối ưu quảng cáo, 5 ngày.</p>
                <div class="price">5.500.000đ</div>
                <button onclick="showCourseDetails('ads-tiktok-basic')">Chi Tiết</button>
            </div>
            <div class="course-card" data-course="ads-tiktok-advanced">
               
                <h3>ADS TikTok Nâng Cao</h3>
                <p>Chiến lược nâng cao, tối ưu hóa đơn, 9 ngày.</p>
                <div class="price">8.500.000đ</div>
                <button onclick="showCourseDetails('ads-tiktok-advanced')">Chi Tiết</button>
            </div>
            <div class="course-card" data-course="dv-fb-basic">
                
                <h3>DV Facebook Cơ Bản</h3>
                <p>Kiến thức dịch vụ, tool miễn phí, 5 ngày.</p>
                <div class="price">3.500.000đ</div>
                <button onclick="showCourseDetails('dv-fb-basic')">Chi Tiết</button>
            </div>
            <div class="course-card" data-course="dv-fb-advanced">
                
                <h3>DV Facebook Nâng Cao</h3>
                <p>Vận hành hiệu quả, tài nguyên đầy đủ, 9 ngày.</p>
                <div class="price">5.500.000đ</div>
                <button onclick="showCourseDetails('dv-fb-advanced')">Chi Tiết</button>
            </div>
            <div class="course-card" data-course="dv-tiktok-basic">
                
                <h3>DV TikTok Cơ Bản</h3>
                <p>Kiến thức dịch vụ TikTok, cải thiện tương tác, 5 ngày.</p>
                <div class="price">3.500.000đ</div>
                <button onclick="showCourseDetails('dv-tiktok-basic')">Chi Tiết</button>
            </div>
            <div class="course-card" data-course="dv-tiktok-advanced">
               
                <h3>DV TikTok Nâng Cao</h3>
                <p>Vận hành hệ thống, cải thiện tương tác, 9 ngày.</p>
                <div class="price">5.500.000đ</div>
                <button onclick="showCourseDetails('dv-tiktok-advanced')">Chi Tiết</button>
            </div>
            <div class="course-card" data-course="web-design">
               
                <h3>Thiết Kế Website Cơ Bản</h3>
                <p>Học thiết kế web không cần code, hỗ trợ trọn đời.</p>
                <div class="price">7.500.000đ</div>
                <button onclick="showCourseDetails('web-design')">Chi Tiết</button>
            </div>
            <div class="course-card" data-course="vip-course">
               
                <h3>Full Khóa Học VIP</h3>
                <p>Tất cả khóa học, giảm 40%, hỗ trợ trọn đời.</p>
                <div class="price">20.000.000đ</div>
                <button onclick="showCourseDetails('vip-course')">Chi Tiết</button>
            </div>
        </div>
        
      

        <!-- Dịch Vụ -->
        <h3 class="category-title" id="services">Dịch Vụ</h3>
        <div class="course-grid" id="service-grid">
            <!-- Xóa Tài Khoản -->
            <div class="course-card" data-course="delete-fb-account">
                <img src="https://tlacademy.vn/wp-content/uploads/2023/05/dich-vu-cham-soc-mang-xa-hoi.jpg" alt="Xoa Tai Khoan FB">
                <h3>Dame Tài Khoản Facebook</h3>
                <p>Xóa tài khoản từ 200.000đ - 2.000.000đ.</p>
                <div class="price">500.000đ - 2.000.000đ</div>
                <button onclick="showCourseDetails('delete-fb-account')">Chi Tiết</button>
            </div>
            <div class="course-card" data-course="delete-fanpage">
                <img src="https://tlacademy.vn/wp-content/uploads/2023/05/dich-vu-cham-soc-mang-xa-hoi.jpg" alt="Xoa Fanpage">
                <h3>Dame Fanpage Facebook</h3>
                <p>Xóa fanpage từ 800.000đ - 5.000.000đ.</p>
                <div class="price">800.000đ - 5.000.000đ</div>
                <button onclick="showCourseDetails('delete-fanpage')">Chi Tiết</button>
            </div>
            <div class="course-card" data-course="delete-group">
                <img src="https://tlacademy.vn/wp-content/uploads/2023/05/dich-vu-cham-soc-mang-xa-hoi.jpg" alt="Xoa Group">
                <h3>Dame Group Facebook</h3>
                <p>Xóa group từ 2.000.000đ - 10.000.000đ.</p>
                <div class="price">2.000.000đ - 10.000.000đ</div>
                <button onclick="showCourseDetails('delete-group')">Chi Tiết</button>
            </div>
            <div class="course-card" data-course="delete-telegram">
                <img src="https://tlacademy.vn/wp-content/uploads/2023/05/dich-vu-cham-soc-mang-xa-hoi.jpg" alt="Xoa Telegram">
                <h3>Dame Channel Telegram</h3>
                <p>Xóa channel từ 2.000.000đ - 8.000.000đ.</p>
                <div class="price">2.000.000đ - 8.000.000đ</div>
                <button onclick="showCourseDetails('delete-telegram')">Chi Tiết</button>
            </div>
            <div class="course-card" data-course="delete-zalo">
                <img src="https://tlacademy.vn/wp-content/uploads/2023/05/dich-vu-cham-soc-mang-xa-hoi.jpg" alt="Xoa Zalo">
                <h3>Dame Tài Khoản Zalo</h3>
                <p>Xóa tài khoản từ 1.000.000đ - 10.000.000đ.</p>
                <div class="price">1.000.000đ - 10.000.000đ</div>
                <button onclick="showCourseDetails('delete-zalo')">Chi Tiết</button>
            </div>
            <div class="course-card" data-course="delete-tiktok">
                <img src="https://tlacademy.vn/wp-content/uploads/2023/05/dich-vu-cham-soc-mang-xa-hoi.jpg" alt="Xoa TikTok">
                <h3>Dame Tài Khoản TikTok</h3>
                <p>Xóa tài khoản từ 500.000đ - 20.000.000đ.</p>
                <div class="price">500.000đ - 20.000.000đ</div>
                <button onclick="showCourseDetails('delete-tiktok')">Chi Tiết</button>
            </div>
            <div class="course-card" data-course="delete-tiktok-video">
                <img src="https://tlacademy.vn/wp-content/uploads/2023/05/dich-vu-cham-soc-mang-xa-hoi.jpg" alt="Xoa Video TikTok">
                <h3>Dame Video TikTok</h3>
                <p>Xóa video từ 500.000đ - 4.000.000đ.</p>
                <div class="price">500.000đ - 4.000.000đ</div>
                <button onclick="showCourseDetails('delete-tiktok-video')">Chi Tiết</button>
            </div>
            <div class="course-card" data-course="delete-instagram">
                <img src="https://tlacademy.vn/wp-content/uploads/2023/05/dich-vu-cham-soc-mang-xa-hoi.jpg" alt="Xoa Instagram">
                <h3>Dame Tài Khoản Instagram</h3>
                <p>Xóa tài khoản từ 500.000đ - 4.000.000đ.</p>
                <div class="price">500.000đ - 4.000.000đ</div>
                <button onclick="showCourseDetails('delete-instagram')">Chi Tiết</button>
            </div>
            <div class="course-card" data-course="delete-youtube">
                <img src="https://tlacademy.vn/wp-content/uploads/2023/05/dich-vu-cham-soc-mang-xa-hoi.jpg" alt="Xoa YouTube">
                <h3>Dame Tài Khoản YouTube</h3>
                <p>Xóa tài khoản từ 4.000.000đ - 15.000.000đ.</p>
                <div class="price">4.000.000đ - 15.000.000đ</div>
                <button onclick="showCourseDetails('delete-youtube')">Chi Tiết</button>
            </div>
            <div class="course-card" data-course="delete-youtube-video">
                <img src="https://tlacademy.vn/wp-content/uploads/2023/05/dich-vu-cham-soc-mang-xa-hoi.jpg" alt="Xoa Video YouTube">
                <h3>Dame Video YouTube</h3>
                <p>Xóa video từ 2.000.000đ - 5.000.000đ.</p>
                <div class="price">2.000.000đ - 5.000.000đ</div>
                <button onclick="showCourseDetails('delete-youtube-video')">Chi Tiết</button>
            </div>
            <div class="course-card" data-course="delete-threads">
                <img src="https://tlacademy.vn/wp-content/uploads/2023/05/dich-vu-cham-soc-mang-xa-hoi.jpg">
                <h3>Dame Tài Khoản Threads</h3>
                <p>Xóa tài khoản từ 400.000đ - 4.000.000đ.</p>
                <div class="price">400.000đ - 4.000.000đ</div>
                <button onclick="showCourseDetails('delete-threads')">Chi Tiết</button>
            </div>

            <!-- Xác Thực & Mở Khóa -->
            <div class="course-card" data-course="verify-fb-profile">
                <img src="https://tlacademy.vn/wp-content/uploads/2023/05/dich-vu-cham-soc-mang-xa-hoi.jpg" alt="Xac Thuc FB">
                <h3>Lên Tick Xanh Profile Facebook</h3>
                <p>Lên tick từ 1.850.000đ - 10.850.000đ.</p>
                <div class="price">1.850.000đ - 10.850.000đ</div>
                <button onclick="showCourseDetails('verify-fb-profile')">Chi Tiết</button>
            </div>
            <div class="course-card" data-course="verify-tiktok">
                <img src="https://tlacademy.vn/wp-content/uploads/2023/05/dich-vu-cham-soc-mang-xa-hoi.jpg" alt="Xac Thuc TikTok">
                <h3>Lên Tick Xanh TikTok</h3>
                <p>Lên tick 9.000.000đ.</p>
                <div class="price">9.000.000đ</div>
                <button onclick="showCourseDetails('verify-tiktok')">Chi Tiết</button>
            </div>
            <div class="course-card" data-course="verify-instagram">
                <img src="https://tlacademy.vn/wp-content/uploads/2023/05/dich-vu-cham-soc-mang-xa-hoi.jpg" alt="Xac Thuc Instagram">
                <h3>Lên Tick Xanh Instagram</h3>
                <p>Lên tick 1.850.000đ.</p>
                <div class="price">1.850.000đ</div>
                <button onclick="showCourseDetails('verify-instagram')">Chi Tiết</button>
            </div>
            <div class="course-card" data-course="unlock-fb">
                <img src="https://tlacademy.vn/wp-content/uploads/2023/05/dich-vu-cham-soc-mang-xa-hoi.jpg" alt="Mo Khoa FB">
                <h3>Mở Khóa Tài Khoản Facebook</h3>
                <p>Mở khóa từ 300.000đ - 3.500.000đ.</p>
                <div class="price">300.000đ - 3.500.000đ</div>
                <button onclick="showCourseDetails('unlock-fb')">Chi Tiết</button>
            </div>
            <div class="course-card" data-course="unlock-tiktok">
                <img src="https://tlacademy.vn/wp-content/uploads/2023/05/dich-vu-cham-soc-mang-xa-hoi.jpg" alt="Mo Khoa TikTok">
                <h3>Mở Khóa Tài Khoản TikTok</h3>
                <p>Mở khóa từ 1.500.000đ - 5.000.000đ.</p>
                <div class="price">1.500.000đ - 5.000.000đ</div>
                <button onclick="showCourseDetails('unlock-tiktok')">Chi Tiết</button>
            </div>
            <div class="course-card" data-course="unlock-instagram">
                <img src="https://tlacademy.vn/wp-content/uploads/2023/05/dich-vu-cham-soc-mang-xa-hoi.jpg" alt="Mo Khoa Instagram">
                <h3>Mở Khóa Tài Khoản Instagram</h3>
                <p>Mở khóa từ 1.000.000đ - 4.500.000đ.</p>
                <div class="price">1.000.000đ - 4.500.000đ</div>
                <button onclick="showCourseDetails('unlock-instagram')">Chi Tiết</button>
            </div>
            <div class="course-card" data-course="unlock-youtube">
                <img src="https://tlacademy.vn/wp-content/uploads/2023/05/dich-vu-cham-soc-mang-xa-hoi.jpg" alt="Mo Khoa YouTube">
                <h3>Mở Khóa Tài Khoán YouTube</h3>
                <p>Mở khóa trong lượt (thường).</p>
                <div class="price">Thường</div>
                <button onclick="showCourseDetails('unlock-youtube')">Chi Tiết</button>
            </div>

            <!-- Quảng Cáo -->
            <div class="course-card" data-course="ad-logo">
                <img src="https://tlacademy.vn/wp-content/uploads/2023/05/dich-vu-cham-soc-mang-xa-hoi.jpg" alt="Quang Cao Logo">
                <h3>Thiết Kế Logo Thương Hiệu</h3>
                <p>Thiết kế từ 200.000đ.</p>
                <div class="price">200.000đ</div>
                <button onclick="showCourseDetails('ad-logo')">Chi Tiết</button>
            </div>
            <div class="course-card" data-course="ad-content">
                <img src="https://tlacademy.vn/wp-content/uploads/2023/05/dich-vu-cham-soc-mang-xa-hoi.jpg" alt="Quang Cao Content">
                <h3>Soạn Content Bản Hàng</h3>
                <p>Soạn content trong lượt (thường).</p>
                <div class="price">Thường</div>
                <button onclick="showCourseDetails('ad-content')">Chi Tiết</button>
            </div>
            <div class="course-card" data-course="ad-landing">
                <img src="https://tlacademy.vn/wp-content/uploads/2023/05/dich-vu-cham-soc-mang-xa-hoi.jpg" alt="Quang Cao Landing">
                <h3>Thiết Kế Landing Page</h3>
                <p>Thiết kế từ 1.000.000đ.</p>
                <div class="price">1.000.000đ</div>
                <button onclick="showCourseDetails('ad-landing')">Chi Tiết</button>
            </div>
            <div class="course-card" data-course="ad-facebook">
                <img src="https://tlacademy.vn/wp-content/uploads/2023/05/dich-vu-cham-soc-mang-xa-hoi.jpg" alt="Quang Cao FB">
                <h3>Chạy Quảng Cáo Facebook</h3>
                <p>Chạy từ 15.000.000đ/tháng.</p>
                <div class="price">15.000.000đ/tháng</div>
                <button onclick="showCourseDetails('ad-facebook')">Chi Tiết</button>
            </div>
            <div class="course-card" data-course="ad-tiktok">
                <img src="https://tlacademy.vn/wp-content/uploads/2023/05/dich-vu-cham-soc-mang-xa-hoi.jpg" alt="Quang Cao TikTok">
                <h3>Chạy Quảng Cáo TikTok</h3>
                <p>Chạy từ 15.000.000đ/tháng.</p>
                <div class="price">15.000.000đ/tháng</div>
                <button onclick="showCourseDetails('ad-tiktok')">Chi Tiết</button>
            </div>
            <div class="course-card" data-course="ad-instagram">
                <img src="https://tlacademy.vn/wp-content/uploads/2023/05/dich-vu-cham-soc-mang-xa-hoi.jpg" alt="Quang Cao Instagram">
                <h3>Chạy Quảng Cáo Instagram</h3>
                <p>Chạy từ 10.000.000đ/tháng.</p>
                <div class="price">10.000.000đ/tháng</div>
                <button onclick="showCourseDetails('ad-instagram')">Chi Tiết</button>
            </div>
            <div class="course-card" data-course="ad-google">
                <img src="https://tlacademy.vn/wp-content/uploads/2023/05/dich-vu-cham-soc-mang-xa-hoi.jpg" alt="Quang Cao Google">
                <h3>Chạy Quảng Cáo Google</h3>
                <p>Chạy từ 10.000.000đ/tháng.</p>
                <div class="price">10.000.000đ/tháng</div>
                <button onclick="showCourseDetails('ad-google')">Chi Tiết</button>
            </div>

            <!-- Tăng Tương Tác -->
            <div class="course-card" data-course="interact-fb-like">
                <img src="https://tlacademy.vn/wp-content/uploads/2023/05/dich-vu-cham-soc-mang-xa-hoi.jpg" alt="Tang Tuong Tac FB">
                <h3>Tăng Like Facebook</h3>
                <p>Tăng like trong lượt (thường).</p>
                <div class="price">Thường</div>
                <button onclick="showCourseDetails('interact-fb-like')">Chi Tiết</button>
            </div>
            <div class="course-card" data-course="interact-fb-follow">
                <img src="https://tlacademy.vn/wp-content/uploads/2023/05/dich-vu-cham-soc-mang-xa-hoi.jpg" alt="Tang Follow FB">
                <h3>Tăng Follow Facebook</h3>
                <p>Tăng follow trong lượt (thường).</p>
                <div class="price">Thường</div>
                <button onclick="showCourseDetails('interact-fb-follow')">Chi Tiết</button>
            </div>
            <div class="course-card" data-course="interact-fb-live">
                <img src="https://tlacademy.vn/wp-content/uploads/2023/05/dich-vu-cham-soc-mang-xa-hoi.jpg" alt="Tang Mat Live FB">
                <h3>Tăng Mắt Live Facebook</h3>
                <p>Tăng mắt live trong lượt (thường).</p>
                <div class="price">Thường</div>
                <button onclick="showCourseDetails('interact-fb-live')">Chi Tiết</button>
            </div>
            <div class="course-card" data-course="interact-fb-fanpage">
                <img src="https://tlacademy.vn/wp-content/uploads/2023/05/dich-vu-cham-soc-mang-xa-hoi.jpg" alt="Tang Dan Fanpage">
                <h3>Tăng Đánh Giá Fanpage</h3>
                <p>Tăng đánh giá trong lượt (thường).</p>
                <div class="price">Thường</div>
                <button onclick="showCourseDetails('interact-fb-fanpage')">Chi Tiết</button>
            </div>
            <div class="course-card" data-course="interact-fb-story">
                <img src="https://tlacademy.vn/wp-content/uploads/2023/05/dich-vu-cham-soc-mang-xa-hoi.jpg" alt="Tang View Story">
                <h3>Tăng View Story Facebook</h3>
                <p>Tăng view story trong lượt (thường).</p>
                <div class="price">Thường</div>
                <button onclick="showCourseDetails('interact-fb-story')">Chi Tiết</button>
            </div>
            <div class="course-card" data-course="interact-tiktok-tim">
                <img src="https://tlacademy.vn/wp-content/uploads/2023/05/dich-vu-cham-soc-mang-xa-hoi.jpg" alt="Tang Tim TikTok">
                <h3>Tăng Tim TikTok</h3>
                <p>Tăng tim trong lượt (thường).</p>
                <div class="price">Thường</div>
                <button onclick="showCourseDetails('interact-tiktok-tim')">Chi Tiết</button>
            </div>
            <div class="course-card" data-course="interact-tiktok-follow">
                <img src="https://tlacademy.vn/wp-content/uploads/2023/05/dich-vu-cham-soc-mang-xa-hoi.jpg" alt="Tang Follow TikTok">
                <h3>Tăng Follow TikTok</h3>
                <p>Tăng follow trong lượt (thường).</p>
                <div class="price">Thường</div>
                <button onclick="showCourseDetails('interact-tiktok-follow')">Chi Tiết</button>
            </div>
            <div class="course-card" data-course="interact-tiktok-view">
                <img src="https://tlacademy.vn/wp-content/uploads/2023/05/dich-vu-cham-soc-mang-xa-hoi.jpg" alt="Tang View TikTok">
                <h3>Tăng View TikTok</h3>
                <p>Tăng view trong lượt (thường).</p>
                <div class="price">Thường</div>
                <button onclick="showCourseDetails('interact-tiktok-view')">Chi Tiết</button>
            </div>
            <div class="course-card" data-course="interact-instagram-tim">
                <img src="https://tlacademy.vn/wp-content/uploads/2023/05/dich-vu-cham-soc-mang-xa-hoi.jpg" alt="Tang Tim Instagram">
                <h3>Tăng Tim Instagram</h3>
                <p>Tăng tim trong lượt (thường).</p>
                <div class="price">Thường</div>
                <button onclick="showCourseDetails('interact-instagram-tim')">Chi Tiết</button>
            </div>
            <div class="course-card" data-course="interact-instagram-follow">
                <img src="https://tlacademy.vn/wp-content/uploads/2023/05/dich-vu-cham-soc-mang-xa-hoi.jpg" alt="Tang Follow Instagram">
                <h3>Tăng Follow Instagram</h3>
                <p>Tăng follow trong lượt (thường).</p>
                <div class="price">Thường</div>
                <button onclick="showCourseDetails('interact-instagram-follow')">Chi Tiết</button>
            </div>
            <div class="course-card" data-course="interact-instagram-live">
                <img src="https://tlacademy.vn/wp-content/uploads/2023/05/dich-vu-cham-soc-mang-xa-hoi.jpg" alt="Tang Mat Live Instagram">
                <h3>Tăng Mắt Live Instagram</h3>
                <p>Tăng mắt live trong lượt (thường).</p>
                <div class="price">Thường</div>
                <button onclick="showCourseDetails('interact-instagram-live')">Chi Tiết</button>
            </div>
        </div>

        <!-- Blog -->
        <h3 class="category-title" id="blog">Blog</h3>
        <div class="blog-section">
            <h2>Bài Viết Mới Nhất</h2>
            <p><strong>Làm cách nào để mở khóa facebook bị khóa</stroing>-hướng dẫn cách mở khóa facebook bị khóa.</p>
            <p><strong>Hướng Dẫn Chạy Quảng Cáo Facebook</strong> - Các bước cơ bản và mẹo tránh bị khóa tài khoản.</p>
            <p><strong>Cập Nhật Luật Dame Tài Khoản 2025</strong> - Những thay đổi mới từ các nền tảng mạng xã hội.</p>
            <p><strong>Cách nào để có follow tik tok , facebook </strong>-hướng dẫn cách tăng follow.</p>
        </div>

        <!-- Giỏ Hàng -->
        <div class="cart" id="cart">
            <h2>Giỏ Hàng</h2>
            <ul id="cart-items"></ul>
            <button onclick="checkout()">Thanh Toán Qua Zalo</button>
        </div>

        <!-- Liên Hệ -->
        <h3 class="category-title" id="contact">Liên Hệ</h3>
        <div class="contact-form">
            <h2>Gửi Thông Tin Liên Hệ</h2>
            <input type="text" placeholder="Họ và tên" id="name">
            <input type="text" placeholder="Số điện thoại" id="phone">
            <textarea placeholder="Lời nhắn" id="message" rows="4"></textarea>
            <button onclick="submitContact()">Gửi</button>
        </div>
    </div>

    <!-- Modal -->
    <div id="courseModal" class="modal">
        <div class="modal-content">
            <span class="close-btn" onclick="closeModal()">&times;</span>
            <h2>Chi Tiết Khóa Học/Dịch Vụ</h2>
            <p id="modal-details"></p>
        </div>
    </div>

    <!-- Welcome Modal -->
    <div id="welcomeModal" class="modal">
        <div class="modal-content">
            <span class="close-btn" onclick="closeWelcome()">&times;</span>
            <h2>Chào Mừng!</h2>
            <p>Chào mừng bạn đến với XCHUN MEDIA – Giải pháp toàn diện cho kinh doanh online!</p>
            <p>🔹 Tăng like, follow, view thật – Nâng tầm uy tín cá nhân & doanh nghiệp</p>
            <p>🔹 Chạy quảng cáo Facebook, TikTok hiệu quả – Tối ưu chi phí, tiếp cận đúng khách hàng</p>
            <p>🔹 Thiết kế website bán hàng chuyên nghiệp – Chuẩn SEO, giao diện đẹp, dễ sử dụng</p>
            <p>🔹 Quản lý fanpage – Lên nội dung, chăm sóc inbox, tăng trưởng bền vững</p>
            <p>🔹 Hỗ trợ kỹ thuật: Mở khóa tài khoản, kháng cáo checkpoint, xử lý lỗi Facebook</p>
            <pv>👉 Cam kết bảo mật thông tin – Hỗ trợ nhanh chóng – Giá cả hợp lý</pv>
        </div>
    </div>

    <footer>
        <p>&copy; 2025 XChun Media. All rights reserved. Liên hệ: <a href="https://zalo.me/0332066509" target="_blank">Zalo</a></p>
    </footer>
<!-- Nút Zalo Chat -->
<a href="https://zalo.me/0332066509" target="_blank" class="zalo-button">
  <span class="zalo-text">Chat hỗ trợ</span>
  <span class="zalo-icon">
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/91/Icon_of_Zalo.svg/1200px-Icon_of_Zalo.svg.png" alt="Zalo" />
  </span>
</a>
<style>.zalo-button {
  position: fixed;
  bottom: 20px;
  right: 20px;
  display: flex;
  align-items: center;
  background: rgba(0, 255, 187, 0.1); /* xanh neon nhạt */
  border: 1px solid #00ffc3;
  border-radius: 30px;
  padding: 8px 14px 8px 16px;
  box-shadow: 0 0 12px rgba(0, 255, 187, 0.4);
  text-decoration: none;
  z-index: 1000;
  transition: all 0.3s ease;
  backdrop-filter: blur(4px);
}

.zalo-button:hover {
  transform: scale(1.05);
  box-shadow: 0 0 20px rgba(0, 255, 187, 0.6);
}

.zalo-text {
  color: #00ffc3;
  font-weight: 500;
  margin-right: 8px;
  font-size: 14px;
}

.zalo-icon img {
  width: 26px;
  height: 26px;
  filter: brightness(1.2);
}
</style>
    <script>
        // Welcome Modal
        function showWelcome() {
            document.getElementById('welcomeModal').style.display = 'block';
        }

        function closeWelcome() {
            document.getElementById('welcomeModal').style.display = 'none';
        }

        // Course Modal
        function showCourseDetails(courseId) {
            let details = '';
            const courses = {
                'dame-fb-basic': 'Khóa học cơ bản về dame Facebook, bao gồm Report và Proxy/VPN. Thời gian: 3 ngày.',
                'dame-fb-advanced': 'Khóa nâng cao về dame FB, cập nhật liên tục khi có fix. Thời gian: 5 ngày.',
                'full-dame-fb': 'Khóa full dame FB, hỗ trợ 1:1 và nhóm update. Thời gian: 7 ngày.',
                'dame-ig-threads': 'Khóa dame Instagram & Threads, phòng tránh report. Thời gian: 5 ngày.',
                'tut-dame-faq': 'Khóa dame FAQ với video hướng dẫn, hỗ trợ 1:1. Thời gian: 10 ngày.',
                'unlock-282': 'Giải pháp mở khóa 282, tỉ lệ thành công 90%. Thời gian: 3 ngày.',
                'unlock-956': 'Giải pháp mở khóa 956, tỉ lệ thành công 90%. Thời gian: 3 ngày.',
                'unlock-956-282': 'Mở khóa 956 & 282, hướng dẫn phòng tránh. Thời gian: 5 ngày.',
                'back-acc': 'Phục hồi tài khoản bị hack, tỉ lệ 100%. Thời gian: 2 ngày.',
                'unlock-faq': 'Mở khóa các dạng FAQ, tỉ lệ 80%. Thời gian: 7 ngày.',
                'full-unlock': 'Full unlock các dạng, tỉ lệ thành công cao. Thời gian: 10 ngày.',
                'ads-fb-basic': 'Khóa ADS FB cơ bản, 8 bài học, 5 ngày.',
                'ads-fb-advanced': 'Khóa ADS FB nâng cao, tối ưu ROAS/CPA, 9 ngày.',
                'ads-tiktok-basic': 'Khóa ADS TikTok cơ bản, 8 bài học, 5 ngày.',
                'ads-tiktok-advanced': 'Khóa ADS TikTok nâng cao, tối ưu hóa, 9 ngày.',
                'dv-fb-basic': 'Dịch vụ FB cơ bản, tool miễn phí, 5 ngày.',
                'dv-fb-advanced': 'Dịch vụ FB nâng cao, tài nguyên đầy đủ, 9 ngày.',
                'dv-tiktok-basic': 'Dịch vụ TikTok cơ bản, cải thiện tương tác, 5 ngày.',
                'dv-tiktok-advanced': 'Dịch vụ TikTok nâng cao, vận hành hệ thống, 9 ngày.',
                'web-design': 'Khóa thiết kế web không code, hỗ trợ trọn đời. Thời gian: 15 ngày.',
                'vip-course': 'Full khóa học VIP, giảm 40%, hỗ trợ trọn đời. Thời gian: 30 ngày.',
                'delete-fb-account': 'Dịch vụ xóa tài khoản FB, từ 500.000đ - 2.000.000đ. Thời gian: 3-7 ngày.',
                'delete-fanpage': 'Dịch vụ xóa fanpage FB, từ 800.000đ - 5.000.000đ. Thời gian: 5-10 ngày.',
                'delete-group': 'Dịch vụ xóa group FB, từ 4.000.000đ - 10.000.000đ. Thời gian: 7-14 ngày.',
                'delete-telegram': 'Dịch vụ xóa channel Telegram, từ 2.000.000đ - 8.000.000đ. Thời gian: 5-10 ngày.',
                'delete-zalo': 'Dịch vụ xóa tài khoản Zalo, từ 3.000.000đ - 10.000.000đ. Thời gian: 5-10 ngày.',
                'delete-tiktok': 'Dịch vụ xóa tài khoản TikTok, từ 4.000.000đ - 20.000.000đ. Thời gian: 7-14 ngày.',
                'delete-tiktok-video': 'Dịch vụ xóa video TikTok, từ 2.000.000đ - 4.000.000đ. Thời gian: 3-5 ngày.',
                'delete-instagram': 'Dịch vụ xóa tài khoản Instagram, từ 1.500.000đ - 4.000.000đ. Thời gian: 3-7 ngày.',
                'delete-youtube': 'Dịch vụ xóa tài khoản YouTube, từ 4.000.000đ - 15.000.000đ. Thời gian: 7-14 ngày.',
                'delete-youtube-video': 'Dịch vụ xóa video YouTube, từ 2.000.000đ - 5.000.000đ. Thời gian: 3-7 ngày.',
                'delete-threads': 'Dịch vụ xóa tài khoản Threads, từ 1.500.000đ - 4.000.000đ. Thời gian: 3-7 ngày.',
                'verify-fb-profile': 'Dịch vụ lên tick xanh profile FB, từ 1.850.000đ - 6.850.000đ. Thời gian: 7-14 ngày.',
                'verify-tiktok': 'Dịch vụ lên tick xanh TikTok, 78.000.000đ. Thời gian: 30 ngày.',
                'verify-instagram': 'Dịch vụ lên tick xanh Instagram, 1.850.000đ. Thời gian: 7 ngày.',
                'unlock-fb': 'Dịch vụ mở khóa tài khoản FB, từ 550.000đ - 8.500.000đ. Thời gian: 3-7 ngày.',
                'unlock-tiktok': 'Dịch vụ mở khóa tài khoản TikTok, từ 1.500.000đ - 20.000.000đ. Thời gian: 5-14 ngày.',
                'unlock-instagram': 'Dịch vụ mở khóa tài khoản Instagram, từ 2.000.000đ - 8.500.000đ. Thời gian: 3-7 ngày.',
                'unlock-youtube': 'Dịch vụ mở khóa tài khoản YouTube, trong lượt (thường). Thời gian: 3-5 ngày.',
                'ad-logo': 'Dịch vụ thiết kế logo thương hiệu, từ 999.000đ. Thời gian: 5-7 ngày.',
                'ad-content': 'Dịch vụ soạn content bán hàng, trong lượt (thường). Thời gian: 2-3 ngày.',
                'ad-landing': 'Dịch vụ thiết kế landing page, từ 2.500.000đ. Thời gian: 7-10 ngày.',
                'ad-facebook': 'Dịch vụ chạy quảng cáo FB, từ 30.000.000đ/tháng. Thời gian: tùy chỉnh.',
                'ad-tiktok': 'Dịch vụ chạy quảng cáo TikTok, từ 30.000.000đ/tháng. Thời gian: tùy chỉnh.',
                'ad-instagram': 'Dịch vụ chạy quảng cáo Instagram, từ 30.000.000đ/tháng. Thời gian: tùy chỉnh.',
                'ad-google': 'Dịch vụ chạy quảng cáo Google, từ 30.000.000đ/tháng. Thời gian: tùy chỉnh.',
                'interact-fb-like': 'Dịch vụ tăng like FB, trong lượt (thường). Thời gian: 1-2 ngày.',
                'interact-fb-follow': 'Dịch vụ tăng follow FB, trong lượt (thường). Thời gian: 1-2 ngày.',
                'interact-fb-live': 'Dịch vụ tăng mắt live FB, trong lượt (thường). Thời gian: 1-2 ngày.',
                'interact-fb-fanpage': 'Dịch vụ tăng đánh giá fanpage FB, trong lượt (thường). Thời gian: 1-2 ngày.',
                'interact-fb-story': 'Dịch vụ tăng view story FB, trong lượt (thường). Thời gian: 1-2 ngày.',
                'interact-tiktok-tim': 'Dịch vụ tăng tim TikTok, trong lượt (thường). Thời gian: 1-2 ngày.',
                'interact-tiktok-follow': 'Dịch vụ tăng follow TikTok, trong lượt (thường). Thời gian: 1-2 ngày.',
                'interact-tiktok-live': 'Dịch vụ tăng mắt live TikTok, trong lượt (thường). Thời gian: 1-2 ngày.',
                'interact-tiktok-view': 'Dịch vụ tăng view TikTok, trong lượt (thường). Thời gian: 1-2 ngày.',
                'interact-instagram-tim': 'Dịch vụ tăng tim Instagram, trong lượt (thường). Thời gian: 1-2 ngày.',
                'interact-instagram-follow': 'Dịch vụ tăng follow Instagram, trong lượt (thường). Thời gian: 1-2 ngày.',
                'interact-instagram-live': 'Dịch vụ tăng mắt live Instagram, trong lượt (thường). Thời gian: 1-2 ngày.'
            };
            details = courses[courseId] || 'Chi tiết không có sẵn.';
            document.getElementById('modal-details').innerText = details;
            document.getElementById('courseModal').style.display = 'block';
        }

        function closeModal() {
            document.getElementById('courseModal').style.display = 'none';
        }

        // Cart Functionality
        let cart = [];

        function addToCart(name, price) {
            cart.push({ name, price });
            updateCart();
        }

        function updateCart() {
            const cartItems = document.getElementById('cart-items');
            cartItems.innerHTML = '';
            cart.forEach(item => {
                const li = document.createElement('li');
                li.textContent = `${item.name} - ${item.price.toLocaleString('vi-VN')}đ`;
                cartItems.appendChild(li);
            });
        }

        function clearCart() {
            cart = [];
            updateCart();
        }

        function checkout() {
            if (cart.length > 0) {
                alert('Vui lòng liên hệ qua Zalo để thanh toán!');
            } else {
                alert('Giỏ hàng trống!');
            }
        }

        // Contact Form
        function submitContact() {
            const name = document.getElementById('name').value;
            const phone = document.getElementById('phone').value;
            const message = document.getElementById('message').value;
            if (name && phone && message) {
                alert('Thông tin đã được gửi! Chúng tôi sẽ liên hệ bạn qua Zalo.');
                document.getElementById('name').value = '';
                document.getElementById('phone').value = '';
                document.getElementById('message').value = '';
            } else {
                alert('Vui lòng điền đầy đủ thông tin!');
            }
        }

        // Scroll Functionality
        function scrollToSection(sectionId) {
            document.getElementById(sectionId).scrollIntoView({ behavior: 'smooth' });
        }

        // Animate Cards
        function animateCards() {
  const cards = document.querySelectorAll('.course-card');
  cards.forEach((card, index) => {
    setTimeout(() => {
      card.classList.add('visible');
    }, index * 100);
  });
}

// 👇 Thêm đoạn này để tự mở modal
window.onload = function () {
  showWelcome();
};
</script>


<!-- Thư viện particles.js -->
<script src="https://cdn.jsdelivr.net/npm/particles.js@2.0.0/particles.min.js"></script>
<script>
particlesJS("particles-js", {
  "particles": {
    "number": { "value": 80, "density": { "enable": true, "value_area": 800 } },
    "color": { "value": "#ffffff" },
    "shape": { "type": "circle" },
    "opacity": { "value": 0.5, "random": true },
    "size": { "value": 3, "random": true },
    "line_linked": {
      "enable": true,
      "distance": 150,
      "color": "#ffffff",
      "opacity": 0.4,
      "width": 1
    },
    "move": {
      "enable": true,
      "speed": 2,
      "direction": "none",
      "random": false,
      "straight": false,
      "out_mode": "out"
    }
  },
  "interactivity": {
    "events": {
      "onhover": { "enable": true, "mode": "repulse" },
      "onclick": { "enable": true, "mode": "push" }
    },
    "modes": {
      "repulse": { "distance": 100, "duration": 0.4 },
      "push": { "particles_nb": 4 }
    }
  },
  "retina_detect": true
});
</script>

</body>
</html>