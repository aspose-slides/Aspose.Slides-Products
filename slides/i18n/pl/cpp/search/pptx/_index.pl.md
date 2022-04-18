---
title: Przeszukuj dokument PPTX bez otwierania za pomocą C++
weight: 5870
url: /pl/cpp/search/pptx/ 
description: Przykładowy kod C++ do wyszukiwania słów ze wzorem w pliku PPTX w C++ Runtime Environment dla Windows 32-bitowy, Windows 64-bitowy i Linux 64-bitowy.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Wyszukaj formaty PPTX w C++" h2="Natywne i wysokowydajne wyszukiwanie dokumentów PPTX przy użyciu Aspose.Slides po stronie serwera dla interfejsów API C++, bez użycia jakiegokolwiek oprogramowania, takiego jak Microsoft lub Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="PPTX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/cpp" installationsDocsLink="https://docs.aspose.com/slides/cpp" nugetLink="https://www.nuget.org/packages/aspose.slides" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/cpp" learnAsLink="https://docs.aspose.com/slides/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Jak wyszukiwać plik PPTX za pomocą C++" %}}

 Aby wyszukać plik PPTX, użyjemy
 [Aspose.Slides dla C++](https://products.aspose.com/slides/cpp)
 API, które jest bogatym w funkcje, wydajnym i łatwym w użyciu interfejsem API do wyszukiwania dokumentów dla platformy C++. Możesz pobrać jego najnowszą wersję bezpośrednio, po prostu otwórz
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 menedżer pakietów, szukaj
 **Załóż.Slajdy.Cpp**
 i zainstaluj. Możesz również użyć następującego polecenia z konsoli Menedżera pakietów.

{{% blocks/products/pf/agp/code-block title="Komenda" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="Kroki wyszukiwania plików PPTX w C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Podstawowe wyszukiwanie dokumentów przy użyciu interfejsów API Aspose.Slides można wykonać za pomocą zaledwie kilku wierszy kodu." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Załaduj plik PPTX, tworząc wystąpienie obiektu klasy prezentacji.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Pobierz tablicę obiektów ITextFrame z pierwszego slajdu.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Przeprowadź pętlę przez tablicę TextFrames
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Przewijaj akapity w bieżącym ITextFrame
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Przewijaj fragmenty w bieżącym paragrafie IP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Wyświetlaj wysokość i nazwę czcionki.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="wymagania systemowe" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Slides dla C++ obsługuje wszystkie główne platformy i systemy operacyjne. Upewnij się, że masz następujące wymagania wstępne.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows lub kompatybilny system operacyjny z C++ Runtime Environment dla Windows 32-bitowy, Windows 64-bitowy i Linux 64-bitowy.
- Aspose.Slides dla C++ DLL, do którego odwołuje się Twój projekt.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Wyszukaj pliki PPTX — C++" offSpacer="" %}}

```cs
// Sample file path
const String sourceFilePath = u"SourceDirectory\\sourceFile.pptx";

// Load the Presentation file
SharedPtr<Presentation> presentation = MakeObject<Presentation>(sourceFilePath);

// Get an Array of ITextFrame objects from the first slide
System::ArrayPtr<SharedPtr<ITextFrame>> textFramesSlideOne = SlideUtil::GetAllTextBoxes(presentation->get_Slides()->idx_get(0));

// Loop through the Array of TextFrames
for (int i = 0; i get_Length(); i++){
	// Loop through paragraphs in current ITextFrame
	for (SharedPtr<IParagraph> paragraph : textFramesSlideOne[i]->get_Paragraphs()){
		// Loop through portions in the current IParagraph
		for (SharedPtr<IPortion> portion : paragraph->get_Portions()){
			
			//Display text using portion->get_Text());
		}
	}
}  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="O Aspose.Slides dla C++ API" %}}

 Aspose.Slides API może być używany do czytania, pisania, manipulowania i konwertowania dokumentów Microsoft PowerPoint do PDF, XPS, HTML, TIFF, ODP i różnych innych formatów. Można tworzyć nowe pliki od podstaw i zapisywać je w odpowiednich obsługiwanych formatach. Aspose.Slides to samodzielny interfejs API do tworzenia, analizowania lub manipulowania prezentacjami, slajdami i elementami i nie zależy od żadnego oprogramowania, takiego jak Microsoft lub OpenOffice.  



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Online PPTX Search Live Demos" sectionDescription="Search text, words, phrases within PPTX documents right now by visiting our [Live Demos website](https://products.aspose.app/slides/search). The live demo has the following benefits" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Just upload your PPTX files." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Search result appears instantly." >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PPTX " readMoreLink="https://docs.fileformat.com/presentation/pptx/" >}}
Files with PPTX extension are presentation files created with popular Microsoft PowerPoint application. Unlike the previous version of presentation file format PPT which was binary, the PPTX format is based on the Microsoft PowerPoint open XML presentation file format. A presentation file is a collection of slides where each slide can comprise of text, images, formatting, animations, and other media. These slides are presented to audience in the form of slideshows with custom presentation settings. 

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane dokumenty wyszukiwania" subTitle="Używając C++, można również przeszukiwać inne pliki, w tym." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/search/odp/" name="ODP" description="Format prezentacji OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/search/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}