---
lastmod: 2023-04-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Converter JPG para PPTX em Java
url: /pt/java/conversion/jpg-to-pptx/
keywords: Converta JPG para PPTX, JPG para PPTX, PowerPoint, JPG, PPTX, API Java, Biblioteca Java
description: Converta JPG para PPTX em Java. Use a API da biblioteca Java para converter imagens JPG em PowerPoint
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Converter JPG para PPTX em Java" h2="Poderosa API Java de plataforma cruzada para converter JPG em PPTX usando código Java" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Converter JPG para PPTX em Java" variant="code" %}}

Usando [**Aspose.Slides para Java**](https://products.aspose.com/slides/pt/java/), você pode converter imagens JPG em apresentações do PowerPoint com apenas algumas linhas de código:

{{< blocks/products/pf/slides-design-update-10-2026/code title="Código Java para converter JPG para PPTX" >}}
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
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Converter JPG para PPTX usando Aspose.Slides" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/pt/java/) é uma poderosa biblioteca Java usada para criar, converter e manipular apresentações em PowerPoint, PDFs, documentos HTML e outros arquivos. Ao converter JPG para PPTX, você está essencialmente criando uma apresentação do PowerPoint que contém slides baseados em imagens JPG.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Como converter JPG para PPTX em Java" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instale **Aspose.Slides para Java**. Consulte [**Instalação**](https://docs.aspose.com/slides/java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Adicione a biblioteca como referência em seu projeto.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Crie uma instância da classe Presentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carregue a imagem JPG que deseja converter para PPTX.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Salve o arquivo resultante como uma apresentação PPTX.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Conversor Online Gratuito"
  description="[Como converter PPT para HTML em Python](https://products.aspose.com/slides/pt/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Outras Conversões de PowerPoint Suportadas" subTitle="Você também pode converter arquivos em outros formatos para PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/java/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/java/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/java/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/java/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/java/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/java/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/java/conversion/html-to-pptx/" name="HTML TO PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
