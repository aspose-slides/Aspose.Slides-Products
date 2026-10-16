---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: تحويل POTM إلى JPEG عبر Java
weight: 7380
url: /ar/java/conversion/potm-to-jpeg/ 
description: نموذج كود تحويل Java لتنسيق POTM إلى ملف JPEG. استخدم رمز المثال هذا لتصدير عروض PowerPoint & OpenOffice التقديمية إلى JPEG داخل أي تطبيق يستند إلى Web أو Desktop Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="تحويل POTM إلى JPEG عبر Java" h2="تحويل POTM إلى JPEG Java لتحويل صفحة واحدة أو عدة صفحات إلى JPEG باستخدام مكتبة Java المحلية."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/java"
  learnLink="https://docs.aspose.com/slides/java"
  pricingLink="https://purchase.aspose.com/pricing/slides/java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="كيفية تحويل POTM إلى JPEG باستخدام Java" %}}

من أجل تقديم POTM إلى JPEG ، سنستخدم ملفات
 [Aspose.Slides for Java](https://products.aspose.com/slides/ar/java/)
 API وهي واجهة برمجة تطبيقات تحويل غنية بالميزات وقوية وسهلة الاستخدام لمنصة Java. يمكنك تنزيل أحدث إصدار مباشرة من
 [مافن](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides)
 وقم بتثبيته ضمن مشروعك المستند إلى Maven عن طريق إضافة التكوينات التالية إلى ملف pom.xml.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="مخزن" >}}
```xml

<repository>
    <id>AsposeJavaAPI</id>
    <name>Aspose Java API</name>
    <url>https://releases.aspose.com/java/repo/</url>
</repository>

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="الاعتماد" >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/code title="POTM إلى كود مصدر تحويل جافا JPEG" >}}
```cs
// load POTM with Aspose.Slides
Presentation presentation = new Presentation("template.potm");
   
    // iterate over all slides in the presentation
for (ISlide sld : presentation.getSlides()) 
{
  
  // create a full scale image of each slide
  BufferedImage bi = sld.getThumbnail(new RenderingOptions());

  // create a new file of type JPEG for every slide
  File outputfile = new File(sld.getSlideNumber() + ".jpeg");
  
  // save the slide image to disk
  ImageIO.write(bi, "jpeg", outputfile);
}   

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="خطوات تحويل POTM إلى JPEG عبر Java" intro="يمكن لمطوري Java تحويل ملف POTM إلى JPEG بسهولة في بضعة أسطر من التعليمات البرمجية." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم بتحميل ملف POTM بنسخة من فئة Presentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}كرر خلال كل شريحة في العرض التقديمي{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم بإنشاء صورة كاملة الحجم كصورة نقطية مع كل تكرار{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}استدعاء طريقة Bitmap.save مع امتداد ملف JPEG وتنسيق الصورة{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="متطلبات النظام" intro="قبل تشغيل نموذج كود التحويل Java ، تأكد من أن لديك المتطلبات الأساسية التالية." %}}

- Microsoft Windows أو نظام تشغيل متوافق مع Java Runtime Environment لتطبيق JSP / JSF وتطبيقات سطح المكتب.
- احصل على أحدث إصدار من Aspose.Slides for Java مباشرة من Maven.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="تطبيق مجاني لتحويل POTM إلى JPEG"
  description="[جرب تطبيقنا المجاني لتحويل PPT إلى JPG](https://products.aspose.app/slides/conversion/ppt-to-jpg)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="التحويلات المدعومة الأخرى" subTitle="يمكنك أيضًا تحويل POTM إلى العديد من تنسيقات الملفات الأخرى بما في ذلك بعض التنسيقات المدرجة أدناه." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/potm-to-bmp/" name="POTM TO BMP" description="سيب" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/potm-to-gif/" name="POTM TO GIF" description="تنسيق التبادل الرسومي" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/potm-to-html/" name="POTM TO HTML" description="لغة ترميز النصوص التشعبية" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/potm-to-odp/" name="POTM TO ODP" description="تنسيق العرض التقديمي OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/potm-to-otp/" name="POTM TO OTP" description="تنسيق OpenDocument القياسي" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/potm-to-pdf/" name="POTM TO PDF" description="نموذج المستندات المحمولة" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/potm-to-png/" name="POTM TO PNG" description="رسومات الشبكة المحمولة" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/potm-to-pot/" name="POTM TO POT" description="ملفات قوالب Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/potm-to-potx/" name="POTM TO POTX" description="عرض تقديمي لقالب Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/potm-to-pps/" name="POTM TO PPS" description="عرض شرائح PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/potm-to-ppsm/" name="POTM TO PPSM" description="عرض شرائح ممكّن بماكرو" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/potm-to-ppsx/" name="POTM TO PPSX" description="عرض شرائح PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/potm-to-ppt/" name="POTM TO PPT" description="مايكروسوفت باور بوينت 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/potm-to-pptm/" name="POTM TO PPTM" description="ملف العرض التقديمي الممكّن بماكرو" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/potm-to-pptx/" name="POTM TO PPTX" description="افتح تنسيق عرض XML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/potm-to-svg/" name="POTM TO SVG" description="الرسومات المتجهات قابلة لل" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/potm-to-swf/" name="POTM TO SWF" description="تنسيق SWF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/potm-to-tiff/" name="POTM TO TIFF" description="تنسيق الصورة الموسومة" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/potm-to-xps/" name="POTM TO XPS" description="مواصفات ورق XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
