---
title: تحويل ODP إلى BMP في Python
weight: 230
url: /ar/python-net/conversion/odp-to-bmp/ 
keywords: "Convert, PowerPoint, ODP, BMP, Presentation, Python"
description: رمز عينة لتحويل ODP إلى BMP Python. استخدم PowerPoint Python API لتحويل ملفات ODP إلى ملفات BMP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="تحويل ODP إلى BMP في Python" h2="مكتبة بايثون قوية لتحويل ODP إلى BMP" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="SVG" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/python-net/" installationsDocsLink="https://docs.aspose.com/slides/python-net/installation/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/python-net" learnAsLink="https://docs.aspose.com/slides/python-net/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="تحويل ODP إلى BMP في Python" %}}

هل تحتاج إلى تحويل ملفات ODP إلى BMP برمجيًا؟ باستخدام [* Aspose.Slides for Python عبر .NET *](https://products.aspose.com/slides/python-net/) يمكن لأي مطور تحويل ODP إلى تنسيق BMP ببضعة أسطر فقط من كود Python.

كواجهة برمجة تطبيقات حديثة لمعالجة العروض التقديمية ، تقوم Aspose.Slides for Python بإنشاء BMP من ODP بسرعة. اختبر جودة تحويل ODP إلى BMP مباشرة في [المتصفح](https://products.aspose.app/slides/conversion). تسمح لك مكتبة Aspose PowerPoint PPTX بتحويل ملفات ODP إلى العديد من التنسيقات الشائعة.

يمكنك تثبيت المكتبة من [PyPI](https://pypi.org/project/Aspose.Slides/) باستخدام أمر pip التالي:

{{% blocks/products/pf/agp/code-block title="وحدة التحكم / المحطة" offSpacer="true" %}}

```console
> pip install aspose.slides

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/agp/feature-section-col title="كيفية تحويل ODP إلى BMP في Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="هذه هي خطوات تحويل ملف ODP إلى BMP باستخدام Python." >}}

{{< blocks/products/pf/agp/step-autogen >}}
قم بتحميل ملف ODP بنسخة من فئة العرض التقديمي
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
استدعاء طريقة "save" أثناء تحديد مسار ملف الإخراج & SaveFormat.BMP كمعلمات
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
سيتم حفظ ملف ODP في المسار المحدد
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات النظام" %}}

{{% blocks/products/pf/agp/text %}}

 قبل تشغيل رمز مصدر نموذج تحويل Python ، تأكد من توفر المتطلبات الأساسية التالية.

{{% /blocks/products/pf/agp/text %}}

- نظام التشغيل Microsoft Windows أو Linux (راجع [المزيد](https://docs.aspose.com/slides/python-net/system-requirements/)).
- Python 3.5 أو أحدث
- Aspose.Slides for Python المشار إليها في مشروعك.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="يوضح نموذج الكود هذا تحويل ODP إلى BMP Python" offSpacer="" %}}

```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.odp") as presentation:
    for slide in presentation.slides:
        slide.get_thumbnail(2, 2).save("presentation_slide_{0}.bmp".format(str(slide.slide_number)), drawing.imaging.ImageFormat.bmp)

```
{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 
{{% blocks/products/pf/agp/content h2="احفظ ODP كـ BMP في Python" %}}
استخدم التطبيق المجاني لمشاهدة عرض توضيحي لعملية تحويل ODP إلى BMP. 
{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension="odp-to-bmp"
        sectionTitle="تطبيق مجاني لتحويل ODP إلى BMP" 
        sectionDescription="[جرب تطبيقنا المجاني لتحويل PPT إلى BMP](https://products.aspose.app/slides/conversion/ppt-to-bmp)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="التحويلات المدعومة الأخرى" subTitle="يمكنك أيضًا تحويل ODP إلى العديد من تنسيقات الملفات الأخرى. انظر التحويلات الأخرى المدعومة أدناه" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-emf/" name="ODP TO EMF" description="تنسيق ملف التعريف المحسن" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-fodp/" name="ODP TO FODP" description="عرض تقديمي XML مسطح OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-gif/" name="ODP TO GIF" description="تنسيق التبادل الرسومي" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-html/" name="ODP TO HTML" description="لغة ترميز النصوص التشعبية" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-jpg/" name="ODP TO JPG" description="صورة JPEG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-otp/" name="ODP TO OTP" description="تنسيق OpenDocument القياسي" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-pdf/" name="ODP TO PDF" description="نموذج المستندات المحمولة" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-png/" name="ODP TO PNG" description="رسومات الشبكة المحمولة" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-pot/" name="ODP TO POT" description="ملفات قوالب Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-potm/" name="ODP TO POTM" description="ملف قالب Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-potx/" name="ODP TO POTX" description="عرض تقديمي لقالب Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-pps/" name="ODP TO PPS" description="عرض شرائح PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-ppsm/" name="ODP TO PPSM" description="عرض شرائح ممكّن بماكرو" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-ppsx/" name="ODP TO PPSX" description="عرض شرائح PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-ppt/" name="ODP TO PPT" description="مايكروسوفت باور بوينت 97-2003" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-pptm/" name="ODP TO PPTM" description="ملف العرض التقديمي الممكّن بماكرو" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-pptx/" name="ODP TO PPTX" description="افتح تنسيق عرض XML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-svg/" name="ODP TO SVG" description="الرسومات المتجهات قابلة لل" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-swf/" name="ODP TO SWF" description="تنسيق SWF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-tiff/" name="ODP TO TIFF" description="تنسيق الصورة الموسومة" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-xps/" name="ODP TO XPS" description="مواصفات ورق XML" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}