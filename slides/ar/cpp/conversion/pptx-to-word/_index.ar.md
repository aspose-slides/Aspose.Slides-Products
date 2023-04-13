---
title: تحويل PPTX إلى Word في C++
url: /ar/cpp/conversion/pptx-to-word/
keywords: تحويل PPTX إلى Word ، PPTX إلى Word ، PPTX إلى DOC ، PowerPoint إلى Word ، C++ API ، C++ Library ، CPP
description: تحويل PPTX إلى Word في C++. استخدم واجهة برمجة تطبيقات مكتبة C++ لتحويل PowerPoint إلى Word
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="تحويل PPTX إلى Word في C++" h2="واجهة برمجة تطبيقات C++ قوية عبر الأنظمة الأساسية لتحويل PowerPoint إلى Word باستخدام كود C++ بدون Microsoft PowerPoint أو Office" >}}

{{% blocks/products/pf/feature-page-section h2="تحويل PowerPoint إلى Word باستخدام Aspose.Slides و Aspose.Words" %}}

[** Aspose.Slides for C++ **](https://products.aspose.com/slides/ar/cpp/) و [** Aspose.Words for C++ **](https://products.aspose.com/ الكلمات / cpp /) هي مكتبات C++ قوية تستخدم لمعالجة وتحويل عروض PowerPoint التقديمية ومستندات Word والملفات الأخرى. عندما تقوم بتحويل PowerPoint إلى Word ، فأنت تقوم بشكل أساسي بنقل محتويات شرائح العرض التقديمي إلى صفحات في مستند Word.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="تحويل PowerPoint إلى Word في C++" %}}
يمكنك تحويل PPTX إلى Word بسرعة ببضعة أسطر من التعليمات البرمجية

{{% blocks/products/pf/agp/code-block title="كود C++ لتحويل PowerPoint إلى Word" offSpacer="true" %}}
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
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="كيفية تحويل PPTX إلى Word" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
قم بتثبيت ** Aspose.Slides for C++ ** و ** Aspose.Words for C++ ** 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
قم بإنشاء مثيل لفئة العرض التقديمي وفئة المستند.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
قم بتحميل العرض التقديمي PPTX الذي تريد تحويله إلى Word.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
قم بإنشاء صور ونصوص بناءً على محتويات الشرائح.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
احفظ مستند Word الناتج.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="محول مجاني على الإنترنت" sectionDescription="[كيفية تحويل PPT إلى HTML في Python](https://products.aspose.com/slides/ar/en/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="التحويلات المدعومة الأخرى" subTitle="يمكنك أيضًا تحويل PowerPoint إلى ملفات بتنسيقات أخرى" >}}


{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/cpp/conversion/pptx-to-html/" name="PPTX TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/cpp/conversion/pptx-to-jpeg/" name="PPTX TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/cpp/conversion/pptx-to-png/" name="PPTX TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/cpp/conversion/pptx-to-svg/" name="PPTX TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/cpp/conversion/pptx-to-bmp/" name="PPTX TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/cpp/conversion/pptx-to-emf/" name="PPTX TO EMF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/cpp/conversion/pptx-to-gif/" name="PPTX TO GIF" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}