---
lastmod: 2023-04-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convertir PNG en PPT en Python
url: /fr/python-net/conversion/png-to-ppt/
keywords: Convertir PNG en PPT, PNG en PPT, PowerPoint, PNG, PPT, API Python, Bibliothèque Python
description: Convertir PNG en PPT en Python. Utilisez l'API de la bibliothèque Python pour convertir des images PNG en PowerPoint
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convertir PNG en PPT en Python" h2="Puissante API Python multiplateforme pour convertir PNG en PPT à l'aide de code Python" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convertir PNG en PPT en Python" variant="code" %}}

En utilisant [**Aspose.Slides pour Python via .NET**](https://products.aspose.com/slides/fr/python-net/), vous pouvez convertir une image PNG en présentation PowerPoint avec seulement quelques lignes de code :

{{< blocks/products/pf/slides-design-update-10-2026/code title="Code Python pour convertir PNG en PPT" >}}
```py
import aspose.slides as slides

with slides.Presentation() as pres:
    slide = pres.slides[0]
    with open("img.png", "rb") as in_file:
        image = pres.images.add_image(in_file)
        slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 0, 0, 720, 540, image)
    
    pres.save("pres_with_image.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convertir PNG en PPT en utilisant Aspose.Slides" %}}

[**Aspose.Slides pour Python via .NET**](https://products.aspose.com/slides/fr/python-net/) est une puissante bibliothèque Python utilisée pour créer, convertir et manipuler des présentations PowerPoint, des PDF, Documents HTML et autres fichiers. Lorsque vous convertissez PNG en PPT, vous créez essentiellement une présentation PowerPoint contenant des diapositives basées sur des images PNG.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Comment convertir PNG en PPT en Python" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install **Aspose.Slides for Python via .NET**. See [**Installation**](https://docs.aspose.com/slides/python-net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ajoutez la bibliothèque comme référence dans votre projet.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Créez une instance de la classe Presentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chargez l'image PNG que vous souhaitez convertir en PPT.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Enregistrez le fichier résultant en tant que présentation PPT.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Convertisseur en ligne gratuit"
  description="[Comment convertir PPT en HTML en Python](https://products.aspose.com/slides/fr/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Autres conversions PowerPoint prises en charge" subTitle="Vous pouvez également convertir des fichiers dans d'autres formats en PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/python-net/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/python-net/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/python-net/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/python-net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/python-net/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/python-net/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/python-net/conversion/html-to-pptx/" name="HTML TO PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
