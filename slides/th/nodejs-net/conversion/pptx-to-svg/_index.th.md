---
title: แปลง PPTX เป็น SVG ใน JavaScript
url: /th/nodejs-net/conversion/pptx-to-svg/
keywords: PPTX เป็น SVG, แปลง PPTX เป็น SVG, Node.js API, ไลบรารี JavaScript, PPTX, SVG
description: แปลง PPTX เป็น SVG ใน JavaScript ใช้ API ไลบรารี Node.js เพื่อแปลงไฟล์ PPTX เป็น SVG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="แปลง PPTX เป็น SVG ใน JavaScript" h2="Aspose.Slides สำหรับ Node.js ผ่าน .NET เป็นไลบรารีที่ทรงพลังและใช้งานง่ายที่ให้คุณแปลงงานนำเสนอ PowerPoint เป็นรูปแบบต่างๆ ใน ​​JavaScript รองรับองค์ประกอบและรูปแบบการนำเสนอทั้งหมด และมี API ที่หลากหลายเพื่อเข้าถึงและแก้ไข นอกจากนี้ยังช่วยให้คุณสามารถส่งออกสไลด์ของคุณไปยังรูปแบบต่างๆ เพื่อการประมวลผลหรือการแชร์เพิ่มเติม" >}}

{{% blocks/products/pf/feature-page-section h2="แปลง PPTX เป็น SVG ใน Node.js" %}}

[**Aspose.Slides สำหรับ Node.js ผ่าน .NET**](https://products.aspose.com/slides/th/nodejs-net/) เป็นไลบรารี Node.js อันทรงพลังสำหรับการสร้างและจัดการไฟล์งานนำเสนอ นอกจากนี้ยังมีวิธีที่ยืดหยุ่นในการแปลง PPTX เป็น SVG เมื่อใช้ **Aspose.Slides สำหรับ Node.js ผ่าน .NET** นักพัฒนาหรือแอปพลิเคชันใดๆ ก็สามารถแปลงไฟล์ PPTX เป็น SVG ได้โดยใช้โค้ดเพียงไม่กี่บรรทัด

ในฐานะ API การประมวลผลเอกสารสมัยใหม่ Aspose.Slides สำหรับ Node.js ผ่าน .NET จะส่งออกไฟล์ PPTX ไปเป็นรูปแบบไฟล์ SVG อย่างรวดเร็ว ไลบรารี Aspose PowerPoint ช่วยให้คุณสามารถแปลง PPTX เป็น SVG และรูปแบบไฟล์อื่นๆ อีกมากมาย

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="แปลง PPTX เป็น SVG โดยใช้ JavaScript" %}}
หากต้องการแปลง PPTX เป็น SVG คุณจะต้องสร้างงานนำเสนอจากไฟล์ PPTX และบันทึกเป็น SVG

{{% blocks/products/pf/agp/code-block title="โค้ด JavaScript สำหรับแปลง PPTX เป็น SVG" offSpacer="true" %}}

```javascript

const fs = require('fs');
const asposeSlides = require('aspose.slides.via.net');
const { Presentation, SaveFormat } = asposeSlides;
var pres = new Presentation("welcome-to-powerpoint.pptx");
try
{
    for (let i = 0; i < pres.slides.length; i++) {
        var slideByteArray = pres.slides.get(i).getAsSvg();
        fs.writeFile('slide" + i + ".svg', Buffer.from(slideByteArray), (err) => {
            if (err)
                console.error(err);
        });
    }
}
finally
{
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="วิธีแปลง PPTX เป็น SVG โดยใช้ Aspose.Slides สำหรับ Node.js ผ่าน .NET API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="หากต้องการแปลง PPTX เป็น SVG โดยใช้ Aspose.Slides สำหรับ Node.js ผ่าน .NET คุณจะต้องนำเข้าแพ็กเกจในไฟล์ JavaScript ของคุณและสร้างอินสแตนซ์ของคลาส Presentation คลาสการนำเสนอแสดงถึงเอกสาร PowerPoint และจัดเตรียมวิธีการเข้าถึงและจัดการองค์ประกอบต่างๆ" >}}

{{< blocks/products/pf/agp/step-autogen >}}
ติดตั้ง [**Aspose.Slides สำหรับ Node.js ผ่าน .NET**](https://products.aspose.com/slides/th/nodejs-net/)
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
เพิ่มการอ้างอิงไลบรารี (นำเข้าไลบรารี) ให้กับโปรเจ็กต์ Node.js ของคุณ
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
เปิดไฟล์ต้นฉบับ PPTX ใน Node.js
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
บันทึกผลลัพธ์เป็นไฟล์ SVG
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="แปลง PPTX เป็นรูปแบบอื่นที่รองรับ" subTitle="คุณยังสามารถแปลง PPTX และบันทึกเป็นรูปแบบไฟล์อื่นๆ ได้ด้วย ดูรูปแบบที่รองรับทั้งหมดด้านล่าง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/nodejs-net/conversion/pptx-to-ppt/" name="PPTX TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/nodejs-net/conversion/pptx-to-pdf/" name="PPTX TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/nodejs-net/conversion/pptx-to-html/" name="PPTX TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/nodejs-net/conversion/pptx-to-png/" name="PPTX TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/nodejs-net/conversion/pptx-to-bmp/" name="PPTX TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/nodejs-net/conversion/pptx-to-jpg/" name="PPTX TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/nodejs-net/conversion/pptx-to-fodp/" name="PPTX TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/nodejs-net/conversion/pptx-to-gif/" name="PPTX TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/nodejs-net/conversion/pptx-to-odp/" name="PPTX TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/nodejs-net/conversion/pptx-to-otp/" name="PPTX TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/nodejs-net/conversion/pptx-to-pot/" name="PPTX TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/nodejs-net/conversion/pptx-to-potm/" name="PPTX TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/nodejs-net/conversion/pptx-to-potx/" name="PPTX TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/nodejs-net/conversion/pptx-to-pps/" name="PPTX TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/nodejs-net/conversion/pptx-to-ppsm/" name="PPTX TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/nodejs-net/conversion/pptx-to-ppsx/" name="PPTX TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/nodejs-net/conversion/pptx-to-pptm/" name="PPTX TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/nodejs-net/conversion/pptx-to-tiff/" name="PPTX TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}