---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: قم بتحويل TIFF إلى PNG عبر تطبيق C ++
weight: 3410
url: /ar/cpp/conversion/tiff-to-png/ 
description: عينة كود تحويل C ++ لمستند TIFF إلى تنسيق PNG. استخدم رمز المثال لتحويل TIFF إلى PNG دفعة ضمن أي تطبيق C ++.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="تحويل TIFF إلى PNG عبر C ++" h2="تحويل TIFF عالي الأداء إلى PNG باستخدام مكتبة C ++ دون الحاجة إلى تثبيت Microsoft PowerPoint."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/cpp"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="كيفية تحويل TIFF إلى PNG باستخدام C ++" %}}

من أجل تحويل TIFF إلى PNG ، سنستخدم ملفات
 [Aspose.Slides for C ++](https://products.aspose.com/slides/ar/cpp/)
 واجهة برمجة التطبيقات API وهي غنية بالميزات وقوية وسهلة الاستخدام للتعامل مع المستندات وتحويلها API لمنصة C ++. يمكنك تنزيل أحدث إصدار مباشرة ، فقط افتح
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 مدير الحزم ، ابحث عن
 Aspose.Slides.CP
 وتثبيت. يمكنك أيضًا استخدام الأمر التالي من Package Manager Console.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="أمر" >}}
```cs

PM> Install-Package Aspose.Slides.Cpp

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="TIFF إلى رمز مصدر تحويل PNG C ++" >}}
```cs
// Load the TIFF
SharedPtr<Presentation> pres = MakeObject<Presentation>(u"sourceFile.tiff");

// Access the first slide
SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// User defined dimension
int desiredX = 1200;
int desiredY = 800;

// Getting scaled value  of X and Y
float ScaleX = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Width()) * desiredX;
float ScaleY = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Height()) * desiredY;

// Create a custom scale image
auto bitmap = slide->GetThumbnail(ScaleX, ScaleY);

bitmap->Save(u"output.png", ImageFormat::get_Png());
	
//Iterate through each slide via index and convert

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="خطوات تحويل TIFF إلى PNG عبر C ++" intro="يمكن لمطوري C ++ تحويل ملف TIFF إلى PNG بسهولة في بضعة أسطر من التعليمات البرمجية." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم بتحميل ملف TIFF باستخدام Aspose.Slides لـ C ++ Presentation Object.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}حدد الشريحة الأولى.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}تعيين الأبعاد المطلوبة.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}احصل على الصورة المصغرة بالأبعاد المطلوبة.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}استدعاء طريقة حفظ () التي تحتوي على معلمة إخراج PNG.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}افتح ملف PNG في برنامج متوافق.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="متطلبات النظام" intro="قبل تشغيل رمز مثال التحويل C ++ ، تأكد من أن لديك المتطلبات الأساسية التالية." %}}

- Microsoft Windows أو نظام تشغيل متوافق مع C ++ Runtime Environment لأنظمة Windows 32 بت و Windows 64 بت و Linux 64 بت.
- Aspose.Slides لـ C ++ DLL المشار إليها في مشروعك.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="تطبيق مجاني لتحويل TIFF إلى PNG"
  description="[جرب التطبيق لدينا Editor](https://products.aspose.app/slides/editor/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="التحويلات المدعومة الأخرى" subTitle="يمكنك أيضًا تحويل TIFF إلى العديد من تنسيقات الملفات الأخرى بما في ذلك القليل منها المدرجة أدناه." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/tiff-to-bmp/" name="TIFF TO BMP" description="سيب" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/tiff-to-emf/" name="TIFF TO EMF" description="تنسيق ملف التعريف المحسن" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/tiff-to-gif/" name="TIFF TO GIF" description="تنسيق التبادل الرسومي" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/tiff-to-html/" name="TIFF TO HTML" description="لغة ترميز النصوص التشعبية" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/tiff-to-jpeg/" name="TIFF TO JPEG" description="صورة JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/tiff-to-odp/" name="TIFF TO ODP" description="تنسيق العرض التقديمي OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/tiff-to-otp/" name="TIFF TO OTP" description="تنسيق OpenDocument القياسي" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/tiff-to-pdf/" name="TIFF TO PDF" description="نموذج المستندات المحمولة" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/tiff-to-pot/" name="TIFF TO POT" description="ملفات قوالب Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/tiff-to-potm/" name="TIFF TO POTM" description="ملف قالب Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/tiff-to-potx/" name="TIFF TO POTX" description="عرض تقديمي لقالب Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/tiff-to-pps/" name="TIFF TO PPS" description="عرض شرائح PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/tiff-to-ppsm/" name="TIFF TO PPSM" description="عرض شرائح ممكّن بماكرو" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/tiff-to-ppsx/" name="TIFF TO PPSX" description="عرض شرائح PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/tiff-to-ppt/" name="TIFF TO PPT" description="مايكروسوفت باور بوينت 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/tiff-to-pptm/" name="TIFF TO PPTM" description="ملف العرض التقديمي الممكّن بماكرو" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/tiff-to-pptx/" name="TIFF TO PPTX" description="افتح تنسيق عرض XML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/tiff-to-svg/" name="TIFF TO SVG" description="الرسومات المتجهات قابلة لل" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/tiff-to-xml/" name="TIFF TO XML" description="لغة التوصيف الموسعة" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/tiff-to-xps/" name="TIFF TO XPS" description="مواصفات ورق XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
