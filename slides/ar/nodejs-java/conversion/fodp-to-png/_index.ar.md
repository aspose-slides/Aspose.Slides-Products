---
title: تحويل FODP إلى PNG في Node.js
url: /ar/nodejs-java/conversion/fodp-to-png/
keywords: FODP إلى PNG، تحويل FODP إلى PNG، Node.js API، مكتبة Node.js، FODP، PNG
description: تحويل FODP إلى PNG في Node.js. استخدم واجهة برمجة تطبيقات مكتبة Node.js لتحويل ملفات FODP إلى ملفات PNG.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="تحويل FODP إلى PNG في Node.js" h2="Aspose.Slides for Node.js via Java هي مكتبة قوية وسهلة الاستخدام تسمح لك بتحويل عروض PowerPoint التقديمية إلى تنسيقات مختلفة في Node.js. وهو يدعم جميع عناصر وتنسيقات العرض التقديمي ويوفر واجهة برمجة تطبيقات غنية للوصول إليها وتعديلها. كما يسمح لك بتصدير الشرائح الخاصة بك إلى تنسيقات مختلفة لمزيد من المعالجة أو المشاركة." >}}

{{% blocks/products/pf/feature-page-section h2="تحويل FODP إلى PNG في Node.js" %}}

[**Aspose.Slides for Node.js via Java**](https://products.aspose.com/slides/ar/nodejs-java/) هي مكتبة Node.js قوية لإنشاء ملفات العرض التقديمي ومعالجتها. علاوة على ذلك، فإنه يوفر طرقًا مرنة لتحويل FODP إلى PNG. باستخدام **Aspose.Slides for Node.js عبر Java**، يمكن لأي مطور أو تطبيق تحويل ملفات FODP إلى PNG باستخدام بضعة أسطر فقط من التعليمات البرمجية.

باعتباره واجهة برمجة تطبيقات حديثة لمعالجة المستندات، يقوم Aspose.Slides for Node.js بتصدير ملفات FODP إلى تنسيقات ملفات PNG بسرعة. تتيح لك مكتبة Aspose PowerPoint تحويل FODP إلى PNG والعديد من تنسيقات الملفات الأخرى

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="تحويل FODP إلى PNG باستخدام Node.js" %}}
لتحويل FODP إلى PNG، ستحتاج إلى إنشاء عرض تقديمي من ملف FODP وحفظه باسم PNG.

{{% blocks/products/pf/agp/code-block title="كود Node.js لتحويل FODP إلى PNG" offSpacer="true" %}}

```javascript

var aspose = aspose || {};

aspose.slides = require("aspose.slides.via.java");

var pres = new aspose.slides.Presentation("welcome-to-powerpoint.fodp");
try
{
    for(var i = 0; i < pres.getSlides().size(); i++)
    {
        var sld = pres.getSlides().get_Item(i);
        var bi = sld.getThumbnail(2, 2);
        var outputfile = java.newInstanceSync("java.io.File", "slide_" + sld.getSlideNumber() + ".png");
        java.callStaticMethod("javax.imageio.ImageIO", "write", bi, "png", outputfile);
    }
}
finally
{
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="كيفية تحويل FODP إلى PNG باستخدام Aspose.Slides for Node.js عبر Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="لتحويل FODP إلى PNG باستخدام Aspose.Slides for Node.js عبر Java، تحتاج إلى استيراد الحزمة في ملف JavaScript الخاص بك وإنشاء مثيل لفئة العرض التقديمي. تمثل فئة العرض التقديمي مستند PowerPoint وتوفر طرقًا للوصول إلى عناصره ومعالجتها." >}}

{{< blocks/products/pf/agp/step-autogen >}}
قم بتثبيت [**Aspose.Slides for Node.js عبر Java**](https://products.aspose.com/slides/ar/nodejs-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
أضف مرجع مكتبة (قم باستيراد المكتبة) إلى مشروع Node.js الخاص بك.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
افتح ملفات المصدر FODP في Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
حفظ النتيجة كملف PNG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="تحويل FODP إلى التنسيقات المدعومة الأخرى" subTitle="يمكنك أيضًا تحويل FODP وحفظه بتنسيقات ملفات أخرى. شاهد جميع التنسيقات المدعومة أدناه" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/nodejs-java/conversion/fodp-to-pptx/" name="FODP TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/nodejs-java/conversion/fodp-to-ppt/" name="FODP TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/nodejs-java/conversion/fodp-to-pdf/" name="FODP TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/nodejs-java/conversion/fodp-to-html/" name="FODP TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/nodejs-java/conversion/fodp-to-bmp/" name="FODP TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/nodejs-java/conversion/fodp-to-jpg/" name="FODP TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/nodejs-java/conversion/fodp-to-gif/" name="FODP TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/nodejs-java/conversion/fodp-to-odp/" name="FODP TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/nodejs-java/conversion/fodp-to-otp/" name="FODP TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/nodejs-java/conversion/fodp-to-pot/" name="FODP TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/nodejs-java/conversion/fodp-to-potm/" name="FODP TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/nodejs-java/conversion/fodp-to-potx/" name="FODP TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/nodejs-java/conversion/fodp-to-pps/" name="FODP TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/nodejs-java/conversion/fodp-to-ppsm/" name="FODP TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/nodejs-java/conversion/fodp-to-ppsx/" name="FODP TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/nodejs-java/conversion/fodp-to-pptm/" name="FODP TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/nodejs-java/conversion/fodp-to-svg/" name="FODP TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/nodejs-java/conversion/fodp-to-tiff/" name="FODP TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}