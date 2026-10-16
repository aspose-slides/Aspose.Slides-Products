---
lastmod: 2023-03-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konwertuj obraz na PPT w C#
url: /pl/net/conversion/image-to-ppt/
keywords: Konwertuj obraz na PPT, obraz na PPT, PowerPoint, obraz, PPT, C# API, bibliotekę .NET
description: Konwertuj obraz na PPT w C#. Użyj interfejsu API biblioteki .NET, aby przekonwertować obraz do programu PowerPoint
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konwertuj obraz na PPT w C#" h2="Potężny, wieloplatformowy interfejs API platformy .NET do konwersji obrazu do formatu PPT przy użyciu kodu C# na platformach NET Framework, .NET Core, Windows Azure, Mono lub Xamarin" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konwertuj obraz na PPT w C#" variant="code" %}}

Używając [**Aspose.Slides for .NET**](https://products.aspose.com/slides/pl/net/), możesz przekonwertować obraz na prezentację PowerPoint za pomocą zaledwie kilku linijek kodu:

{{< blocks/products/pf/slides-design-update-10-2026/code title="Kod C# do konwersji obrazu na PPT" >}}
```cs

using (Presentation pres = new Presentation())
{
    IPPImage image = pres.Images.AddImage(File.ReadAllBytes("image.jpg"));
    pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 0, 720, 540, image);
    pres.Save("Presentation.ppt", SaveFormat.Ppt);
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konwertuj obraz do PPT za pomocą Aspose.Slides" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/pl/net/) to potężna biblioteka .NET używana do tworzenia, konwertowania i manipulowania prezentacjami programu PowerPoint, plikami PDF, dokumentami HTML, i inne pliki. Kiedy konwertujesz obraz do PPT, zasadniczo tworzysz prezentację PowerPoint zawierającą slajdy oparte na tych obrazach.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak przekonwertować obraz na PPT w C#" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zainstaluj **Aspose.Slides dla platformy .NET**. Zobacz [**Instalacja**](https://docs.aspose.com/slides/net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Dodaj bibliotekę jako odniesienie w swoim projekcie.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Utwórz wystąpienie klasy Presentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Załaduj obraz, który chcesz przekonwertować na PPT.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zapisz wynikowy plik jako prezentację PPT.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Darmowy konwerter online"
  description="[Jak przekonwertować PPT na HTML w Pythonie](https://products.aspose.com/slides/pl/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Inne obsługiwane konwersje programu PowerPoint" subTitle="Możesz także konwertować pliki w innych formatach do programu PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/conversion/image-to-pptx/" name="IMAGE TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/conversion/html-to-pptx/" name="HTML TO PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
