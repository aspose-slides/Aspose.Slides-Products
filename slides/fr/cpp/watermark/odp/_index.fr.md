---
title: Ajouter un filigrane aux fichiers de présentation ODP à l'aide de C++
url: /fr/cpp/watermark/odp/
keywords: Ajouter un filigrane ODP, Ajouter un filigrane de texte ODP, Ajouter un filigrane d'image ODP
description: Code source C++ pour ajouter un filigrane à la présentation ODP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Ajouter un filigrane à la présentation ODP en utilisant C++" h2="Créez vos propres applications C++ pour insérer un filigrane de texte ou d'image dans une présentation PPT, PPTX ou ODP à l'aide d'API côté serveur." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="Ajouter un filigrane à la présentation ODP via C++" %}}
À l'aide de Aspose.Slides for C++, vous pouvez ajouter un filigrane à la présentation ODP. Les filigranes sont une partie essentielle de toute présentation. Ils sont utilisés pour protéger le contenu de la présentation contre toute copie ou utilisation sans autorisation. Un filigrane est une image ou un texte visible ou invisible placé au-dessus de la présentation. Il peut être utilisé pour identifier le propriétaire de la présentation et empêcher toute utilisation non autorisée. Les filigranes peuvent également être utilisés pour ajouter une touche professionnelle à la présentation et lui donner un aspect plus soigné. 
{{% blocks/products/pf/agp/code-block title="Ajouter un filigrane de texte à ODP en utilisant C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);
auto master = presentation->get_Masters()->idx_get(0);
auto watermarkShape = slide->get_Shapes()->AddAutoShape(ShapeType::Triangle, 0.0f, 0.0f, 0.0f, 0.0f);

auto watermarkTextFrame = watermarkShape->AddTextFrame(u"Watermark");
presentation->Save(u"watermark.odp", SaveFormat::Odp);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Ajouter un filigrane d'image à la présentation ODP à l'aide de C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);
auto master = presentation->get_Masters()->idx_get(0);
auto watermarkShape = slide->get_Shapes()->AddAutoShape(ShapeType::Triangle, 0.0f, 0.0f, 0.0f, 0.0f);

auto image = presentation->get_Images()->AddImage(:File::ReadAllBytes(u"watermark.png"));

watermarkShape->get_FillFormat()->set_FillType(FillType::Picture);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->get_Picture()->set_Image(image);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->set_PictureFillMode(PictureFillMode::Stretch);

presentation->Save(u"watermark2.odp", SaveFormat::Odp);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Comment ajouter un filigrane à ODP via C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Voici les étapes pour ajouter un filigrane de texte aux fichiers ODP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Charger ODP avec une instance de Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sélectionnez la présentation principale
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ajouter un type de forme à l'aide de la méthode AddAutoShape
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ajouter du texte en filigrane à l'aide de la méthode AddTextFrame
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Enregistrer le résultat au format ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Autres formats pris en charge" subTitle="À l'aide de C++, vous pouvez également ajouter un filigrane aux formats suivants :" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/watermark/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/watermark/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}