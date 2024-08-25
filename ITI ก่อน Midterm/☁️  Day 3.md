
### **Types of Server Machines/Hardware**

- **Tower Servers**: เซิร์ฟเวอร์ขนาดใหญ่ตั้งอยู่ในโครงสร้างแนวตั้ง (ตัวอย่าง: Dell PowerEdge T440)
- **Rack Servers**: เซิร์ฟเวอร์ที่ติดตั้งในตู้แร็ค มาตรฐานขนาด 19 นิ้ว (ตัวอย่าง: Dell PowerEdge R440)
- **Blade Servers**: เซิร์ฟเวอร์ที่ถูกออกแบบให้มีความหนาเพียงเล็กน้อย เหมาะกับการติดตั้งในพื้นที่จำกัด (ตัวอย่าง: Dell PowerEdge M630)

### **Server Memory**

- **RDIMM**: Registered DIMM, ความเร็วสูง มักใช้ในเซิร์ฟเวอร์
- **LRDIMM**: Load-Reduced DIMM, ความจุสูงกว่า RDIMM
- **ECC Memory**: Error-Correcting Code Memory, ป้องกันข้อผิดพลาดในการเก็บข้อมูล

### **Storage Technologies**

- **SATA (Serial ATA)**: เหมาะสำหรับการจัดเก็บข้อมูล มีราคาถูก ความจุสูง
- **SAS (Serial Attached SCSI)**: เหมาะสำหรับเซิร์ฟเวอร์และเวิร์กสเตชัน ให้ความเร็วในการอ่าน/เขียนสูงกว่า SATA
- **PCIe (PCI Express)**: เทคโนโลยีที่ให้ความเร็วในการส่งข้อมูลสูงสุด เหมาะสำหรับการใช้งานกับ SSDs

### **Cloud Service Models**

- **IaaS (Infrastructure as a Service)**: ผู้ใช้สามารถสร้างโครงสร้างพื้นฐาน IT ที่กำหนดเองได้ตามต้องการ (ตัวอย่าง: Amazon EC2)
- **PaaS (Platform as a Service)**: ให้แพลตฟอร์มสำหรับพัฒนาและจัดการแอปพลิเคชัน (ตัวอย่าง: Google App Engine)
- **SaaS (Software as a Service)**: บริการซอฟต์แวร์ที่สามารถใช้งานผ่านอินเทอร์เน็ตได้ทันที (ตัวอย่าง: Google Apps)

### **Edge Computing**

- **Edge Servers**: เซิร์ฟเวอร์ที่ตั้งอยู่ใกล้กับผู้ใช้เพื่อลดเวลาในการตอบสนอง (Latency) มีสองประเภทหลัก:
    - **CDN Edge Servers**: ใช้สำหรับการจัดส่งเนื้อหาเช่น HTML, CSS, JavaScript
    - **Edge Compute Servers**: ใช้สำหรับประมวลผลข้อมูล เช่น การประมวลผลข้อมูลจาก IoT

### **Performance and Benchmarking**

- **Measuring Performance**: ใช้เกณฑ์เช่น ความเร็ว (Speed), ความน่าเชื่อถือ (Reliability), ความพร้อมใช้งาน (Availability)
- **Benchmarking Tools**: ใช้ทดสอบและเปรียบเทียบประสิทธิภาพของฮาร์ดแวร์และซอฟต์แวร์ (ตัวอย่าง: CPU-Z)

### **Magnetic Tape**

- **ใช้สำหรับการสำรองข้อมูลขนาดใหญ่**: แม้ว่าจะเก็บข้อมูลได้มาก แต่การเข้าถึงข้อมูลจะช้ากว่าเทคโนโลยีอื่นเนื่องจากต้องใช้การอ่านข้อมูลแบบต่อเนื่อง

### **USB Ports**

- **USB Types and Versions**: มีหลากหลายรูปแบบและความเร็ว เช่น USB 3.2, USB 4.0, USB-C

### **System Bus**

- **Data Bus**: ส่งข้อมูลระหว่างหน่วยประมวลผล, หน่วยความจำ, และอุปกรณ์ I/O
- **Address Bus**: กำหนดที่อยู่ของข้อมูลในระบบ
- **Control Bus**: ควบคุมและสั่งการให้ดำเนินการต่างๆ ในระบบ