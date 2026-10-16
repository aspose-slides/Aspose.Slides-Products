---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: แปลง POTM เป็น BMP ผ่านแอปพลิเคชัน C++
weight: 3300
url: /th/cpp/conversion/potm-to-bmp/ 
description: ตัวอย่างรหัสการแปลง C++ สำหรับเอกสาร POTM เป็นรูปแบบ BMP ใช้โค้ดตัวอย่างสำหรับการแปลง POTM เป็น BMP แบบแบตช์ภายในแอปพลิเคชัน C++ ใดๆ
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="แปลง POTM เป็น BMP ผ่าน C++" h2="การแปลง POTM เป็น BMP ประสิทธิภาพสูงโดยใช้ไลบรารี C++ โดยไม่จำเป็นต้องติดตั้ง Microsoft PowerPoint"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/cpp"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="วิธีแปลง POTM เป็น BMP โดยใช้ C++" %}}

ในการแปลง POTM เป็น BMP เราจะใช้
 [Aspose.Slides สำหรับ C++](https://products.aspose.com/slides/cpp/)
 API ซึ่งเป็น API การจัดการและการแปลงเอกสารที่มีคุณลักษณะหลากหลาย มีประสิทธิภาพ และใช้งานง่ายสำหรับแพลตฟอร์ม C++ คุณสามารถดาวน์โหลดเวอร์ชันล่าสุดได้โดยตรง เพียงแค่เปิด
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 package manager ค้นหา
 Aspose.Slides.Cpp
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

{{< blocks/products/pf/slides-design-update-10-2026/code title="รหัสที่มาการแปลง POTM เป็น BMP C++" >}}
```cs
// Load the POTM
SharedPtr<Presentation> pres = MakeObject<Presentation>(u"sourceFile.potm");

// Access the first slide
SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// User defined dimension
int desiredX = 1200;
int desiredY = 800;

// Getting scaled value  of X and Y
float ScaleX = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Width()) * desiredX;
float ScaleY = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Height()) * desiredY;

// Create a custom scale image
auto bitmap = slide->GetThumbnail(ScaleX, ScaleY);

bitmap->Save(u"output.bmp", ImageFormat::get_Bmp());
	
//Iterate through each slide via index and convert

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="ขั้นตอนในการแปลง POTM เป็น BMP ผ่าน C++" intro="นักพัฒนา C++ สามารถแปลงไฟล์ POTM เป็น BMP ได้อย่างง่ายดายด้วยโค้ดเพียงไม่กี่บรรทัด" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}โหลดไฟล์ POTM ด้วย Aspose.Slides สำหรับวัตถุการนำเสนอ C++{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เลือกสไลด์แรก{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}กำหนดขนาดที่ต้องการ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}รับภาพขนาดย่อที่มีขนาดที่ต้องการ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เมธอด Call Save() ที่มีพารามิเตอร์เอาต์พุต BMP{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เปิดไฟล์ BMP ในโปรแกรมที่เข้ากันได้{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="ความต้องการของระบบ" intro="ก่อนรันโค้ดตัวอย่างการแปลง C++ ตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้" %}}

- Microsoft Windows หรือ OS ที่เข้ากันได้กับ C++ Runtime Environment สำหรับ Windows 32 บิต, Windows 64 บิต และ Linux 64 บิต
- Aspose.Slides สำหรับ C ++ DLL ที่อ้างอิงในโครงการของคุณ

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="แอปฟรีเพื่อแปลง POTM เป็น BMP"
  description="[ลองใช้แอปฟรีของเราเพื่อแปลง PPT เพื่อ BMP](https://products.aspose.app/slides/conversion/ppt-to-bmp)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="การแปลงอื่น ๆ ที่รองรับ" subTitle="คุณยังสามารถแปลง POTM เป็นรูปแบบไฟล์อื่นๆ ได้มากมาย รวมถึงบางรูปแบบตามรายการด้านล่าง" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potm-to-emf/" name="POTM TO EMF" description="รูปแบบไฟล์ Metafile ที่ปรับปรุงแล้ว" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potm-to-gif/" name="POTM TO GIF" description="รูปแบบการแลกเปลี่ยนกราฟิก" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potm-to-html/" name="POTM TO HTML" description="ภาษามาร์กอัปข้อความไฮเปอร์" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potm-to-jpeg/" name="POTM TO JPEG" description="ภาพ JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potm-to-odp/" name="POTM TO ODP" description="รูปแบบการนำเสนอ OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potm-to-otp/" name="POTM TO OTP" description="รูปแบบมาตรฐานของ OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potm-to-pdf/" name="POTM TO PDF" description="รูปแบบเอกสารพกพา" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potm-to-png/" name="POTM TO PNG" description="กราฟิกเครือข่ายแบบพกพา" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potm-to-pot/" name="POTM TO POT" description="ไฟล์เทมเพลต Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potm-to-potx/" name="POTM TO POTX" description="การนำเสนอเทมเพลต Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potm-to-pps/" name="POTM TO PPS" description="สไลด์โชว์ PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potm-to-ppsm/" name="POTM TO PPSM" description="สไลด์โชว์ที่เปิดใช้งานมาโคร" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potm-to-ppsx/" name="POTM TO PPSX" description="สไลด์โชว์ PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potm-to-ppt/" name="POTM TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potm-to-pptm/" name="POTM TO PPTM" description="ไฟล์นำเสนอที่เปิดใช้งานมาโคร" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potm-to-pptx/" name="POTM TO PPTX" description="เปิดรูปแบบการนำเสนอ XML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potm-to-svg/" name="POTM TO SVG" description="กราฟิกแบบเวกเตอร์ที่ปรับขนาดได้" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potm-to-tiff/" name="POTM TO TIFF" description="รูปแบบภาพที่ติดแท็ก" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potm-to-xml/" name="POTM TO XML" description="ภาษามาร์กอัปที่ขยายได้" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potm-to-xps/" name="POTM TO XPS" description="ข้อมูลจำเพาะกระดาษ XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
