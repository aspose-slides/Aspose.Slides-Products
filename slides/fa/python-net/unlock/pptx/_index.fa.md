---
title: باز کردن قفل فایل‌های ارائه PPTX با استفاده از Python
url: /fa/python-net/unlock/pptx/
keywords: حذف حفاظت نوشتن PPTX، رمزگشایی یک PPTX، باز کردن قفل ارائه PPTX، لغو محافظت PPTX
description: کد منبع Python برای حذف حفاظت از ارائه PPTX.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="باز کردن قفل PPTX با استفاده از Python" h2="برای حذف رمزهای عبور از PowerPoint و رمزگشایی فایل‌های ارائه‌ها با استفاده از APIهای سمت سرور، برنامه‌های Python خود را بسازید." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="حذف رمزگذاری از ارائه PPTX از طریق Python" %}}
با استفاده از Aspose.Slides for Python via .NET، می‌توانید حفاظت از رمزگذاری یا رمز عبور را در ارائه PPTX حذف کنید. به این ترتیب، کاربران می توانند بدون محدودیت به ارائه PPTX دسترسی داشته باشند یا آن را تغییر دهند.
{{% blocks/products/pf/agp/code-block title="غیرفعال کردن محافظت از رمز عبور از PPTX با استفاده از Python" offSpacer="true" %}}

```py

import aspose.slides as slides

loadOptions = slides.LoadOptions()
loadOptions.password = "123123"
with slides.Presentation("encrypted-pres.pptx", loadOptions) as pres:
    pres.protection_manager.remove_encryption()
    pres.save("encryption-removed.pptx", slides.export.SaveFormat.PPTX)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="حذف محافظت نوشتاری از ارائه PPTX با استفاده از Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("write-protected-pres.pptx") as pres:
    pres.protection_manager.remove_write_protection()
    pres.save("write-protection-removed.pptx", slides.export.SaveFormat.PPTX)

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="نحوه حذف رمز عبور از PPTX از طریق Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="این مراحل برای حذف حفاظت از فایل‌های PPTX هستند." >}}

{{< blocks/products/pf/agp/step-autogen >}}
PPTX را با یک نمونه از Presentation بارگیری کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Write Protection را با استفاده از کلاس ProtectionManager حذف کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
نتیجه را در قالب PPTX ذخیره کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="سایر فرمت های پشتیبانی شده" subTitle="با استفاده از Python، می‌توانید محافظت از قالب‌های زیر را نیز حذف کنید:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/unlock/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}