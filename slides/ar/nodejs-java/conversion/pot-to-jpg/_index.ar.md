---
lastmod: 2023-09-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: تحويل POT إلى JPG في Node.js
url: /ar/nodejs-java/conversion/pot-to-jpg/
keywords: POT إلى JPG، تحويل POT إلى JPG، Node.js API، مكتبة Node.js، POT، JPG
description: تحويل POT إلى JPG في Node.js. استخدم واجهة برمجة تطبيقات مكتبة Node.js لتحويل ملفات POT إلى ملفات JPG.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="تحويل POT إلى JPG في Node.js" h2="Aspose.Slides for Node.js via Java هي مكتبة قوية وسهلة الاستخدام تسمح لك بتحويل عروض PowerPoint التقديمية إلى تنسيقات مختلفة في Node.js. وهو يدعم جميع عناصر وتنسيقات العرض التقديمي ويوفر واجهة برمجة تطبيقات غنية للوصول إليها وتعديلها. كما يسمح لك بتصدير الشرائح الخاصة بك إلى تنسيقات مختلفة لمزيد من المعالجة أو المشاركة." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تحويل POT إلى JPG باستخدام Node.js" variant="code" %}}

لتحويل POT إلى JPG، ستحتاج إلى إنشاء عرض تقديمي من ملف POT وحفظه باسم JPG.

{{< blocks/products/pf/slides-design-update-10-2026/code title="كود Node.js لتحويل POT إلى JPG" >}}
```javascript

var aspose = aspose || {};

aspose.slides = require("aspose.slides.via.java");

var pres = new aspose.slides.Presentation("welcome-to-powerpoint.pot");
try
{
    for(var i = 0; i < pres.getSlides().size(); i++)
    {
        var sld = pres.getSlides().get_Item(i);
        var bi = sld.getThumbnail(2, 2);
        var outputfile = java.newInstanceSync("java.io.File", "slide_" + sld.getSlideNumber() + ".jpg");
        java.callStaticMethod("javax.imageio.ImageIO", "write", bi, "jpeg", outputfile);
    }
}
finally
{
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تحويل POT إلى JPG في Node.js" %}}

[**Aspose.Slides for Node.js via Java**](https://products.aspose.com/slides/ar/nodejs-java/) هي مكتبة Node.js قوية لإنشاء ملفات العرض التقديمي ومعالجتها. علاوة على ذلك، فإنه يوفر طرقًا مرنة لتحويل POT إلى JPG. باستخدام **Aspose.Slides for Node.js عبر Java**، يمكن لأي مطور أو تطبيق تحويل ملفات POT إلى JPG باستخدام بضعة أسطر فقط من التعليمات البرمجية.

باعتباره واجهة برمجة تطبيقات حديثة لمعالجة المستندات، يقوم Aspose.Slides for Node.js بتصدير ملفات POT إلى تنسيقات ملفات JPG بسرعة. تتيح لك مكتبة Aspose PowerPoint تحويل POT إلى JPG والعديد من تنسيقات الملفات الأخرى

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="كيفية تحويل POT إلى JPG باستخدام Aspose.Slides for Node.js عبر Java API" intro="لتحويل POT إلى JPG باستخدام Aspose.Slides for Node.js عبر Java، تحتاج إلى استيراد الحزمة في ملف JavaScript الخاص بك وإنشاء مثيل لفئة العرض التقديمي. تمثل فئة العرض التقديمي مستند PowerPoint وتوفر طرقًا للوصول إلى عناصره ومعالجتها." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم بتثبيت [**Aspose.Slides for Node.js عبر Java**](https://products.aspose.com/slides/ar/nodejs-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}أضف مرجع مكتبة (قم باستيراد المكتبة) إلى مشروع Node.js الخاص بك.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}افتح ملفات المصدر POT في Node.js.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}حفظ النتيجة كملف JPG.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="تحويل POT إلى التنسيقات المدعومة الأخرى" subTitle="يمكنك أيضًا تحويل POT وحفظه بتنسيقات ملفات أخرى. شاهد جميع التنسيقات المدعومة أدناه" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/nodejs-java/conversion/pot-to-pptx/" name="POT TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/nodejs-java/conversion/pot-to-ppt/" name="POT TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/nodejs-java/conversion/pot-to-pdf/" name="POT TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/nodejs-java/conversion/pot-to-html/" name="POT TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/nodejs-java/conversion/pot-to-png/" name="POT TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/nodejs-java/conversion/pot-to-bmp/" name="POT TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/nodejs-java/conversion/pot-to-fodp/" name="POT TO FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/nodejs-java/conversion/pot-to-gif/" name="POT TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/nodejs-java/conversion/pot-to-odp/" name="POT TO ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/nodejs-java/conversion/pot-to-otp/" name="POT TO OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/nodejs-java/conversion/pot-to-potm/" name="POT TO POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/nodejs-java/conversion/pot-to-potx/" name="POT TO POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/nodejs-java/conversion/pot-to-pps/" name="POT TO PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/nodejs-java/conversion/pot-to-ppsm/" name="POT TO PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/nodejs-java/conversion/pot-to-ppsx/" name="POT TO PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/nodejs-java/conversion/pot-to-pptm/" name="POT TO PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/nodejs-java/conversion/pot-to-svg/" name="POT TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/nodejs-java/conversion/pot-to-tiff/" name="POT TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
