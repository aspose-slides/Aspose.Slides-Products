---
title: HTML را در پایتون ویرایش کنید
url: /fa/python-net/editor/html/
keywords: HTML، HTML، Python API، Python Library را ویرایش کنید
description: HTML را در پایتون ویرایش کنید. از API کتابخانه پایتون برای ویرایش فایل HTML استفاده کنید
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="HTML را در پایتون ویرایش کنید" h2="کتابخانه Python با سرعت بالا و کراس پلتفرم برای ویرایش HTML با استفاده از کد پایتون" >}}

{{% blocks/products/pf/feature-page-section h2="HTML را با استفاده از Aspose.Slides ویرایش کنید" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/fa/python-net/) یک کتابخانه قدرتمند پایتون است که برای دستکاری و ویرایش ارائه ها، اسناد HTML و سایر فایل ها استفاده می شود. . شما می توانید یک سند HTML را با افزودن یک خط متن جدید به آن ویرایش کنید. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="HTML را در پایتون ویرایش کنید" %}}
با استفاده از [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/fa/python-net/)، می توانید تنها با چند خط یک متن جدید به سند HTML اضافه کنید. خطوط کد

{{% blocks/products/pf/agp/code-block title="کد پایتون برای ویرایش HTML" offSpacer="true" %}}
```python

import aspose.slides as slides

with slides.Presentation() as pres:
    pres.slides.remove_at(0)
    with open("page.html", "rt") as stream:
        data = stream.read()
    pres.slides.add_from_html(data)

    shape = pres.slides[0].shapes.add_auto_shape(slides.ShapeType.RECTANGLE, 10, 10, 100, 50)
    shape.text_frame.text = "New text"

    pres.save("page.html", slides.export.SaveFormat.HTML5)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="نحوه ویرایش HTML در پایتون" >}}


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
سند HTML را که می خواهید ویرایش کنید بارگیری کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
یک خط جدید از متن اضافه کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
فایل HTML تغییر یافته را ذخیره کنید.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="فایل های دیگر را ویرایش کنید" subTitle="همچنین می توانید فایل ها را با فرمت های دیگر ویرایش کنید" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/editor/pdf/" name="Edit PDF" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}