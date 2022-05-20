---
title: مستند العلامة المائية PPTX عبر C ++
weight: 2900
url: /ar/cpp/watermark/pptx/ 
description: مثال على كود C ++ لإضافة أو إزالة العلامة المائية إلى ملف PPTX على C ++ Runtime Environment لنظام التشغيل Windows 32 بت و Windows 64 بت و Linux 64 بت.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="أضف علامة مائية نصية إلى PPTX عبر C ++" h2="قم ببناء تطبيقات C ++ الخاصة بك لوضع علامة مائية على ملفات PPTX باستخدام واجهات برمجة التطبيقات من جانب الخادم." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/cpp" installationsDocsLink="https://docs.aspose.com/slides/cpp" nugetLink="https://www.nuget.org/packages/aspose.slides" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/cpp" learnAsLink="https://docs.aspose.com/slides/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="كيفية وضع علامة مائية على ملف PPTX باستخدام C ++" %}}

 من أجل وضع علامة مائية على ملف PPTX ، سنستخدمه
 [Aspose.Slides for C ++](https://products.aspose.com/slides/ar/cpp)
 API وهي غنية بالميزات وقوية وسهلة الاستخدام لعلامة مائية للوثائق API لمنصة C ++. يمكنك تنزيل أحدث إصدار مباشرة ، فقط افتح
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 مدير الحزم ، ابحث عن
 ** Aspose.Slides.Cpp **
 وتثبيت. يمكنك أيضًا استخدام الأمر التالي من Package Manager Console.

{{% blocks/products/pf/agp/code-block title="أمر" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="خطوات إضافة علامة مائية إلى PPTX عبر C ++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="أنت بحاجة إلى [aspose.slides.dll](https://downloads.aspose.com/slides/cpp) لتجربة سير العمل التالي في بيئتك الخاصة." >}}

{{< blocks/products/pf/agp/step-autogen >}}
تحميل ملفات PPTX مع مثيل لفئة العرض التقديمي
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
احصل على الشريحة الأولى
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
قم بإضافة شكل تلقائي من نوع المستطيل
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
أضف TextFrame إلى المستطيل
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
قم بإنشاء كائن فقرة لإطار النص
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
إنشاء كائن جزء للفقرة
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
أضف علامة مائية باستخدام set \ _Text ()
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
احفظ المستند
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات النظام" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Slides for C ++ يدعم جميع المنصات وأنظمة التشغيل الرئيسية. يرجى التأكد من توفر المتطلبات التالية.

{{% /blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="أضف علامة مائية إلى PPTX - C ++" offSpacer="" %}}

```cs

// Load the desired PPTX File
SharedPtr<Presentation> pres = MakeObject<Presentation>(u"templatePath.pptx");

// Access first slide
SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Add an AutoShape of Rectangle type
SharedPtr<IAutoShape>  ashp = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150, 75, 150, 50);

ashp->get_FillFormat()->set_FillType(FillType::NoFill);

// Add TextFrame to the Rectangle
ashp->AddTextFrame(u" ");

// Accessing the text frame
SharedPtr<ITextFrame>  txtFrame = ashp->get_TextFrame();

// Create the Paragraph object for text frame
SharedPtr<IParagraph> paragraph = txtFrame->get_Paragraphs()->idx_get(0);

// Create Portion object for paragraph
SharedPtr<IPortion> portion = paragraph->get_Portions()->idx_get(0);
portion->set_Text(u"Watermark Text Watermark Text Watermark Text");

//Adding another shape
SharedPtr<IAutoShape>  ashape2 = slide->get_Shapes()->AddAutoShape(ShapeType::Triangle, 200, 365, 400, 150);

//Reorder shape
slide->get_Shapes()->Reorder(2, ashape2);

// Save PPTX to Disk
pres->Save(u"outPath.pptx", Aspose::Slides::Export::SaveFormat::Pptx);  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="حول Aspose.Slides for C ++ API" %}}

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

{{< blocks/products/pf/agp/other-supported-section title="تنسيقات العلامات المائية الأخرى المدعومة" subTitle="باستخدام C ++ ، يمكن للمرء بسهولة وضع علامة مائية على تنسيقات مختلفة بما في ذلك." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/cpp/watermark/ppt/" name="PPT" description="مايكروسوفت باور بوينت 97-2003" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}