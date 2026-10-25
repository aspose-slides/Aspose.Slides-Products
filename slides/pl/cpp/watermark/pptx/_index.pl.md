---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Dodawanie znaku wodnego do prezentacji PPTX w C++
url: /pl/cpp/watermark/pptx/
description: Dodawaj tekstowe lub graficzne znaki wodne do prezentacji PPTX w C++. Użyj Aspose.Slides for C++, aby umieszczać znaki wodne na slajdach.
keywords: dodawanie znaku wodnego do PPTX, tekstowy znak wodny PPTX, graficzny znak wodny PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Dodawanie znaku wodnego do prezentacji PPTX w C++ – przykład" h2="Użyj Aspose.Slides for C++, aby dodawać tekstowe lub graficzne znaki wodne do plików prezentacji bez programu Microsoft PowerPoint." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Dodawanie znaku wodnego do prezentacji PPTX za pomocą C++" variant="code" %}}

Aspose.Slides for C++ pozwala dodawać tekstowe lub graficzne znaki wodne do prezentacji PPTX. Dodaj kształt znaku wodnego do wzorca slajdów za pomocą `AddAutoShape`, dodaj tekst za pomocą `AddTextFrame` lub wypełnij kształt obrazem wczytanym przez `File::ReadAllBytes` i `AddImage`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Dodawanie tekstowego znaku wodnego do PPTX w C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");
auto masterSlide = presentation->get_Master(0);
auto watermarkShape = masterSlide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100, 100, 400, 80);

watermarkShape->AddTextFrame(u"Watermark");
presentation->Save(u"watermarked-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Dodawanie graficznego znaku wodnego do prezentacji PPTX w C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");
auto masterSlide = presentation->get_Master(0);
auto watermarkShape = masterSlide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100, 100, 400, 200);

auto imageData = File::ReadAllBytes(u"watermark.png");
auto watermarkImage = presentation->get_Images()->AddImage(imageData);

watermarkShape->get_FillFormat()->set_FillType(FillType::Picture);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->get_Picture()->set_Image(watermarkImage);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->set_PictureFillMode(PictureFillMode::Stretch);

presentation->Save(u"image-watermarked-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak dodać znak wodny do PPTX w C++" intro="Wykonaj poniższe kroki, aby dodać tekstowy lub graficzny znak wodny do plików PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Wczytaj plik PPTX za pomocą klasy `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Wybierz wzorzec slajdów z kolekcji `Presentation::get_Masters`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Dodaj kształt znaku wodnego za pomocą metody `AddAutoShape`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Dodaj tekst znaku wodnego za pomocą metody `AddTextFrame` lub ustaw wypełnienie obrazem za pomocą `AddImage`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zapisz plik ze znakiem wodnym za pomocą `SaveFormat::Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Zbudowano z Aspose.Slides" title="Dodawaj znaki wodne do plików PPTX online" description="Bezpłatna aplikacja Aspose.Slides Watermark została zbudowana z użyciem [Aspose.Slides for C++](https://products.aspose.com/slides/pl/cpp/), tego samego API co w powyższym kodzie. Otwórz ją i zobacz, co API potrafi zrobić z Twoimi plikami PPTX." button="Otwórz Aspose.Slides Watermark" note="[Wszystkie bezpłatne aplikacje](https://products.aspose.app/slides/family)" >}}
- Działa w przeglądarce, nie trzeba niczego instalować.
- Zobacz, jak Aspose.Slides dodaje znaki wodne, zanim napiszesz kod.
- Dodaj tekstowy lub graficzny znak wodny do pliku PPTX.
- Pobierz plik ze znakiem wodnym.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Inne formaty obsługujące znaki wodne" subTitle="W C++ możesz też dodawać znaki wodne do następujących formatów." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/cpp/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/cpp/watermark/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
