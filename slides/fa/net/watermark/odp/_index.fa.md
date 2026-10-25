---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: افزودن واترمارک به ارائه‌های ODP با C#
url: /fa/net/watermark/odp/
description: با Aspose.Slides for .NET در C# واترمارک متنی و تصویری به ارائه‌های ODP اضافه کنید.
keywords: افزودن واترمارک به ODP، افزودن واترمارک متنی به ODP، افزودن واترمارک تصویری به ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="افزودن واترمارک به ارائه ODP با C#" h2="برنامه‌های .NET بسازید که واترمارک متنی یا تصویری را در فایل‌های ارائه درج می‌کنند." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="افزودن واترمارک به ارائه ODP از طریق C#" variant="code" %}}

با [Aspose.Slides for .NET](/slides/fa/net/) می‌توانید واترمارک متنی و تصویری به ارائه‌های ODP اضافه کنید. یک شکل واترمارک به اسلاید اصلی اضافه کنید تا واترمارک در اسلایدهایی که از آن اسلاید اصلی استفاده می‌کنند نمایش داده شود.

{{< blocks/products/pf/slides-design-update-10-2026/code title="افزودن واترمارک متنی به ODP با C#" >}}
```cs
using var presentation = new Presentation("presentation.odp");

var masterSlide = presentation.Masters[0];
var watermarkShape = masterSlide.Shapes.AddAutoShape(ShapeType.Rectangle, 100, 100, 400, 120);
var watermarkTextFrame = watermarkShape.AddTextFrame("Watermark");
watermarkTextFrame.Paragraphs[0].Portions[0].PortionFormat.FontHeight = 48;

presentation.Save("watermarked-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="افزودن واترمارک تصویری به ارائه ODP با C#" >}}
```cs
using var presentation = new Presentation("presentation.odp");

var imageData = File.ReadAllBytes("watermark.png");
var watermarkImage = presentation.Images.AddImage(imageData);
var masterSlide = presentation.Masters[0];
var watermarkShape = masterSlide.Shapes.AddAutoShape(ShapeType.Rectangle, 100, 100, 300, 200);

watermarkShape.FillFormat.FillType = FillType.Picture;
watermarkShape.FillFormat.PictureFillFormat.Picture.Image = watermarkImage;
watermarkShape.FillFormat.PictureFillFormat.PictureFillMode = PictureFillMode.Stretch;

presentation.Save("image-watermarked-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="نحوه افزودن واترمارک به ODP با C#" intro="برای افزودن واترمارک متنی یا تصویری به فایل‌های ODP این مراحل را دنبال کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل `ODP` را با کلاس `Presentation` بارگذاری کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}یک اسلاید اصلی از مجموعه `Presentation.Masters` انتخاب کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}متد `AddAutoShape` را برای افزودن شکل واترمارک فراخوانی کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}متد `AddTextFrame` را برای افزودن متن واترمارک فراخوانی کنید یا برای واترمارک تصویری از `AddImage` استفاده کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل دارای واترمارک را با `SaveFormat.Odp` ذخیره کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="ساخته شده با Aspose.Slides" title="افزودن آنلاین واترمارک به فایل‌های ODP" description="برنامه رایگان Aspose.Slides Watermark با [Aspose.Slides for .NET](https://products.aspose.com/slides/fa/net/) ساخته شده است، همان API که در کد بالا استفاده شده است. آن را باز کنید و ببینید API با فایل‌های ODP شما چه کارهایی می‌تواند انجام دهد." button="باز کردن Aspose.Slides Watermark" note="[همه برنامه‌های رایگان](https://products.aspose.app/slides/family)" >}}
- در مرورگر شما اجرا می‌شود، بدون نیاز به نصب.
- پیش از نوشتن کد ببینید Aspose.Slides چگونه واترمارک اضافه می‌کند.
- یک واترمارک متنی یا تصویری به فایل ODP خود اضافه کنید.
- فایل دارای واترمارک را دانلود کنید.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="سایر قالب‌های پشتیبانی‌کننده واترمارک" subTitle="با C# می‌توانید به قالب‌های زیر نیز واترمارک اضافه کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/net/watermark/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/net/watermark/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
