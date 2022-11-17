---
title: Převeďte PDF do SVG v Javě
url: /cs/java/conversion/pdf-to-svg/
keywords: PDF do SVG, Převést PDF do SVG, Java API, Java Library, PDF, SVG
description: Převeďte PDF do SVG v Javě. K převodu souborů PDF na SVG použijte rozhraní API knihovny Java
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Převeďte PDF do SVG v Javě" h2="Vysokorychlostní a multiplatformní knihovna Java, která pomáhá při vývoji aplikací se schopností vytvářet, slučovat, kontrolovat nebo převádět prezentační soubory Microsoft PowerPoint a OpenOffice bez použití jakéhokoli softwaru, jako je Microsoft nebo Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Převeďte PDF do SVG v Javě" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/cs/java/) je výkonná Java knihovna pro vytváření a manipulaci s prezentačními soubory. Navíc poskytuje flexibilní způsoby převodu PDF do SVG. Pomocí **Aspose.Slides for Java** může každý vývojář nebo aplikace převést soubory PDF do SVG pomocí několika řádků kódu Java.

Aspose.Slides for Java jako moderní API pro zpracování dokumentů rychle exportuje soubory PDF do formátů souborů SVG. Knihovna Aspose PowerPoint vám umožňuje převést PDF do SVGs a mnoho dalších formátů souborů

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Převeďte PDF do SVG pomocí Javy" %}}
Chcete-li převést PDF do SVG, budete muset vytvořit prezentaci ze souboru PDF a uložit ji jako SVG.

{{% blocks/products/pf/agp/code-block title="Java kód pro převod PDF do SVG" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    pres.getSlides().addFromPdf("InputPDF.pdf");
    for (int index = 0; index < pres.getSlides().size(); index++)
    {
        ISlide slide = pres.getSlides().get_Item(index);

        FileOutputStream fileStream = new FileOutputStream("slide-" + index + ".svg");
        try {
            slide.writeAsSvg(fileStream);
        } finally {
            fileStream.close();
        }
    }
} finally {
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Jak převést PDF do SVG pomocí Aspose.Slides for Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Toto jsou kroky k převodu PDF do SVG v Javě." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Nainstalujte [**Aspose.Slides for Java**](https://products.aspose.com/slides/cs/java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Přidejte odkaz na knihovnu (importujte knihovnu) do svého projektu Java.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Otevřete zdrojové soubory PDF v Javě.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Uložit výsledek jako soubor SVG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Převést PDF do jiných podporovaných formátů" subTitle="Můžete také převést PDF a uložit do jiných formátů souborů. Všechny podporované formáty naleznete níže" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/java/conversion/pdf-to-html/" name="PDF TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/java/conversion/pdf-to-image/" name="PDF TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/java/conversion/pdf-to-jpg/" name="PDF TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/java/conversion/pdf-to-png/" name="PDF TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/java/conversion/pdf-to-tiff/" name="PDF TO TIFF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/java/conversion/pdf-to-xml/" name="PDF TO XML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/java/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/java/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}