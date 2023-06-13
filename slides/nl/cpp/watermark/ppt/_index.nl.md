---
title: Watermerk toevoegen aan PPT presentatiebestanden met C++
url: /nl/cpp/watermark/ppt/
keywords: Watermerk toevoegen PPT, Tekstwatermerk toevoegen PPT, Afbeeldingswatermerk toevoegen PPT
description: C++ broncode voor het toevoegen van watermerk aan PPT presentatie.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Watermerk toevoegen aan presentatie PPT met behulp van C++" h2="Bouw uw eigen C++-apps om tekst- of afbeeldingswatermerken in PPT-, PPTX- of ODP-presentaties in te voegen met behulp van server-side API's." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="Watermerk toevoegen aan presentatie PPT via C++" %}}
Met Aspose.Slides for C++ kunt u een watermerk toevoegen aan de PPT-presentatie. Watermerken zijn een essentieel onderdeel van elke presentatie. Ze worden gebruikt om te voorkomen dat de inhoud van de presentatie zonder toestemming wordt gekopieerd of gebruikt. Een watermerk is een zichtbare of onzichtbare afbeelding of tekst die bovenop de presentatie wordt geplaatst. Het kan worden gebruikt om de eigenaar van de presentatie te identificeren en ongeoorloofd gebruik te voorkomen. Watermerken kunnen ook worden gebruikt om een ​​professionele toets aan de presentatie te geven en deze er verzorgder uit te laten zien. 
{{% blocks/products/pf/agp/code-block title="Voeg tekstwatermerk toe aan PPT met C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);
auto master = presentation->get_Masters()->idx_get(0);
auto watermarkShape = slide->get_Shapes()->AddAutoShape(ShapeType::Triangle, 0.0f, 0.0f, 0.0f, 0.0f);

auto watermarkTextFrame = watermarkShape->AddTextFrame(u"Watermark");
presentation->Save(u"watermark.ppt", SaveFormat::Ppt);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Afbeeldingswatermerk toevoegen aan presentatie PPT met behulp van C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);
auto master = presentation->get_Masters()->idx_get(0);
auto watermarkShape = slide->get_Shapes()->AddAutoShape(ShapeType::Triangle, 0.0f, 0.0f, 0.0f, 0.0f);

auto image = presentation->get_Images()->AddImage(:File::ReadAllBytes(u"watermark.png"));

watermarkShape->get_FillFormat()->set_FillType(FillType::Picture);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->get_Picture()->set_Image(image);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->set_PictureFillMode(PictureFillMode::Stretch);

presentation->Save(u"watermark2.ppt", SaveFormat::Ppt);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Watermerk toevoegen aan PPT via C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Dit zijn de stappen om een ​​tekstwatermerk toe te voegen aan PPT-bestanden." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laad PPT met een instantie van Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Selecteer de masterpresentatie
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Vormtype toevoegen met de methode AddAutoShape
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Voeg watermerktekst toe met de methode AddTextFrame
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sla resultaat op in PPT formaat
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde formaten" subTitle="Met C++ kunt u ook een watermerk toevoegen aan de volgende indelingen:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/cpp/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/cpp/watermark/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}