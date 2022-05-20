---
title: Visualizza i formati di file POTX tramite .NET
weight: 5740
url: /it/net/viewer/potx/ 
description: Codice sorgente C# per caricare, eseguire il rendering e visualizzare documenti POTX su piattaforme .NET Framework, .NET Core, Windows Azure, Mono o Xamarin.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Visualizzatore di file POTX per .NET" h2="Visualizza file di presentazione come POTX senza Microsoft PowerPoint o Office Automation" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="POTX" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="POTX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/net" installationsDocsLink="https://docs.aspose.com/slides/net" nugetLink="https://www.nuget.org/packages/aspose.slides.net" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/net" learnAsLink="https://docs.aspose.com/slides/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Come visualizzare il file POTX usando C#" %}}

 Per visualizzare il file POTX, utilizzeremo
 [Aspose.Slides per .NET](https://products.aspose.com/slides/it/net)
 API che è un'API ricca di funzionalità, potente e facile da usare per la piattaforma C# da utilizzare con qualsiasi visualizzatore. Aprire
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 gestore pacchetti, cerca
 **Aspose.Slides**
 e installa. È inoltre possibile utilizzare il seguente comando dalla Console di gestione pacchetti.

{{% blocks/products/pf/agp/code-block title="Comando della console di gestione dei pacchetti" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.NET

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="Passaggi per visualizzare POTX tramite C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Aspose.Slides consente agli sviluppatori di visualizzare facilmente il file POTX con poche righe di codice." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Crea un'istanza di un oggetto Presentazione e carica il file POTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Crea un'istanza di ResponsiveHtmlController per la formattazione
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Crea un'istanza di HtmlOptions e imposta la proprietà HtmlFormatter
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salva la presentazione POTX in formato HTML
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Chiama Process.Start con il percorso dell'HTML risultante per caricare il contenuto POTX nel browser predefinito
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Slides per .NET è supportato su tutti i principali sistemi operativi. Assicurati solo di avere i seguenti prerequisiti.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatibile con piattaforme .NET Framework, .NET Core, Windows Azure, Mono o Xamarin
- Ambiente di sviluppo come Microsoft Visual Studio
- Aspose.Slides per .NET referenziato nel tuo progetto

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Codice di esempio C# per visualizzare il file POTX" offSpacer="" %}}

```cs

string output = System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".html";

// instantiate a Presentation object & load the POTX file
using (var presentation = new Aspose.Slides.Presentation("templatepotx"))
{
    // create HTML export controller
    var controller = new Aspose.Slides.Export.ResponsiveHtmlController();
    // create an instance of HtmlOptions and set HtmlFormatter property
    var htmlOptions = new Aspose.Slides.Export.HtmlOptions 
    { 
        HtmlFormatter = Aspose.Slides.Export.HtmlFormatter.CreateCustomFormatter(controller) 
    };

    // save the presentation in HTML
    presentation.Save(output, Aspose.Slides.Export.SaveFormat.Html, htmlOptions);
}
// load HTML to view the presentation content
System.Diagnostics.Process.Start(output);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Informazioni su Aspose.Slides per .NET API" %}}

 L'API Aspose.Slides può essere utilizzata per leggere, scrivere, manipolare e convertire documenti Microsoft PowerPoint in PDF, XPS, HTML, TIFF, ODP e vari altri formati. Si possono creare nuovi file da zero e salvarli nei relativi formati supportati. Aspose.Slides è un'API standalone per la creazione, l'analisi o la manipolazione di presentazioni, diapositive ed elementi e non dipende da alcun software come Microsoft o OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Free App to View POTX" sectionDescription="Check our live demos to [View POTX](https://products.aspose.app/slides/viewer/potx) with following benefits." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write or compile code" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload POTX file and hit the \"View\" button" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Download POTX file from the link, if required" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="POTX" readMoreLink="https://docs.fileformat.com/presentation/potx/" >}}
Files with .POTX extension represent Microsoft PowerPoint template presentations that are created with Microsoft PowerPoint 2007 and above. This format was created to replace the POT file format that is based on the binary file format and is supported with PowerPoint 97-2003. The files generated can be used to create presentations that have same layout and other settings required to be applied to new files. These settings can include styles, backgrounds, colour palette, fonts and defaults. Such files are generated in order to create ready-to-use template files for official use.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Altri formati di visualizzazione supportati" subTitle="Usando C#, One può anche visualizzare molti altri formati di file tra cui." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/viewer/odp/" name="ODP" description="Formato di presentazione OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/viewer/otp/" name="OTP" description="Formato standard OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/viewer/pot/" name="POT" description="File modello di Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/viewer/potm/" name="POTM" description="File modello Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/viewer/pps/" name="PPS" description="Presentazione di PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/viewer/ppsm/" name="PPSM" description="Presentazione con attivazione macro" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/viewer/ppsx/" name="PPSX" description="Presentazione di PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/viewer/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/viewer/pptm/" name="PPTM" description="File di presentazione abilitato per le macro" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/viewer/pptx/" name="PPTX" description="Apri il formato di presentazione XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}