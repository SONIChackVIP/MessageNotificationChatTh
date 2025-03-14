<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>เว็บไซต์ของฉัน</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
        }

        header {
            background: #007bff;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }

        nav ul {
            list-style: none;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin: 0 15px;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
        }

        main {
            padding: 20px;
        }

        section {
            margin-bottom: 20px;
        }

        footer {
            text-align: center;
            padding: 10px 0;
            background: #f4f4f4;
        }
    </style>
</head>
<body>
    <header>
        <h1>ยินดีต้อนรับสู่เว็บไซต์ของฉัน</h1>
        <nav>
            <ul>
                <li><a href="#about">เกี่ยวกับเรา</a></li>
                <li><a href="#services">บริการ</a></li>
                <li><a href="#contact">ติดต่อเรา</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="about">
            <h2>เกี่ยวกับเรา</h2>
            <p>นี่คือเว็บไซต์ตัวอย่างที่สร้างขึ้นด้วย HTML, CSS, และ JavaScript</p>
        </section>
        <section id="services">
            <h2>บริการของเรา</h2>
            <ul>
                <li>บริการ 1</li>
                <li>บริการ 2</li>
                <li>บริการ 3</li>
            </ul>
        </section>
        <section id="contact">
            <h2>ติดต่อเรา</h2>
            <form>
                <label for="name">ชื่อ:</label>
                <input type="text" id="name" name="name" required>
                <label for="email">อีเมล:</label>
                <input type="email" id="email" name="email" required>
                <button type="submit">ส่ง</button>
            </form>
        </section>
    </main>
    <footer>
        <p>&copy; 2023 เว็บไซต์ของฉัน</p>
    </footer>
    <script>
        document.addEventListener('DOMContentLoaded', function () {
            // โค้ด JavaScript ที่ใช้งานได้ในเว็บไซต์
            console.log("เว็บไซต์พร้อมใช้งาน!");
        });
    </script>
</body>
</html>
