---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Converti PPS in BMP in Python
weight: 1550
url: /it/python-net/conversion/pps-to-bmp/ 
keywords: "Convert, PowerPoint, PPS, BMP, Presentation, Python"
description: Codice di esempio per la conversione da PPS a BMP Python. Usa l'API Python di PowerPoint per la conversione batch di file PPS in file BMP.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Converti PPS in BMP in Python" h2="Potente libreria PowerPoint Python per convertire PPS in BMP"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/python-net"
  learnLink="https://docs.aspose.com/slides/python-net/"
  pricingLink="https://purchase.aspose.com/pricing/slides/python-net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Converti PPS in BMP in Python" %}}

Hai bisogno di convertire i file PPS in BMP a livello di codice? Utilizzando [*Aspose.Slides per Python tramite .NET*](https://products.aspose.com/slides/it/python-net/) qualsiasi sviluppatore può convertire PPS in formato BMP con poche righe di codice Python.

In quanto moderna API di elaborazione delle presentazioni, Aspose.Slides for Python crea rapidamente BMP da PPS. Verifica la qualità della conversione da PPS a BMP direttamente nel tuo [browser](https://products.aspose.app/slides/conversion). La libreria Aspose PowerPoint PPTX ti consente di convertire i file PPS in molti formati popolari.

È possibile installare la libreria da [PyPI](https://pypi.org/project/Aspose.Slides/) utilizzando il seguente comando pip:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Console/Terminale" >}}
```console
> pip install aspose.slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Salva PPS come BMP in Python" %}}

Usa l'app gratuita per vedere una dimostrazione del processo di conversione da PPS a BMP.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Questo codice di esempio mostra la conversione da PPS a BMP Python" >}}
```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.pps") as presentation:
    for slide in presentation.slides:
        slide.get_thumbnail(2, 2).save("presentation_slide_{0}.bmp".format(str(slide.slide_number)), drawing.imaging.ImageFormat.bmp)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Come convertire PPS in BMP in Python" intro="Questi sono i passaggi per convertire un file PPS in BMP usando Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carica il file PPS con un'istanza della classe Presentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chiama il metodo `save` mentre specifichi il percorso del file di output e SaveFormat.BMP come parametri{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Il file PPS verrà salvato nel percorso specificato{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Requisiti di sistema" intro="Prima di eseguire il codice sorgente di esempio di conversione Python, assicurati di disporre dei seguenti prerequisiti." %}}

- Sistema operativo basato su Microsoft Windows o Linux (vedi [altro](https://docs.aspose.com/slides/python-net/system-requirements/)).
- Python 3.5 o successivo
- Aspose.Slides per Python referenziato nel tuo progetto.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="App gratuita da convertire PPS in BMP"
  description="[Prova la nostra app gratuita per convertire PPT in BMP](https://products.aspose.app/slides/conversion/ppt-to-bmp)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Altre conversioni supportate" subTitle="Puoi anche convertire PPS in molti altri formati di file. Vedi altre conversioni supportate di seguito" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/python-net/conversion/pps-to-emf/" name="PPS TO EMF" description="Formato Metafile migliorato" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/python-net/conversion/pps-to-fodp/" name="PPS TO FODP" description="Presentazione XML piatta di OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/python-net/conversion/pps-to-gif/" name="PPS TO GIF" description="Formato di scambio grafico" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/python-net/conversion/pps-to-html/" name="PPS TO HTML" description="Hyper Text Markup Language" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/python-net/conversion/pps-to-jpg/" name="PPS TO JPG" description="Immagine JPEG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/python-net/conversion/pps-to-odp/" name="PPS TO ODP" description="Formato di presentazione OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/python-net/conversion/pps-to-otp/" name="PPS TO OTP" description="Formato standard OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/python-net/conversion/pps-to-pdf/" name="PPS TO PDF" description="Formato documento portatile" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/python-net/conversion/pps-to-png/" name="PPS TO PNG" description="Grafica di rete portatile" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/python-net/conversion/pps-to-pot/" name="PPS TO POT" description="File modello di Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/python-net/conversion/pps-to-potm/" name="PPS TO POTM" description="File modello Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/python-net/conversion/pps-to-potx/" name="PPS TO POTX" description="Presentazione del modello di Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/python-net/conversion/pps-to-ppsm/" name="PPS TO PPSM" description="Presentazione con attivazione macro" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/python-net/conversion/pps-to-ppsx/" name="PPS TO PPSX" description="Presentazione di PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/python-net/conversion/pps-to-ppt/" name="PPS TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/python-net/conversion/pps-to-pptm/" name="PPS TO PPTM" description="File di presentazione abilitato per le macro" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/python-net/conversion/pps-to-pptx/" name="PPS TO PPTX" description="Apri il formato di presentazione XML" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/python-net/conversion/pps-to-svg/" name="PPS TO SVG" description="Grafica vettoriale scalabile" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/python-net/conversion/pps-to-swf/" name="PPS TO SWF" description="Formato SWF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/python-net/conversion/pps-to-tiff/" name="PPS TO TIFF" description="Formato immagine contrassegnato" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/python-net/conversion/pps-to-xps/" name="PPS TO XPS" description="Specifiche della carta XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
