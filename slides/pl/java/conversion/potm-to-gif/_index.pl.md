---
title: Konwertuj POTM na GIF za pomocą Javy
weight: 7030
url: /pl/java/conversion/potm-to-gif/ 
description: Przykładowy kod konwersji Java dla formatu POTM do pliku GIF. Użyj tego przykładowego kodu, aby wyeksportować prezentacje PowerPoint i OpenOffice do formatu GIF w dowolnej aplikacji internetowej lub aplikacji opartej na języku Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Konwertuj POTM na GIF za pomocą Javy" h2="Konwersja POTM do GIF Java w celu konwersji jednej lub wielu stron do formatu GIF przy użyciu lokalnej biblioteki Java." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="GIF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="POTM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/java" installationsDocsLink="https://docs.aspose.com/slides/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/java" learnAsLink="https://docs.aspose.com/slides/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides" >}}

{{% blocks/products/pf/agp/content h2="Jak przekonwertować POTM na GIF za pomocą Javy?" %}}

 Aby renderować POTM do GIF, użyjemy
 [Aspose.Slides for Java](https://products.aspose.com/slides/pl/java/)
 API, który jest bogatym w funkcje, wydajnym i łatwym w użyciu interfejsem API konwersji dla platformy Java. Możesz pobrać jego najnowszą wersję bezpośrednio z
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides)
 i zainstaluj go w swoim projekcie opartym na Maven, dodając następujące konfiguracje do pom.xml.

{{% blocks/products/pf/agp/code-block title="Magazyn" offSpacer="true" %}}

```xml

<repository>
    <id>AsposeJavaAPI</id>
    <name>Aspose Java API</name>
    <url>https://releases.aspose.com/java/repo/</url>
</repository>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Zależność" offSpacer="true" %}}

```xml

<dependency>
    <groupId>com.aspose</groupId>
    <artifactId>aspose-slides</artifactId>
    <version>version of aspose-slides API</version>
    <classifier>jdk17</classifier>
</dependency>
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Kroki, aby przekonwertować POTM na GIF za pomocą Javy" %}}

{{% blocks/products/pf/agp/text %}}

 Programiści Java mogą łatwo przekonwertować plik POTM na GIF w zaledwie kilku linijkach kodu.

{{% /blocks/products/pf/agp/text %}}

1. Załaduj plik POTM z instancją klasy Presentation
1. Powtórz każdy slajd w prezentacji
1. Utwórz obraz w pełnej skali jako bitmapę z każdą iteracją
1. Wywołaj metodę Bitmap.save z rozszerzeniem pliku GIF i formatem ImageFormat

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="wymagania systemowe" %}}

{{% blocks/products/pf/agp/text %}}

 Przed uruchomieniem przykładowego kodu konwersji Java upewnij się, że spełnione są następujące wymagania wstępne.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows lub kompatybilny system operacyjny z Java Runtime Environment dla aplikacji JSP/JSF i aplikacji komputerowych.
- Pobierz najnowszą wersję Aspose.Slides for Java bezpośrednio od Maven.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Kod źródłowy konwersji POTM do GIF Java" offSpacer="" %}}

```cs
// load POTM with Aspose.Slides
Presentation presentation = new Presentation("template.potm");
   
    // iterate over all slides in the presentation
for (ISlide sld : presentation.getSlides()) 
{
  
  // create a full scale image of each slide
  BufferedImage bi = sld.getThumbnail(new RenderingOptions());

  // create a new file of type GIF for every slide
  File outputfile = new File(sld.getSlideNumber() + ".gif");
  
  // save the slide image to disk
  ImageIO.write(bi, "gif", outputfile);
}   

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension=""
        sectionTitle="Darmowa aplikacja do konwersji POTM do GIF" 
        sectionDescription="[Wypróbuj naszą bezpłatną aplikację MP4 To MP3](https://products.aspose.app/slides/video/mp4-to-mp3/)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="Możesz także przekonwertować POTM na wiele innych formatów plików, w tym kilka wymienionych poniżej." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/potm-to-bmp/" name="POTM TO BMP" description="Bitmapa" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/potm-to-html/" name="POTM TO HTML" description="hipertekstowy język znaczników" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/potm-to-jpeg/" name="POTM TO JPEG" description="Obraz JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/potm-to-odp/" name="POTM TO ODP" description="Format prezentacji OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/potm-to-otp/" name="POTM TO OTP" description="Standardowy format OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/potm-to-pdf/" name="POTM TO PDF" description="format dokumentu przenośnego" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/potm-to-png/" name="POTM TO PNG" description="Przenośna Grafika Sieciowa" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/potm-to-pot/" name="POTM TO POT" description="Pliki szablonów programu Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/potm-to-potx/" name="POTM TO POTX" description="Prezentacja szablonu Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/potm-to-pps/" name="POTM TO PPS" description="Pokaz slajdów programu PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/potm-to-ppsm/" name="POTM TO PPSM" description="Pokaz slajdów z obsługą makr" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/potm-to-ppsx/" name="POTM TO PPSX" description="Pokaz slajdów programu PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/potm-to-ppt/" name="POTM TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/potm-to-pptm/" name="POTM TO PPTM" description="Plik prezentacji z obsługą makr" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/potm-to-pptx/" name="POTM TO PPTX" description="Otwórz format prezentacji XML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/potm-to-svg/" name="POTM TO SVG" description="Skalowalna Grafika wektorowa" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/potm-to-swf/" name="POTM TO SWF" description="Format SWF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/potm-to-tiff/" name="POTM TO TIFF" description="Oznaczony format obrazu" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/potm-to-xps/" name="POTM TO XPS" description="Specyfikacje papieru XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}