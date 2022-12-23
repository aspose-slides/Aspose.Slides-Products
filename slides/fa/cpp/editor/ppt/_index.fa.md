---
title: PPT را در C++ ویرایش کنید
url: /fa/cpp/editor/ppt/
keywords: ویرایش PPT، ویرایش پاورپوینت، PPT، پاورپوینت، C++ API، کتابخانه C++
description: PPT را در C++ ویرایش کنید. از C++ library API برای ویرایش ارائه پاورپوینت استفاده کنید
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="PPT را در C++ ویرایش کنید" h2="کتابخانه C++ پرسرعت و کراس پلتفرم برای ویرایش PPT با استفاده از کد C++" >}}

{{% blocks/products/pf/feature-page-section h2="PPT را با استفاده از Aspose.Slides ویرایش کنید" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/fa/cpp/) یک کتابخانه قدرتمند C++ است که برای دستکاری و ویرایش ارائه ها استفاده می شود. شما می توانید یک ارائه PPT را با افزودن یک خط متن جدید به آن ویرایش کنید. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="PPT را در C++ ویرایش کنید" %}}
با استفاده از [**Aspose.Slides for C++**](https://products.aspose.com/slides/fa/cpp/)، می توانید تنها با چند خط کد، یک خط متن جدید به سند PPT اضافه کنید.

{{% blocks/products/pf/agp/code-block title="کد C++ برای ویرایش PPT" offSpacer="true" %}}
```cpp

auto pres = System::MakeObject<Presentation>(u"pres.ppt");

auto slide = pres->get_Slides()->idx_get(0);
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 50.0f);
shape->get_TextFrame()->set_Text(u"New text");

pres->Save(u"pres.pdf", SaveFormat::Ppt);
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="نحوه ویرایش PPT در C++" >}}


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
ارائه PPT را که می خواهید ویرایش کنید بارگیری کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
یک خط جدید از متن اضافه کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
فایل پاورپوینت تغییر یافته را ذخیره کنید.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="فایل های دیگر را ویرایش کنید" subTitle="همچنین می توانید فایل ها را با فرمت های دیگر ویرایش کنید" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/cpp/editor/pdf/" name="Edit PDF" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/cpp/editor/html/" name="Edit HTML" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}