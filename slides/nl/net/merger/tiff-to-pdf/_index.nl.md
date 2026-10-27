---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Voeg TIFF samen met PDF in C#
url: /nl/net/merger/tiff-to-pdf/
keywords: TIFF naar PDF, TIFF naar PDF samenvoegen, TIFF naar PDF, PDF, TIFF, C# API, .NET Library samenvoegen
description: Voeg TIFF samen met PDF in C#. Gebruik de .NET-bibliotheek-API om TIFF en PDF te combineren
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Voeg TIFF samen met PDF in C#" h2="Krachtige platformonafhankelijke .NET API voor het samenvoegen van TIFF- naar PDF-bestanden met behulp van C#-code op NET Framework-, .NET Core-, Windows Azure-, Mono- of Xamarin-platforms" related="JPG,PNG,HTML,IMAGE,PDF,SVG,BMP" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Voeg TIFF samen met PDF in C#" variant="code" %}}

Met [**Aspose.Slides for .NET**](https://products.aspose.com/slides/nl/net/) kunt u snel TIFF naar PDF samenvoegen met slechts een paar regels code

{{< blocks/products/pf/slides-design-update-10-2026/code title="C#-code voor het samenvoegen van TIFF naar PDF" >}}
```cs
using (Presentation pres = new Presentation())
{
    IPPImage tiff1 = pres.Images.AddImage(File.ReadAllBytes("image1.tiff"));
    pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 0, 100, 100, tiff1);

    IPPImage tiff2 = pres.Images.AddImage(File.ReadAllBytes("image2.tiff"));
    pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 200, 100, 100, tiff2);

    pres.Save("MergedFile.pdf", SaveFormat.Pdf);
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Voeg TIFF samen met PDF met behulp van Aspose.Slides" %}}

[**Aspose.Slides voor .NET**](https://products.aspose.com/slides/nl/net/) is een krachtige .NET-bibliotheek die wordt gebruikt om presentaties, pdf's, afbeeldingen, en andere bestanden. Wanneer u TIFF naar PDF samenvoegt, combineert u in feite afbeeldingen om één enkel PDF-bestand te verkrijgen.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="TIFF samenvoegen met PDF in C#" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installeer **Aspose.Slides voor .NET**. Zie [**Installatie**](https://docs.aspose.com/slides/net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Voeg de bibliotheek toe als referentie in uw project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Maak een instantie van de klasse Presentatie.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laad de TIFF-bestanden die u wilt samenvoegen als fotolijsten.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Sla de resulterende PDF op.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/merger-app label="Gebouwd met Aspose.Slides" title="TIFF online samenvoegen tot PDF" description="De gratis app Aspose.Slides Merger is gebouwd met [Aspose.Slides for .NET](https://products.aspose.com/slides/nl/net/), dezelfde API als in de bovenstaande code. Open de app en ontdek wat de API kan met uw eigen TIFF-bestanden." button="Aspose.Slides Merger openen" note="[Alle gratis apps](https://products.aspose.app/slides/family)" >}}
- Werkt in uw browser, niets te installeren.
- Bekijk hoe Aspose.Slides bestanden samenvoegt voordat u code schrijft.
- Upload meerdere TIFF-bestanden en voeg ze samen tot één PDF-bestand.
- Download het samengevoegde resultaat als één bestand.
{{< /blocks/products/pf/slides-design-update-10-2026/merger-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere bestanden samenvoegen" subTitle="Je kunt ook bestanden in andere formaten combineren om een ​​enkel bestand te krijgen" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/merger/jpg-to-jpg/" name="JPG TO JPG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/merger/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/merger/pdf-to-pdf/" name="PDF TO PDF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/merger/png-to-pdf/" name="PNG TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/merger/svg-to-png/" name="SVG TO PNG" >}} 
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/merger/image-to-bmp/" name="IMAGE TO BMP" >}} 
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/merger/html-to-image/" name="HTML TO IMAGE" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
