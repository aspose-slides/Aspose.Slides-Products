---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: تحويل POTX إلى ODP عبر Java
weight: 2840
url: /ar/java/conversion/potx-to-odp/ 
description: نموذج كود تحويل Java لتنسيق POTX إلى ملف ODP. استخدم رمز المثال هذا لتصدير عروض PowerPoint & OpenOffice التقديمية إلى ODP داخل أي تطبيق يستند إلى Web أو Desktop Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="تحويل POTX إلى ODP عبر Java" h2="تحويل POTX إلى ODP Java لتحويل صفحات مفردة أو متعددة إلى ODP باستخدام مكتبة Java المحلية."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/java"
  learnLink="https://docs.aspose.com/slides/java"
  pricingLink="https://purchase.aspose.com/pricing/slides/java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="كيفية تحويل POTX إلى ODP باستخدام Java" %}}

من أجل تقديم POTX إلى ODP ، سنستخدم
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

{{< blocks/products/pf/slides-design-update-10-2026/code title="POTX إلى كود مصدر تحويل جافا ODP" >}}
```cs
// instantiate a Presentation object that represents a POTX file
Presentation presentation = new Presentation("template.potx");
// save the presentation as ODP
presentation.save("output.odp", SaveFormat.Odp);   

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="خطوات تحويل POTX إلى ODP عبر Java" intro="يمكن لمطوري Java تحويل ملف POTX بسهولة إلى ODP في بضعة أسطر من التعليمات البرمجية." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم بتحميل ملف POTX بنسخة من فئة Presentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}استدعاء طريقة Presentation.save أثناء تحديد مسار ملف الإخراج & SaveFormat{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}سيتم حفظ ملف ODP في المسار المحدد{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="متطلبات النظام" intro="قبل تشغيل نموذج كود التحويل Java ، تأكد من أن لديك المتطلبات الأساسية التالية." %}}

- Microsoft Windows أو نظام تشغيل متوافق مع Java Runtime Environment لتطبيق JSP / JSF وتطبيقات سطح المكتب.
- احصل على أحدث إصدار من Aspose.Slides for Java مباشرة من Maven.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="مبني باستخدام Aspose.Slides" title="تحويل POTX إلى ODP عبر الإنترنت" description="تطبيق Aspose.Slides Conversion المجاني مبني باستخدام [Aspose.Slides for Java](https://products.aspose.com/slides/ar/java/)، وهي نفس واجهة برمجة التطبيقات المستخدمة في الكود أعلاه. افتحه واكتشف ما يمكن لواجهة برمجة التطبيقات فعله بملفات POTX الخاصة بك." button="افتح Aspose.Slides Conversion" note="[جميع التطبيقات المجانية](https://products.aspose.app/slides/family)" upload="أفلت ملفك أو ارفعه" saveAs="حفظ بتنسيق" convert="تحويل" >}}
- يعمل في متصفحك، دون الحاجة إلى تثبيت أي شيء.
- شاهد كيف يحوّل Aspose.Slides الملفات قبل أن تكتب الكود.
- ارفع ملفات POTX واحفظها بتنسيق ODP.
- نزّل النتيجة أو حوّل المزيد من الملفات.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="التحويلات المدعومة الأخرى" subTitle="يمكنك أيضًا تحويل POTX إلى العديد من تنسيقات الملفات الأخرى بما في ذلك القليل منها المدرجة أدناه." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/potx-to-bmp/" name="POTX TO BMP" description="سيب" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/potx-to-gif/" name="POTX TO GIF" description="تنسيق التبادل الرسومي" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/potx-to-html/" name="POTX TO HTML" description="لغة ترميز النصوص التشعبية" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/potx-to-jpeg/" name="POTX TO JPEG" description="صورة JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/potx-to-otp/" name="POTX TO OTP" description="تنسيق OpenDocument القياسي" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/potx-to-pdf/" name="POTX TO PDF" description="نموذج المستندات المحمولة" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/potx-to-png/" name="POTX TO PNG" description="رسومات الشبكة المحمولة" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/potx-to-pot/" name="POTX TO POT" description="ملفات قوالب Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/potx-to-potm/" name="POTX TO POTM" description="ملف قالب Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/potx-to-pps/" name="POTX TO PPS" description="عرض شرائح PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/potx-to-ppsm/" name="POTX TO PPSM" description="عرض شرائح ممكّن بماكرو" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/potx-to-ppsx/" name="POTX TO PPSX" description="عرض شرائح PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/potx-to-ppt/" name="POTX TO PPT" description="مايكروسوفت باور بوينت 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/potx-to-pptm/" name="POTX TO PPTM" description="ملف العرض التقديمي الممكّن بماكرو" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/potx-to-pptx/" name="POTX TO PPTX" description="افتح تنسيق عرض XML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/potx-to-svg/" name="POTX TO SVG" description="الرسومات المتجهات قابلة لل" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/potx-to-swf/" name="POTX TO SWF" description="تنسيق SWF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/potx-to-tiff/" name="POTX TO TIFF" description="تنسيق الصورة الموسومة" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/potx-to-xps/" name="POTX TO XPS" description="مواصفات ورق XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
