---
title: تحويل PNG إلى PPTX في C++
url: /ar/cpp/conversion/png-to-pptx/
keywords: تحويل PNG إلى PPTX ، PNG إلى PPTX ، PowerPoint ، PNG ، PPTX ، C++ API ، مكتبة C++
description: تحويل PNG إلى PPTX في C++. استخدم واجهة برمجة تطبيقات مكتبة C++ لتحويل صور PNG إلى PowerPoint
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="تحويل PNG إلى PPTX في C++" h2="واجهة برمجة تطبيقات C++ قوية عبر الأنظمة الأساسية لتحويل PNG إلى PPTX باستخدام كود C++" >}}

{{% blocks/products/pf/feature-page-section h2="قم بتحويل PNG إلى PPTX باستخدام Aspose.Slides" %}}

[** Aspose.Slides for C++ **](https://products.aspose.com/slides/ar/cpp/) هي مكتبة C++ قوية تُستخدم لإنشاء وتحويل ومعالجة عروض PowerPoint التقديمية وملفات PDF ومستندات HTML وغيرها الملفات. عندما تقوم بتحويل PNG إلى PPTX ، فأنت تقوم بشكل أساسي بإنشاء عرض PowerPoint تقديمي يحتوي على شرائح بناءً على صور PNG.

{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="تحويل PNG إلى PPTX في C++" %}}
باستخدام [** Aspose.Slides for C++ **](https://products.aspose.com/slides/ar/cpp/) ، يمكنك تحويل صورة PNG إلى عرض تقديمي في PowerPoint ببضعة سطور فقط من التعليمات البرمجية:

{{% blocks/products/pf/agp/code-block title="كود C++ لتحويل PNG إلى PPTX" offSpacer="true" %}}
```cpp
auto pres = System::MakeObject<Presentation>();

auto slide = pres->get_Slides()->idx_get(0);
auto image = pres->get_Images()->AddImage(File::ReadAllBytes(u"image.png"));
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 0.0f, 720.0f, 540.0f, image);

pres->Save(u"pres.pptx", SaveFormat::Pptx);
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="كيفية تحويل PNG إلى PPTX في C++" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
قم بتثبيت ** Aspose.Slides for C++ **. راجع [** التثبيت **](https://docs.aspose.com/slides/cpp/installation/).
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




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="محول مجاني على الإنترنت" sectionDescription="[كيفية تحويل PPT إلى HTML في Python](https://products.aspose.com/slides/ar/en/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="تحويلات PowerPoint المدعومة الأخرى" subTitle="يمكنك أيضًا تحويل الملفات بتنسيقات أخرى إلى PowerPoint" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/cpp/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/cpp/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/cpp/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/cpp/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/cpp/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/cpp/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/cpp/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}