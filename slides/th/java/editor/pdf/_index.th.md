---
lastmod: 2022-12-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: แก้ไข PDF ใน Java
url: /th/java/editor/pdf/
keywords: แก้ไข PDF, PDF, Java API, Java Library
description: แก้ไข PDF ใน Java ใช้ Java library API เพื่อแก้ไขเอกสาร PDF
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="แก้ไข PDF ใน Java" h2="ไลบรารี Java ความเร็วสูงและข้ามแพลตฟอร์มสำหรับแก้ไข PDF โดยใช้โค้ด Java" related="PPT,HTML" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="แก้ไข PDF ใน Java" variant="code" %}}

เมื่อใช้ [**Aspose.Slides สำหรับ Java**](https://products.aspose.com/slides/th/java/) คุณจะเพิ่มข้อความบรรทัดใหม่ลงในเอกสาร PDF โดยใช้โค้ดเพียงไม่กี่บรรทัดได้

{{< blocks/products/pf/slides-design-update-10-2026/code title="รหัส Java สำหรับแก้ไข PDF" >}}
```java

Presentation pres = new Presentation();
try {
    pres.getSlides().removeAt(0);
    pres.getSlides().addFromPdf("document.pdf");

    ISlide slide = pres.getSlides().get_Item(0);
    IAutoShape shape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 50);
    shape.getTextFrame().setText("New text");

    pres.save("document.pdf", SaveFormat.Pdf);
} finally {
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="แก้ไข PDF โดยใช้ Aspose.Slides" %}}

[**Aspose.Slides สำหรับ Java**](https://products.aspose.com/slides/th/java/) คือไลบรารี Java อันทรงพลังที่ใช้ในการจัดการและแก้ไขงานนำเสนอ เอกสาร PDF และไฟล์อื่นๆ คุณสามารถแก้ไขเอกสาร PDF ได้โดยเพิ่มบรรทัดข้อความใหม่เข้าไป

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="วิธีแก้ไข PDF ใน Java" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ติดตั้ง **Aposose.Slides สำหรับ Java** ดู [**การติดตั้ง**](https://docs.aspose.com/slides/java/installation/){{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เพิ่มไลบรารีเป็นข้อมูลอ้างอิงในโครงการของคุณ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}สร้างอินสแตนซ์ของคลาสการนำเสนอ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}โหลดเอกสาร PDF ที่คุณต้องการแก้ไข{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เพิ่มบรรทัดใหม่ของข้อความ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}บันทึกไฟล์ PDF ที่เปลี่ยนแปลง{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="แก้ไขไฟล์อื่นๆ" subTitle="คุณยังสามารถแก้ไขไฟล์ในรูปแบบอื่นๆ" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/java/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/java/editor/html/" name="Edit HTML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
