---
title: Redigera eller visa PPT-dokumentmetadata via C++
weight: 6080
url: /sv/cpp/metadata/ppt/ 
description: C++ exempelkod för att redigera eller visa PPT-filmetadata i C++ Runtime Environment för Windows 32 bitar, Windows 64 bitar och Linux 64 bitar.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Extrahera PPT-metadata via C++" h2="Bygg dina egna C++-appar för att lägga till, redigera, ta bort eller extrahera metadata från PPT-filer med hjälp av API:er på serversidan." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/cpp" installationsDocsLink="https://docs.aspose.com/slides/cpp" nugetLink="https://www.nuget.org/packages/aspose.slides" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/cpp" learnAsLink="https://docs.aspose.com/slides/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Hur man får PPT-metadata med C++" %}}

 För att extrahera PPT-metadata kommer vi att använda
 [Aspose.Slides för C++](https://products.aspose.com/slides/sv/cpp)
 API som är ett funktionsrikt, kraftfullt och lättanvänt API för extraktion av dokumentmetadata för C++-plattformen. Du kan ladda ner den senaste versionen direkt, bara öppna
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


{{< blocks/products/pf/agp/feature-section-col title="Steg för att extrahera metadata från PPT via C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Klassen IDocumentProperties representerar dokumentegenskaperna som är associerade med en presentationsfil. Utvecklare kan använda den här egenskapen för att komma åt metadata enligt beskrivningen nedan." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ladda PPT-fil
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Hämta dokumentegenskaper med get\_DocumentProperties()
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
iterera för alla egenskaper med loop
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Skriv ut egenskaper med varje iteration.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="Systemkrav" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Slides för C++ stöder på alla större plattformar och operativsystem. Se till att du har följande förutsättningar.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows eller ett kompatibelt operativsystem med C++ Runtime Environment för Windows 32 bit, Windows 64 bit och Linux 64 bit.
- Aspose.Slides för C++ DLL som refereras till i ditt projekt.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Extrahera metadata för PPT - C++" offSpacer="" %}}

```cs

const String templatePath = u"../templates/AccessModifyingProperties.ppt";

System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(templatePath);

// Create a reference to DocumentProperties object associated with Prsentation
System::SharedPtr<IDocumentProperties> documentProperties = presentation->get_DocumentProperties();

for (int32_t i = 0; i get_CountOfCustomProperties(); i++){
	System::Console::WriteLine(u"Custom Property Name : {0}", documentProperties->GetCustomPropertyName(i));
	System::Console::WriteLine(u"Custom Property Vlaue : {0}", documentProperties->idx_get(documentProperties->GetCustomPropertyName(i)));
}  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Om Aspose.Slides för C++ API" %}}

 Aspose.Slides API kan användas för att läsa, skriva, manipulera och konvertera Microsoft PowerPoint-dokument till PDF, XPS, HTML, TIFF, ODP och olika andra format. Man kan skapa nya filer från grunden och spara dem i relevanta format som stöds. Aspose.Slides är ett fristående API för att skapa, analysera eller manipulera presentationer, bilder och element och det är inte beroende av någon programvara som Microsoft eller OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Extract Metadata of PPT via Online App" sectionDescription="View & edit Metadata to PPT documents by using our [Live Demos](https://products.aspose.app/slides/metadata) with following benefits." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your PPT file & edit document properties" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Instantly get the download link for the resultant file" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PPT" readMoreLink="https://docs.fileformat.com/presentation/ppt/" >}}
A file with PPT extension represents PowerPoint file that consists of a collection of slides for displaying as SlideShow. It specifies the Binary File Format used by Microsoft PowerPoint 97-2003. A PPT file can contain several different types of information such as text, bulleted points, images, multimedia and other embedded OLE objects. Microsoft came up with newer file format for PowerPoint, known as PPTX, from 2007 onwards that is based on Office OpenXML and is different from this binary file format. Several other application programs such as OpenOffice Impress and Apple Keynote can also create PPT files.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andra metadataformat som stöds" subTitle="Med C++ kan man också manipulera metadata i många andra format inklusive" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/metadata/odp/" name="ODP" description="OpenDocument presentationsformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/metadata/otp/" name="OTP" description="OpenDocument standardformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/metadata/pot/" name="POT" description="Microsoft PowerPoint-mallfiler" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/metadata/potm/" name="POTM" description="Microsoft PowerPoint-mallfil" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/metadata/potx/" name="POTX" description="Presentation av Microsoft PowerPoint-mall" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/metadata/pps/" name="PPS" description="PowerPoint-bildspel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/metadata/ppsm/" name="PPSM" description="Makroaktiverat bildspel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/metadata/ppsx/" name="PPSX" description="PowerPoint-bildspel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/metadata/pptm/" name="PPTM" description="Makroaktiverad presentationsfil" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/metadata/pptx/" name="PPTX" description="Öppna XML-presentationsformat" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}