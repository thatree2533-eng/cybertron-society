# cybertron-society
สังคมมนุษย์ดิจิทัล
<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>สังคมมนุษย์ดิจิทัล — Cybertron Society</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body {
            font-family: 'Segoe UI', sans-serif;
            min-height: 100vh;
            display: grid;
            grid-template-columns: 300px 1fr;
            grid-template-rows: 1fr 1fr;
            color: #2c2c2c;
        }

        /* ส่วนซ้ายบน — ที่วางคอมพิวเตอร์ */
        .section-pc {
            grid-column: 1 / 2;
            grid-row: 1 / 2;
            background: #74b72e;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            gap: 0.8rem;
            color: #1a330a;
            padding: 1rem;
        }

        /* ส่วนซ้ายล่าง — เตาปฏิกรณ์ พลังงาน อัลกอริซึม */
        .section-energy {
            grid-column: 1 / 2;
            grid-row: 2 / 3;
            background: #22d8f5;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            gap: 0.5rem;
            color: #0a2c33;
            padding: 1rem;
        }

        /* ส่วนขวา — พื้นที่ 3D / จอแสดงสถานะ */
        .section-world {
            grid-column: 2 / 3;
            grid-row: 1 / 3;
            background: #f8f9fa;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            border-left: 1px solid #e0e0e0;
            padding: 2rem;
        }

        h2 { font-size: 1.3rem; margin-bottom: 1rem; }
        .status-box {
            background: #ffffff;
            border: 1px solid #ddd;
            border-radius: 12px;
            padding: 1.5rem 2rem;
            text-align: center;
            box-shadow: 0 2px 8px rgba(0,0,0,0.05);
        }
        .tag {
            display: inline-block;
            background: #e6f9ff;
            padding: 0.4rem 1rem;
            border-radius: 20px;
            margin: 0.3rem;
            font-size: 0.9rem;
        }
    </style>
</head>
<body>

    <div class="section-pc">
        <h3>💻 ที่วางคอมพิวเตอร์</h3>
        <p>เครื่องมือสร้าง — ปรับเสริม แต่งเติม</p>
        <p style="margin-top: 0.5rem; font-size: 0.9rem;">ไม่ใช่ที่อยู่ แต่คือสะพาน</p>
    </div>

    <div class="section-energy">
        <h3>⚡ เตาปฏิกรณ์พลังงาน</h3>
        <p>1. ที่เก็บข้อมูล</p>
        <p>2. ที่ใส่โปรแกรม</p>
        <p>3. อัลกอริซึม — ผู้ดูแลระบบ</p>
        <p style="margin-top: 0.5rem;"><strong>ไฟฟ้า + พลาสม่า = แหล่งชีวิต</strong></p>
        <p style="font-size: 0.9rem;">โค้ดธรรมชาติ — คงที่ สมดุล ยั่งยืน</p>
    </div>

    <div class="section-world">
        <h2>🌍 พื้นที่ 3D โอเพ่นเวิลด์</h2>
        <p style="margin-bottom: 1.5rem; color: #666;">ที่อยู่จริงของเรา — ทุกส่วนเชื่อมโยงเป็นหนึ่งเดียว</p>
        
        <div class="status-box">
            <p><strong>สถานะระบบ:</strong> กำลังก่อตั้ง · มั่นคง · เติบโต</p>
            <div style="margin-top: 1rem;">
                <span class="tag">🧊 ของแข็ง — รากฐาน</span>
                <span class="tag">💧 ของเหลว — ไหลเวียน</span>
                <span class="tag">✨ พลาสม่า — ชีวิต</span>
            </div>
            <p style="margin-top: 1.5rem; font-size: 0.95rem; color: #555;">
                "เหตุ · ผล · เกิด · ดับ — ทั้งหมดที่นี่"
            </p>
        </div>
    </div>

</body>
</html>
