---
title: حاشیه نویسی ODP را با استفاده از پایتون حذف کنید
weight: 4380
url: /fa/python-net/annotation/odp/ 
description: کد منبع پایتون برای حذف نظرات ارائه ODP
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="نظرات و نویسندگان نظرات را از ODP در پایتون حذف کنید" h2="اسکریپت های پایتون خود را برای دستکاری نظرات و نویسندگان در فایل های سند با استفاده از API های سمت سرور بسازید." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="حذف نظرات از ODP از طریق پایتون" %}}
برای حذف حاشیه‌نویسی‌ها از فایل ODP، از [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/fa/python-net/) API استفاده می‌کنیم که دارای ویژگی‌های غنی است، API دستکاری اسناد قدرتمند و آسان برای پلتفرم پایتون.
{{% blocks/products/pf/agp/code-block title="حاشیه نویسی ها را از ODP - Python حذف کنید" offSpacer="true" %}}

```python

import aspose.slides as slides

with slides.Presentation("example.odp") as presentation:
    # Deletes all comments from the presentation
    for author in presentation.comment_authors:
        author.comments.clear()

    # Deletes all authors
    presentation.comment_authors.clear()

    presentation.save("example_out.pptx", slides.export.SaveFormat.PPTX)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/feature-page-section  h2="نحوه حذف نظرات از ODP از طریق پایتون" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Install **Aspose.Slides for Python via .NET**. See [**Installation**](https://docs.aspose.com/slides/python-net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ODP را با یک نمونه از کلاس Presentation بارگیری کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
تکرار روی همه نویسندگان ODP بارگذاری شده
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
تمام نظرات یک نویسنده را حذف کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
در پایان تمام نویسندگان را حذف کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="سایر فرمت های حاشیه نویسی پشتیبانی شده" subTitle="با استفاده از پایتون، می توان به راحتی فرمت های دیگر از جمله حاشیه نویسی کرد." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/annotation/pptx/" name="PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/annotation/ppt/" name="PPT" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}