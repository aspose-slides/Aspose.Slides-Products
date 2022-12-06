---
title: Egyesítse az SVG-t PNG-be Java nyelven
url: /hu/java/merger/svg-to-png/
keywords: Egyesítse az SVG-t PNG-be, SVG-t PNG-be, csatlakozzon az SVG-hez PNG-hez, egyesítse az SVG-t PNG-be, Java API, Java Library
description: Egyesítse az SVG-t PNG-be Java nyelven. Használja a Java könyvtár API-t az SVG és PNG fájlok kombinálásához
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Egyesítse az SVG-t PNG-be Java nyelven" h2="Nagy sebességű és többplatformos Java könyvtár az SVG-képek PNG-képek egyesítéséhez Java kód használatával" >}}

{{% blocks/products/pf/feature-page-section h2="Egyesítse az SVG-t PNG-be az Aspose.Slides segítségével" %}}

Az [**Aspose.Slides for Java**](https://products.aspose.com/slides/hu/java/) egy hatékony Java-könyvtár, amellyel prezentációkat, képeket és egyéb fájlokat egyesíthet és kezelhet. Ha egyesíti az SVG-t PNG-vel, akkor hatékonyan kombinálja az SVG-képeket, hogy PNG-képet kapjon.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Egyesítse az SVG-t PNG-be Java nyelven" %}}
Az [**Aspose.Slides for Java**](https://products.aspose.com/slides/hu/java/) használatával gyorsan egyesítheti az SVG-fájlokat PNG-fájlokkal, mindössze néhány sornyi kóddal.

{{% blocks/products/pf/agp/code-block title="Java kód az SVG és a PNG egyesítéséhez" offSpacer="true" %}}
```java

Presentation pres = new Presentation();
try {
    String svgContent = new String(Files.readAllBytes("image.svg"));
    ISvgImage svgImage = new SvgImage(svgContent);
    IPPImage ppImage = pres.getImages().addImage(svgImage);
    pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 
			ppImage.getWidth(), ppImage.getHeight(), ppImage);

    for (int index = 0; index < pres.getSlides().size(); index++)
    {
        ISlide slide = pres.getSlides().get_Item(index);
        BufferedImage bufferedImage = slide.getThumbnail();
        ImageIO.write(bufferedImage, "PNG", new File("image_java_" + index + ".png"));
    }
} finally {
    if (pres != null) pres.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Hogyan lehet egyesíteni az SVG-t PNG-vel Java-ban" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Telepítse az **Aspose.Slides for Java** programot. Lásd: [**Telepítés**](https://docs.aspose.com/slides/java/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Adja hozzá a könyvtárat referenciaként a projekthez.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Hozzon létre egy példányt a Prezentáció osztályból.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Töltse be az egyesíteni kívánt SVG-fájlokat.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Mentse el a kapott PNG-képet.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Más fájlok egyesítése" subTitle="Más formátumú fájlokat is kombinálhat egyetlen fájl létrehozásához" >}}
  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/merger/jpg-to-jpg/" name="JPG TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/merger/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/merger/pdf-to-pdf/" name="PDF TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/merger/image-to-bmp/" name="IMAGE TO BMP" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/merger/html-to-image/" name="HTML TO IMAGE" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}