---
title: Mesclar imagens PNG em Java
url: /pt/java/merger/png-to-png/
keywords: Mesclar PNG, PNG para PNG, Unir PNG, Combinar PNG, Java API, Biblioteca Java
description: Mesclar PNG para PNG em Java. Use a API da biblioteca Java para combinar arquivos PNG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Mesclar PNG em Java" h2="Biblioteca Java de plataforma cruzada e de alta velocidade para mesclar imagens PNG usando código Java" >}}

{{% blocks/products/pf/feature-page-section h2="Mesclar PNG para PNG usando Aspose.Slides" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/pt/java/) é uma poderosa biblioteca Java usada para mesclar e manipular apresentações, imagens e outros arquivos. Ao mesclar PNG com PNG, você está efetivamente combinando duas imagens para obter uma imagem.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Mesclar PNG para PNG em Java" %}}
Usando [**Aspose.Slides for Java**](https://products.aspose.com/slides/pt/java/), você pode mesclar arquivos PNG rapidamente com apenas algumas linhas de código

{{% blocks/products/pf/agp/code-block title="Código Java para mesclar PNG para PNG" offSpacer="true" %}}
```java

Presentation pres = new Presentation();
try {
    IPPImage image1 = pres.getImages().addImage(Files.readAllBytes("image1.png"));
    pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 100, 100, image1);

    IPPImage image2 = pres.getImages().addImage(Files.readAllBytes("image2.png"));
    pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 200, 100, 100, image2);

    for (int index = 0; index < pres.getSlides().size(); index++)
    {
        ISlide slide = pres.getSlides().get_Item(index);
        BufferedImage bufferedImage = slide.getThumbnail();
        ImageIO.write(bufferedImage, "PNG", new File("image_java_" + index + ".png"));
    }
} finally {
    if (pres != null) pres.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Como mesclar PNG em Java" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Instale **Aspose.Slides para Java**. Consulte [**Instalação**](https://docs.aspose.com/slides/java/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Adicione a biblioteca como referência em seu projeto.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Crie uma instância da classe Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Carregue os arquivos PNG que deseja mesclar como molduras.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salve a imagem PNG resultante.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Mesclar outros arquivos" subTitle="Você também pode combinar arquivos em outros formatos para obter um único arquivo" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/java/merger/jpg-to-jpg/" name="JPG TO JPG" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/java/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/java/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/java/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/java/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/java/merger/png-to-pdf/" name="PNG TO PDF" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/java/merger/svg-to-png/" name="SVG TO PNG" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/java/merger/image-to-bmp/" name="IMAGE TO BMP" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/java/merger/html-to-image/" name="HTML TO IMAGE" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}