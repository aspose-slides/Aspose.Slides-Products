---
title: Převeďte JPG do Image v Javě
url: /cs/java/conversion/jpg-to-image/
keywords: JPG do Image, Převést JPG do Image, Java API, Java Library, JPG, Image
description: Převeďte JPG do Image v Javě. K převodu souborů JPG na Image použijte rozhraní API knihovny Java
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Převeďte JPG do Image v Javě" h2="Vysokorychlostní a multiplatformní knihovna Java, která pomáhá při vývoji aplikací se schopností vytvářet, slučovat, kontrolovat nebo převádět prezentační soubory Microsoft PowerPoint a OpenOffice bez použití jakéhokoli softwaru, jako je Microsoft nebo Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Převeďte JPG do Image v Javě" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/cs/java/) je výkonná Java knihovna pro vytváření a manipulaci s prezentačními soubory. Navíc poskytuje flexibilní způsoby převodu JPG do Image. Pomocí **Aspose.Slides for Java** může každý vývojář nebo aplikace převést soubory JPG do Image pomocí několika řádků kódu Java.

Aspose.Slides for Java jako moderní API pro zpracování dokumentů rychle exportuje soubory JPG do formátů souborů Image. Knihovna Aspose PowerPoint vám umožňuje převést JPG do Images a mnoho dalších formátů souborů

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Převeďte JPG do Image pomocí Javy" %}}
Chcete-li převést JPG do Image, budete muset vytvořit prezentaci ze souboru JPG a uložit ji jako Image.

{{% blocks/products/pf/agp/code-block title="Java kód pro převod JPG do Image" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    ISlide slide = pres.getSlides().get_Item(0);
	IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.jpg")));
	slide.getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
    Dimension size = new Dimension(960, 720);
    for (int index = 0; index < pres.getSlides().size(); index++)
    {
        ISlide slide = pres.getSlides().get_Item(index);
        BufferedImage bufferedImage = slide.getThumbnail(size);
        ImageIO.write(bufferedImage, "PNG", new File("image_java_" + index + ".png"));
    }
} finally {
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Jak převést JPG do Image pomocí Aspose.Slides for Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Toto jsou kroky k převodu JPG do Image v Javě." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Nainstalujte [**Aspose.Slides for Java**](https://products.aspose.com/slides/cs/java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Přidejte odkaz na knihovnu (importujte knihovnu) do svého projektu Java.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Otevřete zdrojové soubory JPG v Javě.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Uložit výsledek jako soubor Image.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Zdarma online konvertor" sectionDescription="[Jak převést PPT na HTML v Pythonu](https://products.aspose.com/slides/cs/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Převést JPG do jiných podporovaných formátů" subTitle="Můžete také převést JPG a uložit do jiných formátů souborů. Všechny podporované formáty naleznete níže" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/java/conversion/jpg-to-png/" name="JPG TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/java/conversion/jpg-to-pdf/" name="JPG TO PDF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}