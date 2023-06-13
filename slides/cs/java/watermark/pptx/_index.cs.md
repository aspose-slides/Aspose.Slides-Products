---
title: Přidat vodoznak do prezentačních souborů PPTX pomocí Java
url: /cs/java/watermark/pptx/
keywords: Přidat vodoznak PPTX, Přidat textový vodoznak PPTX, Přidat vodoznak obrázku PPTX
description: Zdrojový kód Java pro přidání vodoznaku do prezentace PPTX.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Přidat vodoznak do prezentace PPTX pomocí Java" h2="Vytvořte si své vlastní aplikace pro Java a vkládejte textový nebo obrázkový vodoznak do prezentace PPT, PPTX nebo ODP pomocí rozhraní API na straně serveru." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Přidat vodoznak do prezentace PPTX prostřednictvím Java" %}}
Pomocí Aspose.Slides for Java můžete přidat vodoznak do prezentace PPTX. Vodoznaky jsou nezbytnou součástí každé prezentace. Používají se k ochraně obsahu prezentace před kopírováním nebo používáním bez povolení. Vodoznak je viditelný nebo neviditelný obrázek nebo text, který je umístěn v horní části prezentace. Lze jej použít k identifikaci vlastníka prezentace a k zabránění neoprávněnému použití. Vodoznaky lze také použít, aby prezentaci dodaly profesionální nádech a aby vypadala uhlazeněji. 
{{% blocks/products/pf/agp/code-block title="Přidejte textový vodoznak do PPTX pomocí Java" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    IMasterSlide master = pres.getMasters().get_Item(0);
    IAutoShape watermarkShape = master.getShapes().addAutoShape(ShapeType.Triangle, 0, 0, 0, 0);
    ITextFrame watermarkTextFrame = watermarkShape.addTextFrame("Watermark");

    pres.save("watermark.pptx", SaveFormat.Pptx);
} finally {
    if (pres != null) pres.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Přidat vodoznak obrázku do prezentace PPTX pomocí Java" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("watermark.png")));

    IMasterSlide master = pres.getMasters().get_Item(0);

    IAutoShape watermarkShape = master.getShapes().addAutoShape(ShapeType.Triangle, 0, 0, 100, 100);

    watermarkShape.getFillFormat().setFillType(FillType.Picture);
    watermarkShape.getFillFormat().getPictureFillFormat().getPicture().setImage(image);
    watermarkShape.getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);

    pres.save("watermark2.pptx", SaveFormat.Pptx);
} finally {
    if (pres != null) pres.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Jak přidat vodoznak do PPTX prostřednictvím Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Toto jsou kroky k přidání textového vodoznaku do souborů PPTX." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Načtěte PPTX s instancí Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Vyberte hlavní prezentaci
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Přidejte typ tvaru pomocí metody AddAutoShape
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Přidejte text vodoznaku pomocí metody AddTextFrame
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Uložte výsledek ve formátu PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Další podporované formáty" subTitle="Pomocí Java můžete také přidat vodoznak do následujících formátů:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/java/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/java/watermark/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}