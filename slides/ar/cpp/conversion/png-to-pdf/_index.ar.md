---
title: تحويل PNG إلى PDF في C ++
url: /ar/cpp/conversion/png-to-pdf/
keywords: PNG إلى PDF ، تحويل PNG إلى PDF ، واجهة برمجة تطبيقات C ++ ، مكتبة C ++ ، PNG ، PDF
description: تحويل PNG إلى PDF في C ++. استخدم واجهة برمجة تطبيقات مكتبة C ++ لتحويل ملفات PNG إلى PDF
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="تحويل PNG إلى PDF في C ++" h2="مكتبة C ++ عالية السرعة ومتعددة المنصات تساعد في تطوير التطبيقات مع القدرة على إنشاء ملفات Microsoft PowerPoint و OpenOffice أو دمجها أو فحصها أو تحويلها دون استخدام أي برنامج مثل Microsoft أو Open Office أو Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="تحويل PNG إلى PDF في C ++" %}}

[** Aspose.Slides for C ++ **](https://products.aspose.com/slides/ar/cpp/) هي مكتبة C ++ قوية لإنشاء ملفات العروض التقديمية ومعالجتها. علاوة على ذلك ، فإنه يوفر طرقًا مرنة لتحويل PNG إلى PDF. باستخدام ** Aspose.Slides for C ++ ** ، يمكن لأي مطور أو تطبيق تحويل PNG إلى PDF من خلال بضعة أسطر من كود C ++.

كواجهة برمجة تطبيقات حديثة لمعالجة المستندات ، تقوم Aspose.Slides for C ++ بتصدير ملفات PNG إلى PDF تنسيقات الملفات بسرعة. تسمح لك مكتبة Aspose PowerPoint بتحويل PNG إلى PDF والعديد من تنسيقات الملفات الأخرى

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="تحويل PNG إلى PDF باستخدام C ++" %}}
لتحويل PNG إلى PDF ، ستحتاج إلى إنشاء عرض تقديمي من ملف PNG وحفظه بتنسيق PDF.

{{% blocks/products/pf/agp/code-block title="كود C ++ لتحويل PNG إلى PDF" offSpacer="true" %}}

```cpp

auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto image = pres->get_Images()->AddImage(File::ReadAllBytes(u"image.png"));
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pres->Save(u"pres.pdf", SaveFormat::Pdf);

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="كيفية تحويل PNG إلى PDF باستخدام Aspose.Slides for C ++ API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="هذه هي خطوات تحويل PNG إلى PDF في C ++." >}}

{{< blocks/products/pf/agp/step-autogen >}}
ثبّت [** Aspose.Slides for C ++ **](https://products.aspose.com/slides/ar/cpp/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
أضف مرجع مكتبة (استيراد المكتبة) إلى مشروع C ++ الخاص بك.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
افتح المصدر PNG ملفات في C ++.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
حفظ النتيجة كملف PDF.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="محول مجاني على الإنترنت" sectionDescription="[كيفية تحويل PPT إلى HTML في Python](https://products.aspose.com/slides/ar/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="تحويل PNG إلى التنسيقات المدعومة الأخرى" subTitle="يمكنك أيضًا تحويل PNG وحفظه إلى تنسيقات ملفات أخرى. انظر جميع التنسيقات المدعومة أدناه" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/cpp/conversion/png-to-jpg/" name="PNG TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/cpp/conversion/png-to-svg/" name="PNG TO SVG" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}