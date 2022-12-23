---
title: Edytuj PDF w Pythonie
url: /pl/python-net/editor/pdf/
keywords: Edytuj PDF, PDF, Python API, Python Library
description: Edytuj PDF w Pythonie. Użyj API biblioteki Pythona do edycji dokumentu PDF
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Edytuj PDF w Pythonie" h2="Szybka i wieloplatformowa biblioteka Pythona do edycji plików PDF przy użyciu kodu Pythona" >}}

{{% blocks/products/pf/feature-page-section h2="Edytuj PDF za pomocą Aspose.Slides" %}}

[**Aspose.Slides for Python przez .NET**](https://products.aspose.com/slides/pl/python-net/) to potężna biblioteka Pythona używana do manipulowania i edytowania prezentacji, dokumentów PDF i innych plików . Możesz edytować dokument PDF, dodając do niego nowy wiersz tekstu. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Edytuj PDF w Pythonie" %}}
Używając [**Aspose.Slides for Python przez .NET**](https://products.aspose.com/slides/pl/python-net/), możesz dodać nowy wiersz tekstu do dokumentu PDF za pomocą zaledwie kilku linie kodu.

{{% blocks/products/pf/agp/code-block title="Kod Pythona do edycji plików PDF" offSpacer="true" %}}
```python

import aspose.slides as slides

with slides.Presentation() as pres:
    pres.slides.remove_at(0)
    pres.slides.add_from_pdf("document.pdf")

    shape = pres.slides[0].shapes.add_auto_shape(slides.ShapeType.RECTANGLE, 10, 10, 100, 50)
    shape.text_frame.text = "New text"

    pres.save("document.pdf", slides.export.SaveFormat.PDF)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Jak edytować PDF w Pythonie" >}}


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
Załaduj dokument PDF, który chcesz edytować.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Dodaj nowy wiersz tekstu.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Zapisz zmieniony plik PDF.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Edytuj inne pliki" subTitle="Możesz także edytować pliki w innych formatach" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/editor/html/" name="Edit HTML" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}