---
title: PNG را در C++ به PDF تبدیل کنید
url: /fa/cpp/conversion/png-to-pdf/
keywords: PNG به PDF، تبدیل PNG به PDF، C++ API، C++ Library، PNG، PDF
description: PNG را در C++ به PDF تبدیل کنید. از C++ library API برای تبدیل فایل‌های PNG به PDF استفاده کنید
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="PNG را در C++ به PDF تبدیل کنید" h2="کتابخانه C++ پرسرعت و چند پلتفرمی که به توسعه برنامه‌های کاربردی با قابلیت ایجاد، ادغام، بازرسی یا تبدیل فایل‌های ارائه Microsoft PowerPoint و OpenOffice بدون استفاده از هیچ نرم‌افزاری مانند Microsoft یا Open Office، Adobe PDF کمک می‌کند." >}}

{{% blocks/products/pf/feature-page-section h2="PNG را در C++ به PDF تبدیل کنید" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/fa/cpp/) یک کتابخانه قدرتمند C++ برای ایجاد و دستکاری فایل های ارائه است. علاوه بر این، راه‌های انعطاف‌پذیری برای تبدیل PNG به PDF ارائه می‌کند. با استفاده از **Aspose.Slides برای C++**، هر برنامه‌نویس یا برنامه‌ای می‌تواند فایل‌های PNG را تنها با چند خط کد C++ به PDF تبدیل کند.

Aspose.Slides برای C++ به عنوان یک API مدرن برای پردازش اسناد، فایل‌های PNG را به فرمت‌های فایل PDF صادر می‌کند. کتابخانه پاورپوینت Aspose به شما امکان می دهد PNG را به PDF و بسیاری از فرمت های فایل دیگر تبدیل کنید.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="با استفاده از C++ PNG را به PDF تبدیل کنید" %}}
برای تبدیل PNG به PDF، باید Presentation را از فایل PNG ایجاد کنید و آن را به عنوان PDF ذخیره کنید.

{{% blocks/products/pf/agp/code-block title="کد C++ برای تبدیل PNG به PDF" offSpacer="true" %}}

```cpp

auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto image = pres->get_Images()->AddImage(File::ReadAllBytes(u"image.png"));
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pres->Save(u"pres.pdf", SaveFormat::Pdf);

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="نحوه تبدیل PNG به PDF با استفاده از Aspose.Slides for C++ API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="این مراحل برای تبدیل PNG به PDF در C++ است." >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for C++**](https://products.aspose.com/slides/fa/cpp/) را نصب کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
یک مرجع کتابخانه (وارد کردن کتابخانه) به پروژه ++C خود اضافه کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
فایل های منبع PNG را در C++ باز کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
نتیجه را به عنوان فایل PDF ذخیره کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="مبدل آنلاین رایگان" sectionDescription="[نحوه تبدیل PPT به HTML در پایتون](https://products.aspose.com/slides/fa/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="تبدیل PNG به فرمت های دیگر پشتیبانی شده" subTitle="همچنین می‌توانید PNG را تبدیل کنید و در قالب‌های دیگر ذخیره کنید. تمام فرمت های پشتیبانی شده را در زیر مشاهده کنید" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/cpp/conversion/png-to-jpg/" name="PNG TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/cpp/conversion/png-to-svg/" name="PNG TO SVG" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}