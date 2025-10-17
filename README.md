<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width,initial-scale=1">
    <meta name="description" content="Trang web bảo trì tạm thời">
    <title>Trang Bảo Trì (EOE LLC)</title>
    
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
            line-height: 1.6;
        }

        header {
            background: #333;
            color: #fff;
            padding: 1em 0;
            text-align: center;
        }

        header h1 {
            margin-bottom: 0.5em;
        }

        nav ul {
            padding: 0;
            list-style: none;
            display: flex;
            justify-content: center;
        }

        nav ul li {
            margin: 0 15px;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            font-weight: bold;
        }

        main {
            display: flex;
            max-width: 1100px;
            margin: 20px auto;
            padding: 0 20px;
        }

        section {
            flex: 3;
            padding: 20px;
            background: #fff;
            margin-right: 20px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        aside {
            flex: 1;
            padding: 20px;
            background: #e6e6e6;
            border-radius: 5px;
        }

        footer {
            text-align: center;
            padding: 1em 0;
            background: #333;
            color: #fff;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        
        .maintenance-message {
            text-align: center;
            padding: 50px 0;
            font-size: 1.5em;
            color: #d9534f;
            font-weight: bold;
        }
    </style>

    </head>
<body>
    <header>
        <h1>TRANG WEB ĐANG BẢO TRÌ</h1>
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
            <h2>Thông báo</h2>
            <div class="maintenance-message">
                WEB ĐANG ĐƯỢC NÂNG CẤP VÀ BẢO TRÌ. VUI LÒNG QUAY LẠI SAU.
            </div>
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
        document.getElementById('year').textContent = new Date().getFullYear();
    </script>
</body>
</html>
