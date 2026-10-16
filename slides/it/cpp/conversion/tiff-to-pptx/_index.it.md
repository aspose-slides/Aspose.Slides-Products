---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Converti TIFF in PPTX tramite l'applicazione C++
weight: 6570
url: /it/cpp/conversion/tiff-to-pptx/ 
description: Esempio di codice di conversione C++ per documenti TIFF in formato PPTX. Utilizzare il codice di esempio per la conversione batch da TIFF a PPTX all'interno di qualsiasi applicazione C++.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Converti TIFF in PPTX tramite C++" h2="Conversione da TIFF a PPTX ad alte prestazioni utilizzando la libreria C++ senza la necessità dell'installazione di Microsoft PowerPoint."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/cpp"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Come convertire TIFF in PPTX usando C++" %}}

Per convertire TIFF in PPTX, useremo
 [Aspose.Slides per C++](https://products.aspose.com/slides/it/cpp/)
 API che è un'API di conversione e manipolazione dei documenti ricca di funzionalità, potente e facile da usare per la piattaforma C++. Puoi scaricare direttamente la sua ultima versione, basta aprire
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 gestore pacchetti, cerca
 Aspose.Slides.Cpp
 e installa. È inoltre possibile utilizzare il seguente comando dalla Console di gestione pacchetti.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Comando" >}}
```cs

PM> Install-Package Aspose.Slides.Cpp

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Codice sorgente di conversione da TIFF a PPTX C++" >}}
```cs
// Load the TIFF.
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"sourceFile.tiff");
// Save in PPTX format.
prs->Save(u"convertedFile.pptx", Aspose::Slides::Export::SaveFormat::Pptx);

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Passaggi per convertire TIFF in PPTX tramite C++" intro="Gli sviluppatori C++ possono convertire facilmente file TIFF in PPTX in poche righe di codice." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Caricare il file TIFF con Aspose.Slides per C++ Presentation Object.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chiamare il metodo Save().{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Passare il percorso del file di output con l'estensione del file (PPTX).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Il file PPTX verrà salvato nel percorso specificato.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Aprire il file PPTX nel programma compatibile.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Requisiti di sistema" intro="Prima di eseguire il codice di esempio di conversione C++, assicurati di disporre dei prerequisiti seguenti." %}}

- Microsoft Windows o un sistema operativo compatibile con C++ Runtime Environment per Windows 32 bit, Windows 64 bit e Linux 64 bit.
- Aspose.Slides per C++ DLL a cui si fa riferimento nel progetto.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="App gratuita da convertire TIFF in PPTX"
  description="[Prova la nostra app gratuita MP4 To MP3](https://products.aspose.app/slides/video/mp4-to-mp3/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Altre conversioni supportate" subTitle="Puoi anche convertire TIFF in molti altri formati di file, inclusi alcuni elencati di seguito." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/cpp/conversion/tiff-to-bmp/" name="TIFF TO BMP" description="Immagine bitmap" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/cpp/conversion/tiff-to-emf/" name="TIFF TO EMF" description="Formato Metafile migliorato" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/cpp/conversion/tiff-to-gif/" name="TIFF TO GIF" description="Formato di scambio grafico" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/cpp/conversion/tiff-to-html/" name="TIFF TO HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/cpp/conversion/tiff-to-jpeg/" name="TIFF TO JPEG" description="Immagine JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/cpp/conversion/tiff-to-odp/" name="TIFF TO ODP" description="Formato di presentazione OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/cpp/conversion/tiff-to-otp/" name="TIFF TO OTP" description="Formato standard OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/cpp/conversion/tiff-to-pdf/" name="TIFF TO PDF" description="Formato documento portatile" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/cpp/conversion/tiff-to-png/" name="TIFF TO PNG" description="Grafica di rete portatile" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/cpp/conversion/tiff-to-pot/" name="TIFF TO POT" description="File modello di Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/cpp/conversion/tiff-to-potm/" name="TIFF TO POTM" description="File modello Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/cpp/conversion/tiff-to-potx/" name="TIFF TO POTX" description="Presentazione del modello di Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/cpp/conversion/tiff-to-pps/" name="TIFF TO PPS" description="Presentazione di PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/cpp/conversion/tiff-to-ppsm/" name="TIFF TO PPSM" description="Presentazione con attivazione macro" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/cpp/conversion/tiff-to-ppsx/" name="TIFF TO PPSX" description="Presentazione di PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/cpp/conversion/tiff-to-ppt/" name="TIFF TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/cpp/conversion/tiff-to-pptm/" name="TIFF TO PPTM" description="File di presentazione abilitato per le macro" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/cpp/conversion/tiff-to-svg/" name="TIFF TO SVG" description="Grafica vettoriale scalabile" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/cpp/conversion/tiff-to-xml/" name="TIFF TO XML" description="Linguaggio di markup estensibile" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/cpp/conversion/tiff-to-xps/" name="TIFF TO XPS" description="Specifiche della carta XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
