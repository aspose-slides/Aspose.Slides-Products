---
title: محافظت از فایل‌های ارائه PPT با استفاده از Java
url: /fa/java/protect/ppt/
keywords: حفاظت از نوشتن PPT، رمزگذاری ارائه PPT، قفل PPT، محافظت از PPT
description: کد منبع Java برای محافظت از ارائه PPT.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="قفل کردن یا محافظت با گذرواژه PPT با استفاده از Java" h2="برای محافظت از فایل های ارائه با استفاده از API های سمت سرور، برنامه های Java خود را بسازید." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="محافظت از ارائه PPT از طریق Java" %}}
با استفاده از Aspose.Slides for Java، می‌توانید از ارائه PPT خود در برابر باز کردن یا تغییر با تنظیم رمز عبور محافظت کنید. سپس، برای باز کردن یا اصلاح ارائه قفل شده، کاربر باید رمز عبور را ارائه کند.
{{% blocks/products/pf/agp/code-block title="رمزگذاری یک ارائه PPT با استفاده از Java" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("pres.ppt");
try {
    presentation.getProtectionManager().encrypt("123123");
    presentation.save("encrypted-pres.ppt", SaveFormat.Ppt);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="تنظیم محافظت از نوشتن روی یک ارائه PPT با استفاده از Java" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("pres.ppt");
try {
    presentation.getProtectionManager().setWriteProtection("123123");
    presentation.save("write-protected-pres.ppt", SaveFormat.Ppt);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="نحوه محافظت از رمز عبور PPT از طریق Java" >}}

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

{{< blocks/products/pf/agp/other-supported-section title="سایر فرمت های محافظتی پشتیبانی شده" subTitle="با استفاده از Java، می‌توانید از قالب‌های زیر نیز محافظت کنید:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/protect/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}