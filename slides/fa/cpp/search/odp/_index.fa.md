---
title: جستجوی متن در فایل‌های ارائه ODP با استفاده از C++
url: /fa/cpp/search/odp/
keywords: کلمات جستجو در ODP، جستجو و جایگزینی متن در ODP، متن جستجو ODP ارائه
description: کد منبع C++ برای جستجوی متن در ارائه ODP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="جستجوی متن ODP با استفاده از C++" h2="برنامه‌های C++ خود را برای جستجو و جایگزینی متن در فایل‌های ارائه با استفاده از APIهای سمت سرور بسازید. یاد بگیرید که چگونه تمام ورودی های یک کلمه یا عبارت خاص را در اسناد ارائه پیدا کنید. متن را با تطبیق دقیق داده ها و تطبیق عبارت منظم جستجو کنید." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="جستجو و جایگزینی متن ODP ارائه از طریق C++" %}}
جستجوی اولیه سند و جایگزینی متن در محتوا، نظرات، یادداشت‌های اسلاید یا ابرداده با APIهای Aspose.Slides for C++ تنها با چند خط کد انجام می‌شود. برای جستجوی متن در ارائه، از تطبیق عبارات منظم، حروف مطابقت استفاده کنید. متن را در عنوان، محتوا، پاورقی یا سرصفحه جستجو کنید.
{{% blocks/products/pf/agp/code-block title="جستجوی متن ODP ارائه با استفاده از C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"welcome-to-powerpoint.odp");

SlideUtil::FindAndReplaceText(presentation, true, u"PowerPoint", u"Aspose.Slides", nullptr);
presentation->Save(u"replaced.odp", SaveFormat::Odp);	
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="نحوه جستجوی متن در ODP از طریق C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="این مراحل برای جستجوی فایل‌های متنی ODP است." >}}

{{< blocks/products/pf/agp/step-autogen >}}
ODP را با یک نمونه از Presentation بارگیری کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
برای یافتن و جایگزینی متن از روش [FindAndReplaceText](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/findandreplacetext/) استفاده کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
نتیجه را در قالب ODP ذخیره کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="جستجوی آنلاین نسخه‌های نمایشی زنده ODP" sectionDescription="در حال حاضر متن، نظرات یا ابرداده را در اسناد ODP جستجو و جایگزین کنید." >}}

{{< blocks/products/pf/agp/other-supported-section title="سایر فرمت های جستجوی پشتیبانی شده" subTitle="با استفاده از C++، می‌توانید متن را در قالب‌های زیر نیز جستجو کنید:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/cpp/search/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/cpp/search/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}