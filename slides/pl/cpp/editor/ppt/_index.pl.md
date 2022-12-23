---
title: Edytuj PPT w C++
url: /pl/cpp/editor/ppt/
keywords: Edytuj PPT, edytuj PowerPoint, PPT, PowerPoint, C++ API, bibliotekę C++
description: Edytuj PPT w C++. Użyj API biblioteki C++ do edycji prezentacji PowerPoint
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Edytuj PPT w C++" h2="Szybka i wieloplatformowa biblioteka C++ do edycji PPT przy użyciu kodu C++" >}}

{{% blocks/products/pf/feature-page-section h2="Edytuj PPT za pomocą Aspose.Slides" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/pl/cpp/) to potężna biblioteka C++ używana do manipulowania i edytowania prezentacji. Możesz edytować prezentację PPT, dodając do niej nowy wiersz tekstu. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Edytuj PPT w C++" %}}
Korzystając z [**Aspose.Slides for C++**](https://products.aspose.com/slides/pl/cpp/), możesz dodać nowy wiersz tekstu do dokumentu PPT za pomocą zaledwie kilku wierszy kodu.

{{% blocks/products/pf/agp/code-block title="Kod C++ do edycji PPT" offSpacer="true" %}}
```cpp

auto pres = System::MakeObject<Presentation>(u"pres.ppt");

auto slide = pres->get_Slides()->idx_get(0);
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 50.0f);
shape->get_TextFrame()->set_Text(u"New text");

pres->Save(u"pres.pdf", SaveFormat::Ppt);
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Jak edytować PPT w C++" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Zainstaluj **Aspose.Slides dla C++**. Zobacz [**Instalacja**](https://docs.aspose.com/slides/cpp/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Dodaj bibliotekę jako odniesienie w swoim projekcie.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Utwórz wystąpienie klasy Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Załaduj prezentację PPT, którą chcesz edytować.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Dodaj nowy wiersz tekstu.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Zapisz zmieniony plik programu PowerPoint.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Edytuj inne pliki" subTitle="Możesz także edytować pliki w innych formatach" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/cpp/editor/pdf/" name="Edit PDF" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/cpp/editor/html/" name="Edit HTML" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}