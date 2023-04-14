---
title: تحويل PNG إلى PPTX في C#
url: /ar/net/conversion/png-to-pptx/
keywords: قم بتحويل PNG إلى PPTX و PNG إلى PPTX و PowerPoint و PNG و PPTX و C# API و .NET Library
description: تحويل PNG إلى PPTX في C#. استخدم .NET library API لتحويل صور PNG إلى PowerPoint
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="تحويل PNG إلى PPTX في C#" h2="واجهة برمجة تطبيقات .NET API قوية ومتعددة المنصات لتحويل PNG إلى PPTX باستخدام كود C# على NET Framework أو .NET Core أو Windows Azure أو Mono أو Xamarin الأنظمة الأساسية" >}}

{{% blocks/products/pf/feature-page-section h2="قم بتحويل PNG إلى PPTX باستخدام Aspose.Slides" %}}

[** Aspose.Slides for .NET **](https://products.aspose.com/slides/ar/net/) هي مكتبة .NET قوية تُستخدم لإنشاء وتحويل ومعالجة عروض PowerPoint التقديمية وملفات PDF ومستندات HTML و وغيرها من الملفات. عندما تقوم بتحويل PNG إلى PPTX ، فأنت تقوم بشكل أساسي بإنشاء عرض PowerPoint تقديمي يحتوي على شرائح بناءً على صور PNG.

{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="تحويل PNG إلى PPTX في C#" %}}
باستخدام [** Aspose.Slides for .NET **](https://products.aspose.com/slides/ar/net/) ، يمكنك تحويل صورة PNG إلى عرض PowerPoint تقديمي ببضعة سطور من التعليمات البرمجية:

{{% blocks/products/pf/agp/code-block title="كود C# لتحويل PNG إلى PPTX" offSpacer="true" %}}
```cs
using (Presentation pres = new Presentation())
{
    IPPImage image = pres.Images.AddImage(File.ReadAllBytes("image.png"));
    pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 0, 720, 540, image);
    pres.Save("Presentation.pptx", SaveFormat.Pptx);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="كيفية تحويل PNG إلى PPTX في C#" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
ثبّت ** Aspose.Slides for .NET **. راجع [** التثبيت **](https://docs.aspose.com/slides/net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
أضف المكتبة كمرجع في مشروعك.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
قم بإنشاء مثيل لفئة العرض التقديمي.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
قم بتحميل صورة PNG التي تريد تحويلها إلى PPTX.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
احفظ الملف الناتج كعرض تقديمي PPTX.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="محول مجاني على الإنترنت" sectionDescription="[كيفية تحويل PPT إلى HTML في Python](https://products.aspose.com/slides/ar/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="تحويلات PowerPoint المدعومة الأخرى" subTitle="يمكنك أيضًا تحويل الملفات بتنسيقات أخرى إلى PowerPoint" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/net/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/net/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/net/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/net/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/net/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/net/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}