---
title: تحويل PDF إلى JPG في JavaScript
url: /ar/nodejs-net/conversion/pdf-to-jpg/
keywords: PDF إلى JPG، تحويل PDF إلى JPG، Node.js API، مكتبة JavaScript، PDF، JPG
description: تحويل PDF إلى JPG في JavaScript. استخدم واجهة برمجة تطبيقات مكتبة Node.js لتحويل ملفات PDF إلى JPG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="تحويل PDF إلى JPG في JavaScript" h2="Aspose.Slides for Node.js via .NET هي مكتبة قوية وسهلة الاستخدام تسمح لك بتحويل عروض PowerPoint التقديمية إلى تنسيقات مختلفة في JavaScript. وهو يدعم جميع عناصر وتنسيقات العرض التقديمي ويوفر واجهة برمجة تطبيقات غنية للوصول إليها وتعديلها. كما يسمح لك بتصدير الشرائح الخاصة بك إلى تنسيقات مختلفة لمزيد من المعالجة أو المشاركة." >}}

{{% blocks/products/pf/feature-page-section h2="تحويل PDF إلى JPG في Node.js" %}}

[**Aspose.Slides for Node.js via .NET**](https://products.aspose.com/slides/ar/nodejs-net/) هي مكتبة Node.js قوية لإنشاء ملفات العرض التقديمي ومعالجتها. علاوة على ذلك، فإنه يوفر طرقًا مرنة لتحويل PDF إلى JPG. باستخدام **Aspose.Slides for Node.js عبر .NET**، يمكن لأي مطور أو تطبيق تحويل ملفات PDF إلى ملفات JPG باستخدام بضعة أسطر فقط من التعليمات البرمجية.

باعتباره واجهة برمجة تطبيقات حديثة لمعالجة المستندات، يقوم Aspose.Slides for Node.js عبر .NET بتصدير ملفات PDF إلى تنسيقات ملفات JPG بسرعة. تتيح لك مكتبة Aspose PowerPoint تحويل PDF إلى JPG والعديد من تنسيقات الملفات الأخرى

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="تحويل PDF إلى JPG باستخدام JavaScript" %}}
لتحويل PDF إلى JPG، ستحتاج إلى إنشاء عرض تقديمي من ملف PDF وحفظه باسم JPG.

{{% blocks/products/pf/agp/code-block title="كود جافا سكريبت لتحويل PDF إلى JPG" offSpacer="true" %}}

```javascript

const fs = require('fs');
const asposeSlides = require('aspose.slides.via.net');
const { Presentation, SaveFormat, ShapeType } = asposeSlides;

var pres = new Presentation();
try
{
    pres.slides.removeAt(0);
    var slides = pres.slides.addFromPdf("welcome-to-powerpoint.pdf");

    for (let i = 0; i < pres.slides.length; i++) {
        var slide = pres.slides.get(i);
        var image = slide.getThumbnail(new asposeSlides.RenderingOptions(), { width: 1080, height: 960 });

        image.save("slide" + i + ".jpg", ImageFormat.Jpeg); 
    }
}
finally
{
    if (pres != null) pres.dispose();
} 

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="كيفية تحويل PDF إلى JPG باستخدام Aspose.Slides لـ Node.js عبر .NET API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="لتحويل PDF إلى JPG باستخدام Aspose.Slides لـ Node.js عبر .NET، تحتاج إلى استيراد الحزمة في ملف JavaScript الخاص بك وإنشاء مثيل لفئة العرض التقديمي. تمثل فئة العرض التقديمي مستند PowerPoint وتوفر طرقًا للوصول إلى عناصره ومعالجتها." >}}

{{< blocks/products/pf/agp/step-autogen >}}
قم بتثبيت [**Aspose.Slides for Node.js عبر .NET**](https://products.aspose.com/slides/ar/nodejs-net/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
أضف مرجع مكتبة (قم باستيراد المكتبة) إلى مشروع Node.js الخاص بك.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
افتح ملفات المصدر PDF في Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
حفظ النتيجة كملف JPG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="تحويل PDF إلى التنسيقات المدعومة الأخرى" subTitle="يمكنك أيضًا تحويل PDF وحفظه بتنسيقات ملفات أخرى. شاهد جميع التنسيقات المدعومة أدناه" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/nodejs-net/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/nodejs-net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/nodejs-net/conversion/pdf-to-html/" name="PDF TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/nodejs-net/conversion/pdf-to-png/" name="PDF TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/nodejs-net/conversion/pdf-to-bmp/" name="PDF TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/nodejs-net/conversion/pdf-to-fodp/" name="PDF TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/nodejs-net/conversion/pdf-to-gif/" name="PDF TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/nodejs-net/conversion/pdf-to-odp/" name="PDF TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/nodejs-net/conversion/pdf-to-otp/" name="PDF TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/nodejs-net/conversion/pdf-to-pot/" name="PDF TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/nodejs-net/conversion/pdf-to-potm/" name="PDF TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/nodejs-net/conversion/pdf-to-potx/" name="PDF TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/nodejs-net/conversion/pdf-to-pps/" name="PDF TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/nodejs-net/conversion/pdf-to-ppsm/" name="PDF TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/nodejs-net/conversion/pdf-to-ppsx/" name="PDF TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/nodejs-net/conversion/pdf-to-pptm/" name="PDF TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/nodejs-net/conversion/pdf-to-svg/" name="PDF TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/nodejs-net/conversion/pdf-to-tiff/" name="PDF TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}