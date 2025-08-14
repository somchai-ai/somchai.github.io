<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>โปรไฟล์บริษัท | ตัวอย่าง</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&family=Noto+Sans+Thai:wght@400;600;700&display=swap');
        body {
            font-family: 'Noto Sans Thai', 'Inter', sans-serif;
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">

    <!-- ส่วนหัว (Header) -->
    <header class="sticky top-0 z-50 bg-white shadow-sm">
        <nav class="container mx-auto px-6 py-4 flex justify-between items-center">
            <!-- โลโก้บริษัท -->
            <a href="#" class="text-2xl font-bold text-indigo-600">
                ชื่อบริษัท
            </a>
            
            <!-- เมนูนำทาง -->
            <ul class="hidden md:flex space-x-8">
                <li><a href="#home" class="text-gray-600 hover:text-indigo-600 transition-colors duration-300">หน้าแรก</a></li>
                <li><a href="#about" class="text-gray-600 hover:text-indigo-600 transition-colors duration-300">เกี่ยวกับเรา</a></li>
                <li><a href="#services" class="text-gray-600 hover:text-indigo-600 transition-colors duration-300">บริการ</a></li>
                <li><a href="#contact" class="text-gray-600 hover:text-indigo-600 transition-colors duration-300">ติดต่อ</a></li>
            </ul>
            
            <!-- ปุ่มสำหรับ Mobile Menu (ซ่อนใน Desktop) -->
            <button id="menu-button" class="md:hidden text-gray-600 hover:text-indigo-600 focus:outline-none">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path>
                </svg>
            </button>
        </nav>
        <!-- Mobile Menu (ซ่อนใน Desktop) -->
        <div id="mobile-menu" class="hidden md:hidden bg-white shadow-lg py-4">
            <a href="#home" class="block px-6 py-2 text-gray-600 hover:bg-gray-100">หน้าแรก</a>
            <a href="#about" class="block px-6 py-2 text-gray-600 hover:bg-gray-100">เกี่ยวกับเรา</a>
            <a href="#services" class="block px-6 py-2 text-gray-600 hover:bg-gray-100">บริการ</a>
            <a href="#contact" class="block px-6 py-2 text-gray-600 hover:bg-gray-100">ติดต่อ</a>
        </div>
    </header>

    <main>
        <!-- ส่วนหน้าหลัก (Hero Section) -->
        <section id="home" class="bg-indigo-600 text-white min-h-screen flex items-center justify-center p-6">
            <div class="text-center max-w-4xl">
                <h1 class="text-4xl md:text-6xl font-extrabold tracking-tight leading-tight mb-4">
                    เราสร้างอนาคตไปพร้อมกับคุณ
                </h1>
                <p class="text-lg md:text-xl font-light mb-8">
                    ภารกิจของเราคือการนำเสนอโซลูชันที่สร้างสรรค์และมีคุณภาพสูง เพื่อขับเคลื่อนธุรกิจของคุณให้เติบโตอย่างยั่งยืน
                </p>
                <a href="#contact" class="bg-white text-indigo-600 font-semibold py-3 px-8 rounded-full shadow-lg hover:bg-gray-200 transition-colors duration-300">
                    ติดต่อเรา
                </a>
            </div>
        </section>

        <!-- ส่วนเกี่ยวกับเรา (About Us Section) -->
        <section id="about" class="py-20 bg-white">
            <div class="container mx-auto px-6 grid md:grid-cols-2 gap-12 items-center">
                <div class="order-2 md:order-1">
                    <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-4">เกี่ยวกับบริษัทของเรา</h2>
                    <p class="text-gray-600 text-lg mb-6">
                        ชื่อบริษัทของเราก่อตั้งขึ้นด้วยวิสัยทัศน์ที่จะเป็นผู้นำในอุตสาหกรรม... เรามุ่งมั่นที่จะนำเสนอผลิตภัณฑ์และบริการที่ตอบสนองความต้องการของลูกค้าอย่างแท้จริง
                    </p>
                    <p class="text-gray-600 text-lg">
                        ทีมงานของเราประกอบด้วยผู้เชี่ยวชาญที่มีความสามารถและประสบการณ์สูง พร้อมที่จะมอบสิ่งที่ดีที่สุดให้กับทุกๆ โปรเจกต์ที่เราได้รับมอบหมาย เราเชื่อมั่นในคุณค่าของการทำงานร่วมกันและความมุ่งมั่นสู่ความเป็นเลิศ
                    </p>
                </div>
                <div class="order-1 md:order-2">
                    <!-- รูปภาพเกี่ยวกับเรา - สามารถเปลี่ยน URL ได้ -->
                    <img src="https://placehold.co/800x600/6366f1/ffffff?text=Company+Team" alt="ทีมงานบริษัท" class="w-full h-auto rounded-lg shadow-xl object-cover">
                </div>
            </div>
        </section>

        <!-- ส่วนบริการ (Services Section) -->
        <section id="services" class="py-20 bg-gray-100">
            <div class="container mx-auto px-6 text-center">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-12">บริการของเรา</h2>
                <div class="grid sm:grid-cols-2 lg:grid-cols-3 gap-8">
                    <!-- การ์ดบริการ 1 -->
                    <div class="bg-white p-8 rounded-lg shadow-md hover:shadow-xl transition-shadow duration-300 transform hover:-translate-y-2">
                        <svg class="w-12 h-12 text-indigo-600 mx-auto mb-4" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9.75 17L12 21M14.25 17L12 21M12 21V3M12 3a2 2 0 012 2v2a2 2 0 01-2 2z"></path>
                        </svg>
                        <h3 class="text-xl font-semibold mb-2">บริการที่ 1</h3>
                        <p class="text-gray-600">คำอธิบายสั้นๆ ของบริการนี้ อธิบายว่าลูกค้าจะได้รับประโยชน์อะไร</p>
                    </div>
                    <!-- การ์ดบริการ 2 -->
                    <div class="bg-white p-8 rounded-lg shadow-md hover:shadow-xl transition-shadow duration-300 transform hover:-translate-y-2">
                        <svg class="w-12 h-12 text-indigo-600 mx-auto mb-4" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6.253v13m0-13C10.832 5.485 9.167 5 7.5 5S4.168 5.485 3 6.253m9 0c1.168-.768 2.832-1.253 4.5-1.253s3.332.485 4.5 1.253m-9 0V11a3 3 0 003 3h.5m-3.5 0a3 3 0 00-3 3v2m3-2v2m-2-2h4m-4 0v2m2-2a2 2 0 012-2h2a2 2 0 012 2z"></path>
                        </svg>
                        <h3 class="text-xl font-semibold mb-2">บริการที่ 2</h3>
                        <p class="text-gray-600">คำอธิบายสั้นๆ ของบริการนี้ อธิบายว่าลูกค้าจะได้รับประโยชน์อะไร</p>
                    </div>
                    <!-- การ์ดบริการ 3 -->
                    <div class="bg-white p-8 rounded-lg shadow-md hover:shadow-xl transition-shadow duration-300 transform hover:-translate-y-2">
                        <svg class="w-12 h-12 text-indigo-600 mx-auto mb-4" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path>
                        </svg>
                        <h3 class="text-xl font-semibold mb-2">บริการที่ 3</h3>
                        <p class="text-gray-600">คำอธิบายสั้นๆ ของบริการนี้ อธิบายว่าลูกค้าจะได้รับประโยชน์อะไร</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- ส่วนติดต่อ (Contact Section) -->
        <section id="contact" class="py-20 bg-white">
            <div class="container mx-auto px-6 text-center">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-4">ติดต่อเรา</h2>
                <p class="text-lg text-gray-600 max-w-2xl mx-auto mb-12">
                    หากคุณมีข้อสงสัยหรือต้องการสอบถามข้อมูลเพิ่มเติม สามารถติดต่อเราได้ตามช่องทางด้านล่างนี้
                </p>
                <div class="grid md:grid-cols-2 gap-12 items-start">
                    <!-- ข้อมูลการติดต่อ -->
                    <div class="text-left">
                        <div class="mb-6">
                            <h3 class="text-xl font-semibold text-gray-900 mb-2">ข้อมูลติดต่อ</h3>
                            <p class="text-gray-600">อีเมล: <a href="mailto:info@yourcompany.com" class="text-indigo-600 hover:underline">info@yourcompany.com</a></p>
                            <p class="text-gray-600">โทรศัพท์: +66 123 456 789</p>
                            <p class="text-gray-600">ที่อยู่: 123 ถนนตัวอย่าง, เขตตัวอย่าง, กรุงเทพฯ 12345</p>
                        </div>
                    </div>
                    <!-- แบบฟอร์มติดต่อ -->
                    <div class="bg-gray-100 p-8 rounded-lg shadow-md text-left">
                        <form action="#" method="POST" class="space-y-4">
                            <div>
                                <label for="name" class="block text-sm font-medium text-gray-700">ชื่อ-นามสกุล</label>
                                <input type="text" id="name" name="name" class="mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-indigo-500 focus:ring-indigo-500 p-2">
                            </div>
                            <div>
                                <label for="email" class="block text-sm font-medium text-gray-700">อีเมล</label>
                                <input type="email" id="email" name="email" class="mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-indigo-500 focus:ring-indigo-500 p-2">
                            </div>
                            <div>
                                <label for="message" class="block text-sm font-medium text-gray-700">ข้อความ</label>
                                <textarea id="message" name="message" rows="4" class="mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-indigo-500 focus:ring-indigo-500 p-2"></textarea>
                            </div>
                            <div>
                                <button type="submit" class="w-full py-2 px-4 border border-transparent rounded-md shadow-sm text-sm font-medium text-white bg-indigo-600 hover:bg-indigo-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-500">
                                    ส่งข้อความ
                                </button>
                            </div>
                        </form>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <!-- ส่วนท้าย (Footer) -->
    <footer class="bg-gray-800 text-gray-300 py-8">
        <div class="container mx-auto px-6 text-center">
            <p>&copy; 2024 ชื่อบริษัท. สงวนลิขสิทธิ์</p>
            <p class="text-sm mt-2">เว็บไซต์นี้เป็นเพียงตัวอย่างเท่านั้น</p>
        </div>
    </footer>

    <!-- JavaScript สำหรับเมนูมือถือ -->
    <script>
        const menuButton = document.getElementById('menu-button');
        const mobileMenu = document.getElementById('mobile-menu');

        menuButton.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });
    </script>
</body>
</html>
