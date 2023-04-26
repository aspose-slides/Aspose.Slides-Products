---
title: محافظت از فایل‌های ارائه PPT با استفاده از Python
url: /fa/python-net/protect/ppt/
keywords: حفاظت از نوشتن PPT، رمزگذاری ارائه PPT، قفل PPT، محافظت از PPT
description: کد منبع Python برای محافظت از ارائه PPT.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="قفل کردن یا محافظت با گذرواژه PPT با استفاده از Python" h2="برای محافظت از فایل های ارائه با استفاده از API های سمت سرور، برنامه های Python خود را بسازید." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="محافظت از ارائه PPT از طریق Python" %}}
با استفاده از Aspose.Slides for Python via .NET، می‌توانید از ارائه PPT خود در برابر باز کردن یا تغییر با تنظیم رمز عبور محافظت کنید. سپس، برای باز کردن یا اصلاح ارائه قفل شده، کاربر باید رمز عبور را ارائه کند.
{{% blocks/products/pf/agp/code-block title="رمزگذاری یک ارائه PPT با استفاده از Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("pres.ppt") as pres:
    pres.protection_manager.encrypt("123123")
    pres.save("encrypted-pres.ppt", slides.export.SaveFormat.PPT)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="تنظیم محافظت از نوشتن روی یک ارائه PPT با استفاده از Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("pres.ppt") as pres:
    pres.protection_manager.set_write_protection("123123")
    pres.save("write-protected-pres.ppt", slides.export.SaveFormat.PPT)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="نحوه محافظت از رمز عبور PPT از طریق Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="این مراحل برای محافظت از فایل‌های PPT هستند." >}}

{{< blocks/products/pf/agp/step-autogen >}}
PPT را با یک نمونه از Presentation بارگیری کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
با استفاده از کلاس ProtectionManager از ارائه محافظت کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
نتیجه را در قالب PPT ذخیره کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="سایر فرمت های محافظتی پشتیبانی شده" subTitle="با استفاده از Python، می‌توانید از قالب‌های زیر نیز محافظت کنید:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/protect/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}