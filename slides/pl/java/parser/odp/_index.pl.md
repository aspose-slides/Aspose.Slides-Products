---
title: Wyodrębnij tekst i obrazy z dokumentu ODP za pomocą Javy
weight: 5200
url: /pl/java/parser/odp/ 
description: Przykładowy kod Java do wyodrębniania tekstu i obrazów z pliku ODP w środowisku Java Runtime Environment dla aplikacji JSP/JSF i aplikacji komputerowych.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Analizuj formaty ODP w Javie" h2="Natywne i wysokowydajne analizowanie dokumentów ODP przy użyciu Aspose.Slides po stronie serwera dla interfejsów API Java, bez użycia jakiegokolwiek oprogramowania, takiego jak Microsoft lub Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/java" installationsDocsLink="https://docs.aspose.com/slides/java" nugetLink="https://www.nuget.org/packages/aspose.slides.java" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/java" learnAsLink="https://docs.aspose.com/slides/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides" >}}

{{% blocks/products/pf/agp/content h2="Jak przeanalizować plik ODP za pomocą Javy" %}}

 Aby przeanalizować plik ODP, użyjemy
 [Aspose.Slides for Java](https://products.aspose.com/slides/pl/java)
 API, które jest bogatym w funkcje, potężnym i łatwym w użyciu API do analizowania dla platformy Java. Możesz pobrać jego najnowszą wersję bezpośrednio z
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


{{< blocks/products/pf/agp/feature-section-col title="Kroki parsowania plików ODP w Javie" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Podstawowe przetwarzanie dokumentów za pomocą interfejsów API [Aspose.Slides for Java](https://products.aspose.com/slides/pl/java) można wykonać za pomocą zaledwie kilku wierszy kodu." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Załaduj plik ODP, uruchamiając klasę Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Pobierz pierwsze ramki tekstowe slajdu.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Przewiń każdą część akapitu.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Uzyskaj wymagane dane wyjściowe, takie jak tekst, czcionka itp.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="wymagania systemowe" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Slides for Java obsługuje wszystkie główne platformy i systemy operacyjne. Upewnij się, że masz następujące wymagania wstępne.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows lub kompatybilny system operacyjny z Java Runtime Environment dla aplikacji JSP/JSF i aplikacji komputerowych.
- Pobierz najnowszą wersję Aspose.Slides for Java bezpośrednio z
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides) .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Analizuj pliki ODP — Java" offSpacer="" %}}

```cs
//Load ODP file
Presentation odpPresentation = new Presentation("demo.odp");
try{
    //Get an Array of TextFrameEx objects from the first slide
    ITextFrame[] textFramesSlideOne = SlideUtil.getAllTextBoxes(odpPresentation.getSlides().get_Item(0));

    //Loop through the Array of TextFrames
    for (int i = 0; i < textFramesSlideOne.length; i++){
        //Loop through paragraphs in current TextFrame
        for (IParagraph para : textFramesSlideOne[0].getParagraphs()){
            //Loop through portions in the current Paragraph
            for (IPortion port : para.getPortions()){
                //Display text in the current portion
                System.out.print(port.getText());

                //Display font height of the text
                System.out.print(port.getPortionFormat().getFontHeight());

                //Display font name of the text
                System.out.print(port.getPortionFormat().getLatinFont().getFontName());
            }
        }
    }
} finally {
    if (odpPresentation != null) odpPresentation.dispose();
}
//Similarly extarcting text from the Whole Presentation
//Use getAllTextFrames(odpPresentation, true) method and Iterate through Array   

    

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="Informacje o Aspose.Slides dla Java API" %}}

 Aspose.Slides API może być używany do czytania, pisania, manipulowania i konwertowania dokumentów Microsoft PowerPoint do PDF, XPS, HTML, TIFF, ODP i różnych innych formatów. Można tworzyć nowe pliki od podstaw i zapisywać je w odpowiednich obsługiwanych formatach. Aspose.Slides to samodzielny interfejs API do tworzenia, analizowania lub manipulowania prezentacjami, slajdami i elementami i nie zależy od żadnego oprogramowania, takiego jak Microsoft lub OpenOffice.  



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Online ODP Parser Live Demos" sectionDescription="Extract text and images from ODP documents right now by visiting our [Live Demos website](https://products.aspose.app/slides/parser). The live demo has the following benefits" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your ODP files." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" It will be parsed instantly." >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODP" readMoreLink="https://docs.fileformat.com/presentation/odp/" >}}
Files with ODP extension represent presentation file format used by OpenOffice.org in the OASISOpen standard. A presentation file is a collection of slides where each slide can comprise of text, images, formatting, animations, and other media. These slides are presented to audience in the form of slideshows with custom presentation settings. ODP files can be opened by applications that conform to the OpenDocument format (such as OpenOffice or StarOffice). 

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane dokumenty parsowania" subTitle="Korzystając z Javy, można łatwo analizować inne formaty, w tym." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/parser/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/parser/pptx/" name="PPTX" description="Otwórz format prezentacji XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}