---
title: Ajouter un filigrane aux fichiers de présentation PPTX à l'aide de Python
url: /fr/python-net/watermark/pptx/
keywords: Ajouter un filigrane PPTX, Ajouter un filigrane de texte PPTX, Ajouter un filigrane d'image PPTX
description: Code source Python pour ajouter un filigrane à la présentation PPTX.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Ajouter un filigrane à la présentation PPTX en utilisant Python" h2="Créez vos propres applications Python pour insérer un filigrane de texte ou d'image dans une présentation PPT, PPTX ou ODP à l'aide d'API côté serveur." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Ajouter un filigrane à la présentation PPTX via Python" %}}
À l'aide de Aspose.Slides for Python via .NET, vous pouvez ajouter un filigrane à la présentation PPTX. Les filigranes sont une partie essentielle de toute présentation. Ils sont utilisés pour protéger le contenu de la présentation contre toute copie ou utilisation sans autorisation. Un filigrane est une image ou un texte visible ou invisible placé au-dessus de la présentation. Il peut être utilisé pour identifier le propriétaire de la présentation et empêcher toute utilisation non autorisée. Les filigranes peuvent également être utilisés pour ajouter une touche professionnelle à la présentation et lui donner un aspect plus soigné. 
{{% blocks/products/pf/agp/code-block title="Ajouter un filigrane de texte à PPTX en utilisant Python" offSpacer="true" %}}

```py

import aspose.slides as slides
import aspose.pydrawing as draw

with slides.Presentation() as pres:
    master = pres.masters[0]

    watermarkShape = master.shapes.add_auto_shape(slides.ShapeType.RECTANGLE, 0, 0, 100, 100)
    watermarkTextFrame = watermarkShape.add_text_frame("Watermark")

    # Lock Watermark from Editing
    watermarkShape.shape_lock.select_locked = True
    watermarkShape.shape_lock.size_locked = True
    watermarkShape.shape_lock.text_locked = True
    watermarkShape.shape_lock.position_locked = True
    watermarkShape.shape_lock.grouping_locked = True
    
    # Set Text Watermark Transparency
    watermarkPortion = watermarkTextFrame.paragraphs[0].portions[0]
    watermarkPortion.portion_format.fill_format.fill_type = slides.FillType.SOLID
    watermarkPortion.portion_format.fill_format.solid_fill_color.color = draw.Color.from_argb(150, 200, 200, 200)
    
    # Set Font Size of Text Watermark
    watermarkPortion.portion_format.font_height = 16

    pres.save("watermark.pptx", slides.export.SaveFormat.PPTX)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Ajouter un filigrane d'image à la présentation PPTX à l'aide de Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation() as presentation:
    with open("image1.png", "rb") as fs:
        data = fs.read()
    image = presentation.images.add_image(data)

    master = presentation.masters[0]
    watermarkShape = master.shapes.add_auto_shape(slides.ShapeType.RECTANGLE, 0, 0, image.width, image.height)
    
    watermarkShape.fill_format.fill_type = slides.FillType.PICTURE
    watermarkShape.fill_format.picture_fill_format.picture.image = image
    watermarkShape.fill_format.picture_fill_format.picture_fill_mode = slides.PictureFillMode.STRETCH

    presentation.save("watermark2.pptx", slides.export.SaveFormat.PPTX)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Comment ajouter un filigrane à PPTX via Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Voici les étapes pour ajouter un filigrane de texte aux fichiers PPTX." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Charger PPTX avec une instance de Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sélectionnez la présentation principale
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ajouter un type de forme à l'aide de la méthode AddAutoShape
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ajouter du texte en filigrane à l'aide de la méthode AddTextFrame
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Enregistrer le résultat au format PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Autres formats pris en charge" subTitle="À l'aide de Python, vous pouvez également ajouter un filigrane aux formats suivants :" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/watermark/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}