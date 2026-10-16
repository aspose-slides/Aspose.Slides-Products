---
lastmod: 2024-04-10
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: تحويل POT إلى PPT في JavaScript
url: /ar/nodejs-net/conversion/pot-to-ppt/
keywords: POT إلى PPT، تحويل POT إلى PPT، Node.js API، مكتبة JavaScript، POT، PPT
description: تحويل POT إلى PPT في JavaScript. استخدم واجهة برمجة تطبيقات مكتبة Node.js لتحويل ملفات POT إلى PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="تحويل POT إلى PPT في JavaScript" h2="Aspose.Slides for Node.js via .NET هي مكتبة قوية وسهلة الاستخدام تسمح لك بتحويل عروض PowerPoint التقديمية إلى تنسيقات مختلفة في JavaScript. وهو يدعم جميع عناصر وتنسيقات العرض التقديمي ويوفر واجهة برمجة تطبيقات غنية للوصول إليها وتعديلها. كما يسمح لك بتصدير الشرائح الخاصة بك إلى تنسيقات مختلفة لمزيد من المعالجة أو المشاركة." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تحويل POT إلى PPT باستخدام JavaScript" variant="code" %}}

لتحويل POT إلى PPT، ستحتاج إلى إنشاء عرض تقديمي من ملف POT وحفظه باسم PPT.

{{< blocks/products/pf/slides-design-update-10-2026/code title="كود جافا سكريبت لتحويل POT إلى PPT" >}}
```javascript

const fs = require('fs');
const asposeSlides = require('aspose.slides.via.net');
const { Presentation, SaveFormat } = asposeSlides;
var pres = new Presentation("welcome-to-powerpoint.pot");
try
{
    pres.save("output.ppt", SaveFormat.Ppt);
}
finally
{
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تحويل POT إلى PPT في Node.js" %}}

[**Aspose.Slides for Node.js via .NET**](https://products.aspose.com/slides/ar/nodejs-net/) هي مكتبة Node.js قوية لإنشاء ملفات العرض التقديمي ومعالجتها. علاوة على ذلك، فإنه يوفر طرقًا مرنة لتحويل POT إلى PPT. باستخدام **Aspose.Slides for Node.js عبر .NET**، يمكن لأي مطور أو تطبيق تحويل ملفات POT إلى ملفات PPT باستخدام بضعة أسطر فقط من التعليمات البرمجية.

باعتباره واجهة برمجة تطبيقات حديثة لمعالجة المستندات، يقوم Aspose.Slides for Node.js عبر .NET بتصدير ملفات POT إلى تنسيقات ملفات PPT بسرعة. تتيح لك مكتبة Aspose PowerPoint تحويل POT إلى PPT والعديد من تنسيقات الملفات الأخرى

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="كيفية تحويل POT إلى PPT باستخدام Aspose.Slides لـ Node.js عبر .NET API" intro="لتحويل POT إلى PPT باستخدام Aspose.Slides لـ Node.js عبر .NET، تحتاج إلى استيراد الحزمة في ملف JavaScript الخاص بك وإنشاء مثيل لفئة العرض التقديمي. تمثل فئة العرض التقديمي مستند PowerPoint وتوفر طرقًا للوصول إلى عناصره ومعالجتها." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم بتثبيت [**Aspose.Slides for Node.js عبر .NET**](https://products.aspose.com/slides/ar/nodejs-net/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}أضف مرجع مكتبة (قم باستيراد المكتبة) إلى مشروع Node.js الخاص بك.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}افتح ملفات المصدر POT في Node.js.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}حفظ النتيجة كملف PPT.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="تحويل POT إلى التنسيقات المدعومة الأخرى" subTitle="يمكنك أيضًا تحويل POT وحفظه بتنسيقات ملفات أخرى. شاهد جميع التنسيقات المدعومة أدناه" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/nodejs-net/conversion/pot-to-pptx/" name="POT TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/nodejs-net/conversion/pot-to-pdf/" name="POT TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/nodejs-net/conversion/pot-to-html/" name="POT TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/nodejs-net/conversion/pot-to-png/" name="POT TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/nodejs-net/conversion/pot-to-bmp/" name="POT TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/nodejs-net/conversion/pot-to-jpg/" name="POT TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/nodejs-net/conversion/pot-to-fodp/" name="POT TO FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/nodejs-net/conversion/pot-to-gif/" name="POT TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/nodejs-net/conversion/pot-to-odp/" name="POT TO ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/nodejs-net/conversion/pot-to-otp/" name="POT TO OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/nodejs-net/conversion/pot-to-potm/" name="POT TO POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/nodejs-net/conversion/pot-to-potx/" name="POT TO POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/nodejs-net/conversion/pot-to-pps/" name="POT TO PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/nodejs-net/conversion/pot-to-ppsm/" name="POT TO PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/nodejs-net/conversion/pot-to-ppsx/" name="POT TO PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/nodejs-net/conversion/pot-to-pptm/" name="POT TO PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/nodejs-net/conversion/pot-to-svg/" name="POT TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/nodejs-net/conversion/pot-to-tiff/" name="POT TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
