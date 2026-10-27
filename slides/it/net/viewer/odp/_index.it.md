---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Visualizzare ODP in C#
keywords: Visualizza ODP, Apri ODP, Visualizzatore ODP, ODP, API C#, Libreria .NET
weight: 8370
url: /it/net/viewer/odp/ 
description: Visualizza file ODP in C#. Usa Aspose.Slides for .NET per aprire file di presentazione e salvarli in HTML.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Visualizzare ODP in C#" h2="API C# per aprire file ODP e salvarli come HTML responsive."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="OTP,POT,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Visualizzare ODP con Aspose.Slides" %}}

Per visualizzare file ODP, usa l'API [Aspose.Slides for .NET](https://products.aspose.com/slides/it/net/), un'API C# potente, completa e facile da usare. Apri il gestore di pacchetti [NuGet](https://www.nuget.org/packages/aspose.slides.net), cerca **Aspose.Slides** e installalo. Puoi anche eseguire il seguente comando nella Console di Gestione pacchetti.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Comando della Console di Gestione pacchetti" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

Con [**Aspose.Slides for .NET**](/slides/it/net/) puoi caricare un file ODP e salvarlo come HTML responsive con poche righe di codice.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Codice C# per visualizzare ODP" >}}
```cs
using var presentation = new Presentation("presentation.odp");

var responsiveHtmlController = new ResponsiveHtmlController();
var htmlOptions = new HtmlOptions
{
    HtmlFormatter = HtmlFormatter.CreateCustomFormatter(responsiveHtmlController)
};

presentation.Save("output.html", SaveFormat.Html, htmlOptions);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Come visualizzare ODP in C#" intro="Aspose.Slides consente agli sviluppatori di visualizzare file ODP con poche righe di codice." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installa **Aspose.Slides for .NET**. Vedi [**Installazione**](https://docs.aspose.com/slides/net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Aggiungi la libreria come riferimento nel tuo progetto.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carica il file `ODP` con la classe `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Crea un oggetto `ResponsiveHtmlController` per un output HTML responsive.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Crea un oggetto `HtmlOptions` e imposta la proprietà `HtmlFormatter`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Salva il file ODP in formato HTML con `SaveFormat.Html`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Requisiti di sistema" intro="Aspose.Slides for .NET supporta tutti i principali sistemi operativi. Assicurati di soddisfare i seguenti prerequisiti." %}}

- Microsoft Windows o un sistema operativo compatibile con .NET Framework, .NET Core, Windows Azure, Mono o Xamarin
- Un ambiente di sviluppo come Microsoft Visual Studio
- Un riferimento ad Aspose.Slides for .NET nel tuo progetto

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/viewer-app label="Realizzato con Aspose.Slides" title="Visualizza file ODP online" description="L'app gratuita Aspose.Slides Viewer è realizzata con [Aspose.Slides for .NET](https://products.aspose.com/slides/it/net/), la stessa API del codice sopra. Aprila e scopri cosa può fare l'API con i tuoi file ODP." button="Apri Aspose.Slides Viewer" note="[Tutte le app gratuite](https://products.aspose.app/slides/family)" >}}
- Funziona nel browser, senza installare nulla.
- Scopri come Aspose.Slides visualizza i tuoi file prima di scrivere codice.
- Carica il tuo file ODP e visualizzane subito le diapositive.
- Funziona su desktop e dispositivi mobili, senza PowerPoint.
{{< /blocks/products/pf/slides-design-update-10-2026/viewer-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="ODP" readMoreLink="https://docs.fileformat.com/presentation/odp/" %}}

I file con estensione `.ODP` usano il formato OpenDocument Presentation definito dallo standard OASIS OpenDocument. Un file ODP contiene una raccolta di diapositive che possono includere testo, immagini, formattazione, animazioni e altri contenuti multimediali. Le applicazioni che supportano le presentazioni OpenDocument, come LibreOffice Impress e Apache OpenOffice Impress, possono aprire i file ODP.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Visualizzare altri file" subTitle="Puoi anche aprire e visualizzare presentazioni in altri formati." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/net/viewer/otp/" name="OTP" description="Modello di presentazione OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/net/viewer/pot/" name="POT" description="Modello di PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/net/viewer/potm/" name="POTM" description="Modello di PowerPoint con macro" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/net/viewer/potx/" name="POTX" description="Modello di PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/net/viewer/pps/" name="PPS" description="Presentazione di PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/net/viewer/ppsm/" name="PPSM" description="Presentazione di PowerPoint con macro" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/net/viewer/ppsx/" name="PPSX" description="Presentazione di PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/net/viewer/ppt/" name="PPT" description="Presentazione di PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/net/viewer/pptm/" name="PPTM" description="Presentazione di PowerPoint con macro" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/net/viewer/pptx/" name="PPTX" description="Presentazione di PowerPoint" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
