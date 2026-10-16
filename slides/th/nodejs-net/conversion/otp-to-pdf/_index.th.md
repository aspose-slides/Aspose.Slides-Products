---
lastmod: 2024-04-10
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: แปลง OTP เป็น PDF ใน JavaScript
url: /th/nodejs-net/conversion/otp-to-pdf/
keywords: OTP เป็น PDF, แปลง OTP เป็น PDF, Node.js API, ไลบรารี JavaScript, OTP, PDF
description: แปลง OTP เป็น PDF ใน JavaScript ใช้ API ไลบรารี Node.js เพื่อแปลงไฟล์ OTP เป็น PDF
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="แปลง OTP เป็น PDF ใน JavaScript" h2="Aspose.Slides สำหรับ Node.js ผ่าน .NET เป็นไลบรารีที่ทรงพลังและใช้งานง่ายที่ให้คุณแปลงงานนำเสนอ PowerPoint เป็นรูปแบบต่างๆ ใน ​​JavaScript รองรับองค์ประกอบและรูปแบบการนำเสนอทั้งหมด และมี API ที่หลากหลายเพื่อเข้าถึงและแก้ไข นอกจากนี้ยังช่วยให้คุณสามารถส่งออกสไลด์ของคุณไปยังรูปแบบต่างๆ เพื่อการประมวลผลหรือการแชร์เพิ่มเติม" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="แปลง OTP เป็น PDF โดยใช้ JavaScript" variant="code" %}}

หากต้องการแปลง OTP เป็น PDF คุณจะต้องสร้างงานนำเสนอจากไฟล์ OTP และบันทึกเป็น PDF

{{< blocks/products/pf/slides-design-update-10-2026/code title="โค้ด JavaScript สำหรับแปลง OTP เป็น PDF" >}}
```javascript

const fs = require('fs');
const asposeSlides = require('aspose.slides.via.net');
const { Presentation, SaveFormat } = asposeSlides;
var pres = new Presentation("welcome-to-powerpoint.otp");
try
{
    pres.save("output.pdf", SaveFormat.Pdf);
}
finally
{
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="แปลง OTP เป็น PDF ใน Node.js" %}}

[**Aspose.Slides สำหรับ Node.js ผ่าน .NET**](https://products.aspose.com/slides/th/nodejs-net/) เป็นไลบรารี Node.js อันทรงพลังสำหรับการสร้างและจัดการไฟล์งานนำเสนอ นอกจากนี้ยังมีวิธีที่ยืดหยุ่นในการแปลง OTP เป็น PDF เมื่อใช้ **Aspose.Slides สำหรับ Node.js ผ่าน .NET** นักพัฒนาหรือแอปพลิเคชันใดๆ ก็สามารถแปลงไฟล์ OTP เป็น PDF ได้โดยใช้โค้ดเพียงไม่กี่บรรทัด

ในฐานะ API การประมวลผลเอกสารสมัยใหม่ Aspose.Slides สำหรับ Node.js ผ่าน .NET จะส่งออกไฟล์ OTP ไปเป็นรูปแบบไฟล์ PDF อย่างรวดเร็ว ไลบรารี Aspose PowerPoint ช่วยให้คุณสามารถแปลง OTP เป็น PDF และรูปแบบไฟล์อื่นๆ อีกมากมาย

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="วิธีแปลง OTP เป็น PDF โดยใช้ Aspose.Slides สำหรับ Node.js ผ่าน .NET API" intro="หากต้องการแปลง OTP เป็น PDF โดยใช้ Aspose.Slides สำหรับ Node.js ผ่าน .NET คุณจะต้องนำเข้าแพ็กเกจในไฟล์ JavaScript ของคุณและสร้างอินสแตนซ์ของคลาส Presentation คลาสการนำเสนอแสดงถึงเอกสาร PowerPoint และจัดเตรียมวิธีการเข้าถึงและจัดการองค์ประกอบต่างๆ" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ติดตั้ง [**Aspose.Slides สำหรับ Node.js ผ่าน .NET**](https://products.aspose.com/slides/th/nodejs-net/){{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เพิ่มการอ้างอิงไลบรารี (นำเข้าไลบรารี) ให้กับโปรเจ็กต์ Node.js ของคุณ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เปิดไฟล์ต้นฉบับ OTP ใน Node.js{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}บันทึกผลลัพธ์เป็นไฟล์ PDF{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="แปลง OTP เป็นรูปแบบอื่นที่รองรับ" subTitle="คุณยังสามารถแปลง OTP และบันทึกเป็นรูปแบบไฟล์อื่นๆ ได้ด้วย ดูรูปแบบที่รองรับทั้งหมดด้านล่าง" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/nodejs-net/conversion/otp-to-pptx/" name="OTP TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/nodejs-net/conversion/otp-to-ppt/" name="OTP TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/nodejs-net/conversion/otp-to-html/" name="OTP TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/nodejs-net/conversion/otp-to-png/" name="OTP TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/nodejs-net/conversion/otp-to-bmp/" name="OTP TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/nodejs-net/conversion/otp-to-jpg/" name="OTP TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/nodejs-net/conversion/otp-to-fodp/" name="OTP TO FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/nodejs-net/conversion/otp-to-gif/" name="OTP TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/nodejs-net/conversion/otp-to-odp/" name="OTP TO ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/nodejs-net/conversion/otp-to-pot/" name="OTP TO POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/nodejs-net/conversion/otp-to-potm/" name="OTP TO POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/nodejs-net/conversion/otp-to-potx/" name="OTP TO POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/nodejs-net/conversion/otp-to-pps/" name="OTP TO PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/nodejs-net/conversion/otp-to-ppsm/" name="OTP TO PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/nodejs-net/conversion/otp-to-ppsx/" name="OTP TO PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/nodejs-net/conversion/otp-to-pptm/" name="OTP TO PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/nodejs-net/conversion/otp-to-svg/" name="OTP TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/nodejs-net/conversion/otp-to-tiff/" name="OTP TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
