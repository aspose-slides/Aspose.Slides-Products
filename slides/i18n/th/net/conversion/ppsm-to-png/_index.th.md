---
title: แปลง PPSM เป็น PNG ผ่าน C #
weight: 6640
url: /th/net/conversion/ppsm-to-png/ 
description: โค้ดตัวอย่างสำหรับการแปลง PPSM เป็น PNG C# ใช้โค้ดตัวอย่าง API สำหรับไฟล์แบตช์ PPSM เป็นการแปลง PNG ภายใน VB.NET, Asp.NET หรือแอปพลิเคชันที่ใช้ .NET
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="แปลง PPSM เป็น PNG ผ่าน C #" h2="ส่งออกไฟล์ PowerPoint® PPSM เป็น PNG บน .NET Framework, .NET Core, Windows Azure, Mono หรือ Xamarin Platforms" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PNG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PPSM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/net" installationsDocsLink="https://docs.aspose.com/slides/net" nugetLink="https://www.nuget.org/packages/aspose.slides.net" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/net" learnAsLink="https://docs.aspose.com/slides/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="วิธีแปลง PPSM เป็น PNG โดยใช้ C #" %}}

 ในการแปลง PPSM เป็น PNG เราจะใช้
 [Aspose.Slides สำหรับ .NET](https://products.aspose.com/slides/net)
 API ซึ่งเป็น API ที่มีคุณลักษณะหลากหลาย มีประสิทธิภาพ และใช้งานง่ายสำหรับการจัดการเอกสารและการแปลง API สำหรับแพลตฟอร์ม C# เปิด
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 package manager ค้นหา
 Aspose.สไลด์
 และติดตั้ง คุณยังสามารถใช้คำสั่งต่อไปนี้จาก Package Manager Console

{{% blocks/products/pf/agp/code-block title="คำสั่งคอนโซลตัวจัดการแพ็คเกจ" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.NET

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="ขั้นตอนในการแปลง PPSM เป็น PNG ผ่าน C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="นักพัฒนา .NET สามารถโหลดและแปลงไฟล์ PPSM เป็น PNG ได้อย่างง่ายดายด้วยโค้ดเพียงไม่กี่บรรทัด" >}}

{{< blocks/products/pf/agp/step-autogen >}}
โหลดไฟล์ PPSM ด้วยอินสแตนซ์ของคลาสการนำเสนอ
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ทำซ้ำผ่านแต่ละสไลด์ในการนำเสนอ
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
สร้างภาพขนาดเต็มเป็นบิตแมปด้วยการวนซ้ำแต่ละครั้ง
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
เรียกวิธี Bitmap.Save ด้วยนามสกุลไฟล์ PNG และ ImageFormat.Png เป็นพารามิเตอร์
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

{{% blocks/products/pf/agp/text %}}

 ก่อนเรียกใช้ซอร์สโค้ดตัวอย่างการแปลง .NET ตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นต่อไปนี้

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows หรือระบบปฏิบัติการที่เข้ากันได้กับ .NET Framework, .NET Core, Windows Azure, Mono หรือ Xamarin Platforms
- สภาพแวดล้อมการพัฒนาเช่น Microsoft Visual Studio
- Aspose.Slides สำหรับ .NET DLL ที่อ้างอิงในโครงการของคุณ

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="โค้ดตัวอย่างนี้แสดงการแปลง PPSM เป็น PNG C#" offSpacer="" %}}

```cs
using (var presentation = new Presentation("template.ppsm"))
{
    // iterate over all slides in the presentation
    foreach (var slide in presentation.Slides)
    {
        // create a full scale image
        var bitmap = slide.GetThumbnail(1f, 1f);

        // save the image to disk in PNG format
        bitmap.Save(string.Format("Slide_{0}.png", slide.SlideNumber), System.Drawing.Imaging.ImageFormat.Png);
    }
} 

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Free App to Convert PPSM to PNG" sectionDescription="Check our live demos for [PPSM to PNG conversion](https://products.aspose.app/slides/conversion/ppsm-to-png) with following benefits." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your PPSM file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant PNG file." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 ไลบรารีการประมวลผลการนำเสนอสำหรับรูปแบบการนำเสนอ PowerPoint และ OpenOffice API ช่วยให้แอปพลิเคชันสามารถอ่าน เขียน ป้องกัน แก้ไข และแปลงงานนำเสนอใน .NET C# นักพัฒนาสามารถใช้เพื่อจัดการข้อความ รูปร่าง แผนภูมิ ตารางและภาพเคลื่อนไหว เพิ่มเสียงและวิดีโอลงในสไลด์ แสดงตัวอย่างสไลด์ และอื่นๆ อีกมากมาย



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PPSM" readMoreLink="https://docs.fileformat.com/presentation/ppsm/" >}}
Files with PPSM extension represent Macro-enabled Slide Show file format created with Microsoft PowerPoint 2007 or higher. Another similar file format is PPTM which differs in opening with Microsoft PowerPoint in editable format instead of running as Slide Show. When run as slide show, the PPSM file shows the presentation slides with contents intact in the slide show and is in read-only mode by default. PPSM files can still be edited in Microsoft PowerPoint by opening it in PowerPoint.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="png" readMoreLink="https://docs.fileformat.com/image/png/" >}}
PNG, Portable Network Graphics, refers to a type of raster image file format that use loseless compression. This file format was created as a replacement of Graphics Interchange Format (GIF) and has no copyright limitations. However, PNG file format does not support animations. PNG file format supports loseless image compression that makes it popular among its users. With the passage of time, PNG has evolved as one of the mostly used image file format. Almost all Operating Systems have support for opening PNG files. For example, Microsoft Windows viewer has the capability to open PNG files as the OS has by default the support available as part of installation.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="คุณยังสามารถแปลง PPSM เป็นรูปแบบไฟล์อื่นๆ ได้มากมาย รวมถึงบางรูปแบบตามรายการด้านล่าง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/ppsm-to-bmp/" name="PPSM TO BMP" description="ภาพบิตแมป" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/ppsm-to-emf/" name="PPSM TO EMF" description="รูปแบบไฟล์ Metafile ที่ปรับปรุงแล้ว" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/ppsm-to-gif/" name="PPSM TO GIF" description="รูปแบบการแลกเปลี่ยนกราฟิก" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/ppsm-to-html/" name="PPSM TO HTML" description="ภาษามาร์กอัปข้อความไฮเปอร์" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/ppsm-to-jpeg/" name="PPSM TO JPEG" description="ภาพ JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/ppsm-to-odp/" name="PPSM TO ODP" description="รูปแบบการนำเสนอ OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/ppsm-to-otp/" name="PPSM TO OTP" description="รูปแบบมาตรฐานของ OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/ppsm-to-pdf/" name="PPSM TO PDF" description="รูปแบบเอกสารพกพา" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/ppsm-to-pot/" name="PPSM TO POT" description="ไฟล์เทมเพลต Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/ppsm-to-potm/" name="PPSM TO POTM" description="ไฟล์เทมเพลต Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/ppsm-to-potx/" name="PPSM TO POTX" description="การนำเสนอเทมเพลต Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/ppsm-to-pps/" name="PPSM TO PPS" description="สไลด์โชว์ PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/ppsm-to-ppsx/" name="PPSM TO PPSX" description="สไลด์โชว์ PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/ppsm-to-ppt/" name="PPSM TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/ppsm-to-pptm/" name="PPSM TO PPTM" description="ไฟล์นำเสนอที่เปิดใช้งานมาโคร" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/ppsm-to-pptx/" name="PPSM TO PPTX" description="เปิดรูปแบบการนำเสนอ XML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/ppsm-to-svg/" name="PPSM TO SVG" description="กราฟิกแบบเวกเตอร์ที่ปรับขนาดได้" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/ppsm-to-swf/" name="PPSM TO SWF" description="รูปแบบ SWF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/ppsm-to-tiff/" name="PPSM TO TIFF" description="รูปแบบภาพที่ติดแท็ก" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/ppsm-to-xps/" name="PPSM TO XPS" description="ข้อมูลจำเพาะกระดาษ XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}