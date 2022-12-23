---
title: Modifica HTML in Python
url: /it/python-net/editor/html/
keywords: Modifica HTML, HTML, API Python, Libreria Python
description: Modifica HTML in Python. Usa l'API della libreria Python per modificare il file HTML
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Modifica HTML in Python" h2="Libreria Python ad alta velocità e multipiattaforma per la modifica di HTML utilizzando il codice Python" >}}

{{% blocks/products/pf/feature-page-section h2="Modifica HTML utilizzando Aspose.Slides" %}}

[**Aspose.Slides per Python tramite .NET**](https://products.aspose.com/slides/it/python-net/) è una potente libreria Python utilizzata per manipolare e modificare presentazioni, documenti HTML e altri file . Puoi modificare un documento HTML aggiungendovi una nuova riga di testo. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Modifica HTML in Python" %}}
Usando [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/it/python-net/), puoi aggiungere una nuova riga di testo a un documento HTML con pochi righe di codice.

{{% blocks/products/pf/agp/code-block title="Codice Python per la modifica dell'HTML" offSpacer="true" %}}
```python

import aspose.slides as slides

with slides.Presentation() as pres:
    pres.slides.remove_at(0)
    with open("page.html", "rt") as stream:
        data = stream.read()
    pres.slides.add_from_html(data)

    shape = pres.slides[0].shapes.add_auto_shape(slides.ShapeType.RECTANGLE, 10, 10, 100, 50)
    shape.text_frame.text = "New text"

    pres.save("page.html", slides.export.SaveFormat.HTML5)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Come modificare l'HTML in Python" >}}


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
Carica il documento HTML che desideri modificare.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Aggiungi una nuova riga di testo.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salva il file HTML modificato.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Modifica altri file" subTitle="Puoi anche modificare i file in altri formati" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/editor/pdf/" name="Edit PDF" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}