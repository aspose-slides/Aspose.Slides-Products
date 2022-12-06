---
title: Fusionner l'image en BMP en C#
url: /fr/net/merger/image-to-bmp/
keywords: Image vers BMP, Fusionner l'image vers BMP, Joindre l'image vers BMP, Combiner des images, Image, BMP, API C#, Bibliothèque .NET
description: Fusionner l'image en BMP en C#. Utiliser l'API de la bibliothèque .NET pour combiner des images
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Fusionner l'image en BMP en C#" h2="Puissante API .NET multiplateforme pour fusionner des fichiers Image vers BMP à l'aide de code C# sur les plates-formes NET Framework, .NET Core, Windows Azure, Mono ou Xamarin" >}}

{{% blocks/products/pf/feature-page-section h2="Fusionner l'image en BMP à l'aide d'Aspose.Slides" %}}

[**Aspose.Slides pour .NET**](https://products.aspose.com/slides/fr/net/) est une puissante bibliothèque .NET utilisée pour créer, convertir, fusionner et manipuler des présentations, des PDF, des images, et d'autres fichiers. Lorsque vous fusionnez une image en BMP, vous combinez efficacement des images pour obtenir un seul fichier BMP.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Fusionner l'image en BMP en C#" %}}
En utilisant [**Aspose.Slides pour .NET**](https://products.aspose.com/slides/fr/net/), vous pouvez rapidement fusionner une image en BMP avec seulement quelques lignes de code

{{% blocks/products/pf/agp/code-block title="Code C# pour fusionner l'image en BMP" offSpacer="true" %}}
```cs
using (Presentation pres = new Presentation())
{
    IPPImage image = pres.Images.AddImage(File.ReadAllBytes("image1.png"));
    pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 0, 100, 100, image);

    IPPImage image2 = pres.Images.AddImage(File.ReadAllBytes("image2.png"));
    pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 200, 100, 100, image2);

    pres.Slides[0].GetThumbnail(new Size(960, 720)).Save("MergedFile.bmp", ImageFormat.Bmp);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Comment fusionner une image en BMP en C#" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Installez **Aspose.Slides pour .NET**. Voir [**Installation**](https://docs.aspose.com/slides/net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ajoutez la bibliothèque comme référence dans votre projet.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Créez une instance de la classe Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Chargez les images que vous souhaitez fusionner en tant que cadres photo.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Enregistrez le fichier BMP résultant.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Fusionner d'autres fichiers" subTitle="Vous pouvez également combiner des fichiers dans d'autres formats pour obtenir un seul fichier" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/net/merger/jpg-to-jpg/" name="JPG TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/net/merger/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/net/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/net/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/net/merger/pdf-to-pdf/" name="PDF TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/net/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/net/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/net/merger/svg-to-png/" name="SVG TO PNG" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/net/merger/html-to-image/" name="HTML TO IMAGE" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}