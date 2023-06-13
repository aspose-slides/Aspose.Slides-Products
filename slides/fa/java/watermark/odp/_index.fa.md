---
title: اضافه کردن واترمارک به فایل‌های ارائه ODP با استفاده از Java
url: /fa/java/watermark/odp/
keywords: افزودن واترمارک ODP، افزودن واترمارک متنی ODP، افزودن واترمارک تصویری ODP
description: کد منبع Java برای افزودن واترمارک به ارائه ODP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="اضافه کردن واترمارک به ارائه ODP با استفاده از Java" h2="برنامه های Java خود را بسازید تا با استفاده از API های سمت سرور، متن یا علامت تصویر را در ارائه PPT، PPTX یا ODP وارد کنید." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="اضافه کردن واترمارک به ارائه ODP از طریق Java" %}}
با استفاده از Aspose.Slides for Java، می‌توانید واترمارک را به ارائه ODP اضافه کنید. واترمارک ها بخش مهمی از هر ارائه هستند. آنها برای محافظت از محتوای ارائه در برابر کپی یا استفاده بدون اجازه استفاده می شوند. واترمارک یک تصویر یا متن قابل مشاهده یا نامرئی است که در بالای ارائه قرار می گیرد. می توان از آن برای شناسایی صاحب ارائه و جلوگیری از استفاده غیرمجاز استفاده کرد. همچنین می‌توان از واترمارک‌ها برای افزودن حسی حرفه‌ای به ارائه استفاده کرد و آن را صیقلی‌تر نشان داد. 
{{% blocks/products/pf/agp/code-block title="اضافه کردن متن واترمارک به ODP با استفاده از Java" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    IMasterSlide master = pres.getMasters().get_Item(0);
    IAutoShape watermarkShape = master.getShapes().addAutoShape(ShapeType.Triangle, 0, 0, 0, 0);
    ITextFrame watermarkTextFrame = watermarkShape.addTextFrame("Watermark");

    pres.save("watermark.odp", SaveFormat.Odp);
} finally {
    if (pres != null) pres.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="اضافه کردن واترمارک تصویر به ارائه ODP با استفاده از Java" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("watermark.png")));

    IMasterSlide master = pres.getMasters().get_Item(0);

    IAutoShape watermarkShape = master.getShapes().addAutoShape(ShapeType.Triangle, 0, 0, 100, 100);

    watermarkShape.getFillFormat().setFillType(FillType.Picture);
    watermarkShape.getFillFormat().getPictureFillFormat().getPicture().setImage(image);
    watermarkShape.getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);

    pres.save("watermark2.odp", SaveFormat.Odp);
} finally {
    if (pres != null) pres.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="نحوه افزودن واترمارک به ODP از طریق Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="این مراحل برای افزودن واترمارک متنی به فایل‌های ODP است." >}}

{{< blocks/products/pf/agp/step-autogen >}}
ODP را با یک نمونه از Presentation بارگیری کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ارائه اصلی را انتخاب کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
نوع شکل را با استفاده از روش AddAutoShape اضافه کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
متن واترمارک را با استفاده از روش AddTextFrame اضافه کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
نتیجه را در قالب ODP ذخیره کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="سایر فرمت های پشتیبانی شده" subTitle="با استفاده از Java، می‌توانید واترمارک را نیز به قالب‌های زیر اضافه کنید:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/watermark/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/watermark/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}