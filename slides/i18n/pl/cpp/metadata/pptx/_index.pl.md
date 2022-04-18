---
title: Edytuj lub przeglądaj metadane dokumentu PPTX za pomocą C++
weight: 3950
url: /pl/cpp/metadata/pptx/ 
description: Przykładowy kod C++ do edycji lub przeglądania metadanych pliku PPTX w C++ Runtime Environment dla Windows 32-bitowy, Windows 64-bitowy i Linux 64-bitowy.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Wyodrębnij metadane PPTX za pomocą C++" h2="Twórz własne aplikacje w języku C++, aby dodawać, edytować, usuwać lub wyodrębniać metadane z plików PPTX za pomocą interfejsów API po stronie serwera." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/cpp" installationsDocsLink="https://docs.aspose.com/slides/cpp" nugetLink="https://www.nuget.org/packages/aspose.slides" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/cpp" learnAsLink="https://docs.aspose.com/slides/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Jak uzyskać metadane PPTX za pomocą C++?" %}}

 Aby wyodrębnić metadane PPTX, użyjemy
 [Aspose.Slides dla C++](https://products.aspose.com/slides/cpp)
 API, które jest bogatym w funkcje, wydajnym i łatwym w użyciu interfejsem API ekstrakcji metadanych dokumentów dla platformy C++. Możesz pobrać jego najnowszą wersję bezpośrednio, po prostu otwórz
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


{{< blocks/products/pf/agp/feature-section-col title="Kroki wyodrębniania metadanych PPTX za pomocą C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Klasa IdocumentProperties reprezentuje właściwości dokumentu skojarzone z plikiem prezentacji. Deweloperzy mogą używać tej właściwości, aby uzyskać dostęp do metadanych, jak opisano poniżej." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Załaduj plik PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Pobierz właściwości dokumentu za pomocą get\_DocumentProperties()
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
iteruj dla wszystkich właściwości za pomocą pętli
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Właściwości wydruku w każdej iteracji.
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

{{% blocks/products/pf/agp/code-block title="Wyodrębnij metadane PPTX - C++" offSpacer="" %}}

```cs

const String templatePath = u"../templates/AccessModifyingProperties.pptx";

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

    {{% blocks/products/pf/agp/content h2="O Aspose.Slides dla C++ API" %}}

 Aspose.Slides API może być używany do czytania, pisania, manipulowania i konwertowania dokumentów Microsoft PowerPoint do PDF, XPS, HTML, TIFF, ODP i różnych innych formatów. Można tworzyć nowe pliki od podstaw i zapisywać je w odpowiednich obsługiwanych formatach. Aspose.Slides to samodzielny interfejs API do tworzenia, analizowania lub manipulowania prezentacjami, slajdami i elementami i nie zależy od żadnego oprogramowania, takiego jak Microsoft lub OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Extract Metadata of PPTX via Online App" sectionDescription="View & edit Metadata to PPTX documents by using our [Live Demos](https://products.aspose.app/slides/metadata) with following benefits." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your PPTX file & edit document properties" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Instantly get the download link for the resultant file" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PPTX" readMoreLink="https://docs.fileformat.com/presentation/pptx/" >}}
Files with PPTX extension are presentation files created with popular Microsoft PowerPoint application. Unlike the previous version of presentation file format PPT which was binary, the PPTX format is based on the Microsoft PowerPoint open XML presentation file format. A presentation file is a collection of slides where each slide can comprise of text, images, formatting, animations, and other media. These slides are presented to audience in the form of slideshows with custom presentation settings.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane formaty metadanych" subTitle="Używając C++, można również manipulować metadanymi wielu innych formatów, w tym" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/metadata/odp/" name="ODP" description="Format prezentacji OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/metadata/otp/" name="OTP" description="Standardowy format OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/metadata/pot/" name="POT" description="Pliki szablonów programu Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/metadata/potm/" name="POTM" description="Plik szablonu programu Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/metadata/potx/" name="POTX" description="Prezentacja szablonu Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/metadata/pps/" name="PPS" description="Pokaz slajdów programu PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/metadata/ppsm/" name="PPSM" description="Pokaz slajdów z obsługą makr" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/metadata/ppsx/" name="PPSX" description="Pokaz slajdów programu PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/metadata/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/metadata/pptm/" name="PPTM" description="Plik prezentacji z obsługą makr" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}