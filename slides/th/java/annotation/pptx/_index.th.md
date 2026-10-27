---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 360
title: ลบคำอธิบายประกอบ PPTX ด้วย Java
url: /th/java/annotation/pptx/ 
description: ลบความคิดเห็นและผู้เขียนความคิดเห็นออกจากงานนำเสนอ PPTX ใน Java ด้วย Aspose.Slides for Java
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="ลบความคิดเห็นและผู้เขียนความคิดเห็นออกจาก PPTX ใน Java" h2="ใช้ Aspose.Slides for Java เพื่อลบความคิดเห็นและผู้เขียนความคิดเห็นออกจากไฟล์งานนำเสนอ" related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="ลบความคิดเห็นออกจาก PPTX ผ่าน Java" variant="code" %}}

Aspose.Slides for Java ช่วยให้คุณลบความคิดเห็นและผู้เขียนความคิดเห็นออกจากงานนำเสนอ PPTX ได้ โหลดไฟล์ด้วยคลาส `Presentation` วนซ้ำออบเจ็กต์ `ICommentAuthor` จาก `getCommentAuthors` ล้างความคิดเห็นของแต่ละคน แล้วบันทึกงานนำเสนอที่อัปเดตแล้ว

{{< blocks/products/pf/slides-design-update-10-2026/code title="ลบคำอธิบายประกอบออกจาก PPTX – Java" >}}
```java
Presentation presentation = new Presentation("presentation.pptx");
try {
    for (ICommentAuthor commentAuthor : presentation.getCommentAuthors())
    {
        commentAuthor.getComments().clear();
    }

    presentation.getCommentAuthors().clear();

    presentation.save("cleaned-presentation.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="วิธีลบความคิดเห็นออกจาก PPTX ผ่าน Java" intro="ทำตามขั้นตอนเหล่านี้เพื่อลบความคิดเห็นและผู้เขียนความคิดเห็นออกจากงานนำเสนอ PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ติดตั้ง Aspose.Slides for Java ดู [การติดตั้ง](https://docs.aspose.com/slides/java/installation/){{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}โหลดไฟล์ PPTX ด้วยคลาส `Presentation`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}วนซ้ำออบเจ็กต์ `ICommentAuthor` จาก `getCommentAuthors`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ล้างความคิดเห็นของผู้เขียนแต่ละคนด้วย `getComments().clear()`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ล้างคอลเลกชันผู้เขียนความคิดเห็นและบันทึกไฟล์ PPTX ที่อัปเดตแล้ว{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="สร้างด้วย Aspose.Slides" title="ลบความคิดเห็น PPTX ออนไลน์" description="แอป Aspose.Slides Annotation ฟรีนี้สร้างด้วย [Aspose.Slides for Java](https://products.aspose.com/slides/th/java/) ซึ่งเป็น API เดียวกับโค้ดด้านบน เปิดแอปแล้วดูว่า API ทำอะไรได้บ้างกับไฟล์ PPTX ของคุณเอง" button="เปิด Aspose.Slides Annotation" note="[แอปฟรีทั้งหมด](https://products.aspose.app/slides/family)" >}}
- ทำงานในเบราว์เซอร์ ไม่ต้องติดตั้งสิ่งใด
- ดูว่า Aspose.Slides ลบความคิดเห็นอย่างไรก่อนเขียนโค้ด
- ลบความคิดเห็นทั้งหมดออกจากไฟล์ PPTX ของคุณ
- ดาวน์โหลดไฟล์ที่ล้างแล้ว
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="รูปแบบอื่นที่รองรับสำหรับคำอธิบายประกอบ" subTitle="ด้วย Java คุณยังลบคำอธิบายประกอบออกจากรูปแบบอื่นได้ด้วย" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/java/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/java/annotation/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
