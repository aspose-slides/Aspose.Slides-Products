---
title: Konwertuj POT na PPTX przez Java
weight: 1630
url: /pl/java/conversion/pot-to-pptx/ 
description: Przykładowy kod konwersji Java dla formatu POT do pliku PPTX. Użyj tego przykładowego kodu, aby wyeksportować prezentacje PowerPoint i OpenOffice do PPTX w dowolnej aplikacji internetowej lub aplikacji opartej na Javie.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Konwertuj POT na PPTX przez Java" h2="Konwersja POT do PPTX Java w celu konwersji jednej lub wielu stron na PPTX przy użyciu lokalnej biblioteki Java." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="POT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/java" installationsDocsLink="https://docs.aspose.com/slides/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/java" learnAsLink="https://docs.aspose.com/slides/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides" >}}

{{% blocks/products/pf/agp/content h2="Jak przekonwertować POT na PPTX za pomocą Javy?" %}}

 Aby renderować POT do PPTX, użyjemy
 [Aspose.Slides for Java](https://products.aspose.com/slides/pl/java)
 API, który jest bogatym w funkcje, wydajnym i łatwym w użyciu interfejsem API konwersji dla platformy Java. Możesz pobrać jego najnowszą wersję bezpośrednio z
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides)
 i zainstaluj go w swoim projekcie opartym na Maven, dodając następujące konfiguracje do pom.xml.

{{% blocks/products/pf/agp/code-block title="Magazyn" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Zależność" offSpacer="true" %}}

```cs
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

{{% blocks/products/pf/agp/feature-section-col title="Kroki, aby przekonwertować POT na PPTX przez Java" %}}

{{% blocks/products/pf/agp/text %}}

 Programiści Java mogą łatwo przekonwertować plik POT na PPTX w zaledwie kilku linijkach kodu.

{{% /blocks/products/pf/agp/text %}}

1. Załaduj plik POT z instancją klasy Presentation
1. Wywołaj metodę Presentation.save, określając ścieżkę pliku wyjściowego i SaveFormat
1. Plik PPTX zostanie zapisany pod określoną ścieżką

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="wymagania systemowe" %}}

{{% blocks/products/pf/agp/text %}}

 Przed uruchomieniem przykładowego kodu konwersji Java upewnij się, że spełnione są następujące wymagania wstępne.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows lub kompatybilny system operacyjny z Java Runtime Environment dla aplikacji JSP/JSF i aplikacji komputerowych.
- Pobierz najnowszą wersję Aspose.Slides for Java bezpośrednio od Maven.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Kod źródłowy konwersji POT do PPTX Java" offSpacer="" %}}

```cs
// instantiate a Presentation object that represents a POT file
Presentation presentation = new Presentation("template.pot");
// save the presentation as PPTX
presentation.save("output.pptx", SaveFormat.Pptx);   

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension="pot-to-pptx"
        sectionTitle="Darmowa aplikacja do konwersji POT do PPTX" 
        sectionDescription="[Wypróbuj naszą bezpłatną aplikację MP4 To MP3](https://products.aspose.app/slides/video/mp4-to-mp3/)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="Możesz także przekonwertować POT na wiele innych formatów plików, w tym kilka wymienionych poniżej." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/pot-to-bmp/" name="POT TO BMP" description="Bitmapa" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/pot-to-gif/" name="POT TO GIF" description="Graficzny format wymiany" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/pot-to-html/" name="POT TO HTML" description="hipertekstowy język znaczników" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/pot-to-jpeg/" name="POT TO JPEG" description="Obraz JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/pot-to-odp/" name="POT TO ODP" description="Format prezentacji OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/pot-to-otp/" name="POT TO OTP" description="Standardowy format OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/pot-to-pdf/" name="POT TO PDF" description="format dokumentu przenośnego" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/pot-to-png/" name="POT TO PNG" description="Przenośna Grafika Sieciowa" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/pot-to-potm/" name="POT TO POTM" description="Plik szablonu programu Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/pot-to-potx/" name="POT TO POTX" description="Prezentacja szablonu Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/pot-to-pps/" name="POT TO PPS" description="Pokaz slajdów programu PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/pot-to-ppsm/" name="POT TO PPSM" description="Pokaz slajdów z obsługą makr" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/pot-to-ppsx/" name="POT TO PPSX" description="Pokaz slajdów programu PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/pot-to-ppt/" name="POT TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/pot-to-pptm/" name="POT TO PPTM" description="Plik prezentacji z obsługą makr" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/pot-to-svg/" name="POT TO SVG" description="Skalowalna Grafika wektorowa" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/pot-to-swf/" name="POT TO SWF" description="Format SWF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/pot-to-tiff/" name="POT TO TIFF" description="Oznaczony format obrazu" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/pot-to-xps/" name="POT TO XPS" description="Specyfikacje papieru XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}