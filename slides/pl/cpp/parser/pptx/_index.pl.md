---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 2290
title: Wyodrębnianie tekstu z prezentacji PPTX w C++
url: /pl/cpp/parser/pptx/ 
description: Wyodrębniaj tekst z prezentacji PPTX w C++. Użyj Aspose.Slides for C++ do analizy slajdów, ramek tekstowych, akapitów i fragmentów tekstu.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Analiza prezentacji PPTX w C++" h2="Użyj Aspose.Slides for C++, aby wyodrębniać tekst ze slajdów bez programu Microsoft PowerPoint."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/cpp/"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/"
  related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Analiza pliku PPTX w C++" %}}

Użyj Aspose.Slides for C++, aby analizować pliki prezentacji PPTX i wyodrębniać tekst ze slajdów. API udostępnia tekst slajdów przez `SlideUtil::GetAllTextBoxes`, `ITextFrame`, `IParagraph` i `IPortion`, dzięki czemu możesz odczytać treść bez automatyzacji programu Microsoft PowerPoint. Zainstaluj pakiet [`Aspose.Slides.Cpp`](https://www.nuget.org/packages/Aspose.Slides.Cpp/) z NuGet lub użyj poniższego polecenia w konsoli Menedżera pakietów.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Polecenie" >}}
```powershell
PM> Install-Package Aspose.Slides.Cpp
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Analiza plików PPTX – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");
auto textFrames = SlideUtil::GetAllTextBoxes(presentation->get_Slide(0));

for (auto&& textFrame : textFrames)
{
    for (auto&& paragraph : textFrame->get_Paragraphs())
    {
        for (auto&& portion : paragraph->get_Portions())
        {
            Console::WriteLine(portion->get_Text());
        }
    }
}

presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak analizować pliki PPTX w C++" intro="Wyodrębniaj tekst z plików PPTX za pomocą Aspose.Slides for C++." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Wczytaj plik PPTX za pomocą klasy `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Pobierz obiekty `ITextFrame` z pierwszego slajdu za pomocą `SlideUtil::GetAllTextBoxes`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Przejdź przez obiekty `ITextFrame`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Przejdź przez obiekty `IParagraph` w każdym `ITextFrame`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Przejdź przez obiekty `IPortion` w każdym `IParagraph`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Odczytaj tekst za pomocą `get_Text`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Wymagania systemowe" intro="Aspose.Slides for C++ obsługuje najważniejsze platformy desktopowe i serwerowe. Upewnij się, że Twój projekt spełnia poniższe wymagania." %}}

-  Microsoft Windows, Linux, macOS lub inny zgodny system operacyjny z obsługiwanym środowiskiem uruchomieniowym C++.
-  Biblioteka Aspose.Slides for C++ dodana jako odwołanie w projekcie.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Zbudowano z Aspose.Slides" title="Wyodrębniaj tekst i obrazy online" description="Bezpłatna aplikacja Aspose.Slides Parser została zbudowana z użyciem [Aspose.Slides for C++](https://products.aspose.com/slides/pl/cpp/), tego samego API co w powyższym kodzie. Otwórz ją i zobacz, co API potrafi zrobić z Twoimi plikami PPTX." button="Otwórz Aspose.Slides Parser" note="[Wszystkie bezpłatne aplikacje](https://products.aspose.app/slides/family)" >}}
- Działa w przeglądarce, nie trzeba niczego instalować.
- Zobacz, jak Aspose.Slides odczytuje Twoje pliki, zanim napiszesz kod.
- Prześlij plik PPTX i otrzymaj jego tekst oraz obrazy.
- Pobierz wszystko jako jedno archiwum ZIP.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPTX" readMoreLink="https://docs.fileformat.com/presentation/pptx/" %}}

Plik PPTX to plik prezentacji Microsoft PowerPoint w formacie Open XML. Przechowuje slajdy, tekst, obrazy, formatowanie, animacje i inne treści prezentacji w skompresowanym pakiecie opartym na XML.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Inne obsługiwane formaty do analizy" subTitle="W C++ możesz też analizować inne formaty prezentacji." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/cpp/parser/odp/" name="ODP" description="Prezentacja OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/cpp/parser/ppt/" name="PPT" description="Prezentacja programu PowerPoint 97-2003" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
