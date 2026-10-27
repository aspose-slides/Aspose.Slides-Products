---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Scal pliki POTM przez .NET
weight: 4860
url: /pl/net/merger/potm/ 
description: Kod źródłowy C# do łączenia dokumentów POTM na platformach .NET Framework, .NET Core, Windows Azure, Mono lub Xamarin.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Scal formaty POTM w C#" h2="Natywne i wysokowydajne łączenie dokumentów POTM przy użyciu Aspose.Slides po stronie serwera dla interfejsów API .NET, bez użycia jakiegokolwiek oprogramowania, takiego jak Microsoft lub Open Office, Adobe PDF."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="ODP,OTP,POT,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Jak scalić plik POTM za pomocą C#" %}}

Aby scalić plik POTM, użyjemy
 [Aspose.Slides dla .NET](https://products.aspose.com/slides/pl/net)
 API, które jest bogatym w funkcje, potężnym i łatwym w użyciu interfejsem do manipulacji dokumentami i łączenia API dla platformy C#. otwarty
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 menedżer pakietów, szukaj
 **Aspose.Slajdy**
 i zainstaluj. Możesz również użyć następującego polecenia z konsoli Menedżera pakietów.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Komenda" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Scal pliki POTM — C#" >}}
```cs
var ps1 = new Presentation("presen1.potm");
    var ps2 = new Presentation("presen2.pptx");
    
    //merged Presentation 
    var mp = new Presentation("template.pptx");
    while (mp.Slides.Count > 0){
        mp.Slides.RemoveAt(0);
    }
    // master slide
    var ms = mp.Masters[0];
    
    // The first POTM presentation is added with its own styles.
    foreach (var slide in ps1.Slides){
        mp.Slides.AddClone(slide);
    }
    
    // The second PPTX presentation is added with template presentation styles using.
    foreach (var slide in ps2.Slides){
        mp.Slides.AddClone(slide, ms, true);
    }
    
    // It is possible to save the merged presentation to any supported format.
    mp.Save("mp.pptx", SaveFormat.Pptx);
    mp.Save("mp.pptx", SaveFormat.Pdf);  

    

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Kroki scalania plików POTM w C#" intro="Podstawowe łączenie i łączenie dokumentów z interfejsami API [Aspose.Slides for .NET](https://products.aspose.com/slides/pl/net) można wykonać za pomocą zaledwie kilku wierszy kodu." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Załaduj wszystkie pliki POTM z pełną ścieżką.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Stwórz jeden dokument jako plik podstawowy{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Wywołaj odpowiednią metodę łączenia i scalania plików jeden po drugim.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Wywołaj metodę Save() i przekaż nazwę pliku (pełna ścieżka) oraz format (POTM) jako parametr.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Teraz możesz otworzyć i używać pliku POTM w Microsoft Office, Adobe PDF lub dowolnym innym kompatybilnym programie.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="wymagania systemowe" intro="Nasze interfejsy API są obsługiwane na wszystkich głównych platformach i systemach operacyjnych. Przed wykonaniem poniższego kodu upewnij się, że masz w systemie następujące wymagania wstępne." %}}

- Microsoft Windows lub kompatybilny system operacyjny z platformami .NET Framework, .NET Core, Windows Azure, Mono lub Xamarin
- Środowisko programistyczne, takie jak Microsoft Visual Studio — Aspose.Slides for .NET DLL, do którego odwołuje się Twój projekt — Zainstaluj z NuGet za pomocą przycisku Pobierz powyżej

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="merger" extension=""
  title="Scal pliki PDF online"
  description="[Jak scalić PDF w Pythonie](https://products.aspose.com/slides/pl/python-net/merge/pdf/)" >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="POTM" readMoreLink="https://docs.fileformat.com/presentation/potm/" %}}

Pliki z rozszerzeniem `.POTM` to szablony Microsoft PowerPoint z obsługą makr, wprowadzone w PowerPoint 2007. Mogą przechowywać ustawienia prezentacji wielokrotnego użytku, takie jak układy, style, tła, palety kolorów, czcionki, domyślne formatowanie i makra VBA. PowerPoint 2007 i nowsze wersje mogą otwierać i edytować pliki POTM.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Inne obsługiwane formaty scalania" subTitle="Używając C#, można również łączyć wiele innych formatów plików, w tym." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/merger/odp/" name="ODP" description="Format prezentacji OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/merger/otp/" name="OTP" description="Standardowy format OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/merger/pot/" name="POT" description="Pliki szablonów programu Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/merger/potx/" name="POTX" description="Prezentacja szablonu Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/merger/pps/" name="PPS" description="Pokaz slajdów programu PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/merger/ppsm/" name="PPSM" description="Pokaz slajdów z obsługą makr" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/merger/ppsx/" name="PPSX" description="Pokaz slajdów programu PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/merger/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/merger/pptm/" name="PPTM" description="Plik prezentacji z obsługą makr" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/merger/pptx/" name="PPTX" description="Otwórz format prezentacji XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
