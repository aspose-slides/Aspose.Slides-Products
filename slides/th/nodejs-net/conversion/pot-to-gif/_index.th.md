---
lastmod: 2024-04-10
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: แปลง POT เป็น GIF ใน JavaScript
url: /th/nodejs-net/conversion/pot-to-gif/
keywords: POT เป็น GIF, แปลง POT เป็น GIF, Node.js API, ไลบรารี JavaScript, POT, GIF
description: แปลง POT เป็น GIF ใน JavaScript ใช้ API ไลบรารี Node.js เพื่อแปลงไฟล์ POT เป็น GIF
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="แปลง POT เป็น GIF ใน JavaScript" h2="Aspose.Slides สำหรับ Node.js ผ่าน .NET เป็นไลบรารีที่ทรงพลังและใช้งานง่ายที่ให้คุณแปลงงานนำเสนอ PowerPoint เป็นรูปแบบต่างๆ ใน ​​JavaScript รองรับองค์ประกอบและรูปแบบการนำเสนอทั้งหมด และมี API ที่หลากหลายเพื่อเข้าถึงและแก้ไข นอกจากนี้ยังช่วยให้คุณสามารถส่งออกสไลด์ของคุณไปยังรูปแบบต่างๆ เพื่อการประมวลผลหรือการแชร์เพิ่มเติม" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="แปลง POT เป็น GIF โดยใช้ JavaScript" variant="code" %}}

หากต้องการแปลง POT เป็น GIF คุณจะต้องสร้างงานนำเสนอจากไฟล์ POT และบันทึกเป็น GIF

{{< blocks/products/pf/slides-design-update-10-2026/code title="โค้ด JavaScript สำหรับแปลง POT เป็น GIF" >}}
```javascript

const fs = require('fs');
const asposeSlides = require('aspose.slides.via.net');
const { Presentation, SaveFormat } = asposeSlides;
var pres = new Presentation("welcome-to-powerpoint.pot");
try
{
    pres.save("output.gif", SaveFormat.Gif);
}
finally
{
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="แปลง POT เป็น GIF ใน Node.js" %}}

[**Aspose.Slides สำหรับ Node.js ผ่าน .NET**](https://products.aspose.com/slides/th/nodejs-net/) เป็นไลบรารี Node.js อันทรงพลังสำหรับการสร้างและจัดการไฟล์งานนำเสนอ นอกจากนี้ยังมีวิธีที่ยืดหยุ่นในการแปลง POT เป็น GIF เมื่อใช้ **Aspose.Slides สำหรับ Node.js ผ่าน .NET** นักพัฒนาหรือแอปพลิเคชันใดๆ ก็สามารถแปลงไฟล์ POT เป็น GIF ได้โดยใช้โค้ดเพียงไม่กี่บรรทัด

ในฐานะ API การประมวลผลเอกสารสมัยใหม่ Aspose.Slides สำหรับ Node.js ผ่าน .NET จะส่งออกไฟล์ POT ไปเป็นรูปแบบไฟล์ GIF อย่างรวดเร็ว ไลบรารี Aspose PowerPoint ช่วยให้คุณสามารถแปลง POT เป็น GIF และรูปแบบไฟล์อื่นๆ อีกมากมาย

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="วิธีแปลง POT เป็น GIF โดยใช้ Aspose.Slides สำหรับ Node.js ผ่าน .NET API" intro="หากต้องการแปลง POT เป็น GIF โดยใช้ Aspose.Slides สำหรับ Node.js ผ่าน .NET คุณจะต้องนำเข้าแพ็กเกจในไฟล์ JavaScript ของคุณและสร้างอินสแตนซ์ของคลาส Presentation คลาสการนำเสนอแสดงถึงเอกสาร PowerPoint และจัดเตรียมวิธีการเข้าถึงและจัดการองค์ประกอบต่างๆ" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ติดตั้ง [**Aspose.Slides สำหรับ Node.js ผ่าน .NET**](https://products.aspose.com/slides/th/nodejs-net/){{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เพิ่มการอ้างอิงไลบรารี (นำเข้าไลบรารี) ให้กับโปรเจ็กต์ Node.js ของคุณ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เปิดไฟล์ต้นฉบับ POT ใน Node.js{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}บันทึกผลลัพธ์เป็นไฟล์ GIF{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="แปลง POT เป็นรูปแบบอื่นที่รองรับ" subTitle="คุณยังสามารถแปลง POT และบันทึกเป็นรูปแบบไฟล์อื่นๆ ได้ด้วย ดูรูปแบบที่รองรับทั้งหมดด้านล่าง" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/nodejs-net/conversion/pot-to-pptx/" name="POT TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/nodejs-net/conversion/pot-to-ppt/" name="POT TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/nodejs-net/conversion/pot-to-pdf/" name="POT TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/nodejs-net/conversion/pot-to-html/" name="POT TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/nodejs-net/conversion/pot-to-png/" name="POT TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/nodejs-net/conversion/pot-to-bmp/" name="POT TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/nodejs-net/conversion/pot-to-jpg/" name="POT TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/nodejs-net/conversion/pot-to-fodp/" name="POT TO FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/nodejs-net/conversion/pot-to-odp/" name="POT TO ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/nodejs-net/conversion/pot-to-otp/" name="POT TO OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/nodejs-net/conversion/pot-to-potm/" name="POT TO POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/nodejs-net/conversion/pot-to-potx/" name="POT TO POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/nodejs-net/conversion/pot-to-pps/" name="POT TO PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/nodejs-net/conversion/pot-to-ppsm/" name="POT TO PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/nodejs-net/conversion/pot-to-ppsx/" name="POT TO PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/nodejs-net/conversion/pot-to-pptm/" name="POT TO PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/nodejs-net/conversion/pot-to-svg/" name="POT TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/nodejs-net/conversion/pot-to-tiff/" name="POT TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
