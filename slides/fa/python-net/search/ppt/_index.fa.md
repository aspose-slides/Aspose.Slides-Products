---
title: جستجوی متن در فایل‌های ارائه PPT با استفاده از Python
url: /fa/python-net/search/ppt/
keywords: کلمات جستجو در PPT، جستجو و جایگزینی متن در PPT، متن جستجو PPT ارائه
description: کد منبع Python برای جستجوی متن در ارائه PPT.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="جستجوی متن PPT با استفاده از Python" h2="برنامه‌های Python خود را برای جستجو و جایگزینی متن در فایل‌های ارائه با استفاده از APIهای سمت سرور بسازید. یاد بگیرید که چگونه تمام ورودی های یک کلمه یا عبارت خاص را در اسناد ارائه پیدا کنید. متن را با تطبیق دقیق داده ها و تطبیق عبارت منظم جستجو کنید." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="جستجو و جایگزینی متن PPT ارائه از طریق Python" %}}
جستجوی اولیه سند و جایگزینی متن در محتوا، نظرات، یادداشت‌های اسلاید یا ابرداده با APIهای Aspose.Slides for Python via .NET تنها با چند خط کد انجام می‌شود. برای جستجوی متن در ارائه، از تطبیق عبارات منظم، حروف مطابقت استفاده کنید. متن را در عنوان، محتوا، پاورقی یا سرصفحه جستجو کنید.
{{% blocks/products/pf/agp/code-block title="جستجوی متن PPT ارائه با استفاده از Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("welcome-to-powerpoint.ppt") as pres:
    slides.util.SlideUtil.find_and_replace_text(pres, True, "PowerPoint", "Aspose.Slides", None)
    pres.save("replaced.ppt", slides.export.SaveFormat.PPT)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="نحوه جستجوی متن در PPT از طریق Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="این مراحل برای جستجوی فایل‌های متنی PPT است." >}}

{{< blocks/products/pf/agp/step-autogen >}}
PPT را با یک نمونه از Presentation بارگیری کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
برای یافتن و جایگزینی متن از روش [FindAndReplaceText](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/) استفاده کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
نتیجه را در قالب PPT ذخیره کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="جستجوی آنلاین نسخه‌های نمایشی زنده PPT" sectionDescription="در حال حاضر متن، نظرات یا ابرداده را در اسناد PPT جستجو و جایگزین کنید." >}}

{{< blocks/products/pf/agp/other-supported-section title="سایر فرمت های جستجوی پشتیبانی شده" subTitle="با استفاده از Python، می‌توانید متن را در قالب‌های زیر نیز جستجو کنید:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/search/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/search/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}