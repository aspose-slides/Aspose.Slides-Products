---
title: Editar PPT en C++
url: /es/cpp/editor/ppt/
keywords: Editar PPT, Editar PowerPoint, PPT, PowerPoint, API de C++, Biblioteca de C++
description: Editar PPT en C++. Utilice la API de la biblioteca de C++ para editar la presentación de PowerPoint
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Editar PPT en C++" h2="Biblioteca C++ de alta velocidad y multiplataforma para editar PPT usando código C++" >}}

{{% blocks/products/pf/feature-page-section h2="Editar PPT usando Aspose.Slides" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/es/cpp/) es una potente biblioteca de C++ que se utiliza para manipular y editar presentaciones. Puede editar una presentación PPT agregándole una nueva línea de texto. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Editar PPT en C++" %}}
Usando [**Aspose.Slides para C++**](https://products.aspose.com/slides/es/cpp/), puede agregar una nueva línea de texto a un documento PPT con solo unas pocas líneas de código.

{{% blocks/products/pf/agp/code-block title="Código C++ para editar PPT" offSpacer="true" %}}
```cpp

auto pres = System::MakeObject<Presentation>(u"pres.ppt");

auto slide = pres->get_Slides()->idx_get(0);
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 50.0f);
shape->get_TextFrame()->set_Text(u"New text");

pres->Save(u"pres.pdf", SaveFormat::Ppt);
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Cómo editar PPT en C++" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Instale **Aspose.Slides para C++**. Consulte [**Instalación**](https://docs.aspose.com/slides/cpp/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Agregue la biblioteca como referencia en su proyecto.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Crea una instancia de la clase Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Cargue la presentación PPT que desea editar.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Agrega una nueva línea de texto.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Guarde el archivo de PowerPoint modificado.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Editar otros archivos" subTitle="También puedes editar archivos en otros formatos" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/cpp/editor/pdf/" name="Edit PDF" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/cpp/editor/html/" name="Edit HTML" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}