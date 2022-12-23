---
title: ویرایش PDF در سی شارپ
url: /fa/net/editor/pdf/
keywords: ویرایش PDF، PDF، C# API، کتابخانه دات نت
description: PDF را در سی شارپ ویرایش کنید. برای ویرایش سند PDF از .NET library API استفاده کنید
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="ویرایش PDF در سی شارپ" h2="API قدرتمند کراس پلتفرم دات نت برای ویرایش PDF با استفاده از کد سی شارپ در NET Framework، .NET Core، Windows Azure، Mono یا Xamarin" >}}

{{% blocks/products/pf/feature-page-section h2="PDF را با استفاده از Aspose.Slides ویرایش کنید" %}}

[**Aspose.Slides for.NET**](https://products.aspose.com/slides/fa/net/) یک کتابخانه قدرتمند دات نت است که برای دستکاری و ویرایش ارائه ها، اسناد PDF و فایل های دیگر استفاده می شود. می توانید یک سند PDF را با افزودن یک خط متن جدید به آن ویرایش کنید. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="ویرایش PDF در سی شارپ" %}}
با استفاده از [**Aspose.Slides for .NET**](https://products.aspose.com/slides/fa/net/)، می توانید تنها با چند خط کد، یک خط متن جدید به سند PDF اضافه کنید.

{{% blocks/products/pf/agp/code-block title="کد سی شارپ برای ویرایش PDF" offSpacer="true" %}}
```cs
using (Presentation pres = new Presentation())
{
    pres.Slides.RemoveAt(0); // remove default empty slide
    pres.Slides.AddFromPdf("doc.pdf");

    AutoShape shape = (AutoShape)pres.Slides[0].Shapes[0];
    shape.TextFrame.Text = "New text";

    pres.Save("doc.pdf", SaveFormat.Pdf);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="نحوه ویرایش PDF در سی شارپ" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
**Aspose.Slides را برای NET** نصب کنید. [**نصب**](https://docs.aspose.com/slides/net/installation/) را ببینید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
کتابخانه را به عنوان مرجع در پروژه خود اضافه کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
یک نمونه از کلاس Presentation ایجاد کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
سند PDF را که می خواهید ویرایش کنید بارگیری کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
یک خط جدید از متن اضافه کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
فایل PDF تغییر یافته را ذخیره کنید.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="فایل های دیگر را ویرایش کنید" subTitle="همچنین می توانید فایل ها را با فرمت های دیگر ویرایش کنید" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/net/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/net/editor/html/" name="Edit HTML" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}