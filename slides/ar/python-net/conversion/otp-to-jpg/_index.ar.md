---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: تحويل OTP إلى JPG في Python
weight: 500
url: /ar/python-net/conversion/otp-to-jpg/ 
keywords: "Convert, PowerPoint, OTP, JPG, Presentation, Python"
description: رمز عينة لتحويل OTP إلى JPG Python. استخدم PowerPoint Python API لتحويل ملفات OTP إلى ملفات JPG.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="تحويل OTP إلى JPG في Python" h2="مكتبة بايثون قوية لتحويل OTP إلى JPG"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/python-net"
  learnLink="https://docs.aspose.com/slides/python-net/"
  pricingLink="https://purchase.aspose.com/pricing/slides/python-net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تحويل OTP إلى JPG في Python" %}}

هل تحتاج إلى تحويل ملفات OTP إلى JPG برمجيًا؟ باستخدام [* Aspose.Slides for Python عبر .NET *](https://products.aspose.com/slides/ar/python-net/) يمكن لأي مطور تحويل OTP إلى تنسيق JPG ببضعة أسطر فقط من كود Python.

باعتبارها واجهة برمجة تطبيقات حديثة لمعالجة العروض التقديمية ، تقوم Aspose.Slides for Python بإنشاء JPG من OTP بسرعة. اختبر جودة تحويل OTP إلى JPG مباشرة في [المتصفح](https://products.aspose.app/slides/conversion/ppt-to-jpg). تسمح لك مكتبة Aspose PowerPoint PPTX بتحويل ملفات OTP إلى العديد من التنسيقات الشائعة.

يمكنك تثبيت المكتبة من [PyPI](https://pypi.org/project/Aspose.Slides/) باستخدام أمر pip التالي:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="وحدة التحكم / المحطة" >}}
```console
> pip install aspose.slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="احفظ OTP بصيغة JPG في Python" %}}

استخدم التطبيق المجاني لمشاهدة عرض توضيحي لعملية تحويل OTP إلى JPG.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="يوضح نموذج الكود هذا تحويل OTP إلى JPG Python" >}}
```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.otp") as presentation:
    for slide in presentation.slides:
        slide.get_thumbnail(2, 2).save("presentation_slide_{0}.jpg".format(str(slide.slide_number)), drawing.imaging.ImageFormat.jpeg)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="كيفية تحويل OTP إلى JPG في Python" intro="هذه هي خطوات تحويل ملف OTP إلى JPG باستخدام Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم بتحميل ملف OTP بنسخة من فئة Presentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم باستدعاء طريقة "save" أثناء تحديد مسار ملف الإخراج & SaveFormat.JPG كمعلمات{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}سيتم حفظ ملف OTP في المسار المحدد{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="متطلبات النظام" intro="قبل تشغيل رمز مصدر نموذج تحويل Python ، تأكد من توفر المتطلبات الأساسية التالية." %}}

- نظام التشغيل Microsoft Windows أو Linux (راجع [المزيد](https://docs.aspose.com/slides/python-net/system-requirements/)).
- Python 3.5 أو أحدث
- Aspose.Slides for Python المشار إليها في مشروعك.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="تطبيق مجاني لتحويل OTP إلى JPG"
  description="[جرب تطبيقنا المجاني لتحويل PPT إلى JPG](https://products.aspose.app/slides/conversion/ppt-to-jpg)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="التحويلات المدعومة الأخرى" subTitle="يمكنك أيضًا تحويل OTP إلى العديد من تنسيقات الملفات الأخرى. انظر التحويلات الأخرى المدعومة أدناه" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/otp-to-bmp/" name="OTP TO BMP" description="سيب" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/otp-to-emf/" name="OTP TO EMF" description="تنسيق ملف التعريف المحسن" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/otp-to-fodp/" name="OTP TO FODP" description="عرض تقديمي XML مسطح OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/otp-to-gif/" name="OTP TO GIF" description="تنسيق التبادل الرسومي" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/otp-to-html/" name="OTP TO HTML" description="لغة ترميز النصوص التشعبية" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/otp-to-odp/" name="OTP TO ODP" description="تنسيق العرض التقديمي OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/otp-to-pdf/" name="OTP TO PDF" description="نموذج المستندات المحمولة" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/otp-to-png/" name="OTP TO PNG" description="رسومات الشبكة المحمولة" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/otp-to-pot/" name="OTP TO POT" description="ملفات قوالب Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/otp-to-potm/" name="OTP TO POTM" description="ملف قالب Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/otp-to-potx/" name="OTP TO POTX" description="عرض تقديمي لقالب Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/otp-to-pps/" name="OTP TO PPS" description="عرض شرائح PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/otp-to-ppsm/" name="OTP TO PPSM" description="عرض شرائح ممكّن بماكرو" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/otp-to-ppsx/" name="OTP TO PPSX" description="عرض شرائح PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/otp-to-ppt/" name="OTP TO PPT" description="مايكروسوفت باور بوينت 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/otp-to-pptm/" name="OTP TO PPTM" description="ملف العرض التقديمي الممكّن بماكرو" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/otp-to-pptx/" name="OTP TO PPTX" description="افتح تنسيق عرض XML" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/otp-to-svg/" name="OTP TO SVG" description="الرسومات المتجهات قابلة لل" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/otp-to-swf/" name="OTP TO SWF" description="تنسيق SWF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/otp-to-tiff/" name="OTP TO TIFF" description="تنسيق الصورة الموسومة" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/python-net/conversion/otp-to-xps/" name="OTP TO XPS" description="مواصفات ورق XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
