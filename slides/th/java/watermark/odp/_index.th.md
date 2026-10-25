---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: เพิ่มลายน้ำในไฟล์งานนำเสนอ ODP ด้วย Java
url: /th/java/watermark/odp/
description: เพิ่มลายน้ำข้อความและรูปภาพในงานนำเสนอ ODP ใน Java โดยใช้ Aspose.Slides for Java
keywords: เพิ่มลายน้ำใน ODP, เพิ่มลายน้ำข้อความใน ODP, เพิ่มลายน้ำรูปภาพใน ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="เพิ่มลายน้ำในงานนำเสนอ ODP ด้วย Java" h2="สร้างแอป Java ที่แทรกลายน้ำข้อความหรือรูปภาพลงในไฟล์งานนำเสนอด้วย API ฝั่งเซิร์ฟเวอร์" related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="เพิ่มลายน้ำในงานนำเสนอ ODP ผ่าน Java" variant="code" %}}

ด้วย [Aspose.Slides for Java](/slides/th/java/) คุณสามารถเพิ่มลายน้ำข้อความและรูปภาพในงานนำเสนอ ODP ได้ เพิ่มรูปร่างลายน้ำลงในสไลด์ต้นแบบเพื่อให้ลายน้ำปรากฏบนสไลด์ที่ใช้ต้นแบบนั้น

{{< blocks/products/pf/slides-design-update-10-2026/code title="เพิ่มลายน้ำข้อความใน ODP ด้วย Java" >}}
```java
Presentation presentation = new Presentation("presentation.odp");
try {
    IMasterSlide masterSlide = presentation.getMasters().get_Item(0);
    IAutoShape watermarkShape = masterSlide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 400, 120);
    ITextFrame watermarkTextFrame = watermarkShape.addTextFrame("Watermark");
    watermarkTextFrame.getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().setFontHeight(48);

    presentation.save("watermark.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="เพิ่มลายน้ำรูปภาพในงานนำเสนอ ODP ด้วย Java" >}}
```java
Presentation presentation = new Presentation("presentation.odp");
try {
    byte[] imageData = Files.readAllBytes(Paths.get("watermark.png"));
    IPPImage watermarkImage = presentation.getImages().addImage(imageData);
    IMasterSlide masterSlide = presentation.getMasters().get_Item(0);
    IAutoShape watermarkShape = masterSlide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 200);

    watermarkShape.getFillFormat().setFillType(FillType.Picture);
    watermarkShape.getFillFormat().getPictureFillFormat().getPicture().setImage(watermarkImage);
    watermarkShape.getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);

    presentation.save("image-watermark.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="วิธีเพิ่มลายน้ำใน ODP ด้วย Java" intro="ทำตามขั้นตอนเหล่านี้เพื่อเพิ่มลายน้ำข้อความหรือรูปภาพในไฟล์ ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}โหลดไฟล์ `ODP` ด้วยคลาส `Presentation`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เลือกสไลด์ต้นแบบผ่านเมธอด `getMasters`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เรียกเมธอด `addAutoShape` เพื่อเพิ่มรูปร่างลายน้ำ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เรียกเมธอด `addTextFrame` เพื่อเพิ่มข้อความลายน้ำ หรือใช้ `addImage` สำหรับลายน้ำรูปภาพ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}บันทึกงานนำเสนอที่มีลายน้ำในรูปแบบ ODP{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="สร้างด้วย Aspose.Slides" title="เพิ่มลายน้ำในไฟล์ ODP ออนไลน์" description="แอป Aspose.Slides Watermark ฟรีนี้สร้างด้วย [Aspose.Slides for Java](https://products.aspose.com/slides/th/java/) ซึ่งเป็น API เดียวกับโค้ดด้านบน เปิดแอปแล้วดูว่า API ทำอะไรได้บ้างกับไฟล์ ODP ของคุณเอง" button="เปิด Aspose.Slides Watermark" note="[แอปฟรีทั้งหมด](https://products.aspose.app/slides/family)" >}}
- ทำงานในเบราว์เซอร์ ไม่ต้องติดตั้งสิ่งใด
- ดูว่า Aspose.Slides เพิ่มลายน้ำอย่างไรก่อนเขียนโค้ด
- เพิ่มลายน้ำข้อความหรือรูปภาพในไฟล์ ODP ของคุณ
- ดาวน์โหลดไฟล์ที่มีลายน้ำ
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="รูปแบบอื่นที่รองรับลายน้ำ" subTitle="ด้วย Java คุณยังสามารถเพิ่มลายน้ำในรูปแบบต่อไปนี้ได้" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/java/watermark/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/java/watermark/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
