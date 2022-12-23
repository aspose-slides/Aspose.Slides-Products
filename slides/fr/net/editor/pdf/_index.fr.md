---
title: Modifier un PDF en C#
url: /fr/net/editor/pdf/
keywords: Modifier PDF, PDF, API C#, bibliothèque .NET
description: Modifier un PDF en C#. Utiliser l'API de la bibliothèque .NET pour modifier le document PDF
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Modifier un PDF en C#" h2="Puissante API .NET multiplateforme pour l'édition de PDF à l'aide de code C# sur les plates-formes NET Framework, .NET Core, Windows Azure, Mono ou Xamarin" >}}

{{% blocks/products/pf/feature-page-section h2="Modifier un PDF à l'aide d'Aspose.Slides" %}}

[**Aspose.Slides pour .NET**](https://products.aspose.com/slides/fr/net/) est une puissante bibliothèque .NET utilisée pour manipuler et modifier des présentations, des documents PDF et d'autres fichiers. Vous pouvez modifier un document PDF en y ajoutant une nouvelle ligne de texte. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Modifier un PDF en C#" %}}
En utilisant [**Aspose.Slides pour .NET**](https://products.aspose.com/slides/fr/net/), vous pouvez ajouter une nouvelle ligne de texte à un document PDF avec seulement quelques lignes de code.

{{% blocks/products/pf/agp/code-block title="Code C# pour l'édition de PDF" offSpacer="true" %}}
```cs
using (Presentation pres = new Presentation())
{
    pres.Slides.RemoveAt(0); // remove default empty slide
    pres.Slides.AddFromPdf("doc.pdf");

    AutoShape shape = (AutoShape)pres.Slides[0].Shapes[0];
    shape.TextFrame.Text = "New text";

    pres.Save("doc.pdf", SaveFormat.Pdf);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Comment éditer un PDF en C#" >}}


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
Chargez le document PDF que vous souhaitez modifier.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ajoutez une nouvelle ligne de texte.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Enregistrez le fichier PDF modifié.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Modifier d'autres fichiers" subTitle="Vous pouvez également modifier des fichiers dans d'autres formats" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/net/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/net/editor/html/" name="Edit HTML" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}