---
title: Editar PPT em Python
url: /pt/python-net/editor/ppt/
keywords: Editar PPT, Editar PowerPoint, PPT, PowerPoint, API Python, Biblioteca Python
description: Editar PPT em Python. Use a API da biblioteca Python para editar a apresentação do PowerPoint
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Editar PPT em Python" h2="Biblioteca Python multiplataforma e de alta velocidade para edição de PPT usando código Python" >}}

{{% blocks/products/pf/feature-page-section h2="Editar PPT usando Aspose.Slides" %}}

[**Aspose.Slides para Python via .NET**](https://products.aspose.com/slides/pt/python-net/) é uma poderosa biblioteca Python usada para manipular e editar apresentações. Você pode editar uma apresentação PPT adicionando uma nova linha de texto a ela. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Editar PPT em Python" %}}
Usando [**Aspose.Slides para Python via .NET**](https://products.aspose.com/slides/pt/python-net/), você pode adicionar uma nova linha de texto a um documento PPT com apenas alguns linhas de código.

{{% blocks/products/pf/agp/code-block title="Código Python para edição de PPT" offSpacer="true" %}}
```python

import aspose.slides as slides

with slides.Presentation("pres.ppt") as pres:
    shape = pres.slides[0].shapes.add_auto_shape(slides.ShapeType.RECTANGLE, 10, 10, 100, 50)
    shape.text_frame.text = "New text"

    pres.save("pres.ppt", slides.export.SaveFormat.PPT)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Como editar PPT em Python" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Install **Aspose.Slides for Python via .NET**. See [**Installation**](https://docs.aspose.com/slides/python-net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Adicione a biblioteca como referência em seu projeto.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Crie uma instância da classe Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Carregue a apresentação PPT que deseja editar.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Adicione uma nova linha de texto.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salve o arquivo PowerPoint alterado.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Editar outros arquivos" subTitle="Você também pode editar arquivos em outros formatos" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/editor/pdf/" name="Edit PDF" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/editor/html/" name="Edit HTML" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}