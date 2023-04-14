---
title: تبدیل PPT به Word در سی شارپ
url: /fa/net/conversion/ppt-to-word/
keywords: تبدیل PPT به Word، PPT به Word، PPT به DOC، PowerPoint به Word، C# API، کتابخانه دات نت
description: تبدیل PPT به Word در سی شارپ. برای تبدیل پاورپوینت به ورد از .NET library API استفاده کنید
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="تبدیل PPT به Word در سی شارپ" h2="API قدرتمند کراس پلتفرم دات نت برای تبدیل پاورپوینت به ورد با استفاده از کد سی شارپ در NET Framework، .NET Core، Windows Azure، Mono یا Xamarin" >}}

{{% blocks/products/pf/feature-page-section h2="با استفاده از Aspose.Slides و Aspose.Words پاورپوینت را به ورد تبدیل کنید" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/fa/net/) و [**Aspose.Words for .NET**](https://products.aspose. com/words/net/) کتابخانه های قدرتمند دات نت هستند که برای دستکاری و تبدیل ارائه های پاورپوینت، اسناد Word و سایر فایل ها استفاده می شوند. هنگامی که پاورپوینت را به Word تبدیل می کنید، اساساً محتوای اسلایدهای ارائه را به صفحات یک سند Word منتقل می کنید.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="تبدیل پاورپوینت به ورد در سی شارپ" %}}
تنها با چند خط کد می توانید سریعاً PPT را به Word تبدیل کنید

{{% blocks/products/pf/agp/code-block title="کد سی شارپ برای تبدیل پاورپوینت به ورد" offSpacer="true" %}}
```cs
using var presentation = new Presentation();
var doc = new Document();
var builder = new DocumentBuilder(doc);
foreach (var slide in presentation.Slides)
{
    // generates and inserts slide image
    using var bitmap = slide.GetThumbnail(1, 1);
    using var stream = new MemoryStream();
    bitmap.Save(stream, ImageFormat.Png);
    stream.Seek(0, SeekOrigin.Begin);
    using var skBitmap = SKBitmap.Decode(stream);
    builder.InsertImage(skBitmap);

    // inserts slide texts
    foreach (var shape in slide.Shapes)
    {
        if (shape is AutoShape autoShape)
        {
            builder.Writeln(autoShape.TextFrame.Text);
        }
    }

    builder.InsertBreak(BreakType.PageBreak);
}
doc.Save("document.docx");
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="نحوه تبدیل PPT به Word" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
**Aspose.Slides را برای NET** و **Aspose.Words را برای NET** نصب کنید. 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
دو کتابخانه را به عنوان مرجع در پروژه خود اضافه کنید.
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




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="مبدل آنلاین رایگان" sectionDescription="[نحوه تبدیل PPT به HTML در پایتون](https://products.aspose.com/slides/fa/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="سایر تبدیل های پشتیبانی شده" subTitle="همچنین می توانید پاورپوینت را به فایل هایی با فرمت های دیگر تبدیل کنید" >}}


{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/net/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/net/conversion/ppt-to-jpeg/" name="PPT TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/net/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/net/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/net/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/net/conversion/ppt-to-emf/" name="PPT TO EMF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/net/conversion/ppt-to-gif/" name="PPT TO GIF" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}