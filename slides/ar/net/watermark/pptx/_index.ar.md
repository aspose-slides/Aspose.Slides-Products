---
title: مستند العلامة المائية PPTX عبر .NET
weight: 5590
url: /ar/net/watermark/pptx/ 
description: كود مصدر C # لإضافة أو إزالة العلامة المائية إلى ملف PPTX على .NET Framework أو .NET Core أو Windows Azure أو Mono أو Xamarin الأنظمة الأساسية.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="أضف علامة مائية نصية إلى PPTX عبر C #" h2="قم ببناء تطبيقات .NET الخاصة بك لوضع علامة مائية على ملفات PPTX باستخدام واجهات برمجة التطبيقات من جانب الخادم." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/net" installationsDocsLink="https://docs.aspose.com/slides/net" nugetLink="https://www.nuget.org/packages/aspose.slides.net" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/net" learnAsLink="https://docs.aspose.com/slides/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="كيفية وضع علامة مائية على ملف PPTX باستخدام C #" %}}

 من أجل وضع علامة مائية على ملف PPTX ، سنستخدمه
 [Aspose.Slides for .NET](https://products.aspose.com/slides/ar/net)
 API وهو واجهة برمجة تطبيقات لمعالجة المستندات غنية بالميزات وقوية وسهلة الاستخدام لمنصة C #. يفتح
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 مدير الحزم ، ابحث عن
 ** Aspose.Slides **
 وتثبيت. يمكنك أيضًا استخدام الأمر التالي من Package Manager Console.

{{% blocks/products/pf/agp/code-block title="أمر" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.NET

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="خطوات إضافة علامة مائية إلى PPTX عبر C #" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="أنت بحاجة إلى [aspose.slides.dll](https://downloads.aspose.com/slides/net) لتجربة سير العمل التالي في بيئتك الخاصة." >}}

{{< blocks/products/pf/agp/step-autogen >}}
قم بإنشاء مثيل لفئة العرض التقديمي
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
حدد العرض التقديمي الرئيسي
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
أضف نوع الشكل باستخدام AddAutoShape
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
أضف نص العلامة المائية باستخدام AddTextFrame
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات النظام" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Slides for .NET مدعوم على جميع أنظمة التشغيل الرئيسية. فقط تأكد من أن لديك المتطلبات الأساسية التالية.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows أو نظام تشغيل متوافق مع .NET Framework أو .NET Core أو Windows Azure أو Mono أو Xamarin الأنظمة الأساسية.
- بيئة التطوير مثل Microsoft Visual Studio.
- Aspose.Slides for .NET المشار إليها في مشروعك.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="أضف علامة مائية إلى PPTX - C #" offSpacer="" %}}

```cs

// create a Presentation from scratch
using (var presentation = new Aspose.Slides.Presentation())
{
    // get the Master Slide to add watermark on all slides
    var master = presentation.Masters[0];
    // add a new shape using IShapeColection.AddAutoShape
    var shape = master.Shapes.AddAutoShape(Aspose.Slides.ShapeType.Triangle, 0, 0, 0, 0);
    // set watermark text
    shape.AddTextFrame("CONFIDENTIAL");
    // save presentation in PPTX format
    presentation.Save("output.pptx", Aspose.Slides.Export.SaveFormat.Pptx);
}  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="حول Aspose.Slides for .NET API" %}}

 يمكن استخدام Aspose.Slides API لقراءة وكتابة ومعالجة وتحويل مستندات Microsoft PowerPoint إلى PDF و XPS و HTML و TIFF و ODP وتنسيقات أخرى متنوعة. يمكن للمرء إنشاء ملفات جديدة من البداية وحفظ تلك في التنسيقات المدعومة ذات الصلة. Aspose.Slides هي واجهة برمجة تطبيقات مستقلة لإنشاء العروض التقديمية والشرائح والعناصر أو تحليلها أو معالجتها ، ولا تعتمد على أي برنامج مثل Microsoft أو OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Watermark PPTX via Online App" sectionDescription="Add watermark to PPTX documents by visiting our [Live Demos website](https://products.aspose.app/slides/watermark). The live demo has the following benefits" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Just upload your PPTX file, set your watermark and hit \"Add\" button" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Instantly get the download link for the resultant file" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PPTX" readMoreLink="https://docs.fileformat.com/presentation/pptx/" >}}
Files with PPTX extension are presentation files created with popular Microsoft PowerPoint application. Unlike the previous version of presentation file format PPT which was binary, the PPTX format is based on the Microsoft PowerPoint open XML presentation file format. A presentation file is a collection of slides where each slide can comprise of text, images, formatting, animations, and other media. These slides are presented to audience in the form of slideshows with custom presentation settings.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="تنسيقات العلامات المائية الأخرى المدعومة" subTitle="باستخدام C # ، يمكن للمرء بسهولة وضع علامة مائية على تنسيقات مختلفة بما في ذلك." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/net/watermark/ppt/" name="PPT" description="مايكروسوفت باور بوينت 97-2003" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}