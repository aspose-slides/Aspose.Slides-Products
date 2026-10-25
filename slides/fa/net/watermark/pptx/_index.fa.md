---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: افزودن واترمارک به ارائه‌های PPTX با C#
url: /fa/net/watermark/pptx/
description: با Aspose.Slides for .NET در C# واترمارک متنی و تصویری به ارائه‌های PPTX اضافه کنید.
keywords: افزودن واترمارک به PPTX، افزودن واترمارک متنی به PPTX، افزودن واترمارک تصویری به PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="افزودن واترمارک به ارائه PPTX با C#" h2="برنامه‌های .NET بسازید که واترمارک متنی یا تصویری را در فایل‌های ارائه درج می‌کنند." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="افزودن واترمارک به ارائه PPTX از طریق C#" variant="code" %}}

با [Aspose.Slides for .NET](/slides/fa/net/) می‌توانید واترمارک متنی و تصویری به ارائه‌های PPTX اضافه کنید. یک شکل واترمارک به اسلاید اصلی اضافه کنید تا واترمارک در اسلایدهایی که از آن اسلاید اصلی استفاده می‌کنند نمایش داده شود.

{{< blocks/products/pf/slides-design-update-10-2026/code title="افزودن واترمارک متنی به PPTX با C#" >}}
```cs
using var presentation = new Presentation("presentation.pptx");

var masterSlide = presentation.Masters[0];
var watermarkShape = masterSlide.Shapes.AddAutoShape(ShapeType.Rectangle, 100, 100, 400, 120);
var watermarkTextFrame = watermarkShape.AddTextFrame("Watermark");
watermarkTextFrame.Paragraphs[0].Portions[0].PortionFormat.FontHeight = 48;

presentation.Save("watermarked-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="افزودن واترمارک تصویری به ارائه PPTX با C#" >}}
```cs
using var presentation = new Presentation("presentation.pptx");

var imageData = File.ReadAllBytes("watermark.png");
var watermarkImage = presentation.Images.AddImage(imageData);
var masterSlide = presentation.Masters[0];
var watermarkShape = masterSlide.Shapes.AddAutoShape(ShapeType.Rectangle, 100, 100, 300, 200);

watermarkShape.FillFormat.FillType = FillType.Picture;
watermarkShape.FillFormat.PictureFillFormat.Picture.Image = watermarkImage;
watermarkShape.FillFormat.PictureFillFormat.PictureFillMode = PictureFillMode.Stretch;

presentation.Save("image-watermarked-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="نحوه افزودن واترمارک به PPTX با C#" intro="برای افزودن واترمارک متنی یا تصویری به فایل‌های PPTX این مراحل را دنبال کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل `PPTX` را با کلاس `Presentation` بارگذاری کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}یک اسلاید اصلی از مجموعه `Presentation.Masters` انتخاب کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}متد `AddAutoShape` را برای افزودن شکل واترمارک فراخوانی کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}متد `AddTextFrame` را برای افزودن متن واترمارک فراخوانی کنید یا برای واترمارک تصویری از `AddImage` استفاده کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل دارای واترمارک را با `SaveFormat.Pptx` ذخیره کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="ساخته شده با Aspose.Slides" title="افزودن آنلاین واترمارک به فایل‌های PPTX" description="برنامه رایگان Aspose.Slides Watermark با [Aspose.Slides for .NET](https://products.aspose.com/slides/fa/net/) ساخته شده است، همان API که در کد بالا استفاده شده است. آن را باز کنید و ببینید API با فایل‌های PPTX شما چه کارهایی می‌تواند انجام دهد." button="باز کردن Aspose.Slides Watermark" note="[همه برنامه‌های رایگان](https://products.aspose.app/slides/family)" >}}
- در مرورگر شما اجرا می‌شود، بدون نیاز به نصب.
- پیش از نوشتن کد ببینید Aspose.Slides چگونه واترمارک اضافه می‌کند.
- یک واترمارک متنی یا تصویری به فایل PPTX خود اضافه کنید.
- فایل دارای واترمارک را دانلود کنید.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="سایر قالب‌های پشتیبانی‌کننده واترمارک" subTitle="با C# می‌توانید به قالب‌های زیر نیز واترمارک اضافه کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/net/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/net/watermark/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
