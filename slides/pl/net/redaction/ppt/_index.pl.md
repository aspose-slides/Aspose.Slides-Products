---
title: Zredaguj pliki prezentacji PPT za pomocą .NET
url: /pl/net/redaction/ppt/
keywords: Zredaguj PPT, znajdź i zamień tekst w PPT, zaktualizuj prezentację PPT
description: Kod źródłowy C# do znajdowania i zastępowania tekstu w prezentacji PPT.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Zredaguj PPT za pomocą C#" h2="Twórz własne aplikacje .NET, aby wyszukiwać i zamieniać tekst w plikach prezentacji za pomocą interfejsów API po stronie serwera. Dowiedz się, jak wyszukiwać i zastępować tekst w treści, komentarzach lub metadanych prezentacji PPT" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Zredaguj prezentację PPT za pośrednictwem C#" %}}
Podstawowe wyszukiwanie dokumentów i zastępowanie tekstu w treści, komentarzach, notatkach slajdów lub metadanych za pomocą interfejsów API Aspose.Slides for .NET można wykonać za pomocą zaledwie kilku wierszy kodu. Znajdź i zamień tekst w programach PowerPoint i OpenOffice. Edytuj tekst, komentarze, metadane w prezentacji za pomocą dopasowywania danych wyrażeń regularnych.
{{% blocks/products/pf/agp/code-block title="Zredaguj prezentację PPT za pomocą C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("welcome-to-powerpoint.ppt"))
{
    Aspose.Slides.Util.SlideUtil.FindAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.Save("replaced.ppt", SaveFormat.Ppt);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Jak zredagować PPT przez C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Oto kroki redagowania plików PPT." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Załaduj PPT z instancją Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Użyj metody [FindAndReplaceText](https://reference.aspose.com/slides/net/aspose.slides.util/slideutil/findandreplacetext/), aby znaleźć i zamienić tekst.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Zapisz wynik w formacie PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Online PPT Redakcyjne prezentacje na żywo" sectionDescription="Wyszukuj i zastępuj tekst w treści, komentarzach lub metadanych w dokumentach PPT już teraz." >}}

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane formaty redakcji" subTitle="Korzystając z C#, możesz również zredagować następujące formaty:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/net/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/net/redaction/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}