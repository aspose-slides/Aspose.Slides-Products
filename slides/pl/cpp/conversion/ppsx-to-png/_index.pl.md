---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konwertuj PPSX na PNG za pomocą aplikacji C++
weight: 6170
url: /pl/cpp/conversion/ppsx-to-png/ 
description: Przykładowy kod konwersji C++ dla dokumentu PPSX do formatu PNG. Użyj przykładowego kodu do wsadowej konwersji PPSX na PNG w dowolnej aplikacji C++.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konwertuj PPSX na PNG za pomocą C++" h2="Wydajna konwersja PPSX do PNG przy użyciu biblioteki C++ bez konieczności instalacji programu Microsoft PowerPoint."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/cpp"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Jak przekonwertować PPSX na PNG za pomocą C++" %}}

Aby przekonwertować PPSX na PNG, użyjemy
 [Aspose.Slides dla C++](https://products.aspose.com/slides/pl/cpp/)
 API, które jest bogatym w funkcje, potężnym i łatwym w użyciu interfejsem API do manipulacji i konwersji dokumentów dla platformy C++. Możesz pobrać jego najnowszą wersję bezpośrednio, po prostu otwórz
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 menedżer pakietów, szukaj
 Aspose.Slajdy.Cpp
 i zainstaluj. Możesz również użyć następującego polecenia z konsoli Menedżera pakietów.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Komenda" >}}
```cs

PM> Install-Package Aspose.Slides.Cpp

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Kod źródłowy konwersji PPSX do PNG C++" >}}
```cs
// Load the PPSX
SharedPtr<Presentation> pres = MakeObject<Presentation>(u"sourceFile.ppsx");

// Access the first slide
SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// User defined dimension
int desiredX = 1200;
int desiredY = 800;

// Getting scaled value  of X and Y
float ScaleX = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Width()) * desiredX;
float ScaleY = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Height()) * desiredY;

// Create a custom scale image
auto bitmap = slide->GetThumbnail(ScaleX, ScaleY);

bitmap->Save(u"output.png", ImageFormat::get_Png());
	
//Iterate through each slide via index and convert

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Kroki, aby przekonwertować PPSX na PNG za pomocą C++" intro="Programiści C++ mogą łatwo przekonwertować plik PPSX na PNG w zaledwie kilku linijkach kodu." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Załaduj plik PPSX za pomocą Aspose.Slides dla obiektu prezentacji C++.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Wybierz pierwszy slajd.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ustaw żądane wymiary.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Pobierz miniaturę o żądanych wymiarach.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Wywołaj metodę Save() z parametrem wyjściowym PNG.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Otwórz plik PNG w kompatybilnym programie.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="wymagania systemowe" intro="Przed uruchomieniem C++ przykładowego kodu konwersji upewnij się, że masz następujące wymagania wstępne." %}}

- Microsoft Windows lub kompatybilny system operacyjny z C++ Runtime Environment dla Windows 32-bitowy, Windows 64-bitowy i Linux 64-bitowy.
- Aspose.Slides dla C++ DLL, do którego odwołuje się Twój projekt.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Zbudowano z Aspose.Slides" title="Konwertuj PPSX na PNG online" description="Bezpłatna aplikacja Aspose.Slides Conversion została zbudowana z użyciem [Aspose.Slides for C++](https://products.aspose.com/slides/pl/cpp/), tego samego API co w powyższym kodzie. Otwórz ją i zobacz, co API potrafi zrobić z Twoimi plikami PPSX." button="Otwórz Aspose.Slides Conversion" note="[Wszystkie bezpłatne aplikacje](https://products.aspose.app/slides/family)" upload="Upuść lub prześlij plik" saveAs="Zapisz jako" convert="Konwertuj" >}}
- Działa w przeglądarce, nie trzeba niczego instalować.
- Zobacz, jak Aspose.Slides konwertuje pliki, zanim napiszesz kod.
- Prześlij pliki PPSX i zapisz je jako PNG.
- Pobierz wynik lub przekonwertuj kolejne pliki.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Inne obsługiwane konwersje" subTitle="Możesz także przekonwertować PPSX na wiele innych formatów plików, w tym kilka wymienionych poniżej." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/cpp/conversion/ppsx-to-bmp/" name="PPSX TO BMP" description="Bitmapa" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/cpp/conversion/ppsx-to-emf/" name="PPSX TO EMF" description="Ulepszony format metapliku" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/cpp/conversion/ppsx-to-gif/" name="PPSX TO GIF" description="Graficzny format wymiany" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/cpp/conversion/ppsx-to-html/" name="PPSX TO HTML" description="hipertekstowy język znaczników" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/cpp/conversion/ppsx-to-jpeg/" name="PPSX TO JPEG" description="Obraz JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/cpp/conversion/ppsx-to-odp/" name="PPSX TO ODP" description="Format prezentacji OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/cpp/conversion/ppsx-to-otp/" name="PPSX TO OTP" description="Standardowy format OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/cpp/conversion/ppsx-to-pdf/" name="PPSX TO PDF" description="format dokumentu przenośnego" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/cpp/conversion/ppsx-to-pot/" name="PPSX TO POT" description="Pliki szablonów programu Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/cpp/conversion/ppsx-to-potm/" name="PPSX TO POTM" description="Plik szablonu programu Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/cpp/conversion/ppsx-to-potx/" name="PPSX TO POTX" description="Prezentacja szablonu Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/cpp/conversion/ppsx-to-pps/" name="PPSX TO PPS" description="Pokaz slajdów programu PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/cpp/conversion/ppsx-to-ppsm/" name="PPSX TO PPSM" description="Pokaz slajdów z obsługą makr" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/cpp/conversion/ppsx-to-ppt/" name="PPSX TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/cpp/conversion/ppsx-to-pptm/" name="PPSX TO PPTM" description="Plik prezentacji z obsługą makr" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/cpp/conversion/ppsx-to-pptx/" name="PPSX TO PPTX" description="Otwórz format prezentacji XML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/cpp/conversion/ppsx-to-svg/" name="PPSX TO SVG" description="Skalowalna Grafika wektorowa" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/cpp/conversion/ppsx-to-tiff/" name="PPSX TO TIFF" description="Oznaczony format obrazu" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/cpp/conversion/ppsx-to-xml/" name="PPSX TO XML" description="Rozszerzalny język znaczników" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/cpp/conversion/ppsx-to-xps/" name="PPSX TO XPS" description="Specyfikacje papieru XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
