---
title: Dodaj znak wodny do PPT plików prezentacji za pomocą Java
url: /pl/java/watermark/ppt/
keywords: Dodaj znak wodny PPT, Dodaj tekstowy znak wodny PPT, Dodaj graficzny znak wodny PPT
description: Kod źródłowy Java do dodawania znaku wodnego do prezentacji PPT.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Dodaj znak wodny do PPT prezentacji za pomocą Java" h2="Twórz własne aplikacje Java, aby wstawiać tekstowy lub graficzny znak wodny do prezentacji PPT, PPTX lub ODP za pomocą interfejsów API po stronie serwera." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Dodaj znak wodny do PPT prezentacji za pośrednictwem Java" %}}
Za pomocą Aspose.Slides for Java możesz dodać znak wodny do prezentacji PPT. Znaki wodne są istotną częścią każdej prezentacji. Służą one ochronie treści prezentacji przed kopiowaniem lub wykorzystywaniem bez zezwolenia. Znak wodny to widoczny lub niewidoczny obraz lub tekst umieszczony w górnej części prezentacji. Może służyć do identyfikacji właściciela prezentacji i zapobiegania nieautoryzowanemu użyciu. Znaki wodne mogą również służyć do nadania prezentacji profesjonalnego charakteru i nadania jej bardziej dopracowanego wyglądu. 
{{% blocks/products/pf/agp/code-block title="Dodaj tekstowy znak wodny do PPT za pomocą Java" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    IMasterSlide master = pres.getMasters().get_Item(0);
    IAutoShape watermarkShape = master.getShapes().addAutoShape(ShapeType.Triangle, 0, 0, 0, 0);
    ITextFrame watermarkTextFrame = watermarkShape.addTextFrame("Watermark");

    pres.save("watermark.ppt", SaveFormat.Ppt);
} finally {
    if (pres != null) pres.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Dodaj znak wodny obrazu do PPT prezentacji za pomocą Java" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("watermark.png")));

    IMasterSlide master = pres.getMasters().get_Item(0);

    IAutoShape watermarkShape = master.getShapes().addAutoShape(ShapeType.Triangle, 0, 0, 100, 100);

    watermarkShape.getFillFormat().setFillType(FillType.Picture);
    watermarkShape.getFillFormat().getPictureFillFormat().getPicture().setImage(image);
    watermarkShape.getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);

    pres.save("watermark2.ppt", SaveFormat.Ppt);
} finally {
    if (pres != null) pres.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Jak dodać znak wodny do PPT przez Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Oto kroki, aby dodać tekstowy znak wodny do plików PPT." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Załaduj PPT z instancją Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Wybierz główną prezentację
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Dodaj typ kształtu za pomocą metody AddAutoShape
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Dodaj tekst znaku wodnego za pomocą metody AddTextFrame
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Zapisz wynik w formacie PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane formaty" subTitle="Korzystając z Java, możesz również dodać znak wodny do następujących formatów:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/watermark/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}