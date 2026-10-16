---
lastmod: 2023-09-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: تحويل PPTM إلى SVG في Node.js
url: /ar/nodejs-java/conversion/pptm-to-svg/
keywords: PPTM إلى SVG، تحويل PPTM إلى SVG، Node.js API، مكتبة Node.js، PPTM، SVG
description: تحويل PPTM إلى SVG في Node.js. استخدم واجهة برمجة تطبيقات مكتبة Node.js لتحويل ملفات PPTM إلى ملفات SVG.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="تحويل PPTM إلى SVG في Node.js" h2="Aspose.Slides for Node.js via Java هي مكتبة قوية وسهلة الاستخدام تسمح لك بتحويل عروض PowerPoint التقديمية إلى تنسيقات مختلفة في Node.js. وهو يدعم جميع عناصر وتنسيقات العرض التقديمي ويوفر واجهة برمجة تطبيقات غنية للوصول إليها وتعديلها. كما يسمح لك بتصدير الشرائح الخاصة بك إلى تنسيقات مختلفة لمزيد من المعالجة أو المشاركة." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تحويل PPTM إلى SVG باستخدام Node.js" variant="code" %}}

لتحويل PPTM إلى SVG، ستحتاج إلى إنشاء عرض تقديمي من ملف PPTM وحفظه باسم SVG.

{{< blocks/products/pf/slides-design-update-10-2026/code title="كود Node.js لتحويل PPTM إلى SVG" >}}
```javascript

var aspose = aspose || {};

aspose.slides = require("aspose.slides.via.java");

var pres = new aspose.slides.Presentation("welcome-to-powerpoint.pptm");
try
{
    var slide = pres.getSlides().get_Item(0);
    var svgStream = java.newInstanceSync("java.io.FileOutputStream", "image.svg");
    slide.writeAsSvg(svgStream);
    svgStream.close();
}
finally
{
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تحويل PPTM إلى SVG في Node.js" %}}

[**Aspose.Slides for Node.js via Java**](https://products.aspose.com/slides/ar/nodejs-java/) هي مكتبة Node.js قوية لإنشاء ملفات العرض التقديمي ومعالجتها. علاوة على ذلك، فإنه يوفر طرقًا مرنة لتحويل PPTM إلى SVG. باستخدام **Aspose.Slides for Node.js عبر Java**، يمكن لأي مطور أو تطبيق تحويل ملفات PPTM إلى SVG باستخدام بضعة أسطر فقط من التعليمات البرمجية.

باعتباره واجهة برمجة تطبيقات حديثة لمعالجة المستندات، يقوم Aspose.Slides for Node.js بتصدير ملفات PPTM إلى تنسيقات ملفات SVG بسرعة. تتيح لك مكتبة Aspose PowerPoint تحويل PPTM إلى SVG والعديد من تنسيقات الملفات الأخرى

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="كيفية تحويل PPTM إلى SVG باستخدام Aspose.Slides for Node.js عبر Java API" intro="لتحويل PPTM إلى SVG باستخدام Aspose.Slides for Node.js عبر Java، تحتاج إلى استيراد الحزمة في ملف JavaScript الخاص بك وإنشاء مثيل لفئة العرض التقديمي. تمثل فئة العرض التقديمي مستند PowerPoint وتوفر طرقًا للوصول إلى عناصره ومعالجتها." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم بتثبيت [**Aspose.Slides for Node.js عبر Java**](https://products.aspose.com/slides/ar/nodejs-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}أضف مرجع مكتبة (قم باستيراد المكتبة) إلى مشروع Node.js الخاص بك.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}افتح ملفات المصدر PPTM في Node.js.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}حفظ النتيجة كملف SVG.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="تحويل PPTM إلى التنسيقات المدعومة الأخرى" subTitle="يمكنك أيضًا تحويل PPTM وحفظه بتنسيقات ملفات أخرى. شاهد جميع التنسيقات المدعومة أدناه" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/nodejs-java/conversion/pptm-to-pptx/" name="PPTM TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/nodejs-java/conversion/pptm-to-ppt/" name="PPTM TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/nodejs-java/conversion/pptm-to-pdf/" name="PPTM TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/nodejs-java/conversion/pptm-to-html/" name="PPTM TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/nodejs-java/conversion/pptm-to-png/" name="PPTM TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/nodejs-java/conversion/pptm-to-bmp/" name="PPTM TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/nodejs-java/conversion/pptm-to-jpg/" name="PPTM TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/nodejs-java/conversion/pptm-to-fodp/" name="PPTM TO FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/nodejs-java/conversion/pptm-to-gif/" name="PPTM TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/nodejs-java/conversion/pptm-to-odp/" name="PPTM TO ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/nodejs-java/conversion/pptm-to-otp/" name="PPTM TO OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/nodejs-java/conversion/pptm-to-pot/" name="PPTM TO POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/nodejs-java/conversion/pptm-to-potm/" name="PPTM TO POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/nodejs-java/conversion/pptm-to-potx/" name="PPTM TO POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/nodejs-java/conversion/pptm-to-pps/" name="PPTM TO PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/nodejs-java/conversion/pptm-to-ppsm/" name="PPTM TO PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/nodejs-java/conversion/pptm-to-ppsx/" name="PPTM TO PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/nodejs-java/conversion/pptm-to-tiff/" name="PPTM TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
