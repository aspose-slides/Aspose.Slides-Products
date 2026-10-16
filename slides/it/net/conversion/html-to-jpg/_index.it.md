---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Converti HTML in JPG in C#
weight: 150
url: /it/net/conversion/html-to-jpg/ 
keywords: HTML in JPG, Converti HTML in JPG, API C#, Libreria .NET, HTML, JPG
description: Converti HTML in JPG in C#. Usa l'API della libreria .NET per convertire i file HTML in immagini JPG
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Converti HTML in JPG in C#" h2="API PowerPoint .NET per la conversione di file HTML in immagini JPG su piattaforme NET Framework, .NET Core, Windows Azure, Mono o Xamarin"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Come convertire HTML in JPG in C#" %}}

Come posso convertire HTML in JPG nel codice?

Utilizzando [**Aspose.Slides for .NET**](https://products.aspose.com/slides/it/net/), qualsiasi sviluppatore o applicazione può convertire HTML in formato JPG con poche righe di codice C#.

In quanto moderna API di elaborazione dei documenti, Aspose.Slides per .NET esporta rapidamente i file HTML in JPG. La libreria Aspose PowerPoint ti consente di convertire HTML in JPG e molti altri formati di file

Per installare Aspose.Slides: Apri il gestore di pacchetti [NuGet](https://www.nuget.org/packages/aspose.slides.net). Cerca *Aspose.Slides* e installalo.
 
Oppure puoi installare **Aspose.Slides** eseguendo questo comando dalla Console di Gestione pacchetti.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Comando della console di gestione dei pacchetti" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Codice C# per convertire HTML in JPG" >}}
```cs
using (Presentation pres = new Presentation())
    {
        pres.Slides.AddFromHtml("page.html");
        pres.Slides.RemoveAt(0); // removes default empty slide

        for (var index = 0; index < pres.Slides.Count; index++)
        {
            ISlide slide = pres.Slides[index];
            slide.GetThumbnail(new Size(960, 720)).Save($"image-{index}.jpg", ImageFormat.Jpeg);
        }
    }
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Come convertire HTML in JPG in C#" intro="Gli sviluppatori e le applicazioni possono convertire HTML in JPG in questo modo:" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Crea un'istanza della classe Presentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carica il file HTML.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Aggiungi diapositive in base al contenuto del documento HTML.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Salva le diapositive come immagini JPG.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Requisiti di sistema" intro="Prima di eseguire il codice C# di conversione da HTML a JPG, la tua macchina deve avere questi prerequisiti:" %}}

- Microsoft Windows o un sistema operativo compatibile con piattaforme .NET Framework, .NET Core, Windows Azure, Mono o Xamarin.
- Ambiente di sviluppo come Microsoft Visual Studio.
- Nel progetto è stato fatto riferimento ad Aspose.Slides per .NET DLL.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Convertitore online gratuito"
  description="[Come convertire PPT in HTML in Python](https://products.aspose.com/slides/it/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Altre conversioni supportate" subTitle="Aspose.Slides supporta le operazioni di conversione per molti formati di file" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/net/conversion/ppt-to-bmp/" name="PPT TO BMP" description="Bitmap Image" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/net/conversion/ppt-to-emf/" name="PPT TO EMF" description="Enhanced Metafile Format" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/net/conversion/ppt-to-gif/" name="PPT TO GIF" description="Graphical Interchange Format" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/net/conversion/ppt-to-html/" name="PPT TO HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/net/conversion/ppt-to-png/" name="PPT TO PNG" description="PNG Image" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/net/conversion/ppt-to-odp/" name="PPT TO ODP" description="OpenDocument Presentation Format" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/net/conversion/ppt-to-otp/" name="PPT TO OTP" description="OpenDocument Standard Format" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/net/conversion/ppt-to-png/" name="PPT TO PNG" description="Portable Network Graphics" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/net/conversion/ppt-to-pot/" name="PPT TO POT" description="Microsoft PowerPoint Template Files" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/net/conversion/ppt-to-potm/" name="PPT TO POTM" description="Microsoft PowerPoint Template File" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/net/conversion/ppt-to-potx/" name="PPT TO POTX" description="Microsoft PowerPoint Template Presentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/net/conversion/ppt-to-pps/" name="PPT TO PPS" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/net/conversion/ppt-to-ppsm/" name="PPT TO PPSM" description="Macro-enabled Slide Show" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/net/conversion/ppt-to-ppsx/" name="PPT TO PPSX" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/net/conversion/ppt-to-pptm/" name="PPT TO PPTM" description="Macro-enabled Presentation File" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/net/conversion/ppt-to-pptx/" name="PPT TO PPTX" description="Open XML presentation Format" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/net/conversion/ppt-to-svg/" name="PPT TO SVG" description="Scalable Vector Graphics" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/net/conversion/ppt-to-swf/" name="PPT TO SWF" description="SWF Format" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/net/conversion/ppt-to-tiff/" name="PPT TO TIFF" description="Tagged Image Format" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/net/conversion/ppt-to-xps/" name="PPT TO XPS" description="XML Paper Specifications" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
