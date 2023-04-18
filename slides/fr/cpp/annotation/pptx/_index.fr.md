---
title: Supprimer l'annotation PPTX à l'aide de C++
weight: 4380
url: /fr/cpp/annotation/pptx/ 
description: Code source C++ pour supprimer les annotations de PPTX
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Supprimer les commentaires et les auteurs de commentaires de PPTX en C++" h2="Créez vos propres applications C++ pour manipuler les commentaires et les auteurs dans les fichiers de document à l'aide d'API côté serveur." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="Supprimer les commentaires de PPTX via C++" %}}
Afin de supprimer les annotations du fichier PPTX, nous utiliserons l'API [Aspose.Slides pour C++](https://products.aspose.com/slides/fr/cpp/) qui est riche en fonctionnalités, puissante et facile à utiliser API de manipulation de documents pour la plate-forme C++.
{{% blocks/products/pf/agp/code-block title="Supprimer les annotations de PPTX - C++" offSpacer="true" %}}

```cpp

using namespace Aspose::Slides;
using namespace Aspose::Slides::Export;
using namespace System::Drawing;

auto presentation = System::MakeObject<Presentation>(u"example.pptx");

// Deletes all comments from the presentation
for (auto author : presentation->get_CommentAuthors())
{
    author->get_Comments()->Clear();
}
        
// Deletes all authors
presentation->get_CommentAuthors()->Clear();
presentation->Save(u"example_out.pptx", SaveFormat::Pptx);
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/feature-page-section  h2="Comment supprimer des commentaires de PPTX via C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installez **Aspose.Slides pour C++**. Voir [**Installation**](https://docs.aspose.com/slides/cpp/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Charger PPTX avec une instance de la classe Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Itérer sur tous les auteurs du PPTX chargé
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Supprimer tous les commentaires d'un auteur
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Supprimer tous les auteurs à la fin
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Autres formats d'annotation pris en charge" subTitle="En utilisant C++, on peut facilement annoter d'autres formats, y compris." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/annotation/ppt/" name="PPT" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}