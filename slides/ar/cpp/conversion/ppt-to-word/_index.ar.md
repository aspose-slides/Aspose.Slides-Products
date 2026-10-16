---
lastmod: 2023-04-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: تحويل PPT إلى Word في C++
url: /ar/cpp/conversion/ppt-to-word/
keywords: تحويل PPT إلى Word ، PPT إلى Word ، PPT إلى DOC ، PowerPoint إلى Word ، C++ API ، مكتبة C++ ، CPP
description: تحويل PPT إلى Word في C++. استخدم واجهة برمجة تطبيقات مكتبة C++ لتحويل PowerPoint إلى Word
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="تحويل PPT إلى Word في C++" h2="واجهة برمجة تطبيقات C++ قوية عبر الأنظمة الأساسية لتحويل PowerPoint إلى Word باستخدام كود C++ بدون Microsoft PowerPoint أو Office" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تحويل PowerPoint إلى Word في C++" variant="code" %}}

يمكنك تحويل PPT إلى Word بسرعة باستخدام بضعة أسطر من التعليمات البرمجية

{{< blocks/products/pf/slides-design-update-10-2026/code title="كود C++ لتحويل PowerPoint إلى Word" >}}
```cpp
auto presentation = MakeObject<Presentation>();
auto doc = MakeObject<Aspose::Words::Document>();
auto builder = MakeObject<Aspose::Words::DocumentBuilder>(doc);

for (const auto& slide : presentation->get_Slides())
{
    // generates and inserts slide image
    auto bitmap = slide->GetThumbnail(1.0f, 1.0f);
    builder->InsertImage(bitmap);

    // inserts slide's texts
    for (const auto& shape : slide->get_Shapes())
    {
        if (ObjectExt::Is<AutoShape>(shape))
        {
            auto autoShape = System::AsCast<AutoShape>(shape);
            builder->Writeln(autoShape->get_TextFrame()->get_Text());
        }
    }

    builder->InsertBreak(Aspose::Words::BreakType::PageBreak);
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تحويل PowerPoint إلى Word باستخدام Aspose.Slides و Aspose.Words" %}}

[** Aspose.Slides for C++ **](https://products.aspose.com/slides/ar/cpp/) و [** Aspose.Words for C++ **](https://products.aspose.com/ الكلمات / cpp /) هي مكتبات C++ قوية تستخدم لمعالجة وتحويل عروض PowerPoint التقديمية ومستندات Word والملفات الأخرى. عندما تقوم بتحويل PowerPoint إلى Word ، فأنت تقوم بشكل أساسي بنقل محتويات شرائح العرض التقديمي إلى صفحات في مستند Word.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="كيفية تحويل PPT إلى Word" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم بتثبيت ** Aspose.Slides for C++ ** و ** Aspose.Words for C++ **{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم بإنشاء مثيل لفئة العرض التقديمي وفئة المستند.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم بتحميل العرض التقديمي PPT الذي تريد تحويله إلى Word.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم بإنشاء صور ونصوص بناءً على محتويات الشرائح.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}احفظ مستند Word الناتج.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="محول مجاني على الإنترنت"
  description="[كيفية تحويل PPT إلى HTML في Python](https://products.aspose.com/slides/ar/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="التحويلات المدعومة الأخرى" subTitle="يمكنك أيضًا تحويل PowerPoint إلى ملفات بتنسيقات أخرى" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/ppt-to-jpeg/" name="PPT TO JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/ppt-to-emf/" name="PPT TO EMF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/ppt-to-gif/" name="PPT TO GIF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
