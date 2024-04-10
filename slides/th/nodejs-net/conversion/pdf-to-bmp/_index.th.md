---
title: แปลง PDF เป็น BMP ใน JavaScript
url: /th/nodejs-net/conversion/pdf-to-bmp/
keywords: PDF เป็น BMP, แปลง PDF เป็น BMP, Node.js API, ไลบรารี JavaScript, PDF, BMP
description: แปลง PDF เป็น BMP ใน JavaScript ใช้ API ไลบรารี Node.js เพื่อแปลงไฟล์ PDF เป็น BMP
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="แปลง PDF เป็น BMP ใน JavaScript" h2="Aspose.Slides สำหรับ Node.js ผ่าน .NET เป็นไลบรารีที่ทรงพลังและใช้งานง่ายที่ให้คุณแปลงงานนำเสนอ PowerPoint เป็นรูปแบบต่างๆ ใน ​​JavaScript รองรับองค์ประกอบและรูปแบบการนำเสนอทั้งหมด และมี API ที่หลากหลายเพื่อเข้าถึงและแก้ไข นอกจากนี้ยังช่วยให้คุณสามารถส่งออกสไลด์ของคุณไปยังรูปแบบต่างๆ เพื่อการประมวลผลหรือการแชร์เพิ่มเติม" >}}

{{% blocks/products/pf/feature-page-section h2="แปลง PDF เป็น BMP ใน Node.js" %}}

[**Aspose.Slides สำหรับ Node.js ผ่าน .NET**](https://products.aspose.com/slides/th/nodejs-net/) เป็นไลบรารี Node.js อันทรงพลังสำหรับการสร้างและจัดการไฟล์งานนำเสนอ นอกจากนี้ยังมีวิธีที่ยืดหยุ่นในการแปลง PDF เป็น BMP เมื่อใช้ **Aspose.Slides สำหรับ Node.js ผ่าน .NET** นักพัฒนาหรือแอปพลิเคชันใดๆ ก็สามารถแปลงไฟล์ PDF เป็น BMP ได้โดยใช้โค้ดเพียงไม่กี่บรรทัด

ในฐานะ API การประมวลผลเอกสารสมัยใหม่ Aspose.Slides สำหรับ Node.js ผ่าน .NET จะส่งออกไฟล์ PDF ไปเป็นรูปแบบไฟล์ BMP อย่างรวดเร็ว ไลบรารี Aspose PowerPoint ช่วยให้คุณสามารถแปลง PDF เป็น BMP และรูปแบบไฟล์อื่นๆ อีกมากมาย

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="แปลง PDF เป็น BMP โดยใช้ JavaScript" %}}
หากต้องการแปลง PDF เป็น BMP คุณจะต้องสร้างงานนำเสนอจากไฟล์ PDF และบันทึกเป็น BMP

{{% blocks/products/pf/agp/code-block title="โค้ด JavaScript สำหรับแปลง PDF เป็น BMP" offSpacer="true" %}}

```javascript

const fs = require('fs');
const asposeSlides = require('aspose.slides.via.net');
const { Presentation, SaveFormat, ShapeType } = asposeSlides;

var pres = new Presentation();
try
{
    pres.slides.removeAt(0);
    var slides = pres.slides.addFromPdf("welcome-to-powerpoint.pdf");

    for (let i = 0; i < pres.slides.length; i++) {
        var slide = pres.slides.get(i);
        var image = slide.getThumbnail(new asposeSlides.RenderingOptions(), { width: 1080, height: 960 });

        image.save("slide" + i + ".bmp", ImageFormat.Bmp); 
    }
}
finally
{
    if (pres != null) pres.dispose();
} 

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="วิธีแปลง PDF เป็น BMP โดยใช้ Aspose.Slides สำหรับ Node.js ผ่าน .NET API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="หากต้องการแปลง PDF เป็น BMP โดยใช้ Aspose.Slides สำหรับ Node.js ผ่าน .NET คุณจะต้องนำเข้าแพ็กเกจในไฟล์ JavaScript ของคุณและสร้างอินสแตนซ์ของคลาส Presentation คลาสการนำเสนอแสดงถึงเอกสาร PowerPoint และจัดเตรียมวิธีการเข้าถึงและจัดการองค์ประกอบต่างๆ" >}}

{{< blocks/products/pf/agp/step-autogen >}}
ติดตั้ง [**Aspose.Slides สำหรับ Node.js ผ่าน .NET**](https://products.aspose.com/slides/th/nodejs-net/)
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
เพิ่มการอ้างอิงไลบรารี (นำเข้าไลบรารี) ให้กับโปรเจ็กต์ Node.js ของคุณ
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
เปิดไฟล์ต้นฉบับ PDF ใน Node.js
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
บันทึกผลลัพธ์เป็นไฟล์ BMP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="แปลง PDF เป็นรูปแบบอื่นที่รองรับ" subTitle="คุณยังสามารถแปลง PDF และบันทึกเป็นรูปแบบไฟล์อื่นๆ ได้ด้วย ดูรูปแบบที่รองรับทั้งหมดด้านล่าง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/nodejs-net/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/nodejs-net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/nodejs-net/conversion/pdf-to-html/" name="PDF TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/nodejs-net/conversion/pdf-to-png/" name="PDF TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/nodejs-net/conversion/pdf-to-jpg/" name="PDF TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/nodejs-net/conversion/pdf-to-fodp/" name="PDF TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/nodejs-net/conversion/pdf-to-gif/" name="PDF TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/nodejs-net/conversion/pdf-to-odp/" name="PDF TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/nodejs-net/conversion/pdf-to-otp/" name="PDF TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/nodejs-net/conversion/pdf-to-pot/" name="PDF TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/nodejs-net/conversion/pdf-to-potm/" name="PDF TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/nodejs-net/conversion/pdf-to-potx/" name="PDF TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/nodejs-net/conversion/pdf-to-pps/" name="PDF TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/nodejs-net/conversion/pdf-to-ppsm/" name="PDF TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/nodejs-net/conversion/pdf-to-ppsx/" name="PDF TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/nodejs-net/conversion/pdf-to-pptm/" name="PDF TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/nodejs-net/conversion/pdf-to-svg/" name="PDF TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/nodejs-net/conversion/pdf-to-tiff/" name="PDF TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}