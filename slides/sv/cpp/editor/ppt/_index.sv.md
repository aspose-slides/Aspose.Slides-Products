---
title: Redigera PPT i C++
url: /sv/cpp/editor/ppt/
keywords: Redigera PPT, Redigera PowerPoint, PPT, PowerPoint, C++ API, C++ Library
description: Redigera PPT i C++. Använd C++ biblioteks-API för att redigera PowerPoint-presentation
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Redigera PPT i C++" h2="Höghastighets- och plattformsoberoende C++-bibliotek för redigering av PPT med C++-kod" >}}

{{% blocks/products/pf/feature-page-section h2="Redigera PPT med Aspose.Slides" %}}

[**Aspose.Slides för C++**](https://products.aspose.com/slides/sv/cpp/) är ett kraftfullt C++-bibliotek som används för att manipulera och redigera presentationer. Du kan redigera en PPT-presentation genom att lägga till en ny textrad till den. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Redigera PPT i C++" %}}
Med [**Aspose.Slides för C++**](https://products.aspose.com/slides/sv/cpp/) kan du lägga till en ny textrad till ett PPT-dokument med bara några rader kod.

{{% blocks/products/pf/agp/code-block title="C++-kod för redigering av PPT" offSpacer="true" %}}
```cpp

auto pres = System::MakeObject<Presentation>(u"pres.ppt");

auto slide = pres->get_Slides()->idx_get(0);
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 50.0f);
shape->get_TextFrame()->set_Text(u"New text");

pres->Save(u"pres.pdf", SaveFormat::Ppt);
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Hur man redigerar PPT i C++" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Installera **Aspose.Slides för C++**. Se [**Installation**](https://docs.aspose.com/slides/cpp/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lägg till biblioteket som referens i ditt projekt.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Skapa en instans av klassen Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ladda PPT-presentationen du vill redigera.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lägg till en ny textrad.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Spara den ändrade PowerPoint-filen.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Redigera andra filer" subTitle="Du kan även redigera filer i andra format" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/editor/pdf/" name="Edit PDF" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/editor/html/" name="Edit HTML" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}