---
title: Wasserzeichen zu PPT-Präsentationsdateien mit Python hinzufügen
url: /de/python-net/watermark/ppt/
keywords: Wasserzeichen hinzufügen PPT, Textwasserzeichen hinzufügen PPT, Bildwasserzeichen hinzufügen PPT
description: Python-Quellcode zum Hinzufügen eines Wasserzeichens zur PPT-Präsentation.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Wasserzeichen zur PPT-Präsentation mit Python hinzufügen" h2="Erstellen Sie Ihre eigenen Python-Apps, um mithilfe serverseitiger APIs Text- oder Bildwasserzeichen in PPT-, PPTX- oder ODP-Präsentationen einzufügen." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Wasserzeichen zur PPT-Präsentation über Python hinzufügen" %}}
Mit Aspose.Slides for Python via .NET können Sie der Präsentation von PPT ein Wasserzeichen hinzufügen. Wasserzeichen sind ein wesentlicher Bestandteil jeder Präsentation. Sie dienen dazu, den Inhalt der Präsentation vor der Vervielfältigung oder unerlaubten Verwendung zu schützen. Ein Wasserzeichen ist ein sichtbares oder unsichtbares Bild oder Text, das über der Präsentation platziert wird. Es kann verwendet werden, um den Eigentümer der Präsentation zu identifizieren und eine unbefugte Nutzung zu verhindern. Wasserzeichen können auch verwendet werden, um der Präsentation eine professionelle Note zu verleihen und sie eleganter aussehen zu lassen. 
{{% blocks/products/pf/agp/code-block title="Textwasserzeichen zu PPT mit Python hinzufügen" offSpacer="true" %}}

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

    pres.save("watermark.ppt", slides.export.SaveFormat.PPT)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Bildwasserzeichen zur PPT-Präsentation mit Python hinzufügen" offSpacer="true" %}}

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

    presentation.save("watermark2.ppt", slides.export.SaveFormat.PPT)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="So fügen Sie über Python ein Wasserzeichen zu PPT hinzu" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Dies sind die Schritte zum Hinzufügen von Textwasserzeichen zu PPT-Dateien." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laden Sie PPT mit einer Präsentationsinstanz
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Wählen Sie die Masterpräsentation aus
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Fügen Sie einen Formtyp mit der AddAutoShape-Methode hinzu
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Fügen Sie Wasserzeichentext mit der AddTextFrame-Methode hinzu
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ergebnis im Format PPT speichern
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Formate" subTitle="Mit Python können Sie Wasserzeichen auch zu den folgenden Formaten hinzufügen:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/watermark/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}