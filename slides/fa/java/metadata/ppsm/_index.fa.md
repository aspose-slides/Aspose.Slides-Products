---
title: مشاهده یا ویرایش فراداده فایل‌های PPSM با استفاده از Java
url: /fa/java/metadata/ppsm/
keywords: ویرایش فراداده PPSM، مشاهده فراداده PPSM، ویرایش ویژگی‌های PPSM، مشاهده ویژگی‌های PPSM
description: کد منبع Java برای ویرایش یا مشاهده فراداده قالب PPSM.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="ویرایش ویژگی‌های PPSM با استفاده از Java" h2="برنامه‌های Java خود را بسازید تا ویژگی‌های داخلی و سفارشی را در فایل‌های ارائه با استفاده از APIهای سمت سرور تغییر دهید." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPSM" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="اصلاح ویژگی‌های PPSM از طریق Java" %}}
با استفاده از Aspose.Slides for Java، توسعه‌دهندگان می‌توانند به مقادیر ویژگی‌های داخلی و همچنین ویژگی‌های سفارشی دسترسی داشته باشند و آن‌ها را تغییر دهند. توسعه‌دهندگان می‌توانند از ویژگی [DocumentProperties](https://reference.aspose.com/slides/java/com.aspose.slides/documentproperties/) که توسط شی Presentation در معرض دید قرار می‌گیرد برای دسترسی به ویژگی‌های سند فایل ارائه استفاده کنند.
{{% blocks/products/pf/agp/code-block title="اصلاح ویژگی‌های داخلی PPSM - Java" offSpacer="true" %}}

```java

Presentation pres = new Presentation("Presentation.ppsm");
try {
    // Create a reference to IDocumentProperties object associated with Presentation
    IDocumentProperties dp = pres.getDocumentProperties();
    
    // Set the built-in properties
    dp.setAuthor("Aspose.Slides for Java");
    dp.setTitle("Modifying Presentation Properties");
    dp.setSubject("Aspose Subject");
    dp.setComments("Aspose Description");
    dp.setManager("Aspose Manager");
    
    // Save your presentation to a file
    pres.save("DocProps.ppsm", SaveFormat.Ppsm);
} finally {
    if (pres != null) pres.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="افزودن ویژگی های سفارشی به PPSM - Java" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    // Getting Document Properties
    IDocumentProperties dProps = pres.getDocumentProperties();
    
    // Adding Custom properties
    dProps.set_Item("New Custom", 12);
    dProps.set_Item("My Name", "Aspose Metadata Editor");
    dProps.set_Item("Custom", 124);
    
    // Getting property name at particular index
    String getPropertyName = dProps.getCustomPropertyName(2);
    
    // Removing selected property
    dProps.removeCustomProperty(getPropertyName);
    
    // Saving presentation
    pres.save("CustomDemo.ppsm", SaveFormat.Ppsm);
} finally {
    if (pres != null) pres.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="نحوه استخراج فراداده PPSM از طریق Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="این مراحل برای استخراج فراداده از فایل‌های PPSM است." >}}

{{< blocks/products/pf/agp/step-autogen >}}
کلاس Presentation را با مسیر فایل PPSM نمونه سازی کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
دریافت شی DocumentProperties مرتبط با Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
حلقه روی آیتم ها در شی DocumentProperties
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
دسترسی و اصلاح خواص سفارشی
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="سایر فرمت های فراداده پشتیبانی شده" subTitle="با استفاده از Java، می‌توانید ابرداده‌های بسیاری از قالب‌های دیگر از جمله را نیز دستکاری کنید." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/metadata/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}