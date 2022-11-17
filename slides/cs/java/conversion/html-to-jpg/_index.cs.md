---
title: Převeďte HTML do JPG v Javě
url: /cs/java/conversion/html-to-jpg/
keywords: HTML do JPG, Převést HTML do JPG, Java API, Java Library, HTML, JPG
description: Převeďte HTML do JPG v Javě. K převodu souborů HTML na JPG použijte rozhraní API knihovny Java
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Převeďte HTML do JPG v Javě" h2="Vysokorychlostní a multiplatformní knihovna Java, která pomáhá při vývoji aplikací se schopností vytvářet, slučovat, kontrolovat nebo převádět prezentační soubory Microsoft PowerPoint a OpenOffice bez použití jakéhokoli softwaru, jako je Microsoft nebo Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Převeďte HTML do JPG v Javě" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/cs/java/) je výkonná Java knihovna pro vytváření a manipulaci s prezentačními soubory. Navíc poskytuje flexibilní způsoby převodu HTML do JPG. Pomocí **Aspose.Slides for Java** může každý vývojář nebo aplikace převést soubory HTML do JPG pomocí několika řádků kódu Java.

Aspose.Slides for Java jako moderní API pro zpracování dokumentů rychle exportuje soubory HTML do formátů souborů JPG. Knihovna Aspose PowerPoint vám umožňuje převést HTML do JPGs a mnoho dalších formátů souborů

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Převeďte HTML do JPG pomocí Javy" %}}
Chcete-li převést HTML do JPG, budete muset vytvořit prezentaci ze souboru HTML a uložit ji jako JPG.

{{% blocks/products/pf/agp/code-block title="Java kód pro převod HTML do JPG" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    TextReader tr = new StreamReader("file.html");
    pres.getSlides().addFromHtml(tr);
    Dimension size = new Dimension(960, 720);
    for (int index = 0; index < pres.getSlides().size(); index++)
    {
        ISlide slide = pres.getSlides().get_Item(index);
        BufferedImage bufferedImage = slide.getThumbnail(size);
        ImageIO.write(bufferedImage, "jpeg", new File("image_java_" + index + ".jpg"));
    }
} finally {
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Jak převést HTML do JPG pomocí Aspose.Slides for Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Toto jsou kroky k převodu HTML do JPG v Javě." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Nainstalujte [**Aspose.Slides for Java**](https://products.aspose.com/slides/cs/java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Přidejte odkaz na knihovnu (importujte knihovnu) do svého projektu Java.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Otevřete zdrojové soubory HTML v Javě.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Uložit výsledek jako soubor JPG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Převést HTML do jiných podporovaných formátů" subTitle="Můžete také převést HTML a uložit do jiných formátů souborů. Všechny podporované formáty naleznete níže" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/java/conversion/html-to-image/" name="HTML TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/java/conversion/html-to-pdf/" name="HTML TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/java/conversion/html-to-png/" name="HTML TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/java/conversion/html-to-tiff/" name="HTML TO TIFF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/java/conversion/html-to-xml/" name="HTML TO XML" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}