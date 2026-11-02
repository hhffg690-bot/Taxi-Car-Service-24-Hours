# Taxi-Car-Service-24-Hours
<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Taxi Car Service 24 Hours (แท็กซี่คาร์เซอร์วิส 24 ชั่วโมง)</title>
    <style>
        * {
            margin:0;
            padding:0;
            box-sizing:border-box;
            font-family: 'Arial', sans-serif;
        }
        body {
            background:#f8f9fc;
            color:#2d2d2d;
        }
        header {
            background:linear-gradient(135deg,#0b1c34,#14305a);
            color:white;
            padding:40px 20px;
            text-align:center;
        }
        h1 {
            font-size:32px;
            margin-bottom:14px;
        }
        .tagline {
            font-size:20px;
            color:#ffd84d;
        }
        section {
            padding:50px 20px;
            max-width:1050px;
            margin:0 auto;
        }
        .hero {
            background:white;
            border-radius:20px;
            padding:40px;
            text-align:center;
            box-shadow:0 8px 20px rgba(0,0,0,0.07);
        }
        .hero h2 {
            font-size:28px;
            margin-bottom:15px;
        }
        .hero p {
            font-size:17px;
            color:#555;
            line-height:1.7;
        }
        .cta {
            background:#c8243a;
            color:white;
            display:inline-block;
            padding:18px 34px;
            border-radius:12px;
            text-decoration:none;
            font-size:20px;
            font-weight:bold;
            margin:25px 0;
        }
        .info-grid {
            display:grid;
            grid-template-columns:repeat(auto-fit, minmax(270px,1fr));
            gap:25px;
            margin-top:40px;
        }
        .card {
            background:white;
            padding:30px;
            border-radius:20px;
            box-shadow:0 8px 20px rgba(0,0,0,0.07);
        }
        .card h3 {
            color:#14305a;
            margin-bottom:12px;
            font-size:20px;
        }
        .car-img {
            width:100%;
            height:210px;
            object-fit:cover;
            border-radius:16px;
            margin-bottom:18px;
        }
        form {
            background:white;
            padding:35px;
            border-radius:20px;
            box-shadow:0 8px 20px rgba(0,0,0,0.07);
        }
        input,textarea,select {
            width:100%;
            padding:14px;
            margin:12px 0;
            border:1px solid #dcdfe6;
            border-radius:12px;
            font-size:16px;
        }
        button {
            background:#14305a;
            color:white;
            padding:16px 28px;
            border:none;
            border-radius:12px;
            cursor:pointer;
            font-size:18px;
            font-weight:bold;
        }
        .note {
            color:#707070;
            font-size:14px;
            margin-top:14px;
        }
        footer {
            background:#0b1c34;
            color:white;
            text-align:center;
            padding:25px;
        }
    </style>
</head>
<body>
    <header>
        <h1>🚗 Taxi Car Service 24 Hours (แท็กซี่คาร์เซอร์วิส 24 ชั่วโมง)</h1>
        <div class="tagline">บริการรถเหมาพร้อมคนขับ 24 ชั่วโมง (Chauffeur‑Driven Car Rental 24 Hours) ทั่วประเทศไทย (Throughout Thailand) ไม่มีนายหน้า (No Middlemen)</div>
    </header>

    <section>
        <div class="hero">
            <h2>เดินทางระดับพรีเมียมไว้วางใจเรา (Premium Travel You Can Trust)</h2>
            <p>รับส่งสนามบินทุกจังหวัด (Airport Transfer Across All Provinces) • เดินทางไป‑กลับต่างจังหวัด (Inter‑province Round Trips) • พร้อมออกเดินทางเร็วที่สุดภายใน 30 นาที* (Ready for Departure Within 30 Minutes*) ด้วยรถหลากประเภทพร้อมคนขับมืออาชีพ (Variety of Vehicles with Professional Drivers)</p>
            <a href="tel:0643287389" class="cta">📞 โทรเลย 064‑328‑7389 (Call Now +66 64‑328‑7389)</a>
            <p class="note">*ขึ้นอยู่กับตำแหน่ง สภาพจราจร และความพร้อมของรถจริง (*Subject to Location, Traffic and Vehicle Availability)</p>
        </div>

        <h2 style="margin-top:50px;text-align:center;">🚙 แกลเลอรี่รถของเรา (Our Vehicle Gallery)</h2>
        <div class="info-grid">
            <div class="card">
                <img src="images/sedan.jpg" alt="รถเก๋งซีดาน 5 ที่นั่ง (5‑Seater Sedan)" class="car-img">
                <h3>🚗 รถเก๋งซีดาน 5 ที่นั่ง (5‑Seater Sedan)</h3>
                <p>สะดวกสบาย คล่องตัว เหมาะรับส่งสนามบินและเดินทางส่วนตัว (Comfortable and Agile, Ideal for Airport Transfers and Private Trips)</p>
            </div>
            <div class="card">
                <img src="images/suv.jpg" alt="SUV 7 ที่นั่ง (7‑Seater SUV)" class="car-img">
                <h3>🚙 SUV 7 ที่นั่ง (7‑Seater SUV)</h3>
                <p>กว้างขวาง เหมาะครอบครัวและกลุ่มเพื่อนเดินทางต่างจังหวัด (Spacious, Perfect for Families and Groups Travelling Between Provinces)</p>
            </div>
            <div class="card">
                <img src="images/van.jpg" alt="รถตู้ VIP (VIP Van)" class="car-img">
                <h3>🚌 รถตู้ VIP (VIP Van)</h3>
                <p>หรูหรา สะดวกสบาย เหมาะกลุ่มใหญ่และการเดินทางสำคัญ (Luxurious and Comfortable, Suitable for Large Groups and Important Trips)</p>
            </div>
            <div class="card">
                <img src="images/camry.jpg" alt="Toyota Camry รับผู้บริหาร (Executive Toyota Camry)" class="car-img">
                <h3>💼 Toyota Camry รับผู้บริหาร (Executive Toyota Camry)</h3>
                <p>ระดับพรีเมียม สง่างาม เหมาะสำหรับผู้บริหารและการเดินทางสำคัญ (Premium and Elegant, Ideal for Executives and Important Travel)</p>
            </div>
        </div>

        <h2 style="margin-top:50px;text-align:center;">📋 บริการหลัก (Main Services)</h2>
        <div class="info-grid">
            <div class="card">
                <h3>✈️ รับส่งสนามบินทุกจังหวัด (Airport Transfer Across All Provinces)</h3>
                <p>บริการรับ‑ส่งสนามบินทั่วประเทศ ตรงเวลา ปลอดภัย สะดวกสบาย (Nationwide Airport Transfer – On Time, Safe and Comfortable)</p>
            </div>
            <div class="card">
                <h3>🗺️ เดินทางไป‑กลับต่างจังหวัด (Inter‑province Round Trips)</h3>
                <p>รับจองเดินทางไปกลับต่างจังหวัดทั่วประเทศไทย ตลอด 24 ชั่วโมง (Book Nationwide Inter‑province Round Trips 24 Hours)</p>
            </div>
            <div class="card">
                <h3>⚡ เรียกรถเร่งด่วน (Urgent Booking)</h3>
                <p>พร้อมออกเดินทางเร็วที่สุดภายใน 30 นาที* เมื่อได้รับการยืนยันจากเรา (Ready for Departure Within 30 Minutes* Upon Confirmation)</p>
            </div>
            <div class="card">
                <h3>✅ ไม่มีนายหน้า (No Middlemen)</h3>
                <p>ติดต่อตรงกับเราโดยตรง ไม่มีค่าธรรมเนียมเพิ่มเติมจากนายหน้า (Contact Us Directly – No Additional Middleman Fees)</p>
            </div>
        </div>

        <h2 style="margin:50px 0 20px;text-align:center;">📩 ส่งคำขอบริการ (Send Booking Request)</h2>
        <form action="https://formspree.io/f/ใส่โค้ดFormspreeตรงนี้" method="POST">
            <input type="text" name="name" placeholder="ชื่อผู้ติดต่อ (Contact Name)" required>
            <input type="tel" name="phone" placeholder="เบอร์โทรติดต่อ (Contact Number)" required>
            <select name="carType" required>
                <option value="">เลือกประเภทรถ (Select Vehicle Type)</option>
                <option value="sedan5">รถเก๋งซีดาน 5 ที่นั่ง (5‑Seater Sedan)</option>
                <option value="suv7">SUV 7 ที่นั่ง (7‑Seater SUV)</option>
                <option value="vanVIP">รถตู้ VIP (VIP Van)</option>
                <option value="camry">Toyota Camry รับผู้บริหาร (Executive Toyota Camry)</option>
            </select>
            <textarea name="detail" rows="5" placeholder="ระบุจุดรับ‑ส่ง / เวลา / จำนวนผู้โดยสาร (State Pick‑up / Drop‑off / Time / Number of Passengers)"></textarea>
            <button type="submit">ส่งคำขอบริการ (Send Request)</button>
        </form>
    </section>

    <footer>
        <p>© Taxi Car Service 24 Hours (แท็กซี่คาร์เซอร์วิส 24 ชั่วโมง) | โทร +66 064‑328‑7389 (Tel +66 64‑328‑7389)</p>
    </footer>
</body>
</html>
