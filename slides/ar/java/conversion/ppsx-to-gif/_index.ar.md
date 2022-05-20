---
title: قم بتحويل PPSX إلى GIF عبر Java
weight: 5090
url: /ar/java/conversion/ppsx-to-gif/ 
description: نموذج كود تحويل Java لتنسيق PPSX إلى ملف GIF. استخدم رمز المثال هذا لتصدير عروض PowerPoint & OpenOffice التقديمية إلى GIF داخل أي تطبيق يستند إلى Web أو Desktop Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="قم بتحويل PPSX إلى GIF عبر Java" h2="تحويل PPSX إلى GIF Java لتحويل صفحات مفردة أو متعددة إلى GIF باستخدام مكتبة Java المحلية." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="GIF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PPSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/java" installationsDocsLink="https://docs.aspose.com/slides/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/java" learnAsLink="https://docs.aspose.com/slides/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides" >}}

{{% blocks/products/pf/agp/content h2="كيفية تحويل PPSX إلى GIF باستخدام Java" %}}

 من أجل تحويل PPSX إلى GIF ، سنستخدم
 [Aspose.Slides for Java](https://products.aspose.com/slides/ar/java)
 API وهي واجهة برمجة تطبيقات تحويل غنية بالميزات وقوية وسهلة الاستخدام لمنصة Java. يمكنك تنزيل أحدث إصدار مباشرة من
 [مافن](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides)
 وقم بتثبيته ضمن مشروعك المستند إلى Maven عن طريق إضافة التكوينات التالية إلى ملف pom.xml.

{{% blocks/products/pf/agp/code-block title="مخزن" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="الاعتماد" offSpacer="true" %}}

```cs
<dependency>
<groupId>com.aspose</groupId>
<artifactId>aspose-slides</artifactId>
<version>version of aspose-slides API</version>
<classifier>jdk17</classifier>
</dependency>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="خطوات تحويل PPSX إلى GIF عبر Java" %}}

{{% blocks/products/pf/agp/text %}}

 يمكن لمطوري Java تحويل ملف PPSX إلى GIF بسهولة في بضعة أسطر من التعليمات البرمجية.

{{% /blocks/products/pf/agp/text %}}

1. قم بتحميل ملف PPSX بنسخة من فئة Presentation
1. كرر خلال كل شريحة في العرض التقديمي
1. قم بإنشاء صورة كاملة الحجم كصورة نقطية مع كل تكرار
1. استدعاء طريقة Bitmap.save مع امتداد ملف GIF وتنسيق الصورة

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات النظام" %}}

{{% blocks/products/pf/agp/text %}}

 قبل تشغيل نموذج كود التحويل Java ، تأكد من أن لديك المتطلبات الأساسية التالية.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows أو نظام تشغيل متوافق مع Java Runtime Environment لتطبيق JSP / JSF وتطبيقات سطح المكتب.
- احصل على أحدث إصدار من Aspose.Slides for Java مباشرة من Maven.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="PPSX إلى رمز مصدر تحويل جافا GIF" offSpacer="" %}}

```cs
// load PPSX with Aspose.Slides
Presentation presentation = new Presentation("template.ppsx");
   
    // iterate over all slides in the presentation
for (ISlide sld : presentation.getSlides()) 
{
  
  // create a full scale image of each slide
  BufferedImage bi = sld.getThumbnail(new RenderingOptions());

  // create a new file of type GIF for every slide
  File outputfile = new File(sld.getSlideNumber() + ".gif");
  
  // save the slide image to disk
  ImageIO.write(bi, "gif", outputfile);
}   

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension=""
        sectionTitle="تطبيق مجاني لتحويل PPSX إلى GIF" 
        sectionDescription="[جرب التطبيق لدينا MP4 To MP3](https://products.aspose.app/slides/video/mp4-to-mp3/)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="التحويلات المدعومة الأخرى" subTitle="يمكنك أيضًا تحويل PPSX إلى العديد من تنسيقات الملفات الأخرى بما في ذلك القليل منها المدرجة أدناه." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/conversion/ppsx-to-bmp/" name="PPSX TO BMP" description="سيب" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/conversion/ppsx-to-html/" name="PPSX TO HTML" description="لغة ترميز النصوص التشعبية" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/conversion/ppsx-to-jpeg/" name="PPSX TO JPEG" description="صورة JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/conversion/ppsx-to-odp/" name="PPSX TO ODP" description="تنسيق العرض التقديمي OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/conversion/ppsx-to-otp/" name="PPSX TO OTP" description="تنسيق OpenDocument القياسي" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/conversion/ppsx-to-pdf/" name="PPSX TO PDF" description="نموذج المستندات المحمولة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/conversion/ppsx-to-png/" name="PPSX TO PNG" description="رسومات الشبكة المحمولة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/conversion/ppsx-to-pot/" name="PPSX TO POT" description="ملفات قوالب Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/conversion/ppsx-to-potm/" name="PPSX TO POTM" description="ملف قالب Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/conversion/ppsx-to-potx/" name="PPSX TO POTX" description="عرض تقديمي لقالب Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/conversion/ppsx-to-pps/" name="PPSX TO PPS" description="عرض شرائح PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/conversion/ppsx-to-ppsm/" name="PPSX TO PPSM" description="عرض شرائح ممكّن بماكرو" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/conversion/ppsx-to-ppt/" name="PPSX TO PPT" description="مايكروسوفت باور بوينت 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/conversion/ppsx-to-pptm/" name="PPSX TO PPTM" description="ملف العرض التقديمي الممكّن بماكرو" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/conversion/ppsx-to-pptx/" name="PPSX TO PPTX" description="افتح تنسيق عرض XML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/conversion/ppsx-to-svg/" name="PPSX TO SVG" description="الرسومات المتجهات قابلة لل" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/conversion/ppsx-to-swf/" name="PPSX TO SWF" description="تنسيق SWF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/conversion/ppsx-to-tiff/" name="PPSX TO TIFF" description="تنسيق الصورة الموسومة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/conversion/ppsx-to-xps/" name="PPSX TO XPS" description="مواصفات ورق XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}