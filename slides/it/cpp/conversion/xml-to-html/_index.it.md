---
title: Converti XML in HTML tramite l'applicazione C++
weight: 230
url: /it/cpp/conversion/xml-to-html/ 
description: Esempio di codice di conversione C++ per documenti XML in formato HTML. Utilizzare il codice di esempio per la conversione batch da XML a HTML all'interno di qualsiasi applicazione C++.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Converti XML in HTML tramite C++" h2="Conversione da XML a HTML ad alte prestazioni utilizzando la libreria C++ senza la necessità dell'installazione di Microsoft PowerPoint." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="HTML" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XML" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/cpp" installationsDocsLink="https://docs.aspose.com/slides/cpp" nugetLink="https://www.nuget.org/packages/aspose.slides" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/cpp" learnAsLink="https://docs.aspose.com/slides/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Come convertire XML in HTML usando C++" %}}

 Per convertire XML in HTML, useremo
 [Aspose.Slides per C++](https://products.aspose.com/slides/it/cpp/)
 API che è un'API di conversione e manipolazione dei documenti ricca di funzionalità, potente e facile da usare per la piattaforma C++. Puoi scaricare direttamente la sua ultima versione, basta aprire
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 gestore pacchetti, cerca
 Aspose.Slides.Cpp
 e installa. È inoltre possibile utilizzare il seguente comando dalla Console di gestione pacchetti.

{{% blocks/products/pf/agp/code-block title="Comando" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Passaggi per convertire XML in HTML tramite C++" %}}

{{% blocks/products/pf/agp/text %}}

 Gli sviluppatori C++ possono convertire facilmente file XML in HTML in poche righe di codice.

{{% /blocks/products/pf/agp/text %}}

1. Caricare il file XML con Aspose.Slides per l'oggetto presentazione C++.
1. Chiamare il metodo Save().
1. Passa il percorso del file di output con l'estensione del file (HTML).
1. Il file HTML verrà salvato nel percorso specificato.
1. Aprire il file HTML nel programma compatibile.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Prima di eseguire il codice di esempio di conversione C++, assicurati di disporre dei prerequisiti seguenti.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatibile con C++ Runtime Environment per Windows 32 bit, Windows 64 bit e Linux 64 bit.
- Aspose.Slides per C++ DLL a cui si fa riferimento nel progetto.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Codice sorgente di conversione da XML a HTML C++" offSpacer="" %}}

```cs
// Load the XML.
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"sourceFile.xml");
// Save in HTML format.
prs->Save(u"convertedFile.html", Aspose::Slides::Export::SaveFormat::Html);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension=""
        sectionTitle="App gratuita da convertire XML in HTML" 
        sectionDescription="[Prova la nostra app gratuita Collage](https://products.aspose.app/slides/collage/)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Altre conversioni supportate" subTitle="Puoi anche convertire XML in molti altri formati di file, inclusi alcuni elencati di seguito." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/conversion/xml-to-bmp/" name="XML TO BMP" description="Immagine bitmap" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/conversion/xml-to-emf/" name="XML TO EMF" description="Formato Metafile migliorato" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/conversion/xml-to-gif/" name="XML TO GIF" description="Formato di scambio grafico" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/conversion/xml-to-jpeg/" name="XML TO JPEG" description="Immagine JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/conversion/xml-to-odp/" name="XML TO ODP" description="Formato di presentazione OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/conversion/xml-to-otp/" name="XML TO OTP" description="Formato standard OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/conversion/xml-to-pdf/" name="XML TO PDF" description="Formato documento portatile" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/conversion/xml-to-png/" name="XML TO PNG" description="Grafica di rete portatile" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/conversion/xml-to-pot/" name="XML TO POT" description="File modello di Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/conversion/xml-to-potm/" name="XML TO POTM" description="File modello Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/conversion/xml-to-potx/" name="XML TO POTX" description="Presentazione del modello di Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/conversion/xml-to-pps/" name="XML TO PPS" description="Presentazione di PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/conversion/xml-to-ppsm/" name="XML TO PPSM" description="Presentazione con attivazione macro" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/conversion/xml-to-ppsx/" name="XML TO PPSX" description="Presentazione di PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/conversion/xml-to-ppt/" name="XML TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/conversion/xml-to-pptm/" name="XML TO PPTM" description="File di presentazione abilitato per le macro" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/conversion/xml-to-pptx/" name="XML TO PPTX" description="Apri il formato di presentazione XML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/conversion/xml-to-svg/" name="XML TO SVG" description="Grafica vettoriale scalabile" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/conversion/xml-to-tiff/" name="XML TO TIFF" description="Formato immagine contrassegnato" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/conversion/xml-to-xps/" name="XML TO XPS" description="Specifiche della carta XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}