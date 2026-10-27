---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: تحويل HTML إلى PDF في جافا
url: /ar/java/conversion/html-to-pdf/
keywords: HTML إلى PDF ، تحويل HTML إلى PDF ، واجهة برمجة تطبيقات جافا ، مكتبة جافا ، HTML ، PDF
description: تحويل HTML إلى PDF في جافا. استخدم Java Library API لتحويل ملفات HTML إلى PDF s
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="تحويل HTML إلى PDF في جافا" h2="مكتبة Java عالية السرعة ومتعددة الأنظمة تساعد في تطوير التطبيقات مع القدرة على إنشاء ملفات Microsoft PowerPoint و OpenOffice أو دمجها أو فحصها أو تحويلها دون استخدام أي برنامج مثل Microsoft أو Open Office أو Adobe PDF." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تحويل HTML إلى PDF باستخدام جافا" variant="code" %}}

لتحويل HTML إلى PDF ، ستحتاج إلى إنشاء عرض تقديمي من ملف HTML وحفظه بتنسيق PDF.

{{< blocks/products/pf/slides-design-update-10-2026/code title="كود جافا لتحويل HTML إلى PDF" >}}
```java

Presentation pres = new Presentation();
try {
    pres.getSlides().removeAt(0);
    FileInputStream tr = new FileInputStream("file.html");
    pres.getSlides().addFromHtml(tr);
    pres.save("index.pdf", SaveFormat.Pdf);
} finally {
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تحويل HTML إلى PDF في جافا" %}}

تعد [** Aspose.Slides for Java **](https://products.aspose.com/slides/ar/java/) مكتبة جافا قوية لإنشاء ملفات العروض التقديمية ومعالجتها. علاوة على ذلك ، فإنه يوفر طرقًا مرنة لتحويل HTML إلى PDF. باستخدام ** Aspose.Slides for Java ** ، يمكن لأي مطور أو تطبيق تحويل HTML إلى PDF من الملفات ببضعة سطور من كود جافا.

كواجهة برمجة تطبيقات حديثة لمعالجة المستندات ، تصدر Aspose.Slides for Java ملفات HTML إلى PDF تنسيقات الملفات بسرعة. تسمح لك مكتبة Aspose PowerPoint بتحويل HTML إلى PDF والعديد من تنسيقات الملفات الأخرى

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="كيفية تحويل HTML إلى PDF باستخدام Aspose.Slides for Java API" intro="هذه هي خطوات تحويل HTML إلى PDF في جافا." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم بتثبيت [** Aspose.Slides for Java **](https://products.aspose.com/slides/ar/java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}أضف مرجع مكتبة (استيراد المكتبة) إلى مشروع Java الخاص بك.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}افتح المصدر من ملفات HTML بجافا.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}حفظ النتيجة كملف PDF.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="مبني باستخدام Aspose.Slides" title="تحويل HTML إلى PDF عبر الإنترنت" description="تطبيق Aspose.Slides Conversion المجاني مبني باستخدام [Aspose.Slides for Java](https://products.aspose.com/slides/ar/java/)، وهي نفس واجهة برمجة التطبيقات المستخدمة في الكود أعلاه. افتحه واكتشف ما يمكن لواجهة برمجة التطبيقات فعله بملفات HTML الخاصة بك." button="افتح Aspose.Slides Conversion" note="[جميع التطبيقات المجانية](https://products.aspose.app/slides/family)" upload="أفلت ملفك أو ارفعه" saveAs="حفظ بتنسيق" convert="تحويل" >}}
- يعمل في متصفحك، دون الحاجة إلى تثبيت أي شيء.
- شاهد كيف يحوّل Aspose.Slides الملفات قبل أن تكتب الكود.
- ارفع ملفات HTML واحفظها بتنسيق PDF.
- نزّل النتيجة أو حوّل المزيد من الملفات.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="تحويل HTML إلى التنسيقات المدعومة الأخرى" subTitle="يمكنك أيضًا تحويل HTML وحفظه إلى تنسيقات ملفات أخرى. انظر جميع التنسيقات المدعومة أدناه" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/html-to-image/" name="HTML TO IMAGE" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/html-to-jpg/" name="HTML TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/html-to-png/" name="HTML TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/html-to-tiff/" name="HTML TO TIFF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/html-to-xml/" name="HTML TO XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
