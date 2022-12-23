---
title: Bewerk PPT in C++
url: /nl/cpp/editor/ppt/
keywords: PPT bewerken, PowerPoint, PPT, PowerPoint, C++ API, C++-bibliotheek bewerken
description: Bewerk PPT in C++. Gebruik de C++-bibliotheek-API om de PowerPoint-presentatie te bewerken
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Bewerk PPT in C++" h2="Snelle en platformonafhankelijke C++-bibliotheek voor het bewerken van PPT met behulp van C++-code" >}}

{{% blocks/products/pf/feature-page-section h2="Bewerk PPT met Aspose.Slides" %}}

[**Aspose.Slides voor C++**](https://products.aspose.com/slides/nl/cpp/) is een krachtige C++-bibliotheek die wordt gebruikt om presentaties te manipuleren en te bewerken. U kunt een PPT-presentatie bewerken door er een nieuwe regel tekst aan toe te voegen. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Bewerk PPT in C++" %}}
Met behulp van [**Aspose.Slides voor C++**](https://products.aspose.com/slides/nl/cpp/) kunt u met slechts een paar regels code een nieuwe regel tekst toevoegen aan een PPT-document.

{{% blocks/products/pf/agp/code-block title="C++-code voor het bewerken van PPT" offSpacer="true" %}}
```cpp

auto pres = System::MakeObject<Presentation>(u"pres.ppt");

auto slide = pres->get_Slides()->idx_get(0);
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 50.0f);
shape->get_TextFrame()->set_Text(u"New text");

pres->Save(u"pres.pdf", SaveFormat::Ppt);
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Hoe PPT in C++ te bewerken" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Installeer **Aspose.Slides voor C++**. Zie [**Installatie**](https://docs.aspose.com/slides/cpp/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Voeg de bibliotheek toe als referentie in uw project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Maak een instantie van de klasse Presentatie.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laad de PPT-presentatie die u wilt bewerken.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Voeg een nieuwe regel tekst toe.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sla het gewijzigde PowerPoint-bestand op.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Bewerk andere bestanden" subTitle="U kunt ook bestanden in andere indelingen bewerken" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/cpp/editor/pdf/" name="Edit PDF" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/cpp/editor/html/" name="Edit HTML" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}