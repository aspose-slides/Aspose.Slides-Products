---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: تحويل PPTX إلى EMF في Python
weight: 2660
url: /ar/python-net/conversion/pptx-to-emf/ 
keywords: "Convert, PowerPoint, PPTX, EMF, Presentation, Python"
description: رمز عينة من PPTX إلى EMF Python التحويل. استخدم PowerPoint Python API لتحويل ملفات PPTX إلى ملفات EMF.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="تحويل PPTX إلى EMF في Python" h2="مكتبة بايثون قوية لتحويل PPTX إلى EMF"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/python-net"
  learnLink="https://docs.aspose.com/slides/python-net/"
  pricingLink="https://purchase.aspose.com/pricing/slides/python-net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تحويل PPTX إلى EMF في Python" %}}

هل تحتاج إلى تحويل ملفات PPTX إلى EMF برمجيًا؟ باستخدام [* Aspose.Slides for Python عبر .NET *](https://products.aspose.com/slides/ar/python-net/) يمكن لأي مطور تحويل PPTX إلى تنسيق EMF ببضعة أسطر فقط من كود Python.

كواجهة برمجة تطبيقات حديثة لمعالجة العروض التقديمية ، تقوم Aspose.Slides for Python بإنشاء EMF من PPTX بسرعة. اختبر جودة تحويل PPTX إلى EMF مباشرة في [المتصفح](https://products.aspose.app/slides/conversion). تسمح لك مكتبة Aspose PowerPoint PPTX بتحويل ملفات PPTX إلى العديد من التنسيقات الشائعة.

يمكنك تثبيت المكتبة من [PyPI](https://pypi.org/project/Aspose.Slides/) باستخدام أمر pip التالي:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="وحدة التحكم / المحطة" >}}
```console
> pip install aspose.slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="احفظ PPTX كـ EMF في Python" %}}

استخدم التطبيق المجاني لمشاهدة عرض توضيحي لعملية تحويل PPTX إلى EMF.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="يوضح نموذج التعليمات البرمجية هذا PPTX إلى EMF Python Conversion" >}}
```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.pptx") as presentation:
    for slide in presentation.slides:
        slide.get_thumbnail(2, 2).save("presentation_slide_{0}.emf".format(str(slide.slide_number)), drawing.imaging.ImageFormat.emf)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="كيفية تحويل PPTX إلى EMF في Python" intro="هذه هي الخطوات لتحويل ملف PPTX إلى EMF باستخدام Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم بتحميل ملف PPTX بنسخة من فئة العرض التقديمي{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم باستدعاء طريقة "save" أثناء تحديد مسار ملف الإخراج & SaveFormat.EMF كمعلمات{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}سيتم حفظ ملف PPTX في المسار المحدد{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="متطلبات النظام" intro="قبل تشغيل رمز مصدر نموذج تحويل Python ، تأكد من توفر المتطلبات الأساسية التالية." %}}

- نظام التشغيل Microsoft Windows أو Linux (راجع [المزيد](https://docs.aspose.com/slides/python-net/system-requirements/)).
- Python 3.5 أو أحدث
- Aspose.Slides for Python المشار إليها في مشروعك.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="تطبيق مجاني لتحويل PPTX إلى EMF"
  description="[جرب التطبيق لدينا Text To Gif](https://products.aspose.app/slides/text-to-gif/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="التحويلات المدعومة الأخرى" subTitle="يمكنك أيضًا تحويل PPTX إلى العديد من تنسيقات الملفات الأخرى. انظر التحويلات الأخرى المدعومة أدناه" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/pptx-to-bmp/" name="PPTX TO BMP" description="سيب" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/pptx-to-fodp/" name="PPTX TO FODP" description="عرض تقديمي XML مسطح OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/pptx-to-gif/" name="PPTX TO GIF" description="تنسيق التبادل الرسومي" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/pptx-to-html/" name="PPTX TO HTML" description="لغة ترميز النصوص التشعبية" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/pptx-to-jpg/" name="PPTX TO JPG" description="صورة JPEG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/pptx-to-odp/" name="PPTX TO ODP" description="تنسيق العرض التقديمي OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/pptx-to-otp/" name="PPTX TO OTP" description="تنسيق OpenDocument القياسي" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/pptx-to-pdf/" name="PPTX TO PDF" description="نموذج المستندات المحمولة" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/pptx-to-png/" name="PPTX TO PNG" description="رسومات الشبكة المحمولة" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/pptx-to-pot/" name="PPTX TO POT" description="ملفات قوالب Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/pptx-to-potm/" name="PPTX TO POTM" description="ملف قالب Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/pptx-to-potx/" name="PPTX TO POTX" description="عرض تقديمي لقالب Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/pptx-to-pps/" name="PPTX TO PPS" description="عرض شرائح PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/pptx-to-ppsm/" name="PPTX TO PPSM" description="عرض شرائح ممكّن بماكرو" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/pptx-to-ppsx/" name="PPTX TO PPSX" description="عرض شرائح PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/pptx-to-ppt/" name="PPTX TO PPT" description="مايكروسوفت باور بوينت 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/pptx-to-pptm/" name="PPTX TO PPTM" description="ملف العرض التقديمي الممكّن بماكرو" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/pptx-to-svg/" name="PPTX TO SVG" description="الرسومات المتجهات قابلة لل" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/pptx-to-swf/" name="PPTX TO SWF" description="تنسيق SWF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/pptx-to-tiff/" name="PPTX TO TIFF" description="تنسيق الصورة الموسومة" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/pptx-to-xps/" name="PPTX TO XPS" description="مواصفات ورق XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
