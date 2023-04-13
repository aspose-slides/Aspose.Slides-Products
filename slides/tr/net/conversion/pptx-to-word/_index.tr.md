---
title: PPTX'i C# dilinde Word'e dönüştürün
url: /tr/net/conversion/pptx-to-word/
keywords: PPTX'i Word'e, PPTX'i Word'e, PPTX'i DOC'a, PowerPoint'i Word'e, C# API'sini, .NET Library'ye dönüştürün
description: PPTX'i C# dilinde Word'e dönüştürün. PowerPoint'i Word'e dönüştürmek için .NET kitaplığı API'sini kullanın
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="PPTX'i C# dilinde Word'e dönüştürün" h2="NET Framework, .NET Core, Windows Azure, Mono veya Xamarin Platformlarında C# kodunu kullanarak PowerPoint'i Word'e dönüştürmek için güçlü çapraz platform .NET API'si" >}}

{{% blocks/products/pf/feature-page-section h2="Aspose.Slides ve Aspose.Words kullanarak PowerPoint'i Word'e dönüştürün" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/tr/net/) ve [**Aspose.Words for .NET**](https://products.aspose. com/words/net/), PowerPoint sunumlarını, Word belgelerini ve diğer dosyaları değiştirmek ve dönüştürmek için kullanılan güçlü .NET kitaplıklarıdır. PowerPoint'i Word'e dönüştürdüğünüzde, aslında bir sunumun slaytlarının içeriğini bir Word belgesindeki sayfalara taşıyorsunuz.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="PowerPoint'i C# dilinde Word'e dönüştürün" %}}
PPTX'i yalnızca birkaç satır kodla hızlı bir şekilde Word'e dönüştürebilirsiniz.

{{% blocks/products/pf/agp/code-block title="PowerPoint'i Word'e dönüştürmek için C# kodu" offSpacer="true" %}}
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




{{< blocks/products/pf/feature-page-section  h2="PPTX'i Word'e dönüştürme" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
**Aspose.Slides for .NET** ve **Aspose.Words for .NET**'i yükleyin 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
İki kitaplığı projenize referans olarak ekleyin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Presentation sınıfı ve Doc sınıfının bir örneğini oluşturun.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Word'e dönüştürmek istediğiniz PPTX sunumunu yükleyin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Slaytların içeriğine göre resimler ve metinler oluşturun.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ortaya çıkan Word belgesini kaydedin.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Ücretsiz Çevrimiçi Dönüştürücü" sectionDescription="[Python'da PPT'yi HTML'ye Dönüştürme](https://products.aspose.com/slides/tr/en/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="PowerPoint'i başka biçimlerdeki dosyalara da dönüştürebilirsiniz." >}}


{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/net/conversion/pptx-to-html/" name="PPTX TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/net/conversion/pptx-to-jpeg/" name="PPTX TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/net/conversion/pptx-to-png/" name="PPTX TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/net/conversion/pptx-to-svg/" name="PPTX TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/net/conversion/pptx-to-bmp/" name="PPTX TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/net/conversion/pptx-to-emf/" name="PPTX TO EMF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/net/conversion/pptx-to-gif/" name="PPTX TO GIF" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}