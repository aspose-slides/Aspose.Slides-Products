---
lastmod: 2023-03-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Converti Image in JPG in Python
url: /it/python-net/conversion/image-to-jpg/
keywords: Image in JPG, conversione di Image in JPG, API Python, libreria Python, Image, JPG
description: Converti Image in JPG in Python. Usa l'API della libreria Python per convertire i file Image in JPG
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Converti Image in JPG in Python" h2="Libreria Python ad alta velocità e multipiattaforma che aiuta nello sviluppo di applicazioni con la possibilità di creare, unire, ispezionare o convertire file di presentazione Microsoft PowerPoint e OpenOffice senza l'uso di software come Microsoft o Open Office, Adobe PDF." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Converti Image in JPG usando Python" variant="code" %}}

Per convertire Image in JPG, dovrai creare una presentazione dal file Image e salvarla come JPG.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Codice Python per convertire Image in JPG" >}}
```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    slide = pres.slides[0]
    image = pres.images.add_image(drawing.Bitmap(dataDir+ "image.png"))
	slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 10, 10, 100, 100, image)
    for sld in pres.slides:
        bmp = sld.get_thumbnail(1, 1)
        bmp.save("Slide_{num}.jpg".format(num=str(sld.slide_number)), drawing.imaging.ImageFormat.jpeg)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Converti Image in JPG in Python" %}}

[**Aspose.Slides per Python tramite .NET**](https://products.aspose.com/slides/it/python-net/) è una potente libreria Python per la creazione e la manipolazione di file di presentazione. Inoltre, fornisce modi flessibili per convertire Image in JPG. Utilizzando **Aspose.Slides per Python tramite .NET**, qualsiasi sviluppatore o applicazione può convertire i file Image in JPG con poche righe di codice Python.

Come moderna API di elaborazione dei documenti, Aspose.Slides per Python esporta rapidamente file Image in formati di file JPG. La libreria Aspose PowerPoint ti consente di convertire Image in JPG se molti altri formati di file

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Come convertire Image in JPG utilizzando Aspose.Slides per l'API Python" intro="Questi sono i passaggi per convertire Image in JPG in Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installa [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/it/python-net/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Aggiungi un riferimento alla libreria (importa la libreria) al tuo progetto Python.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Apri i file di origine Image in Python.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Salva il risultato come file JPG.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Convertitore online gratuito"
  description="[Come convertire PPT in HTML in Python](https://products.aspose.com/slides/it/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Converti Image in altri formati supportati" subTitle="Puoi anche convertire Image e salvare in altri formati di file. Vedi tutti i formati supportati di seguito" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/python-net/conversion/image-to-pdf/" name="IMAGE TO PDF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
