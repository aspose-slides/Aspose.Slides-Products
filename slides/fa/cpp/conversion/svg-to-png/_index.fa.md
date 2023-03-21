---
title: SVG را در C++ به PNG تبدیل کنید
url: /fa/cpp/conversion/svg-to-png/
keywords: SVG به PNG، تبدیل SVG به PNG، C++ API، C++ Library، SVG، PNG
description: SVG را در C++ به PNG تبدیل کنید. از C++ library API برای تبدیل فایل‌های SVG به PNG استفاده کنید
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="SVG را در C++ به PNG تبدیل کنید" h2="کتابخانه C++ پرسرعت و چند پلتفرمی که به توسعه برنامه‌های کاربردی با قابلیت ایجاد، ادغام، بازرسی یا تبدیل فایل‌های ارائه Microsoft PowerPoint و OpenOffice بدون استفاده از هیچ نرم‌افزاری مانند Microsoft یا Open Office، Adobe PDF کمک می‌کند." >}}

{{% blocks/products/pf/feature-page-section h2="SVG را در C++ به PNG تبدیل کنید" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/fa/cpp/) یک کتابخانه قدرتمند C++ برای ایجاد و دستکاری فایل های ارائه است. علاوه بر این، راه‌های انعطاف‌پذیری برای تبدیل SVG به PNG ارائه می‌کند. با استفاده از **Aspose.Slides برای C++**، هر برنامه‌نویس یا برنامه‌ای می‌تواند فایل‌های SVG را تنها با چند خط کد C++ به PNG تبدیل کند.

Aspose.Slides برای C++ به عنوان یک API مدرن برای پردازش اسناد، فایل‌های SVG را به فرمت‌های فایل PNG صادر می‌کند. کتابخانه پاورپوینت Aspose به شما امکان می دهد SVG را به PNG و بسیاری از فرمت های فایل دیگر تبدیل کنید.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="با استفاده از C++ SVG را به PNG تبدیل کنید" %}}
برای تبدیل SVG به PNG، باید Presentation را از فایل SVG ایجاد کنید و آن را به عنوان PNG ذخیره کنید.

{{% blocks/products/pf/agp/code-block title="کد C++ برای تبدیل SVG به PNG" offSpacer="true" %}}

```cpp

auto pres = System::MakeObject<Presentation>();
System::String svgContent = System::IO::File::ReadAllText(svgPath);
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(svgContent);
System::SharedPtr<IPPImage> ppImage = pres->get_Images()->AddImage(svgImage);
pres->get_Slides()->idx_get(0)->get_Shapes()->AddPictureFrame(Aspose::Slides::ShapeType::Rectangle, 0.0f, 0.0f, 
    static_cast<float>(ppImage->get_Width()), 
    static_cast<float>(ppImage->get_Height()), ppImage);
for (int32_t i = 0; i < pres->get_Slides()->get_Count(); i++)
{
    // Control hidden slides (do not render hidden slides)
    if (pres->get_Slides()->idx_get(i)->get_Hidden())
    {
        continue;
    }
    
    // Convert slide to a Bitmap object
    System::SharedPtr<Bitmap> bmp = pres->get_Slides()->idx_get(i)->GetThumbnail(2.f, 2.f);

    // Create file name for an image
    System::String outputFilePath = Path::Combine(outputDir, System::String(u"Slide_") + i + u".png");
    
    // Save the image in PNG format
    bmp->Save(outputFilePath, ImageFormat::get_Png());
}

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="نحوه تبدیل SVG به PNG با استفاده از Aspose.Slides for C++ API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="این مراحل برای تبدیل SVG به PNG در C++ است." >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for C++**](https://products.aspose.com/slides/fa/cpp/) را نصب کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
یک مرجع کتابخانه (وارد کردن کتابخانه) به پروژه ++C خود اضافه کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
فایل های منبع SVG را در C++ باز کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
نتیجه را به عنوان فایل PNG ذخیره کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="مبدل آنلاین رایگان" sectionDescription="[نحوه تبدیل PPT به HTML در پایتون](https://products.aspose.com/slides/fa/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="تبدیل SVG به فرمت های دیگر پشتیبانی شده" subTitle="همچنین می‌توانید SVG را تبدیل کنید و در قالب‌های دیگر ذخیره کنید. تمام فرمت های پشتیبانی شده را در زیر مشاهده کنید" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}