---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 460
title: แยกข้อความจากงานนำเสนอ ODP ด้วย C++
url: /th/cpp/parser/odp/ 
description: แยกข้อความจากงานนำเสนอ ODP ใน C++ ใช้ Aspose.Slides for C++ เพื่อแยกวิเคราะห์สไลด์ กรอบข้อความ ย่อหน้า และส่วนข้อความ
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="แยกวิเคราะห์งานนำเสนอ ODP ใน C++" h2="ใช้ Aspose.Slides for C++ เพื่อแยกข้อความจากสไลด์งานนำเสนอโดยไม่ต้องใช้ Microsoft PowerPoint"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/cpp/"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/"
  related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="แยกวิเคราะห์ไฟล์ ODP ด้วย C++" %}}

ใช้ Aspose.Slides for C++ เพื่อแยกวิเคราะห์ไฟล์งานนำเสนอ ODP และแยกข้อความจากสไลด์ API ให้เข้าถึงข้อความในสไลด์ผ่าน `SlideUtil::GetAllTextBoxes`, `ITextFrame`, `IParagraph` และ `IPortion` คุณจึงอ่านเนื้อหาข้อความได้โดยไม่ต้องควบคุม Microsoft PowerPoint อัตโนมัติ ติดตั้งแพ็กเกจ [`Aspose.Slides.Cpp`](https://www.nuget.org/packages/Aspose.Slides.Cpp/) จาก NuGet หรือใช้คำสั่งด้านล่างใน Package Manager Console

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="คำสั่ง" >}}
```powershell
PM> Install-Package Aspose.Slides.Cpp
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="แยกวิเคราะห์ไฟล์ ODP – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");
auto textFrames = SlideUtil::GetAllTextBoxes(presentation->get_Slide(0));

for (auto&& textFrame : textFrames)
{
    for (auto&& paragraph : textFrame->get_Paragraphs())
    {
        for (auto&& portion : paragraph->get_Portions())
        {
            Console::WriteLine(portion->get_Text());
        }
    }
}

presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="วิธีแยกวิเคราะห์ไฟล์ ODP ใน C++" intro="แยกข้อความจากไฟล์ ODP ด้วย Aspose.Slides for C++" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}โหลดไฟล์ ODP ด้วยคลาส `Presentation`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ดึงออบเจ็กต์ `ITextFrame` จากสไลด์แรกด้วย `SlideUtil::GetAllTextBoxes`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}วนผ่านออบเจ็กต์ `ITextFrame`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}วนผ่านออบเจ็กต์ `IParagraph` ในแต่ละ `ITextFrame`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}วนผ่านออบเจ็กต์ `IPortion` ในแต่ละ `IParagraph`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}อ่านข้อความด้วย `get_Text`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="ความต้องการของระบบ" intro="Aspose.Slides for C++ รองรับแพลตฟอร์มเดสก์ท็อปและเซิร์ฟเวอร์หลัก ตรวจสอบให้แน่ใจว่าโปรเจกต์ของคุณมีสิ่งที่จำเป็นต่อไปนี้" %}}

-  Microsoft Windows, Linux, macOS หรือระบบปฏิบัติการอื่นที่เข้ากันได้ซึ่งมีรันไทม์ C++ ที่รองรับ
-  ไลบรารี Aspose.Slides for C++ ที่อ้างอิงในโปรเจกต์ของคุณ

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="สร้างด้วย Aspose.Slides" title="แยกข้อความและรูปภาพออนไลน์" description="แอป Aspose.Slides Parser ฟรีนี้สร้างด้วย [Aspose.Slides for C++](https://products.aspose.com/slides/th/cpp/) ซึ่งเป็น API เดียวกับโค้ดด้านบน เปิดแอปแล้วดูว่า API ทำอะไรได้บ้างกับไฟล์ ODP ของคุณเอง" button="เปิด Aspose.Slides Parser" note="[แอปฟรีทั้งหมด](https://products.aspose.app/slides/family)" >}}
- ทำงานในเบราว์เซอร์ ไม่ต้องติดตั้งสิ่งใด
- ดูว่า Aspose.Slides อ่านไฟล์ของคุณอย่างไรก่อนเขียนโค้ด
- อัปโหลดไฟล์ ODP แล้วรับข้อความและรูปภาพ
- ดาวน์โหลดทั้งหมดเป็นไฟล์ ZIP เดียว
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="ODP" readMoreLink="https://docs.fileformat.com/presentation/odp/" %}}

ไฟล์ ODP คือไฟล์งานนำเสนอ OpenDocument ที่ใช้โดยแอปพลิเคชันอย่าง OpenOffice Impress และ LibreOffice Impress ไฟล์นี้จัดเก็บสไลด์ ข้อความ รูปภาพ การจัดรูปแบบ ภาพเคลื่อนไหว และเนื้อหางานนำเสนออื่นๆ ไว้ในแพ็กเกจแบบเปิดที่อิง XML

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="รูปแบบอื่นที่รองรับการแยกวิเคราะห์" subTitle="ด้วย C++ คุณยังสามารถแยกวิเคราะห์รูปแบบงานนำเสนออื่นได้" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/cpp/parser/ppt/" name="PPT" description="งานนำเสนอ PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/cpp/parser/pptx/" name="PPTX" description="งานนำเสนอ PowerPoint Open XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
