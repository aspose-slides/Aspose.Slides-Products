---
lastmod: 2023-04-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: تحويل PNG إلى PPT في C++
url: /ar/cpp/conversion/png-to-ppt/
keywords: تحويل PNG إلى PPT ، PNG إلى PPT ، PowerPoint ، PNG ، PPT ، C++ API ، مكتبة C++
description: تحويل PNG إلى PPT في C++. استخدم واجهة برمجة تطبيقات مكتبة C++ لتحويل صور PNG إلى PowerPoint
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="تحويل PNG إلى PPT في C++" h2="واجهة برمجة تطبيقات C++ قوية عبر الأنظمة الأساسية لتحويل PNG إلى PPT باستخدام كود C++" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تحويل PNG إلى PPT في C++" variant="code" %}}

باستخدام [** Aspose.Slides for C++ **](https://products.aspose.com/slides/ar/cpp/) ، يمكنك تحويل صورة PNG إلى عرض تقديمي في PowerPoint ببضعة سطور فقط من التعليمات البرمجية:

{{< blocks/products/pf/slides-design-update-10-2026/code title="كود C++ لتحويل PNG إلى PPT" >}}
```cpp
auto pres = System::MakeObject<Presentation>();

auto slide = pres->get_Slides()->idx_get(0);
auto image = pres->get_Images()->AddImage(File::ReadAllBytes(u"image.png"));
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 0.0f, 720.0f, 540.0f, image);

pres->Save(u"pres.pptx", SaveFormat::Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="قم بتحويل PNG إلى PPT باستخدام Aspose.Slides" %}}

[** Aspose.Slides for C++ **](https://products.aspose.com/slides/ar/cpp/) هي مكتبة C++ قوية تُستخدم لإنشاء وتحويل ومعالجة عروض PowerPoint التقديمية وملفات PDF ومستندات HTML وغيرها الملفات. عندما تقوم بتحويل PNG إلى PPT ، فأنت تقوم بشكل أساسي بإنشاء عرض PowerPoint تقديمي يحتوي على شرائح بناءً على صور PNG.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="كيفية تحويل PNG إلى PPT في C++" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم بتثبيت ** Aspose.Slides for C++ **. راجع [** التثبيت **](https://docs.aspose.com/slides/cpp/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}أضف المكتبة كمرجع في مشروعك.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم بإنشاء مثيل لفئة العرض التقديمي.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم بتحميل صورة PNG التي تريد تحويلها إلى PPT.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}احفظ الملف الناتج كعرض تقديمي PPT.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="محول مجاني على الإنترنت"
  description="[كيفية تحويل PPT إلى HTML في Python](https://products.aspose.com/slides/ar/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="تحويلات PowerPoint المدعومة الأخرى" subTitle="يمكنك أيضًا تحويل الملفات بتنسيقات أخرى إلى PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/html-to-pptx/" name="HTML TO PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
