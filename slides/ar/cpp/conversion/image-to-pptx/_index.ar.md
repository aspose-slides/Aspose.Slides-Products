---
lastmod: 2023-03-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: تحويل الصورة إلى PPTX في C++
url: /ar/cpp/conversion/image-to-pptx/
keywords: صورة إلى PPTX ، تحويل الصورة إلى PPTX ، C++ API ، مكتبة C++ ، صورة ، PPTX
description: تحويل الصورة إلى PPTX في C++. استخدم واجهة برمجة تطبيقات مكتبة C++ لتحويل ملفات الصور إلى ملفات PDF
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="تحويل الصورة إلى PPTX في C++" h2="مكتبة C++ عالية السرعة ومتعددة المنصات تساعد في تطوير التطبيقات مع القدرة على إنشاء ملفات Microsoft PowerPoint و OpenOffice أو دمجها أو فحصها أو تحويلها دون استخدام أي برنامج مثل Microsoft أو Open Office أو Adobe PDF." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تحويل الصورة إلى PPTX باستخدام C++" variant="code" %}}

لتحويل الصورة إلى PPTX ، ستحتاج إلى إنشاء عرض تقديمي من ملف صورة وحفظه بتنسيق PPTX.

{{< blocks/products/pf/slides-design-update-10-2026/code title="كود C++ لتحويل الصورة إلى PPTX" >}}
```cpp

auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto image = pres->get_Images()->AddImage(File::ReadAllBytes(u"image.jpg"));
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 0.0f, 720.0f, 540.0f, image);
pres->Save(u"presentation.pptx", SaveFormat::Pptx);

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تحويل الصورة إلى PPTX في C++" %}}

[** Aspose.Slides for C++ **](https://products.aspose.com/slides/ar/cpp/) هي مكتبة C++ قوية لإنشاء ملفات العروض التقديمية ومعالجتها. علاوة على ذلك ، فإنه يوفر طرقًا مرنة لتحويل الصورة إلى PPTX. باستخدام ** Aspose.Slides for C++ ** ، يمكن لأي مطور أو تطبيق تحويل الصورة إلى ملفات PPTX ببضعة أسطر من كود C++.

بصفتها واجهة برمجة تطبيقات حديثة لمعالجة المستندات ، تقوم Aspose.Slides for C++ بتصدير ملفات الصور إلى تنسيقات ملفات PPTX بسرعة. تسمح لك مكتبة Aspose PowerPoint بتحويل الصور إلى ملفات PDF والعديد من تنسيقات الملفات الأخرى

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="كيفية تحويل الصورة إلى PPTX باستخدام Aspose.Slides for C++ API" intro="هذه هي خطوات تحويل الصورة إلى PPTX في C++." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ثبّت [** Aspose.Slides for C++ **](https://products.aspose.com/slides/ar/cpp/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}أضف مرجع مكتبة (استيراد المكتبة) إلى مشروع C++ الخاص بك.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}افتح ملفات الصور المصدر في C++.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}حفظ النتيجة كملف PPTX.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="محول مجاني على الإنترنت"
  description="[كيفية تحويل PPT إلى HTML في Python](https://products.aspose.com/slides/ar/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="تحويل الصورة إلى تنسيقات أخرى مدعومة" subTitle="يمكنك أيضًا تحويل الصورة وحفظها في تنسيقات ملفات أخرى. انظر جميع التنسيقات المدعومة أدناه" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/image-to-ppt/" name="IMAGE TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/html-to-pptx/" name="HTML TO PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
