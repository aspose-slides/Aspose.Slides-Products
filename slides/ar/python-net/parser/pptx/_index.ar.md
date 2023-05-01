---
title: استخراج النص والصور من ملفات PPTX باستخدام Python
url: /ar/python-net/parser/pptx/
keywords: تحليل PPTX باستخدام Python ، PPTX المحلل اللغوي Python ، واستخراج البيانات من PPTX في Python ، واستخراج النص من PPTX باستخدام Python ، واستخراج الصور من PPTX باستخدام Python
description: Python شفرة المصدر لتحليل العرض التقديمي PPTX.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="استخراج النص والصور من عرض PPTX باستخدام Python" h2="أنشئ تطبيقات Python الخاصة بك لاستخراج ملفات النصوص والصور والفيديو والصوت من PowerPoint باستخدام واجهات برمجة التطبيقات من جانب الخادم." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="استخراج نص من PPTX العرض التقديمي عبر Python" %}}
لمسح النص من العرض التقديمي بأكمله ، استخدم الأسلوب الثابت [GetAllTextFrames](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/) الذي تعرضه فئة SlideUtil. يقوم الكود أدناه بمسح النص ومعلومات التنسيق من العرض التقديمي ، بما في ذلك الشرائح الرئيسية.
{{% blocks/products/pf/agp/code-block title="استخراج نص من PPTX عرض تقديمي باستخدام Python" offSpacer="true" %}}

```py

import aspose.slides as slides

#Instatiate Presentation class that represents a PPTX file
with slides.Presentation("pres.pptx") as pptxPresentation:
    # Get an Array of ITextFrame objects from all slides in the PPTX
    textFramesPPTX = slides.util.SlideUtil.get_all_text_frames(pptxPresentation, True)
    
    # Loop through the Array of TextFrames
    for i in range(len(textFramesPPTX)):
	    # Loop through paragraphs in current ITextFrame
        for para in textFramesPPTX[i].paragraphs:
            # Loop through portions in the current IParagraph
            for port in para.portions:
			    # Display text in the current portion
                print(port.text)

    			# Display font height of the text
                print(port.portion_format.font_height)

			    # Display font name of the text
                if port.portion_format.latin_font != None:
                    print(port.portion_format.latin_font.font_name)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="كيفية استخراج نص من PPTX عبر Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="هذه هي خطوات تحليل ملفات PPTX." >}}

{{< blocks/products/pf/agp/step-autogen >}}
تحميل PPTX بمثيل عرض تقديمي
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
الحصول على صفيف من كائنات TextFrame من كل الشرائح في PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
حلقة خلال صفيف إطارات النص
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
تكرار الفقرات في TextFrame الحالي
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
تكرار خلال الأجزاء في الفقرة الحالية
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
احصل على نص في الجزء الحالي
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="تنسيقات التحليل المدعومة الأخرى" subTitle="باستخدام Python ، يمكنك أيضًا فحص التنسيقات التالية:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/parser/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/parser/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}