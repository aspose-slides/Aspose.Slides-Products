---
title: Bearbeiten Sie PPT in Python
url: /de/python-net/editor/ppt/
keywords: PPT bearbeiten, PowerPoint bearbeiten, PPT, PowerPoint, Python-API, Python-Bibliothek
description: Bearbeiten Sie PPT in Python. Verwenden Sie die Python-Bibliotheks-API, um PowerPoint-Präsentationen zu bearbeiten
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Bearbeiten Sie PPT in Python" h2="Hochgeschwindigkeits- und plattformübergreifende Python-Bibliothek zum Bearbeiten von PPT mit Python-Code" >}}

{{% blocks/products/pf/feature-page-section h2="Bearbeiten Sie PPT mit Aspose.Slides" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/de/python-net/) ist eine leistungsstarke Python-Bibliothek zum Manipulieren und Bearbeiten von Präsentationen. Sie können eine PPT-Präsentation bearbeiten, indem Sie ihr eine neue Textzeile hinzufügen. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Bearbeiten Sie PPT in Python" %}}
Mit [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/de/python-net/) können Sie einem PPT-Dokument mit nur wenigen eine neue Textzeile hinzufügen Zeilen von Code.

{{% blocks/products/pf/agp/code-block title="Python-Code zum Bearbeiten von PPT" offSpacer="true" %}}
```python

import aspose.slides as slides

with slides.Presentation("pres.ppt") as pres:
    shape = pres.slides[0].shapes.add_auto_shape(slides.ShapeType.RECTANGLE, 10, 10, 100, 50)
    shape.text_frame.text = "New text"

    pres.save("pres.ppt", slides.export.SaveFormat.PPT)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="So bearbeiten Sie PPT in Python" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Install **Aspose.Slides for Python via .NET**. See [**Installation**](https://docs.aspose.com/slides/python-net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Fügen Sie die Bibliothek als Referenz in Ihrem Projekt hinzu.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Erstellen Sie eine Instanz der Presentation-Klasse.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laden Sie die PPT-Präsentation, die Sie bearbeiten möchten.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Fügen Sie eine neue Textzeile hinzu.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Speichern Sie die geänderte PowerPoint-Datei.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Bearbeiten Sie andere Dateien" subTitle="Sie können auch Dateien in anderen Formaten bearbeiten" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/editor/pdf/" name="Edit PDF" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/editor/html/" name="Edit HTML" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}