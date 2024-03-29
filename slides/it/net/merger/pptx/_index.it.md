---
title: Unisci file PPTX tramite .NET
weight: 3150
url: /it/net/merger/pptx/ 
description: Codice sorgente C# per combinare documenti PPTX su piattaforme .NET Framework, .NET Core, Windows Azure, Mono o Xamarin.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Unisci formati PPTX in C#" h2="Fusione di documenti PPTX nativi e ad alte prestazioni utilizzando Aspose.Slides lato server per API .NET, senza l'uso di software come Microsoft o Open Office, Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="PPTX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/net" installationsDocsLink="https://docs.aspose.com/slides/net" nugetLink="https://www.nuget.org/packages/aspose.slides.net" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/net" learnAsLink="https://docs.aspose.com/slides/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Come unire file PPTX usando C#" %}}

 Per unire il file PPTX, useremo
 [Aspose.Slides per .NET](https://products.aspose.com/slides/it/net)
 API che è un'API di fusione e manipolazione dei documenti ricca di funzionalità, potente e facile da usare per la piattaforma C#. Aprire
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 gestore pacchetti, cerca
 **Aspose.Slides**
 e installa. È inoltre possibile utilizzare il seguente comando dalla Console di gestione pacchetti.

{{% blocks/products/pf/agp/code-block title="Comando" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.NET

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="Passaggi per l'unione di file PPTX in C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Un documento di base che si unisce e si concatena con le API [Aspose.Slides for .NET](https://products.aspose.com/slides/it/net) può essere eseguito con poche righe di codice." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Carica tutti i file PPTX con il percorso completo.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Crea un documento come file di base
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Chiama il metodo pertinente per concatenare e unire i file uno per uno.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Chiama il metodo Save() e passa il nome del file (percorso completo) e il formato (PPTX) come parametro.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ora puoi aprire e utilizzare il file PPTX in Microsoft Office, Adobe PDF o qualsiasi altro programma compatibile.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Le nostre API sono supportate su tutte le principali piattaforme e sistemi operativi. Prima di eseguire il codice seguente, assicurati di avere i seguenti prerequisiti sul tuo sistema.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatibile con piattaforme .NET Framework, .NET Core, Windows Azure, Mono o Xamarin
- Ambiente di sviluppo come Microsoft Visual Studio
- Aspose.Slides per .NET DLL a cui si fa riferimento nel progetto - Installa da NuGet utilizzando il pulsante Download sopra

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Unisci file PPTX - C#" offSpacer="" %}}

```cs
var ps1 = new Presentation("presen1.pptx");
    var ps2 = new Presentation("presen2.pptx");
    
    //merged Presentation 
    var mp = new Presentation("template.pptx");
    while (mp.Slides.Count > 0){
        mp.Slides.RemoveAt(0);
    }
    // master slide
    var ms = mp.Masters[0];
    
    // The first PPTX presentation is added with its own styles.
    foreach (var slide in ps1.Slides){
        mp.Slides.AddClone(slide);
    }
    
    // The second PPTX presentation is added with template presentation styles using.
    foreach (var slide in ps2.Slides){
        mp.Slides.AddClone(slide, ms, true);
    }
    
    // It is possible to save the merged presentation to any supported format.
    mp.Save("mp.pptx", SaveFormat.Pptx);
    mp.Save("mp.pptx", SaveFormat.Pdf);  

    

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

{{< blocks/slides-app-widget  appName="merger" extension="" sectionTitle="Unisci file PDF online" sectionDescription="[Come unire PDF in Python](https://products.aspose.com/slides/it/python-net/merge/pdf/)" >}}

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Informazioni su Aspose.Slides per .NET API" %}}

 L'API Aspose.Slides può essere utilizzata per leggere, scrivere, manipolare e convertire documenti Microsoft PowerPoint in PDF, XPS, HTML, TIFF, ODP e vari altri formati. Si possono creare nuovi file da zero e salvarli nei relativi formati supportati. Aspose.Slides è un'API standalone per la creazione, l'analisi o la manipolazione di presentazioni, diapositive ed elementi e non dipende da alcun software come Microsoft o OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Online PPTX Merger Live Demos" sectionDescription="Merge PPTX documents right now by visiting our [Live Demos website](https://products.aspose.app/slides/merger). The live demo has the following benefits" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Just upload your PPTX files." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" It will be merged and concatenated instantly." >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PPTX" readMoreLink="https://docs.fileformat.com/presentation/pptx/" >}}
Files with PPTX extension are presentation files created with popular Microsoft PowerPoint application. Unlike the previous version of presentation file format PPT which was binary, the PPTX format is based on the Microsoft PowerPoint open XML presentation file format. A presentation file is a collection of slides where each slide can comprise of text, images, formatting, animations, and other media. These slides are presented to audience in the form of slideshows with custom presentation settings. 

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Altri formati di unione supportati" subTitle="Usando C#, One può anche unire molti altri formati di file tra cui." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/merger/odp/" name="ODP" description="Formato di presentazione OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/merger/otp/" name="OTP" description="Formato standard OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/merger/pot/" name="POT" description="File modello di Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/merger/potm/" name="POTM" description="File modello Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/merger/potx/" name="POTX" description="Presentazione del modello di Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/merger/pps/" name="PPS" description="Presentazione di PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/merger/ppsm/" name="PPSM" description="Presentazione con attivazione macro" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/merger/ppsx/" name="PPSX" description="Presentazione di PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/merger/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/merger/pptm/" name="PPTM" description="File di presentazione abilitato per le macro" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}