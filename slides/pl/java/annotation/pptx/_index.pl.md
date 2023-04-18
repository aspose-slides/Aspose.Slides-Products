---
title: Usuń adnotację PPTX za pomocą Java
weight: 360
url: /pl/java/annotation/pptx/ 
description: Przykładowy kod Java służący do usuwania adnotacji w formacie PPTX w środowisku Java Runtime Environment dla aplikacji JSP/JSF i aplikacji komputerowych.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Usuń komentarze i autorów komentarzy z PPTX w Javie" h2="Twórz własne aplikacje Java, aby manipulować komentarzami i autorami w plikach dokumentów za pomocą interfejsów API po stronie serwera." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{% blocks/products/pf/feature-page-section  h2="Usuń komentarze z PPTX przez Javę" %}}
Aby usunąć adnotacje z pliku PPTX, użyjemy [Aspose.Slides for Java](https://products.aspose.com/slides/pl/java/) API, które jest bogate w funkcje, wydajne i łatwe w użyciu API manipulacji dokumentami dla platformy Java.
{{% blocks/products/pf/agp/code-block title="Usuń adnotacje z PPTX — Java" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("example.pptx");
try {
    // Deletes all comments from the presentation
    for (ICommentAuthor author : presentation.getCommentAuthors())
    {
        author.getComments().clear();
    }

    // Deletes all authors
    presentation.getCommentAuthors().clear();

    presentation.save("example_out.pptx", SaveFormat.Pptx);
} finally {
    if (presentation != null) presentation.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/feature-page-section  h2="Jak usunąć komentarze z PPTX przez Javę" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Zainstaluj **Aspose.Slides dla Javy**. Zobacz [**Instalacja**](https://docs.aspose.com/slides/java/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Załaduj PPTX z instancją klasy Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Iteruj przez wszystkich autorów załadowanego PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Usuń wszystkie komentarze autora
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Usuń wszystkich autorów na końcu
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane formaty adnotacji" subTitle="Korzystając z języka Java, można łatwo dodawać adnotacje do innych formatów, w tym." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/annotation/ppt/" name="PPT" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}