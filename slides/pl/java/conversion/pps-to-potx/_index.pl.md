---
title: Konwertuj PPS na POTX przez Java
weight: 7150
url: /pl/java/conversion/pps-to-potx/ 
description: Przykładowy kod konwersji Java dla formatu PPS do pliku POTX. Użyj tego przykładowego kodu, aby wyeksportować prezentacje PowerPoint i OpenOffice do POTX w dowolnej aplikacji internetowej lub aplikacji opartej na Javie.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Konwertuj PPS na POTX przez Java" h2="Konwersja PPS na POTX Java w celu konwersji jednej lub wielu stron na POTX przy użyciu lokalnej biblioteki Java." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="POTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PPS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/java" installationsDocsLink="https://docs.aspose.com/slides/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/java" learnAsLink="https://docs.aspose.com/slides/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides" >}}

{{% blocks/products/pf/agp/content h2="Jak przekonwertować PPS na POTX za pomocą Javy?" %}}

 Aby renderować PPS do POTX, użyjemy
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

{{% blocks/products/pf/agp/feature-section-col title="Kroki, aby przekonwertować PPS na POTX za pomocą Javy" %}}

{{% blocks/products/pf/agp/text %}}

 Programiści Java mogą łatwo przekonwertować plik PPS na POTX w zaledwie kilku linijkach kodu.

{{% /blocks/products/pf/agp/text %}}

1. Załaduj plik PPS z instancją klasy Presentation
1. Wywołaj metodę Presentation.save, określając ścieżkę pliku wyjściowego i SaveFormat
1. Plik POTX zostanie zapisany pod określoną ścieżką

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="wymagania systemowe" %}}

{{% blocks/products/pf/agp/text %}}

 Przed uruchomieniem przykładowego kodu konwersji Java upewnij się, że spełnione są następujące wymagania wstępne.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows lub kompatybilny system operacyjny z Java Runtime Environment dla aplikacji JSP/JSF i aplikacji komputerowych.
- Pobierz najnowszą wersję Aspose.Slides for Java bezpośrednio od Maven.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Kod źródłowy konwersji PPS na POTX Java" offSpacer="" %}}

```cs
// instantiate a Presentation object that represents a PPS file
Presentation presentation = new Presentation("template.pps");
// save the presentation as POTX
presentation.save("output.potx", SaveFormat.Potx);   

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension=""
        sectionTitle="Darmowa aplikacja do konwersji PPS do POTX" 
        sectionDescription="[Wypróbuj naszą bezpłatną aplikację MP4 To MP3](https://products.aspose.app/slides/video/mp4-to-mp3/)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="Możesz także przekonwertować PPS na wiele innych formatów plików, w tym kilka wymienionych poniżej." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/pps-to-bmp/" name="PPS TO BMP" description="Bitmapa" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/pps-to-gif/" name="PPS TO GIF" description="Graficzny format wymiany" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/pps-to-html/" name="PPS TO HTML" description="hipertekstowy język znaczników" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/pps-to-jpeg/" name="PPS TO JPEG" description="Obraz JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/pps-to-odp/" name="PPS TO ODP" description="Format prezentacji OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/pps-to-otp/" name="PPS TO OTP" description="Standardowy format OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/pps-to-pdf/" name="PPS TO PDF" description="format dokumentu przenośnego" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/pps-to-png/" name="PPS TO PNG" description="Przenośna Grafika Sieciowa" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/pps-to-pot/" name="PPS TO POT" description="Pliki szablonów programu Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/pps-to-potm/" name="PPS TO POTM" description="Plik szablonu programu Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/pps-to-ppsm/" name="PPS TO PPSM" description="Pokaz slajdów z obsługą makr" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/pps-to-ppsx/" name="PPS TO PPSX" description="Pokaz slajdów programu PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/pps-to-ppt/" name="PPS TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/pps-to-pptm/" name="PPS TO PPTM" description="Plik prezentacji z obsługą makr" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/pps-to-pptx/" name="PPS TO PPTX" description="Otwórz format prezentacji XML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/pps-to-svg/" name="PPS TO SVG" description="Skalowalna Grafika wektorowa" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/pps-to-swf/" name="PPS TO SWF" description="Format SWF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/pps-to-tiff/" name="PPS TO TIFF" description="Oznaczony format obrazu" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/pps-to-xps/" name="PPS TO XPS" description="Specyfikacje papieru XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}