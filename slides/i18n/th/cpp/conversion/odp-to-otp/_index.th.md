---
title: แปลง ODP เป็น OTP ผ่านแอปพลิเคชัน C++
weight: 6540
url: /th/cpp/conversion/odp-to-otp/ 
description: ตัวอย่างรหัสการแปลง C++ สำหรับเอกสาร ODP เป็นรูปแบบ OTP ใช้โค้ดตัวอย่างสำหรับการแปลงชุด ODP เป็น OTP ภายในแอปพลิเคชัน C ++
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="แปลง ODP เป็น OTP ผ่าน C++" h2="การแปลง ODP เป็น OTP ประสิทธิภาพสูงโดยใช้ไลบรารี C++ โดยไม่จำเป็นต้องติดตั้ง Microsoft PowerPoint" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="OTP" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/cpp" installationsDocsLink="https://docs.aspose.com/slides/cpp" nugetLink="https://www.nuget.org/packages/aspose.slides" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/cpp" learnAsLink="https://docs.aspose.com/slides/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="วิธีแปลง ODP เป็น OTP โดยใช้ C++" %}}

 ในการแปลง ODP เป็น OTP เราจะใช้
 [Aspose.Slides สำหรับ C++](https://products.aspose.com/slides/cpp)
 API ซึ่งเป็น API การจัดการและการแปลงเอกสารที่มีคุณลักษณะหลากหลาย มีประสิทธิภาพ และใช้งานง่ายสำหรับแพลตฟอร์ม C++ คุณสามารถดาวน์โหลดเวอร์ชันล่าสุดได้โดยตรง เพียงแค่เปิด
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 package manager ค้นหา
 Aspose.Slides.Cpp
 และติดตั้ง คุณยังสามารถใช้คำสั่งต่อไปนี้จาก Package Manager Console

{{% blocks/products/pf/agp/code-block title="สั่งการ" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="ขั้นตอนในการแปลง ODP เป็น OTP ผ่าน C++" %}}

{{% blocks/products/pf/agp/text %}}

 นักพัฒนา C++ สามารถแปลงไฟล์ ODP เป็น OTP ได้อย่างง่ายดายด้วยโค้ดเพียงไม่กี่บรรทัด

{{% /blocks/products/pf/agp/text %}}

1. โหลดไฟล์ ODP ด้วย Aspose.Slides สำหรับวัตถุการนำเสนอ C++
1. เรียกใช้เมธอด Save()
1. ส่งพาธไฟล์เอาต์พุตที่มีนามสกุลไฟล์ (OTP)
1. ไฟล์ OTP จะถูกบันทึกตามเส้นทางที่กำหนด
1. เปิดไฟล์ OTP ในโปรแกรมที่เข้ากันได้

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

{{% blocks/products/pf/agp/text %}}

 ก่อนรันโค้ดตัวอย่างการแปลง C++ ตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows หรือ OS ที่เข้ากันได้กับ C++ Runtime Environment สำหรับ Windows 32 บิต, Windows 64 บิต และ Linux 64 บิต
- Aspose.Slides สำหรับ C ++ DLL ที่อ้างอิงในโครงการของคุณ

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="ซอร์สโค้ดการแปลง ODP เป็น OTP C++" offSpacer="" %}}

```cs
// Load the ODP.
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"sourceFile.odp");
// Save in OTP format.
prs->Save(u"convertedFile.otp", Aspose::Slides::Export::SaveFormat::Otp);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="ODP to OTP Conversion Live Demos" sectionDescription="[Convert ODP to OTP](https://products.aspose.app/slides/conversion/odp-to-otp) right now by visiting our Live Demos website.The live demo has the following benefits" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your ODP file, it will be converted instantly to OTP." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will get the download link." >}}

    {{% blocks/products/pf/agp/content h2="ไลบรารีการจัดการการนำเสนอ C ++" %}}

 สามารถใช้ Slides และ Presentation API เพื่ออ่าน เขียน จัดการ และแปลงเอกสาร Microsoft PowerPoint เป็น PDF, XPS, HTML, TIFF, ODP และรูปแบบอื่นๆ ได้ หนึ่งสามารถสร้างไฟล์ใหม่ตั้งแต่เริ่มต้นและบันทึกในรูปแบบที่รองรับที่เกี่ยวข้อง Aspose.Slides เป็น API แบบสแตนด์อโลนสำหรับการสร้าง แยกวิเคราะห์ หรือจัดการการนำเสนอ สไลด์ และองค์ประกอบ และไม่ขึ้นกับซอฟต์แวร์ใดๆ เช่น Microsoft หรือ OpenOffice  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODP" readMoreLink="https://docs.fileformat.com/presentation/odp/" >}}

Files with ODP extension represent presentation file format used by OpenOffice.org in the OASISOpen standard. A presentation file is a collection of slides where each slide can comprise of text, images, formatting, animations, and other media. These slides are presented to audience in the form of slideshows with custom presentation settings. ODP files can be opened by applications that conform to the OpenDocument format (such as OpenOffice or StarOffice).


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="OTP" readMoreLink="https://docs.fileformat.com/presentation/otp/" >}}

Files with .OTP extension represent presentation template files created by applications in OASIS OpenDocument standard format. The contents of such a file include presentation information in the form of slides with text, images, shapes, multimedia content, transition effects and other slide elements. These template files are used for creating new presentations quickly based on the styling information stored in the template itself. OTP files can be created and saved with several different applications such as Impress that comes with OpenOffice suite and Microsoft PowerPoint. The OTP file format is similar to Microsoft PowerPoint template files .POT and .POTX.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="คุณยังสามารถแปลง ODP เป็นรูปแบบไฟล์อื่นๆ ได้มากมาย รวมถึงบางรูปแบบตามรายการด้านล่าง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/odp-to-bmp/" name="ODP TO BMP" description="ภาพบิตแมป" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/odp-to-emf/" name="ODP TO EMF" description="รูปแบบไฟล์ Metafile ที่ปรับปรุงแล้ว" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/odp-to-gif/" name="ODP TO GIF" description="รูปแบบการแลกเปลี่ยนกราฟิก" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/odp-to-html/" name="ODP TO HTML" description="ภาษามาร์กอัปข้อความไฮเปอร์" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/odp-to-jpeg/" name="ODP TO JPEG" description="ภาพ JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/odp-to-pdf/" name="ODP TO PDF" description="รูปแบบเอกสารพกพา" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/odp-to-png/" name="ODP TO PNG" description="กราฟิกเครือข่ายแบบพกพา" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/odp-to-pot/" name="ODP TO POT" description="ไฟล์เทมเพลต Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/odp-to-potm/" name="ODP TO POTM" description="ไฟล์เทมเพลต Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/odp-to-potx/" name="ODP TO POTX" description="การนำเสนอเทมเพลต Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/odp-to-pps/" name="ODP TO PPS" description="สไลด์โชว์ PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/odp-to-ppsm/" name="ODP TO PPSM" description="สไลด์โชว์ที่เปิดใช้งานมาโคร" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/odp-to-ppsx/" name="ODP TO PPSX" description="สไลด์โชว์ PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/odp-to-ppt/" name="ODP TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/odp-to-pptm/" name="ODP TO PPTM" description="ไฟล์นำเสนอที่เปิดใช้งานมาโคร" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/odp-to-pptx/" name="ODP TO PPTX" description="เปิดรูปแบบการนำเสนอ XML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/odp-to-svg/" name="ODP TO SVG" description="กราฟิกแบบเวกเตอร์ที่ปรับขนาดได้" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/odp-to-tiff/" name="ODP TO TIFF" description="รูปแบบภาพที่ติดแท็ก" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/odp-to-xml/" name="ODP TO XML" description="ภาษามาร์กอัปที่ขยายได้" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/odp-to-xps/" name="ODP TO XPS" description="ข้อมูลจำเพาะกระดาษ XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}