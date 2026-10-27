---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: รวมไฟล์ POTM ผ่าน C++
weight: 7950
url: /th/cpp/merger/potm/ 
description: โค้ดตัวอย่าง C++ เพื่อรวมเอกสาร POTM บน C++ Runtime Environment สำหรับ Windows 32 บิต, Windows 64 บิต และ Linux 64 บิต
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="รวมไฟล์ POTM โดยใช้ C++" h2="การรวมเอกสาร POTM โดยใช้ C++ API ฝั่งเซิร์ฟเวอร์"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/cpp"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/"
  related="ODP,OTP,POT,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="วิธีผสานไฟล์ POTM โดยใช้ C++" %}}

ในการรวมไฟล์ POTM เราจะใช้
 [Aspose.Slides สำหรับ C++](https://products.aspose.com/slides/th/cpp/)
 API ซึ่งเป็น API การรวมเอกสารที่มีคุณสมบัติหลากหลาย มีประสิทธิภาพ และใช้งานง่ายสำหรับแพลตฟอร์ม C++ คุณสามารถดาวน์โหลดเวอร์ชันล่าสุดได้โดยตรง เพียงแค่เปิด
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 package manager ค้นหา
 **Aspose.Slides.Cpp**
 และติดตั้ง คุณยังสามารถใช้คำสั่งต่อไปนี้จาก Package Manager Console

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="สั่งการ" >}}
```cs

PM> Install-Package Aspose.Slides.Cpp

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="รวมไฟล์ POTM - C++" >}}
```cs
// The path to the documents directory.
const String sourceFilePath1 = u"SourceFile2.potm";
const String sourceFilePath2 = u"SourceFile3.potm";
const String outputFilePath = u"mergedOutput.potm";

// Instantiate Presentation class
SharedPtr<Presentation> presentation1 = MakeObject<Presentation>(sourceFilePath1);
SharedPtr<Presentation> presentation2 = MakeObject<Presentation>(sourceFilePath2);

for (SharedPtr<ISlide> slide : presentation2->get_Slides()){
	// Merge from source to destination 
	presentation1->get_Slides()->AddClone(slide);
}

// Save the presentation
presentation1->Save(outputFilePath, SaveFormat::Potm);  

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="ขั้นตอนในการรวมไฟล์ POTM ใน C++" intro="เอกสารพื้นฐานที่ผสานและต่อด้วย [Aspose.Slides for C++](https://products.aspose.com/slides/th/cpp/) API สามารถทำได้โดยใช้โค้ดเพียงไม่กี่บรรทัด" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}โหลดไฟล์ POTM ทั้งสองไฟล์{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ใช้วิธี get\_Slides() เพื่อวนซ้ำในแต่ละสไลด์{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ใช้ฟังก์ชัน AddClone เพื่อรวมเข้ากับไฟล์ที่ต้องการ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ใช้วิธี Save() เพื่อบันทึกที่เส้นทางที่ระบุ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="ความต้องการของระบบ" intro="Aspose.Slides สำหรับ C ++ รองรับบนแพลตฟอร์มหลักและระบบปฏิบัติการทั้งหมด โปรดตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้" %}}

- Microsoft Windows หรือ OS ที่เข้ากันได้กับ C++ Runtime Environment สำหรับ Windows 32 บิต, Windows 64 บิต และ Linux 64 บิต
- Aspose.Slides สำหรับ C ++ DLL ที่อ้างอิงในโครงการของคุณ

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/merger-app label="สร้างด้วย Aspose.Slides" title="รวมไฟล์ POTM ออนไลน์" description="แอป Aspose.Slides Merger ฟรีนี้สร้างด้วย [Aspose.Slides for C++](https://products.aspose.com/slides/th/cpp/) ซึ่งเป็น API เดียวกับโค้ดด้านบน เปิดแอปแล้วดูว่า API ทำอะไรได้บ้างกับไฟล์ POTM ของคุณเอง" button="เปิด Aspose.Slides Merger" note="[แอปฟรีทั้งหมด](https://products.aspose.app/slides/family)" >}}
- ทำงานในเบราว์เซอร์ ไม่ต้องติดตั้งสิ่งใด
- ดูว่า Aspose.Slides รวมไฟล์อย่างไรก่อนที่คุณจะเขียนโค้ด
- อัปโหลดไฟล์ POTM หลายไฟล์แล้วรวมเป็นไฟล์เดียว
- ดาวน์โหลดผลลัพธ์ที่รวมแล้วเป็นไฟล์เดียว
{{< /blocks/products/pf/slides-design-update-10-2026/merger-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="POTM" readMoreLink="https://docs.fileformat.com/presentation/potm/" %}}

ไฟล์ที่มีนามสกุล `.POTM` คือเทมเพลต Microsoft PowerPoint ที่รองรับแมโคร ซึ่งเปิดตัวพร้อม PowerPoint 2007 ไฟล์นี้จัดเก็บการตั้งค่างานนำเสนอที่นำกลับมาใช้ได้ เช่น เค้าโครง สไตล์ พื้นหลัง ชุดสี ฟอนต์ การจัดรูปแบบเริ่มต้น และแมโคร VBA PowerPoint 2007 ขึ้นไปสามารถเปิดและแก้ไขไฟล์ POTM ได้

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="รูปแบบการผสานที่รองรับอื่น ๆ" subTitle="การใช้ C ++ นั้นสามารถรวมรูปแบบไฟล์อื่น ๆ ได้มากมายรวมถึง.." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/cpp/merger/odp/" name="ODP" description="รูปแบบการนำเสนอ OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/cpp/merger/otp/" name="OTP" description="รูปแบบมาตรฐานของ OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/cpp/merger/pot/" name="POT" description="ไฟล์เทมเพลต Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/cpp/merger/potx/" name="POTX" description="การนำเสนอเทมเพลต Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/cpp/merger/pps/" name="PPS" description="สไลด์โชว์ PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/cpp/merger/ppsm/" name="PPSM" description="สไลด์โชว์ที่เปิดใช้งานมาโคร" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/cpp/merger/ppsx/" name="PPSX" description="สไลด์โชว์ PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/cpp/merger/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/cpp/merger/pptm/" name="PPTM" description="ไฟล์นำเสนอที่เปิดใช้งานมาโคร" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/cpp/merger/pptx/" name="PPTX" description="เปิดรูปแบบการนำเสนอ XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
