---
title: Fusionnez PDF, PPT, PPTX et de nombreux autres formats de fichiers à l'aide de C#
url: /fr/net/merger/
keywords: Fusionner, Joindre, PowerPoint, Présentation, C#, .NET, Aspose
description: Fusionnez plusieurs fichiers en C # PPT, PPTX, ODP, PDF, PNG, JPG et bien d'autres.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Fusionnez Powerpoint, PDF, PPT ou d'autres documents ensemble en C#" h2="Bibliothèque C# haute vitesse pour fusionner les formats PPT, PPTX, PDF, PNG, JPEG et autres." >}}

{{% blocks/products/pf/feature-page-section h2="Fusionner PPT, PPTX, PDF en utilisant C#" %}}

[**Aspose.Slides pour .NET**](https://products.aspose.com/slides/fr/net/) est une puissante bibliothèque C# pour créer et manipuler des fichiers de présentation. De plus, il offre des moyens flexibles de combiner plusieurs présentations PPT/PPTX. Lorsque vous fusionnez une présentation avec une autre, vous combinez efficacement leurs diapositives dans une seule présentation pour obtenir un fichier. Aspose.Slides vous permet de fusionner deux présentations de différentes manières. Vous pouvez fusionner des présentations avec toutes leurs formes, styles, textes, mises en forme, commentaires, animations, etc. sans avoir à vous soucier de la perte de qualité ou de données.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Fusionner des présentations PowerPoint en C#" %}}
Pour fusionner les présentations PowerPoint, vous devrez cloner les diapositives d'une présentation à l'autre.

{{% blocks/products/pf/agp/code-block title="Fusionner des fichiers PPTX à l'aide de C#" offSpacer="true" %}}

```csharp

// Instantiate a Presentation object that represents a target presentation file
using (Presentation presentation1 = new Presentation("presentation1.pptx"))
{
    // Instantiate a Presentation object that represents a source presentation file
    using (Presentation presentation2 = new Presentation("presentation2.pptx"))
    {
        foreach (ISlide slide in presentation2.Slides)
        {
            // Merge slides from source to target 
            presentation1.Slides.AddClone(slide);
        }
    }
    // Save the presentation
    presentation1.Save("merged-presentation.pptx", Export.SaveFormat.Pptx);
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Fusionner des présentations avec Slide Master à l'aide de C #" %}}
Ce code C # montre comment fusionner plusieurs présentations en une seule et appliquer des styles à partir du modèle de présentation du maître des diapositives. Ainsi, la présentation des résultats conservera la même mise en forme source et contiendra la mise en forme de la diapositive principale d'une autre présentation.

{{% blocks/products/pf/agp/code-block title="Fusionner plusieurs PPT en un seul en C#" offSpacer="true" %}}

``` csharp

// Instantiate a Presentation object that represents a target presentation file
using (Presentation presentation1 = new Presentation("presentation1.pptx"))
{
    // Instantiate a Presentation object that represents a source presentation file
    using (Presentation presentation2 = new Presentation("presentation2.pptx"))
    {
        // Merge first two slides only using slide master
        presentation1.Slides.AddClone(presentation2.Slides[0], presentation1.Masters[0], true);
        presentation1.Slides.AddClone(presentation2.Slides[1], presentation1.Masters[0], true);
    }
    presentation1.Save("merged-presentation-master.pptx", Export.SaveFormat.Pptx);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Comment fusionner des présentations à l'aide d'Aspose.Slides pour l'API .NET" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Voici les étapes pour fusionner deux fichiers PPTX et enregistrer le résultat au format PDF dans .NET." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installez [**Aspose.Slides pour .NET**](https://docs.aspose.com/slides/net/installation/). 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ajoutez une référence de bibliothèque (importez la bibliothèque) à votre projet C#.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ouvrez les fichiers PPTX sources en C#.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Combinez les fichiers PPTX à l'aide de la méthode **AddClone**.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Enregistrez la présentation et obtenez le résultat sous forme de fichier PDF unique.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Autres formats pris en charge à fusionner" subTitle="Vous pouvez également combiner d'autres formats de fichiers. Voir les autres formats pris en charge ci-dessous." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/net/merger/otp/" name="OTP" description="OpenDocument Standard Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/net/merger/pot/" name="POT" description="Microsoft PowerPoint Template Files" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/net/merger/potm/" name="POTM" description="Microsoft PowerPoint Template File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/net/merger/potx/" name="POTX" description="Microsoft PowerPoint Template Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/net/merger/pps/" name="PPS" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/net/merger/ppsm/" name="PPSM" description="Macro-enabled Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/net/merger/ppsx/" name="PPSX" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/net/merger/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/net/merger/pptm/" name="PPTM" description="Macro-enabled Presentation File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/net/merger/pptx/" name="PPTX" description="Open XML presentation Format" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}