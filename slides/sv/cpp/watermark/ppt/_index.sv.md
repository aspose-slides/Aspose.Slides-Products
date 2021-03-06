---
title: Vattenstämpel PPT-dokument via C++
weight: 3820
url: /sv/cpp/watermark/ppt/ 
description: C++ exempelkod för att lägga till eller ta bort vattenstämpel till PPT-fil i C++ Runtime Environment för Windows 32 bit, Windows 64 bit och Linux 64 bit.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Lägg till textvattenstämpel till PPT via C++" h2="Bygg dina egna C++-appar för att vattenmärka PPT-filer med hjälp av API:er på serversidan." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/cpp" installationsDocsLink="https://docs.aspose.com/slides/cpp" nugetLink="https://www.nuget.org/packages/aspose.slides" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/cpp" learnAsLink="https://docs.aspose.com/slides/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Hur man vattenmärker PPT-fil med C++" %}}

 För att vattenmärka PPT-filen använder vi
 [Aspose.Slides för C++](https://products.aspose.com/slides/sv/cpp)
 API som är ett funktionsrikt, kraftfullt och lättanvänt API för dokumentvattenmärkning för C++-plattformen. Du kan ladda ner den senaste versionen direkt, bara öppna
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 pakethanterare, sök efter
 **Aspose.Slides.Cpp**
 och installera. Du kan också använda följande kommando från Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Kommando" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="Steg för att lägga till vattenstämpel till PPT via C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Du behöver [aspose.slides.dll](https://downloads.aspose.com/slides/cpp) för att prova följande arbetsflöde i din egen miljö." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ladda PPT-filer med en instans av presentationsklassen
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Få den första bilden
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lägg till en AutoShape av rektangeltyp
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lägg till TextFrame till rektangeln
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Skapa objektet Stycke för textram
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Skapa delobjekt för stycke
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lägg till vattenstämpel med set\_Text()
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Spara dokument
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="Systemkrav" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Slides för C++ stöder på alla större plattformar och operativsystem. Se till att du har följande förutsättningar.

{{% /blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Lägg till vattenstämpel till PPT - C++" offSpacer="" %}}

```cs

// Load the desired PPT File
SharedPtr<Presentation> pres = MakeObject<Presentation>(u"templatePath.ppt");

// Access first slide
SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Add an AutoShape of Rectangle type
SharedPtr<IAutoShape>  ashp = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150, 75, 150, 50);

ashp->get_FillFormat()->set_FillType(FillType::NoFill);

// Add TextFrame to the Rectangle
ashp->AddTextFrame(u" ");

// Accessing the text frame
SharedPtr<ITextFrame>  txtFrame = ashp->get_TextFrame();

// Create the Paragraph object for text frame
SharedPtr<IParagraph> paragraph = txtFrame->get_Paragraphs()->idx_get(0);

// Create Portion object for paragraph
SharedPtr<IPortion> portion = paragraph->get_Portions()->idx_get(0);
portion->set_Text(u"Watermark Text Watermark Text Watermark Text");

//Adding another shape
SharedPtr<IAutoShape>  ashape2 = slide->get_Shapes()->AddAutoShape(ShapeType::Triangle, 200, 365, 400, 150);

//Reorder shape
slide->get_Shapes()->Reorder(2, ashape2);

// Save PPT to Disk
pres->Save(u"outPath.ppt", Aspose::Slides::Export::SaveFormat::Ppt);  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Om Aspose.Slides för C++ API" %}}

 Aspose.Slides API kan användas för att läsa, skriva, manipulera och konvertera Microsoft PowerPoint-dokument till PDF, XPS, HTML, TIFF, ODP och olika andra format. Man kan skapa nya filer från grunden och spara dem i relevanta format som stöds. Aspose.Slides är ett fristående API för att skapa, analysera eller manipulera presentationer, bilder och element och det är inte beroende av någon programvara som Microsoft eller OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Watermark PPT via Online App" sectionDescription="Add watermark to PPT documents by visiting our [Live Demos website](https://products.aspose.app/slides/watermark). The live demo has the following benefits" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Just upload your PPT file, set your watermark and hit \"Add\" button" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Instantly get the download link for the resultant file" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PPT" readMoreLink="https://docs.fileformat.com/presentation/ppt/" >}}
A file with PPT extension represents PowerPoint file that consists of a collection of slides for displaying as SlideShow. It specifies the Binary File Format used by Microsoft PowerPoint 97-2003. A PPT file can contain several different types of information such as text, bulleted points, images, multimedia and other embedded OLE objects. Microsoft came up with newer file format for PowerPoint, known as PPTX, from 2007 onwards that is based on Office OpenXML and is different from this binary file format. Several other application programs such as OpenOffice Impress and Apple Keynote can also create PPT files.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andra vattenmärkeformat som stöds" subTitle="Med C++ kan man enkelt vattenmärka olika format inklusive." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/watermark/pptx/" name="PPTX" description="Öppna XML-presentationsformat" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}