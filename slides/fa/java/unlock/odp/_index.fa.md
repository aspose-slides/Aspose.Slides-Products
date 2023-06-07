---
title: باز کردن قفل فایل‌های ارائه ODP با استفاده از Java
url: /fa/java/unlock/odp/
keywords: حذف حفاظت نوشتن ODP، رمزگشایی یک ODP، باز کردن قفل ارائه ODP، لغو محافظت ODP
description: کد منبع Java برای حذف حفاظت از ارائه ODP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="باز کردن قفل ODP با استفاده از Java" h2="برای حذف رمزهای عبور از PowerPoint و رمزگشایی فایل‌های ارائه‌ها با استفاده از APIهای سمت سرور، برنامه‌های Java خود را بسازید." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="حذف رمزگذاری از ارائه ODP از طریق Java" %}}
با استفاده از Aspose.Slides for Java، می‌توانید حفاظت از رمزگذاری یا رمز عبور را در ارائه ODP حذف کنید. به این ترتیب، کاربران می توانند بدون محدودیت به ارائه ODP دسترسی داشته باشند یا آن را تغییر دهند.
{{% blocks/products/pf/agp/code-block title="غیرفعال کردن محافظت از رمز عبور از ODP با استفاده از Java" offSpacer="true" %}}

```java

LoadOptions loadOptions = new LoadOptions();
loadOptions.setPassword("123123");
Presentation presentation = new Presentation("pres.odp", loadOptions);
try {
    presentation.getProtectionManager().removeEncryption();
    presentation.save("encryption-removed.odp", SaveFormat.Odp);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="حذف محافظت نوشتاری از ارائه ODP با استفاده از Java" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("pres.odp");
try {
    presentation.getProtectionManager().removeWriteProtection();
    presentation.save("write-protection-removed.odp", SaveFormat.Odp);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="نحوه حذف رمز عبور از ODP از طریق Java" >}}

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

{{< blocks/products/pf/agp/other-supported-section title="سایر فرمت های پشتیبانی شده" subTitle="با استفاده از Java، می‌توانید محافظت از قالب‌های زیر را نیز حذف کنید:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/unlock/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/unlock/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}