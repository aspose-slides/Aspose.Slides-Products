---
title: Extrahieren Sie Text und Bilder aus einem PPT-Dokument über C++
weight: 2780
url: /de/cpp/parser/ppt/ 
description: C++-Beispielcode zum Extrahieren von Text und Bildern aus einer PPT-Datei in der C++-Laufzeitumgebung für Windows 32 Bit, Windows 64 Bit und Linux 64 Bit.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Analysieren Sie PPT-Formate in C++" h2="Natives und leistungsstarkes PPT-Dokumentparsing mit serverseitigen Aspose.Slides für C++-APIs, ohne die Verwendung von Software wie Microsoft oder Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/cpp" installationsDocsLink="https://docs.aspose.com/slides/cpp" nugetLink="https://www.nuget.org/packages/aspose.slides.cpp" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/cpp" learnAsLink="https://docs.aspose.com/slides/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="So analysieren Sie eine PPT-Datei mit C++" %}}

 Um die PPT-Datei zu analysieren, verwenden wir
 [Aspose.Folien für C++](https://products.aspose.com/slides/de/cpp/)
 API, die eine funktionsreiche, leistungsstarke und einfach zu verwendende API zum Analysieren von Dokumenten für die C++-Plattform ist. Sie können die neueste Version direkt herunterladen, einfach öffnen
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 Paketmanager, suche nach
 **Aspose.Folien.Cpp**
 und installieren. Sie können auch den folgenden Befehl in der Paket-Manager-Konsole verwenden.

{{% blocks/products/pf/agp/code-block title="Befehl" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="Schritte zum Analysieren von PPT-Dateien in C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Eine einfache Dokumentenanalyse mit [Aspose.Slides for C++](https://products.aspose.com/slides/de/cpp/) APIs kann mit nur wenigen Codezeilen durchgeführt werden." >}}

{{< blocks/products/pf/agp/step-autogen >}}
PPT-Datei laden.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Rufen Sie ein Array von ITextFrame-Objekten der ersten Folie ab.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Durchlaufen Sie das Array von TextFrames
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Absätze im aktuellen ITextFrame durchlaufen.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Teile im aktuellen IParagraph durchlaufen.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Zeigen Sie den Text an.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="System Anforderungen" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Slides für C++ unterstützt auf allen wichtigen Plattformen und Betriebssystemen. Bitte stellen Sie sicher, dass Sie die folgenden Voraussetzungen erfüllen.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows oder ein kompatibles Betriebssystem mit C++ Runtime Environment für Windows 32 Bit, Windows 64 Bit und Linux 64 Bit.
- Aspose.Slides für C++-DLL, auf die in Ihrem Projekt verwiesen wird.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Analysieren Sie PPT-Dateien - C++" offSpacer="" %}}

```cs
// Sample file path
const String sourceFilePath = u"SourcePath\sourceFile.ppt";

// Load the PPT file
SharedPtr<Presentation> presentation = MakeObject<Presentation>(sourceFilePath);

// Get an Array of ITextFrame objects from the first slide
System::ArrayPtr<SharedPtr<ITextFrame>> textFramesSlideOne = SlideUtil::GetAllTextBoxes(presentation->get_Slides()->idx_get(0));

// Loop through the Array of TextFrames
for (int i = 0; i get_Length(); i++){
	// Loop through paragraphs in current ITextFrame
	for (SharedPtr<IParagraph> paragraph : textFramesSlideOne[i]->get_Paragraphs()){
		// Loop through portions in the current IParagraph
		for (SharedPtr<IPortion> portion : paragraph->get_Portions()){
			// Display text
			Console::WriteLine(portion->get_Text());
		}
	}
}  

    

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="Informationen zu Aspose.Slides für die C++-API" %}}

 Aspose.Slides API kann zum Lesen, Schreiben, Bearbeiten und Konvertieren von Microsoft PowerPoint-Dokumenten in PDF, XPS, HTML, TIFF, ODP und verschiedene andere Formate verwendet werden. Man kann neue Dateien von Grund auf neu erstellen und diese in den entsprechenden unterstützten Formaten speichern. Aspose.Slides ist eine eigenständige API zum Erstellen, Analysieren oder Bearbeiten von Präsentationen, Folien und Elementen und ist nicht von Software wie Microsoft oder OpenOffice abhängig.  



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Online PPT Parser Live Demos" sectionDescription="Extract text and images from PPT documents right now by visiting our [Live Demos website](https://products.aspose.app/slides/parser). The live demo has the following benefits" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your PPT files." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" It will be parsed instantly." >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PPT" readMoreLink="https://docs.fileformat.com/presentation/ppt/" >}}
A file with PPT extension represents PowerPoint file that consists of a collection of slides for displaying as SlideShow. It specifies the Binary File Format used by Microsoft PowerPoint 97-2003. A PPT file can contain several different types of information such as text, bulleted points, images, multimedia and other embedded OLE objects. Microsoft came up with newer file format for PowerPoint, known as PPTX, from 2007 onwards that is based on Office OpenXML and is different from this binary file format. Several other application programs such as OpenOffice Impress and Apple Keynote can also create PPT files. 

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Parsing-Dokumente" subTitle="Mit C++ kann man leicht andere Formate analysieren, einschließlich." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/cpp/parser/odp/" name="ODP" description="OpenDocument-Präsentationsformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/cpp/parser/pptx/" name="PPTX" description="Offenes XML-Präsentationsformat" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}