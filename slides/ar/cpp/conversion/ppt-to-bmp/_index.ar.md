---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: تحويل PPT إلى BMP عبر تطبيق C ++
weight: 7880
url: /ar/cpp/conversion/ppt-to-bmp/ 
description: عينة كود تحويل C ++ لمستند PPT إلى تنسيق BMP. استخدم رمز المثال لتحويل دفعة PPT إلى BMP داخل أي تطبيق C ++.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="تحويل PPT إلى BMP عبر C ++" h2="تحويل PPT إلى BMP عالي الأداء باستخدام مكتبة C ++ دون الحاجة إلى تثبيت Microsoft PowerPoint."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/cpp"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="كيفية تحويل PPT إلى BMP باستخدام C ++" %}}

من أجل تحويل PPT إلى BMP ، سنستخدم
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

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPT إلى رمز مصدر التحويل BMP C ++" >}}
```cs
// Load the PPT
SharedPtr<Presentation> pres = MakeObject<Presentation>(u"sourceFile.ppt");

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

bitmap->Save(u"output.bmp", ImageFormat::get_Bmp());
	
//Iterate through each slide via index and convert

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="خطوات تحويل PPT إلى BMP عبر C ++" intro="يمكن لمطوري C ++ تحويل ملف PPT إلى BMP بسهولة في بضعة أسطر من التعليمات البرمجية." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم بتحميل ملف PPT باستخدام Aspose.Slides لـ C ++ Presentation Object.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}حدد الشريحة الأولى.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}تعيين الأبعاد المطلوبة.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}احصل على الصورة المصغرة بالأبعاد المطلوبة.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}استدعاء أسلوب () حفظ مع معلمة الإخراج BMP.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}افتح ملف BMP في برنامج متوافق.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="متطلبات النظام" intro="قبل تشغيل رمز مثال التحويل C ++ ، تأكد من أن لديك المتطلبات الأساسية التالية." %}}

- Microsoft Windows أو نظام تشغيل متوافق مع C ++ Runtime Environment لأنظمة Windows 32 بت و Windows 64 بت و Linux 64 بت.
- Aspose.Slides لـ C ++ DLL المشار إليها في مشروعك.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension="ppt-to-bmp"
  title="تطبيق مجاني لتحويل PPT إلى BMP"
  description="[جرب تطبيقنا المجاني لتحويل PPT إلى BMP](https://products.aspose.app/slides/conversion/ppt-to-bmp)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="التحويلات المدعومة الأخرى" subTitle="يمكنك أيضًا تحويل PPT إلى العديد من تنسيقات الملفات الأخرى بما في ذلك القليل منها المدرجة أدناه." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/ppt-to-emf/" name="PPT TO EMF" description="تنسيق ملف التعريف المحسن" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/ppt-to-gif/" name="PPT TO GIF" description="تنسيق التبادل الرسومي" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/ppt-to-html/" name="PPT TO HTML" description="لغة ترميز النصوص التشعبية" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/ppt-to-jpeg/" name="PPT TO JPEG" description="صورة JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/ppt-to-odp/" name="PPT TO ODP" description="تنسيق العرض التقديمي OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/ppt-to-otp/" name="PPT TO OTP" description="تنسيق OpenDocument القياسي" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/ppt-to-pdf/" name="PPT TO PDF" description="نموذج المستندات المحمولة" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/ppt-to-png/" name="PPT TO PNG" description="رسومات الشبكة المحمولة" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/ppt-to-pot/" name="PPT TO POT" description="ملفات قوالب Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/ppt-to-potm/" name="PPT TO POTM" description="ملف قالب Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/ppt-to-potx/" name="PPT TO POTX" description="عرض تقديمي لقالب Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/ppt-to-pps/" name="PPT TO PPS" description="عرض شرائح PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/ppt-to-ppsm/" name="PPT TO PPSM" description="عرض شرائح ممكّن بماكرو" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/ppt-to-ppsx/" name="PPT TO PPSX" description="عرض شرائح PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/ppt-to-pptm/" name="PPT TO PPTM" description="ملف العرض التقديمي الممكّن بماكرو" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/ppt-to-pptx/" name="PPT TO PPTX" description="افتح تنسيق عرض XML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/ppt-to-svg/" name="PPT TO SVG" description="الرسومات المتجهات قابلة لل" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/ppt-to-tiff/" name="PPT TO TIFF" description="تنسيق الصورة الموسومة" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/ppt-to-xml/" name="PPT TO XML" description="لغة التوصيف الموسعة" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/cpp/conversion/ppt-to-xps/" name="PPT TO XPS" description="مواصفات ورق XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
