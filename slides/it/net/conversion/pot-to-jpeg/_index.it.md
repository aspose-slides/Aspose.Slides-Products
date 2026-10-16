---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Converti POT in JPEG tramite C#
weight: 6650
url: /it/net/conversion/pot-to-jpeg/ 
description: Codice di esempio per la conversione da POT a JPEG C#. Utilizzare il codice di esempio API per la conversione batch di file POT in JPEG all'interno di VB.NET, Asp.NET o qualsiasi applicazione basata su .NET.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Converti POT in JPEG tramite C#" h2="Esporta file PowerPoint® POT in JPEG su piattaforme .NET Framework, .NET Core, Windows Azure, Mono o Xamarin"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Come convertire POT in JPEG usando C#" %}}

Per convertire POT in JPEG, useremo
 [Aspose.Slides per .NET](https://products.aspose.com/slides/it/net)
 API che è un'API di conversione e manipolazione dei documenti ricca di funzionalità, potente e facile da usare per la piattaforma C#. Aprire
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 gestore pacchetti, cerca
 Aspose.Slides
 e installa. È inoltre possibile utilizzare il seguente comando dalla Console di gestione pacchetti.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Comando della console di gestione dei pacchetti" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Questo codice di esempio mostra la conversione da POT a JPEG C#" >}}
```cs
using (var presentation = new Presentation("template.pot"))
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
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Passaggi per convertire POT in JPEG tramite C#" intro="Gli sviluppatori .NET possono facilmente caricare e convertire file POT in JPEG in poche righe di codice." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carica il file POT con un'istanza della classe Presentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Scorri ogni diapositiva nella presentazione{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Crea un'immagine in scala reale come Bitmap ad ogni iterazione{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chiama il metodo Bitmap.Save con estensione file JPEG e ImageFormat.Jpeg come parametri{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Requisiti di sistema" intro="Prima di eseguire il codice sorgente di esempio di conversione .NET, assicurarsi di disporre dei prerequisiti seguenti." %}}

- Microsoft Windows o un sistema operativo compatibile con piattaforme .NET Framework, .NET Core, Windows Azure, Mono o Xamarin.
- Ambiente di sviluppo come Microsoft Visual Studio.
- Aspose.Slides per .NET DLL a cui si fa riferimento nel progetto.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="App gratuita da convertire POT in JPEG"
  description="[Prova la nostra app gratuita per convertire PPT in JPG](https://products.aspose.app/slides/conversion/ppt-to-jpg)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Altre conversioni supportate" subTitle="Puoi anche convertire POT in molti altri formati di file, inclusi alcuni elencati di seguito." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/net/conversion/pot-to-bmp/" name="POT TO BMP" description="Immagine bitmap" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/net/conversion/pot-to-emf/" name="POT TO EMF" description="Formato Metafile migliorato" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/net/conversion/pot-to-gif/" name="POT TO GIF" description="Formato di scambio grafico" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/net/conversion/pot-to-html/" name="POT TO HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/net/conversion/pot-to-odp/" name="POT TO ODP" description="Formato di presentazione OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/net/conversion/pot-to-otp/" name="POT TO OTP" description="Formato standard OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/net/conversion/pot-to-pdf/" name="POT TO PDF" description="Formato documento portatile" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/net/conversion/pot-to-png/" name="POT TO PNG" description="Grafica di rete portatile" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/net/conversion/pot-to-potm/" name="POT TO POTM" description="File modello Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/net/conversion/pot-to-potx/" name="POT TO POTX" description="Presentazione del modello di Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/net/conversion/pot-to-pps/" name="POT TO PPS" description="Presentazione di PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/net/conversion/pot-to-ppsm/" name="POT TO PPSM" description="Presentazione con attivazione macro" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/net/conversion/pot-to-ppsx/" name="POT TO PPSX" description="Presentazione di PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/net/conversion/pot-to-ppt/" name="POT TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/net/conversion/pot-to-pptm/" name="POT TO PPTM" description="File di presentazione abilitato per le macro" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/net/conversion/pot-to-pptx/" name="POT TO PPTX" description="Apri il formato di presentazione XML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/net/conversion/pot-to-svg/" name="POT TO SVG" description="Grafica vettoriale scalabile" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/net/conversion/pot-to-swf/" name="POT TO SWF" description="Formato SWF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/net/conversion/pot-to-tiff/" name="POT TO TIFF" description="Formato immagine contrassegnato" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/net/conversion/pot-to-xps/" name="POT TO XPS" description="Specifiche della carta XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
