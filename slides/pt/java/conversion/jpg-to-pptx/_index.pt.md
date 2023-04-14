---
title: Converter JPG para PPTX em Java
url: /pt/java/conversion/jpg-to-pptx/
keywords: Converta JPG para PPTX, JPG para PPTX, PowerPoint, JPG, PPTX, API Java, Biblioteca Java
description: Converta JPG para PPTX em Java. Use a API da biblioteca Java para converter imagens JPG em PowerPoint
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Converter JPG para PPTX em Java" h2="Poderosa API Java de plataforma cruzada para converter JPG em PPTX usando código Java" >}}

{{% blocks/products/pf/feature-page-section h2="Converter JPG para PPTX usando Aspose.Slides" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/pt/java/) é uma poderosa biblioteca Java usada para criar, converter e manipular apresentações em PowerPoint, PDFs, documentos HTML e outros arquivos. Ao converter JPG para PPTX, você está essencialmente criando uma apresentação do PowerPoint que contém slides baseados em imagens JPG.

{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="Converter JPG para PPTX em Java" %}}
Usando [**Aspose.Slides para Java**](https://products.aspose.com/slides/pt/java/), você pode converter imagens JPG em apresentações do PowerPoint com apenas algumas linhas de código:

{{% blocks/products/pf/agp/code-block title="Código Java para converter JPG para PPTX" offSpacer="true" %}}
```java
Presentation pres = new Presentation();
try {
	ISlide slide = pres.getSlides().get_Item(0);
	IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.jpg")));
	slide.getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 720, 540, image);

	pres.save("pres.pptx", SaveFormat.Pptx);
} finally {
	if (pres != null) pres.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Como converter JPG para PPTX em Java" >}}


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
Carregue a imagem JPG que deseja converter para PPTX.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salve o arquivo resultante como uma apresentação PPTX.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Conversor Online Gratuito" sectionDescription="[Como converter PPT para HTML em Python](https://products.aspose.com/slides/pt/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Outras Conversões de PowerPoint Suportadas" subTitle="Você também pode converter arquivos em outros formatos para PowerPoint" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/java/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/java/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/java/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/java/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/java/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/java/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/java/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}