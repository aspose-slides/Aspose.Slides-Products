---
title: اضافه کردن واترمارک به فایل‌های ارائه PPTX با استفاده از .NET
url: /fa/net/watermark/pptx/
keywords: افزودن واترمارک PPTX، افزودن واترمارک متنی PPTX، افزودن واترمارک تصویری PPTX
description: کد منبع C# برای افزودن واترمارک به ارائه PPTX.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="اضافه کردن واترمارک به ارائه PPTX با استفاده از C#" h2="برنامه های .NET خود را بسازید تا با استفاده از API های سمت سرور، متن یا علامت تصویر را در ارائه PPT، PPTX یا ODP وارد کنید." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="اضافه کردن واترمارک به ارائه PPTX از طریق C#" %}}
با استفاده از Aspose.Slides for .NET، می‌توانید واترمارک را به ارائه PPTX اضافه کنید. واترمارک ها بخش مهمی از هر ارائه هستند. آنها برای محافظت از محتوای ارائه در برابر کپی یا استفاده بدون اجازه استفاده می شوند. واترمارک یک تصویر یا متن قابل مشاهده یا نامرئی است که در بالای ارائه قرار می گیرد. می توان از آن برای شناسایی صاحب ارائه و جلوگیری از استفاده غیرمجاز استفاده کرد. همچنین می‌توان از واترمارک‌ها برای افزودن حسی حرفه‌ای به ارائه استفاده کرد و آن را صیقلی‌تر نشان داد. 
{{% blocks/products/pf/agp/code-block title="اضافه کردن متن واترمارک به PPTX با استفاده از C#" offSpacer="true" %}}

```cs

using (var presentation = new Presentation())
{
    ISlide slide = presentation.Slides[0];
    IAutoShape watermarkShape = slide.Shapes.AddAutoShape(ShapeType.Triangle, 0, 0, 0, 0);
    ITextFrame watermarkTextFrame = watermarkShape.AddTextFrame("Watermark");

    presentation.Save("watermark.pptx", SaveFormat.Pptx);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="اضافه کردن واترمارک تصویر به ارائه PPTX با استفاده از C#" offSpacer="true" %}}

```cs

using (var presentation = new Presentation())
{
    ISlide slide = presentation.Slides[0];
    IAutoShape watermarkShape = slide.Shapes.AddAutoShape(ShapeType.Triangle, 0, 0, 0, 0);

    IPPImage image = presentation.Images.AddImage(File.ReadAllBytes("watermark.png"));

    watermarkShape.FillFormat.FillType = FillType.Picture;
    watermarkShape.FillFormat.PictureFillFormat.Picture.Image = image;
    watermarkShape.FillFormat.PictureFillFormat.PictureFillMode = PictureFillMode.Stretch;

    presentation.Save("watermark2.pptx", SaveFormat.Pptx);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="نحوه افزودن واترمارک به PPTX از طریق C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="این مراحل برای افزودن واترمارک متنی به فایل‌های PPTX است." >}}

{{< blocks/products/pf/agp/step-autogen >}}
PPTX را با یک نمونه از Presentation بارگیری کنید
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
نتیجه را در قالب PPTX ذخیره کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="سایر فرمت های پشتیبانی شده" subTitle="با استفاده از C#، می‌توانید واترمارک را نیز به قالب‌های زیر اضافه کنید:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/net/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/net/watermark/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}