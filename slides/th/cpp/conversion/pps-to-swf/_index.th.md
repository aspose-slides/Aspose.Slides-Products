---
title: แปลง PPS เป็น SWF ผ่านแอปพลิเคชัน C++
url: /th/cpp/conversion/pps-to-swf/ 
description: ตัวอย่างโค้ดการแปลง C++ สำหรับเอกสาร PPS เป็นรูปแบบ SWF ใช้โค้ดตัวอย่างสำหรับการแปลงแบตช์ PPS เป็น SWF ภายในแอปพลิเคชัน C++ ใดๆ
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="แปลง PPS เป็น SWF ผ่าน C++" h2="การแปลง PPS เป็น SWF ประสิทธิภาพสูงโดยใช้ไลบรารี C++ โดยไม่จำเป็นต้องติดตั้ง Microsoft PowerPoint" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="SWF" pfName="Aspose.SLIDES" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="SLIDES" fileiconsmall4="XML" fileiconsmall5="PPS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.SLIDES " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/cpp" installationsDocsLink="https://docs.aspose.com/slides/cpp" nugetLink="https://www.nuget.org/packages/aspose.slides" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/cpp" learnAsLink="https://docs.aspose.com/slides/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="วิธีแปลง PPS เป็น SWF โดยใช้ C++" %}}

ในการแปลง PPS เป็น SWF เราจะใช้ <a href="https://products.aspose.com/slides/th/cpp">Aspose.Slides for C++</a> API ซึ่งเป็นคุณลักษณะที่มีประสิทธิภาพและทรงพลัง และง่ายต่อการใช้การจัดการเอกสารและการแปลง API สำหรับแพลตฟอร์ม C++ คุณสามารถดาวน์โหลดเวอร์ชันล่าสุดได้โดยตรง เพียงเปิด <a href="https://www.nuget.org/packages/aspose.slides">NuGet</a> package manager ค้นหา <b>Aspose.Slides.Cpp </b> และติดตั้ง คุณยังสามารถใช้คำสั่งต่อไปนี้จาก Package Manager Console

{{% blocks/products/pf/agp/code-block title="สั่งการ" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.SLIDES.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="ขั้นตอนในการแปลง PPS เป็น SWF ผ่าน C++" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.SLIDES API ช่วยให้นักพัฒนาแปลงไฟล์ PPS เป็น SWF ได้ง่ายในโค้ดเพียงไม่กี่บรรทัด

{{% /blocks/products/pf/agp/text %}}

1. โหลดไฟล์ PPS ด้วย Aspose.Slides สำหรับวัตถุการนำเสนอ C++
1. เรียกใช้เมธอด Save()
1. ส่งพาธไฟล์เอาต์พุตที่มีนามสกุลไฟล์ (SWF)
1. ไฟล์ SWF จะถูกบันทึกตามเส้นทางที่กำหนด
1. เปิดไฟล์ SWF ในโปรแกรมที่เข้ากันได้



{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.SLIDES สำหรับ C ++ รองรับบนแพลตฟอร์มหลักและระบบปฏิบัติการทั้งหมด โปรดตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows หรือ OS ที่เข้ากันได้กับ C++ Runtime Environment สำหรับ Windows 32 บิต, Windows 64 บิต และ Linux 64 บิต
- Aspose.Slides สำหรับ C ++ DLL ที่อ้างอิงในโครงการของคุณ

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="ซอร์สโค้ดการแปลง PPS เป็น SWF C++" offSpacer="" %}}

```cs
// Load the PPS.
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"sourceFile.pps");
// Save in SWF format.
prs->Save(u"convertedFile.swf", Aspose::Slides::Export::SaveFormat::Swf);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension=""
        sectionTitle="แอปฟรีเพื่อแปลง PPS เป็น SWF" 
        sectionDescription="[ลองใช้แอป Video ฟรีของเรา](https://products.aspose.app/slides/video/)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="คุณยังสามารถแปลง PPS เป็นรูปแบบไฟล์อื่นๆ ได้มากมาย รวมถึงบางไฟล์ที่แสดงด้านล่าง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/conversion/pps-to-bmp/" name="PPS TO BMP" description="Bitmap Image" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/conversion/pps-to-emf/" name="PPS TO EMF" description="Enhanced Metafile Format" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/conversion/pps-to-gif/" name="PPS TO GIF" description="Graphical Interchange Format" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/conversion/pps-to-html/" name="PPS TO HTML" description="Hyper Text Markup Language" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/conversion/pps-to-jpeg/" name="PPS TO JPEG" description="JPEG Image" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/conversion/pps-to-odp/" name="PPS TO ODP" description="OpenDocument Presentation Format" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/conversion/pps-to-otp/" name="PPS TO OTP" description="OpenDocument Standard Format" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/conversion/pps-to-pdf/" name="PPS TO PDF" description="Portable Document Format" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/conversion/pps-to-png/" name="PPS TO PNG" description="Portable Network Graphics" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/conversion/pps-to-pot/" name="PPS TO POT" description="Microsoft PowerPoint Template Files" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/conversion/pps-to-potm/" name="PPS TO POTM" description="Microsoft PowerPoint Template File" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/conversion/pps-to-potx/" name="PPS TO POTX" description="Microsoft PowerPoint Template Presentation" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/conversion/pps-to-ppsm/" name="PPS TO PPSM" description="Macro-enabled Slide Show" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/conversion/pps-to-ppsx/" name="PPS TO PPSX" description="PowerPoint Slide Show" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/conversion/pps-to-ppt/" name="PPS TO PPT" description="Microsoft PowerPoint 97-2003" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/conversion/pps-to-pptm/" name="PPS TO PPTM" description="Macro-enabled Presentation File" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/conversion/pps-to-pptx/" name="PPS TO PPTX" description="Open XML presentation Format" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/conversion/pps-to-svg/" name="PPS TO SVG" description="Scalable Vector Graphics" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/conversion/pps-to-tiff/" name="PPS TO TIFF" description="Tagged Image Format" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/conversion/pps-to-xml/" name="PPS TO XML" description="Extensible Markup Language" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/conversion/pps-to-xps/" name="PPS TO XPS" description="ข้อมูลจำเพาะกระดาษ XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}