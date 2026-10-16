---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: แปลง PPTX เป็น SWF ผ่านแอปพลิเคชัน C++
url: /th/cpp/conversion/pptx-to-swf/ 
description: ตัวอย่างโค้ดการแปลง C++ สำหรับเอกสาร PPTX เป็นรูปแบบ SWF ใช้โค้ดตัวอย่างสำหรับการแปลงแบตช์ PPTX เป็น SWF ภายในแอปพลิเคชัน C++ ใดๆ
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="แปลง PPTX เป็น SWF ผ่าน C++" h2="การแปลง PPTX เป็น SWF ประสิทธิภาพสูงโดยใช้ไลบรารี C++ โดยไม่จำเป็นต้องติดตั้ง Microsoft PowerPoint"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/cpp"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="วิธีแปลง PPTX เป็น SWF โดยใช้ C++" %}}

ในการแปลง PPTX เป็น SWF เราจะใช้ <a href="https://products.aspose.com/slides/th/cpp">Aspose.Slides for C++</a> API ซึ่งเป็นคุณลักษณะที่มีประสิทธิภาพและทรงพลัง และง่ายต่อการใช้การจัดการเอกสารและการแปลง API สำหรับแพลตฟอร์ม C++ คุณสามารถดาวน์โหลดเวอร์ชันล่าสุดได้โดยตรง เพียงเปิด <a href="https://www.nuget.org/packages/aspose.slides">NuGet</a> package manager ค้นหา <b>Aspose.Slides.Cpp </b> และติดตั้ง คุณยังสามารถใช้คำสั่งต่อไปนี้จาก Package Manager Console

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="สั่งการ" >}}
```cs

PM> Install-Package Aspose.SLIDES.Cpp

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="ซอร์สโค้ดการแปลง PPTX เป็น SWF C++" >}}
```cs
// Load the PPTX.
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"sourceFile.pptx");
// Save in SWF format.
prs->Save(u"convertedFile.swf", Aspose::Slides::Export::SaveFormat::Swf);

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="ขั้นตอนในการแปลง PPTX เป็น SWF ผ่าน C++" intro="Aspose.SLIDES API ช่วยให้นักพัฒนาแปลงไฟล์ PPTX เป็น SWF ได้ง่ายในโค้ดเพียงไม่กี่บรรทัด" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}โหลดไฟล์ PPTX ด้วย Aspose.Slides สำหรับวัตถุการนำเสนอ C++{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เรียกใช้เมธอด Save(){{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ส่งพาธไฟล์เอาต์พุตที่มีนามสกุลไฟล์ (SWF){{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ไฟล์ SWF จะถูกบันทึกตามเส้นทางที่กำหนด{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เปิดไฟล์ SWF ในโปรแกรมที่เข้ากันได้{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="ความต้องการของระบบ" intro="Aspose.SLIDES สำหรับ C ++ รองรับบนแพลตฟอร์มหลักและระบบปฏิบัติการทั้งหมด โปรดตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้" %}}

- Microsoft Windows หรือ OS ที่เข้ากันได้กับ C++ Runtime Environment สำหรับ Windows 32 บิต, Windows 64 บิต และ Linux 64 บิต
- Aspose.Slides สำหรับ C ++ DLL ที่อ้างอิงในโครงการของคุณ

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="แอปฟรีเพื่อแปลง PPTX เป็น SWF"
  description="[ลองใช้แอป Video ฟรีของเรา](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="การแปลงอื่น ๆ ที่รองรับ" subTitle="คุณยังสามารถแปลง PPTX เป็นรูปแบบไฟล์อื่น ๆ ได้มากมาย รวมถึงบางรูปแบบตามรายการด้านล่าง" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/cpp/conversion/pptx-to-bmp/" name="PPTX TO BMP" description="Bitmap Image" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/cpp/conversion/pptx-to-emf/" name="PPTX TO EMF" description="Enhanced Metafile Format" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/cpp/conversion/pptx-to-gif/" name="PPTX TO GIF" description="Graphical Interchange Format" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/cpp/conversion/pptx-to-html/" name="PPTX TO HTML" description="Hyper Text Markup Language" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/cpp/conversion/pptx-to-jpeg/" name="PPTX TO JPEG" description="JPEG Image" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/cpp/conversion/pptx-to-odp/" name="PPTX TO ODP" description="OpenDocument Presentation Format" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/cpp/conversion/pptx-to-otp/" name="PPTX TO OTP" description="OpenDocument Standard Format" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/cpp/conversion/pptx-to-pdf/" name="PPTX TO PDF" description="Portable Document Format" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/cpp/conversion/pptx-to-png/" name="PPTX TO PNG" description="Portable Network Graphics" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/cpp/conversion/pptx-to-pot/" name="PPTX TO POT" description="Microsoft PowerPoint Template Files" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/cpp/conversion/pptx-to-potm/" name="PPTX TO POTM" description="Microsoft PowerPoint Template File" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/cpp/conversion/pptx-to-potx/" name="PPTX TO POTX" description="Microsoft PowerPoint Template Presentation" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/cpp/conversion/pptx-to-pps/" name="PPTX TO PPS" description="PowerPoint Slide Show" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/cpp/conversion/pptx-to-ppsm/" name="PPTX TO PPSM" description="Macro-enabled Slide Show" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/cpp/conversion/pptx-to-ppsx/" name="PPTX TO PPSX" description="PowerPoint Slide Show" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/cpp/conversion/pptx-to-ppt/" name="PPTX TO PPT" description="Microsoft PowerPoint 97-2003" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/cpp/conversion/pptx-to-pptm/" name="PPTX TO PPTM" description="Macro-enabled Presentation File" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/cpp/conversion/pptx-to-svg/" name="PPTX TO SVG" description="Scalable Vector Graphics" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/cpp/conversion/pptx-to-tiff/" name="PPTX TO TIFF" description="Tagged Image Format" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/cpp/conversion/pptx-to-xml/" name="PPTX TO XML" description="Extensible Markup Language" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/cpp/conversion/pptx-to-xps/" name="PPTX TO XPS" description="ข้อมูลจำเพาะกระดาษ XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
