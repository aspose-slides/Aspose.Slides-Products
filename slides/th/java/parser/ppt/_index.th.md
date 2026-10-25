---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 7140
title: แยกข้อความจากเอกสาร PPT ด้วย Java
url: /th/java/parser/ppt/ 
description: แยกข้อความจากไฟล์ PPT ใน Java ด้วย Aspose.Slides for Java
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="แยกวิเคราะห์ไฟล์ PPT ใน Java" h2="แยกข้อความและเนื้อหางานนำเสนอจากเอกสาร PPT ด้วย API ฝั่งเซิร์ฟเวอร์ของ Aspose.Slides for Java"
  apiHomeLink="/slides/java/"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/java/"
  learnLink="https://docs.aspose.com/slides/java"
  pricingLink="https://purchase.aspose.com/pricing/slides/java/"
  related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="แยกวิเคราะห์ไฟล์ PPT ด้วย Java" %}}

ใช้ [Aspose.Slides for Java](/slides/th/java/) เพื่อแยกวิเคราะห์งานนำเสนอ PPT และแยกข้อความจากสไลด์ เพิ่มไลบรารีลงในโปรเจกต์ Maven ด้วยการกำหนดค่า repository และ dependency ด้านล่างในไฟล์ `pom.xml`

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Repository" >}}
```xml
<repository>
    <id>AsposeJavaAPI</id>
    <name>Aspose Java API</name>
    <url>https://releases.aspose.com/java/repo/</url>
</repository>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Dependency" >}}
```xml
<dependency>
    <groupId>com.aspose</groupId>
    <artifactId>aspose-slides</artifactId>
    <version>26.8</version>
    <classifier>jdk16</classifier>
</dependency>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="แยกวิเคราะห์ไฟล์ PPT – Java" >}}
```java
Presentation presentation = new Presentation("demo.ppt");
try {
    ISlide slide = presentation.getSlides().get_Item(0);
    ITextFrame[] slideTextFrames = SlideUtil.getAllTextBoxes(slide);

    for (ITextFrame textFrame : slideTextFrames) {
        for (IParagraph paragraph : textFrame.getParagraphs()) {
            for (IPortion portion : paragraph.getPortions()) {
                System.out.print(portion.getText());
                System.out.print(portion.getPortionFormat().getFontHeight());
                System.out.print(portion.getPortionFormat().getLatinFont().getFontName());
            }
        }
    }
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="วิธีแยกวิเคราะห์ไฟล์ PPT ใน Java" intro="แยกข้อความจากงานนำเสนอ PPT ด้วย Aspose.Slides for Java ในโค้ดไม่กี่บรรทัด" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}โหลดไฟล์ `PPT` ด้วยคลาส `Presentation`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เรียกเมธอด `SlideUtil.getAllTextBoxes` เพื่อดึงกรอบข้อความจากสไลด์แรก{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}วนผ่านออบเจ็กต์ `ITextFrame`, `IParagraph` และ `IPortion` แต่ละรายการ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}อ่านข้อความ ขนาดฟอนต์ และชื่อฟอนต์จากออบเจ็กต์ `IPortion` แต่ละรายการ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="ความต้องการของระบบ" intro="Aspose.Slides for Java รองรับแพลตฟอร์มและระบบปฏิบัติการหลัก ตรวจสอบให้แน่ใจว่าสภาพแวดล้อมของคุณมีสิ่งที่จำเป็นต่อไปนี้" %}}

- Microsoft Windows หรือระบบปฏิบัติการที่เข้ากันได้ซึ่งมี Java Runtime Environment สำหรับแอปพลิเคชัน JSP/JSF และแอปพลิเคชันเดสก์ท็อป
- Aspose.Slides for Java เวอร์ชันล่าสุดจาก [Maven](https://releases.aspose.com/java/repo/)

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="สร้างด้วย Aspose.Slides" title="แยกข้อความและรูปภาพออนไลน์" description="แอป Aspose.Slides Parser ฟรีนี้สร้างด้วย [Aspose.Slides for Java](https://products.aspose.com/slides/th/java/) ซึ่งเป็น API เดียวกับโค้ดด้านบน เปิดแอปแล้วดูว่า API ทำอะไรได้บ้างกับไฟล์ PPT ของคุณเอง" button="เปิด Aspose.Slides Parser" note="[แอปฟรีทั้งหมด](https://products.aspose.app/slides/family)" >}}
- ทำงานในเบราว์เซอร์ ไม่ต้องติดตั้งสิ่งใด
- ดูว่า Aspose.Slides อ่านไฟล์ของคุณอย่างไรก่อนเขียนโค้ด
- อัปโหลดไฟล์ PPT แล้วรับข้อความและรูปภาพ
- ดาวน์โหลดทั้งหมดเป็นไฟล์ ZIP เดียว
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPT" readMoreLink="https://docs.fileformat.com/presentation/ppt/" %}}

A PPT file stores a PowerPoint 97-2003 presentation in the binary file format. It can contain slides with text, images, charts, multimedia, and embedded objects.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="รูปแบบอื่นที่รองรับการแยกวิเคราะห์" subTitle="ด้วย Java คุณยังสามารถแยกวิเคราะห์รูปแบบงานนำเสนออื่นได้" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/java/parser/odp/" name="ODP" description="งานนำเสนอ OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/java/parser/pptx/" name="PPTX" description="งานนำเสนอ PowerPoint Open XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
