---
title: PNG را در C++ به PPTX تبدیل کنید
url: /fa/cpp/conversion/png-to-pptx/
keywords: تبدیل PNG به PPTX، PNG به PPTX، پاورپوینت، PNG، PPTX، C++ API، کتابخانه C++
description: PNG را در C++ به PPTX تبدیل کنید. از C++ library API برای تبدیل تصاویر PNG به پاورپوینت استفاده کنید
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="PNG را در C++ به PPTX تبدیل کنید" h2="API چند پلتفرمی قدرتمند C++ برای تبدیل PNG به PPTX با استفاده از کد C++" >}}

{{% blocks/products/pf/feature-page-section h2="با استفاده از Aspose.Slides PNG را به PPTX تبدیل کنید" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/fa/cpp/) یک کتابخانه قدرتمند ++C است که برای ایجاد، تبدیل، و دستکاری ارائه‌های پاورپوینت، فایل‌های PDF، اسناد HTML و موارد دیگر استفاده می‌شود. فایل ها. وقتی PNG را به PPTX تبدیل می کنید، اساساً در حال ایجاد یک ارائه پاورپوینت هستید که حاوی اسلایدهایی بر اساس تصاویر PNG است.

{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="PNG را در C++ به PPTX تبدیل کنید" %}}
با استفاده از [**Aspose.Slides for C++**](https://products.aspose.com/slides/fa/cpp/)، می توانید تنها با چند خط کد، تصویر PNG را به ارائه پاورپوینت تبدیل کنید:

{{% blocks/products/pf/agp/code-block title="کد C++ برای تبدیل PNG به PPTX" offSpacer="true" %}}
```cpp
auto pres = System::MakeObject<Presentation>();

auto slide = pres->get_Slides()->idx_get(0);
auto image = pres->get_Images()->AddImage(File::ReadAllBytes(u"image.png"));
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 0.0f, 720.0f, 540.0f, image);

pres->Save(u"pres.pptx", SaveFormat::Pptx);
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="نحوه تبدیل PNG به PPTX در ++C" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
**Aspose.Slides را برای C++** نصب کنید. [**نصب**](https://docs.aspose.com/slides/cpp/installation/) را ببینید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
کتابخانه را به عنوان مرجع در پروژه خود اضافه کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
یک نمونه از کلاس Presentation ایجاد کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
تصویر PNG را که می خواهید به PPTX تبدیل کنید بارگیری کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
فایل حاصل را به عنوان یک ارائه PPTX ذخیره کنید.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="مبدل آنلاین رایگان" sectionDescription="[نحوه تبدیل PPT به HTML در پایتون](https://products.aspose.com/slides/fa/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="سایر تبدیل های پاورپوینت پشتیبانی شده" subTitle="همچنین می توانید فایل ها را با فرمت های دیگر به پاورپوینت تبدیل کنید" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/cpp/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/cpp/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/cpp/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/cpp/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/cpp/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/cpp/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/cpp/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}