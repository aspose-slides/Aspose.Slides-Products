---
title: تبدیل تصویر به PPT در ++C
url: /fa/cpp/conversion/image-to-ppt/
keywords: تصویر به PPT، تبدیل تصویر به PPT، C++ API، کتابخانه C++، تصویر، PPT
description: تبدیل تصویر به PPT در ++C. از C++ library API برای تبدیل فایل های تصویری به PDF استفاده کنید
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="تبدیل تصویر به PPT در ++C" h2="کتابخانه C++ پرسرعت و چند پلتفرمی که به توسعه برنامه‌های کاربردی با قابلیت ایجاد، ادغام، بازرسی یا تبدیل فایل‌های ارائه Microsoft PowerPoint و OpenOffice بدون استفاده از هیچ نرم‌افزاری مانند Microsoft یا Open Office، Adobe PDF کمک می‌کند." >}}

{{% blocks/products/pf/feature-page-section h2="تبدیل تصویر به PPT در ++C" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/fa/cpp/) یک کتابخانه قدرتمند C++ برای ایجاد و دستکاری فایل های ارائه است. علاوه بر این، راه های انعطاف پذیری را برای تبدیل تصویر به PPT ارائه می دهد. با استفاده از **Aspose.Slides برای C++**، هر برنامه‌نویس یا برنامه‌ای می‌تواند تصویر را تنها با چند خط کد C++ به فایل‌های PPT تبدیل کند.

Aspose.Slides برای C++ به عنوان یک API مدرن برای پردازش اسناد، فایل‌های تصویر را به سرعت به فرمت‌های فایل PPT صادر می‌کند. کتابخانه Aspose PowerPoint به شما امکان تبدیل تصویر به PDF و بسیاری از فرمت های فایل دیگر را می دهد

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="با استفاده از C++ تصویر را به PPT تبدیل کنید" %}}
برای تبدیل تصویر به PPT، باید Presentation را از فایل Image ایجاد کنید و آن را به عنوان PPT ذخیره کنید.

{{% blocks/products/pf/agp/code-block title="کد C++ برای تبدیل تصویر به PPT" offSpacer="true" %}}

```cpp

auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto image = pres->get_Images()->AddImage(File::ReadAllBytes(u"image.jpg"));
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 0.0f, 720.0f, 540.0f, image);
pres->Save(u"presentation.ppt", SaveFormat::Ppt);

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="نحوه تبدیل تصویر به PPT با استفاده از Aspose.Slides برای C++ API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="این مراحل برای تبدیل تصویر به PPT در ++C است." >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for C++**](https://products.aspose.com/slides/fa/cpp/) را نصب کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
یک مرجع کتابخانه (وارد کردن کتابخانه) به پروژه ++C خود اضافه کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
فایل های Image منبع را در C++ باز کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
نتیجه را به عنوان فایل PPT ذخیره کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="تبدیل تصویر به سایر فرمت های پشتیبانی شده" subTitle="شما همچنین می توانید تصویر را تبدیل کرده و به فرمت های فایل دیگر ذخیره کنید. همه فرمت های پشتیبانی شده را در زیر مشاهده کنید" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/cpp/conversion/image-to-pptx/" name="IMAGE TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/cpp/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/cpp/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/cpp/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/cpp/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/cpp/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/cpp/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/cpp/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/cpp/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}