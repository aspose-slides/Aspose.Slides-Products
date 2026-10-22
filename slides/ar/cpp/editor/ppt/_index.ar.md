---
lastmod: 2022-12-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: تحرير PPT في C++
url: /ar/cpp/editor/ppt/
keywords: تحرير PPT ، تحرير PowerPoint ، PPT ، PowerPoint ، C++ API ، مكتبة C++
description: تحرير PPT في C++. استخدم واجهة برمجة تطبيقات مكتبة C++ لتحرير عرض PowerPoint التقديمي
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="تحرير PPT في C++" h2="مكتبة C++ عالية السرعة ومتعددة المنصات لتحرير PPT باستخدام كود C++" related="PDF,HTML" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تحرير PPT في C++" variant="code" %}}

باستخدام [** Aspose.Slides for C++ **](https://products.aspose.com/slides/ar/cpp/) ، يمكنك إضافة سطر جديد من النص إلى مستند PPT ببضعة سطور فقط من التعليمات البرمجية.

{{< blocks/products/pf/slides-design-update-10-2026/code title="كود C++ لتحرير PPT" >}}
```cpp

auto pres = System::MakeObject<Presentation>(u"pres.ppt");

auto slide = pres->get_Slides()->idx_get(0);
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 50.0f);
shape->get_TextFrame()->set_Text(u"New text");

pres->Save(u"pres.pdf", SaveFormat::Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تحرير PPT باستخدام Aspose.Slides" %}}

[** Aspose.Slides for C++ **](https://products.aspose.com/slides/ar/cpp/) هي مكتبة C++ قوية تُستخدم لمعالجة العروض التقديمية وتحريرها. يمكنك تحرير عرض PPT عن طريق إضافة سطر جديد من النص إليه.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="كيفية تحرير PPT في C++" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم بتثبيت ** Aspose.Slides for C++ **. راجع [** التثبيت **](https://docs.aspose.com/slides/cpp/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}أضف المكتبة كمرجع في مشروعك.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم بإنشاء مثيل لفئة العرض التقديمي.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم بتحميل العرض التقديمي PPT الذي تريد تحريره.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}أضف سطرًا جديدًا من النص.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}احفظ ملف PowerPoint الذي تم تغييره.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="قم بتحرير الملفات الأخرى" subTitle="يمكنك أيضًا تحرير الملفات بتنسيقات أخرى" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/editor/pdf/" name="Edit PDF" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/editor/html/" name="Edit HTML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
