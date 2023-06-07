---
title: باز کردن قفل فایل‌های ارائه ODP با استفاده از .NET
url: /fa/net/unlock/odp/
keywords: حذف حفاظت نوشتن ODP، رمزگشایی یک ODP، باز کردن قفل ارائه ODP، لغو محافظت ODP
description: کد منبع C# برای حذف حفاظت از ارائه ODP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="باز کردن قفل ODP با استفاده از C#" h2="برای حذف رمزهای عبور از PowerPoint و رمزگشایی فایل‌های ارائه‌ها با استفاده از APIهای سمت سرور، برنامه‌های .NET خود را بسازید." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="حذف رمزگذاری از ارائه ODP از طریق C#" %}}
با استفاده از Aspose.Slides for .NET، می‌توانید حفاظت از رمزگذاری یا رمز عبور را در ارائه ODP حذف کنید. به این ترتیب، کاربران می توانند بدون محدودیت به ارائه ODP دسترسی داشته باشند یا آن را تغییر دهند.
{{% blocks/products/pf/agp/code-block title="غیرفعال کردن محافظت از رمز عبور از ODP با استفاده از C#" offSpacer="true" %}}

```cs

LoadOptions loadOptions = new LoadOptions {Password = "123123"};
using (Presentation presentation = new Presentation("pres.odp", loadOptions))
{
    presentation.ProtectionManager.RemoveEncryption();
    presentation.Save("encryption-removed.odp", SaveFormat.Odp);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="حذف محافظت نوشتاری از ارائه ODP با استفاده از C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("pres.odp"))
{
    presentation.ProtectionManager.RemoveWriteProtection();
    presentation.Save("write-protection-removed.odp", SaveFormat.Odp);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="نحوه حذف رمز عبور از ODP از طریق C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="این مراحل برای حذف حفاظت از فایل‌های ODP هستند." >}}

{{< blocks/products/pf/agp/step-autogen >}}
ODP را با یک نمونه از Presentation بارگیری کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Write Protection را با استفاده از کلاس ProtectionManager حذف کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
نتیجه را در قالب ODP ذخیره کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="سایر فرمت های پشتیبانی شده" subTitle="با استفاده از C#، می‌توانید محافظت از قالب‌های زیر را نیز حذف کنید:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/net/unlock/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/net/unlock/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}