---
title: محافظت از فایل‌های ارائه PPTX با استفاده از .NET
url: /fa/net/protect/pptx/
keywords: حفاظت از نوشتن PPTX، رمزگذاری ارائه PPTX، قفل PPTX، محافظت از PPTX
description: کد منبع C# برای محافظت از ارائه PPTX.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="قفل کردن یا محافظت با گذرواژه PPTX با استفاده از C#" h2="برای محافظت از فایل های ارائه با استفاده از API های سمت سرور، برنامه های .NET خود را بسازید." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="محافظت از ارائه PPTX از طریق C#" %}}
با استفاده از Aspose.Slides for .NET، می‌توانید از ارائه PPTX خود در برابر باز کردن یا تغییر با تنظیم رمز عبور محافظت کنید. سپس، برای باز کردن یا اصلاح ارائه قفل شده، کاربر باید رمز عبور را ارائه کند.
{{% blocks/products/pf/agp/code-block title="رمزگذاری یک ارائه PPTX با استفاده از C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("pres.pptx"))
{
    presentation.ProtectionManager.Encrypt("123123");
    presentation.Save("encrypted-pres.pptx", SaveFormat.Pptx);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="تنظیم محافظت از نوشتن روی یک ارائه PPTX با استفاده از C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("pres.pptx"))
{
    presentation.ProtectionManager.SetWriteProtection("123123");
    presentation.Save("write-protected-pres.pptx", SaveFormat.Pptx);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="نحوه محافظت از رمز عبور PPTX از طریق C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="این مراحل برای محافظت از فایل‌های PPTX هستند." >}}

{{< blocks/products/pf/agp/step-autogen >}}
PPTX را با یک نمونه از Presentation بارگیری کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
با استفاده از کلاس ProtectionManager از ارائه محافظت کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
نتیجه را در قالب PPTX ذخیره کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="سایر فرمت های محافظتی پشتیبانی شده" subTitle="با استفاده از C#، می‌توانید از قالب‌های زیر نیز محافظت کنید:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/net/protect/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}