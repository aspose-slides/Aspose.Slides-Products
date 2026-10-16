---
lastmod: 2023-09-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: แปลง PPS เป็น JPG ใน Node.js
url: /th/nodejs-java/conversion/pps-to-jpg/
keywords: PPS เป็น JPG, แปลง PPS เป็น JPG, Node.js API, ไลบรารี Node.js, PPS, JPG
description: แปลง PPS เป็น JPG ใน Node.js ใช้ API ไลบรารี Node.js เพื่อแปลงไฟล์ PPS เป็น JPG
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="แปลง PPS เป็น JPG ใน Node.js" h2="Aspose.Slides สำหรับ Node.js ผ่าน Java เป็นไลบรารีที่ทรงพลังและใช้งานง่ายที่ช่วยให้คุณแปลงงานนำเสนอ PowerPoint เป็นรูปแบบต่างๆ ใน ​​Node.js รองรับองค์ประกอบและรูปแบบการนำเสนอทั้งหมด และยังมี API ที่หลากหลายเพื่อเข้าถึงและแก้ไของค์ประกอบเหล่านั้น นอกจากนี้ยังช่วยให้คุณสามารถส่งออกสไลด์ของคุณไปยังรูปแบบต่างๆ เพื่อการประมวลผลหรือการแชร์เพิ่มเติม" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="แปลง PPS เป็น JPG โดยใช้ Node.js" variant="code" %}}

หากต้องการแปลง PPS เป็น JPG คุณจะต้องสร้างงานนำเสนอจากไฟล์ PPS และบันทึกเป็น JPG

{{< blocks/products/pf/slides-design-update-10-2026/code title="รหัส Node.js สำหรับการแปลง PPS เป็น JPG" >}}
```javascript

var aspose = aspose || {};

aspose.slides = require("aspose.slides.via.java");

var pres = new aspose.slides.Presentation("welcome-to-powerpoint.pps");
try
{
    for(var i = 0; i < pres.getSlides().size(); i++)
    {
        var sld = pres.getSlides().get_Item(i);
        var bi = sld.getThumbnail(2, 2);
        var outputfile = java.newInstanceSync("java.io.File", "slide_" + sld.getSlideNumber() + ".jpg");
        java.callStaticMethod("javax.imageio.ImageIO", "write", bi, "jpeg", outputfile);
    }
}
finally
{
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="แปลง PPS เป็น JPG ใน Node.js" %}}

[**Aspose.Slides สำหรับ Node.js ผ่าน Java**](https://products.aspose.com/slides/th/nodejs-java/) เป็นไลบรารี Node.js อันทรงพลังสำหรับการสร้างและจัดการไฟล์งานนำเสนอ นอกจากนี้ยังมีวิธีที่ยืดหยุ่นในการแปลง PPS เป็น JPG เมื่อใช้ **Aspose.Slides สำหรับ Node.js ผ่าน Java** นักพัฒนาหรือแอปพลิเคชันใดๆ ก็สามารถแปลงไฟล์ PPS เป็น JPG ได้โดยใช้โค้ดเพียงไม่กี่บรรทัด

เนื่องจากเป็น API การประมวลผลเอกสารสมัยใหม่ Aspose.Slides สำหรับ Node.js จึงส่งออกไฟล์ PPS ไปเป็นรูปแบบไฟล์ JPG ได้อย่างรวดเร็ว ไลบรารี Aspose PowerPoint ช่วยให้คุณสามารถแปลง PPS เป็น JPG และรูปแบบไฟล์อื่นๆ อีกมากมาย

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="วิธีแปลง PPS เป็น JPG โดยใช้ Aspose.Slides สำหรับ Node.js ผ่าน Java API" intro="หากต้องการแปลง PPS เป็น JPG โดยใช้ Aspose.Slides สำหรับ Node.js ผ่าน Java คุณจะต้องนำเข้าแพ็กเกจในไฟล์ JavaScript ของคุณและสร้างอินสแตนซ์ของคลาส Presentation คลาสการนำเสนอแสดงถึงเอกสาร PowerPoint และจัดเตรียมวิธีการเข้าถึงและจัดการองค์ประกอบต่างๆ" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ติดตั้ง [**Aspose.Slides สำหรับ Node.js ผ่าน Java**](https://products.aspose.com/slides/th/nodejs-java/){{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เพิ่มการอ้างอิงไลบรารี (นำเข้าไลบรารี) ให้กับโปรเจ็กต์ Node.js ของคุณ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เปิดไฟล์ต้นฉบับ PPS ใน Node.js{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}บันทึกผลลัพธ์เป็นไฟล์ JPG{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="แปลง PPS เป็นรูปแบบอื่นที่รองรับ" subTitle="คุณยังสามารถแปลง PPS และบันทึกเป็นรูปแบบไฟล์อื่นๆ ได้ด้วย ดูรูปแบบที่รองรับทั้งหมดด้านล่าง" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/nodejs-java/conversion/pps-to-pptx/" name="PPS TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/nodejs-java/conversion/pps-to-ppt/" name="PPS TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/nodejs-java/conversion/pps-to-pdf/" name="PPS TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/nodejs-java/conversion/pps-to-html/" name="PPS TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/nodejs-java/conversion/pps-to-png/" name="PPS TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/nodejs-java/conversion/pps-to-bmp/" name="PPS TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/nodejs-java/conversion/pps-to-fodp/" name="PPS TO FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/nodejs-java/conversion/pps-to-gif/" name="PPS TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/nodejs-java/conversion/pps-to-odp/" name="PPS TO ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/nodejs-java/conversion/pps-to-otp/" name="PPS TO OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/nodejs-java/conversion/pps-to-pot/" name="PPS TO POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/nodejs-java/conversion/pps-to-potm/" name="PPS TO POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/nodejs-java/conversion/pps-to-potx/" name="PPS TO POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/nodejs-java/conversion/pps-to-ppsm/" name="PPS TO PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/nodejs-java/conversion/pps-to-ppsx/" name="PPS TO PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/nodejs-java/conversion/pps-to-pptm/" name="PPS TO PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/nodejs-java/conversion/pps-to-svg/" name="PPS TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/nodejs-java/conversion/pps-to-tiff/" name="PPS TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
