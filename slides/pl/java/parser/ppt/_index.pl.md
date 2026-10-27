---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 7140
title: Wyodrębnianie tekstu z dokumentów PPT w Javie
url: /pl/java/parser/ppt/ 
description: Wyodrębniaj tekst z plików PPT w Javie za pomocą Aspose.Slides for Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Analiza plików PPT w Javie" h2="Wyodrębniaj tekst i zawartość prezentacji z dokumentów PPT za pomocą serwerowych API Aspose.Slides for Java."
  apiHomeLink="/slides/java/"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/java/"
  learnLink="https://docs.aspose.com/slides/java"
  pricingLink="https://purchase.aspose.com/pricing/slides/java/"
  related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Analiza pliku PPT w Javie" %}}

Użyj [Aspose.Slides for Java](/slides/pl/java/), aby analizować prezentacje PPT i wyodrębniać tekst ze slajdów. Dodaj bibliotekę do projektu Maven, używając poniższej konfiguracji repozytorium i zależności w pliku `pom.xml`.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Repozytorium" >}}
```xml
<repository>
    <id>AsposeJavaAPI</id>
    <name>Aspose Java API</name>
    <url>https://releases.aspose.com/java/repo/</url>
</repository>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Zależność" >}}
```xml
<dependency>
    <groupId>com.aspose</groupId>
    <artifactId>aspose-slides</artifactId>
    <version>26.8</version>
    <classifier>jdk16</classifier>
</dependency>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Analiza plików PPT – Java" >}}
```java
Presentation presentation = new Presentation("demo.ppt");
try {
    ISlide slide = presentation.getSlides().get_Item(0);
    ITextFrame[] slideTextFrames = SlideUtil.getAllTextBoxes(slide);

    for (ITextFrame textFrame : slideTextFrames) {
        for (IParagraph paragraph : textFrame.getParagraphs()) {
            for (IPortion portion : paragraph.getPortions()) {
                System.out.print(portion.getText());
                System.out.print(portion.getPortionFormat().getFontHeight());
                System.out.print(portion.getPortionFormat().getLatinFont().getFontName());
            }
        }
    }
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak analizować pliki PPT w Javie" intro="Wyodrębnij tekst z prezentacji PPT za pomocą Aspose.Slides for Java w kilku liniach kodu." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Wczytaj plik `PPT` za pomocą klasy `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Wywołaj metodę `SlideUtil.getAllTextBoxes`, aby pobrać ramki tekstowe z pierwszego slajdu.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Przejdź przez każdy obiekt `ITextFrame`, `IParagraph` i `IPortion`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Odczytaj tekst, rozmiar czcionki i nazwę czcionki z każdego obiektu `IPortion`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Wymagania systemowe" intro="Aspose.Slides for Java obsługuje najważniejsze platformy i systemy operacyjne. Upewnij się, że Twoje środowisko spełnia poniższe wymagania." %}}

- Microsoft Windows lub zgodny system operacyjny ze środowiskiem Java Runtime Environment dla aplikacji JSP/JSF i aplikacji desktopowych.
- Najnowsza wersja Aspose.Slides for Java z [Maven](https://releases.aspose.com/java/repo/).

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Zbudowano z Aspose.Slides" title="Wyodrębniaj tekst i obrazy online" description="Bezpłatna aplikacja Aspose.Slides Parser została zbudowana z użyciem [Aspose.Slides for Java](https://products.aspose.com/slides/pl/java/), tego samego API co w powyższym kodzie. Otwórz ją i zobacz, co API potrafi zrobić z Twoimi plikami PPT." button="Otwórz Aspose.Slides Parser" note="[Wszystkie bezpłatne aplikacje](https://products.aspose.app/slides/family)" >}}
- Działa w przeglądarce, nie trzeba niczego instalować.
- Zobacz, jak Aspose.Slides odczytuje Twoje pliki, zanim napiszesz kod.
- Prześlij plik PPT i otrzymaj jego tekst oraz obrazy.
- Pobierz wszystko jako jedno archiwum ZIP.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPT" readMoreLink="https://docs.fileformat.com/presentation/ppt/" %}}

Plik PPT przechowuje prezentację PowerPoint 97-2003 w binarnym formacie plików. Może zawierać slajdy z tekstem, obrazami, wykresami, multimediami i osadzonymi obiektami.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Inne obsługiwane formaty do analizy" subTitle="W Javie możesz też analizować inne formaty prezentacji." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/java/parser/odp/" name="ODP" description="Prezentacja OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/java/parser/pptx/" name="PPTX" description="Prezentacja PowerPoint Open XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
