<!doctype html>
<html lang="vi">
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width,initial-scale=1">
    <meta name="description" content="">
    <title>CẶC</title>
    <link rel="stylesheet" href="styles.css">
    <script defer src="script.js"></script>
</head>
<body>
    <header>
        <h1>CẶCCCCCC</h1>
        <nav>
            <ul>
                <li><a href="#">Trang chủ</a></li>
                <li><a href="#">Giới thiệu</a></li>
                <li><a href="#">Liên hệ</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section>
            <h2>Nội dung chính</h2>
            <p>WEB BẢO TRÌ</p>
            <br>
        </section>

        <aside>
            <h3>Thanh bên</h3>
            <p>Ghi chú hoặc liên kết phụ.</p>
        </aside>
    </main>

    <footer>
        <p>&copy; <span id="year"></span> EOE LLC</p>
    </footer>

    <script>
        // Thiết lập năm hiện tại
        document.getElementById('year').textContent = new Date().getFullYear();
    </script>
</body>
</html>
