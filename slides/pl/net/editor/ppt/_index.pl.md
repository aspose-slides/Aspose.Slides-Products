---
title: Edytuj PPT w C#
url: /pl/net/editor/ppt/
keywords: Edytuj PPT, edytuj PowerPoint, PPT, PowerPoint, C# API, bibliotekę .NET
description: Edytuj PPT w C#. Użyj API biblioteki .NET do edycji prezentacji PowerPoint
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Edytuj PPT w C#" h2="Potężne, wieloplatformowe API .NET do edycji PPT przy użyciu kodu C# na platformach NET Framework, .NET Core, Windows Azure, Mono lub Xamarin" >}}

{{% blocks/products/pf/feature-page-section h2="Edytuj PPT za pomocą Aspose.Slides" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/pl/net/) to potężna biblioteka .NET używana do manipulowania i edytowania prezentacji. Możesz edytować prezentację PPT, dodając do niej nowy wiersz tekstu. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Edytuj PPT w C#" %}}
Korzystając z [**Aspose.Slides for .NET**](https://products.aspose.com/slides/pl/net/), możesz dodać nowy wiersz tekstu do dokumentu PPT za pomocą zaledwie kilku wierszy kodu.

{{% blocks/products/pf/agp/code-block title="Kod C# do edycji PPT" offSpacer="true" %}}
```cs
using (Presentation presentation = new Presentation("pres.ppt"))
{
    AutoShape shape = (AutoShape)presentation.Slides[0].Shapes[0];
    shape.TextFrame.Text = "New text";
    presentation.Save("pres.ppt", SaveFormat.Ppt);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Jak edytować PPT w C#" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Zainstaluj **Aspose.Slides dla platformy .NET**. Zobacz [**Instalacja**](https://docs.aspose.com/slides/net/installation/).
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

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/net/editor/pdf/" name="Edit PDF" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/net/editor/html/" name="Edit HTML" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}