---
title: ویرایش فایل‌های ارائه PPTX با استفاده از Python
url: /fa/python-net/redaction/pptx/
keywords: ویرایش PPTX، یافتن و جایگزینی متن در PPTX، به روز رسانی PPTX ارائه
description: کد منبع Python برای یافتن و جایگزینی متن در ارائه PPTX.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="ویرایش PPTX با استفاده از Python" h2="برنامه های Python خود را بسازید تا متن را در فایل های ارائه با استفاده از API های سمت سرور پیدا کرده و جایگزین کنید. با نحوه جستجو و جایگزینی متن در محتوا، نظرات یا ابرداده ارائه‌های PPTX آشنا شوید" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="ویرایش PPTX ارائه از طریق Python" %}}
جستجوی اولیه سند و جایگزینی متن در محتوا، نظرات، یادداشت‌های اسلاید یا ابرداده با APIهای Aspose.Slides for Python via .NET تنها با چند خط کد انجام می‌شود. متن را در پاورپوینت و اپن آفیس پیدا و جایگزین کنید. ویرایش متن، نظرات، ابرداده در ارائه از طریق تطبیق داده های regexp.
{{% blocks/products/pf/agp/code-block title="ویرایش PPTX ارائه با استفاده از Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("welcome-to-powerpoint.pptx") as pres:
    slides.util.SlideUtil.find_and_replace_text(pres, True, "PowerPoint", "Aspose.Slides", None)
    pres.save("replaced.pptx", slides.export.SaveFormat.PPTX)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="نحوه ویرایش PPTX از طریق Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="این مراحل برای ویرایش فایل‌های PPTX هستند." >}}

{{< blocks/products/pf/agp/step-autogen >}}
PPTX را با یک نمونه از Presentation بارگیری کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
برای یافتن و جایگزینی متن از روش [FindAndReplaceText](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/) استفاده کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
نتیجه را در قالب PPTX ذخیره کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="نسخه‌های نمایشی زنده ویرایش آنلاین PPTX" sectionDescription="در حال حاضر متن، نظرات یا ابرداده را در اسناد PPTX جستجو و جایگزین کنید." >}}

{{< blocks/products/pf/agp/other-supported-section title="سایر فرمت های پشتیبانی شده Redact" subTitle="با استفاده از Python، می‌توانید قالب‌های زیر را نیز ویرایش کنید:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/redaction/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}