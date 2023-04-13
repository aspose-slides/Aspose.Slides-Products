---
title: تبدیل PPT به Word در C++
url: /fa/cpp/conversion/ppt-to-word/
keywords: تبدیل PPT به Word، PPT به Word، PPT به DOC، PowerPoint به Word، C++ API، C++ Library، CPP
description: تبدیل PPT به Word در C++. از C++ library API برای تبدیل پاورپوینت به ورد استفاده کنید
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="تبدیل PPT به Word در C++" h2="API قدرتمند بین پلتفرمی C++ برای تبدیل پاورپوینت به ورد با استفاده از کد C++ بدون Microsoft PowerPoint یا Office" >}}

{{% blocks/products/pf/feature-page-section h2="با استفاده از Aspose.Slides و Aspose.Words پاورپوینت را به ورد تبدیل کنید" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/fa/cpp/) و [**Aspose.Words for C++**](https://products.aspose.com/ word/cpp/) کتابخانه‌های قدرتمند C++ هستند که برای دستکاری و تبدیل ارائه‌های پاورپوینت، اسناد Word و سایر فایل‌ها استفاده می‌شوند. هنگامی که پاورپوینت را به Word تبدیل می کنید، اساساً محتوای اسلایدهای ارائه را به صفحات یک سند Word منتقل می کنید.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="تبدیل پاورپوینت به ورد در سی پلاس پلاس" %}}
تنها با چند خط کد می توانید سریعاً PPT را به Word تبدیل کنید

{{% blocks/products/pf/agp/code-block title="کد C++ برای تبدیل پاورپوینت به ورد" offSpacer="true" %}}
```cpp
auto presentation = MakeObject<Presentation>();
auto doc = MakeObject<Aspose::Words::Document>();
auto builder = MakeObject<Aspose::Words::DocumentBuilder>(doc);

for (const auto& slide : presentation->get_Slides())
{
    // generates and inserts slide image
    auto bitmap = slide->GetThumbnail(1.0f, 1.0f);
    builder->InsertImage(bitmap);

    // inserts slide's texts
    for (const auto& shape : slide->get_Shapes())
    {
        if (ObjectExt::Is<AutoShape>(shape))
        {
            auto autoShape = System::AsCast<AutoShape>(shape);
            builder->Writeln(autoShape->get_TextFrame()->get_Text());
        }
    }

    builder->InsertBreak(Aspose::Words::BreakType::PageBreak);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="نحوه تبدیل PPT به Word" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
**Aspose.Slides را برای C++** و **Aspose.Words را برای C++** نصب کنید. 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
یک نمونه از کلاس Presentation و کلاس Doc ایجاد کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ارائه PPT را که می خواهید به Word تبدیل کنید بارگیری کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
تصاویر و متون را بر اساس محتوای اسلایدها ایجاد کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
سند Word حاصل را ذخیره کنید.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="مبدل آنلاین رایگان" sectionDescription="[نحوه تبدیل PPT به HTML در پایتون](https://products.aspose.com/slides/fa/en/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="سایر تبدیل های پشتیبانی شده" subTitle="همچنین می توانید پاورپوینت را به فایل هایی با فرمت های دیگر تبدیل کنید" >}}


{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/cpp/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/cpp/conversion/ppt-to-jpeg/" name="PPT TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/cpp/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/cpp/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/cpp/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/cpp/conversion/ppt-to-emf/" name="PPT TO EMF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/cpp/conversion/ppt-to-gif/" name="PPT TO GIF" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}