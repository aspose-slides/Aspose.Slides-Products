---
title: Converti PPSM in JPEG tramite C#
weight: 8340
url: /it/net/conversion/ppsm-to-jpeg/ 
description: Codice di esempio per la conversione da PPSM a JPEG C#. Utilizzare il codice di esempio API per la conversione batch di file PPSM in JPEG all'interno di VB.NET, Asp.NET o qualsiasi applicazione basata su .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Converti PPSM in JPEG tramite C#" h2="Esporta file PowerPoint® PPSM in JPEG su piattaforme .NET Framework, .NET Core, Windows Azure, Mono o Xamarin" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="JPEG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PPSM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/net" installationsDocsLink="https://docs.aspose.com/slides/net" nugetLink="https://www.nuget.org/packages/aspose.slides.net" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/net" learnAsLink="https://docs.aspose.com/slides/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Come convertire PPSM in JPEG usando C#" %}}

 Per convertire PPSM in JPEG, useremo
 [Aspose.Slides per .NET](https://products.aspose.com/slides/it/net)
 API che è un'API di conversione e manipolazione dei documenti ricca di funzionalità, potente e facile da usare per la piattaforma C#. Aprire
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 gestore pacchetti, cerca
 Aspose.Slides
 e installa. È inoltre possibile utilizzare il seguente comando dalla Console di gestione pacchetti.

{{% blocks/products/pf/agp/code-block title="Comando della console di gestione dei pacchetti" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.NET

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="Passaggi per convertire PPSM in JPEG tramite C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Gli sviluppatori .NET possono facilmente caricare e convertire file PPSM in JPEG in poche righe di codice." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Carica il file PPSM con un'istanza della classe Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Scorri ogni diapositiva nella presentazione
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Crea un'immagine in scala reale come Bitmap ad ogni iterazione
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Chiama il metodo Bitmap.Save con estensione file JPEG e ImageFormat.Jpeg come parametri
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Prima di eseguire il codice sorgente di esempio di conversione .NET, assicurarsi di disporre dei prerequisiti seguenti.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatibile con piattaforme .NET Framework, .NET Core, Windows Azure, Mono o Xamarin.
- Ambiente di sviluppo come Microsoft Visual Studio.
- Aspose.Slides per .NET DLL a cui si fa riferimento nel progetto.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Questo codice di esempio mostra la conversione da PPSM a JPEG C#" offSpacer="" %}}

```cs
using (var presentation = new Presentation("template.ppsm"))
{
    // iterate over all slides in the presentation
    foreach (var slide in presentation.Slides)
    {
        // create a full scale image
        var bitmap = slide.GetThumbnail(1f, 1f);

        // save the image to disk in JPEG format
        bitmap.Save(string.Format("Slide_{0}.jpeg", slide.SlideNumber), System.Drawing.Imaging.ImageFormat.Jpeg);
    }
} 

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension=""
        sectionTitle="App gratuita da convertire PPSM in JPEG" 
        sectionDescription="[Prova la nostra app gratuita per convertire PPT in JPG](https://products.aspose.app/slides/conversion/ppt-to-jpg)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Altre conversioni supportate" subTitle="Puoi anche convertire PPSM in molti altri formati di file inclusi alcuni elencati di seguito." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/conversion/ppsm-to-bmp/" name="PPSM TO BMP" description="Immagine bitmap" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/conversion/ppsm-to-emf/" name="PPSM TO EMF" description="Formato Metafile migliorato" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/conversion/ppsm-to-gif/" name="PPSM TO GIF" description="Formato di scambio grafico" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/conversion/ppsm-to-html/" name="PPSM TO HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/conversion/ppsm-to-odp/" name="PPSM TO ODP" description="Formato di presentazione OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/conversion/ppsm-to-otp/" name="PPSM TO OTP" description="Formato standard OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/conversion/ppsm-to-pdf/" name="PPSM TO PDF" description="Formato documento portatile" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/conversion/ppsm-to-png/" name="PPSM TO PNG" description="Grafica di rete portatile" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/conversion/ppsm-to-pot/" name="PPSM TO POT" description="File modello di Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/conversion/ppsm-to-potm/" name="PPSM TO POTM" description="File modello Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/conversion/ppsm-to-potx/" name="PPSM TO POTX" description="Presentazione del modello di Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/conversion/ppsm-to-pps/" name="PPSM TO PPS" description="Presentazione di PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/conversion/ppsm-to-ppsx/" name="PPSM TO PPSX" description="Presentazione di PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/conversion/ppsm-to-ppt/" name="PPSM TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/conversion/ppsm-to-pptm/" name="PPSM TO PPTM" description="File di presentazione abilitato per le macro" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/conversion/ppsm-to-pptx/" name="PPSM TO PPTX" description="Apri il formato di presentazione XML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/conversion/ppsm-to-svg/" name="PPSM TO SVG" description="Grafica vettoriale scalabile" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/conversion/ppsm-to-swf/" name="PPSM TO SWF" description="Formato SWF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/conversion/ppsm-to-tiff/" name="PPSM TO TIFF" description="Formato immagine contrassegnato" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/conversion/ppsm-to-xps/" name="PPSM TO XPS" description="Specifiche della carta XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}