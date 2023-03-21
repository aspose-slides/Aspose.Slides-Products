---
title: Converter PNG para SVG em Java
url: /pt/java/conversion/png-to-svg/
keywords: PNG para SVG, Converter PNG para SVG, API Java, Biblioteca Java, PNG, SVG
description: Converter PNG para SVG em Java. Use a API da biblioteca Java para converter arquivos PNG em SVGs
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Converter PNG para SVG em Java" h2="Biblioteca Java de plataforma cruzada e de alta velocidade que ajuda no desenvolvimento de aplicativos com a capacidade de criar, mesclar, inspecionar ou converter arquivos de apresentação do Microsoft PowerPoint e OpenOffice sem o uso de qualquer software como Microsoft ou Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Converter PNG para SVG em Java" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/pt/java/) é uma poderosa biblioteca Java para criar e manipular arquivos de apresentação. Além disso, oferece maneiras flexíveis de converter PNG em SVG. Usando **Aspose.Slides para Java**, qualquer desenvolvedor ou aplicativo pode converter arquivos PNG em SVG com apenas algumas linhas de código Java.

Como uma API moderna de processamento de documentos, o Aspose.Slides for Java exporta arquivos PNG para formatos de arquivo SVG rapidamente. A biblioteca Aspose PowerPoint permite converter PNG para SVGs e muitos outros formatos de arquivo

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converter PNG para SVG usando Java" %}}
Para converter o PNG para SVG, você precisará criar a apresentação do arquivo PNG e salvá-lo como SVG.

{{% blocks/products/pf/agp/code-block title="Código Java para converter PNG em SVG" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    ISlide slide = pres.getSlides().get_Item(0);
	IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
	slide.getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
    for (int index = 0; index < pres.getSlides().size(); index++)
    {
        ISlide slide = pres.getSlides().get_Item(index);

        FileOutputStream fileStream = new FileOutputStream("slide-" + index + ".svg");
        try {
            slide.writeAsSvg(fileStream);
        } finally {
            fileStream.close();
        }
    }
} finally {
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Como converter PNG para SVG usando Aspose.Slides para Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Estas são as etapas para converter PNG para SVG em Java." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Instale [**Aspose.Slides para Java**](https://products.aspose.com/slides/pt/java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Adicione uma referência de biblioteca (importe a biblioteca) ao seu projeto Java.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Abra os arquivos de origem PNG em Java.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salve o resultado como arquivo SVG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Conversor Online Gratuito" sectionDescription="[Como converter PPT para HTML em Python](https://products.aspose.com/slides/pt/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Converter PNG para outros formatos suportados" subTitle="Você também pode converter PNG e salvar em outros formatos de arquivo. Veja todos os formatos suportados abaixo" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/java/conversion/png-to-jpg/" name="PNG TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/java/conversion/png-to-pdf/" name="PNG TO PDF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}