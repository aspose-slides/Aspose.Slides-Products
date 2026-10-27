---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Wyświetlanie POT w C#
keywords: Wyświetl POT, Otwórz POT, Przeglądarka POT, POT, PowerPoint, API C#, Biblioteka .NET
weight: 6750
url: /pl/net/viewer/pot/ 
description: Wyświetlaj pliki POT w C#. Użyj Aspose.Slides for .NET, aby otwierać pliki prezentacji i zapisywać je jako HTML.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Wyświetlanie POT w C#" h2="API C# do otwierania plików POT i zapisywania ich jako responsywny HTML."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="ODP,OTP,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Wyświetlanie POT za pomocą Aspose.Slides" %}}

Aby wyświetlić pliki POT, użyj API [Aspose.Slides for .NET](https://products.aspose.com/slides/pl/net/) — wydajnego, bogatego w funkcje i łatwego w użyciu API dla C#. Otwórz menedżer pakietów [NuGet](https://www.nuget.org/packages/aspose.slides.net), wyszukaj **Aspose.Slides** i zainstaluj pakiet. Możesz też uruchomić następujące polecenie w konsoli Menedżera pakietów.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Polecenie konsoli Menedżera pakietów" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

Dzięki [**Aspose.Slides for .NET**](/slides/pl/net/) możesz wczytać plik POT i zapisać go jako responsywny HTML za pomocą kilku linii kodu.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Kod C# do wyświetlania POT" >}}
```cs
using var presentation = new Presentation("presentation.pot");

var responsiveHtmlController = new ResponsiveHtmlController();
var htmlOptions = new HtmlOptions
{
    HtmlFormatter = HtmlFormatter.CreateCustomFormatter(responsiveHtmlController)
};

presentation.Save("output.html", SaveFormat.Html, htmlOptions);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak wyświetlić POT w C#" intro="Aspose.Slides pozwala programistom wyświetlać pliki POT za pomocą kilku linii kodu." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zainstaluj **Aspose.Slides for .NET**. Zobacz [**Instalacja**](https://docs.aspose.com/slides/net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Dodaj bibliotekę jako odwołanie w swoim projekcie.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Wczytaj plik `POT` za pomocą klasy `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Utwórz obiekt `ResponsiveHtmlController`, aby uzyskać responsywny wynik HTML.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Utwórz obiekt `HtmlOptions` i ustaw właściwość `HtmlFormatter`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zapisz plik POT jako HTML za pomocą `SaveFormat.Html`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Wymagania systemowe" intro="Aspose.Slides for .NET obsługuje wszystkie popularne systemy operacyjne. Upewnij się, że spełniasz poniższe wymagania." %}}

- Microsoft Windows lub zgodny system operacyjny z .NET Framework, .NET Core, Windows Azure, Mono lub Xamarin
- Środowisko programistyczne, np. Microsoft Visual Studio
- Odwołanie do Aspose.Slides for .NET w projekcie

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/viewer-app label="Zbudowano z Aspose.Slides" title="Przeglądaj pliki POT online" description="Bezpłatna aplikacja Aspose.Slides Viewer została zbudowana z użyciem [Aspose.Slides for .NET](https://products.aspose.com/slides/pl/net/), tego samego API co w powyższym kodzie. Otwórz ją i zobacz, co API potrafi zrobić z Twoimi plikami POT." button="Otwórz Aspose.Slides Viewer" note="[Wszystkie bezpłatne aplikacje](https://products.aspose.app/slides/family)" >}}
- Działa w przeglądarce, nie trzeba niczego instalować.
- Zobacz, jak Aspose.Slides renderuje Twoje pliki, zanim napiszesz kod.
- Prześlij plik POT i od razu przeglądaj jego slajdy.
- Działa na komputerze i telefonie, bez PowerPointa.
{{< /blocks/products/pf/slides-design-update-10-2026/viewer-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="POT" readMoreLink="https://docs.fileformat.com/presentation/pot/" %}}

Pliki z rozszerzeniem .POT to binarne szablony prezentacji Microsoft PowerPoint. Format należy do rodziny formatów plików PowerPoint 97-2003. Pliki POT przechowują układy slajdów, motywy, style, tła, schematy kolorów, czcionki i inne formatowanie wielokrotnego użytku do tworzenia nowych prezentacji.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Wyświetlanie innych plików" subTitle="Możesz też otwierać i wyświetlać prezentacje w innych formatach." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/viewer/odp/" name="ODP" description="Prezentacja OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/viewer/otp/" name="OTP" description="Szablon prezentacji OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/viewer/potm/" name="POTM" description="Szablon programu PowerPoint z obsługą makr" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/viewer/potx/" name="POTX" description="Szablon programu PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/viewer/pps/" name="PPS" description="Pokaz slajdów programu PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/viewer/ppsm/" name="PPSM" description="Pokaz slajdów programu PowerPoint z obsługą makr" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/viewer/ppsx/" name="PPSX" description="Pokaz slajdów programu PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/viewer/ppt/" name="PPT" description="Prezentacja programu PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/viewer/pptm/" name="PPTM" description="Prezentacja programu PowerPoint z obsługą makr" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/viewer/pptx/" name="PPTX" description="Prezentacja programu PowerPoint" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
