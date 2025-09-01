<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cung Bạch Dương</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Cabin:wght@400;700&family=Lobster&family=Montserrat:wght@800&display=swap');

        :root {
            --color-primary: #0C0950;
            --color-secondary: #161179;
            --color-accent: #261FB3;
            --color-text-light: #FBE4D6;
        }

        body {
            font-family: 'Cabin', sans-serif;
            color: var(--color-text-light);
            line-height: 1.6;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            text-align: center;
            background: radial-gradient(circle at center, var(--color-secondary) 0%, var(--color-primary) 100%);
            position: relative;
            overflow: hidden;
        }

        /* Hiệu ứng sao lấp lánh */
        body::before {
            content: '';
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: transparent;
            /* Tạo các lớp sao với box-shadow */
            box-shadow: 
                -100px -100px 1px 1px var(--color-text-light),
                150px 120px 1px 1px var(--color-text-light),
                -20px 200px 1px 1px var(--color-text-light),
                250px 50px 1px 1px var(--color-text-light),
                -120px 300px 1px 1px var(--color-text-light),
                350px -150px 1px 1px var(--color-text-light),
                100px 400px 1px 1px var(--color-text-light),
                -250px -250px 1px 1px var(--color-text-light);
            animation: twinkle 5s infinite;
            z-index: -1;
        }

        @keyframes twinkle {
            0% { opacity: 0.8; }
            50% { opacity: 0.4; }
            100% { opacity: 0.8; }
        }

        .container {
            max-width: 900px;
            padding: 2rem;
            background-color: rgba(22, 17, 121, 0.7);
            border-radius: 1rem;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.5);
            margin: 20px;
        }

        h1 {
            font-family: 'Montserrat', sans-serif;
            font-size: 3rem;
            color: var(--color-text-light);
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
            margin-bottom: 1rem;
        }

        h2 {
            font-family: 'Lobster', cursive;
            font-size: 2rem;
            color: var(--color-text-light);
            margin-top: 2rem;
            margin-bottom: 1rem;
            border-bottom: 2px solid var(--color-accent);
            padding-bottom: 0.5rem;
            display: inline-block;
        }

        p {
            margin-bottom: 1.5rem;
        }

        .quote {
            font-style: italic;
            font-size: 1.2rem;
            color: var(--color-text-light);
            margin-top: 2rem;
            padding: 1.5rem;
            background-color: var(--color-accent);
            border-radius: 1rem;
        }

        .list-item {
            text-align: left;
            margin-bottom: 1rem;
        }

        .list-title {
            font-weight: bold;
            color: var(--color-text-light);
        }

        ul {
            list-style-type: none;
            padding: 0;
            text-align: left;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>CUNG BẠCH DƯƠNG</h1>

        <h2>1. Thông tin chung</h2>
        <p>Bạch Dương (có nghĩa là "cừu") là một trong những chòm sao hoàng đạo, nằm giữa Song Ngư ở phía tây và Kim Ngưu ở phía đông.</p>
        <p>Chòm sao Bạch Dương có ba ngôi sao nổi bật tạo thành một chùm sao, được Johann Bayer đặt tên là Alpha, Beta và Gamma Arietis. Cả ba ngôi sao này thường được sử dụng trong ngành hàng hải.</p>
        <p>Bạch Dương là nơi diễn ra nhiều trận mưa sao băng. Mưa sao băng Arietid ban ngày là một trong những trận mưa sao băng mạnh nhất xảy ra vào ban ngày, kéo dài từ ngày 22 tháng 5 đến ngày 2 tháng 6. Đây là trận mưa sao băng hàng năm liên quan đến nhóm sao chổi Marsden, đạt cực đại vào ngày 7 tháng 6 với mật độ sao băng thiên đỉnh tối đa mỗi giờ là 54 sao băng. Mưa sao băng Delta Arietid là một trận mưa sao băng khác tỏa ra từ Bạch Dương. Đạt cực đại vào ngày 9 tháng 12 với mật độ sao băng thấp, trận mưa sao băng kéo dài từ ngày 8 tháng 12 đến ngày 14 tháng 1, với mật độ cao nhất có thể nhìn thấy từ ngày 8 đến ngày 14 tháng 12. Mưa sao băng Arietid mùa thu cũng tỏa ra từ Bạch Dương. Trận mưa sao băng kéo dài từ ngày 7 tháng 9 đến ngày 27 tháng 10 và đạt cực đại vào ngày 9 tháng 10</p>

        <h2>2. Truyền thuyết</h2>
        <p>Không có gì ngạc nhiên khi thấy một con cừu đực trên bầu trời, bởi cừu đực thường được hiến tế cho các vị thần, và Zeus đôi khi cũng được đồng nhất với một con cừu đực. Tuy nhiên, các nhà thần thoại học đều đồng ý rằng Aries là một con cừu đực đặc biệt vì con cừu này có bộ lông vàng, là mục tiêu trong chuyến hành trình của Jason và Argonauts. Con cừu đực này xuất hiện trên Trái Đất đúng lúc Vua Athamas xứ Boeotia sắp hiến tế con trai mình là Phrixus để ngăn chặn nạn đói sắp xảy ra.</p>
        <p>Vua Athamas và vợ là Nephele có một cuộc hôn nhân không hạnh phúc, vì vậy Athamas đã tìm đến Ino, con gái của Vua Cadmus từ xứ Thebes lân cận. Ino căm ghét hai người con riêng của chồng mình, Phrixus và Helle, và bà đã lập mưu giết chết họ. Bà bắt đầu bằng cách sấy khô lúa mì để mùa màng thất bát. Khi Athamas cầu cứu Nhà tiên tri Delphic, Ino đã hối lộ các sứ giả để mang về một câu trả lời giả rằng Phrixus phải bị hiến tế để cứu mùa màng.</p>
        
        <h2>3. Vị trí trên bầu trời và khoảng thời gian quan sát</h2>
        <p>Bạch Dương (Aries) là một chòm sao hoàng đạo nhỏ, nằm giữa Song Ngư (Pisces) và Kim Ngưu (Taurus).</p>
        <p>Có thể quan sát rõ nhất vào mùa thu – đông ở bán cầu Bắc (từ tháng 11 đến tháng 1).</p>
        <p>RA (Xích kinh): khoảng từ 1h 40m đến 3h 30m</p>
        <p>Dec (Xích vĩ): từ +10° đến +30°</p>

        <h2>4. Ngôi sao nổi bật nhất</h2>
        <ul>
            <li class="list-item"><span class="list-title">α Arietis (Hamal):</span> sao sáng nhất của Bạch Dương, là sao khổng lồ cam, cách Trái Đất 66 năm ánh sáng.</li>
            <li class="list-item"><span class="list-title">β Arietis (Sheratan):</span> sao đôi, cách Trái Đất khoảng 60 năm ánh sáng.</li>
            <li class="list-item"><span class="list-title">γ Arietis (Mesartim):</span> hệ sao đôi, thường được gọi là “sao đôi của Bạch Dương”.</li>
        </ul>

        <h2>5. Thiên thể đặc biệt</h2>
        <p>Bạch Dương vẫn có một vài thiên thể đặc biệt, chủ yếu là thiên hà mờ, quan sát được bằng kính thiên văn cỡ vừa – lớn:</p>
        <ul>
            <li class="list-item"><span class="list-title">NGC 772:</span> thiên hà xoắn ốc không đối xứng, cách Trái Đất khoảng 130 triệu năm ánh sáng, sáng khoảng cấp 10, đôi khi gọi là "thiên hà không cân xứng".</li>
            <li class="list-item"><span class="list-title">NGC 1156:</span> thiên hà lùn bất thường, cách khoảng 25 triệu năm ánh sáng.</li>
            <li class="list-item"><span class="list-title">NGC 697 & NGC 972:</span> các thiên hà xoắn ốc nhỏ, mờ.</li>
        </ul>

        <h2>6. Ý nghĩa chiêm tinh học và thiên văn học</h2>
        <p>Bạch Dương là cung hoàng đạo mà Mặt Trời đi qua vào khoảng 21/3 đến 19/4.</p>
        <p>Trong chiêm tinh học, đây là cung đầu tiên của vòng hoàng đạo, tượng trưng cho sự khởi đầu, năng lượng và hành động.</p>
        <p>Trong thiên văn, trước đây điểm xuân phân nằm trong chòm Bạch Dương, vì vậy tên gọi “Điểm Aries” vẫn còn được dùng trong thiên văn học hiện đại.</p>

        <p class="quote">“Đừng sợ thất bại, lòng dũng cảm của bạn chính là ngọn lửa mở đường cho những thành công phía trước.”</p>
    </div>
</body>
</html>
