---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Adicionar marcas d'água a apresentações PPTX com Python
url: /pt/python-net/watermark/pptx/
description: Adicione marcas d'água de texto e imagem a apresentações PPTX com Python e Aspose.Slides.
keywords: adicionar marca d'água a PPTX, adicionar marca d'água de texto a PPTX, adicionar marca d'água de imagem a PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Adicionar marcas d'água a apresentações PPTX com Python" h2="Crie aplicativos Python que adicionam marcas d'água de texto ou imagem a apresentações PPTX com o Aspose.Slides." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Adicionar uma marca d'água a uma apresentação PPTX com Python" variant="code" %}}

Com o [Aspose.Slides for Python via .NET](/slides/pt/python-net/), você pode adicionar uma marca d'água de texto ou imagem a uma apresentação PPTX sem usar o Microsoft PowerPoint. Uma marca d'água pode identificar o proprietário, marcar uma apresentação como confidencial ou rascunho, ou garantir uma identidade visual consistente. Os exemplos abaixo colocam a marca d'água no primeiro slide mestre, para que ela apareça nos slides que usam esse mestre.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Adicionar uma marca d'água de texto a uma apresentação PPTX – Python" >}}
```python
with slides.Presentation("presentation.pptx") as presentation:
    master_slide = presentation.masters[0]
    watermark_shape = master_slide.shapes.add_auto_shape(slides.ShapeType.RECTANGLE, 100, 100, 400, 50)
    watermark_text_frame = watermark_shape.add_text_frame("CONFIDENTIAL")

    watermark_shape.fill_format.fill_type = slides.FillType.NO_FILL
    watermark_shape.line_format.fill_format.fill_type = slides.FillType.NO_FILL

    watermark_portion = watermark_text_frame.paragraphs[0].portions[0]
    watermark_portion.portion_format.font_height = 32

    watermark_shape.auto_shape_lock.select_locked = True
    watermark_shape.auto_shape_lock.size_locked = True
    watermark_shape.auto_shape_lock.text_locked = True
    watermark_shape.auto_shape_lock.position_locked = True
    watermark_shape.auto_shape_lock.grouping_locked = True

    presentation.save("watermarked.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Adicionar uma marca d'água de imagem a uma apresentação PPTX – Python" >}}
```python
with slides.Presentation("presentation.pptx") as presentation:
    with open("watermark.png", "rb") as image_stream:
        watermark_image = presentation.images.add_image(image_stream.read())

    master_slide = presentation.masters[0]
    watermark_shape = master_slide.shapes.add_auto_shape(
        slides.ShapeType.RECTANGLE, 100, 100, watermark_image.width, watermark_image.height)

    watermark_shape.fill_format.fill_type = slides.FillType.PICTURE
    watermark_shape.fill_format.picture_fill_format.picture.image = watermark_image
    watermark_shape.fill_format.picture_fill_format.picture_fill_mode = slides.PictureFillMode.STRETCH
    watermark_shape.line_format.fill_format.fill_type = slides.FillType.NO_FILL

    presentation.save("watermarked.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Como adicionar uma marca d'água a PPTX com Python" intro="Siga estas etapas para adicionar uma marca d'água de texto a uma apresentação PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Abra o arquivo PPTX com `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Obtenha o primeiro slide mestre da coleção `masters`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chame `add_auto_shape` para adicionar um retângulo ao slide mestre.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chame `add_text_frame` para adicionar o texto da marca d'água e, em seguida, formate e bloqueie a forma.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chame `save` com `SaveFormat.PPTX` para salvar a apresentação com marca d'água.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Criado com Aspose.Slides" title="Adicione marcas d'água a arquivos PPTX online" description="O aplicativo gratuito Aspose.Slides Watermark é criado com [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/pt/python-net/), a mesma API do código acima. Abra-o e veja o que a API pode fazer com seus próprios arquivos PPTX." button="Abrir Aspose.Slides Watermark" note="[Todos os aplicativos gratuitos](https://products.aspose.app/slides/family)" >}}
- Funciona no seu navegador, sem instalar nada.
- Veja como o Aspose.Slides adiciona marcas d'água antes de escrever código.
- Adicione uma marca d'água de texto ou imagem ao seu arquivo PPTX.
- Baixe o arquivo com marca d'água.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Outros formatos compatíveis com marca d'água" subTitle="Com Python, você também pode adicionar marcas d'água a outros formatos de apresentação compatíveis." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pt/python-net/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pt/python-net/watermark/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
