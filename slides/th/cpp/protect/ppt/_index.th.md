---
title: ป้องกันและล็อกเอกสาร PPT ผ่าน C++
weight: 2570
url: /th/cpp/protect/ppt/ 
description: โค้ดตัวอย่าง C++ สำหรับล็อกไฟล์ PPT โดยใช้รหัสผ่านบน C++ Runtime Environment สำหรับ Windows 32 บิต, Windows 64 บิต และ Linux 64 บิต
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="เข้ารหัสไฟล์ PPT ผ่าน C++" h2="งานนำเสนอ PowerPoint ที่ป้องกันด้วยรหัสผ่านรวมถึงรูปแบบ PPT โดยใช้ .NET Library" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/cpp/" installationsDocsLink="https://docs.aspose.com/slides/cpp/" nugetLink="https://www.nuget.org/packages/aspose.slides" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/cpp" learnAsLink="https://docs.aspose.com/slides/cpp/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="วิธีรักษาความปลอดภัยไฟล์ PPT โดยใช้ C ++" %}}

 เพื่อป้องกันไฟล์ PPT เราจะใช้
 [Aspose.Slides สำหรับ C++](https://products.aspose.com/slides/th/cpp)
 API ซึ่งเป็น API การเข้ารหัสเอกสารที่มีคุณสมบัติหลากหลาย ทรงพลัง และใช้งานง่ายสำหรับแพลตฟอร์ม C++ คุณสามารถดาวน์โหลดเวอร์ชันล่าสุดได้โดยตรง เพียงแค่เปิด
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 package manager ค้นหา
 **Aspose.Slides.Cpp**
 และติดตั้ง คุณยังสามารถใช้คำสั่งต่อไปนี้จาก Package Manager Console

{{% blocks/products/pf/agp/code-block title="Aspose.สไลด์" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="ขั้นตอนในการป้องกันไฟล์ PPT ผ่าน C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="การป้องกันเอกสารโดยใช้ Aspose.Slides API สามารถทำได้โดยใช้โค้ดเพียงไม่กี่บรรทัด" >}}

{{< blocks/products/pf/agp/step-autogen >}}
โหลดไฟล์ PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ตั้งรหัสผ่านโดยใช้ get\_ProtectionManager()->Encrypt(.) method
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
บันทึกการนำเสนอ PPT ที่มีการป้องกัน
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Slides สำหรับ C ++ รองรับบนแพลตฟอร์มหลักและระบบปฏิบัติการทั้งหมด โปรดตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows หรือ OS ที่เข้ากันได้กับ C++ Runtime Environment สำหรับ Windows 32 บิต, Windows 64 บิต และ Linux 64 บิต
- Aspose.Slides สำหรับ C ++ DLL ที่อ้างอิงในโครงการของคุณ

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="สั่งการ" offSpacer="" %}}

```cs

const String sourceFilePath = u"SourcePath\SourceFile.ppt";
const String outputFilePath = u"OutputPath\OutPutFile.ppt";

// Load the PPT file
SharedPtr<Presentation> pptFile = MakeObject<Presentation>(sourceFilePath);

// Protect with password
pptFile->get_ProtectionManager()->Encrypt(u"password");

// Save the PPT
pptFile->Save(outputFilePath, SaveFormat::Ppt);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="เกี่ยวกับ Aspose.Slides สำหรับ C++ API" %}}

 Aspose.Slides API สามารถใช้อ่าน เขียน จัดการ และแปลงเอกสาร Microsoft PowerPoint เป็น PDF, XPS, HTML, TIFF, ODP และรูปแบบอื่นๆ ได้ หนึ่งสามารถสร้างไฟล์ใหม่ตั้งแต่เริ่มต้นและบันทึกในรูปแบบที่รองรับที่เกี่ยวข้อง Aspose.Slides เป็น API แบบสแตนด์อโลนสำหรับการสร้าง แยกวิเคราะห์ หรือจัดการการนำเสนอ สไลด์ และองค์ประกอบ และไม่ขึ้นกับซอฟต์แวร์ใดๆ เช่น Microsoft หรือ OpenOffice  



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Free App to Protect PPT" sectionDescription="Check our live demos to [encrypt PPT files](https://products.aspose.app/slides/protect/ppt) with following benefits." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write or compile code" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload PPT file and hit the \"Unlock\" button" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Download the resultant PPT file from the link" >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PPT" readMoreLink="https://docs.fileformat.com/presentation/ppt/" >}}
A file with PPT extension represents PowerPoint file that consists of a collection of slides for displaying as SlideShow. It specifies the Binary File Format used by Microsoft PowerPoint 97-2003. A PPT file can contain several different types of information such as text, bulleted points, images, multimedia and other embedded OLE objects. Microsoft came up with newer file format for PowerPoint, known as PPTX, from 2007 onwards that is based on Office OpenXML and is different from this binary file format. Several other application programs such as OpenOffice Impress and Apple Keynote can also create PPT files.

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="เอกสารคุ้มครองอื่น ๆ ที่ได้รับการสนับสนุน" subTitle="การใช้ C ++ สามารถป้องกันไฟล์อื่น ๆ รวมถึง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/protect/odp/" name="ODP" description="รูปแบบการนำเสนอ OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/protect/pptx/" name="PPTX" description="เปิดรูปแบบการนำเสนอ XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}