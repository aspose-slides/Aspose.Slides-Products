---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Converti PPT in SVG in Python
weight: 2390
url: /it/python-net/conversion/ppt-to-svg/ 
keywords: "Convert, PowerPoint, PPT, SVG, Presentation, Python"
description: Codice di esempio per la conversione da PPT a SVG Python. Usa l'API Python di PowerPoint per la conversione batch di file PPT in file SVG.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Converti PPT in SVG in Python" h2="Potente libreria PowerPoint Python per convertire PPT in SVG"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/python-net"
  learnLink="https://docs.aspose.com/slides/python-net/"
  pricingLink="https://purchase.aspose.com/pricing/slides/python-net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Converti PPT in SVG in Python" %}}

Hai bisogno di convertire i file PPT in SVG a livello di codice? Utilizzando [*Aspose.Slides per Python tramite .NET*](https://products.aspose.com/slides/it/python-net/) qualsiasi sviluppatore può convertire PPT in formato SVG con poche righe di codice Python.

In quanto moderna API di elaborazione delle presentazioni, Aspose.Slides for Python crea rapidamente SVG da PPT. Verifica la qualità della conversione da PPT a SVG direttamente nel tuo [browser](https://products.aspose.app/slides/conversion). La libreria Aspose PowerPoint PPTX ti consente di convertire i file PPT in molti formati popolari.

È possibile installare la libreria da [PyPI](https://pypi.org/project/Aspose.Slides/) utilizzando il seguente comando pip:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Console/Terminale" >}}
```console
> pip install aspose.slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Salva PPT come SVG in Python" %}}

Usa l'app gratuita per vedere una dimostrazione del processo di conversione da PPT a SVG.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Questo codice di esempio mostra la conversione da PPT a SVG Python" >}}
```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.ppt") as presentation:
    for slide in presentation.slides:
        with open("presentation_slide_{0}.svg".format(str(slide.slide_number)), "wb") as file:
            slide.write_as_svg(file)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Come convertire PPT in SVG in Python" intro="Questi sono i passaggi per convertire un file PPT in SVG usando Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carica il file PPT con un'istanza della classe Presentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chiama il metodo `save` mentre specifichi il percorso del file di output e SaveFormat.SVG come parametri{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Il file PPT verrà salvato nel percorso specificato{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Requisiti di sistema" intro="Prima di eseguire il codice sorgente di esempio di conversione Python, assicurati di disporre dei seguenti prerequisiti." %}}

- Sistema operativo basato su Microsoft Windows o Linux (vedi [altro](https://docs.aspose.com/slides/python-net/system-requirements/)).
- Python 3.5 o successivo
- Aspose.Slides per Python referenziato nel tuo progetto.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension="ppt-to-svg"
  title="App gratuita da convertire PPT in SVG"
  description="[Prova la nostra app gratuita Collage](https://products.aspose.app/slides/collage/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Altre conversioni supportate" subTitle="Puoi anche convertire PPT in molti altri formati di file. Vedi altre conversioni supportate di seguito" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/python-net/conversion/ppt-to-bmp/" name="PPT TO BMP" description="Immagine bitmap" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/python-net/conversion/ppt-to-emf/" name="PPT TO EMF" description="Formato Metafile migliorato" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/python-net/conversion/ppt-to-fodp/" name="PPT TO FODP" description="Presentazione XML piatta di OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/python-net/conversion/ppt-to-gif/" name="PPT TO GIF" description="Formato di scambio grafico" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/python-net/conversion/ppt-to-html/" name="PPT TO HTML" description="Hyper Text Markup Language" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/python-net/conversion/ppt-to-jpg/" name="PPT TO JPG" description="Immagine JPEG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/python-net/conversion/ppt-to-odp/" name="PPT TO ODP" description="Formato di presentazione OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/python-net/conversion/ppt-to-otp/" name="PPT TO OTP" description="Formato standard OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/python-net/conversion/ppt-to-pdf/" name="PPT TO PDF" description="Formato documento portatile" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/python-net/conversion/ppt-to-png/" name="PPT TO PNG" description="Grafica di rete portatile" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/python-net/conversion/ppt-to-pot/" name="PPT TO POT" description="File modello di Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/python-net/conversion/ppt-to-potm/" name="PPT TO POTM" description="File modello Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/python-net/conversion/ppt-to-potx/" name="PPT TO POTX" description="Presentazione del modello di Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/python-net/conversion/ppt-to-pps/" name="PPT TO PPS" description="Presentazione di PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/python-net/conversion/ppt-to-ppsm/" name="PPT TO PPSM" description="Presentazione con attivazione macro" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/python-net/conversion/ppt-to-ppsx/" name="PPT TO PPSX" description="Presentazione di PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/python-net/conversion/ppt-to-pptm/" name="PPT TO PPTM" description="File di presentazione abilitato per le macro" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/python-net/conversion/ppt-to-pptx/" name="PPT TO PPTX" description="Apri il formato di presentazione XML" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/python-net/conversion/ppt-to-swf/" name="PPT TO SWF" description="Formato SWF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/python-net/conversion/ppt-to-tiff/" name="PPT TO TIFF" description="Formato immagine contrassegnato" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/python-net/conversion/ppt-to-xps/" name="PPT TO XPS" description="Specifiche della carta XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
