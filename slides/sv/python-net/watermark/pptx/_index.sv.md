---
title: Lägg till vattenstämpel i PPTX presentationsfiler med Python
url: /sv/python-net/watermark/pptx/
keywords: Lägg till vattenstämpel PPTX, Lägg till textvattenstämpel PPTX, Lägg till bildvattenstämpel PPTX
description: Källkod för Python för att lägga till vattenstämpel i presentationen PPTX.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Lägg till vattenstämpel i presentationen PPTX med Python" h2="Bygg dina egna Python-appar för att infoga text- eller bildvattenstämplar i PPT-, PPTX- eller ODP-presentationer med hjälp av API:er på serversidan." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Lägg till vattenstämpel i presentationen PPTX via Python" %}}
Med Aspose.Slides for Python via .NET kan du lägga till vattenstämpel i presentationen av PPTX. Vattenstämplar är en viktig del av alla presentationer. De används för att skydda innehållet i presentationen från att kopieras eller användas utan tillstånd. En vattenstämpel är en synlig eller osynlig bild eller text som placeras ovanpå presentationen. Den kan användas för att identifiera ägaren till presentationen och för att förhindra obehörig användning. Vattenstämplar kan också användas för att sätta en professionell touch till presentationen och få den att se mer polerad ut. 
{{% blocks/products/pf/agp/code-block title="Lägg till textvattenstämpel i PPTX med Python" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/code-block title="Lägg till bildvattenstämpel i PPTX presentation med Python" offSpacer="true" %}}

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

{{< blocks/products/pf/feature-page-section  h2="Så här lägger du till vattenstämpel i PPTX via Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Det här är stegen för att lägga till textvattenstämpel i PPTX-filer." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ladda PPTX med en instans av Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Välj huvudpresentationen
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lägg till formtyp med metoden AddAutoShape
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lägg till vattenstämpeltext med AddTextFrame-metoden
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Spara resultatet i formatet PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Andra format som stöds" subTitle="Med Python kan du också lägga till vattenstämpel i följande format:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/python-net/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/python-net/watermark/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}