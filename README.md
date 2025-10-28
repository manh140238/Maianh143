# Maianh143
<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Giới Thiệu - Nguyễn Thị Mai Anh (Pink Style)</title>
    <link href="https://fonts.googleapis.com/css2?family=Pacifico&family=Quicksand:wght@400;700&display=swap" rel="stylesheet">
    
    <style>
        :root {
            --pink-primary: #FF69B4; /* Hồng đậm (Hot Pink) */
            --pink-light: #FFC0CB; /* Hồng nhạt (Pink) */
            --background-color: #FFF0F5; /* Hồng phấn (Lavender Blush) */
            --card-background: #FFFFFF; /* Nền trắng */
            --text-color: #4B0082; /* Tím đậm cho chữ */
        }

        body {
            font-family: 'Quicksand', sans-serif;
            background-color: var(--background-color);
            color: var(--text-color);
            margin: 0;
            padding: 20px;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }

        .container {
            width: 90%;
            max-width: 750px;
            background-color: var(--card-background);
            border-radius: 20px;
            box-shadow: 0 10px 40px rgba(255, 105, 180, 0.4); /* Bóng hồng */
            padding: 40px;
            box-sizing: border-box;
            border: 3px solid var(--pink-light);
        }

        header {
            text-align: center;
            padding-bottom: 20px;
            border-bottom: 5px double var(--pink-primary);
            margin-bottom: 30px;
        }

        header h1 {
            font-family: 'Pacifico', cursive; /* Font chữ kiểu viết tay cho tiêu đề */
            color: var(--pink-primary);
            font-size: 3em;
            margin-bottom: 5px;
            text-shadow: 2px 2px var(--pink-light);
        }

        header p {
            color: #8A2BE2; /* Màu tím nhạt */
            font-size: 1.2em;
            font-weight: 700;
        }

        /* Phần Nội Dung Chia cột */
        .content-grid {
            display: grid;
            grid-template-columns: 1fr;
            gap: 25px;
        }

        .info-block {
            background: var(--background-color);
            padding: 20px;
            border-radius: 15px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.05);
            border-top: 5px solid var(--pink-primary);
        }

        .info-block h2 {
            color: var(--pink-primary);
            margin-top: 0;
            margin-bottom: 15px;
            font-size: 1.5em;
        }

        .info-list {
            list-style: none;
            padding: 0;
        }

        .info-list li {
            margin-bottom: 12px;
            line-height: 1.5;
            display: flex;
        }

        .info-list li strong {
            display: inline-block;
            width: 130px; /* Cố định độ rộng cho tiêu đề */
            font-weight: 700;
            color: #8A2BE2; /* Màu tím nhạt */
        }
        
        /* Liên kết */
        .social-links {
            text-align: center;
            margin-top: 30px;
        }

        .social-links a {
            display: inline-block;
            background-color: var(--pink-primary);
            color: white;
            text-decoration: none;
            padding: 12px 25px;
            border-radius: 30px;
            font-weight: 700;
            transition: background-color 0.3s, transform 0.3s;
            margin: 0 10px;
            border: 2px solid var(--pink-primary);
        }

        .social-links a:hover {
            background-color: white;
            color: var(--pink-primary);
            transform: scale(1.05);
            box-shadow: 0 6px 20px rgba(255, 105, 180, 0.5);
        }
        
        /* Responsive cho màn hình lớn */
        @media (min-width: 650px) {
            .content-grid {
                grid-template-columns: 2fr 1fr; 
            }
            .contact-info {
                grid-column: 1 / span 2; /* Phần liên hệ nằm dưới cùng */
            }
        }
    </style>
</head>
<body>

    <div class="container">
        <header>
            <h1>Nguyễn Thị Mai Anh</h1>
            <p>🌷 Học sinh lớp 12A2 - K59 | Phú Xuyên A 🌷</p>
        </header>

        <div class="content-grid">
            
            <div class="info-block personal-info">
                <h2>💖 Thông Tin Cá Nhân</h2>
                <ul class="info-list">
                    <li><strong>Ngày sinh:</strong> 14/03/2008</li>
                    <li><strong>Giới tính:</strong> Nữ</li>
                    <li><strong>Địa chỉ:</strong> Phú Xuyên, Hà Nội</li>
                </ul>
            </div>
            
            <div class="info-block hobbies-school">
                <h2>📚 Học Tập & Sở Thích</h2>
                <ul class="info-list">
                    <li><strong>Trường Lớp:</strong> 12A2-K59-Phú Xuyên A</li>
                    <li><strong>Sở Thích:</strong> Xem Phim, Nghe nhạc, Ăn uống</li>
                </ul>
            </div>
        </div>
        
        <div class="info-block contact-info">
            <h2>📞 Kết Nối Với Mai Anh</h2>
            <ul class="info-list">
                <li><strong>SĐT:</strong> 0369458308</li>
            </ul>
            <div class="social-links">
                <a href="https://www.facebook.com/share/16awY73Mus/" target="_blank" rel="noopener noreferrer">
                    <span style="font-size: 1.2em;">🎀</span> FaceBook Của Mai Anh
                </a>
            </div>
        </div>
        
    </div>

</body>
</html>
