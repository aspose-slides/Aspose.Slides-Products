---
title: اضافه کردن واترمارک به فایل‌های ارائه PPT با استفاده از C++
url: /fa/cpp/watermark/ppt/
keywords: افزودن واترمارک PPT، افزودن واترمارک متنی PPT، افزودن واترمارک تصویری PPT
description: کد منبع C++ برای افزودن واترمارک به ارائه PPT.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="اضافه کردن واترمارک به ارائه PPT با استفاده از C++" h2="برنامه های C++ خود را بسازید تا با استفاده از API های سمت سرور، متن یا علامت تصویر را در ارائه PPT، PPTX یا ODP وارد کنید." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="اضافه کردن واترمارک به ارائه PPT از طریق C++" %}}
با استفاده از Aspose.Slides for C++، می‌توانید واترمارک را به ارائه PPT اضافه کنید. واترمارک ها بخش مهمی از هر ارائه هستند. آنها برای محافظت از محتوای ارائه در برابر کپی یا استفاده بدون اجازه استفاده می شوند. واترمارک یک تصویر یا متن قابل مشاهده یا نامرئی است که در بالای ارائه قرار می گیرد. می توان از آن برای شناسایی صاحب ارائه و جلوگیری از استفاده غیرمجاز استفاده کرد. همچنین می‌توان از واترمارک‌ها برای افزودن حسی حرفه‌ای به ارائه استفاده کرد و آن را صیقلی‌تر نشان داد. 
{{% blocks/products/pf/agp/code-block title="اضافه کردن متن واترمارک به PPT با استفاده از C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);
auto master = presentation->get_Masters()->idx_get(0);
auto watermarkShape = slide->get_Shapes()->AddAutoShape(ShapeType::Triangle, 0.0f, 0.0f, 0.0f, 0.0f);

auto watermarkTextFrame = watermarkShape->AddTextFrame(u"Watermark");
presentation->Save(u"watermark.ppt", SaveFormat::Ppt);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="اضافه کردن واترمارک تصویر به ارائه PPT با استفاده از C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);
auto master = presentation->get_Masters()->idx_get(0);
auto watermarkShape = slide->get_Shapes()->AddAutoShape(ShapeType::Triangle, 0.0f, 0.0f, 0.0f, 0.0f);

auto image = presentation->get_Images()->AddImage(:File::ReadAllBytes(u"watermark.png"));

watermarkShape->get_FillFormat()->set_FillType(FillType::Picture);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->get_Picture()->set_Image(image);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->set_PictureFillMode(PictureFillMode::Stretch);

presentation->Save(u"watermark2.ppt", SaveFormat::Ppt);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="نحوه افزودن واترمارک به PPT از طریق C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="این مراحل برای افزودن واترمارک متنی به فایل‌های PPT است." >}}

{{< blocks/products/pf/agp/step-autogen >}}
PPT را با یک نمونه از Presentation بارگیری کنید
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
نتیجه را در قالب PPT ذخیره کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="سایر فرمت های پشتیبانی شده" subTitle="با استفاده از C++، می‌توانید واترمارک را نیز به قالب‌های زیر اضافه کنید:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/cpp/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/cpp/watermark/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}