---
title: استخراج متن و تصاویر از فایل‌های PPT با استفاده از Python
url: /fa/python-net/parser/ppt/
keywords: تجزیه PPT با استفاده از Python، PPT تجزیه کننده Python، استخراج داده ها از PPT در Python، استخراج متن از PPT با استفاده از Python، استخراج تصاویر از PPT با استفاده از Python
description: کد منبع Python برای تجزیه PPT ارائه.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="استخراج متن و تصاویر از ارائه PPT با استفاده از Python" h2="برنامه های Python خود را برای استخراج متن، تصویر، ویدیو و فایل های صوتی از پاورپوینت با استفاده از API های سمت سرور بسازید." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="استخراج متن از ارائه PPT از طریق Python" %}}
برای اسکن متن از کل ارائه، از روش ثابت [GetAllTextFrames](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/) استفاده کنید که توسط کلاس SlideUtil در معرض دید قرار گرفته است. کد زیر متن و اطلاعات قالب‌بندی ارائه، از جمله اسلایدهای اصلی را اسکن می‌کند.
{{% blocks/products/pf/agp/code-block title="استخراج متن از ارائه PPT با استفاده از Python" offSpacer="true" %}}

```py

import aspose.slides as slides

#Instatiate Presentation class that represents a PPT file
with slides.Presentation("pres.ppt") as pptxPresentation:
    # Get an Array of ITextFrame objects from all slides in the PPT
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

{{< blocks/products/pf/feature-page-section  h2="نحوه استخراج متن از PPT از طریق Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="این مراحل برای تجزیه فایل‌های PPT هستند." >}}

{{< blocks/products/pf/agp/step-autogen >}}
PPT را با یک نمونه از Presentation بارگیری کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
آرایه ای از اشیاء TextFrame را از همه اسلایدها در PPT دریافت کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
از طریق آرایه TextFrames حلقه بزنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
از میان پاراگراف ها در TextFrame فعلی حلقه بزنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
بخش‌های پاراگراف فعلی را حلقه بزنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
دریافت متن در بخش فعلی
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="سایر فرمت های تجزیه پشتیبانی شده" subTitle="با استفاده از Python، می‌توانید قالب‌های زیر را نیز اسکن کنید:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/parser/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/parser/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}