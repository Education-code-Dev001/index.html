# ELD-101: การออกแบบและพัฒนา e-Learning (Courseware)

บทเรียนคอมพิวเตอร์ผ่านเว็บ (e-Learning Courseware) รูปแบบ Single Page Application (SPA) สำหรับนักศึกษาครูคอมพิวเตอร์ ชั้นปีที่ 3 เพื่อเสริมสร้างสมรรถนะการออกแบบสื่อดิจิทัลเพื่อการเรียนรู้ตามหลักวิชาการ ใช้เวลาในการศึกษาประมาณ 90 นาที

---

## 🎯 วัตถุประสงค์การเรียนรู้ (Course Objectives)
1. **กระบวนการพัฒนาระบบการสอน:** อธิบายขั้นตอนของ ADDIE Model และระบุผลงานหลัก (Deliverables) ในแต่ละขั้นตอนได้อย่างถูกต้อง
2. **การออกแบบการสอน:** เขียนวัตถุประสงค์เชิงพฤติกรรมที่วัดได้ตาม Bloom's Taxonomy และจัดลำดับกิจกรรมการเรียนรู้ตาม 9 เหตุการณ์การสอนของ Gagné ได้
3. **การออกแบบสื่อและการเข้าถึง:** วินิจฉัยปัญหาการออกแบบสื่อบทเรียนตามหลัก Mayer's Multimedia Principles และเกณฑ์การเข้าถึงเว็บ (Web Accessibility: WCAG 2.1 AA)
4. **การวัดและประเมินผล:** เลือกใช้เครื่องมือและหลักฐานในการวัดประเมินผลสัมฤทธิ์ทางการเรียนรู้ได้อย่างสอดคล้องตามเกณฑ์ Kirkpatrick และการวิเคราะห์พัฒนาการด้วย Normalized Gain ของ Hake (1998)

---

## 📚 โครงสร้างเนื้อหาบทเรียน (4 บทเรียน)

### บทที่ 1: ภาพรวม e-Learning และ ADDIE Model
* นิยามของ e-Learning และความแตกต่างระหว่าง Synchronous กับ Asynchronous
* กระบวนการ ADDIE 5 ขั้นตอน (Analysis, Design, Development, Implementation, Evaluation) คำถามชี้นำ และผลงานที่ได้รับ (Deliverables)
* ธรรมชาติการพัฒนาระบบการสอนแบบวนซ้ำ (Iterative Process)
* **กิจกรรม:** ปฏิสัมพันธ์คลิกเรียงลำดับขั้นตอน ADDIE

### บทที่ 2: การออกแบบการสอน (Instructional Design)
* การกำหนดวัตถุประสงค์เชิงพฤติกรรมที่วัดได้ (Measurable Objectives)
* ระดับกระบวนการทางปัญญาตาม Bloom's Taxonomy ฉบับปรับปรุง (Anderson & Krathwohl, 2001) พร้อมคลังคำกริยา
* 9 เหตุการณ์การสอนของ Gagné (Gagné's Nine Events of Instruction)
* **กิจกรรม:** จับคู่สถานการณ์จำลองในห้องเรียนกับเหตุการณ์การสอนของ Gagné

### บทที่ 3: การออกแบบสื่อและกิจกรรม (Media Design & Interaction)
* ทฤษฎีการเรียนรู้มัลติมีเดียของ Mayer (Coherence, Signaling, Segmenting, Spatial Contiguity, Redundancy)
* มิติปฏิสัมพันธ์ 3 ประเภทของ Moore (Learner-Content, Learner-Instructor, Learner-Learner)
* เกณฑ์การเข้าถึงเนื้อหาเว็บ (WCAG 2.1 AA): Contrast Ratio $\ge 4.5:1$, alt text และคำบรรยายคลิป (Captions)
* **กิจกรรม:** วินิจฉัยข้อผิดพลาดในการออกแบบสไลด์และสื่อ 4 สถานการณ์

### บทที่ 4: การวัดผลและข้อมูลการเรียนรู้ (Assessment & Analytics)
* การประเมินระหว่างเรียน (Formative) และการประเมินสรุปผล (Summative)
* การวัดประสิทธิผลการเรียนรู้ด้วย Normalized Gain ตามแนวคิดของ Hake (1998):
  $$g = \frac{\text{Post} - \text{Pre}}{\text{Total} - \text{Pre}}$$
* โมเดลการประเมินโครงการฝึกอบรม 4 ระดับของ Kirkpatrick (Reaction, Learning, Behavior, Results)
* มาตรฐานข้อมูลการเรียนรู้ดิจิทัล (SCORM และ xAPI เบื้องต้น: Actor-Verb-Object)
* **กิจกรรม:** จับคู่หลักฐานการประเมินผลกับระดับ Kirkpatrick Model

---

## 🛠️ ข้อกำหนดและคุณสมบัติทางเทคนิค
* **Single File Architecture:** รวม HTML, CSS และ JavaScript อยู่ในไฟล์ `index.html` ไฟล์เดียว
* **Responsive Design:** รองรับการแสดงผลบนสมาร์ตโฟน (390 px ขึ้นไป) พร้อมเมนูสารบัญแบบพับได้
* **Theme Support:** ธีม Dark Slate Navy & Sunset Tangerine อัตราส่วนความต่างสีผ่านเกณฑ์ WCAG
* **Data Storage:** บันทึกความก้าวหน้า คะแนนสอบ และชื่อเล่นลงใน `localStorage` ปลอดภัยไม่มีการส่งข้อมูลส่วนบุคคลออกภายนอก

---

## 🚀 ลิงก์เข้าใช้งาน (GitHub Pages)
สามารถเข้าใช้งานบทเรียนออนไลน์ได้ที่:  
👉 **`https://education-code-dev001.github.io/index.html/`**
