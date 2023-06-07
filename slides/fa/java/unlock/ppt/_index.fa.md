---
title: باز کردن قفل فایل‌های ارائه PPT با استفاده از Java
url: /fa/java/unlock/ppt/
keywords: حذف حفاظت نوشتن PPT، رمزگشایی یک PPT، باز کردن قفل ارائه PPT، لغو محافظت PPT
description: کد منبع Java برای حذف حفاظت از ارائه PPT.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="باز کردن قفل PPT با استفاده از Java" h2="برای حذف رمزهای عبور از PowerPoint و رمزگشایی فایل‌های ارائه‌ها با استفاده از APIهای سمت سرور، برنامه‌های Java خود را بسازید." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="حذف رمزگذاری از ارائه PPT از طریق Java" %}}
با استفاده از Aspose.Slides for Java، می‌توانید حفاظت از رمزگذاری یا رمز عبور را در ارائه PPT حذف کنید. به این ترتیب، کاربران می توانند بدون محدودیت به ارائه PPT دسترسی داشته باشند یا آن را تغییر دهند.
{{% blocks/products/pf/agp/code-block title="غیرفعال کردن محافظت از رمز عبور از PPT با استفاده از Java" offSpacer="true" %}}

```java

LoadOptions loadOptions = new LoadOptions();
loadOptions.setPassword("123123");
Presentation presentation = new Presentation("pres.ppt", loadOptions);
try {
    presentation.getProtectionManager().removeEncryption();
    presentation.save("encryption-removed.ppt", SaveFormat.Ppt);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="حذف محافظت نوشتاری از ارائه PPT با استفاده از Java" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("pres.ppt");
try {
    presentation.getProtectionManager().removeWriteProtection();
    presentation.save("write-protection-removed.ppt", SaveFormat.Ppt);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="نحوه حذف رمز عبور از PPT از طریق Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="این مراحل برای حذف حفاظت از فایل‌های PPT هستند." >}}

{{< blocks/products/pf/agp/step-autogen >}}
PPT را با یک نمونه از Presentation بارگیری کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Write Protection را با استفاده از کلاس ProtectionManager حذف کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
نتیجه را در قالب PPT ذخیره کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="سایر فرمت های پشتیبانی شده" subTitle="با استفاده از Java، می‌توانید محافظت از قالب‌های زیر را نیز حذف کنید:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/unlock/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}