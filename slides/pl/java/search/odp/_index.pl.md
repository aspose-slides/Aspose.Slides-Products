---
title: Wyszukaj tekst w plikach prezentacji ODP za pomocą Java
url: /pl/java/search/odp/
keywords: wyszukaj słowa w ODP, wyszukaj i zamień tekst w ODP, wyszukaj tekst ODP Prezentacja
description: Kod źródłowy Java do wyszukiwania tekstu w prezentacji ODP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Wyszukaj tekst ODP za pomocą Java" h2="Twórz własne aplikacje Java do wyszukiwania i zastępowania tekstu w plikach prezentacji przy użyciu interfejsów API po stronie serwera. Dowiedz się, jak znaleźć wszystkie wejścia określonego słowa lub wyrażenia w dokumentach prezentacji. Wyszukuj tekst według dokładnego dopasowania danych i dopasowania wyrażenia regularnego." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Wyszukaj i zastąp tekst ODP Prezentacja za pośrednictwem Java" %}}
Podstawowe wyszukiwanie dokumentów i zastępowanie tekstu w treści, komentarzach, notatkach slajdów lub metadanych za pomocą interfejsów API Aspose.Slides for Java można wykonać za pomocą zaledwie kilku wierszy kodu. Użyj dopasowywania wyrażeń regularnych, dopasowuj wielkość liter, aby wyszukiwać tekst w prezentacji. Szukaj tekstu w tytułach, treści, stopce lub nagłówku.
{{% blocks/products/pf/agp/code-block title="Wyszukaj tekst ODP Prezentacja za pomocą Java" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("welcome-to-powerpoint.odp");
try {
    SlideUtil.findAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.save("replaced.odp", SaveFormat.Odp);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Jak wyszukiwać tekst w ODP przez Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Oto kroki wyszukiwania plików tekstowych ODP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Załaduj ODP z instancją Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Użyj metody [FindAndReplaceText](https://reference.aspose.com/slides/java/com.aspose.slides/slideutil/#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-), aby znaleźć i zamienić tekst.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Zapisz wynik w formacie ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Online ODP Wyszukaj prezentacje na żywo" sectionDescription="Wyszukuj i zastępuj tekst w treści, komentarzach lub metadanych w dokumentach ODP już teraz." >}}

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane formaty wyszukiwania" subTitle="Korzystając z Java, możesz również wyszukiwać tekst w następujących formatach:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/search/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/search/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}