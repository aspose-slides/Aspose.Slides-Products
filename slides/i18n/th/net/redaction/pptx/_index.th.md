---
title: ค้นหาและแทนที่ข้อความในเอกสาร PPTX ผ่าน .NET
weight: 4070
url: /th/net/redaction/pptx/ 
description: ซอร์สโค้ด C# เพื่อแก้ไขข้อมูลที่ละเอียดอ่อนในไฟล์ PPTX บน .NET Framework, .NET Core, Windows Azure, Mono หรือ Xamarin Platforms
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="แก้ไขรูปแบบ PPTX ใน C #" h2="ข้อมูลการแก้ไขที่ละเอียดอ่อนของเอกสาร PPTX ดั้งเดิมและมีประสิทธิภาพสูงโดยใช้ Aspose.Slides ฝั่งเซิร์ฟเวอร์สำหรับ .NET API โดยไม่ต้องใช้ซอฟต์แวร์ใดๆ เช่น Microsoft หรือ Adobe PDF" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="PPTX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/net" installationsDocsLink="https://docs.aspose.com/slides/net" nugetLink="https://www.nuget.org/packages/aspose.slides.net" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/net" learnAsLink="https://docs.aspose.com/slides/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="วิธี Redact ไฟล์ PPTX โดยใช้ C #" %}}

 เพื่อแก้ไขไฟล์ PPTX เราจะใช้
 [Aspose.Slides สำหรับ .NET](https://products.aspose.com/slides/net)
 API ซึ่งเป็น API การจัดการเอกสารที่มีคุณลักษณะหลากหลาย มีประสิทธิภาพ และใช้งานง่ายสำหรับแพลตฟอร์ม C# เปิด
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 package manager ค้นหา
 **สมมติ.สไลด์**
 และติดตั้ง คุณยังสามารถใช้คำสั่งต่อไปนี้จาก Package Manager Console

{{% blocks/products/pf/agp/code-block title="สั่งการ" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.NET

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="ขั้นตอนในการ Redact ไฟล์ PPTX ใน C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="การค้นหาเอกสารพื้นฐานและแทนที่ข้อความในเนื้อหา ความคิดเห็น หรือข้อมูลเมตาด้วย API ของ [Aspose.Slides for .NET](https://products.aspose.com/slides/net) สามารถทำได้โดยใช้โค้ดเพียงไม่กี่บรรทัด ค้นหาและแทนที่ข้อความใน PowerPoint และ OpenOffice แก้ไขข้อความ ความคิดเห็น ข้อมูลเมตาในการนำเสนอผ่านการจับคู่ข้อมูล regexp" >}}

{{< blocks/products/pf/agp/step-autogen >}}
โหลดการนำเสนอ PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
วนซ้ำแต่ละสไลด์และรับคอลเลกชั่น textFrame
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
วนรอบคอลเลกชัน
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ใช้วิธีแทนที่แล้วเน้นข้อความ
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
บันทึกการนำเสนอ
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

{{% blocks/products/pf/agp/text %}}

 API ของเราได้รับการสนับสนุนบนแพลตฟอร์มหลักและระบบปฏิบัติการทั้งหมด ก่อนดำเนินการโค้ดด้านล่าง โปรดตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นต่อไปนี้ในระบบของคุณ

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows หรือระบบปฏิบัติการที่เข้ากันได้กับ .NET Framework, .NET Core, Windows Azure, Mono หรือ Xamarin Platforms
- สภาพแวดล้อมการพัฒนาเช่น Microsoft Visual Studio
- Aspose.Slides สำหรับ .NET DLL ที่อ้างอิงในโครงการของคุณ - ติดตั้งจาก NuGet โดยใช้ปุ่มดาวน์โหลดด้านบน

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="แก้ไขไฟล์ PPTX - C#" offSpacer="" %}}

```cs
using (Presentation pres = new Presentation("pres.pptx")){
    const string toRedact = "bKIM";
    string stub = new string(' ', toRedact.Length);
   //Using Aspose.Slides, one can use highlight text color feature to Redact text.
    foreach (ISlide slide in pres.Slides){
        ITextFrame[] textFrames = SlideUtil.GetAllTextBoxes(slide);
        foreach (ITextFrame textFrame in textFrames){
            textFrame.Text = textFrame.Text.Replace(toRedact, stub);
            textFrame.HighlightText(stub, Color.Black);
        }
    }

    pres.Save("pres-edited.pptx", SaveFormat.Pptx);
}

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="เกี่ยวกับ Aspose.Slides สำหรับ .NET API" %}}

 Aspose.Slides API สามารถใช้อ่าน เขียน จัดการ และแปลงเอกสาร Microsoft PowerPoint เป็น PDF, XPS, HTML, TIFF, ODP และรูปแบบอื่นๆ ได้ หนึ่งสามารถสร้างไฟล์ใหม่ตั้งแต่เริ่มต้นและบันทึกในรูปแบบที่รองรับที่เกี่ยวข้อง Aspose.Slides เป็น API แบบสแตนด์อโลนสำหรับการสร้าง แยกวิเคราะห์ หรือจัดการการนำเสนอ สไลด์ และองค์ประกอบ และไม่ขึ้นกับซอฟต์แวร์ใดๆ เช่น Microsoft หรือ OpenOffice  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Online PPTX Redaction Live Demos" sectionDescription="Search and replace text in contents, comments or metadata in PPTX documents right now by visiting our [Live Demos website](https://products.aspose.app/slides/redaction). The live demo has the following benefits" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your PPTX files." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" It will be redacted instantly." >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PPTX" readMoreLink="https://docs.fileformat.com/presentation/pptx/" >}}
Files with PPTX extension are presentation files created with popular Microsoft PowerPoint application. Unlike the previous version of presentation file format PPT which was binary, the PPTX format is based on the Microsoft PowerPoint open XML presentation file format. A presentation file is a collection of slides where each slide can comprise of text, images, formatting, animations, and other media. These slides are presented to audience in the form of slideshows with custom presentation settings. 

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="รูปแบบการตอบโต้อื่นๆ ที่รองรับ" subTitle="เมื่อใช้ C# เราสามารถ redact รูปแบบต่าง ๆ ได้อย่างง่ายดายรวมถึง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/redaction/odp/" name="ODP" description="รูปแบบการนำเสนอ OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/redaction/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}