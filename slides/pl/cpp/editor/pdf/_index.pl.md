---
title: Edytuj PDF w C++
url: /pl/cpp/editor/pdf/
keywords: Edytuj PDF, PDF, C++ API, bibliotekę C++
description: Edytuj PDF w C++. Użyj interfejsu API biblioteki C++ do edycji dokumentu PDF
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Edytuj PDF w C++" h2="Szybka i wieloplatformowa biblioteka C++ do edycji plików PDF przy użyciu kodu C++" >}}

{{% blocks/products/pf/feature-page-section h2="Edytuj PDF za pomocą Aspose.Slides" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/pl/cpp/) to potężna biblioteka C++ używana do manipulowania i edytowania prezentacji, dokumentów PDF i innych plików. Możesz edytować dokument PDF, dodając do niego nowy wiersz tekstu. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Edytuj PDF w C++" %}}
Korzystając z [**Aspose.Slides for C++**](https://products.aspose.com/slides/pl/cpp/), możesz dodać nowy wiersz tekstu do dokumentu PDF za pomocą zaledwie kilku wierszy kodu.

{{% blocks/products/pf/agp/code-block title="Kod C++ do edycji plików PDF" offSpacer="true" %}}
```cpp

auto pres = System::MakeObject<Presentation>();

pres->get_Slides()->RemoveAt(0);
pres->get_Slides()->AddFromPdf(u"document.pdf");

auto slide = pres->get_Slides()->idx_get(0);
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 50.0f);
shape->get_TextFrame()->set_Text(u"New text");

pres->Save(u"document.pdf", SaveFormat::Pdf);
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Jak edytować PDF w C++" >}}


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
Załaduj dokument PDF, który chcesz edytować.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Dodaj nowy wiersz tekstu.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Zapisz zmieniony plik PDF.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Edytuj inne pliki" subTitle="Możesz także edytować pliki w innych formatach" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/cpp/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/cpp/editor/html/" name="Edit HTML" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}