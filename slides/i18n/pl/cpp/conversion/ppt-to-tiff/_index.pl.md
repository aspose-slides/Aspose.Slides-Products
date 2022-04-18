---
title: Konwertuj PPT na TIFF za pomocą aplikacji C++
weight: 600
url: /pl/cpp/conversion/ppt-to-tiff/ 
description: Przykładowy kod konwersji C++ dla dokumentu PPT do formatu TIFF. Użyj przykładowego kodu do wsadowej konwersji PPT na TIFF w dowolnej aplikacji C++.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Konwertuj PPT na TIFF za pomocą C++" h2="Wydajna konwersja PPT do TIFF przy użyciu biblioteki C++ bez konieczności instalacji programu Microsoft PowerPoint." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="TIFF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/cpp" installationsDocsLink="https://docs.aspose.com/slides/cpp" nugetLink="https://www.nuget.org/packages/aspose.slides" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/cpp" learnAsLink="https://docs.aspose.com/slides/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Jak przekonwertować PPT na TIFF za pomocą C++" %}}

 Aby przekonwertować PPT na TIFF, użyjemy
 [Aspose.Slides dla C++](https://products.aspose.com/slides/cpp)
 API, które jest bogatym w funkcje, potężnym i łatwym w użyciu interfejsem API do manipulacji i konwersji dokumentów dla platformy C++. Możesz pobrać jego najnowszą wersję bezpośrednio, po prostu otwórz
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 menedżer pakietów, szukaj
 Aspose.Slajdy.Cpp
 i zainstaluj. Możesz również użyć następującego polecenia z konsoli Menedżera pakietów.

{{% blocks/products/pf/agp/code-block title="Komenda" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Kroki, aby przekonwertować PPT na TIFF za pomocą C++" %}}

{{% blocks/products/pf/agp/text %}}

 Programiści C++ mogą łatwo przekonwertować plik PPT na TIFF w zaledwie kilku linijkach kodu.

{{% /blocks/products/pf/agp/text %}}

1. Załaduj plik PPT za pomocą Aspose.Slides dla obiektu prezentacji C++.
1. Wywołaj metodę Save().
1. Przekaż ścieżkę pliku wyjściowego z rozszerzeniem pliku (TIFF).
1. Plik TIFF zostanie zapisany pod określoną ścieżką.
1. Otwórz plik TIFF w kompatybilnym programie.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="wymagania systemowe" %}}

{{% blocks/products/pf/agp/text %}}

 Przed uruchomieniem C++ przykładowego kodu konwersji upewnij się, że masz następujące wymagania wstępne.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows lub kompatybilny system operacyjny z C++ Runtime Environment dla Windows 32-bitowy, Windows 64-bitowy i Linux 64-bitowy.
- Aspose.Slides dla C++ DLL, do którego odwołuje się Twój projekt.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Kod źródłowy konwersji PPT do TIFF C++" offSpacer="" %}}

```cs
// Load the PPT.
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"sourceFile.ppt");
// Save in TIFF format.
prs->Save(u"convertedFile.tiff", Aspose::Slides::Export::SaveFormat::Tiff);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="PPT to TIFF Conversion Live Demos" sectionDescription="[Convert PPT to TIFF](https://products.aspose.app/slides/conversion/ppt-to-tiff) right now by visiting our Live Demos website.The live demo has the following benefits" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your PPT file, it will be converted instantly to TIFF." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will get the download link." >}}

    {{% blocks/products/pf/agp/content h2="Biblioteka manipulacji prezentacją C++" %}}

 Interfejs API slajdów i prezentacji może być używany do czytania, pisania, manipulowania i konwertowania dokumentów programu Microsoft PowerPoint do formatu PDF, XPS, HTML, TIFF, ODP i różnych innych formatów. Można tworzyć nowe pliki od podstaw i zapisywać je w odpowiednich obsługiwanych formatach. Aspose.Slides to samodzielny interfejs API do tworzenia, analizowania lub manipulowania prezentacjami, slajdami i elementami i nie zależy od żadnego oprogramowania, takiego jak Microsoft lub OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PPT" readMoreLink="https://docs.fileformat.com/presentation/ppt/" >}}

A file with PPT extension represents PowerPoint file that consists of a collection of slides for displaying as SlideShow. It specifies the Binary File Format used by Microsoft PowerPoint 97-2003. A PPT file can contain several different types of information such as text, bulleted points, images, multimedia and other embedded OLE objects. Microsoft came up with newer file format for PowerPoint, known as PPTX, from 2007 onwards that is based on Office OpenXML and is different from this binary file format. Several other application programs such as OpenOffice Impress and Apple Keynote can also create PPT files.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TIFF" readMoreLink="https://docs.fileformat.com/image/tiff/" >}}

TIFF or TIF, Tagged Image File Format, represents raster images that are meant for usage on a variety of devices that comply with this file format standard. It is capable of describing bilevel, grayscale, palette-color and full-color image data in several color spaces. It supports lossy as well as lossless compression schemes to choose between space and time for applications using the format. The format is extensible and has underwent several revisions that allows the inclusion of an unlimited amount of private or special-purpose information. The format is not machine dependent and is free from bounds like processor, operating system, or file systems.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="Możesz także przekonwertować PPT na wiele innych formatów plików, w tym kilka wymienionych poniżej." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppt-to-bmp/" name="PPT TO BMP" description="Bitmapa" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppt-to-emf/" name="PPT TO EMF" description="Ulepszony format metapliku" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppt-to-gif/" name="PPT TO GIF" description="Graficzny format wymiany" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppt-to-html/" name="PPT TO HTML" description="hipertekstowy język znaczników" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppt-to-jpeg/" name="PPT TO JPEG" description="Obraz JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppt-to-odp/" name="PPT TO ODP" description="Format prezentacji OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppt-to-otp/" name="PPT TO OTP" description="Standardowy format OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppt-to-pdf/" name="PPT TO PDF" description="format dokumentu przenośnego" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppt-to-png/" name="PPT TO PNG" description="Przenośna Grafika Sieciowa" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppt-to-pot/" name="PPT TO POT" description="Pliki szablonów programu Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppt-to-potm/" name="PPT TO POTM" description="Plik szablonu programu Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppt-to-potx/" name="PPT TO POTX" description="Prezentacja szablonu Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppt-to-pps/" name="PPT TO PPS" description="Pokaz slajdów programu PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppt-to-ppsm/" name="PPT TO PPSM" description="Pokaz slajdów z obsługą makr" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppt-to-ppsx/" name="PPT TO PPSX" description="Pokaz slajdów programu PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppt-to-pptm/" name="PPT TO PPTM" description="Plik prezentacji z obsługą makr" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppt-to-pptx/" name="PPT TO PPTX" description="Otwórz format prezentacji XML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppt-to-svg/" name="PPT TO SVG" description="Skalowalna Grafika wektorowa" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppt-to-xml/" name="PPT TO XML" description="Rozszerzalny język znaczników" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppt-to-xps/" name="PPT TO XPS" description="Specyfikacje papieru XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}