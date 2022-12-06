---
title: Unisci immagini JPG in Python
url: /it/python-net/merge/jpg-to-jpg/
keywords: Unisci JPG, JPEG in JPG, Unisci JPG, Combina JPG, API Python, Libreria Python
description: Unisci JPG a JPG in Python. Usa l'API della libreria Python per combinare i file JPG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Unisci JPG in Python" h2="Libreria Python ad alta velocità e multipiattaforma per l'unione di immagini JPG utilizzando il codice Python" >}}

{{% blocks/products/pf/feature-page-section h2="Unisci JPG a JPG usando Aspose.Slides" %}}

[**Aspose.Slides per Python tramite .NET**](https://products.aspose.com/slides/it/python-net/) è una potente libreria Python utilizzata per unire e manipolare presentazioni, immagini e altri file. Quando unisci JPG a JPG, stai effettivamente combinando due immagini per ottenere un'unica immagine.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Unisci JPG a JPG in Python" %}}
Utilizzando [**Aspose.Slides per Python tramite .NET**](https://products.aspose.com/slides/it/python-net/), puoi unire rapidamente i file JPG con poche righe di codice

{{% blocks/products/pf/agp/code-block title="Codice Python per unire JPG a JPG" offSpacer="true" %}}
```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    slide = pres.slides[0]
    image1 = pres.images.add_image(drawing.Bitmap("image1.jpg"))
	slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 0, 0, 100, 100, image1)

    image2 = pres.images.add_image(drawing.Bitmap("image2.jpg"))
	slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 0, 200, 100, 100, image2)

    for sld in pres.slides:
        bmp = sld.get_thumbnail(1, 1)
        bmp.save("Slide_{num}.jpg".format(num=str(sld.slide_number)), drawing.imaging.ImageFormat.jpeg)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Come unire JPG in Python" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Install **Aspose.Slides for Python via .NET**. See [**Installation**](https://docs.aspose.com/slides/python-net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Aggiungi la libreria come riferimento nel tuo progetto.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Crea un'istanza della classe Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Carica i file JPG che vuoi unire come cornici.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salva l'immagine JPG risultante.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Unisci altri file" subTitle="Puoi anche combinare file in altri formati per ottenere un unico file" >}}
  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/merge/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/merge/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/merge/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/merge/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/merge/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/merge/png-to-pdf/" name="PNG TO PDF" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}