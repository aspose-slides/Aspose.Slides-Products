---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: รวมไฟล์ POTM ผ่าน Java
weight: 6620
url: /th/java/merger/potm/ 
description: โค้ดตัวอย่าง Java เพื่อรวมเอกสาร POTM บน Java Runtime Environment สำหรับแอปพลิเคชัน JSP/JSF และแอปพลิเคชันเดสก์ท็อป
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="รวมรูปแบบ POTM ใน Java" h2="การรวมเอกสาร Native POTM โดยใช้ Java API ฝั่งเซิร์ฟเวอร์"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/java"
  learnLink="https://docs.aspose.com/slides/java"
  pricingLink="https://purchase.aspose.com/pricing/slides/java/"
  related="ODP,OTP,POT,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="วิธีผสานไฟล์ POTM โดยใช้ Java" %}}

ในการรวมไฟล์ POTM เราจะใช้
 [Aspose.Slides สำหรับ Java](https://products.aspose.com/slides/th/java/)
 API ซึ่งเป็น API การควบรวมกิจการที่มีคุณลักษณะหลากหลาย มีประสิทธิภาพ และใช้งานง่ายสำหรับแพลตฟอร์ม Java คุณสามารถดาวน์โหลดเวอร์ชันล่าสุดได้โดยตรงจาก
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides)
 และติดตั้งภายในโปรเจ็กต์ที่ใช้ Maven โดยเพิ่มการกำหนดค่าต่อไปนี้ใน pom.xml

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="ที่เก็บ" >}}
```xml

<repository>
    <id>AsposeJavaAPI</id>
    <name>Aspose Java API</name>
    <url>https://releases.aspose.com/java/repo/</url>
</repository>

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="การพึ่งพา" >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/code title="รวมไฟล์ POTM - Java" >}}
```cs
// Load first POTM File
Presentation prest1 = new Presentation("prest1.potm");

// Load second POTM File
Presentation prest2 = new Presentation("prest2.potm");

// Merge
for (ISlide slide : prest2.getSlides()) {
	// Merge from source to target
	prest1.getSlides().addClone(slide);
}

// Save the File
prest1.save("merged-presentation.potm", SaveFormat.Potm);  

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="ขั้นตอนในการรวมไฟล์ POTM ใน Java" intro="เอกสารพื้นฐานที่ผสานและต่อด้วย [Aspose.Slides for Java](https://products.aspose.com/slides/th/java/) API สามารถทำได้โดยใช้โค้ดเพียงไม่กี่บรรทัด" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}โหลดไฟล์ POTM แรกด้วยอินสแตนซ์ของคลาสการนำเสนอ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}โหลดเอกสาร POTM ที่สองด้วยอินสแตนซ์ของคลาสการนำเสนอ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}วนซ้ำแต่ละสไลด์ของไฟล์ POTM ที่สอง{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ในการวนซ้ำแต่ละครั้ง ใช้ addClone() เพื่อเพิ่มสไลด์ด้วยไฟล์แรก{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ใช้วิธี save() เพื่อบันทึกตามเส้นทางที่ระบุ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="ความต้องการของระบบ" intro="Aspose.Slides สำหรับ Java รองรับบนแพลตฟอร์มหลักและระบบปฏิบัติการทั้งหมด โปรดตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้" %}}

- Microsoft Windows หรือ OS ที่เข้ากันได้กับ Java Runtime Environment สำหรับแอปพลิเคชัน JSP/JSF และแอปพลิเคชันเดสก์ท็อป
- รับเวอร์ชันล่าสุดของ Aspose.Slides สำหรับ Java โดยตรงจาก [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides)

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="merger" extension=""
  title="รวมไฟล์ PDF ออนไลน์"
  description="[วิธีผสาน PDF ใน Python](https://products.aspose.com/slides/th/python-net/merge/pdf/)" >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="POTM" readMoreLink="https://docs.fileformat.com/presentation/potm/" %}}

ไฟล์ที่มีนามสกุล `.POTM` คือไฟล์เทมเพลต Microsoft PowerPoint ที่รองรับแมโคร ไฟล์ `POTM` จัดเก็บเค้าโครง สไตล์ ธีม ค่าเริ่มต้น และแมโครที่ใช้สร้างงานนำเสนอใหม่ได้

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="รูปแบบการผสานที่รองรับอื่น ๆ" subTitle="การใช้ Java One สามารถรวมรูปแบบไฟล์อื่น ๆ ได้มากมายรวมทั้ง.." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/java/merger/odp/" name="ODP" description="รูปแบบการนำเสนอ OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/java/merger/otp/" name="OTP" description="รูปแบบมาตรฐานของ OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/java/merger/pot/" name="POT" description="ไฟล์เทมเพลต Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/java/merger/potx/" name="POTX" description="การนำเสนอเทมเพลต Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/java/merger/pps/" name="PPS" description="สไลด์โชว์ PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/java/merger/ppsm/" name="PPSM" description="สไลด์โชว์ที่เปิดใช้งานมาโคร" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/java/merger/ppsx/" name="PPSX" description="สไลด์โชว์ PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/java/merger/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/java/merger/pptm/" name="PPTM" description="ไฟล์นำเสนอที่เปิดใช้งานมาโคร" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/java/merger/pptx/" name="PPTX" description="เปิดรูปแบบการนำเสนอ XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
