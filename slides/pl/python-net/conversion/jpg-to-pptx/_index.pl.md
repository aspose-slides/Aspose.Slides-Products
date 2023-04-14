---
title: Konwertuj JPG na PPTX w Pythonie
url: /pl/python-net/conversion/jpg-to-pptx/
keywords: Konwertuj JPG na PPTX, JPG na PPTX, PowerPoint, JPG, PPTX, Python API, Python Library
description: Konwertuj JPG na PPTX w Pythonie. Użyj interfejsu API biblioteki Pythona, aby przekonwertować obrazy JPG do programu PowerPoint
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konwertuj JPG na PPTX w Pythonie" h2="Potężny, wieloplatformowy interfejs API Pythona do konwersji JPG na PPTX przy użyciu kodu Pythona" >}}

{{% blocks/products/pf/feature-page-section h2="Konwertuj JPG na PPTX za pomocą Aspose.Slides" %}}

[**Aspose.Slides for Python przez .NET**](https://products.aspose.com/slides/pl/python-net/) to potężna biblioteka Pythona używana do tworzenia, konwertowania i manipulowania prezentacjami programu PowerPoint, plikami PDF, Dokumenty HTML i inne pliki. Kiedy konwertujesz JPG na PPTX, zasadniczo tworzysz prezentację PowerPoint zawierającą slajdy oparte na obrazach JPG.

{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="Konwertuj JPG na PPTX w Pythonie" %}}
Używając [**Aspose.Slides for Python przez .NET**](https://products.aspose.com/slides/pl/python-net/), możesz przekonwertować obraz JPG na prezentację PowerPoint za pomocą zaledwie kilku linijek kodu:

{{% blocks/products/pf/agp/code-block title="Kod Pythona do konwersji JPG na PPTX" offSpacer="true" %}}
```py
import aspose.slides as slides

with slides.Presentation() as pres:
    slide = pres.slides[0]
    with open("img.jpg", "rb") as in_file:
        image = pres.images.add_image(in_file)
        slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 0, 0, 720, 540, image)
    
    pres.save("pres_with_image.pptx", slides.export.SaveFormat.PPTX)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Jak przekonwertować JPG na PPTX w Pythonie" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Install **Aspose.Slides for Python via .NET**. See [**Installation**](https://docs.aspose.com/slides/python-net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Dodaj bibliotekę jako odniesienie w swoim projekcie.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Utwórz wystąpienie klasy Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Załaduj obraz JPG, który chcesz przekonwertować na PPTX.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Zapisz wynikowy plik jako prezentację PPTX.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Darmowy konwerter online" sectionDescription="[Jak przekonwertować PPT na HTML w Pythonie](https://products.aspose.com/slides/pl/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje programu PowerPoint" subTitle="Możesz także konwertować pliki w innych formatach do programu PowerPoint" >}} 

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}