---
title: Proteggi e blocca il documento PPTX tramite C++
weight: 5130
url: /it/cpp/protect/pptx/ 
description: Codice di esempio C++ per bloccare il file PPTX utilizzando la password su C++ Runtime Environment per Windows 32 bit, Windows 64 bit e Linux 64 bit.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Crittografa i file PPTX tramite C++" h2="Proteggi con password le presentazioni PowerPoint, incluso il formato PPTX, utilizzando la libreria .NET." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PPTX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/cpp/" installationsDocsLink="https://docs.aspose.com/slides/cpp/" nugetLink="https://www.nuget.org/packages/aspose.slides" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/cpp" learnAsLink="https://docs.aspose.com/slides/cpp/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Come proteggere il file PPTX usando C++" %}}

 Per proteggere il file PPTX, useremo
 [Aspose.Slides per C++](https://products.aspose.com/slides/it/cpp)
 API che è un'API di crittografia dei documenti ricca di funzionalità, potente e facile da usare per la piattaforma C++. Puoi scaricare direttamente la sua ultima versione, basta aprire
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 gestore pacchetti, cerca
 **Aspose.Slides.Cpp**
 e installa. È inoltre possibile utilizzare il seguente comando dalla Console di gestione pacchetti.

{{% blocks/products/pf/agp/code-block title="Aspose.Slides" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="Passaggi per proteggere i file PPTX tramite C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="La protezione dei documenti utilizzando le API Aspose.Slides può essere eseguita con poche righe di codice." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Carica file PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Imposta la password usando il metodo get\_ProtectionManager()->Encrypt(.).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salva la presentazione PPTX protetta
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Slides per C++ supporta su tutte le principali piattaforme e sistemi operativi. Assicurati di avere i seguenti prerequisiti.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatibile con C++ Runtime Environment per Windows 32 bit, Windows 64 bit e Linux 64 bit.
- Aspose.Slides per C++ DLL a cui si fa riferimento nel progetto.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Comando" offSpacer="" %}}

```cs

const String sourceFilePath = u"SourcePath\SourceFile.pptx";
const String outputFilePath = u"OutputPath\OutPutFile.pptx";

// Load the PPTX file
SharedPtr<Presentation> pptxFile = MakeObject<Presentation>(sourceFilePath);

// Protect with password
pptxFile->get_ProtectionManager()->Encrypt(u"password");

// Save the PPTX
pptxFile->Save(outputFilePath, SaveFormat::Pptx);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="Informazioni su Aspose.Slides per l'API C++" %}}

 L'API Aspose.Slides può essere utilizzata per leggere, scrivere, manipolare e convertire documenti Microsoft PowerPoint in PDF, XPS, HTML, TIFF, ODP e vari altri formati. Si possono creare nuovi file da zero e salvarli nei relativi formati supportati. Aspose.Slides è un'API standalone per la creazione, l'analisi o la manipolazione di presentazioni, diapositive ed elementi e non dipende da alcun software come Microsoft o OpenOffice.  



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Free App to Protect PPTX" sectionDescription="Check our live demos to [encrypt PPTX files](https://products.aspose.app/slides/protect/pptx) with following benefits." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write or compile code" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload PPTX file and hit the \"Unlock\" button" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Download the resultant PPTX file from the link" >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PPTX" readMoreLink="https://docs.fileformat.com/presentation/pptx/" >}}
Files with PPTX extension are presentation files created with popular Microsoft PowerPoint application. Unlike the previous version of presentation file format PPT which was binary, the PPTX format is based on the Microsoft PowerPoint open XML presentation file format. A presentation file is a collection of slides where each slide can comprise of text, images, formatting, animations, and other media. These slides are presented to audience in the form of slideshows with custom presentation settings.

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Altri documenti di protezione supportati" subTitle="Usando C++, è possibile proteggere altri file tra cui." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/protect/odp/" name="ODP" description="Formato di presentazione OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/protect/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}