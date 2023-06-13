---
title: Vízjel hozzáadása a ODP prezentációs fájlokhoz a Java használatával
url: /hu/java/watermark/odp/
keywords: Vízjel hozzáadása ODP, Szöveg vízjel hozzáadása ODP, Kép vízjel hozzáadása ODP
description: Java forráskód vízjel hozzáadásához a ODP prezentációhoz.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Vízjel hozzáadása a ODP prezentációhoz a Java használatával" h2="Készítse el saját Java alkalmazásait, amellyel szöveget vagy képet illeszthet be PPT-, PPTX- vagy ODP-prezentációba szerveroldali API-k segítségével." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Vízjel hozzáadása a ODP prezentációhoz a Java segítségével" %}}
A Aspose.Slides for Java használatával vízjelet adhat a ODP prezentációhoz. A vízjelek minden prezentáció elengedhetetlen részét képezik. Arra szolgálnak, hogy megvédjék a prezentáció tartalmát az engedély nélküli másolástól vagy felhasználástól. A vízjel egy látható vagy láthatatlan kép vagy szöveg, amely a prezentáció tetejére kerül. Segítségével azonosítható a prezentáció tulajdonosa, és megakadályozható a jogosulatlan használat. A vízjelek arra is használhatók, hogy professzionális hatást keltsenek a prezentációban, és még csiszoltabbnak tűnjenek. 
{{% blocks/products/pf/agp/code-block title="Szöveges vízjel hozzáadása a ODP fájlhoz a Java használatával" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    IMasterSlide master = pres.getMasters().get_Item(0);
    IAutoShape watermarkShape = master.getShapes().addAutoShape(ShapeType.Triangle, 0, 0, 0, 0);
    ITextFrame watermarkTextFrame = watermarkShape.addTextFrame("Watermark");

    pres.save("watermark.odp", SaveFormat.Odp);
} finally {
    if (pres != null) pres.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Kép vízjel hozzáadása a ODP prezentációhoz a Java használatával" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("watermark.png")));

    IMasterSlide master = pres.getMasters().get_Item(0);

    IAutoShape watermarkShape = master.getShapes().addAutoShape(ShapeType.Triangle, 0, 0, 100, 100);

    watermarkShape.getFillFormat().setFillType(FillType.Picture);
    watermarkShape.getFillFormat().getPictureFillFormat().getPicture().setImage(image);
    watermarkShape.getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);

    pres.save("watermark2.odp", SaveFormat.Odp);
} finally {
    if (pres != null) pres.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Vízjel hozzáadása a ODP fájlhoz a Java segítségével" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Ezek a lépések a szöveges vízjel hozzáadásához a ODP fájlokhoz." >}}

{{< blocks/products/pf/agp/step-autogen >}}
A ODP betöltése a Presentation egy példányával
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Válassza ki a fő bemutatót
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Adjon hozzá alaktípust az AddAutoShape módszerrel
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Adjon hozzá vízjelszöveget az AddTextFrame módszerrel
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Az eredmény mentése ODP formátumban
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott formátumok" subTitle="A Java használatával a következő formátumokhoz is hozzáadhat vízjelet:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/watermark/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/watermark/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}