<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ครูอายสอนบัญชี</title>
    <style>
        body {
            font-family: 'Sarabun', sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #4a69bd;
            color: white;
            text-align: center;
            padding: 1rem;
        }
        nav {
            background-color: #6a89cc;
            padding: 0.5rem;
        }
        nav ul {
            list-style-type: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin-right: 10px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
        }
        main {
            padding: 20px;
        }
        .course-list {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
        }
        .course {
            background-color: #f1f2f6;
            border-radius: 5px;
            margin-bottom: 20px;
            padding: 15px;
            width: calc(50% - 10px);
        }
        footer {
            background-color: #4a69bd;
            color: white;
            text-align: center;
            padding: 1rem;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>ครูอายสอนบัญชี</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#home">หน้าหลัก</a></li>
            <li><a href="#courses">รายวิชา</a></li>
            <li><a href="#about">เกี่ยวกับเรา</a></li>
            <li><a href="#contact">ติดต่อ</a></li>
        </ul>
    </nav>
    <main>
        <section id="home">
            <h2>ยินดีต้อนรับสู่เว็บไซต์ครูอายสอนบัญชี</h2>
            <p>เว็บไซต์นี้รวบรวมข้อมูลเกี่ยวกับรายวิชาการสอนของสาขาวิชาการบัญชี ทั้งในระดับ ปวช. และ ปวส.</p>
        </section>
        <section id="courses">
            <h2>รายวิชา</h2>
            <div class="course-list">
                <div class="course">
                    <h3>ระดับ ปวช.</h3>
                    <ul>
                        <li>การบัญชีเบื้องต้น</li>
                        <li>การบัญชีซื้อขายสินค้า</li>
                        <li>การบัญชีห้างหุ้นส่วน</li>
                        <li>การบัญชีบริษัทจำกัด</li>
                        <li>การบัญชีกิจการพิเศษ</li>                      
                        <li>การบัญชีภาษีเงินได้บุคคลธรรมดา</li>
                    </ul>
                </div>
                <div class="course">
                    <h3>ระดับ ปวส.</h3>
                    <ul>
                        <li>การบัญชีชั้นกลาง1</li>
                        <li>การบัญชีชั้นกลาง2</li>
                    </ul>
                </div>
            </div>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 ครูอายสอนบัญชี</p>
    </footer>
</body>
</html>
