---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konwertuj PPTM na SVG za pomocą C#
weight: 740
url: /pl/net/conversion/pptm-to-svg/ 
description: Przykładowy kod konwersji PPTM do SVG C#. Użyj przykładowego kodu API dla plików wsadowych PPTM do konwersji SVG w VB.NET, Asp.NET lub dowolnej aplikacji opartej na .NET.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konwertuj PPTM na SVG za pomocą C#" h2="Eksportuj pliki PowerPoint® PPTM do SVG na platformach .NET Framework, .NET Core, Windows Azure, Mono lub Xamarin"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Jak przekonwertować PPTM na SVG za pomocą C#" %}}

Aby przekonwertować PPTM do SVG, użyjemy
 [Aspose.Slides dla .NET](https://products.aspose.com/slides/pl/net)
 API, który jest bogatym w funkcje, wydajnym i łatwym w użyciu interfejsem API do manipulacji i konwersji dokumentów dla platformy C#. otwarty
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 menedżer pakietów, szukaj
 Aspose.Slajdy
 i zainstaluj. Możesz również użyć następującego polecenia z konsoli Menedżera pakietów.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Polecenie konsoli menedżera pakietów" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Ten przykładowy kod pokazuje konwersję PPTM do SVG C#" >}}
```cs
using (Presentation pres = new Presentation("template.pptm"))
{
    for (var index = 0; index < pres.Slides.Count; index++)
    {
        ISlide slide = pres.Slides[index];

        using (FileStream fileStream = new FileStream($"slide-{index}.svg", FileMode.Create, FileAccess.Write))
        {
            slide.WriteAsSvg(fileStream);   
        }
    }
} 
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Kroki, aby przekonwertować PPTM do SVG za pomocą C#" intro="Programiści .NET mogą łatwo ładować i konwertować pliki PPTM do SVG w zaledwie kilku linijkach kodu." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Załaduj plik PPTM z instancją klasy Presentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Wywołaj metodę Save, określając ścieżkę pliku wyjściowego i SaveFormat.Svg jako parametry{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Plik SVG zostanie zapisany pod określoną ścieżką{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="wymagania systemowe" intro="Przed uruchomieniem przykładowego kodu źródłowego konwersji platformy .NET upewnij się, że masz następujące wymagania wstępne." %}}

- Microsoft Windows lub kompatybilny system operacyjny z platformami .NET Framework, .NET Core, Windows Azure, Mono lub Xamarin.
- Środowisko programistyczne, takie jak Microsoft Visual Studio.
- Aspose.Slides dla .NET DLL, do której odwołuje się Twój projekt.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Darmowa aplikacja do konwersji PPTM do SVG"
  description="[Wypróbuj naszą bezpłatną aplikację Editor](https://products.aspose.app/slides/editor/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Inne obsługiwane konwersje" subTitle="Możesz także przekonwertować PPTM na wiele innych formatów plików, w tym kilka wymienionych poniżej." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/conversion/pptm-to-bmp/" name="PPTM TO BMP" description="Bitmapa" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/conversion/pptm-to-emf/" name="PPTM TO EMF" description="Ulepszony format metapliku" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/conversion/pptm-to-gif/" name="PPTM TO GIF" description="Graficzny format wymiany" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/conversion/pptm-to-html/" name="PPTM TO HTML" description="hipertekstowy język znaczników" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/conversion/pptm-to-jpeg/" name="PPTM TO JPEG" description="Obraz JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/conversion/pptm-to-odp/" name="PPTM TO ODP" description="Format prezentacji OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/conversion/pptm-to-otp/" name="PPTM TO OTP" description="Standardowy format OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/conversion/pptm-to-pdf/" name="PPTM TO PDF" description="format dokumentu przenośnego" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/conversion/pptm-to-png/" name="PPTM TO PNG" description="Przenośna Grafika Sieciowa" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/conversion/pptm-to-pot/" name="PPTM TO POT" description="Pliki szablonów programu Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/conversion/pptm-to-potm/" name="PPTM TO POTM" description="Plik szablonu programu Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/conversion/pptm-to-potx/" name="PPTM TO POTX" description="Prezentacja szablonu Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/conversion/pptm-to-pps/" name="PPTM TO PPS" description="Pokaz slajdów programu PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/conversion/pptm-to-ppsm/" name="PPTM TO PPSM" description="Pokaz slajdów z obsługą makr" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/conversion/pptm-to-ppsx/" name="PPTM TO PPSX" description="Pokaz slajdów programu PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/conversion/pptm-to-ppt/" name="PPTM TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/conversion/pptm-to-pptx/" name="PPTM TO PPTX" description="Otwórz format prezentacji XML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/conversion/pptm-to-swf/" name="PPTM TO SWF" description="Format SWF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/conversion/pptm-to-tiff/" name="PPTM TO TIFF" description="Oznaczony format obrazu" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/conversion/pptm-to-xps/" name="PPTM TO XPS" description="Specyfikacje papieru XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
