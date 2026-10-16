---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: تحويل POTX إلى EMF في Python
weight: 1340
url: /ar/python-net/conversion/potx-to-emf/ 
keywords: "Convert, PowerPoint, POTX, EMF, Presentation, Python"
description: رمز عينة لتحويل POTX إلى EMF Python. استخدم PowerPoint Python API لتحويل ملفات POTX إلى ملفات EMF.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="تحويل POTX إلى EMF في Python" h2="مكتبة بايثون قوية لتحويل POTX إلى EMF"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/python-net"
  learnLink="https://docs.aspose.com/slides/python-net/"
  pricingLink="https://purchase.aspose.com/pricing/slides/python-net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تحويل POTX إلى EMF في Python" %}}

هل تحتاج إلى تحويل ملفات POTX إلى EMF برمجيًا؟ باستخدام [* Aspose.Slides for Python عبر .NET *](https://products.aspose.com/slides/ar/python-net/) يمكن لأي مطور تحويل POTX إلى تنسيق EMF ببضعة أسطر فقط من كود Python.

كواجهة برمجة تطبيقات حديثة لمعالجة العروض التقديمية ، تقوم Aspose.Slides for Python بإنشاء EMF من POTX بسرعة. اختبر جودة تحويل POTX إلى EMF مباشرةً في [المتصفح](https://products.aspose.app/slides/conversion). تسمح لك مكتبة Aspose PowerPoint PPTX بتحويل ملفات POTX إلى العديد من التنسيقات الشائعة.

يمكنك تثبيت المكتبة من [PyPI](https://pypi.org/project/Aspose.Slides/) باستخدام أمر pip التالي:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="وحدة التحكم / المحطة" >}}
```console
> pip install aspose.slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="احفظ POTX كـ EMF في Python" %}}

استخدم التطبيق المجاني لمشاهدة عرض توضيحي لعملية تحويل POTX إلى EMF.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="يوضح نموذج التعليمات البرمجية هذا POTX إلى EMF Python Conversion" >}}
```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.potx") as presentation:
    for slide in presentation.slides:
        slide.get_thumbnail(2, 2).save("presentation_slide_{0}.emf".format(str(slide.slide_number)), drawing.imaging.ImageFormat.emf)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="كيفية تحويل POTX إلى EMF في Python" intro="هذه هي خطوات تحويل ملف POTX إلى EMF باستخدام Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم بتحميل ملف POTX بنسخة من فئة العرض التقديمي{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم باستدعاء طريقة "save" أثناء تحديد مسار ملف الإخراج & SaveFormat.EMF كمعلمات{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}سيتم حفظ ملف POTX في المسار المحدد{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="متطلبات النظام" intro="قبل تشغيل رمز مصدر نموذج تحويل Python ، تأكد من توفر المتطلبات الأساسية التالية." %}}

- نظام التشغيل Microsoft Windows أو Linux (راجع [المزيد](https://docs.aspose.com/slides/python-net/system-requirements/)).
- Python 3.5 أو أحدث
- Aspose.Slides for Python المشار إليها في مشروعك.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="تطبيق مجاني لتحويل POTX إلى EMF"
  description="[جرب التطبيق لدينا Editor](https://products.aspose.app/slides/editor/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="التحويلات المدعومة الأخرى" subTitle="يمكنك أيضًا تحويل POTX إلى العديد من تنسيقات الملفات الأخرى. انظر التحويلات الأخرى المدعومة أدناه" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/potx-to-bmp/" name="POTX TO BMP" description="سيب" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/potx-to-fodp/" name="POTX TO FODP" description="عرض تقديمي XML مسطح OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/potx-to-gif/" name="POTX TO GIF" description="تنسيق التبادل الرسومي" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/potx-to-html/" name="POTX TO HTML" description="لغة ترميز النصوص التشعبية" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/potx-to-jpg/" name="POTX TO JPG" description="صورة JPEG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/potx-to-odp/" name="POTX TO ODP" description="تنسيق العرض التقديمي OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/potx-to-otp/" name="POTX TO OTP" description="تنسيق OpenDocument القياسي" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/potx-to-pdf/" name="POTX TO PDF" description="نموذج المستندات المحمولة" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/potx-to-png/" name="POTX TO PNG" description="رسومات الشبكة المحمولة" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/potx-to-pot/" name="POTX TO POT" description="ملفات قوالب Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/potx-to-potm/" name="POTX TO POTM" description="ملف قالب Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/potx-to-pps/" name="POTX TO PPS" description="عرض شرائح PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/potx-to-ppsm/" name="POTX TO PPSM" description="عرض شرائح ممكّن بماكرو" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/potx-to-ppsx/" name="POTX TO PPSX" description="عرض شرائح PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/potx-to-ppt/" name="POTX TO PPT" description="مايكروسوفت باور بوينت 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/potx-to-pptm/" name="POTX TO PPTM" description="ملف العرض التقديمي الممكّن بماكرو" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/potx-to-pptx/" name="POTX TO PPTX" description="افتح تنسيق عرض XML" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/potx-to-svg/" name="POTX TO SVG" description="الرسومات المتجهات قابلة لل" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/potx-to-swf/" name="POTX TO SWF" description="تنسيق SWF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/potx-to-tiff/" name="POTX TO TIFF" description="تنسيق الصورة الموسومة" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/potx-to-xps/" name="POTX TO XPS" description="مواصفات ورق XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
