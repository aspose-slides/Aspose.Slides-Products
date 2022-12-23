---
title: Editar HTML en Java
url: /es/java/editor/html/
keywords: Editar HTML, HTML, API de Java, biblioteca de Java
description: Editar HTML en Java. Use la API de la biblioteca Java para editar el archivo HTML
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Editar HTML en Java" h2="Biblioteca Java de alta velocidad y multiplataforma para editar HTML usando código Java" >}}

{{% blocks/products/pf/feature-page-section h2="Editar HTML usando Aspose.Slides" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/es/java/) es una potente biblioteca de Java que se utiliza para manipular y editar presentaciones, documentos HTML y otros archivos. Puede editar un documento HTML añadiéndole una nueva línea de texto. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Editar HTML en Java" %}}
Con [**Aspose.Slides for Java**](https://products.aspose.com/slides/es/java/), puede agregar una nueva línea de texto a un documento HTML con solo unas pocas líneas de código.

{{% blocks/products/pf/agp/code-block title="Código Java para editar HTML" offSpacer="true" %}}
```java

Presentation pres = new Presentation();
try {
    pres.getSlides().removeAt(0);
    FileInputStream htmlStream = new FileInputStream("page.html");
    try {
        pres.getSlides().addFromHtml(htmlStream);
    } finally {
        if (htmlStream != null) htmlStream.close();
    }

    ISlide slide = pres.getSlides().get_Item(0);
    IAutoShape shape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 50);
    shape.getTextFrame().setText("New text");

    pres.save("page.html", SaveFormat.Html5);
} catch(IOException e) {
} finally {
    if (pres != null) pres.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Cómo editar HTML en Java" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Instale **Aspose.Slides para Java**. Consulte [**Instalación**](https://docs.aspose.com/slides/java/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Agregue la biblioteca como referencia en su proyecto.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Crea una instancia de la clase Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Cargue el documento HTML que desea editar.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Agrega una nueva línea de texto.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Guarde el archivo HTML modificado.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Editar otros archivos" subTitle="También puedes editar archivos en otros formatos" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/java/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/java/editor/pdf/" name="Edit PDF" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}