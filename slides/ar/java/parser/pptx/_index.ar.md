---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 1000
title: استخراج النص من مستندات PPTX باستخدام Java
url: /ar/java/parser/pptx/ 
description: استخرج النص من ملفات PPTX في Java باستخدام Aspose.Slides for Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="تحليل ملفات PPTX في Java" h2="استخرج النص ومحتوى العرض التقديمي من مستندات PPTX باستخدام واجهات Aspose.Slides for Java البرمجية على الخادم."
  apiHomeLink="/slides/java/"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/java/"
  learnLink="https://docs.aspose.com/slides/java"
  pricingLink="https://purchase.aspose.com/pricing/slides/java/"
  related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تحليل ملف PPTX باستخدام Java" %}}

استخدم [Aspose.Slides for Java](/slides/ar/java/) لتحليل عروض PPTX التقديمية واستخراج النص من الشرائح. أضف المكتبة إلى مشروع Maven باستخدام إعدادات المستودع والاعتمادية أدناه في ملف `pom.xml`.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="المستودع" >}}
```xml
<repository>
    <id>AsposeJavaAPI</id>
    <name>Aspose Java API</name>
    <url>https://releases.aspose.com/java/repo/</url>
</repository>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="الاعتمادية" >}}
```xml
<dependency>
    <groupId>com.aspose</groupId>
    <artifactId>aspose-slides</artifactId>
    <version>26.8</version>
    <classifier>jdk16</classifier>
</dependency>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="تحليل ملفات PPTX – Java" >}}
```java
Presentation presentation = new Presentation("demo.pptx");
try {
    ISlide slide = presentation.getSlides().get_Item(0);
    ITextFrame[] slideTextFrames = SlideUtil.getAllTextBoxes(slide);

    for (ITextFrame textFrame : slideTextFrames) {
        for (IParagraph paragraph : textFrame.getParagraphs()) {
            for (IPortion portion : paragraph.getPortions()) {
                System.out.print(portion.getText());
                System.out.print(portion.getPortionFormat().getFontHeight());
                System.out.print(portion.getPortionFormat().getLatinFont().getFontName());
            }
        }
    }
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="كيفية تحليل ملفات PPTX في Java" intro="استخرج النص من عرض PPTX تقديمي باستخدام Aspose.Slides for Java ببضعة أسطر من الكود." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}حمّل ملف `PPTX` باستخدام الفئة `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}استدعِ الأسلوب `SlideUtil.getAllTextBoxes` للحصول على إطارات النص من الشريحة الأولى.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}مرّ على كل كائن `ITextFrame` و`IParagraph` و`IPortion`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}اقرأ النص وحجم الخط واسم الخط من كل كائن `IPortion`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="متطلبات النظام" intro="يدعم Aspose.Slides for Java المنصات وأنظمة التشغيل الرئيسية. تأكد من أن بيئتك تستوفي المتطلبات الأساسية التالية." %}}

- Microsoft Windows أو نظام تشغيل متوافق مع Java Runtime Environment لتطبيقات JSP/JSF وتطبيقات سطح المكتب.
- أحدث إصدار من Aspose.Slides for Java من [Maven](https://releases.aspose.com/java/repo/).

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="مبني باستخدام Aspose.Slides" title="استخراج النص والصور عبر الإنترنت" description="تطبيق Aspose.Slides Parser المجاني مبني باستخدام [Aspose.Slides for Java](https://products.aspose.com/slides/ar/java/)، وهي نفس واجهة برمجة التطبيقات المستخدمة في الكود أعلاه. افتحه واكتشف ما يمكن لواجهة برمجة التطبيقات فعله بملفات PPTX الخاصة بك." button="افتح Aspose.Slides Parser" note="[جميع التطبيقات المجانية](https://products.aspose.app/slides/family)" >}}
- يعمل في متصفحك، دون الحاجة إلى تثبيت أي شيء.
- شاهد كيف يقرأ Aspose.Slides ملفاتك قبل كتابة الكود.
- ارفع ملف PPTX واحصل على نصه وصوره.
- نزّل كل شيء في أرشيف ZIP واحد.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPTX" readMoreLink="https://docs.fileformat.com/presentation/pptx/" %}}

Files with the PPTX extension use the Office Open XML presentation format. A PPTX file stores slides that can contain text, images, formatting, animations, and other presentation content.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="تنسيقات أخرى مدعومة للتحليل" subTitle="باستخدام Java يمكنك أيضًا تحليل تنسيقات عروض تقديمية أخرى." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/java/parser/odp/" name="ODP" description="عرض OpenDocument التقديمي" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/java/parser/ppt/" name="PPT" description="عرض PowerPoint 97-2003 التقديمي" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
