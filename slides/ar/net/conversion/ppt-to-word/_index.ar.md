---
lastmod: 2023-04-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: تحويل PPT إلى Word في C#
url: /ar/net/conversion/ppt-to-word/
keywords: تحويل PPT إلى Word ، PPT إلى Word ، PPT إلى DOC ، PowerPoint إلى Word ، C# API ، مكتبة .NET
description: تحويل PPT إلى Word في C#. استخدم .NET Library API لتحويل PowerPoint إلى Word
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="تحويل PPT إلى Word في C#" h2="واجهة برمجة تطبيقات .NET API قوية ومتعددة الأنظمة لتحويل PowerPoint إلى Word باستخدام كود C# في NET Framework أو .NET Core أو Windows Azure أو Mono أو Xamarin الأنظمة الأساسية" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تحويل PowerPoint إلى Word في C#" variant="code" %}}

يمكنك تحويل PPT إلى Word بسرعة باستخدام بضعة أسطر من التعليمات البرمجية

{{< blocks/products/pf/slides-design-update-10-2026/code title="C# لتحويل PowerPoint إلى Word" >}}
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
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تحويل PowerPoint إلى Word باستخدام Aspose.Slides و Aspose.Words" %}}

[** Aspose.Slides for .NET **](https://products.aspose.com/slides/ar/net/) و [** Aspose.Words for .NET **](https: //products.aspose. com / words / net /) هي مكتبات .NET قوية تستخدم لمعالجة وتحويل عروض PowerPoint التقديمية ومستندات Word والملفات الأخرى. عندما تقوم بتحويل PowerPoint إلى Word ، فأنت تقوم بشكل أساسي بنقل محتويات شرائح العرض التقديمي إلى صفحات في مستند Word.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="كيفية تحويل PPT إلى Word" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ثبّت ** Aspose.Slides for .NET ** و ** Aspose.Words for .NET **{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}أضف المكتبتين كمراجع في مشروعك.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم بإنشاء مثيل لفئة العرض التقديمي وفئة المستند.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم بتحميل العرض التقديمي PPT الذي تريد تحويله إلى Word.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم بإنشاء صور ونصوص بناءً على محتويات الشرائح.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}احفظ مستند Word الناتج.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="محول مجاني على الإنترنت"
  description="[كيفية تحويل PPT إلى HTML في Python](https://products.aspose.com/slides/ar/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="التحويلات المدعومة الأخرى" subTitle="يمكنك أيضًا تحويل PowerPoint إلى ملفات بتنسيقات أخرى" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/conversion/ppt-to-jpeg/" name="PPT TO JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/conversion/ppt-to-emf/" name="PPT TO EMF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/conversion/ppt-to-gif/" name="PPT TO GIF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
