---
title: تحويل PDF إلى PNG في C ++
url: /ar/cpp/conversion/pdf-to-png/
keywords: PDF إلى PNG ، تحويل PDF إلى PNG ، واجهة برمجة تطبيقات C ++ ، مكتبة C ++ ، PDF ، PNG
description: تحويل PDF إلى PNG في C ++. استخدم واجهة برمجة تطبيقات مكتبة C ++ لتحويل ملفات PDF إلى PNG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="تحويل PDF إلى PNG في C ++" h2="مكتبة C ++ عالية السرعة ومتعددة المنصات تساعد في تطوير التطبيقات مع القدرة على إنشاء ملفات Microsoft PowerPoint و OpenOffice أو دمجها أو فحصها أو تحويلها دون استخدام أي برنامج مثل Microsoft أو Open Office أو Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="تحويل PDF إلى PNG في C ++" %}}

[** Aspose.Slides for C ++ **](https://products.aspose.com/slides/ar/cpp/) هي مكتبة C ++ قوية لإنشاء ملفات العروض التقديمية ومعالجتها. علاوة على ذلك ، فإنه يوفر طرقًا مرنة لتحويل PDF إلى PNG. باستخدام ** Aspose.Slides for C ++ ** ، يمكن لأي مطور أو تطبيق تحويل PDF إلى PNG من خلال بضعة أسطر من كود C ++.

كواجهة برمجة تطبيقات حديثة لمعالجة المستندات ، تقوم Aspose.Slides for C ++ بتصدير ملفات PDF إلى PNG تنسيقات الملفات بسرعة. تسمح لك مكتبة Aspose PowerPoint بتحويل PDF إلى PNG والعديد من تنسيقات الملفات الأخرى

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="تحويل PDF إلى PNG باستخدام C ++" %}}
لتحويل PDF إلى PNG ، ستحتاج إلى إنشاء عرض تقديمي من ملف PDF وحفظه بتنسيق PNG.

{{% blocks/products/pf/agp/code-block title="كود C ++ لتحويل PDF إلى PNG" offSpacer="true" %}}

```cpp

auto pres = System::MakeObject<Presentation>();
pres->get_Slides()->AddFromPdf(u"InputPDF.pdf");
for (int32_t i = 0; i < pres->get_Slides()->get_Count(); i++)
{
    // Control hidden slides (do not render hidden slides)
    if (pres->get_Slides()->idx_get(i)->get_Hidden())
    {
        continue;
    }
    
    // Convert slide to a Bitmap object
    System::SharedPtr<Bitmap> bmp = pres->get_Slides()->idx_get(i)->GetThumbnail(2.f, 2.f);

    // Create file name for an image
    System::String outputFilePath = Path::Combine(outputDir, System::String(u"Slide_") + i + u".png");
    
    // Save the image in PNG format
    bmp->Save(outputFilePath, ImageFormat::get_Png());
}

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="كيفية تحويل PDF إلى PNG باستخدام Aspose.Slides for C ++ API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="هذه هي خطوات تحويل PDF إلى PNG في C ++." >}}

{{< blocks/products/pf/agp/step-autogen >}}
ثبّت [** Aspose.Slides for C ++ **](https://products.aspose.com/slides/ar/cpp/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
أضف مرجع مكتبة (استيراد المكتبة) إلى مشروع C ++ الخاص بك.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
افتح المصدر PDF ملفات في C ++.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
حفظ النتيجة كملف PNG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="محول مجاني على الإنترنت" sectionDescription="[كيفية تحويل PPT إلى HTML في Python](https://products.aspose.com/slides/ar/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="تحويل PDF إلى التنسيقات المدعومة الأخرى" subTitle="يمكنك أيضًا تحويل PDF وحفظه إلى تنسيقات ملفات أخرى. انظر جميع التنسيقات المدعومة أدناه" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/cpp/conversion/pdf-to-html/" name="PDF TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/cpp/conversion/pdf-to-image/" name="PDF TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/cpp/conversion/pdf-to-jpg/" name="PDF TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/cpp/conversion/pdf-to-tiff/" name="PDF TO TIFF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/cpp/conversion/pdf-to-xml/" name="PDF TO XML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/cpp/conversion/pdf-to-svg/" name="PDF TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/cpp/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/cpp/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}