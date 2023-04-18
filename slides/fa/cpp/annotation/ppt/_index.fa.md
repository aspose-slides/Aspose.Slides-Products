---
title: حاشیه نویسی PPT را با استفاده از C++ حذف کنید
weight: 4380
url: /fa/cpp/annotation/ppt/ 
description: کد منبع C++ برای حذف حاشیه نویسی از PPT
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="نظرات و نویسندگان نظرات را از PPT در C++ حذف کنید" h2="برنامه های C++ خود را بسازید تا نظرات و نویسندگان را در فایل های سند با استفاده از API های سمت سرور دستکاری کنید." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="نظرات را از PPT از طریق C++ حذف کنید" %}}
برای حذف حاشیه‌نویسی‌ها از فایل PPT، از [Aspose.Slides for C++](https://products.aspose.com/slides/fa/cpp/) API استفاده می‌کنیم که دارای ویژگی‌های غنی، قدرتمند و آسان برای استفاده است. API دستکاری اسناد برای پلتفرم C++.
{{% blocks/products/pf/agp/code-block title="حاشیه نویسی ها را از PPT - C++ حذف کنید" offSpacer="true" %}}

```cpp

using namespace Aspose::Slides;
using namespace Aspose::Slides::Export;
using namespace System::Drawing;

auto presentation = System::MakeObject<Presentation>(u"example.ppt");

// Deletes all comments from the presentation
for (auto author : presentation->get_CommentAuthors())
{
    author->get_Comments()->Clear();
}
        
// Deletes all authors
presentation->get_CommentAuthors()->Clear();
presentation->Save(u"example_out.pptx", SaveFormat::Pptx);
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/feature-page-section  h2="نحوه حذف نظرات از PPT از طریق C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
**Aspose.Slides را برای C++** نصب کنید. [**نصب**](https://docs.aspose.com/slides/cpp/installation/) را ببینید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
PPT را با یک نمونه از کلاس Presentation بارگیری کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
تکرار روی همه نویسندگان PPT بارگذاری شده
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

{{< blocks/products/pf/agp/other-supported-section title="سایر فرمت های حاشیه نویسی پشتیبانی شده" subTitle="با استفاده از C++، می توان به راحتی فرمت های دیگر از جمله حاشیه نویسی کرد." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/cpp/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/cpp/annotation/pptx/" name="PPTX" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}