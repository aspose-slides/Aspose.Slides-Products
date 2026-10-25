---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: إضافة علامة مائية إلى عروض ODP التقديمية باستخدام C++
url: /ar/cpp/watermark/odp/
description: أضف علامات مائية نصية أو مصورة إلى عروض ODP التقديمية في C++. استخدم Aspose.Slides for C++ لوضع العلامات المائية على الشرائح.
keywords: إضافة علامة مائية إلى ODP، إضافة علامة مائية نصية إلى ODP، إضافة علامة مائية مصورة إلى ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="إضافة علامة مائية إلى عرض ODP تقديمي باستخدام C++" h2="استخدم Aspose.Slides for C++ لإضافة علامات مائية نصية أو مصورة إلى ملفات العروض التقديمية دون Microsoft PowerPoint." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="إضافة علامة مائية إلى عرض ODP تقديمي عبر C++" variant="code" %}}

يتيح لك Aspose.Slides for C++ إضافة علامات مائية نصية أو مصورة إلى عروض ODP التقديمية. أضف شكل العلامة المائية إلى الشريحة الرئيسية باستخدام `AddAutoShape`، وأضف النص باستخدام `AddTextFrame`، أو املأ الشكل بصورة محمّلة عبر `File::ReadAllBytes` و`AddImage`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="إضافة علامة مائية نصية إلى ODP باستخدام C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");
auto masterSlide = presentation->get_Master(0);
auto watermarkShape = masterSlide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100, 100, 400, 80);

watermarkShape->AddTextFrame(u"Watermark");
presentation->Save(u"watermarked-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="إضافة علامة مائية مصورة إلى عرض ODP تقديمي باستخدام C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");
auto masterSlide = presentation->get_Master(0);
auto watermarkShape = masterSlide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100, 100, 400, 200);

auto imageData = File::ReadAllBytes(u"watermark.png");
auto watermarkImage = presentation->get_Images()->AddImage(imageData);

watermarkShape->get_FillFormat()->set_FillType(FillType::Picture);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->get_Picture()->set_Image(watermarkImage);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->set_PictureFillMode(PictureFillMode::Stretch);

presentation->Save(u"image-watermarked-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="كيفية إضافة علامة مائية إلى ODP باستخدام C++" intro="اتبع هذه الخطوات لإضافة علامة مائية نصية أو مصورة إلى ملفات ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}حمّل ملف ODP باستخدام الفئة `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}اختر الشريحة الرئيسية من المجموعة `Presentation::get_Masters`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}أضف شكل العلامة المائية باستخدام الأسلوب `AddAutoShape`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}أضف نص العلامة المائية باستخدام الأسلوب `AddTextFrame` أو عيّن تعبئة بصورة باستخدام `AddImage`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}احفظ الملف بالعلامة المائية باستخدام `SaveFormat::Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="مبني باستخدام Aspose.Slides" title="أضف علامات مائية إلى ملفات ODP عبر الإنترنت" description="تطبيق Aspose.Slides Watermark المجاني مبني باستخدام [Aspose.Slides for C++](https://products.aspose.com/slides/ar/cpp/)، وهي نفس واجهة برمجة التطبيقات المستخدمة في الكود أعلاه. افتحه واكتشف ما يمكن لواجهة برمجة التطبيقات فعله بملفات ODP الخاصة بك." button="افتح Aspose.Slides Watermark" note="[جميع التطبيقات المجانية](https://products.aspose.app/slides/family)" >}}
- يعمل في متصفحك، دون الحاجة إلى تثبيت أي شيء.
- شاهد كيف يضيف Aspose.Slides العلامات المائية قبل كتابة الكود.
- أضف علامة مائية نصية أو مصورة إلى ملف ODP.
- نزّل الملف بالعلامة المائية.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="تنسيقات أخرى تدعم العلامات المائية" subTitle="باستخدام C++ يمكنك أيضًا إضافة علامات مائية إلى التنسيقات التالية." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/cpp/watermark/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/cpp/watermark/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
