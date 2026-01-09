# README — สรุปสิ่งที่เคยทำมา

- ทำ API ด้วย Python 3.12+ สำหรับล็อกอิน/ดึงรายงานและไฟล์เคลมจากระบบภายนอก แล้วแปลงผลลัพธ์เป็นไฟล์ส่งออก (Excel/ZIP) ให้ดาวน์โหลดได้  
- วางมาตรฐาน API งานดาวน์โหลดให้ตอบกลับรูปแบบเดียวกันทุก endpoint (status/message/file_url/file_size/content_type) พร้อมระบบลบไฟล์อัตโนมัติหลังใช้งาน  
- ดูแลระบบงานเบื้องหลังด้วย Celery + Redis (broker) และใช้ Flower ดูสถานะงาน  
- ทำโครงสร้าง HA: ตั้ง HAProxy routing และทำ Cloudflare DNS failover ให้สลับปลายทางได้เมื่อเครื่องล่ม  
- สร้าง/ดูแล MariaDB Galera cluster บน Ubuntu พร้อม WireGuard (10.99.0.0/24) และล็อกพอร์ตด้วย UFW เพื่อความปลอดภัย  
- ทำ data pipeline/import ไฟล์ใหญ่ (หลักแสน–หลักล้านแถว) เน้นเร็ว กันซ้ำ และคิวรีได้ดีด้วย schema/index ที่เหมาะสม  
- ทำ Dashboard ด้วย Next.js/React สำหรับสรุปข้อมูลและติดตามสถานะงาน โดยเน้น UI ตารางและชาร์ตที่ใช้งานจริง  
- ทำรายงาน PDF ภาษาไทยด้วย jsPDF+autoTable พร้อมแก้การวางสระ/วรรณยุกต์ให้แสดงผลถูกต้อง

<!--
**nowzenith/nowzenith** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
-->

<!--
[![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=nowzenith&show_icons=true&theme=tokyonight)](https://github.com/anuraghazra/github-readme-stats)
-->
<!--
[![Harlok's WakaTime stats](https://github-readme-stats.vercel.app/api/wakatime?username=nowzenith)](https://github.com/anuraghazra/github-readme-stats)
-->
