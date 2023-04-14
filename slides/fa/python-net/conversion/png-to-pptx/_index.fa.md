---
title: تبدیل PNG به PPTX در پایتون
url: /fa/python-net/conversion/png-to-pptx/
keywords: تبدیل PNG به PPTX، PNG به PPTX، پاورپوینت، PNG، PPTX، Python API، کتابخانه Python
description: تبدیل PNG به PPTX در پایتون. برای تبدیل تصاویر PNG به پاورپوینت از API کتابخانه Python استفاده کنید
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="تبدیل PNG به PPTX در پایتون" h2="API قدرتمند بین پلتفرمی Python برای تبدیل PNG به PPTX با استفاده از کد پایتون" >}}

{{% blocks/products/pf/feature-page-section h2="با استفاده از Aspose.Slides PNG را به PPTX تبدیل کنید" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/fa/python-net/) یک کتابخانه قدرتمند پایتون است که برای ایجاد، تبدیل و دستکاری ارائه‌های پاورپوینت، فایل‌های PDF، استفاده می‌شود. اسناد HTML و فایل های دیگر. وقتی PNG را به PPTX تبدیل می کنید، اساساً در حال ایجاد یک ارائه پاورپوینت هستید که حاوی اسلایدهایی بر اساس تصاویر PNG است.

{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="تبدیل PNG به PPTX در پایتون" %}}
با استفاده از [**Aspose.Slides برای پایتون از طریق .NET**](https://products.aspose.com/slides/fa/python-net/)، می توانید تصویر PNG را تنها با چند خط کد به ارائه پاورپوینت تبدیل کنید:

{{% blocks/products/pf/agp/code-block title="کد پایتون برای تبدیل PNG به PPTX" offSpacer="true" %}}
```py
import aspose.slides as slides

with slides.Presentation() as pres:
    slide = pres.slides[0]
    with open("img.png", "rb") as in_file:
        image = pres.images.add_image(in_file)
        slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 0, 0, 720, 540, image)
    
    pres.save("pres_with_image.pptx", slides.export.SaveFormat.PPTX)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="نحوه تبدیل PNG به PPTX در پایتون" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Install **Aspose.Slides for Python via .NET**. See [**Installation**](https://docs.aspose.com/slides/python-net/installation/).
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

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}